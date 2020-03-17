---
title: Overview of Common Data Model | Microsoft Docs
description: Overview of Common Data Model.
author: msftman
ms.service: common-data-model
ms.reviewer:
ms.topic: article
ms.date: 03/13/2020
ms.author: Deonhe
---

# Overview

The term *Common Data Model* describes at least five related capabilities or ideas:

-   A way to describe the location and shape of data records that are stored in files.

    -   This is also called a *Common Data Model folder*, because the data files are often grouped together in a data lake folder or a hierarchy of folders.

    -   An organizing document called a manifest acts as the entry point for a collection of entity schema definitions and data partition locations.

-   A collection of reference entities that have been published on GitHub to represent the most common shapes of data that our customers are likely to find in our business application ecosystem, including:

    -   Base entities for Common Data Service.

    -   Entities for Dynamics 365 Sales, Dynamics 365 Customer Service, and
        Dynamics 365 Marketing.

    -   Industry-specific accelerator extensions to Common Data Service.

    -   Analytic data from other services.

-   The metadata used to describe the logical concepts, compositions, and semantic meanings for—and relationships between—standard published entities or a customer's private standards or ad-hoc compositions. This includes:

    -   Logical classes of entities, with inheritance and containment.

    -   An extensible way to create rich, complex data types and to describe the semantic meaning and other metadata for entities and their attributes.

    -   A set of shared semantic meaning indicators for many business types and needs, such as:

        -   First name, email address, fiscal calendar parts, distance in meters, and more.

        -   General Data Protection Regulation (GDPR) data categories, usage restrictions, and identifiability.

        -   Estimates, probabilities, occurrence date, and base currency.

-   An object model library to:

    -   Read, manage, and create the Common Data Model folder metadata files.

    -   Create comprehensible logical descriptions and semantic meanings for standard or custom entities.

    -   Generate a Common Data Model folder document and concrete entity metadata by using standard or custom entity schemas as a guide.

-   The overall ecosystem of applications and services that make use of some or all of these four notions to help app developers work cooperatively on standardized entity shapes or share metadata.

## Learn more

- Common Data Model [technical details](technical-details.md)
- Common Data Model [logical definitions](logical-definitions.md)
