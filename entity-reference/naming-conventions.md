---
title: ""
description: ""
author: ""
manager: "robinarh"
ms.date: "08/24/2016"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataModel"
ms.technology: "CommonDataModel"
keywords: ""
audience: "Developer, IT Pro"
ms.assetid: ""
---

#Naming Conventions

To provide a consistent experience across objects, and to improve discoverability and usability, the CDM follows these naming conventions:

* Entity names are singular. Examples: Tenant, Volunteer, SalesOrder.
* Entity ID names are created by appending “ID” to the entity name. Examples: ExpenseID, VolunteerID, FamilyMemberID.
* Lookup fields are named with the entity name of the entity that they are related to. Example: The Employee entity has a lookup field that is named __Company__, and that is foreign key to the primary key of the Company entity. In this case, the company is the employer of the employee.
* Enumeration fields are named with the name of the __Enumeration__ data type.
* The fields for telephone numbers are named __BusinessPhone__, __CellPhone__, and __HomePhone__.
