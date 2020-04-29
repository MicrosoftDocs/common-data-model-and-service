---
title: AssetValueModelSetupEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Fixed asset book setup

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/FixedAssets/AssetValueModelSetupEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fixed asset book setup</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AllowNegativeNetBookValue](#AllowNegativeNetBookValue)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[AllowNetBookValueHigherThanAcquisitionCosts](#AllowNetBookValueHigherThanAcquisitionCosts)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[AlternativeDepreciationProfileId](#AlternativeDepreciationProfileId)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[CalculateDepreciation](#CalculateDepreciation)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[Calendar](#Calendar)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[CalendarId](#CalendarId)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[CreateDepreciationAdjustmentsWithBasisAdjustments](#CreateDepreciationAdjustmentsWithBasisAdjustments)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[DepreciationProfileId](#DepreciationProfileId)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[Description](#Description)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[ExtraordinaryDepreciationProfileId](#ExtraordinaryDepreciationProfileId)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[LeaveNetBookValueAt](#LeaveNetBookValueAt)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[PostingLayer](#PostingLayer)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[RoundOffDepreciation](#RoundOffDepreciation)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[ValueModelId](#ValueModelId)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[AcceleratedDepreciationProfileId](#AcceleratedDepreciationProfileId)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[ActionForAcquisitionOnJanuary1st](#ActionForAcquisitionOnJanuary1st)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[DerogatoryCalculation](#DerogatoryCalculation)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[DerogatoryTaxModel](#DerogatoryTaxModel)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[ReferencedValueModelId](#ReferencedValueModelId)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[RoundingMethod](#RoundingMethod)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[IsOverrideFixedAssetCalendarDays](#IsOverrideFixedAssetCalendarDays)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[AssetWorkingDays](#AssetWorkingDays)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[IsDepreciationRequiredInDisposal](#IsDepreciationRequiredInDisposal)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[ExpectedScrapPercentage](#ExpectedScrapPercentage)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[RoundOffDepreciationReportingCurrency](#RoundOffDepreciationReportingCurrency)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[Relationship_AssetDepreciationProfileRelationshipId](#Relationship_AssetDepreciationProfileRelationshipId)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[Relationship_AssetAlternativeDepreciationProfileRelationshipId](#Relationship_AssetAlternativeDepreciationProfileRelationshipId)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[Relationship_AssetExtraordinaryDepreciationProfileRelationshipId](#Relationship_AssetExtraordinaryDepreciationProfileRelationshipId)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[Relationship_AssetAcceleratedDepreciationProfileRelationshipId](#Relationship_AssetAcceleratedDepreciationProfileRelationshipId)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[BackingTable_AssetBookTableRelationshipId](#BackingTable_AssetBookTableRelationshipId)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="AssetValueModelSetupEntity.md" target="_blank">FixedAssets/AssetValueModelSetupEntity</a>|

### <a href=#AllowNegativeNetBookValue name="AllowNegativeNetBookValue">AllowNegativeNetBookValue</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowNegativeNetBookValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowNetBookValueHigherThanAcquisitionCosts name="AllowNetBookValueHigherThanAcquisitionCosts">AllowNetBookValueHigherThanAcquisitionCosts</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowNetBookValueHigherThanAcquisitionCosts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AlternativeDepreciationProfileId name="AlternativeDepreciationProfileId">AlternativeDepreciationProfileId</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlternativeDepreciationProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalculateDepreciation name="CalculateDepreciation">CalculateDepreciation</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculateDepreciation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Calendar name="Calendar">Calendar</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Calendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalendarId name="CalendarId">CalendarId</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalendarId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreateDepreciationAdjustmentsWithBasisAdjustments name="CreateDepreciationAdjustmentsWithBasisAdjustments">CreateDepreciationAdjustmentsWithBasisAdjustments</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreateDepreciationAdjustmentsWithBasisAdjustments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationProfileId name="DepreciationProfileId">DepreciationProfileId</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExtraordinaryDepreciationProfileId name="ExtraordinaryDepreciationProfileId">ExtraordinaryDepreciationProfileId</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExtraordinaryDepreciationProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LeaveNetBookValueAt name="LeaveNetBookValueAt">LeaveNetBookValueAt</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeaveNetBookValueAt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingLayer name="PostingLayer">PostingLayer</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingLayer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoundOffDepreciation name="RoundOffDepreciation">RoundOffDepreciation</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundOffDepreciation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValueModelId name="ValueModelId">ValueModelId</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValueModelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AcceleratedDepreciationProfileId name="AcceleratedDepreciationProfileId">AcceleratedDepreciationProfileId</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceleratedDepreciationProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActionForAcquisitionOnJanuary1st name="ActionForAcquisitionOnJanuary1st">ActionForAcquisitionOnJanuary1st</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActionForAcquisitionOnJanuary1st attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerogatoryCalculation name="DerogatoryCalculation">DerogatoryCalculation</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerogatoryCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerogatoryTaxModel name="DerogatoryTaxModel">DerogatoryTaxModel</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerogatoryTaxModel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReferencedValueModelId name="ReferencedValueModelId">ReferencedValueModelId</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReferencedValueModelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoundingMethod name="RoundingMethod">RoundingMethod</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOverrideFixedAssetCalendarDays name="IsOverrideFixedAssetCalendarDays">IsOverrideFixedAssetCalendarDays</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOverrideFixedAssetCalendarDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetWorkingDays name="AssetWorkingDays">AssetWorkingDays</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetWorkingDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDepreciationRequiredInDisposal name="IsDepreciationRequiredInDisposal">IsDepreciationRequiredInDisposal</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDepreciationRequiredInDisposal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpectedScrapPercentage name="ExpectedScrapPercentage">ExpectedScrapPercentage</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpectedScrapPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoundOffDepreciationReportingCurrency name="RoundOffDepreciationReportingCurrency">RoundOffDepreciationReportingCurrency</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundOffDepreciationReportingCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetDepreciationProfileRelationshipId name="Relationship_AssetDepreciationProfileRelationshipId">Relationship_AssetDepreciationProfileRelationshipId</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetDepreciationProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetAlternativeDepreciationProfileRelationshipId name="Relationship_AssetAlternativeDepreciationProfileRelationshipId">Relationship_AssetAlternativeDepreciationProfileRelationshipId</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetAlternativeDepreciationProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetExtraordinaryDepreciationProfileRelationshipId name="Relationship_AssetExtraordinaryDepreciationProfileRelationshipId">Relationship_AssetExtraordinaryDepreciationProfileRelationshipId</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetExtraordinaryDepreciationProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetAcceleratedDepreciationProfileRelationshipId name="Relationship_AssetAcceleratedDepreciationProfileRelationshipId">Relationship_AssetAcceleratedDepreciationProfileRelationshipId</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetAcceleratedDepreciationProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_AssetBookTableRelationshipId name="BackingTable_AssetBookTableRelationshipId">BackingTable_AssetBookTableRelationshipId</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_AssetBookTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FixedAssets/Main/AssetBookTable.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Main/AssetBookTable.cdm.json/AssetBookTable</a></td><td><a href="../../../Tables/Finance/FixedAssets/Main/AssetBookTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: FixedAssets/AssetValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
