---
title: Common Data Model and Azure Data Lake Gen2 | Microsoft Docs
description: "Common Data Model provides semantic consistency to data in Azure Data Lake Gen2."
author: theresapalmer
ms.service: commondatamodel
ms.reviewer: anneta
ms.topic: article
ms.date: 11/21/2018
ms.author: tpalmer
---

# CDM & Azure Data Lake Storage Gen2

Data stored in Common Data Model form provides semantic consistency across applications and deployments. With the evolution of the CDM metadata system, CDM now brings the same structural consistency and semantic meaning to the data stored in Azure Data Lake Storage gen2 (ADLSg2) with hierarchical namespaces and folders containing schematized data in standard Common Data Model format. The standardized metadata and self-describing data in an Azure data lake to facilitate effortless metadata discovery and interop between data producers and consumers such as Power BI, Azure Data Factory, Azure Data Lake, Databricks, Azure ML and more. 

![CDM data producers and consumers in ADLSg2](media/cdm-data-lake.png)

The image above shows the wide spectrum of services and users than can contribute to and leverage data in CDM folders in the data lake. The share format helps ensure each consumer doesn’t have to “relearn” the meaning of the data landed in the lake.


## Terminology

These terms are used throughout the documentation.


|    Concepts           |    Definitions                                           |
|-----------------------|----------------------------------------------------------|
|    CDM Folder       |    A “CDM folder” is a folder in a data lake conforming to specific, well-defined and standardized metadata structures and self-describing data, to facilitates effortless metadata discovery and interop between data producers and data consumers    |
|   model.json |    A metadata file within an Azure Data Lake Gen2 folder following the CDM metadata format. The existance of this file is what indicates the folder is a "CDM Folder".   |
|    Data producer    |    A service or application that creates data in CDM folders in Azure Data Lake.  |
|    Data consumer    |    A service or application that consumes data in CDM folders in Azure Data Lake.      |

## CDM folders

A **“CDM folder”** is a folder in the data lake conforming to specific, well-defined and standardized metadata structures and self-describing data, to facilitates effortless metadata discovery and interop between data producers (e.g. Dynamics 365 business application suite) and data consumers, such as Power BI analytics, Azure data platform services (e.g. Azure Machine Learning, Azure Data Factory, Azure Databricks, etc.) and turn-key SaaS applications (Dynamics 365 AI for Sales, etc.). 

A CDM folder contains the following:
- **Model.json**  
    - The Model.json metadata description file contains semantic information about entity records / attributes and links to underlying data files. The existence of this file indicates compliance with CDM metadata format, and may include standard entities which have additional rich out-of-box semantic metadata that applications can leverage.  
- **Data files**  
    - The data files are included in the folder in well-defined structure and format (subfolders are optional, see below) and referenced in the model.json file. Currently the data files must be in .csv format, but we’re working to support additional formats.  

The following diagram shows a sample of a CDM folder created by a Power BI dataflow that contains three entities:
 
![CDM folder structure](media/cdm-folder.png)

The model.json or metadata file above would provide pointers to the entity data files throughout the CDM folder.

## Data Producers

A **data producer** is a service or application that creates data in CDM folders in Azure Data Lake. An example of such a service is Power BI dataflows. The data producer is responsible for creating the folder, the model.json file and the associated data files. By having the data producer do the work of adding the relevant metadata, each consumer can more easily leverage the data that’s produced.

Each data producer stores its data in isolation from other data producers. The storage concept used to isolate data producers from each other is an Azure Data Lake Store Gen2 filesystem.

## Folder organization

Data producers can choose how to organize the CDM folders within their own filesystem. While it is possible to create CDM folders directly under the filesystem, some services may require subfolders for disambiguation or better organization of data as it is presented in their own products. It is recommended that the folder naming and structure is meaningful for customers that access the lake directly. 

The following diagram showcases how a lake shared by data producers may be structured. Each services, Dynamics 365, Dynamics for Finance and Operation and Power BI creates and owns their own filesystem. Depending on the experience in each service, subfolders are created to better organize CDM folders within the filesystem. 

![Filesystems with CDM folders and subfolders](media/cdm-filesystems.png)

## Data Consumers

**Data consumers** are services or applications that read data in CDM folders in Azure Data Lake. A data consumer may have access to many CDM folders to read content throughout the lake. If a data consumer wants to write back data or insights it has derived from other data producers, it should follow the pattern described of data producers above and write within its own filesystem.

## Authorization 

Authorization is an important concept for both data producers and data consumers. Failure to set the right permissions for either scenario can lead to users or services having unrestricted access to all the data in the data lake.

While Azure Data Lake gen2 supports a variety of authentication schemes, **AAD bearer tokens & Access Control Lists (ACLs)** are recommended as it allows more granular scoping of permissions to resources in the lake. Full details of the available schemes are provided in the Azure Storage security guide.

### Active Directory OAuth Bearer token and POSIX ACLs

Azure AD bearer tokens are acquired and refreshed by the driver using either the identity of the end user or a configured Service Principal. Once a token is acquired, all access is authorized on a per-call basis using the identity associated with the supplied token and evaluated against the assigned POSIX ACL. This provides the authorized person or services full access to resources within the scope they were authorized to and nothing more.

#### Authorizing Data Producers

Data producers required full CRUD (create, read, update, delete) permissions their file system including the CDM folders and files they own. The identity of the data producer would be given read and write permission to the specific file share associated with the Data Producer. This allows multiple Data Producers to easily share the same Azure Data Lake store Gen2 Lake without compromising security. In addition, it allows for auditing of access to resources in the storage and authorizing individuals to access CDM folders.

#### Authorizing Data Consumers

Sharing CDM Folders with data consumers, i.e. people, services intended to read the data, is made simple with Active Directory OAuth Bearer token and POSIX ACLs. All that is required is that access is granted to a An Active Directory object of your choice to the CDM Folder. It is recommended that all access to the CDM folder any identity other than the Data Producer be granted as read only. This protects the integrity of the data the producer generates and provides Administrators with the ability to monitor who accessed the CDM folder via audit logs. 

### Alternative forms of authorization

One of the most common types is Storage Account Key or Shared Key authorization. This permits holders of the key to access to ALL resources in the account. Provides the holder of the key full access to all resources in the lake. While this is the simplest path, its less favorable because it limits the ability to share specific resources in the lake and does not provide customers with any auditing of who accessed the storage. Full details of the available schemes are provided in the [Azure Storage security guide](https://docs.microsoft.com/azure/storage/common/storage-security-guide).
