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
keywords: "known issues, release notes"
audience: "Developer, IT Pro"
ms.assetid: "be061389-ef79-4861-9210-671b0bdd00ce"
---

# Microsoft Common Data Service - Known issues

## You can’t save data after you change the title field

When you change the title field on an entity, if any lookups already reference that entity, an error occurs during the attempt to save the update to the entity metadata.

### Solution

To work around this issue, you must first remove lookups to this entity, reapply the change to the title field, and then reestablish the lookups.



## Address data type field name might be missing “/Region”

Customers might notice that the Address data type field name is missing “/Region” when it is viewed by using Entity Data Explorer and the Microsoft Excel Add-in. 

### Solution

This is a known issue, and the fix is imminent. To work around this issue, when you create a Microsoft PowerApp, you can modify the default label that is added on the screen, so that it includes “/Region.” Customers who use Entity Data Explorer or the Excel Add-in will see this issue resolved automatically when the fix is released. 


## Refresh button in Entity Data Explorer might not work

In some cases, the Refresh button in Entity Data Explorer view might not correctly update the data in the view. Therefore, data that has been added to your database via the Excel Add-in, via a PowerApp, or through import might not appear. 

### Solution

The fix for this issue is in progress. To work around this issue, reload the page by using your browser’s Refresh button or navigating back to the Entity list. Note that navigating to Fields, Keys, Relations, or Field Groups will correctly update the data.

## Image support is missing
Customers may notice that support for images has been temporarily removed from this release. We are actively working on providing a simpler and more performant solution for managing images in the Common Data Service.

### Solution
We are actively working on a new solution for this and apologize for the inconvenience or confusion this may cause. Please refer to this document to track when the new feature has been released.

### Copyright and Terms of Use

© 2016 Microsoft Corporation. All rights reserved. 

This document is provided “as-is.” Information and views expressed in this document, including URL and other Internet Web site references, may change without notice. You bear the risk of using it. 

Some examples are for illustration only and are fictitious. No real association is intended or inferred. 

This document does not provide you with any legal rights to any intellectual property in any Microsoft product. You may copy and use this document for your internal, reference purposes. 

Some information relates to pre-released product which may be substantially modified before it’s commercially released. Microsoft makes no warranties, express or implied, with respect to the information provided here. 

