---
title: Frequently asked questions - Common Data Model | Microsoft Docs
description: "Frequently asked questions around using the Common Data Model."
author: theresapalmer
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 11/21/2019
ms.author: tpalmer
---

# Frequently asked questions about the Common Data Model

This topic contains frequently asked questions and best practices around a variety of areas related to the Common Data Model (CDM), including general topics, Common Data Service (CDS) for Apps, and Azure Data Lake Storage Gen2 Preview. If you have more questions or comments on the Common Data Model and related topics, we recommend that you [submit an issue in Git](https://github.com/microsoft/cdm/issues).

- General
  - What is the Common Data Model?
  - How does this relate to the Open Data Initiative?
  - How does the CDM relate to other standard definitions such as schema.org?
  - What type of semantic information can be defined with the CDM?
  - How are schemas and other artifacts versioned?
  - Are there libraries to help read and write CDM metadata?

- CDS for Apps
  - How does the CDM relate to CDS for Apps?
  - How do I get all the standard entities in my instance of CDS for Apps?

- Azure Data Lake Storage Gen2 Preview
  - How to discover CDM content in the lake?
  - [How do I get started?](#how-do-i-get-started)
  - [What are the correct authorization levels for CDM folders?](#what-are-the-correct-authorization-levels-for-cdm-folders)
  - What are the expectations of a CDM data producer?
  - What are the expectations of a CDM data consumer?
  - [What is the cost implication?](#what-is-the-cost-implication)
  - How do I access CDM folders, model.json files, or data files?

- Power BI dataflows
  - How does the CDM relate to Power BI dataflows?
  - Will my dataflows be affected if there are new versions of the CDM standard entities?

## General

### What is the Common Data Model

The Common Data Model (CDM) comprises a standardized metadata system and data schemas that help applications and services interoperate and help you get more value from your data. The CDM simplifies data integration and application-development scenarios, allowing independent development while maintaining shared meaning of data.<br>[More information](index.md)

### How does this relate to the Open Data Initiative

The Open Data Initiative, announced in September 2018 at Ignite, is a vision that was jointly developed by Adobe, Microsoft, and SAP. The Common Data Model, including the CDM metadata format and standard entities, will continue to evolve and directly accrue value toward the Open Data Initiative.<br>[More information](https://aka.ms/opendatainitiative)

### How does CDM relate to other standard definitions such as schema.org

The CDM schema and standard entities are influenced by existing standards throughout a variety of industries. Many CDM standard entities originated from Dynamics 365 but, as we extended to new industries and areas, we look to public standards in that space to help define extensions to CDM. CDM standard entities are open source and available under a Creative Commons license.

### What type of semantic information can be defined with the CDM

The CDM schema definitions include a wide variety of semantic information, such as metadata related to geolocation, demographics, measurements, and calendar/dates, in addition to standard data types. You can see examples of these types within the published CDM standard entities and a full catalog of these types will be released soon.

### How are schemas and other artifacts versioned

There’s a major/minor versioning system in the standard-entity definitions, as well as the schema format itself. For the standard entities, you can find the version in the URI (Account.0.8.cdm.json) and entity definition.

### Are there libraries to help read and write CDM metadata

You can find sample libraries to read CDM schema documents in [TypeScript](https://github.com/Microsoft/CDM/tree/master/src) as well as sample libraries in [.NET](https://aka.ms/AA39f6f) and [Python](https://aka.ms/AA39n1b) to read/write model.json files. More libraries are coming soon; please add your requests/comments at the library location in the GitHub repository.

## CDS for Apps

### How does the CDM relate to CDS for Apps

CDS for Apps implements the CDM standard entities, such as Account and Contact.

### How do I get all the standard entities in my CDS for Apps database

Some standard entities in the CDM are built in to each CDS for Apps database. Other standard entities are installed as part of a solution, including first-party applications (such as Dynamics 365 Field Service) or [industry accelerators](industry-accelerators.md) (such as the Dynamics 365 Healthcare Accelerator).

## Azure Data Lake Gen2 Storage Preview

### How do I discover CDM content in the lake

Today, a CDM folder within the lake can be identified by the existence of a model.json file that conforms to the CDM model.json specification. We're working to add better discovery mechanisms so that you can more easily find and consume data and metadata in CDM folders.

### How do I get started

Start by creating an instance of Azure Data Lake Storage Gen2 Preview, with hierarchical namespaces enabled. When the instance is available, you can onboard it to a service that produces CDM folders (such as Power BI dataflows) or create your own filesystem and CDM folder format. Then provide access to a service that consumes CDM folders or your own applications.

### What are the correct authorization levels for CDM folders

In general, the best practice is to set the least required privilege to complete the action.

For data producers, this strategy means full create, read, update, and delete (CRUD) permissions to content within their filesystems. For data consumers, this strategy means read-access permissions only. When data producers provide access to their filesystems, the best practice is to create and manage groups in Azure Active Directory and set access control lists for those groups. This approach makes adding consumers easier going forward.<br>[More information](data-lake.md#authorization)

### What are the expectations of a CDM data producer

In the CDM ecosystem, data producers are expected to provide sufficient information for a data consumer to understand and parse the data files. A general principle is to make the metadata as rich as possible to simplify the experience for data consumers.

### What are the expectations of a CDM data consumer

In the CDM ecosystem, data consumers are expected to read the metadata and data as the producer described and not to modify any data that consumer didn't also produce. If a data consumer wants to extend or modify the data from another data producer, the consumer then becomes a data producer and should follow the best practices of data producers.

### What is the cost implication

Today CDM folders and data files are treated the same as any other data ([more details on pricing](https://azure.microsoft.com/pricing/details/storage/data-lake/) for Azure Data Lake Storage Gen2 Preview). Moving data between regions incurs additional charges.

### How do I access CDM folders, model json files, and data files

You can create, read, update, or delete CDM folders, model.json files, and data files through APIs and SDKs for Azure Data Lake Storage Gen2 Preview.<br>[More information](https://docs.microsoft.com/rest/api/storageservices/data-lake-storage-gen2
)

## Power BI dataflows

### How does the CDM relate to Power BI dataflows

Power BI dataflows is both a data producer and data consumer of the CDM. Power BI dataflows can write data in CDM folders in Azure Data Lake Storage Gen2 Preview and read data in CDM folder format. Power BI dataflows also offers an experience to [map your data to CDM standard entities](https://docs.microsoft.com/power-bi/service-dataflows-create-use#dataflows-and-the-common-data-model-cdm) through the mapping transformation in Power Query Online.

### Will my dataflows be affected if the CDM standard entities are revised

When entities in a dataflow are mapped to a CDM standard entity, such as Account, the version of the standard entity is included in the dataflow definition (model.json). Existing versions of the CDM standard entities will persist unchanged, so existing dataflows aren't affected. If you'd like to leverage new versions of the CDM standard entities, you can edit existing dataflows, but your changes might affect reports and dashboards that use the dataflow.

## More questions

If you have more questions or comments on the CDM and related topics, we recommend that you [submit an issue in Git](https://github.com/microsoft/cdm/issues).
