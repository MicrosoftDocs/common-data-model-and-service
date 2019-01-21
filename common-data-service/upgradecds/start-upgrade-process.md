---
title: "Upgrade to Common Data Service for Apps | Microsoft Docs"
description: "Provides instructions on how to upgrade from previous version of Common Data Service to CDS for Apps"
author: "JimDaly"
manager: "annbe"
ms.date: "01/14/2019"
ms.topic: "article"
ms.custom: ""
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: ""
audience: "IT Pro"
ms.reviewer: kvivek
ms.author: jdaly
---

# Step 1: Start upgrade process for your existing database to CDS for Apps

To use the new features in CDS for Apps, the Environment Administrator must
update their existing database that was created with the previous version of
CDS. 

## FAQs: Before upgrading your database 

These are some frequently asked questions (FAQs) before upgrading your database.

- [Which databases do I need to upgrade?](#which-databases-do-i-need-to-upgrade)
- [How long will this take?](#how-long-will-this-take)
- [Can I cancel the upgrade process once it’s initiated?](#can-i-cancel-the-upgrade-process-once-its-initiated)
- [Will there be any downtime of the database or apps in production during the upgrade?](#will-there-be-any-downtime-of-the-database-or-apps-in-production-during-the-upgrade-process)

### Which databases do I need to upgrade? 

-   Databases on the previous version of CDS. 

-   Databases containing vital data for your organization. 

You do not need to upgrade test environments and databases created while trying
out the product. Any databases that you choose not to upgrade will eventually be
deleted. 

We recommend first upgrading a test or trial database (on the previous version
of CDS) to familiarize yourself with the process before upgrading your
production database. 

### How long will this take?

The duration of the upgrade will require several hours. The actual amount of time depends on the amount of data in the database.

The first step creates a test migration and should provide some indication of how long the final migration in the 3rd step will require. There is no visual indicator of the progress of the migration.


### Can I cancel the upgrade process once it’s initiated? 

No, you cannot cancel the upgrade process for a database once you initiate it.
It’s important that you read through this entire document and understand the
process before initiating the upgrade. 

> [!IMPORTANT]
> Once you start the upgrade process you must not delete the database. This will leave your environment in an inconsistent state. If you choose to abandon the upgrade process after you have started, contact support for assistance.

### Will there be any downtime of the database or apps in production during the upgrade? 

The upgrade process consists of three steps as described later. Only the third
step involves downtime for the database as well as the apps and flows connecting
to it. We encourage admins to communicate to users when step 3 is planned to be executed. 

## Start the database upgrade process

To start upgrading your database to the latest CDS for Apps: 

1.  If you’re an environment Administrator, go to the [PowerApps admin
    center](https://admin.powerapps.com/), and in the left navigation pane,
    select **Environments**. 

    Environments that have a database on the previous version of CDS have **Upgrade now** listed next to them. 

    ![Environments](media/environments.png)

2.  On the **Upgrade** page, select the language and currency of the database,
    and then select **Create test database**.  

    ![Create test database](media/create-test-database.png)

    > [!IMPORTANT]
    > It may take several hours to create the test database. There is no progress bar. The spinning icon for the first step indicates is is running.
    >
    > You might want to start this in the afternoon and check it the next day to see how it went.

    A test database with the latest version of CDS for Apps is created. You can view the schema of the new database during the creation process, as shown in the following example. 

    ![Database schema](media/db-schema.png)

After the test database is created, the environment looks like the following:  

![After database upgrade](media/after-db-upgrade.png)

## Next step

Verify that the apps and flows are working as expected with the test database on
the latest version of CDS for Apps. 

You can view all changes that occurred during creation of the test database, including any errors that occurred while copying data from the original database to the test database.  

![Errors during database upgrade](media/error-db-upgrade.png)

If you encounter any errors, see [Errors and resolutions](errors-resolutions.md) for information to help troubleshooting.

> [!div class="nextstepaction"]
> [Step 2: Upgrade and verify your apps and flows](upgrade-verify-apps-flows.md)
