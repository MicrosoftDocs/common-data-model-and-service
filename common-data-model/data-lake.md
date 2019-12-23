---
title: Common Data Model and Azure Data Lake Storage Gen2
description: "The Common Data Model provides semantic consistency to data in Azure Data Lake Storage Gen2."
author: theresapalmer
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 11/21/2018
ms.author: tpalmer
---

# The Common Data Model and Azure Data Lake Storage Gen2
<!--This is a very nice topic (though it has some outdated branding in text and in the graphic named cmd-filesystems.png that needs attention). One thing that troubles me is that there's no verb in the title, so I'm not sure whether Data Lake Storage Gen2 the only data service that works with the Common Data Model, or the only one that lets people use Common Data Service, or...? I'm just not sure how it fits into the Common Data Model story.-->
Data stored in accordance with the Common Data Model provides semantic consistency across apps and deployments. With the evolution of the Common Data Model metadata system, the model brings the same structural consistency and semantic meaning to the data stored in Microsoft Azure Data Lake Storage Gen2 with hierarchical namespaces and folders that contain schematized data in standard Common Data Model format. The standardized metadata and self-describing data in an Azure data lake facilitates metadata discovery and interoperability between data producers and data consumers such as Power BI, Azure Data Factory, Azure Databricks, and Azure Machine Learning.

![Common Data Model data producers and consumers in Data Lake Storage Gen2](media/cdm-data-lake.png "Common Data Model data producers and data consumers in Data Lake Storage Gen2")

The preceding graphic shows the wide spectrum of services and users who can contribute to and leverage data in Common Data Model folders in a data lake. The format of a shared folder helps each consumer avoid having to "relearn" the meaning of the data in the lake.

## Terminology

These terms are used throughout Common Data Model documentation.

| Concept | Definition |
|--|--|
|    Common Data Model folder       |    A folder in a data lake that conforms to specific, well-defined, and standardized metadata structures and self-describing data. These folders facilitate metadata discovery and interoperability between data producers and data consumers.    |
|   model.json |    A metadata file in a folder in a Data Lake Storage Gen2 instance that follows the Common Data Model metadata format. If this file exists in such a folder, it's a Common Data Model folder.   |
|    Data producer    |    A service or app that creates data in Common Data Model folders in Data Lake Storage Gen2.  |
|    Data consumer    |    A service or app that consumes data in Common Data Model folders in Data Lake Storage Gen2.      |

## Common Data Model folders

Each Common Data Model folder contains these elements:

- The model.json file

    The model.json metadata file contains semantic information about entity records and attributes, and links to underlying data files. The existence of this file indicates compliance with the Common Data Model metadata format; the file might include standard entities that provide more built-in, rich semantic metadata that apps can leverage.

- Data files

    The data files in a Common Data Model folder have a well-defined structure and format (subfolders are optional, as this topic describes later), and are referenced in the model.json file. These files must be in .csv format, but we're working to support other formats.

The following diagram shows an example of a Common Data Model folder created by a Power BI dataflow. The folder contains three entities.

![Common Data Model folder structure](media/cdm-folder.png "Common Data Model folder structure")

The model.json metadata file provides pointers to the entity data files throughout the Common Data Model folder.

## Data producers

A data producer is a service or application, such as Dynamics 365 or Power BI dataflows, that creates data in Common Data Model folders in Data Lake Storage Gen2. The data producer is responsible for creating the folder, the model.json file, and the associated data files. Because the data producer adds relevant metadata, each consumer can more easily leverage the data that's produced.

Each data producer stores its data in isolation from other data producers. The storage concept that isolates data producers from each other is a Data Lake Storage Gen2 file system.

## Folder organization

<!--Please check edit to "directly under the file system."-->
Data producers can choose how to organize the Common Data Model folders within their own file system. You can create Common Data Model folders directly under the file system level, but for some services you might want to use subfolders for disambiguation or to better organize data as it's presented in your own product. The folder naming and structure should be meaningful for customers who access the data lake directly.

The following diagram shows how a data lake that data producers share can be structured. Each service (Dynamics 365, Dynamics 365 Finance, and Power BI) creates and owns its own file system. Depending on the experience in each service, subfolders might be created to better organize Common Data Model folders in the file system.

<!--I changed "Dynamics for Finance and Operations" to the new name, "Dynamics 365 Finance" in the graphic I overwrote this one with. I think it would be better to have a specific product instead of "Dynamics 365" in this graphic, but I don't think it's absolutely wrong to have it.-->
![File systems with Common Data Model folders and subfolders](media/cdm-filesystems.png "File systems with Common Data Model folders and subfolders")

## Data consumers

Data consumers are services or applications, such as Power BI, that read data in Common Data Model folders in Data Lake Storage Gen2. Other data consumers include Azure data-platform services (such as Azure Machine Learning, Azure Data Factory, and Azure Databricks) and turnkey software as a service (SaaS) applications (such as Dynamics 365 Sales Insights). A data consumer might have access to many Common Data Model folders to read content throughout the data lake. If a data consumer wants to write back data or insights that it has derived from a data producer, the data consumer should follow the pattern described for data producers above and write within its own file system.

## Authorization

Authorization is an important concept for both data producers and data consumers. Failure to set the right permissions for either scenario can lead to users' or services' having unrestricted access to all the data in the data lake.

Data Lake Storage Gen2 supports a variety of authentication schemes, but we recommend you use Azure Active Directory (Azure AD) Bearer tokens and access control lists (ACLs) because they give you more granularity in scoping permissions to resources in the lake. Full details about the available schemes are provided in [Security recommendations for Blob storage](https://docs.microsoft.com/azure/storage/common/storage-security-guide).

### Azure AD OAuth Bearer tokens and POSIX ACLs

The driver acquires and refreshes Azure AD bearer tokens by using either the identity of the end user or a configured Service Principal. After a token is acquired, all access is authorized on a per-call basis by using the identity that's associated with the supplied token and evaluated against the assigned portable operating system interface (POSIX) ACL. This evaluation provides the authorized person or services full access to resources only within the scope for which they're authorized.

#### Authorizing data producers

Data producers require full create, read, update, and delete (CRUD) permissions to their file system, including the Common Data Model folders and files that they own. The identity of the data producer is given read and write permission to the specific file share that's associated with the data producer. This allows multiple data producers to easily share the same data lake without compromising security. In addition, it allows access to resources in the storage to be audited and individuals to be authorized to access Common Data Model folders.

#### Authorizing data consumers

Sharing Common Data Model folders with data consumers (that is, people and services who are meant to read the data) is simplified by using Azure AD OAuth Bearer tokens and POSIX ACLs. The only requirement is that you grant access to the Azure AD object of your choice to the Common Data Model folder. You should grant read-only access to any identity other than the data producer. This approach protects the integrity of the data that the producer generates and allows administrators to use audit logs to monitor who accesses the Common Data Model folder.

### Alternative forms of authorization

Storage Account Key or Shared Key authorization schemes are commonly used; these forms permit holders of the key to access all resources in the account. This path is the simplest, but limits your ability to share specific resources in the lake and doesn't allow administrators to audit who accessed the storage. [Security recommendations for Blob storage](https://docs.microsoft.com/azure/storage/common/storage-security-guide) provides full details about the available schemes.
