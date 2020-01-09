---
title: Frequently asked questions - Common Data Model | Microsoft Docs
description: "Frequently asked questions around using the Common Data Model."
author: theresapalmer
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 11/21/2018
ms.author: tpalmer
---

# Frequently asked questions about the Common Data Model

This topic contains frequently asked questions and best practices around a variety of areas related to the Common Data Model, including general topics, Common Data Service, and Azure Data Lake Storage Gen2. If you have more questions or comments on the Common Data Model and related topics, we recommend that you [submit an issue in Git](https://github.com/microsoft/cdm/issues).

- General
  - [What is the Common Data Model?](#what-is-the-common-data-model)
  - [How does the Common Data Model relate to the Open Data Initiative?](#how-does-the-common-data-model-relate-to-the-open-data-initiative)
  - [How does the Common Data Model relate to other standard definitions?](#how-does-the-common-data-model-relate-to-other-standard-definitions)
  - [What type of semantic information can be defined with the CDM?](#what-type-of-semantic-information-can-be-defined-with-the-common-data-model)
  - [How are schemas and other artifacts versioned?](#how-are-schemas-and-other-artifacts-versioned)
  - [Where can I find libraries to help read and write Common Data Model metadata?](#where-can-i-find-libraries-to-help-read-and-write-common-data-model-metadata)

- Common Data Service
  - [How does the Common Data Model relate to Common Data Service?](#how-does-the-common-data-model-relate-to-common-data-service)
  - [How do I get all the standard entities in my Common Data Service database?](#how-do-i-get-all-the-standard-entities-in-my-common-data-service-database)

- Azure Data Lake Storage Gen2
  - [How do I discover Common Data Model content in the lake?](#how-do-i-discover-common-data-model-content-in-the-lake)
  - [How do I get started?](#how-do-i-get-started)
  - [What are the correct authorization levels for Common Data Model folders?](#what-are-the-correct-authorization-levels-for-common-data-model-folders)
  - [What are the expectations of a Common Data Model data producer?](#what-are-the-expectations-of-a-common-data-model-data-producer)
  - [What are the expectations of a Common Data Model data consumer?](#what-are-the-expectations-of-a-common-data-model-data-consumer)
  - [What is the cost implication?](#what-is-the-cost-implication)
  - [How do I access Common Data Model folders, model.json files, or data files?](#how-do-i-access-common-data-model-artifacts)

- Power BI dataflows
  - [How does the Common Data Model relate to Power BI dataflows?](#how-does-the-common-data-model-relate-to-power-bi-dataflows)
  - [Will my dataflows be affected if the Common Data Model standard entities are revised?](#will-my-dataflows-be-affected-if-the-common-data-model-standard-entities-are-revised)

## General

### What is the Common Data Model

The Common Data Model comprises a standardized metadata system and data schemas that help applications and services interoperate and help you get more value from your data. The Common Data Model simplifies data integration and application-development scenarios, allowing independent development while maintaining shared meaning of data.<br>[More information](index.md)

### How does the Common Data Model relate to the Open Data Initiative

The Open Data Initiative, announced in September 2018 at Ignite, is a vision that was jointly developed by Adobe, Microsoft, and SAP. The Common Data Model, including the Common Data Model metadata format and standard entities, will continue to evolve and directly accrue value toward the Open Data Initiative.<br>[More information](https://aka.ms/opendatainitiative)

### How does the Common Data Model relate to other standard definitions

The Common Data Model schema and standard entities are influenced by existing standards, such as schema.org, throughout a variety of industries. Many Common Data Model standard entities originated from Dynamics 365 but, as we extend to new industries and areas, we look to public standards in that space to help define extensions to the Common Data Model. Common Data Model standard entities are open source and available under a Creative Commons license.

### What type of semantic information can be defined with the Common Data Model

The Common Data Model schema definitions include a wide variety of semantic information, such as metadata related to geolocation, demographics, measurements, and calendar/dates, in addition to standard data types. You can see examples of these types within the published Common Data Model standard entities and a full catalog of these types will be released soon.

### How are schemas and other artifacts versioned

There’s a major/minor versioning system in the standard-entity definitions, as well as the schema format itself. For the standard entities, you can find the version in the URI (Account.0.8.cdm.json) and entity definition.

### Where can I find libraries to help read and write Common Data Model metadata

You can find libraries to read Common Data Model schema documents in [TypeScript](https://aka.ms/cdmsdkts) as well as sample libraries in [.NET](https://aka.ms/AA39f6f) and [Python](https://aka.ms/AA39n1b) to read/write Common Data Model metadata files. Please add your requests/comments at the library location in the GitHub repository.

## Common Data Service

### How does the Common Data Model relate to Common Data Service

Common Data Service implements the Common Data Model standard entities, such as Account and Contact.

### How do I get all the standard entities in my Common Data Service database

Some standard entities in the Common Data Model are built in to each Common Data Service database. Other standard entities are installed as part of a solution, including first-party applications (such as Dynamics 365 Field Service) or [industry accelerators](industry-accelerators.md) (such as the Dynamics 365 Healthcare Accelerator).

## Azure Data Lake Gen2 Storage

### How do I discover Common Data Model content in the lake

Today, a Common Data Model folder within the lake can be identified by the existence of a model.json file that conforms to the Common Data Model model.json specification. We're working to add better discovery mechanisms so that you can more easily find and consume data and metadata in Common Data Model folders.

### How do I get started

Start by creating an instance of Azure Data Lake Storage Gen2, with hierarchical namespaces enabled. When the instance is available, you can onboard it to a service that produces Common Data Model folders (such as Power BI dataflows) or create your own filesystem and Common Data Model folder format. Then provide access to a service that consumes Common Data Model folders or your own applications.

### What are the correct authorization levels for Common Data Model folders

In general, the best practice is to set the least required privilege to complete the action.

For data producers, this strategy means full create, read, update, and delete (CRUD) permissions to content within their filesystems. For data consumers, this strategy means read-access permissions only. When data producers provide access to their filesystems, the best practice is to create and manage groups in Azure Active Directory and set access control lists for those groups. This approach makes adding consumers easier going forward.<br>[More information](data-lake.md#authorization)

### What are the expectations of a Common Data Model data producer

In the Common Data Model ecosystem, data producers are expected to provide sufficient information for a data consumer to understand and parse the data files. A general principle is to make the metadata as rich as possible to simplify the experience for data consumers.

### What are the expectations of a Common Data Model data consumer

In the Common Data Model ecosystem, data consumers are expected to read the metadata and data as the producer described and not to modify any data that consumer didn't also produce. If a data consumer wants to extend or modify the data from another data producer, the consumer then becomes a data producer and should follow the best practices of data producers.

### What is the cost implication

Today Common Data Model folders and data files are treated the same as any other data ([more details on pricing](https://azure.microsoft.com/pricing/details/storage/data-lake/) for Azure Data Lake Storage Gen2). Moving data between regions incurs additional charges.

### How do I access Common Data Model artifacts

You can create, read, update, or delete Common Data Model folders, model.json files, and data files through APIs for Azure Data Lake Storage Gen2.<br>[More information](https://docs.microsoft.com/rest/api/storageservices/data-lake-storage-gen2)

## Power BI dataflows

### How does the Common Data Model relate to Power BI dataflows

Power BI dataflows is both a data producer and data consumer of the Common Data Model. Power BI dataflows can write data in Common Data Model folders in Azure Data Lake Storage Gen2 and read data in Common Data Model folder format. Power BI dataflows also offer an experience to [map your data to Common Data Model standard entities](https://docs.microsoft.com/power-bi/service-dataflows-create-use#dataflows-and-the-common-data-model-cdm) through the mapping transformation in Power Query Online.

### Will my dataflows be affected if the Common Data Model standard entities are revised

When entities in a dataflow are mapped to a Common Data Model standard entity, such as Account, the version of the standard entity is included in the dataflow definition (model.json). Existing versions of the Common Data Model standard entities will persist unchanged, so existing dataflows aren't affected. If you'd like to leverage new versions of the Common Data Model standard entities, you can edit existing dataflows, but your changes might affect reports and dashboards that use the dataflow.

## More questions

If you have more questions or comments on the Common Data Model and related topics, we recommend that you [submit an issue in Git](https://github.com/microsoft/cdm/issues).
