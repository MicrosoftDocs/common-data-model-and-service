---
title: "Known issues | Common Data Service"
description: "This topic lists known issues in the Common Data Service."
author: "robinarh"
manager: "robinarh"
ms.date: "11/02/2016"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: ""
audience: "Developer, IT Pro"
ms.assetid: "be061389-ef79-4861-9210-671b0bdd00ce"
---

# Known issues

## Cannot save data after changing the title field

When changing the title field on an entity, if there are already lookups referencing this entity, an error will occur attempting to save the update to the entity metadata.   

### Solution

To work around this issue, you must first remove lookups to this entity, reapply the change to the title field, and reestablish the lookups.

## Address data type field name may be missing Region

Customers may notice that the Address data type field name is missing "/Region" when viewed with the Data Explorer and Excel Add-in.  

### Solution

This is a known issue and the fix is imminent.  To workaround this issue when creating a PowerApp, you can modify the default label that is added on the screen to include "/Region".  Customers using the Data Explorer or Excel add-in will see this resolved automatically once the issue is resolved.

## Refresh button in Entity Data Explorer may not work

In certain cases, the refresh button on the Entity Data Explorer view may not correctly refresh the data in the view.  As a result, data that has been added to your database via the Excel Add-in, a PowerApp, or through import may not appear. 

### Solution

The fix for this issue is in progress.  To workaround this issue, please reload the page.  You can do this by using your browser's refresh button or navigating back to the Entity list.  Please note that navigating to either "Fields", "Keys", "Relations" or "Field Groups" will not correctly refresh the data.

## Image support is missing at General Availability
Customers may notice that support for images has been temporarily removed from our General Availability release.  We are actively working on providing a simpler and more performant solution for managing images in the Common Data Service.  We apologize for the inconvenience or confusion this may cause.

### Solution
We are actively working on a new solution for this.  Please refer to this document to track when the new feature has been released!
