---
title: "Naming conventions | Common Data Model"
description: "The Common Data Model follows these naming conventions."
author: ""
manager: "robinarh"
ms.date: 05/09/2017
ms.topic: "topic"
ms.prod: "clwesene"
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: "names"
audience: "Developer, IT Pro"
ms.assetid: "de678eaa-6ef2-483a-93ec-17ff7b713159"
ms.reviewer: robinr
ms.author: clwesene
---

# Naming conventions

[!INCLUDE [](../includes/new-version-cdm.md)]


To provide a consistent experience across objects, and to improve discoverability and usability, the common data model follows these naming conventions:

* Entity names are singular. Examples: Tenant, Family, SalesOrder.
* Entity ID names are created by appending “Id” to the entity name. Examples: WorkerId, CaseId, FamilyId.
* Lookup fields are named with the entity name of the entity that they are related to. Example: The Worker entity has a lookup field that is named **Organization**, and that is foreign key to the primary key of the Organization entity. In this case, the company is the employer of the employee.
