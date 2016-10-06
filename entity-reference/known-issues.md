---
title: "Known issues"
description: ""
author: "robinarh"
manager: "robinarh"
ms.date: "08/24/2016"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataModel"
ms.technology: "CommonDataModel"
keywords: ""
audience: "Developer, IT Pro"
ms.assetid: "be061389-ef79-4861-9210-671b0bdd00ce"
---

# Known Issues

[Cannot save data after changing the title field](/entity-reference/known-issues.md#Cannot-save-data-after-changing-the-title-field "Cannot save data after changing the title field")

## Cannot save data after changing the title field

When changing the title field on an entity, if there are already lookups referencing this entity, an error will occur attempting to save the update to the entity metadata.   

### Solution

To work around this issue, you must first remove lookups to this entity, reapply the change to the title field, and reestablish the lookups.
