---
title: HcmBudgetCostElementEntity in HRM - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Budget cost elements in HRM(HcmBudgetCostElementEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/HRM/HcmBudgetCostElementEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget cost elements</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[BudgetCostType](#BudgetCostType)||<a href="HcmBudgetCostElementEntity.md" target="_blank">HRM/HcmBudgetCostElementEntity</a>|
|[Description](#Description)||<a href="HcmBudgetCostElementEntity.md" target="_blank">HRM/HcmBudgetCostElementEntity</a>|
|[ForecastPositionOverride](#ForecastPositionOverride)||<a href="HcmBudgetCostElementEntity.md" target="_blank">HRM/HcmBudgetCostElementEntity</a>|
|[AllocationMethod](#AllocationMethod)||<a href="HcmBudgetCostElementEntity.md" target="_blank">HRM/HcmBudgetCostElementEntity</a>|
|[Percent](#Percent)||<a href="HcmBudgetCostElementEntity.md" target="_blank">HRM/HcmBudgetCostElementEntity</a>|
|[EffectiveDate](#EffectiveDate)||<a href="HcmBudgetCostElementEntity.md" target="_blank">HRM/HcmBudgetCostElementEntity</a>|
|[ExpirationDate](#ExpirationDate)||<a href="HcmBudgetCostElementEntity.md" target="_blank">HRM/HcmBudgetCostElementEntity</a>|
|[AnnualLimit](#AnnualLimit)||<a href="HcmBudgetCostElementEntity.md" target="_blank">HRM/HcmBudgetCostElementEntity</a>|
|[Amount](#Amount)||<a href="HcmBudgetCostElementEntity.md" target="_blank">HRM/HcmBudgetCostElementEntity</a>|
|[CostElementDataAreaId](#CostElementDataAreaId)||<a href="HcmBudgetCostElementEntity.md" target="_blank">HRM/HcmBudgetCostElementEntity</a>|
|[CostElementLedgerDimensionDisplayValue](#CostElementLedgerDimensionDisplayValue)||<a href="HcmBudgetCostElementEntity.md" target="_blank">HRM/HcmBudgetCostElementEntity</a>|
|[CostElementLedgerDimension](#CostElementLedgerDimension)||<a href="HcmBudgetCostElementEntity.md" target="_blank">HRM/HcmBudgetCostElementEntity</a>|
|[CostElementName](#CostElementName)||<a href="HcmBudgetCostElementEntity.md" target="_blank">HRM/HcmBudgetCostElementEntity</a>|
|[BackingTable_HcmBudgetPurposeTypeRelationshipId](#BackingTable_HcmBudgetPurposeTypeRelationshipId)||<a href="HcmBudgetCostElementEntity.md" target="_blank">HRM/HcmBudgetCostElementEntity</a>|

### <a href=#BudgetCostType name="BudgetCostType">BudgetCostType</a>

First included in: HRM/HcmBudgetCostElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetCostType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: HRM/HcmBudgetCostElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastPositionOverride name="ForecastPositionOverride">ForecastPositionOverride</a>

First included in: HRM/HcmBudgetCostElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastPositionOverride attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllocationMethod name="AllocationMethod">AllocationMethod</a>

First included in: HRM/HcmBudgetCostElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllocationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Percent name="Percent">Percent</a>

First included in: HRM/HcmBudgetCostElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Percent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EffectiveDate name="EffectiveDate">EffectiveDate</a>

First included in: HRM/HcmBudgetCostElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EffectiveDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpirationDate name="ExpirationDate">ExpirationDate</a>

First included in: HRM/HcmBudgetCostElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpirationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AnnualLimit name="AnnualLimit">AnnualLimit</a>

First included in: HRM/HcmBudgetCostElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AnnualLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Amount name="Amount">Amount</a>

First included in: HRM/HcmBudgetCostElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Amount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementDataAreaId name="CostElementDataAreaId">CostElementDataAreaId</a>

First included in: HRM/HcmBudgetCostElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementLedgerDimensionDisplayValue name="CostElementLedgerDimensionDisplayValue">CostElementLedgerDimensionDisplayValue</a>

First included in: HRM/HcmBudgetCostElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementLedgerDimension name="CostElementLedgerDimension">CostElementLedgerDimension</a>

First included in: HRM/HcmBudgetCostElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostElementName name="CostElementName">CostElementName</a>

First included in: HRM/HcmBudgetCostElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostElementName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_HcmBudgetPurposeTypeRelationshipId name="BackingTable_HcmBudgetPurposeTypeRelationshipId">BackingTable_HcmBudgetPurposeTypeRelationshipId</a>

First included in: HRM/HcmBudgetCostElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_HcmBudgetPurposeTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Budget/Group/HcmBudgetPurposeType.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/HcmBudgetPurposeType.cdm.json/HcmBudgetPurposeType</a></td><td><a href="../../../Tables/Finance/Budget/Group/HcmBudgetPurposeType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
