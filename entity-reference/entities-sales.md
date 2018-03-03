---
title: "Sales entities | Common Data Model"
description: "The sales entities let you create end-to-end sales solutions."
author: "clwesene"
manager: "robinarh"
ms.date: "05/08/2017"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: "standard entities, ERD, sales, sales invoice, sales order"
audience: "Developer, IT Pro"
ms.assetid: "a652c3f2-17b2-4cc6-9492-98d0f9303c02"
ms.reviewer: robinr
ms.author: clwesene
---

# Sales entities

[!INCLUDE [](../includes/new-version.md)]


The sales entities let you create end-to-end sales solutions, from tracking leads and opportunities, to following through with contacts, to accepting and delivering orders, to sending invoices.

## Sales invoice ERD

![Sales Invoice ERD](media/sales-invoice.png "Sales invoice ERD")

## Sales order ERD

The sales order is modeled with a header, lines, and deliveries. The delivery enables a single line item to be broken up into shipments to different locations. For example, out of 100 items of a specific product, 60 items are shipped to one location, and 40 items are shipped to another location.

![Sales order ERD](media/sales-order.png "Sales order ERD")

## Quotation ERD

![Quotation](media/quotation.png)

## Competitor ERD

![Competitor](media/competitor.png)

## Lead ERD

![Lead](media/lead.png)


## Reference

[Sales reference](entity-tables/sales.md "Sales reference")
