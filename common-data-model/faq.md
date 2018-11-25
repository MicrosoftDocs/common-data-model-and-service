---
title: Frequently Asked Questions | Microsoft Docs
description: "Frequently asked questions around using the Common Data Model."
author: theresapalmer
ms.service: commondatamodel
ms.reviewer: anneta
ms.topic: article
ms.date: 11/21/2019
ms.author: tpalmer
---

#  Frequently Asked Questions

The following contains frequently asked questions and best practices around a variety of areas related to the Common Data Model, including general topics, Common Data Service, Azure Data Lake Gen2, and more. If you have additional questions or comments on the Common Data Model and related topics, please use the "feedback" option at the bottom or top of the page.


**CDM General**  
- [What is the Common Data Model?](#what-is-the-common-data-model)
- [How does this relate to the Open Data Initiative?](#how-does-this-relate-to-the-open-data-initiative)
- [How does CDM relate to other standard definitions like schema.org?](#how-does-cdm-relate-to-other-standard-definitions-like-schema.org)
- [What type of semantic information can be defined with CDM?](#what-type-of-semantic-information-can-be-defined-with-cdm)
- [How are schemas and other artifacts versioned?](#how-are-schemas-and-other-artifacts-versioned)
- [Are there libraries to help read and write CDM metadata?](#are-there-libraries-to-help-read-and-write-cdm-metadata)


**CDM & Common Data Service**  
- [How does CDM relate to the Common Data Service?](#how-does-cdm-relate-to-the-common-data-service)
- [How do I get all the standard entities in my CDS instance?](#how-do-i-get-all-the-standard-entities-in-my-cds-instance)


**CDM in Azure Data Lake Gen2**  
- [How to discover CDM content in the lake?](#how-to-discover-cdm-content-in-the-lake)
- [How do I get started with CDM folders and ADLSg2?](#how-do-i-get-started-with-cdm-folders-and-adlsg2)
- [What are the correct authorization levels for CDM folders in ADLSg2?](#what-are-the-correct-authorization-levels-for-cdm-folders-in-adlsg2)
- [What are the expectations of a CDM data producer?](#what-are-the-expectations-of-a-cdm-data-producer)
- [What are the expectations of a CDM data consumer?](#what-are-the-expectations-of-a-cdm-data-consumer)
- [What is the cost implication of using CDM folders and Azure Data Lake Gen2?](#what-is-the-cost-implication-of-using-cdm-folders-and-azure-data-lake-gen2)
- [How do I access CDM folders, model json files or data files?](#how-do-i-access-cdm-folders-model-json-files-or-data-files)


**CDM in Power BI dataflows**  
- [How does CDM relate to Power BI dataflows?](#how-does-cdm-relate-to-power-bi-dataflows)
- [Will my dataflows be affected if there are new versions of the CDM standard entities?](#will-my-dataflows-be-affected-if-there-are-new-versions-of-the-cdm-standard-entities)


## CDM General

### What is the Common Data Model?
The Common Data Model (CDM) is a standardized metadata system and data schemas that helps applications and services interoperate and get more value from your data. The CDM simplifies data integration and application development scenarios, allowing independent development while maintaining shared meaning of data.

More details [here](index.md)

### How does this relate to the Open Data Initiative?
The Open Data Initiative, announced at Ignite 2018 in September, a jointly-developed vision by Adobe, Microsoft, and SAP. The Common Data Model, including the CDM metadata format, standard entities, and more, will continue to evolve and directly accrue value towards ODI. You can find the latest information at https://aka.ms/opendatainitiative 

### How does CDM relate to other standard definitions like schema.org?
The Common Data Model schema and standard entities are influenced by existing standards throughout a variety of industries. Many CDM standard entities originated from Dynamics 365 but as we extended to new industries and areas we look to public standards in that space to help define extensions to CDM. CDM standard entities are open sourced available under the Creative Commons  License.

### What type of semantic information can be defined with CDM?
The CDM schema definitions include a wide variety of semantic information, such as metadata related to geolocation, demographics, measurements, calendar/dates, and more, in addition to standard data types. You can see examples of these types within the published CDM standard entities and a full catalog of these types will be released soon.

### How are schemas and other artifacts versioned?
Currently there’s a major/minor versioning system in the standard entity definitions as well as the schema format itself. For the standard entities, you can find the version in the URI (Account.0.8.cdm.json) and entity definition. 

### Are there libraries to help read and write CDM metadata?
Yes there are currently sample libraries available to read CDM schema documents in [TypeScript](https://github.com/Microsoft/CDM/tree/master/src) as well as sample libraries in [.NET](https://aka.ms/AA39f6f) and [Python](https://aka.ms/AA39n1b) to read/write model.json files. More libraries are coming soon, please add your requests/comments at the library location in the GitHub repo.

## CDM & Common Data Service

### How does CDM relate to the Common Data Service?
The Common Data Service (CDS) implements the CDM standard entities, such as Account, Contact etc.  

### How do I get all the standard entities in my CDS instance?
Some of the standard entities defined in CDM come out of the box with a CDS instance. Other standard entities are installed as part of a solution, including 1st party applications like Dynamics 365 Field Service or [industry accelerators](industry-accelerators.md) like the Dynamics 365 Healthcare Accelerator.  

## CDM in Azure Data Lake Gen2

### How to discover CDM content in the lake?
Today, a CDM folder within the lake can be identified by the existing of a model.json file that conforms to the CDM model.json specification. We are actively working with the ADLS team to add better discovery mechanisms to make it easier to find and consume data and metadata in CDM folders.

### How do I get started with CDM folders and ADLSg2?
Start by creating an Azure Data Lake Gen2 instance, with hierarchical namespaces enabled. Once the instance is available you can onboard it to a service that produces CDM folders, such as Power BI dataflows, or start by creating your own filesystem and CDM folder format then providing access to a service that consumers CDM folders or your own applications.

### What are the correct authorization levels for CDM folders in ADLSg2?
In general the best practice is to set the least required privilege to complete the action. 

For data producers, this means full CRUD to content within their filesystem. For data consumers, this means read access only. When data producers are providing access to their filesystem, best practice is to create groups and set ACLs for the group, then manage membership through AAD. This will make it easier to add consumers going forward. 

More details [here](data-lake.md/#Authorization)

### What are the expectations of a CDM data producer?
In the CDM ecosystem, the expectation is that the data producer provides sufficient information for a data consumer to understand and parse the data files. A general principle is to make the metadata as rich as possible to simplify the experience for data consumers. 

### What are the expectations of a CDM data consumer?
In the CDM ecosystem, the expectation is that a data consumer reads the metadata and data as the producer described and it does not modify any data it didn't also produce. If a data consumer wants to extend or modify the data from another data producer, it then becomes a data producer and should follow data producer best practices.

### What is the cost implication of using CDM folders and Azure Data Lake Gen2?
Today CDM folders and data files are treated as any other data. More details on Azure Data Lake Gen2 pricing [here](https://azure.microsoft.com/pricing/details/storage/data-lake/). Note that there are additional charges for cross-region data movement so you may 

### How do I access CDM folders, model json files or data files?
CDM folders, model.json files or data files can be created, read, updated or deleted  through Azure Data Lake Gen2 APIs and SDKs. More details [here](https://docs.microsoft.com/rest/api/storageservices/data-lake-storage-gen2
)

## CDM in Power BI dataflows

### How does CDM relate to Power BI dataflows?
Power BI dataflows is a CDM data producer and data consumer as it writes data in CDM folders in Azure Data Lake gen2 and is able to read data in CDM folder format. Power BI dataflows also offers an experience to [map your data to CDM standard entities](https://docs.microsoft.com/power-bi/service-dataflows-create-use#dataflows-and-the-common-data-model-cdm) through the mapping transformation in Power Query online.

### Will my dataflows be affected if there are new versions of the CDM standard entities?
When entities in a dataflow are mapped to a CDM standard entity, such as Account, the version of the standard entity is included in the dataflow definition (model.json). When standard entities. Existing versions of the CDM standard entities will continue to live on and will not change, so existing dataflows are not affected. If you'd like to leverage new versions of the CDM standard entities you can edit existing dataflows, although that may affect downstream reports and dashboards that use the dataflow.

## More questions?

If you have additional questions or comments on the Common Data Model and related topics, please use the "feedback" option below or at the top of your page.