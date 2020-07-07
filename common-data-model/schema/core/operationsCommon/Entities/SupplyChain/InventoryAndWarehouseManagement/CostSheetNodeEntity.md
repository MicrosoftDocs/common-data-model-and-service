---
title: CostSheetNodeEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Costing sheet nodes and absorption basis in InventoryAndWarehouseManagement

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/CostSheetNodeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Costing sheet nodes and absorption basis</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IsCalculationFactorSpecifiedPerItem](#IsCalculationFactorSpecifiedPerItem)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[RateNodeSubtype](#RateNodeSubtype)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[SurchargeNodeSubtype](#SurchargeNodeSubtype)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[UnitBasedNodeSubtype](#UnitBasedNodeSubtype)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[NodeName](#NodeName)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[CostGroupId](#CostGroupId)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[DefaultLedgerDimension](#DefaultLedgerDimension)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[NodeDescription](#NodeDescription)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[EstimatedIndirectAbsorptionMainAccountId](#EstimatedIndirectAbsorptionMainAccountId)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[EstimatedIndirectAbsorptionOffsetMainAccountId](#EstimatedIndirectAbsorptionOffsetMainAccountId)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[IsNodeShownAsHeader](#IsNodeShownAsHeader)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[IndirectAbsorptionMainAccountId](#IndirectAbsorptionMainAccountId)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[IndirectAbsorptionOffsetMainAccountId](#IndirectAbsorptionOffsetMainAccountId)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[PriceNodeSubtype](#PriceNodeSubtype)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[IsNodeShownAsTotalLine](#IsNodeShownAsTotalLine)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[NodeType](#NodeType)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[DefaultLedgerDimensionDisplayValue](#DefaultLedgerDimensionDisplayValue)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[EstimatedIndirectAbsorptionMainAccountIdDisplayValue](#EstimatedIndirectAbsorptionMainAccountIdDisplayValue)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[EstimatedIndirectAbsorptionOffsetMainAccountIdDisplayValue](#EstimatedIndirectAbsorptionOffsetMainAccountIdDisplayValue)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[IndirectAbsorptionMainAccountIdDisplayValue](#IndirectAbsorptionMainAccountIdDisplayValue)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[IndirectAbsorptionOffsetMainAccountIdDisplayValue](#IndirectAbsorptionOffsetMainAccountIdDisplayValue)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[ParentNodeName](#ParentNodeName)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[ParentNodeId](#ParentNodeId)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[AbsorptionBasisNodeName](#AbsorptionBasisNodeName)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[SurchargeNodeAbsorptionBasisSubtype](#SurchargeNodeAbsorptionBasisSubtype)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[RateNodeAbsorptionBasisSubtype](#RateNodeAbsorptionBasisSubtype)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[Relationship_EstimatedIndirectAbsorptionMainAccountIdCombinationRelationshipId](#Relationship_EstimatedIndirectAbsorptionMainAccountIdCombinationRelationshipId)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[Relationship_EstimatedIndirectAbsorptionOffsetMainAccountIdCombinationRelationshipId](#Relationship_EstimatedIndirectAbsorptionOffsetMainAccountIdCombinationRelationshipId)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[Relationship_IndirectAbsorptionMainAccountIdCombinationRelationshipId](#Relationship_IndirectAbsorptionMainAccountIdCombinationRelationshipId)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[Relationship_IndirectAbsorptionOffsetMainAccountIdCombinationRelationshipId](#Relationship_IndirectAbsorptionOffsetMainAccountIdCombinationRelationshipId)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[BackingTable_CostSheetNodeTableRelationshipId](#BackingTable_CostSheetNodeTableRelationshipId)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="CostSheetNodeEntity.md" target="_blank">InventoryAndWarehouseManagement/CostSheetNodeEntity</a>|

### <a href=#IsCalculationFactorSpecifiedPerItem name="IsCalculationFactorSpecifiedPerItem">IsCalculationFactorSpecifiedPerItem</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCalculationFactorSpecifiedPerItem attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RateNodeSubtype name="RateNodeSubtype">RateNodeSubtype</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rate subtype</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RateNodeSubtype attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rate subtype</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SurchargeNodeSubtype name="SurchargeNodeSubtype">SurchargeNodeSubtype</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Surcharge subtype</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SurchargeNodeSubtype attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Surcharge subtype</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitBasedNodeSubtype name="UnitBasedNodeSubtype">UnitBasedNodeSubtype</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit based subtype</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitBasedNodeSubtype attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unit based subtype</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NodeName name="NodeName">NodeName</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NodeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostGroupId name="CostGroupId">CostGroupId</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLedgerDimension name="DefaultLedgerDimension">DefaultLedgerDimension</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NodeDescription name="NodeDescription">NodeDescription</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NodeDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedIndirectAbsorptionMainAccountId name="EstimatedIndirectAbsorptionMainAccountId">EstimatedIndirectAbsorptionMainAccountId</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedIndirectAbsorptionMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedIndirectAbsorptionOffsetMainAccountId name="EstimatedIndirectAbsorptionOffsetMainAccountId">EstimatedIndirectAbsorptionOffsetMainAccountId</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedIndirectAbsorptionOffsetMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsNodeShownAsHeader name="IsNodeShownAsHeader">IsNodeShownAsHeader</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsNodeShownAsHeader attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IndirectAbsorptionMainAccountId name="IndirectAbsorptionMainAccountId">IndirectAbsorptionMainAccountId</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IndirectAbsorptionMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IndirectAbsorptionOffsetMainAccountId name="IndirectAbsorptionOffsetMainAccountId">IndirectAbsorptionOffsetMainAccountId</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IndirectAbsorptionOffsetMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceNodeSubtype name="PriceNodeSubtype">PriceNodeSubtype</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price subtype</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceNodeSubtype attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Price subtype</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsNodeShownAsTotalLine name="IsNodeShownAsTotalLine">IsNodeShownAsTotalLine</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsNodeShownAsTotalLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NodeType name="NodeType">NodeType</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NodeType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLedgerDimensionDisplayValue name="DefaultLedgerDimensionDisplayValue">DefaultLedgerDimensionDisplayValue</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default financial dimensions</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default financial dimensions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedIndirectAbsorptionMainAccountIdDisplayValue name="EstimatedIndirectAbsorptionMainAccountIdDisplayValue">EstimatedIndirectAbsorptionMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated indirect cost absorbed</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedIndirectAbsorptionMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Estimated indirect cost absorbed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EstimatedIndirectAbsorptionOffsetMainAccountIdDisplayValue name="EstimatedIndirectAbsorptionOffsetMainAccountIdDisplayValue">EstimatedIndirectAbsorptionOffsetMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated cost of indirect cost consumed, WIP</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimatedIndirectAbsorptionOffsetMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Estimated cost of indirect cost consumed, WIP</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IndirectAbsorptionMainAccountIdDisplayValue name="IndirectAbsorptionMainAccountIdDisplayValue">IndirectAbsorptionMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Indirect cost absorbed</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IndirectAbsorptionMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indirect cost absorbed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IndirectAbsorptionOffsetMainAccountIdDisplayValue name="IndirectAbsorptionOffsetMainAccountIdDisplayValue">IndirectAbsorptionOffsetMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost of indirect cost consumed, WIP</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IndirectAbsorptionOffsetMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cost of indirect cost consumed, WIP</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParentNodeName name="ParentNodeName">ParentNodeName</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentNodeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Parent name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParentNodeId name="ParentNodeId">ParentNodeId</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentNodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AbsorptionBasisNodeName name="AbsorptionBasisNodeName">AbsorptionBasisNodeName</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Basis name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AbsorptionBasisNodeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Basis name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SurchargeNodeAbsorptionBasisSubtype name="SurchargeNodeAbsorptionBasisSubtype">SurchargeNodeAbsorptionBasisSubtype</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Absorption basis surcharge subtype</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SurchargeNodeAbsorptionBasisSubtype attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Absorption basis surcharge subtype</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RateNodeAbsorptionBasisSubtype name="RateNodeAbsorptionBasisSubtype">RateNodeAbsorptionBasisSubtype</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Absorption basis rate subtype</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RateNodeAbsorptionBasisSubtype attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Absorption basis rate subtype</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_EstimatedIndirectAbsorptionMainAccountIdCombinationRelationshipId name="Relationship_EstimatedIndirectAbsorptionMainAccountIdCombinationRelationshipId">Relationship_EstimatedIndirectAbsorptionMainAccountIdCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EstimatedIndirectAbsorptionMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_EstimatedIndirectAbsorptionOffsetMainAccountIdCombinationRelationshipId name="Relationship_EstimatedIndirectAbsorptionOffsetMainAccountIdCombinationRelationshipId">Relationship_EstimatedIndirectAbsorptionOffsetMainAccountIdCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EstimatedIndirectAbsorptionOffsetMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_IndirectAbsorptionMainAccountIdCombinationRelationshipId name="Relationship_IndirectAbsorptionMainAccountIdCombinationRelationshipId">Relationship_IndirectAbsorptionMainAccountIdCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IndirectAbsorptionMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_IndirectAbsorptionOffsetMainAccountIdCombinationRelationshipId name="Relationship_IndirectAbsorptionOffsetMainAccountIdCombinationRelationshipId">Relationship_IndirectAbsorptionOffsetMainAccountIdCombinationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IndirectAbsorptionOffsetMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_CostSheetNodeTableRelationshipId name="BackingTable_CostSheetNodeTableRelationshipId">BackingTable_CostSheetNodeTableRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CostSheetNodeTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/CostSheetNodeTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/CostSheetNodeTable.cdm.json/CostSheetNodeTable</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/CostSheetNodeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostSheetNodeEntity (this entity)  

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
