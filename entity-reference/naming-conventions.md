---
title: "Naming conventions | Common Data Model"
description: "The Common Data Model follows these naming conventions."
author: ""
manager: "robinarh"
ms.date: "11/02/2016"
ms.topic: "topic"
ms.prod: "clwesene"
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: ""
audience: "Developer, IT Pro"
ms.assetid: "de678eaa-6ef2-483a-93ec-17ff7b713159"
---

#Naming conventions

To provide a consistent experience across objects, and to improve discoverability and usability, the Common Data Model follows these naming conventions:

* Entity names are singular. Examples: Tenant, Volunteer, SalesOrder.
* Entity ID names are created by appending “ID” to the entity name. Examples: ExpenseID, VolunteerID, FamilyMemberID.
* Lookup fields are named with the entity name of the entity that they are related to. Example: The Employee entity has a lookup field that is named __Company__, and that is foreign key to the primary key of the Company entity. In this case, the company is the employer of the employee.
