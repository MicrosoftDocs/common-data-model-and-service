---
title: "System fields | Common Data Model"
description: ""
author: "clwesene"
manager: "robinarh"
ms.date: "11/02/2016"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: ""
audience: "Developer, IT Pro"
ms.assetid: "2fd13f59-0562-4aff-abe0-9eb3b7d49efe"
---

# System fields

A set of standard fields is included with every entity. These fields are used to provide behaviors such as concurrency management, security, and audit trails.

Field Name | Description
---|---
RecordID | Type: BigInteger<br>Description: Uniquely identifies an instance of an entity.
Created By (CreatedByUser) | Type: Text<br>Description: The RecordID of the user who created the entity instance.
Created Record Date (CreatedOnDateTime) | Type: DateTime<br>Description: The date and time when the entity instance was created.
Last Modified By (LastModifiedByUser) | Type: Text<br>Description: The RecordID of the user who last modified the entity instance.
Modified Record Date (LastModifiedDateTime) | Type: DateTime<br>Description: The date and time when the entity instance was last modified.
