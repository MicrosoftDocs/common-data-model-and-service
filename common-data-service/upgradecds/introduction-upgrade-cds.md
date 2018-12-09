---
title: "Upgrade to Common Data Service for Apps | Microsoft Docs"
description: "Provides instructions on how to upgrade from previous version of Common Data Service to CDS for Apps"
author: "JimDaly"
manager: "annbe"
ms.date: "12/09/2018"
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

To use the new capabilities in CDS for Apps, existing users on the previous version of Common Data Service can upgrade to the latest CDS for Apps using the following steps.

[!INCLUDE [options](includes/options.md)]


> [!WARNING]
> We will soon announce a date when the previous version of CDS will end. At that time, any remaining previous version CDS databases will be deleted.
>
> The end date has not yet been determined because we want to monitor how successful people are in completing their upgrades. When we have sufficient telemetry data to establish that people who wish to upgrade are able to, we will announce a date that we expect will provide everyone who wishes to upgrade sufficient time.


## Opt out of upgrade

If you have a previous version of CDS that you were simply evaluating and do not wish to upgrade, you have the following options.

- If your previous version CDS database is not in your default environment, and you do not want to preserve other apps or flows in the environment, use the steps in [Delete your previous version Common Data Service environment](delete-cds-environment.md).
- If your previous version CDS database is in your default environment, or you want to preserve any apps or flows defined in your environment, please wait and we will provide a method for you to delete only the previous version CDS database in any environment.
- Do nothing. When the previous version of CDS is discontinued all remaining previous version CDS databases will be deleted. This date will be announced soon.
 

## Next steps

- [Overview of the upgrade process](upgrade-overview.md): Provides overview of the steps involved in the upgrade process.
- [What to expect on upgrading](what-to-expect.md): Provides information about things to expect when upgrading your previous version of Common Data Service to CDS for Apps.
