---
title: "Upgrade to Common Data Service for Apps | Microsoft Docs"
description: "Provides instructions on how to upgrade from previous version of Common Data Service to CDS for Apps"
author: "JimDaly"
manager: "ryjones"
ms.date: "03/03/2019"
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

## Deadline Extended

> [!IMPORTANT]
> If you intend to upgrade your previous version CDS database you must start the first step before March 15, 2019.
> 
> If you begin Step 1 before March 15, 2019 you can continue to complete the upgrade until the service is discontinued. We intend to continue the service until April 15, 2019.
>
> If you do not start Step 1 before March 15, 2019 we will disconnect your database and store your data for 30 days before deleting it. If you wish to reconnect a database, you must contact support before March 29.

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
    - If you do not start Step 1 of the upgrade process before March 15, 2019, we will disconnect your database and store your data for 30 days before deleting it. If you wish to reconnect a database, you must contact support before March 29. If you want a copy of your data, you must contact support and request a copy before April 15, 2019.


## Next steps

- [Overview of the upgrade process](upgrade-overview.md): Provides overview of the steps involved in the upgrade process.
- [What to expect on upgrading](what-to-expect.md): Provides information about things to expect when upgrading your previous version of Common Data Service to CDS for Apps.
