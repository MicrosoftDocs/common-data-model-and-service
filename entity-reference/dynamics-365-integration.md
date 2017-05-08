---
title: Dynamics 365 data integration  | Microsoft Docs
description: The Dynamics 365 data integration feature enable the flow of data between Dynamics 365 for Sales, Dynamics 365 for Operations, and other products through the Common Data Service.
author: "robinarh"
manager: "robinarh"
ms.date: "04/24/2017"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: "overview, introduction"

audience: "Developer, IT Pro"
ms.assetid: 0c7f8e4f-8433-447f-85b2-8e3788b3714a
---

# Dynamics 365 data integration

> [!NOTE]
> Add pre-release boilerplate.

The Microsoft Dynamics 365 data integration feature enables the flow of data between Microsoft Dynamics 365 for Sales, Microsoft Dynamics 365 for Operations, and other products through the Common Data Service. For example, customer information in Dynamics 365 for Sales can flow to Dynamics 365 for Operations. Users don’t have to manually move the data or use a third-party data integration tool. Specifically, this feature enables a basic flow of accounts and other entity data to enable a prospect-to-cash scenario. This topic describes the capabilities, usage guidelines, and current limitations of the Data Integration feature.

The Data Integration feature is available to customers who have at least one Dynamics 365 product. 

# Concepts

Before you use the Data Integration feature, you should be aware of some important concepts. The following illustration shows the main services and relationships that are involved in Data Integration.

![Dynamics 365 data integration services and relationships](media/dynamics-integration.png)

## Connections

Before you can work with a Data Integration project, you must provision a connection for each system that you intend to work with in the Microsoft PowerApps portal. You then reference those connections in a Data Integration project. Connections are stored in a Common Data Service environment. However, they operate above environments. The Data Integration projects use a connection that is stored in an environment to move data into and out of other systems, and into and out of an environment. Data doesn’t have to move into or out of the same environment as the connection.

When you provision a connection on the PowerApps site, unlike other connection services, you aren’t asked to select a specific instance of your target system. The connections on the PowerApps site just pair your Active Directory credentials with a target system. Later, when you specify a connection in a project, you will select from your set of accessible data set instances.

## Data Integration

The Data Integration feature is currently available as a tab in the PowerApps Admin Center. It's also available in the Business platform admin center (businessplatform.microsoft.com). 

## Projects

Projects enable the flow of data between systems. A project is a list of one or more tasks. Each task identifies a mapping between a source entity and a Common Data Service entity, and then, optionally, a mapping between the Common Data Service entity and a destination entity. Mappings indicate which fields map to which other fields. They also specify default values and value maps. Tasks are run in the order in which they appear.

## Connection sets

Connection sets are named collections of two or three connections and business unit mappings. Connection sets can be reused among projects. For example, you  start to use a connection set with a project that is targeted at development instances of Dynamics 365 for Sales and Dynamics 365 for Operations. However, you later switch to a different connection set that is used for production for that same project. The mappings enable the flow of data from specific business units within Dynamics 365 for Sales, Dynamics 365 for Operations, and the Common Data Servce. For example, you might specify the Dynamics 365 for Operations business unit as **North America**, and then specify the corresponding Common Data Service business unit as **NA** and the Dynamics 365 for Sales business unit as **NorthAmerica**. Then, when a data integration project is run, it will move data from Dynamics 365 for Operations "North America" to Common Data Service "NA" and to Dynamics 365 for Sales "NorthAmerica."

## Transformations 

We currently provide three types of transformations: default values, value maps, and truncate. Default values are values that are filled into a field when  no value is available. Default values are required in order to map to an entity that has a required field but there is no source field to map from. Value maps define how values that are present in one entity should be mapped to values in the other entity.

You should inspect the default values and value maps that we provide for your project, and make sure that they are aligned with the values in your entities. Visit all sides of mappings: source to the Common Data Service, and the Common Data Service to destination. The example that follows shows both default values and value maps. You can directly edit and save your changes back to the project.

Eventually, you will be able to specify more complex transformations and filters on the data. On each row that maps a field, in the middle **Map Type** column, there is either an equal sign (**=**) or **Fn**. **Fn** indicates that a function, or transformation, has been applied. Currently, **Fn** is available only for fields that we know you might have to customize. To edit a default value or value map, click the pencil symbol next to the **Fn**.

![Mapping fields between Dynamics 365 and the Common Data Service](media/dynamics-integration-mapping.png)

Currently, the default values and transforms are in JavaScript Object Notation (JSON) format. However, the format will likely change over time.

The following example shows a default value.

    \[{"transformType":"Default","defaultValue":"Organization"}\]

The following example shows a value map.

    \[{"transformType":"ValueMap","valueMap":{
    "us":"US",
    "usa":"US",
    "united States":"US",
    "united States of America":"US",
    "germany":"DE",
    "de":"DE",
    "deu":"DE",
    "france":"FR",
    "fr":"FR",
    "fra":"FR",
    "uk":"GB",
    "united Kingdom":"GB",
    "ja":"JA",
    "jap":"JA",
    "japan":"JA",
    "india":"IN",
    "in":"IN",

    "ind":"IN",
        "au":"AU",
        "ca":"CA"
    }}\]

## Synchronization direction

Data Integration projects synchronize data in only one direction. This system is therefore a single-master system. The flow through a project goes only from source to destination. The source always overwrites the destination. If you edit data in the destination so that it differs from the data in the source, and you then synchronize the project, the Data Integration project writes over the data in the destination system. A template can define either Dynamics 365 for Sales or Dynamics 365 for Operations as the source.

Eventually, we plan to support a multi-master system. In a multi-master system, if the user edits data in either the source or the destination, the other system is updated. However, this feature isn’t yet implemented.

## Business keys

The predefined templates assume synchronization that is based on a business key. A business key is a key that the business wants to enforce uniformly across multiple systems (for example, both Dynamics 365 for Sales and Dynamics 365 for Operations). For example, a car rental company uses a car’s vehicle identification number (VIN) as a unique way to identify cars across all its internal systems. As another example, many Microsoft Dynamics customers might want to use the same customer ID for a customer in both Dynamics 365 for Sales and Dynamics 365 for Operations. We designed the Data Integration feature so that customers can use a business key across multiple systems.

By default, Dynamics 365 for Sales doesn’t require a business key. To enable business keys, we will provide a Dynamics 365 for Sales solution. After you import the solution into your Dynamics 365 for Sales system, the Data Integration projects will work. In general, we will augment Dynamics 365 for Sales either by using an existing field or by creating a new column for the business key. In the case of the Dynamics 365 for Sales entity that we want to synchronize with the Dynamics 365 for Operations entity, we use the **Account.Account Number** field in Dynamics 365 for Sales, and make it both required and unique. You're responsible for making sure that there is a valid customer identification value in the **Account.Account Number** field in Dynamics 365 for Sales. If there is no value in this field, we won’t synchronize the records from Dynamics 365 for Sales to Dynamics 365 for Operations.

Addtionally, data in Dynamics 365 for Operations is guaranteed to be unique only if it has a combination of the legal entity and the key of an entity. If you want to integrate data from Dynamics 365 for Operations to Dynamics 365 for Sales, the data that you syncronize should also be unique independently of the legal entity, just as we require data to be unique in Dynamics 365 for Sales.

Eventually, we will enable data integration that doesn’t require business keys. Instead, mapping tables will be used.

## Consent

When you create a new project, we ask you for explicit consent, because we are moving data between systems. There are two areas of concern:

+ Data from a high-compliance system (such as Dynamics 365 for Sales) might be brought into a less-compliant system (such as the Common Data Service or Dynamics 365 for Operations).
+ Data might be moved between regional data centers, such as North America and Europe.

Be sure to read the **Privacy Notice and Consent** page carefully, and make sure that the correct persons give consent. We won’t create a project unless consent is given. We record the consent in our log files.

## Running a project

Currently, we can run a project only on demand. We haven’t yet implemented the Scheduled runs feature. First, inspect the mapping in the task to make sure that the values will be mapped as you expect. Make any adjustments that are required to help guarantee that the data will flow correctly. Pay special attention to default values and value maps. In this topic, we outline specific default values and value maps for several of the key entities that enable the prospect-to-cash scenario.

## Monitoring a project run

The **Scheduling** tab provides a dashboard where you can currently view a list of current and previous project runs. If you click a project run, you can view detailed progress information as the Data Integration project moves data along the paths from source to destination.

Eventually, the **Scheduling** tab will also show error records. However, this feature isn’t yet implemented.

# Running a Data Integration project

> [!WARNING]
> Don’t use the Data Integration feature with production data or production environments until Microsoft releases it as Generally Available (GA). Otherwise, you might lose data. For example, data might be corrupted or overwritten. For additional guidance, see your Technology Adoption Program (TAP) agreement.

## Prerequisites

You must have the following items:

+ An instance of Microsoft Dynamics 365 for Operations update 5 or later. (You might have to apply some hotfixes.) You should stay current with the latest updates of Dynamics 365 for Operations.
+ The most current version of Dynamics 365 for Sales. Minor mapping issues will be fixed in later versions of Dynamics 365 for Sales.
+ A Dynamics 365 for Sales solution to help guarantee that the business keys work correctly. Work with your TAP customer contact or the product team to obtain and install the solution.
+ An environment in the Common Data Service. You must also have created a database in that environment.

## Tenant ID

To access the Data Integration feature, you might have to provide your tenant ID to Microsoft.

## Create connections

> [!NOTE]
> You must create a connection for each system that you will work with.

1. Go to the PowerApps site at <https://web.powerapps.com>.
2. Click **Connections**.
    
   The **Connections** page shows all the connections that you’ve provisioned. If you don’t yet have the connections that are required for your Data Integration project, you must create a new connection.

3. Click **New connection**.
4. In the list of connection types that PowerApps can work with, select a connection type. For example, if you’re working with Dynamics 365 for Sales, select **Dynamics 365**. Then, in the dialog box, enter your identity and access credentials.
5. On the PowerApps site, on the **Entities** tab, you should see a list of standard entities. If you don’t see a list of standard entities, you must create a Common Data Service environment and database.

## Navigate to the Data Integration feature

To work with the Data Integration feature, follow these steps.

1. Open the PowerApps Admin Center at <https://admin.powerapps.com>. The **Data Integration** tab should appear in the left navigation pane. If it doesn’t appear there, and you’re an authorized TAP customer, check with your Microsoft contact.
2. Click the **Data Integration** tab. The **Data integration projects (Technical Preview)** page should appear. If you’re just starting to use the feature, you should see a **New Project** link that you can use to create a new project.

## Create a new project

To create a new project, follow these steps.

1. Click the **New Project** link in the upper-right corner, or click the link that is provided on the page. The **New data integration** wizard starts.
2. Enter a name for the project.
3. Select a predefined project template to create a base project that you can run directly. (Eventually, you will be able to customize the project before you run it. However, project customization isn’t yet supported.)
4. For each system, select the connection, select the dataset, and enter a company code (for Dynamics 365 for Operations). As we noted earlier, you must first provision your connection on the PowerApps site.

## Customize connection sets

When you first create a project, if you don't use an existing connection set, we will create a connection set for you. To edit a connection set, follow these steps.

1. On the main project page, click the **Connection Set** tab.
2. Change the connection set properties that you require.

Note, you might want to add additional business unit lines so that the same connection set can be used with different combinations of business units.

## Customize a project with new tasks

1. In a project, click **Add task** in the upper-right corner of the project page.
2. In the **Add task** dialog box, provide the name of the task, the entities in Dynamics 365 for Sales, Dynamics 365 for Operations, and the Common Data Service. A new task will be created in your project.

## Customize an existing mapping  

If a mapping between entities is incorrect or incomplete, you can change the mapping.

1. Select the attribute. A drop-down list becomes available, where you can select a different attribute.
2. Select the attribute to use.

## Create a new mapping 

If your project doesn't have all the attributes that you want to map, you can add a new mapping. Note that there is an empty task line at the bottom of your set of tasks.

+ Select the attribute for each source that you want to add.

## Run a project

To run a project, click **Sync Now** in the upper-right corner. After a project has started synchronization, click the **Scheduling** tab to monitor the progress of the project.
