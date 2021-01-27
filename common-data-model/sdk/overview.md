---
title: Overview of Common Data Model | Microsoft Docs
description: Overview of Common Data Model.
author: msftman
ms.service: common-data-model
ms.reviewer: v-iap
ms.topic: article
ms.date: 03/13/2020
ms.author: Deonhe
---

# Overview

The term *Common Data Model* describes at least five related capabilities or ideas:

Capability | Details
---|---
A way to describe the location and shape of data records that are stored in files.|  <UL><LI>This is also called a *Common Data Model folder*, because the data files are often grouped together in a data lake folder or a hierarchy of folders. </LI><LI>An organizing document called a manifest acts as the entry point for a collection of entity schema definitions and data partition locations.</LI></UL>
A collection of reference entities that have been published on GitHub to represent the most common shapes of data that customers may find in the business application ecosystem. | The collection includes:<UL><LI>Base entities for Dataverse.</LI><LI>Entities for Dynamics 365 Sales, Dynamics 365 Customer Service, and Dynamics 365 Marketing.</LI><LI>Industry-specific accelerator extensions to Dataverse.</LI><LI>Analytic data from other services.</LI></UL>
The metadata used to describe the logical concepts, compositions, and semantic meanings for, and relationships between, standard published entities or a customer's private standards or ad-hoc compositions. | The metadata includes: <ul><li>Logical classes of entities, with inheritance and containment.<li>An extensible way to create rich, complex data types and to describe the semantic meaning and other metadata for entities and their attributes.<li>A set of shared semantic meaning indicators for many business types and needs, such as:<ul><li>First name, email address, fiscal calendar parts, distance in meters, and more.<li>General Data Protection Regulation (GDPR) data categories, usage restrictions, and identifiability.<li>Estimates, probabilities, occurrence date, and base currency.</ul>
An object model library.| The object library:<ul><li>Reads, manages, and creates the Common Data Model folder metadata files.<li>Creates comprehensible logical descriptions and semantic meanings for standard or custom entities.<li>Generates a Common Data Model folder document and concrete entity metadata by using standard or custom entity schemas as a guide.</li></ul>
The ecosystem of applications and services. | The ecosystem makes use of some or all of the four capabilities to help app developers work cooperatively on standardized entity shapes or share metadata.

## Learn more

- Common Data Model [fundamentals](fundamentals.md)
- Common Data Model [logical definitions](logical-definitions.md)


