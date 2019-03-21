---
title: Usage - Common Data Model | Microsoft Docs
description: How to use the Common Data Model to develop apps and solutions.
author: theresapalmer
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 07/24/2018
ms.author: tpalmer
---

# How to use the Common Data Model

With the Common Data Model (CDM), you can put your data into formats that represent concepts and activities that are commonly used and well understood. That way, you can query that data, reuse it, and interoperate with other businesses and apps that use the same format. This strategy matches that of, for example, manufacturers who produce AA batteries that fit in most remote controls. The CDM defines the size and shape of a **Contact**, for example, so that your app developers and business partners can parse that data and build your apps (or interoperate) with agility and confidence. The CDM is an open-source definition of standard entities and a metadata system that enable consistency of data and its meaning across apps and business processes.

Today, the CDM is used within Common Data Service, which supports Dynamics 365, PowerApps, and the data-preparation capabilities in Power BI dataflows to create schematized files in Azure Data Lake. The CDM definitions are open and available to any service or application that wants to use them.

![Common Data Model with Common Data Service](media/cdm-with-cds.png "Common Data Model with Common Data Service")

You can use the CDM in multiple applications and platforms:

- **Bring your data together in Common Data Service**: You can use Common Data Service to bring your data together in the standardized format of the CDM and quickly create powerful apps. The data can then be managed in Microsoft apps and services such as Dynamics 365, PowerApps, Microsoft Flow, Power BI, or your own custom apps.

- **Extend CDM standard entities**: The CDM is extensible, so you can extend existing entities or create entities that are specific to your organization. These entities can relate back to the CDM standard entities so that your app can more easily leverage the full power of the platform.

- **Create your own repositories of data with Azure Data Lake Storage Gen2 (Preview)**: You can build repositories of data that adhere to the schema of the CDM, and you can connect to those data sources by using Microsoft data connectors. Then you can build custom, line-of-business apps that use or share your data in the CDM, regardless of where the data originated or resides.

- **Quickly derive and distribute insights using Power BI**: You can use advanced data-preparation services with Power BI dataflows to load data into CDM form, including templates that map into CDM standard entities. Then you can create report-generating apps that automatically pull your data from the CDM into customized insights for individuals and groups in your organization.

Microsoft continues to extend the CDM in concert with many partners and subject-matter experts so that more industries, such as healthcare, can benefit from the CDM and the platforms that support it.

## Data integration and Power Query Online

Both platforms that currently support the CDM also offer data-integration experiences through Power Query Online that allow users to bring in data from a variety of sources, transform it if necessary, and then map it to standard entities in the CDM or create custom entities. Power Query Online leverages the same visual, self-service data-prep experience as Power Query within Excel and Power BI Desktop, so existing users can ramp up quickly.

![Map data with entities in CDM](media/cdm-map-entities.png "Map data with entities in CDM")

## Common Data Service

By using Common Data Service, you can jumpstart apps using the CDM with business logic, security, and integration already built in. The platform provides these benefits:

- **Leverage packaged business applications**: Many Microsoft Dynamics solutions and third-party apps are built on top of (or at least leverage) Common Data Service. When your data is in the CDM, you can take advantage of those packaged applications.

- **Gain access to customized solutions**: Developers who understand and work with data in the CDM format have created an ecosystem of extensions and complete apps. For more information, see [Introduction to solutions](https://docs.microsoft.com/powerapps/developer/common-data-service/introduction-solutions).

Whatever your intent, the CDM puts your data into a common format so that you can use, share, and analyze it more easily.

### Resources for Common Data Service

- [What is Common Data Service?](https://docs.microsoft.com/powerapps/maker/common-data-service/data-platform-intro)
- [Add data to an entity in Common Data Service by using Power Query](https://docs.microsoft.com/powerapps/maker/common-data-service/data-platform-cds-newentity-pq)
- [Introduction to solutions](https://docs.microsoft.com/powerapps/developer/common-data-service/introduction-solutions)
- [Build a model-driven app](https://docs.microsoft.com/powerapps/maker/model-driven-apps/model-driven-app-overview)
- [Build a canvas app](https://docs.microsoft.com/powerapps/maker/canvas-apps/getting-started)
- [Create a flow that uses Common Data Service](https://docs.microsoft.com/flow/common-data-model-intro)

## Power BI Dataflows

You can use the dataflows feature of Power BI to ingest data into the CDM form from Dynamics 365, Salesforce, Azure SQL Database, Excel, SharePoint, or another source. You create and manage dataflows in app workspaces by using the Power BI service. Once you've connected and prepared your data, you can choose to map it to a CDM standard entity or load it as a custom entity in CDM form in Azure Data Lake Storage Gen2.

> [!NOTE]
> The dataflows functionality is in preview, and is subject to change and updates prior to general availability.

Similar to how spreadsheets handle recalculations for all affected formulas, dataflows manage changes for an entity or data element on your behalf, automating updates, and alleviating what used to be tedious and time-consuming logic checks for even a basic data refresh. With dataflows and a few clicks, analysts and report creators can handle tasks that once required data scientists to oversee (and many hours or days to complete).

Organizations can incorporate dataflows in these ways, among others, to suit their needs:

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

## The Common Data Model and Microsoft Azure Data Lake Storage Gen2 (Preview)

Azure Data Lake Storage Gen2 (Preview) is designed specifically for enterprises to run large-scale analytics workloads in the cloud. A wide variety of applications and services can easily access data in this format, but each consumer must understand the meaning of the data before it can provide value. The CDM simplifies this process by providing a metadata system that describes the data and standard entites to which producers can map. More information: [CDM and Azure Data Lake Storage Gen2 (Preview)](data-lake.md).

### Resources for CDM and Azure Data Lake Storage Gen2 (Preview)

- [Introduction to Azure Data Lake Storage Gen2 (Preview)](https://docs.microsoft.com/azure/storage/blobs/data-lake-storage-introduction)
- [Azure Data Services dismantle data silos and unlock insights](https://aka.ms/cdmadsblog)
- [CDM and Azure Data Services Integration (tutorial)](https://github.com/Azure-Samples/cdm-azure-data-services-integration/blob/master/Tutorial/CDM-Azure-Data-Services-Integration-Tutorial.md)
