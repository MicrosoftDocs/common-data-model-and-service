---
title: WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity in WMS - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# Warehouse mobile device menu item work confirmation in WMS(WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Warehouse mobile device menu item work confirmation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[WarehouseMobileDeviceMenuItemId](#WarehouseMobileDeviceMenuItemId)||<a href="WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity</a>|
|[WorkType](#WorkType)||<a href="WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity</a>|
|[IsAutoConfirmUsed](#IsAutoConfirmUsed)||<a href="WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity</a>|
|[IsWarehouseLocationConfirmationUsed](#IsWarehouseLocationConfirmationUsed)||<a href="WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity</a>|
|[IsQuantityConfirmationUsed](#IsQuantityConfirmationUsed)||<a href="WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity</a>|
|[IsProductConfirmationUsed](#IsProductConfirmationUsed)||<a href="WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity</a>|
|[IsPieceByPieceConfirmationUsed](#IsPieceByPieceConfirmationUsed)||<a href="WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity</a>|
|[MaximumPieceConfirmation](#MaximumPieceConfirmation)||<a href="WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity</a>|
|[IsBatchConfirmationUsed](#IsBatchConfirmationUsed)||<a href="WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity</a>|
|[IsLicensePlateConfirmationUsed](#IsLicensePlateConfirmationUsed)||<a href="WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity</a>|
|[IsPickDetailsConfirmationShown](#IsPickDetailsConfirmationShown)||<a href="WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity</a>|
|[Relationship_WarehouseMobileDeviceMenuItemV3RelationshipId](#Relationship_WarehouseMobileDeviceMenuItemV3RelationshipId)||<a href="WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity</a>|
|[BackingTable_WHSRFAutoConfirmRelationshipId](#BackingTable_WHSRFAutoConfirmRelationshipId)||<a href="WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity.md" target="_blank">WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity</a>|

### <a href=#WarehouseMobileDeviceMenuItemId name="WarehouseMobileDeviceMenuItemId">WarehouseMobileDeviceMenuItemId</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseMobileDeviceMenuItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkType name="WorkType">WorkType</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAutoConfirmUsed name="IsAutoConfirmUsed">IsAutoConfirmUsed</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAutoConfirmUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWarehouseLocationConfirmationUsed name="IsWarehouseLocationConfirmationUsed">IsWarehouseLocationConfirmationUsed</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWarehouseLocationConfirmationUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuantityConfirmationUsed name="IsQuantityConfirmationUsed">IsQuantityConfirmationUsed</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuantityConfirmationUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductConfirmationUsed name="IsProductConfirmationUsed">IsProductConfirmationUsed</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductConfirmationUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPieceByPieceConfirmationUsed name="IsPieceByPieceConfirmationUsed">IsPieceByPieceConfirmationUsed</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPieceByPieceConfirmationUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumPieceConfirmation name="MaximumPieceConfirmation">MaximumPieceConfirmation</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumPieceConfirmation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBatchConfirmationUsed name="IsBatchConfirmationUsed">IsBatchConfirmationUsed</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBatchConfirmationUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLicensePlateConfirmationUsed name="IsLicensePlateConfirmationUsed">IsLicensePlateConfirmationUsed</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLicensePlateConfirmationUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPickDetailsConfirmationShown name="IsPickDetailsConfirmationShown">IsPickDetailsConfirmationShown</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPickDetailsConfirmationShown attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WarehouseMobileDeviceMenuItemV3RelationshipId name="Relationship_WarehouseMobileDeviceMenuItemV3RelationshipId">Relationship_WarehouseMobileDeviceMenuItemV3RelationshipId</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseMobileDeviceMenuItemV3RelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_WHSRFAutoConfirmRelationshipId name="BackingTable_WHSRFAutoConfirmRelationshipId">BackingTable_WHSRFAutoConfirmRelationshipId</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSRFAutoConfirmRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSRFAutoConfirm.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSRFAutoConfirm.cdm.json/WHSRFAutoConfirm</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSRFAutoConfirm.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WHSWarehouseMobileDeviceMenuItemWorkConfirmationEntity (this entity)  

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
