---
title: ReqForecastPlanEntity in MasterPlanning - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Forecast plans in MasterPlanning(ReqForecastPlanEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/MasterPlanning/ReqForecastPlanEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Forecast plans</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ForecastPlanId](#ForecastPlanId)||<a href="ReqForecastPlanEntity.md" target="_blank">MasterPlanning/ReqForecastPlanEntity</a>|
|[ForecastPlanDescription](#ForecastPlanDescription)||<a href="ReqForecastPlanEntity.md" target="_blank">MasterPlanning/ReqForecastPlanEntity</a>|
|[ForecastModelId](#ForecastModelId)||<a href="ReqForecastPlanEntity.md" target="_blank">MasterPlanning/ReqForecastPlanEntity</a>|
|[WillForecastPlanningIncludeSupplyForecast](#WillForecastPlanningIncludeSupplyForecast)||<a href="ReqForecastPlanEntity.md" target="_blank">MasterPlanning/ReqForecastPlanEntity</a>|
|[WillForecastPlanningIncludeDemandForecast](#WillForecastPlanningIncludeDemandForecast)||<a href="ReqForecastPlanEntity.md" target="_blank">MasterPlanning/ReqForecastPlanEntity</a>|
|[WillForecastPlanningSkipCoverageCalculations](#WillForecastPlanningSkipCoverageCalculations)||<a href="ReqForecastPlanEntity.md" target="_blank">MasterPlanning/ReqForecastPlanEntity</a>|
|[ForecastRequirementReductionMethod](#ForecastRequirementReductionMethod)||<a href="ReqForecastPlanEntity.md" target="_blank">MasterPlanning/ReqForecastPlanEntity</a>|
|[PlannedOrderNumberSequenceRecId](#PlannedOrderNumberSequenceRecId)||<a href="ReqForecastPlanEntity.md" target="_blank">MasterPlanning/ReqForecastPlanEntity</a>|
|[PlannedOrderNumberSequenceCode](#PlannedOrderNumberSequenceCode)||<a href="ReqForecastPlanEntity.md" target="_blank">MasterPlanning/ReqForecastPlanEntity</a>|
|[ForecastPlanCalculationSessionNumberSequenceRecId](#ForecastPlanCalculationSessionNumberSequenceRecId)||<a href="ReqForecastPlanEntity.md" target="_blank">MasterPlanning/ReqForecastPlanEntity</a>|
|[ForecastPlanCalculationSessionNumberSequenceCode](#ForecastPlanCalculationSessionNumberSequenceCode)||<a href="ReqForecastPlanEntity.md" target="_blank">MasterPlanning/ReqForecastPlanEntity</a>|
|[RequirementDateDeductedSafetyIssueMarginDays](#RequirementDateDeductedSafetyIssueMarginDays)||<a href="ReqForecastPlanEntity.md" target="_blank">MasterPlanning/ReqForecastPlanEntity</a>|
|[RequirementDateAddedSafetyReceiptMarginDays](#RequirementDateAddedSafetyReceiptMarginDays)||<a href="ReqForecastPlanEntity.md" target="_blank">MasterPlanning/ReqForecastPlanEntity</a>|
|[ItemLeadTimeAddedReorderMarginDays](#ItemLeadTimeAddedReorderMarginDays)||<a href="ReqForecastPlanEntity.md" target="_blank">MasterPlanning/ReqForecastPlanEntity</a>|
|[CapacitySchedulingTimeFenceDays](#CapacitySchedulingTimeFenceDays)||<a href="ReqForecastPlanEntity.md" target="_blank">MasterPlanning/ReqForecastPlanEntity</a>|
|[CoverageTimeFenceDays](#CoverageTimeFenceDays)||<a href="ReqForecastPlanEntity.md" target="_blank">MasterPlanning/ReqForecastPlanEntity</a>|
|[BOMOrFormulaExplosionTimeFenceDays](#BOMOrFormulaExplosionTimeFenceDays)||<a href="ReqForecastPlanEntity.md" target="_blank">MasterPlanning/ReqForecastPlanEntity</a>|
|[BackingTable_ReqPlanForecastRelationshipId](#BackingTable_ReqPlanForecastRelationshipId)||<a href="ReqForecastPlanEntity.md" target="_blank">MasterPlanning/ReqForecastPlanEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ReqForecastPlanEntity.md" target="_blank">MasterPlanning/ReqForecastPlanEntity</a>|

### <a href=#ForecastPlanId name="ForecastPlanId">ForecastPlanId</a>

First included in: MasterPlanning/ReqForecastPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastPlanId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastPlanDescription name="ForecastPlanDescription">ForecastPlanDescription</a>

First included in: MasterPlanning/ReqForecastPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastPlanDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastModelId name="ForecastModelId">ForecastModelId</a>

First included in: MasterPlanning/ReqForecastPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastModelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillForecastPlanningIncludeSupplyForecast name="WillForecastPlanningIncludeSupplyForecast">WillForecastPlanningIncludeSupplyForecast</a>

First included in: MasterPlanning/ReqForecastPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillForecastPlanningIncludeSupplyForecast attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillForecastPlanningIncludeDemandForecast name="WillForecastPlanningIncludeDemandForecast">WillForecastPlanningIncludeDemandForecast</a>

First included in: MasterPlanning/ReqForecastPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillForecastPlanningIncludeDemandForecast attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillForecastPlanningSkipCoverageCalculations name="WillForecastPlanningSkipCoverageCalculations">WillForecastPlanningSkipCoverageCalculations</a>

First included in: MasterPlanning/ReqForecastPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillForecastPlanningSkipCoverageCalculations attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastRequirementReductionMethod name="ForecastRequirementReductionMethod">ForecastRequirementReductionMethod</a>

First included in: MasterPlanning/ReqForecastPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastRequirementReductionMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedOrderNumberSequenceRecId name="PlannedOrderNumberSequenceRecId">PlannedOrderNumberSequenceRecId</a>

First included in: MasterPlanning/ReqForecastPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedOrderNumberSequenceRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedOrderNumberSequenceCode name="PlannedOrderNumberSequenceCode">PlannedOrderNumberSequenceCode</a>

First included in: MasterPlanning/ReqForecastPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedOrderNumberSequenceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastPlanCalculationSessionNumberSequenceRecId name="ForecastPlanCalculationSessionNumberSequenceRecId">ForecastPlanCalculationSessionNumberSequenceRecId</a>

First included in: MasterPlanning/ReqForecastPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastPlanCalculationSessionNumberSequenceRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastPlanCalculationSessionNumberSequenceCode name="ForecastPlanCalculationSessionNumberSequenceCode">ForecastPlanCalculationSessionNumberSequenceCode</a>

First included in: MasterPlanning/ReqForecastPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastPlanCalculationSessionNumberSequenceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequirementDateDeductedSafetyIssueMarginDays name="RequirementDateDeductedSafetyIssueMarginDays">RequirementDateDeductedSafetyIssueMarginDays</a>

First included in: MasterPlanning/ReqForecastPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequirementDateDeductedSafetyIssueMarginDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequirementDateAddedSafetyReceiptMarginDays name="RequirementDateAddedSafetyReceiptMarginDays">RequirementDateAddedSafetyReceiptMarginDays</a>

First included in: MasterPlanning/ReqForecastPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequirementDateAddedSafetyReceiptMarginDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemLeadTimeAddedReorderMarginDays name="ItemLeadTimeAddedReorderMarginDays">ItemLeadTimeAddedReorderMarginDays</a>

First included in: MasterPlanning/ReqForecastPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemLeadTimeAddedReorderMarginDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CapacitySchedulingTimeFenceDays name="CapacitySchedulingTimeFenceDays">CapacitySchedulingTimeFenceDays</a>

First included in: MasterPlanning/ReqForecastPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CapacitySchedulingTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CoverageTimeFenceDays name="CoverageTimeFenceDays">CoverageTimeFenceDays</a>

First included in: MasterPlanning/ReqForecastPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CoverageTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOMOrFormulaExplosionTimeFenceDays name="BOMOrFormulaExplosionTimeFenceDays">BOMOrFormulaExplosionTimeFenceDays</a>

First included in: MasterPlanning/ReqForecastPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOMOrFormulaExplosionTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_ReqPlanForecastRelationshipId name="BackingTable_ReqPlanForecastRelationshipId">BackingTable_ReqPlanForecastRelationshipId</a>

First included in: MasterPlanning/ReqForecastPlanEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ReqPlanForecastRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/MasterPlanning/Group/ReqPlanForecast.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Group/ReqPlanForecast.cdm.json/ReqPlanForecast</a></td><td><a href="../../../Tables/SupplyChain/MasterPlanning/Group/ReqPlanForecast.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: MasterPlanning/ReqForecastPlanEntity (this entity)  

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
