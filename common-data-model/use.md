---
title: About - Common Data Model | Microsoft Docs
description: Learn about Common Data Model.
author: theresapalmer
ms.service: common-data-model
ms.reviewer: v-iap
ms.topic: article
ms.date: 07/07/2020
ms.author: olegov
---

# About Common Data Model

Common Data Model is built upon a rich and extensible metadata definition system
that enables you to describe and share your own semantically enhanced data types
and structured tags, capturing valuable business insight which can be integrated
and enriched with heterogeneous data to deliver actionable intelligence.

With Common Data Model, you can structure your data to represent concepts and
activities that are commonly used and well understood. You can query and analyze
that data, reuse it, and interoperate with other businesses and apps that use
the same format. Common data model can be used to define thousands of entities
such as Customer, Product, Opportunity, Sale, Purchase Order, etc. as well as
identifying data for regulatory and compliance purposes. Discover and explore
up-to-date [Common Data Model Entity Reference](./schema/core/overview.md)


[Learn
more](./sdk/logical-definitions.md#glossary-of-definable-objects)
about Common Data Model definable objects.

Microsoft provided Common Data Model reference entities are categorized into
subject areas for easy discoverability and published to public GitHub repo with
supporting documentation. These entities have matured over tens of years with
thousands of hours of investment from within Microsoft as well as the partner
eco-system. 

As opposed to building a new data model for your app, you can simply
re-use the entity definitions available to you. Common Data Model can be used by
various applications and services including Microsoft Dataverse, Dynamics 365,
Microsoft Power Platform, and Azure ensuring that all of your services can access the same
data. Common Data Model is already available to many customers a great example
of how Common Data Model can be leveraged is with the data-preparation
capabilities in Power BI dataflows that creates data files which follow the
Common Data Model definition, which is stored in Azure Data Lake. The Common
Data Model definitions are open and available to any service or application that wants to use them.

![Common Data Model with Dataverse.](media/cdm-with-cds.png)

Data described using Common Data Model can be used with Azure services to build
scalable analytical solutions as well as being a
[source](/dynamics365/ai/customer-insights/connect-common-data-model-folder)
of semantically rich data for applications driving actionable insights like
Dynamics 365 Customer Insights. that reason over data using machine-readable
semantic metadata. Common Data Model is used to define entities for Dynamics 365
applications in Sales, Finance, Supply Chain and Commerce can be readily
available in Azure Data Lake.

Microsoft continues to extend the Common Data Model in collaboration with many
partners and subject-matter experts so that more industries, building [Industry
Accelerators](/dynamics365/industry/accelerators/overview)
such as
[Automotive](/dynamics365/industry/accelerators/automotive),
[Banking](/dynamics365/industry/accelerators/banking),
[Healthcare](/dynamics365/industry/accelerators/healthcare),
[Higher
Education](/dynamics365/industry/accelerators/hied),
[Not for
profit](/dynamics365/industry/accelerators/NFP) can
benefit from the Common Data Model and the platforms that support it.

Let’s explore some of the scenarios in detail

-   Jump-start app development with Power Apps and Dataverse

-   Export data from Dataverse into Azure Data Lake.

-   Export data from Dynamics 365 Finance and Operations into Azure Data Lake

-   Perform quick data integration using Power Query Online.

-   Ingest data from other systems into Azure Data Lake using Power BI
    dataflows.

-   Optimize data exchange in the Azure Data Lake.

## Jump-start Dataverse app development

By using [Dataverse](/powerapps/maker/common-data-service/data-platform-intro), you can jump-start app development by using the
Common Data Model with business logic, security, and integration already built-
in. The platform provides these benefits:

-   **Leverage packaged business applications**: Many Microsoft Dynamics 365
    solutions and third-party apps are built on top of (or at least leverage)
    Dataverse. When your data is structured according to the Common
    Data Model, you can take advantage of those packaged applications.

-   **Gain access to customized solutions**: Developers who understand and work
    with data in the Common Data Model format have created an ecosystem of
    extensions and complete apps.

Whatever your intent, using the Common Data Model structures your data in a
common format so that you can use, share, and analyze it more easily.

## Resources for Dataverse

-   [What is Dataverse?](/powerapps/maker/common-data-service/data-platform-intro)

-   [Add data to an entity in Dataverse by using Power
    Query](/powerapps/maker/common-data-service/data-platform-cds-newentity-pq)

-   [Introduction to
    solutions](/powerapps/developer/common-data-service/introduction-solutions)

-   [Build a model-driven
    app](/powerapps/maker/model-driven-apps/model-driven-app-overview)

-   [Build a canvas
    app](/powerapps/maker/canvas-apps/getting-started)

-   [Create a flow that uses Dataverse](/flow/common-data-model-intro)

-   [Exporting Dataverse data to Azure Data
    Lake](/powerapps/maker/common-data-service/export-to-data-lake)

## Export data from Dataverse into Azure Data 
-------------------------------------------------------------------------

-   Simple and intuitive interface to enable and administer replicated entities.

-   Ability to link/unlink the Dataverse environment to a data lake in
    customer’s Azure subscription.

-   Continuous replication of entities to Azure data lake.

-   Support for initial and incremental writes for data and metadata.

-   Support for replicating standard and custom entities.

-   Support for replicating create, update and delete operations.

-   Continuous snapshot updates for large analytics scenarios.

>   Learn more: [Exporting Dataverse data to Azure Data
>   Lake](/powerapps/maker/common-data-service/export-to-data-lake)

## Export data from Dynamics 365 Finance and Operations into Azure Data 

You can configure your Dynamics 365 Finance and Operations environment with an
Azure Data Lake in your own subscription. After the configuration is completed,
your data lake will reflect tables and entities from Finance and Operations
apps.

See more details here:

-   Overview of Azure Data Lake integration in Dynamics 365 for Finance and
    Operations

    <https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/data-entities/azure-data-lake-overview>

-   Configuring an Azure Data Lake in Finance and Operations

    <https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/data-entities/finance-data-azure-data-lake>

## Perform quick data integration by using Power Query Online

Power Platform and Power BI offer data-integration experiences through Power
Query Online, allowing users to bring in data from a variety of sources,
transform it if necessary, and then map it to standard entities in the Common
Data Model or create custom entities. Power Query Online leverages the same
visual, self-service data preparation experience as Power Query within Microsoft
Excel and Power BI Desktop, so existing users can begin using it quickly.

![Map data with entities in the Common Data Model.](media/cdm-map-entities.png)

## Ingest data by using Power BI dataflows

You can use the dataflows feature of Power BI to ingest data into the Common
Data Model format from Dynamics 365, Salesforce, Azure SQL Database, Excel,
SharePoint, or another source. You create and manage dataflows in app workspaces
by using the Power BI service. After you've connected and prepared your data,
you can choose to map it to a Common Data Model standard entity or load it as a
custom entity in the Common Data Model form in Azure Data Lake Storage Gen2.

Organizations can incorporate dataflows to suit their needs in these ways:

-   Customize standard entities and create their own.

-   Create dataflows programmatically with custom definition files (model.json).

-   Leverage powerful Azure products such as Azure Machine Learning, Azure
    Databricks, and Azure Data Factory.

-   Add CSV data from Azure Blob storage.

-   Enjoy more storage, more frequent refreshes, incremental refresh, and
    computed and linked entities with Power BI Premium.

## Resources for Power BI

-   [Self-service data prep in Power
    BI](/power-bi/service-dataflows-overview)

-   [Creating and using dataflows in Power
    BI](/power-bi/service-dataflows-create-use)

-   [Connect to data created by Power BI dataflows in Power BI
    Desktop](/power-bi/desktop-connect-dataflows)

-   [Developer resources for Power BI
    dataflows](/power-bi/service-dataflows-developer-resources)

## Optimize data exchange in the Azure Data Lake

[Azure Data Lake Storage
Gen2](./data-lake.md) is designed
specifically for enterprises to run large-scale analytical workloads in the
cloud. A wide variety of applications and services can easily access data in a
data lake, however, each consumer must understand the format and meaning of the
data before it can provide value. The Common Data Model simplifies this process
by providing a metadata system that describes the data and standard entities to
which producers can map.

## Resources for the Common Data Model and Azure Data Lake Storage Gen2

-   [Introduction to Azure Data Lake Storage
    Gen2](/azure/storage/blobs/data-lake-storage-introduction)

-   [Power BI and Azure Data Services dismantle data silos and unlock
    insights](https://aka.ms/cdmadsblog)
-   [Learn how to create Common Data Model definitions](./creating-schemas.md)
- [Learn how to use Common Data Model SDK](./1.0om/api-reference/api-reference.md) with [sample code](./samples.md) to [author Common Data Model artifacts](https://github.com/microsoft/CDM/tree/master/objectModel)