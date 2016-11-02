---
title: "Known issues | Common Data Model"
description: ""
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

[Cannot save data after changing the title field](/entity-reference/known-issues.md#Cannot-save-data-after-changing-the-title-field "Cannot save data after changing the title field")

[Address data type field name may be missing Region](/entity-reference/known-issues.md#Address-data-type-field-name-may-be-missing-Region "Address data type field name may be missing Region")

[Refresh button in Entity Data Explorer may not work](/entity-reference/known-issues.md#Refresh-button-in-Entity-Data-Explorer-may-not-work "Refresh button in Entity Data Explorer may not work")


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

The fix for this issue is in progress.  To workaround this issue, please reload the page.  You can do this by using your browser's refresh button or navigating back to the Entity list.  Please note that navigating to either "Fields", "Keys", "Relations" or "Field Groups" will not suffice for this purpose.
