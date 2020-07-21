---
title: CostCalculationGroupEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Calculation groups in InventoryAndWarehouseManagement(CostCalculationGroupEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/CostCalculationGroupEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Calculation groups</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[GroupId](#GroupId)||<a href="CostCalculationGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostCalculationGroupEntity</a>|
|[GroupName](#GroupName)||<a href="CostCalculationGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostCalculationGroupEntity</a>|
|[UnitCostCalculationMethod](#UnitCostCalculationMethod)||<a href="CostCalculationGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostCalculationGroupEntity</a>|
|[AlternativeUnitCostCalculationMethod](#AlternativeUnitCostCalculationMethod)||<a href="CostCalculationGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostCalculationGroupEntity</a>|
|[SalesPriceCalculationMethod](#SalesPriceCalculationMethod)||<a href="CostCalculationGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostCalculationGroupEntity</a>|
|[StopExplosionAtItem](#StopExplosionAtItem)||<a href="CostCalculationGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostCalculationGroupEntity</a>|
|[WillCostCalculationIssueNoActiveAssignedBOMWarning](#WillCostCalculationIssueNoActiveAssignedBOMWarning)||<a href="CostCalculationGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostCalculationGroupEntity</a>|
|[WillCostCalculationIssueNoActiveAssignedRouteWarning](#WillCostCalculationIssueNoActiveAssignedRouteWarning)||<a href="CostCalculationGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostCalculationGroupEntity</a>|
|[WillCostCalculationIssueZeroConsumptionWarning](#WillCostCalculationIssueZeroConsumptionWarning)||<a href="CostCalculationGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostCalculationGroupEntity</a>|
|[WillCostCalulationIssueOperationsResourceRequirementNotMetWarning](#WillCostCalulationIssueOperationsResourceRequirementNotMetWarning)||<a href="CostCalculationGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostCalculationGroupEntity</a>|
|[WillCostCalulationIssueZeroCostPriceWarning](#WillCostCalulationIssueZeroCostPriceWarning)||<a href="CostCalculationGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostCalculationGroupEntity</a>|
|[ShowWarningIfCostPriceCalculationOlderThanDays](#ShowWarningIfCostPriceCalculationOlderThanDays)||<a href="CostCalculationGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostCalculationGroupEntity</a>|
|[ShowWarningIfContributionMarginPercentageLowerThan](#ShowWarningIfContributionMarginPercentageLowerThan)||<a href="CostCalculationGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostCalculationGroupEntity</a>|
|[BackingTable_BOMCalcGroupRelationshipId](#BackingTable_BOMCalcGroupRelationshipId)||<a href="CostCalculationGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostCalculationGroupEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="CostCalculationGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/CostCalculationGroupEntity</a>|

### <a href=#GroupId name="GroupId">GroupId</a>

First included in: InventoryAndWarehouseManagement/CostCalculationGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupName name="GroupName">GroupName</a>

First included in: InventoryAndWarehouseManagement/CostCalculationGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitCostCalculationMethod name="UnitCostCalculationMethod">UnitCostCalculationMethod</a>

First included in: InventoryAndWarehouseManagement/CostCalculationGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitCostCalculationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AlternativeUnitCostCalculationMethod name="AlternativeUnitCostCalculationMethod">AlternativeUnitCostCalculationMethod</a>

First included in: InventoryAndWarehouseManagement/CostCalculationGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlternativeUnitCostCalculationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPriceCalculationMethod name="SalesPriceCalculationMethod">SalesPriceCalculationMethod</a>

First included in: InventoryAndWarehouseManagement/CostCalculationGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceCalculationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StopExplosionAtItem name="StopExplosionAtItem">StopExplosionAtItem</a>

First included in: InventoryAndWarehouseManagement/CostCalculationGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StopExplosionAtItem attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillCostCalculationIssueNoActiveAssignedBOMWarning name="WillCostCalculationIssueNoActiveAssignedBOMWarning">WillCostCalculationIssueNoActiveAssignedBOMWarning</a>

First included in: InventoryAndWarehouseManagement/CostCalculationGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillCostCalculationIssueNoActiveAssignedBOMWarning attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillCostCalculationIssueNoActiveAssignedRouteWarning name="WillCostCalculationIssueNoActiveAssignedRouteWarning">WillCostCalculationIssueNoActiveAssignedRouteWarning</a>

First included in: InventoryAndWarehouseManagement/CostCalculationGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillCostCalculationIssueNoActiveAssignedRouteWarning attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillCostCalculationIssueZeroConsumptionWarning name="WillCostCalculationIssueZeroConsumptionWarning">WillCostCalculationIssueZeroConsumptionWarning</a>

First included in: InventoryAndWarehouseManagement/CostCalculationGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillCostCalculationIssueZeroConsumptionWarning attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillCostCalulationIssueOperationsResourceRequirementNotMetWarning name="WillCostCalulationIssueOperationsResourceRequirementNotMetWarning">WillCostCalulationIssueOperationsResourceRequirementNotMetWarning</a>

First included in: InventoryAndWarehouseManagement/CostCalculationGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillCostCalulationIssueOperationsResourceRequirementNotMetWarning attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillCostCalulationIssueZeroCostPriceWarning name="WillCostCalulationIssueZeroCostPriceWarning">WillCostCalulationIssueZeroCostPriceWarning</a>

First included in: InventoryAndWarehouseManagement/CostCalculationGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillCostCalulationIssueZeroCostPriceWarning attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowWarningIfCostPriceCalculationOlderThanDays name="ShowWarningIfCostPriceCalculationOlderThanDays">ShowWarningIfCostPriceCalculationOlderThanDays</a>

First included in: InventoryAndWarehouseManagement/CostCalculationGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowWarningIfCostPriceCalculationOlderThanDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowWarningIfContributionMarginPercentageLowerThan name="ShowWarningIfContributionMarginPercentageLowerThan">ShowWarningIfContributionMarginPercentageLowerThan</a>

First included in: InventoryAndWarehouseManagement/CostCalculationGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowWarningIfContributionMarginPercentageLowerThan attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_BOMCalcGroupRelationshipId name="BackingTable_BOMCalcGroupRelationshipId">BackingTable_BOMCalcGroupRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostCalculationGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BOMCalcGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Group/BOMCalcGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/BOMCalcGroup.cdm.json/BOMCalcGroup</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Group/BOMCalcGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostCalculationGroupEntity (this entity)  

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
