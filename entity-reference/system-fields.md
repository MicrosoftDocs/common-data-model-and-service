---
title: ""
description: ""
author: ""
manager: "robinarh"
ms.date: "08/24/2016"
ms.topic: "topic"
ms.prod: "CommonDataModel"
ms.service: ""
ms.technology: "CommonDataModel"
keywords: ""
audience: "Developer, IT Pro"
ms.assetid: ""
---

# System Fields

A set of standard fields is included with every entity. These fields are used by the CDM to provide behaviors such as concurrency management, security, and audit trails.

Field Name | Description
---|---
RecordID | Type: BigInteger<br>Description: Uniquely identifies an instance of an entity.
CreatedByUser | Type: Text<br>Description: The RecordID of the user who created the entity instance.
CreatedOnDateTime | Type: DateTime<br>Description: The date and time when the entity instance was created.
LastModifiedByUser | Type: Text<br>Description: The RecordID of the user who last modified the entity instance.
LastModifiedDateTime | Type: DateTime<br>Description: The date and time when the entity instance was last modified.
