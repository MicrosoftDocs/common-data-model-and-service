---
title: InventQualitySamplingEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# Item sampling in InventoryAndWarehouseManagement(InventQualitySamplingEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventQualitySamplingEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item sampling</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[SamplingId](#SamplingId)||<a href="InventQualitySamplingEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualitySamplingEntity</a>|
|[SamplingDescription](#SamplingDescription)||<a href="InventQualitySamplingEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualitySamplingEntity</a>|
|[FixedInventoryQuantity](#FixedInventoryQuantity)||<a href="InventQualitySamplingEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualitySamplingEntity</a>|
|[QuantityPercentage](#QuantityPercentage)||<a href="InventQualitySamplingEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualitySamplingEntity</a>|
|[WillQualityOrderFullyBlockOrderLineQuantity](#WillQualityOrderFullyBlockOrderLineQuantity)||<a href="InventQualitySamplingEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualitySamplingEntity</a>|
|[WillEveryInventoryUpdateCreateQualityOrder](#WillEveryInventoryUpdateCreateQualityOrder)||<a href="InventQualitySamplingEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualitySamplingEntity</a>|
|[IsQualityOrderWarehouseSpecific](#IsQualityOrderWarehouseSpecific)||<a href="InventQualitySamplingEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualitySamplingEntity</a>|
|[IsQualityOrderInventoryStatusSpecific](#IsQualityOrderInventoryStatusSpecific)||<a href="InventQualitySamplingEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualitySamplingEntity</a>|
|[IsQualityOrderWarehouseLocationSpecific](#IsQualityOrderWarehouseLocationSpecific)||<a href="InventQualitySamplingEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualitySamplingEntity</a>|
|[IsQualityOrderBatchNumberSpecific](#IsQualityOrderBatchNumberSpecific)||<a href="InventQualitySamplingEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualitySamplingEntity</a>|
|[IsQualityOrderSerialNumberSpecific](#IsQualityOrderSerialNumberSpecific)||<a href="InventQualitySamplingEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualitySamplingEntity</a>|
|[TestQtySpecification](#TestQtySpecification)||<a href="InventQualitySamplingEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualitySamplingEntity</a>|
|[ItemSamplingValue](#ItemSamplingValue)||<a href="InventQualitySamplingEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualitySamplingEntity</a>|
|[DiscriminatingInventoryDimensions](#DiscriminatingInventoryDimensions)||<a href="InventQualitySamplingEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualitySamplingEntity</a>|
|[BackingTable_InventItemSamplingRelationshipId](#BackingTable_InventItemSamplingRelationshipId)||<a href="InventQualitySamplingEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualitySamplingEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventQualitySamplingEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualitySamplingEntity</a>|

### <a href=#SamplingId name="SamplingId">SamplingId</a>

First included in: InventoryAndWarehouseManagement/InventQualitySamplingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SamplingId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SamplingDescription name="SamplingDescription">SamplingDescription</a>

First included in: InventoryAndWarehouseManagement/InventQualitySamplingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SamplingDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedInventoryQuantity name="FixedInventoryQuantity">FixedInventoryQuantity</a>

First included in: InventoryAndWarehouseManagement/InventQualitySamplingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedInventoryQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuantityPercentage name="QuantityPercentage">QuantityPercentage</a>

First included in: InventoryAndWarehouseManagement/InventQualitySamplingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuantityPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillQualityOrderFullyBlockOrderLineQuantity name="WillQualityOrderFullyBlockOrderLineQuantity">WillQualityOrderFullyBlockOrderLineQuantity</a>

First included in: InventoryAndWarehouseManagement/InventQualitySamplingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillQualityOrderFullyBlockOrderLineQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillEveryInventoryUpdateCreateQualityOrder name="WillEveryInventoryUpdateCreateQualityOrder">WillEveryInventoryUpdateCreateQualityOrder</a>

First included in: InventoryAndWarehouseManagement/InventQualitySamplingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillEveryInventoryUpdateCreateQualityOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQualityOrderWarehouseSpecific name="IsQualityOrderWarehouseSpecific">IsQualityOrderWarehouseSpecific</a>

First included in: InventoryAndWarehouseManagement/InventQualitySamplingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQualityOrderWarehouseSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQualityOrderInventoryStatusSpecific name="IsQualityOrderInventoryStatusSpecific">IsQualityOrderInventoryStatusSpecific</a>

First included in: InventoryAndWarehouseManagement/InventQualitySamplingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQualityOrderInventoryStatusSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQualityOrderWarehouseLocationSpecific name="IsQualityOrderWarehouseLocationSpecific">IsQualityOrderWarehouseLocationSpecific</a>

First included in: InventoryAndWarehouseManagement/InventQualitySamplingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQualityOrderWarehouseLocationSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQualityOrderBatchNumberSpecific name="IsQualityOrderBatchNumberSpecific">IsQualityOrderBatchNumberSpecific</a>

First included in: InventoryAndWarehouseManagement/InventQualitySamplingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQualityOrderBatchNumberSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQualityOrderSerialNumberSpecific name="IsQualityOrderSerialNumberSpecific">IsQualityOrderSerialNumberSpecific</a>

First included in: InventoryAndWarehouseManagement/InventQualitySamplingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQualityOrderSerialNumberSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TestQtySpecification name="TestQtySpecification">TestQtySpecification</a>

First included in: InventoryAndWarehouseManagement/InventQualitySamplingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TestQtySpecification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSamplingValue name="ItemSamplingValue">ItemSamplingValue</a>

First included in: InventoryAndWarehouseManagement/InventQualitySamplingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSamplingValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscriminatingInventoryDimensions name="DiscriminatingInventoryDimensions">DiscriminatingInventoryDimensions</a>

First included in: InventoryAndWarehouseManagement/InventQualitySamplingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscriminatingInventoryDimensions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_InventItemSamplingRelationshipId name="BackingTable_InventItemSamplingRelationshipId">BackingTable_InventItemSamplingRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventQualitySamplingEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventItemSamplingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Group/InventItemSampling.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventItemSampling.cdm.json/InventItemSampling</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Group/InventItemSampling.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventQualitySamplingEntity (this entity)  

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
