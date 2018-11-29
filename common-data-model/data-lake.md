---
title: Microsoft Azure Data Lake Storage Gen2 - Common Data Model | Microsoft Docs
description: "The Common Data Model provides semantic consistency to data in Microsoft Azure Data Lake Storage Gen2."
author: theresapalmer
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 11/21/2018
ms.author: tpalmer
---

# The Common Data Model and Microsoft Azure Data Lake Storage Gen2

Data stored in the Common Data Model (CDM) format provides semantic consistency across apps and deployments. With the evolution of the CDM metadata system, the CDM brings the same structural consistency and semantic meaning to the data stored in Azure Data Lake Storage Gen2 with hierarchical namespaces and folders containing schematized data in standard CDM format. The standardized metadata and self-describing data in an Azure data lake facilitates effortless metadata discovery and interoperability between data producers and consumers such as Power BI, Azure Data Factory, Azure Data Lake, Databricks, and Azure ML.

![CDM data producers and consumers in ADLSg2](media/cdm-data-lake.png)

The previous graphic shows the wide spectrum of services and users that can contribute to and leverage data in CDM folders in the data lake. The share format helps ensure each consumer doesn’t have to “relearn” the meaning of the data landed in the lake.

## Terminology

These terms are used throughout the documentation.

|    Concept           |    Definition                                           |
|-----------------------|----------------------------------------------------------|
|    CDM folder       |    A folder in a data lake that conforms to specific, well-defined, and standardized metadata structures and self-describing data. These folders facilitate effortless metadata discovery and interoperability between data producers and data consumers.    |
|   model.json |    A metadata file within an Azure Data Lake Storage Gen2 folder that follows the CDM metadata format. If this file exists in such a folder, it's a CDM folder.   |
|    Data producer    |    A service or app that creates data in CDM folders in Azure Data Lake Storage Gen2.  |
|    Data consumer    |    A service or app that consumes data in CDM folders in Azure Data Lake Storage Gen2.      |

## CDM folders

Each CDM folder contains these elements:

- Model.json

    The Model.json metadata description file contains semantic information about entity records/attributes and links to underlying data files. The existence of this file indicates compliance with the CDM metadata format and may include standard entities that provide more built-in, rich semantic metadata that apps can leverage.

- Data files

    The data files in a CDM folder have a well-defined structure and format (subfolders are optional, as this topic describes later) and are referenced in the model.json file. These files must be in .csv format, but we’re working to support other formats.

This diagram shows a sample of a CDM folder that a Power BI dataflow created and that contains three entities:

![CDM folder structure](media/cdm-folder.png)

The model.json metadata file provides pointers to the entity data files throughout the CDM folder.

## Data producers

A data producer is a service or application, such as Dynamics 365 or Power BI dataflows, that creates data in CDM folders in Azure Data LakeS Storage Gen2. The data producer is responsible for creating the folder, the model.json file, and the associated data files. Because the data producer adds the relevant metadata, each consumer can more easily leverage the data that’s produced.

Each data producer stores its data in isolation from other data producers. The storage concept that isolates data producers from each other is an Azure Data Lake Storage Gen2 filesystem.

## Folder organization

Data producers can choose how to organize the CDM folders within their own filesystem. While it's possible to create CDM folders directly under the filesystem, some services may require subfolders for disambiguation or better organization of data as it's presented in their own products. The folder naming and structure should be meaningful for customers who access the lake directly.

This diagram showcases how a lake shared that data producers share may be structured. Each service (Dynamics 365, Dynamics for Finance and Operation, and Power BI) creates and owns its own filesystem. Depending on the experience in each service, subfolders are created to better organize CDM folders in the filesystem.

![Filesystems with CDM folders and subfolders](media/cdm-filesystems.png)

## Data consumers

Data consumers are services or applications, such as Power BI analytics, that read data in CDM folders in Azure Data Lake. Other examples of data consumers include Azure data platform services (such as Azure Machine Learning, Azure Data Factory, and Azure Databricks) and turn-key SaaS applications (such as Dynamics 365 AI for Sales). A data consumer may have access to many CDM folders to read content throughout the lake. If a data consumer wants to write back data or insights it has derived from other data producers, it should follow the pattern described of data producers above and write within its own filesystem.

## Authorization

Authorization is an important concept for both data producers and data consumers. Failure to set the right permissions for either scenario can lead to users or services having unrestricted access to all the data in the data lake.

While Azure Data Lake gen2 supports a variety of authentication schemes, **AAD bearer tokens & Access Control Lists (ACLs)** are recommended as it allows more granular scoping of permissions to resources in the lake. Full details of the available schemes are provided in the Azure Storage security guide.

### Active Directory OAuth Bearer token and POSIX ACLs

Azure AD bearer tokens are acquired and refreshed by the driver using either the identity of the end user or a configured Service Principal. Once a token is acquired, all access is authorized on a per-call basis using the identity associated with the supplied token and evaluated against the assigned POSIX ACL. This provides the authorized person or services full access to resources within the scope they were authorized to and nothing more.

#### Authorizing data producers

Data producers required full CRUD (create, read, update, delete) permissions their file system including the CDM folders and files they own. The identity of the data producer would be given read and write permission to the specific file share associated with the Data Producer. This allows multiple Data Producers to easily share the same Azure Data Lake store Gen2 Lake without compromising security. In addition, it allows for auditing of access to resources in the storage and authorizing individuals to access CDM folders.

#### Authorizing data consumers

Sharing CDM Folders with data consumers, i.e. people, services intended to read the data, is made simple with Active Directory OAuth Bearer token and POSIX ACLs. All that is required is that access is granted to a An Active Directory object of your choice to the CDM Folder. It is recommended that all access to the CDM folder any identity other than the Data Producer be granted as read only. This protects the integrity of the data the producer generates and provides Administrators with the ability to monitor who accessed the CDM folder via audit logs. 

### Alternative forms of authorization

One of the most common types is Storage Account Key or Shared Key authorization. This permits holders of the key to access to ALL resources in the account. Provides the holder of the key full access to all resources in the lake. While this is the simplest path, its less favorable because it limits the ability to share specific resources in the lake and does not provide customers with any auditing of who accessed the storage. Full details of the available schemes are provided in the [Azure Storage security guide](https://docs.microsoft.com/azure/storage/common/storage-security-guide).