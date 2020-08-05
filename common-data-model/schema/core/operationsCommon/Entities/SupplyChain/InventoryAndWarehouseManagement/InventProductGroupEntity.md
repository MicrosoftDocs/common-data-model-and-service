---
title: InventProductGroupEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Item groups in InventoryAndWarehouseManagement(InventProductGroupEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventProductGroupEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item groups</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[GroupId](#GroupId)||<a href="InventProductGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductGroupEntity</a>|
|[GroupName](#GroupName)||<a href="InventProductGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductGroupEntity</a>|
|[DefaultForecastAllocationKeyId](#DefaultForecastAllocationKeyId)||<a href="InventProductGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductGroupEntity</a>|
|[DefaultSalesSalesTaxItemGroupCode](#DefaultSalesSalesTaxItemGroupCode)||<a href="InventProductGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductGroupEntity</a>|
|[DefaultPurchaseSalesTaxItemGroupCode](#DefaultPurchaseSalesTaxItemGroupCode)||<a href="InventProductGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductGroupEntity</a>|
|[ShipmentPhysicalLoadTemplateId](#ShipmentPhysicalLoadTemplateId)||<a href="InventProductGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductGroupEntity</a>|
|[IsWarehouseFilterCodeRequired](#IsWarehouseFilterCodeRequired)||<a href="InventProductGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductGroupEntity</a>|
|[IsFilterCodeDeterminingWarehouseFilterGroup](#IsFilterCodeDeterminingWarehouseFilterGroup)||<a href="InventProductGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductGroupEntity</a>|
|[RevRecDefaultRevenueRecognitionSchedule](#RevRecDefaultRevenueRecognitionSchedule)||<a href="InventProductGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductGroupEntity</a>|
|[RevRecExcludeFromCarveOut](#RevRecExcludeFromCarveOut)||<a href="InventProductGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductGroupEntity</a>|
|[RevRecMedianPrice](#RevRecMedianPrice)||<a href="InventProductGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductGroupEntity</a>|
|[RevRecMedianPriceMaximumTolerance](#RevRecMedianPriceMaximumTolerance)||<a href="InventProductGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductGroupEntity</a>|
|[RevRecMedianPriceMinimumTolerance](#RevRecMedianPriceMinimumTolerance)||<a href="InventProductGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductGroupEntity</a>|
|[RevRecRevenueRecognitionEnabled](#RevRecRevenueRecognitionEnabled)||<a href="InventProductGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductGroupEntity</a>|
|[RevRecRevenueType](#RevRecRevenueType)||<a href="InventProductGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductGroupEntity</a>|
|[BackingTable_InventItemGroupRelationshipId](#BackingTable_InventItemGroupRelationshipId)||<a href="InventProductGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductGroupEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventProductGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventProductGroupEntity</a>|

### <a href=#GroupId name="GroupId">GroupId</a>

First included in: InventoryAndWarehouseManagement/InventProductGroupEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventProductGroupEntity (this entity)  

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

### <a href=#DefaultForecastAllocationKeyId name="DefaultForecastAllocationKeyId">DefaultForecastAllocationKeyId</a>

First included in: InventoryAndWarehouseManagement/InventProductGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultForecastAllocationKeyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultSalesSalesTaxItemGroupCode name="DefaultSalesSalesTaxItemGroupCode">DefaultSalesSalesTaxItemGroupCode</a>

First included in: InventoryAndWarehouseManagement/InventProductGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultSalesSalesTaxItemGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultPurchaseSalesTaxItemGroupCode name="DefaultPurchaseSalesTaxItemGroupCode">DefaultPurchaseSalesTaxItemGroupCode</a>

First included in: InventoryAndWarehouseManagement/InventProductGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultPurchaseSalesTaxItemGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShipmentPhysicalLoadTemplateId name="ShipmentPhysicalLoadTemplateId">ShipmentPhysicalLoadTemplateId</a>

First included in: InventoryAndWarehouseManagement/InventProductGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipmentPhysicalLoadTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWarehouseFilterCodeRequired name="IsWarehouseFilterCodeRequired">IsWarehouseFilterCodeRequired</a>

First included in: InventoryAndWarehouseManagement/InventProductGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWarehouseFilterCodeRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFilterCodeDeterminingWarehouseFilterGroup name="IsFilterCodeDeterminingWarehouseFilterGroup">IsFilterCodeDeterminingWarehouseFilterGroup</a>

First included in: InventoryAndWarehouseManagement/InventProductGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFilterCodeDeterminingWarehouseFilterGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevRecDefaultRevenueRecognitionSchedule name="RevRecDefaultRevenueRecognitionSchedule">RevRecDefaultRevenueRecognitionSchedule</a>

First included in: InventoryAndWarehouseManagement/InventProductGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecDefaultRevenueRecognitionSchedule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevRecExcludeFromCarveOut name="RevRecExcludeFromCarveOut">RevRecExcludeFromCarveOut</a>

First included in: InventoryAndWarehouseManagement/InventProductGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecExcludeFromCarveOut attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevRecMedianPrice name="RevRecMedianPrice">RevRecMedianPrice</a>

First included in: InventoryAndWarehouseManagement/InventProductGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecMedianPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevRecMedianPriceMaximumTolerance name="RevRecMedianPriceMaximumTolerance">RevRecMedianPriceMaximumTolerance</a>

First included in: InventoryAndWarehouseManagement/InventProductGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecMedianPriceMaximumTolerance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevRecMedianPriceMinimumTolerance name="RevRecMedianPriceMinimumTolerance">RevRecMedianPriceMinimumTolerance</a>

First included in: InventoryAndWarehouseManagement/InventProductGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecMedianPriceMinimumTolerance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevRecRevenueRecognitionEnabled name="RevRecRevenueRecognitionEnabled">RevRecRevenueRecognitionEnabled</a>

First included in: InventoryAndWarehouseManagement/InventProductGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecRevenueRecognitionEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevRecRevenueType name="RevRecRevenueType">RevRecRevenueType</a>

First included in: InventoryAndWarehouseManagement/InventProductGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecRevenueType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_InventItemGroupRelationshipId name="BackingTable_InventItemGroupRelationshipId">BackingTable_InventItemGroupRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventProductGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventItemGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Group/InventItemGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventItemGroup.cdm.json/InventItemGroup</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Group/InventItemGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventProductGroupEntity (this entity)  

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
