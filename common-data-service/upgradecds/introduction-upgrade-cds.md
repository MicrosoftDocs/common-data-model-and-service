---
title: "Upgrade to Common Data Service for Apps | Microsoft Docs"
description: "Provides instructions on how to upgrade from previous version of Common Data Service to CDS for Apps"
author: "JimDaly"
manager: "annbe"
ms.date: "01/11/2018"
ms.topic: "article"
ms.custom: ""
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: ""
audience: "IT Pro"
ms.reviewer: kvivek
ms.author: jdaly
---

# Upgrade to Common Data Service for Apps

The previous version of Common Data Service (CDS) was enhanced and released as **Common Data Service (CDS) for Apps** in March 2018 to offer significant new capabilities such as server-side logic, improved app-building experience, and a solid extensibility platform (based on the proven Dynamics 365 Customer Engagement platform) for developers and ISVs. More information: [New features in the Common Data Service for Apps and PowerApps Spring Update](https://powerapps.microsoft.com/en-us/blog/cds-for-apps-march/).

## Options

To use the new capabilities in CDS for Apps, existing users on the previous version of Common Data Service can upgrade to the latest CDS for Apps using one of the following options:

- **Upgrade your previous version of CDS to CDS for Apps.**
    - This is the best option to preserve any apps or flows that use the previous version of CDS.
    - This process will require several hours and require cooperation with the authors of any apps or flows connected to this database.
    - More information: [Overview of the upgrade process](upgrade-overview.md).
- **Delete your previous version CDS database, then create a new CDS for Apps database in the existing environment.**
    - If you haven't used the previous version CDS database or you don't care to preserve any apps for flows that used it. This is a simple option that will allow you to use CDS for Apps right away with a minimum amount of time.
        > [!IMPORTANT]
        > Do not delete a database if you have started the upgrade process.
    - More information: [Delete your previous version Common Data Service database](delete-legacy-cds-database.md)
- **Do nothing**
    - When the previous version of CDS is discontinued, all remaining previous version CDS databases will be deleted. This date will be announced soon.



> [!WARNING]
> We will soon announce a date when the previous version of CDS will end. At that time, any remaining previous version CDS databases will be deleted.
>
> The end date has not yet been determined because we want to monitor how successful people are in completing their upgrades. When we have sufficient telemetry data to establish that people who wish to upgrade are able to, we will announce a date that we expect will provide everyone who wishes to upgrade sufficient time.

 

## Next steps

- [Overview of the upgrade process](upgrade-overview.md): Provides overview of the steps involved in the upgrade process.
- [What to expect on upgrading](what-to-expect.md): Provides information about things to expect when upgrading your previous version of Common Data Service to CDS for Apps.
