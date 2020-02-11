---
title: Usage - Common Data Model | Microsoft Docs
description: How to use the Common Data Model to develop apps and solutions.
author: theresapalmer
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 02/11/2020
ms.author: tpalmer
---

# How to use the Common Data Model

With the Common Data Model, you can structure your data to represent concepts and activities that are commonly used and well understood. You can query that data, reuse it, and interoperate with other businesses and apps that use the same format. The Common Data Model defines the size and shape of a **Contact**, for example, so that your app developers and business partners can parse that data and build your apps (or interoperate with other people's apps) with agility and confidence.


The Common Data Model is used within Common Data Service, which supports Dynamics 365, Power Apps, and the data-preparation capabilities in Power BI dataflows to create schematized files in Azure Data Lake. The Common Data Model definitions are open and available to any service or application that wants to use them.

![Common Data Model with Common Data Service](media/cdm-with-cds.png "Common Data Model with Common Data Service and Power BI dataflows")

You can use the Common Data Model in multiple applications and platforms to:

* Perform quick data integration by using Power Query Online.
* Jump-start Common Data Service app development.
* Ingest data by using Power BI dataflows.
* Optimize data exchange in the Azure Data Lake.

Microsoft continues to extend the Common Data Model in concert with many partners and subject-matter experts so that more industries, such as healthcare, can benefit from the Common Data Model and the platforms that support it.

## Perform quick data integration by using Power Query Online


Both platforms that currently support the Common Data Model also offer data-integration experiences through Power Query Online, which lets users bring in data from a variety of sources, transform it if necessary, and then map it to standard entities in the Common Data Model or create custom entities. Power Query Online leverages the same visual, self-service data-prep experience as Power Query within Excel and Power BI Desktop, so existing users can ramp up quickly.

![Map data with entities in the Common Data Model](media/cdm-map-entities.png "Map data with entities in the Common Data Model")

## Jump-start Common Data Service app development

By using Common Data Service, you can jump-start app development by using the Common Data Model with business logic, security, and integration already built in. The platform provides these benefits:

- **Leverage packaged business applications**: Many Microsoft Dynamics 365 solutions and third-party apps are built on top of (or at least leverage) Common Data Service. When your data is structured according to the Common Data Model, you can take advantage of those packaged applications.

- **Gain access to customized solutions**: Developers who understand and work with data in the Common Data Model format have created an ecosystem of extensions and complete apps.

Whatever your intent, using the Common Data Model structures your data in a common format so that you can use, share, and analyze it more easily.

### Resources for Common Data Service

- [What is Common Data Service?](https://docs.microsoft.com/powerapps/maker/common-data-service/data-platform-intro)
- [Add data to an entity in Common Data Service by using Power Query](https://docs.microsoft.com/powerapps/maker/common-data-service/data-platform-cds-newentity-pq)
- [Introduction to solutions](https://docs.microsoft.com/powerapps/developer/common-data-service/introduction-solutions)
- [Build a model-driven app](https://docs.microsoft.com/powerapps/maker/model-driven-apps/model-driven-app-overview)
- [Build a canvas app](https://docs.microsoft.com/powerapps/maker/canvas-apps/getting-started)
- [Create a flow that uses Common Data Service](https://docs.microsoft.com/flow/common-data-model-intro)

## Ingest data by using Power BI dataflows

You can use the dataflows feature of Power BI to ingest data into the Common Data Model format from Dynamics 365, Salesforce, Azure SQL Database, Excel, SharePoint, or another source. You create and manage dataflows in app workspaces by using the Power BI service. After you've connected and prepared your data, you can choose to map it to a Common Data Model standard entity or load it as a custom entity in the Common Data Model form in Azure Data Lake Storage Gen2.

Organizations can incorporate dataflows to suit their needs in these ways:

- Customize standard entities and create their own.
- Create dataflows programmatically with custom definition files (model.json).
- Leverage powerful Azure products such as Azure Machine Learning, Azure Databricks, and Azure Data Factory.
- Add CSV data from Azure Blob storage.
- Enjoy more storage, more frequent refreshes, incremental refresh, and computed and linked entities with Power BI Premium.

### Resources for Power BI

- [Self-service data prep in Power BI](https://docs.microsoft.com/power-bi/service-dataflows-overview)
- [Creating and using dataflows in Power BI](https://docs.microsoft.com/power-bi/service-dataflows-create-use)
- [Connect to data created by Power BI dataflows in Power BI Desktop](https://docs.microsoft.com/power-bi/desktop-connect-dataflows)
- [Developer resources for Power BI dataflows](https://docs.microsoft.com/power-bi/service-dataflows-developer-resources)

## Optimize data exchange in the Azure Data Lake

[Azure Data Lake Storage Gen2](data-lake.md) is designed specifically for enterprises to run large-scale analytics workloads in the cloud. A wide variety of applications and services can easily access data in this format, but each consumer must understand the meaning of the data before it can provide value. The Common Data Model simplifies this process by providing a metadata system that describes the data and standard entities to which producers can map.

### Resources for the Common Data Model and Azure Data Lake Storage Gen2

- [Introduction to Azure Data Lake Storage Gen2](https://docs.microsoft.com/azure/storage/blobs/data-lake-storage-introduction)
- [Power BI and Azure Data Services dismantle data silos and unlock insights](https://aka.ms/cdmadsblog)
- [Common Data Model and Azure Data Services Integration (tutorial)](https://github.com/Azure-Samples/cdm-azure-data-services-integration/blob/master/Tutorial/CDM-Azure-Data-Services-Integration-Tutorial.md)
