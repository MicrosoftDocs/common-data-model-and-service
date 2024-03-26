---
title: Overview of CloudforSustainabilityEnergyDataModel - Common Data Model | Microsoft Docs
description: CloudforSustainabilityEnergyDataModel is a folder that contains standard entities related to the Common Data Model.
author: cdm-publisher
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 3/11/2024
ms.author: anbichse
---

# Overview of CloudforSustainabilityEnergyDataModel

The Microsoft Cloud for Sustainability energy data model helps organizations unify and streamline energy data to achieve their energy sustainability goals. It helps you to unify, standardize, and streamline energy data collection and storage for your organization across generation, procurement, and end use into a single unified data model.

The Cloud for Sustainability energy data model builds on the Cloud for Sustainability data model. It provides the schema required for generated energy, renewable energy, and purchased energy from different sources. It also provides associated consumption patterns across multiple sites and geographic components within a unified data model. The schema makes energy sustainability data available for use cases such as energy sustainability disclosures and energy regulatory reporting.

## Entities

|Name|Description|
|---|---|
|[AgreementDetails](AgreementDetails.md)|Binding agreement between the energy provider and the customer for the energy being sourced or procured.|
|[EnergyContract](EnergyContract.md)|Documented method/approach to source energy.|
|[EnergyContractType](EnergyContractType.md)|Various types of documented method/approach to source energy.|
|[EnergySource](EnergySource.md)|Medium or sources to generate energy.|
|[GeneratedEnergy](GeneratedEnergy.md)|Electric energy, measured in MWh, generated by the utility in a given location.|
|[PurchasedEnergy](PurchasedEnergy.md)|Electric energy, measured in MWh, delivered by the utility to a customer in accordance with the signed agreement.|
|[RenewableEnergyCertificate](RenewableEnergyCertificate.md)|Market-based instrument that represents the environmental attributes of electricity generated from renewable energy sources.|
|[UtilityType](UtilityType.md)|Classification of energy entities such as electricity or gas.|