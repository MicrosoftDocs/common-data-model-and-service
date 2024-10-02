---
title: Frequently asked questions - Common Data Model
description: "Frequently asked questions about using Common Data Model."
author: theresapalmer

ms.reviewer: v-iap
ms.topic: reference 
ms.date: 02/11/2020
ms.author: matgos
---

# Frequently asked questions about Common Data Model

This topic contains answers to frequently asked questions and best practices around a variety of areas related to the Common Data Model, including Microsoft Dataverse and Microsoft Azure [data lake](./data-lake.md) Storage Gen2. If you have more questions or comments about the Common Data Model and related topics, we recommend that you [submit an issue in GitHub](https://github.com/microsoft/cdm/issues).


- General
  - [What is Common Data Model?](#what-is-common-data-model)
  - [How is Common Data Model related to the Open Data Initiative?](#how-is-common-data-model-related-to-the-open-data-initiative)
  - [How is Common Data Model related to other standard definitions?](#how-is-common-data-model-related-to-other-standard-definitions)
  - [What type of semantic information can be defined with Common Data Model?](#what-type-of-semantic-information-can-be-defined-with-common-data-model)
  - [How are schemas and other artifacts versioned?](#how-are-schemas-and-other-artifacts-versioned)
  - [Where can I find libraries to help read and write Common Data Model metadata?](#where-can-i-find-libraries-to-help-read-and-write-common-data-model-metadata)

- Microsoft Dataverse
  - [How is Common Data Model related to Dataverse?](#how-is-common-data-model-related-to-dataverse)
  - [How do I get all the standard entities in my Dataverse database?](#how-do-i-get-all-the-standard-entities-in-my-dataverse-database)

- Azure data lake Storage Gen2
  - [How do I discover Common Data Model content in the data lake?](#how-do-i-discover-common-data-model-content-in-the-data-lake)
  - [How do I get started?](#how-do-i-get-started)
  - [What are the correct authorization levels for Common Data Model folders?](#what-are-the-correct-authorization-levels-for-common-data-model-folders)
  - [What are the expectations of a Common Data Model data producer?](#what-are-the-expectations-of-a-common-data-model-data-producer)
  - [What are the expectations of a Common Data Model data consumer?](#what-are-the-expectations-of-a-common-data-model-data-consumer)
  - [What is the cost implication?](#whats-the-cost-implication)
  - [How do I access Common Data Model folders, model.json files, or data files?](#how-do-i-access-common-data-model-artifacts)

- Power BI dataflows
  - [How is the Common Data Model related to Power BI dataflows?](#how-is-the-common-data-model-related-to-power-bi-dataflows)
  - [Will my dataflows be affected if the Common Data Model standard entities are revised?](#will-my-dataflows-be-affected-if-the-common-data-model-standard-entities-are-revised)

## General

### What is Common Data Model?

The Common Data Model comprises of Microsoft application and analytical data schemas which have a standardized metadata system that help applications and services interoperate so that you get more value from your data. The Common Data Model simplifies data integration and application-development scenarios, allowing applications to be developed independently while they still maintain shared meaning of data.<br>More information: [The Common Data Model](index.md)


### How is Common Data Model related to the Open Data Initiative?

The Open Data Initiative, announced in September 2018 at Microsoft Ignite, is a vision that was jointly developed by Adobe, Microsoft, and SAP. The Common Data Model, including the Common Data Model metadata format and standard [entities](./sdk/logical-definitions.md#entities-and-their-attributes), will continue to evolve and directly accrue value toward the Open Data Initiative.<br>More information: [The Open Data Initiative](https://aka.ms/opendatainitiative) website


### How is Common Data Model related to other standard definitions?

The Common Data Model schema and standard [entities](./sdk/logical-definitions.md#entities-and-their-attributes) are influenced by existing standards, such as schema.org, throughout a variety of industries. Many Common Data Model [standard entities](./schema/core/overview.md) originated from Dynamics 365 but, as we extend to new industries and areas, we look to public standards in that space to help define extensions to the Common Data Model. Common Data Model [standard entities](./schema/core/overview.md) are open source and available under a Creative Commons license on [GitHub](https://aka.ms/cdmrepo).


### What type of semantic information can be defined with Common Data Model?

The Common Data Model schema [definitions](./sdk/logical-definitions.md#definition-documents) include a wide variety of semantic information, such as metadata related to geolocation, demographics, measurements, and calendar/dates, in addition to standard data types. You can see examples of these types within the published Common Data Model [standard entities](./schema/core/applicationcommon/overview.md).

### How are schemas and other artifacts versioned?

The standard entity [definitions](./sdk/logical-definitions.md#definition-documents), and the schema format itself, use a major/minor versioning system. Learn more about [versions](https://github.com/microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon) for [standard entities](./schema/core/overview.md).

### Where can I find libraries to help read and write Common Data Model metadata?

You can find sample libraries to read and write Common Data Model schema documents in [.NET](https://aka.ms/AA39f6f), [Java](https://github.com/microsoft/CDM/tree/master/objectModel/Java), [Python](https://aka.ms/AA39n1b), and [TypeScript](https://github.com/microsoft/CDM/tree/master/objectModel/TypeScript).


## Dataverse


### How is Common Data Model related to Dataverse?

Dataverse implements the Common Data Model [standard entities](./schema/core/overview.md), such as [Account](./schema/core/applicationcommon/account.md) and [Contact](./schema/core/applicationcommon/contact.md).

### How do I get all the standard entities in my Dataverse database?

Some [standard entities](./schema/core/overview.md) in the Common Data Model are built in to each Dataverse database. Other [standard entities](./schema/core/overview.md) are installed as part of a solution, including first-party applications (such as Dynamics 365 Field Service) or [industry solution accelerators](/dynamics365/industry/accelerators/overview) (such as the [Dynamics 365 Automotive Accelerator](/dynamics365/industry/accelerators/automotive)).

## Azure Data Lake gen2 Storage

### How do I discover Common Data Model content in the data lake?

Today, you can identify which is a Common Data Model folder in the [data lake](./data-lake.md) by whether the folder includes a [model.json](./sdk/from-modeljson-to-the-future.md#using-the-common-data-model-sdk-with-modeljson-files)
 file that conforms to the Common Data Model [model.json](./sdk/from-modeljson-to-the-future.md#using-the-common-data-model-sdk-with-modeljson-files) specification. We're working to add better discovery mechanisms, so that you can more easily find and consume data and metadata in Common Data Model folders.

### How do I get started?

Start by creating an instance of [data lake](./data-lake.md) Storage Gen2 that has hierarchical namespaces enabled. When the instance is available, you can onboard it to a service that produces Common Data Model folders (such as Power BI dataflows) or create your own file system and Common Data Model folder format. Then, you provide access to a service &mdash;or your own application&mdash;that consumes Common Data Model folders.

### What are the correct authorization levels for Common Data Model folders?

In general, the best practice is to set the least required privilege to complete the action. For data producers, this strategy gives full create, read, update, and delete (CRUD) permissions to content within their file systems. For data consumers, this strategy gives read-access permissions only. When data producers provide access to their file systems, the best practice is to create and manage groups in Azure Active Directory and set access control lists for those groups. This approach makes adding consumers easier going forward.<br>More information: [Authorization for Common Data Model folders](data-lake.md#authorization)

### What are the expectations of a Common Data Model data producer?

In the Common Data Model ecosystem, data producers are expected to provide sufficient information for a data consumer to understand and parse the data files. A general principle is to make the metadata as rich as possible to simplify the experience for data consumers.

### What are the expectations of a Common Data Model data consumer?

In the Common Data Model ecosystem, data consumers are expected to read the metadata and data as the producer described them, and not modify any data that the consumer didn't also produce. If a data consumer wants to extend or modify the data from another data producer, the consumer then becomes a data producer and should follow the best practices of data producers.

### What's the cost implication?

Today, Common Data Model folders and data files are treated the same as any other data. Moving data between regions incurs additional charges. <br>More information: [Azure Data Lake Storage Gen 2 pricing](https://azure.microsoft.com/pricing/details/storage/data-lake/)

### How do I access Common Data Model artifacts?

You can create, read, update, or delete Common Data Model folders, [model.json](./sdk/from-modeljson-to-the-future.md#using-the-common-data-model-sdk-with-modeljson-files) files, and data files by using APIs for Azure data lake Storage Gen2.<br>More information: [Azure data lake Store REST API](/rest/api/storageservices/data-lake-storage-gen2)

## Power BI dataflows


### How is the Common Data Model related to Power BI dataflows?

Power BI dataflows are both a data producer and data consumer of the Common Data Model. Power BI dataflows can write data in Common Data Model folders in [data lake](./data-lake.md) Storage Gen2 and read data in Common Data Model folder format. Power BI dataflows also offer an experience to [map your data to Common Data Model standard entities](/power-bi/service-dataflows-create-use#dataflows-and-the-common-data-model-cdm) through the mapping transformation in Power Query Online.


### Will my dataflows be affected if the Common Data Model standard entities are revised?

When entities in a dataflow are mapped to a Common Data Model standard entity, such as Account, the version of that standard entity is included in the dataflow definition ([model.json](./sdk/from-modeljson-to-the-future.md#using-the-common-data-model-sdk-with-modeljson-files)). Existing versions of the Common Data Model [standard entities](https://github.com/microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon) will persist unchanged, so existing dataflows won't be affected. If you'd like to leverage new versions of the Common Data Model [standard entities](https://github.com/microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon), you can edit existing dataflows, but your changes might affect reports and dashboards that use the dataflow.

## More questions?

If you have more questions or comments about Common Data Model or related topics, please [submit an issue in GitHub](https://github.com/microsoft/cdm/issues).
