---
title: Automotive Accelerator - Dynamics 365 | Microsoft Docs
description: Develop automotive solutions with the extensions to Common Data Model and the built-in forms, views, and dashboards of the Dynamics 365 Automotive Accelerator. 
author: smithy7
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 07/10/2019
ms.author: smithc
---

# The Dynamics 365 Automotive Accelerator

[!INCLUDE[cc-beta-prerelease-disclaimer](../includes/cc-beta-prerelease-disclaimer.md)]

With the [Dynamics 365 Automotive Accelerator](https://appsource.microsoft.com/product/dynamics-365/msauto.msftautomotivecommondatamodel?tab=Overview), you can develop solutions based on entities and attributes that dealerships and OEMs commonly leverage for customer experience and other business processes. These entities include deals, sales contracts, specifications, fleet, warranties, inspection, test drives, branding, business, customer-vehicle relationship, vehicle and equipment, lead, service and after-sales management, and more. The accelerator includes an automotive data model, PowerBI apps, canvas and model-driven sample apps based on connected experiences.

> [!IMPORTANT]
> The Automotive Accelerator is a preview feature.

The automotive accelerator provides the following to partners and customers:

-   Extensions to Common Data Model to include a data model that supports customer experiences, including entity definitions and relationships.
-	Sample model-driven apps to show some possibilities of how Dynamics 365 and the automotive data model can be used, including customer experience management, customer 360, connected field service, and DMS.
-	Sample canvas apps for the Fleet Manager to quickly and pro-actively schedule service appointments with service centers to show how anyone can quickly develop new apps with the Power Platform using the Automotive Accelerator.
-	Sample Power BI dashboards that provide analytics around vehicle inventory, services, lead disposition, branding, and business operation. 
-	Sample "Model.json" file to implement the automotive data model as Common Data Model folders in Azure Data Lake Storage for analytics, AI, and Machine Learning.
-	Individual solutions for Sales, After Sales, Marketing and a package that you can deploy and install, including sample data. The Automotive Common Data Model extension can also be installed using a Power Platform SKU. 
-	Test drive experience through AppSource with walkthroughs, reference guides, entity-relationship diagrams, and metadata documentation on the data model.


## Sitemap extensions

With the Dynamics 365 Automotive Accelerator, you can optimize the customer experience, streamline OEM-to-dealer integration, and gain insights from analytics. When the accelerator is installed into Dynamics 365, the experience is transformed into one specifically built for automotive and it allows partners and customers to quickly build PowerApps and Power BI visualizations.
- [**Marketing**: Test Drives - Customer Segmentation]
- [**Sales**: Deals - Trade Ins - Quotes - Activities]
- [**After Sales**: Service Appointments - Service Contracts - Sales Contracts - Device Warranties]
- [**Vehicles**: Vehicles - Fleet]
- [**Setup Branding**: Device Brand - Device Class - Device Models - Device Model Codes - Device Variant - Device Type]
- [**Setup Business**: Business - Business Facility - Business Operation]


## Entities and workflows

These entities are built in to the Automotive Accelerator:

| **Marketing** | **Sales**   | **customers**         | **Devices (Vehicles/Components)** | **Foundation**         |
|------------------|-------------------|---------------------------|----------------------------------------|----------------------------------|
| Account          | Lead              | Lead                      | Objective                              | Condition                        |
| Contact          | Opportunity       | Opportunity               | Delivery Framework                     | Participating Org                |
| Address          | Campaign          | Campaign                  | Budget                                 | Location                         |
| Connection       | Designation       | OFAC Match                | Result                                 | Delivery Framework Contact       |
| Salutation       | Designation Plan | Docket                    | Indicator                              | Identifier                       |
| Employment       | Credit Plan       | Recommendation            | Indicator Value                        | Delivery Framework Description   |
| Education        | Credit Recipient | Request                   |                                        | Recipient Country                |
| Preference       | Designated Credit | Report                    |                                        | Recipient Region                 |
| Volunteers*      | Donor Commitment | Award                     |                                        | Sector                           |
| Membership*      | Planned Giving    | Award Version             |                                        | Expenditure                      |
| Connection*      | Payment Schedule | Review                    |                                        | Humanitarian Scope               |
| Connection Role* | Payment Asset     | Disbursement              |                                        | Policy Marker                    |
|                  | Transaction       | Objective                 |                                        | Result Reference                 |
|                  | Payment Method    | Delivery Framework        |                                        | Indicator Reference              |
|                  | Payment Processor | Budget                    |                                        | Indicator Value Location         |
|                  |                   | Disbursement Distribution |                                        | Dimension                        |
|                  |                   |                           |                                        | Narrative Translation            |
|                  |                   |                           |                                        | Non-Embedded Codelist            |
|                  |                   |                           |                                        | Non-Embedded Codelist Vocabulary |
|                  |                   |                           |                                        | Document Link                    |
|                  |                   |                           |                                        | Document Category                |
|                  |                   |                           |                                        | Document Language                |
|                  |                   |                           |                                        | Document Country                 |
|                  |                   |                           |                                        | Tag                              |

