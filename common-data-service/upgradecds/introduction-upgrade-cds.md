---
title: "Upgrade to Common Data Service for Apps | Microsoft Docs"
description: "Provides instructions on how to upgrade from previous version of Common Data Service to CDS for Apps"
author: "JimDaly"
manager: "ryjones"
ms.date: "03/17/2019"
ms.topic: "article"
ms.custom: ""
ms.service: CommonDataService
ms.technology: "CommonDataService"
keywords: ""
audience: "IT Pro"
ms.reviewer: jdaly
ms.author: jdaly
---

# Upgrade to Common Data Service for Apps

The previous version of Common Data Service (CDS) was enhanced and released as **Common Data Service (CDS) for Apps** in March 2018 to offer significant new capabilities such as server-side logic, improved app-building experience, and a solid extensibility platform (based on the proven Dynamics 365 Customer Engagement platform) for developers and ISVs. More information: [New features in the Common Data Service for Apps and PowerApps Spring Update](https://powerapps.microsoft.com/en-us/blog/cds-for-apps-march/).

## Is it too late to start an upgrade?

Our goal is that everyone who wants to upgrade is able to upgrade. 

The deadline to start an upgrade ended on March 15, 2019. We have started the process of disconnecting databases for everyone who did not start their upgrade before March 15, but the process will take several weeks.

If you are still able to start an upgrade as described in [Start the database upgrade process](start-upgrade-process.md#start-the-database-upgrade-process), there is a very good chance you can proceed. Before we disconnect any database we will double-check to make sure no one has started an upgrade. *As we approach the end of March, the chance you can start an upgrade by yourself will decrease as more databases are disconnected.*

If you cannot successfully start the upgrade process, we have probably already disconnected your database. If you wish to upgrade, please contact support and we can re-connect you so that you can start the upgrade.

> [!IMPORTANT]
>  We intend to discontinue the service on April 15, 2019.
>
>  After a database is disconnected, we will keep the data for 30 days. If you want to request a copy of your data please contact support.

## Options

To use the new capabilities in CDS for Apps, existing users on the previous version of Common Data Service can upgrade to the latest CDS for Apps using one of the following options:

- **Upgrade your previous version of CDS to CDS for Apps.**
    - This is the best option to preserve any apps or flows that use the previous version of CDS.
    - This process will require several hours and require cooperation with the authors of any apps or flows connected to this database.
    - More information: [Overview of the upgrade process](upgrade-overview.md).
- **Delete your previous version CDS database, then create a new CDS for Apps database in the existing environment.**
    - If you haven't used the previous version CDS database or you don't care to preserve any apps for flows that used it. This is a simple option that will allow you to use CDS for Apps right away with a minimum amount of time.

    > [!IMPORTANT]
    > Do not delete a database if you have started the upgrade process. Contact support to request your database be deleted.

    - More information: [Delete your previous version Common Data Service database](delete-legacy-cds-database.md)
- **Do nothing**
    - If you did not start Step 1 of the upgrade process before March 15, 2019, we will disconnect your database and store your data for 30 days before deleting it. If you wish to reconnect a database, you must contact support. If you want a copy of your data, you must contact support and request and request it.


## Next steps

- [Overview of the upgrade process](upgrade-overview.md): Provides overview of the steps involved in the upgrade process.
- [What to expect on upgrading](what-to-expect.md): Provides information about things to expect when upgrading your previous version of Common Data Service to CDS for Apps.
