---
title: Dynamics 365 integration  | Microsoft Docs
description: 
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

The Dynamics 365 data integration feature enables the flow of data between Dynamics 365 for Sales, Dynamics 365 for Operations, and other products through Common Data Service. This Technical Preview of the Data Integration feature enables a basic flow of accounts and other entity data to enable a prospect-to-cash scenario. This document describes the capabilities, usage guidelines, and current limitations of the Data Integration feature.

The Microsoft Dynamics 365 Data Integration feature is available to customers who have at least one Dynamics 365 product. Currently, it is available to authorized Technology Adoption Program (TAP) customers via the Microsoft PowerApps Admin Center. This feature enables the flow of data between Microsoft Dynamics products through Common Data Service (CDS). For example, customer information in Microsoft Dynamics 365 for Sales can flow to Microsoft Dynamics 365 for Operations. Users don’t have to manually move the data or use a third-party data integration tool.

This document includes detailed descriptions of the capabilities, usage guidelines, and current limitations of this feature.

Concepts
========

You should be aware of key concepts as you go on to use the Data Integration feature. The following illustration shows the key services and relationships that are involved in Data Integration.

![Dynamics 365 data integration services and relationships](media/dynamics-integration.png)

Connections
-----------

Before you can work with a Data Integration project, you must provision a connection for each system that you intend to work with in the PowerApps portal. You then reference those connections in a Data Integration project. Connections are stored in a CDS environment. However, they operate above environments. The Data Integration projects use a connection that is stored in an environment to move data into and out of other systems, and into and out of an environment. Data doesn’t have to move into or out of the same environment as the connection.

When you provision a connection on the PowerApps site, unlike other connection services, you aren’t asked to select a specific instance of your target system. The connections on the PowerApps site just pair your Active Directory credentials with a target system. Later, when you specify a connection in a project, you will select from your set of accessible data set instances.

Data Integration
----------------

The Data Integration feature is currently available as a tab in the PowerApps Admin Center. The **Data Integration** tab appears only to customers who are authorized TAP customers, and who are on our permissions list. Currently, the feature is limited to two users per tenant.

The PowerApps Admin Center is a temporary home for the **Data Integration** tab. Eventually, it will be located in a new Admin center that is dedicated to Dynamics 365.

Projects
--------

Projects enable the flow of data between systems. A project is a list of one or more tasks. Each task identifies a mapping between a source entity and a CDS entity, and then, optionally, a mapping between CDS entity and a destination entity. Mappings indicate which fields map to which other fields. They also specify default values and value maps. Tasks are run in the order in which they appear.

Transformations (default values and value maps)
-----------------------------------------------

We currently provide two types of transformations: default values and value maps. Default values are values that are filled into a field when there is no value available. Default values are required for mapping to an entity which has a required field but there is no source field to map from. Value maps define how values that are present in one entity should be mapped to values in the other entity.

You should inspect the default values and value maps that we provide for your project, and make sure that they align with the values in your entities. Visit all sides of mappings: Source to CDS, and CDS to Destination. The example that follows shows both default values and value maps. You can directly edit and save your changes back to the project.

Eventually, you will be able to specify more complex transformations and filters on the data. On each row that maps a field, in the middle **Map Type** column, there is either an equal sign, **=**, or **Fn**. **Fn** indicates that a function, or transformation, has been applied. Currently, **Fn** is only available for fields we know you might need to customize. To edit a default value or value map, click the pencil symbol next to the **Fn**.

![Mapping fields between Dynamics 365 and Common Data Service](media/dynamics-integration-mapping.jpg)

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

Synchronization direction
-------------------------

Data Integration projects synchronize data in only one direction. This system is therefore a single-master system. The flow through a project goes only from source to destination. The source always overwrites the destination. If you edit data in the destination, so that it differs from the data in the source, and you then synchronize the project, the Data Integration project writes over the data in the destination system. A template can define either Dynamics 365 for Sales or Dynamics 365 for Operations as the source.

Eventually, we plan to support a multi-master system. In a multi-master system, if the user edits data in either the source or the destination, the other system is updated. However, this feature isn’t yet implemented.

Business keys
-------------

The predefined templates assume synchronization based on a business key. A business key is a key that the business wants to enforce uniformly across multiple systems (for example, both Dynamics 365 for Sales and Dynamics 365 for Operations). For example, a car rental company uses a car’s vehicle identification number (VIN) as a unique way to identify cars across all its internal systems. As another example, many Microsoft Dynamics customers might want to use the same customer ID for a customer in both Dynamics 365 for Sales and Dynamics 365 for Operations. We designed the Data Integration feature so that customers can use a business key across multiple systems.

By default, Dynamics 365 for Sales doesn’t require a business key. To enable business keys, we will provide you a Dynamics 365 for Sales solution. After you import the solution into your Dynamics 365 for Sales system, the Data Integration projects will work. In general, we will augment Dynamics 365 for Sales either by using an existing field or by creating a new column for the business key. In the case of the Dynamics 365 for Sales entity, which we want to synchronize with the Dynamics 365 for Operations entity, we use the **Account.Account Number** field in Dynamics 365 for Sales, and make it both required and unique. You are responsible for making sure that there is a valid customer identification value in **Account.Account Number** field in Dynamics 365 for Sales. If there is no value in this field, we won’t synchronize the records from Dynamics 365 for Sales to Dynamics 365 for Operations.

Eventually, we will enable data integration that doesn’t require business keys. Instead, mapping tables will be used.

Consent
-------

When you create a new project, we ask you for explicit consent, because we are moving data between systems. There are two areas of concern:

Data from a high-compliance system (such as Dynamics 365 for Sales) might be brought into a less-compliant system (such as CDS or Dynamics 365 for Operations).

Data might be moved between regional data centers, such as North America and Europe.

Be sure to read the **Privacy Notice and Consent** page carefully, and make sure that the correct persons give consent. We won’t create a project unless consent is given. We record the consent in our log files.

Running a project
-----------------

Currently, we can run a project only on demand. We haven’t yet implemented the Scheduled runs feature. First, inspect the mapping in the task to make sure that the values will map as you expect. Make any adjustments that are required to help guarantee that the data will flow correctly. Pay special attention to default values and value maps. In this document, we outline specific default values and value maps for several of the key entities that enable the prospect-to-cash scenario.

Monitoring a project run
------------------------

The **Scheduling** tab provides a dashboard where you can currently view a list of current and previous project runs. If you click a project run, you can view detailed progress information as the Data Integration project moves data along the paths from source to destination.

Eventually, the **Scheduling** tab will also show error records. However, this feature isn’t yet implemented.

Running a Data Integration project
==================================

Caution
-------

Don’t use the Data Integration feature with production data or production environments until Microsoft releases it as “Generally Available” (GA). Otherwise, you might lose data. For example, data might be corrupted or overwritten. For additional guidance, see your TAP agreement.

Prerequisites
-------------

You must have the following items:

An instance of Microsoft Dynamics 365 for Operations update 4 or later. (You might have to apply some hotfixes.) You should stay current with the latest updates of Dynamics 365 for Operations.

The most current version of Dynamics 365 for Sales. Minor mapping issues will be fixed in later versions of Dynamics 365 for Sales.

A Dynamics 365 for Sales solution to help guarantee that the business keys work correctly. Work with your TAP customer contact or the product team to obtain and install the solution.

You must have an environment in CDS, and you must have created a database in that environment.

Tenant ID
---------

To access the Data Integration feature, you might have to provide your tenant ID to Microsoft.

Create connections
------------------

**Note:** You must create a connection for each system that you will work with.

Go to the PowerApps site at <https://web.powerapps.com>.

Click **Connections**.

> The **Connections** page shows all the connections that you’ve provisioned. If you don’t yet have the connections that are required for your Data Integration project, you must create a new connection.

Click **New connection**.

In the list of connection types that PowerApps can work with, select a connection type. For example, if you’re working with Dynamics 365 for Sales, select **Dynamics 365**. Then, in the dialog box, enter your identity and access credentials.

On the PowerApps site, you should see a list of standard entities on the **Entities** tab. If you don’t see a list of standard entities, you must create a CDS environment and database.

Navigate to the Data Integration feature
----------------------------------------

To work with the Data Integration feature, follow these steps.

Open the PowerApps Admin Center at <https://admin.powerapps.com>. The **Data Integration** tab should appear in the left navigation pane. If it doesn’t appear there, and you’re an authorized TAP customer, check with your Microsoft contact.

Click the **Data Integration** tab. The **Data integration projects (Technical Preview)** page should appear. If you’re just starting to use the feature, you should see a **New Project** link that you can use to create a new project.

Create a new project
--------------------

To create a new project, follow these steps.

Click the **New Project** link in the upper-right corner, or click the link that is provided on the page. The **New data integration** wizard starts.

Enter a name for the project.

Select a predefined project template to create a base project that you can run directly. (Eventually, you will be able to customize the project before you run it. However, project customization isn’t yet supported.)

For each system, select the connection, select the dataset, and enter a company code (for Dynamics 365 for Operations). As we noted earlier, you must first provision your connection on the PowerApps site.

Run a project
-------------

To run a project, click S**ync Now** in the upper-right corner. After a project has started synchronization, click the **Scheduling** tab to monitor the progress of the project.

