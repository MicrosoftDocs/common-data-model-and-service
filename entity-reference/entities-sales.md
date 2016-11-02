---
title: "Sales entities | Common Data Model"
description: "The sales entities let you create end-to-end sales solutions."
author: "clwesene"
manager: "robinarh"
ms.date: "11/02/2016"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: ""
audience: "Developer, IT Pro"
ms.assetid: "a652c3f2-17b2-4cc6-9492-98d0f9303c02"
---

# Sales entities

The sales entities let you create end-to-end sales solutions, from tracking leads and opportunities, to following through with contacts, to accepting and delivering orders, to sending invoices.

## Sales invoice ERD

![Sales Invoice ERD](/entity-reference/media/sales-invoice.png "Sales invoice ERD")

## Sales order ERD

The sales order is modeled with a header, lines, and deliveries. The delivery enables a single line item to be broken up into shipments to different locations. For example, out of 100 items of a specific product, 60 items are shipped to one location, and 40 items are shipped to another location.

![Sales order ERD](/entity-reference/media/sales-order.png "Sales order ERD")

## Reference

[Sales reference](/entity-reference/entity-tables/sales.md "Sales reference")
