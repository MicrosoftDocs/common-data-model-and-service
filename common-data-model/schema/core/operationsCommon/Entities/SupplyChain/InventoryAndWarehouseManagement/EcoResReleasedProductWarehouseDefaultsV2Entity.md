---
title: EcoResReleasedProductWarehouseDefaultsV2Entity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Released product warehouse defaults V2 in InventoryAndWarehouseManagement(EcoResReleasedProductWarehouseDefaultsV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Released product warehouse defaults V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ItemNumber](#ItemNumber)||<a href="EcoResReleasedProductWarehouseDefaultsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity</a>|
|[ProductColorId](#ProductColorId)||<a href="EcoResReleasedProductWarehouseDefaultsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="EcoResReleasedProductWarehouseDefaultsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="EcoResReleasedProductWarehouseDefaultsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="EcoResReleasedProductWarehouseDefaultsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="EcoResReleasedProductWarehouseDefaultsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity</a>|
|[ProductWarehouseId](#ProductWarehouseId)||<a href="EcoResReleasedProductWarehouseDefaultsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity</a>|
|[CountingGroupId](#CountingGroupId)||<a href="EcoResReleasedProductWarehouseDefaultsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity</a>|
|[DefaultIssueWarehouseLocationId](#DefaultIssueWarehouseLocationId)||<a href="EcoResReleasedProductWarehouseDefaultsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity</a>|
|[DefaultReceiptWarehouseLocationId](#DefaultReceiptWarehouseLocationId)||<a href="EcoResReleasedProductWarehouseDefaultsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity</a>|
|[PickingWarehouseLocationId](#PickingWarehouseLocationId)||<a href="EcoResReleasedProductWarehouseDefaultsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity</a>|
|[CountingJournalNumber](#CountingJournalNumber)||<a href="EcoResReleasedProductWarehouseDefaultsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity</a>|
|[IsCountingStarted](#IsCountingStarted)||<a href="EcoResReleasedProductWarehouseDefaultsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity</a>|
|[Relationship_InventoryCountingGroupRelationshipId](#Relationship_InventoryCountingGroupRelationshipId)||<a href="EcoResReleasedProductWarehouseDefaultsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity</a>|
|[Relationship_ProductConfigurationRelationshipId](#Relationship_ProductConfigurationRelationshipId)||<a href="EcoResReleasedProductWarehouseDefaultsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity</a>|
|[Relationship_ProductColorRelationshipId](#Relationship_ProductColorRelationshipId)||<a href="EcoResReleasedProductWarehouseDefaultsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity</a>|
|[Relationship_ProductSizeRelationshipId](#Relationship_ProductSizeRelationshipId)||<a href="EcoResReleasedProductWarehouseDefaultsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity</a>|
|[Relationship_ProductStyleRelationshipId](#Relationship_ProductStyleRelationshipId)||<a href="EcoResReleasedProductWarehouseDefaultsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity</a>|
|[Relationship_ProductVersionRelationshipId](#Relationship_ProductVersionRelationshipId)||<a href="EcoResReleasedProductWarehouseDefaultsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity</a>|
|[Relationship_ReleasedProductRelationshipId](#Relationship_ReleasedProductRelationshipId)||<a href="EcoResReleasedProductWarehouseDefaultsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity</a>|
|[Relationship_DefaultIssueWarehouseLocationRelationshipId](#Relationship_DefaultIssueWarehouseLocationRelationshipId)||<a href="EcoResReleasedProductWarehouseDefaultsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity</a>|
|[Relationship_DefaultReceiptWarehouseLocationRelationshipId](#Relationship_DefaultReceiptWarehouseLocationRelationshipId)||<a href="EcoResReleasedProductWarehouseDefaultsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity</a>|
|[Relationship_PickingWarehouseLocationRelationshipId](#Relationship_PickingWarehouseLocationRelationshipId)||<a href="EcoResReleasedProductWarehouseDefaultsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity</a>|
|[Relationship_InventoryCountingJournalHeaderRelationshipId](#Relationship_InventoryCountingJournalHeaderRelationshipId)||<a href="EcoResReleasedProductWarehouseDefaultsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity</a>|
|[Relationship_ProductWarehouseRelationshipId](#Relationship_ProductWarehouseRelationshipId)||<a href="EcoResReleasedProductWarehouseDefaultsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity</a>|
|[BackingTable_InventItemLocationRelationshipId](#BackingTable_InventItemLocationRelationshipId)||<a href="EcoResReleasedProductWarehouseDefaultsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="EcoResReleasedProductWarehouseDefaultsV2Entity.md" target="_blank">InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity</a>|

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVersionId name="ProductVersionId">ProductVersionId</a>

First included in: InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductWarehouseId name="ProductWarehouseId">ProductWarehouseId</a>

First included in: InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountingGroupId name="CountingGroupId">CountingGroupId</a>

First included in: InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountingGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultIssueWarehouseLocationId name="DefaultIssueWarehouseLocationId">DefaultIssueWarehouseLocationId</a>

First included in: InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultIssueWarehouseLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultReceiptWarehouseLocationId name="DefaultReceiptWarehouseLocationId">DefaultReceiptWarehouseLocationId</a>

First included in: InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultReceiptWarehouseLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PickingWarehouseLocationId name="PickingWarehouseLocationId">PickingWarehouseLocationId</a>

First included in: InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PickingWarehouseLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountingJournalNumber name="CountingJournalNumber">CountingJournalNumber</a>

First included in: InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountingJournalNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCountingStarted name="IsCountingStarted">IsCountingStarted</a>

First included in: InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCountingStarted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventoryCountingGroupRelationshipId name="Relationship_InventoryCountingGroupRelationshipId">Relationship_InventoryCountingGroupRelationshipId</a>

First included in: InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventoryCountingGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductConfigurationRelationshipId name="Relationship_ProductConfigurationRelationshipId">Relationship_ProductConfigurationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductConfigurationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductColorRelationshipId name="Relationship_ProductColorRelationshipId">Relationship_ProductColorRelationshipId</a>

First included in: InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductColorRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductSizeRelationshipId name="Relationship_ProductSizeRelationshipId">Relationship_ProductSizeRelationshipId</a>

First included in: InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductSizeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductStyleRelationshipId name="Relationship_ProductStyleRelationshipId">Relationship_ProductStyleRelationshipId</a>

First included in: InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductStyleRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductVersionRelationshipId name="Relationship_ProductVersionRelationshipId">Relationship_ProductVersionRelationshipId</a>

First included in: InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductVersionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReleasedProductRelationshipId name="Relationship_ReleasedProductRelationshipId">Relationship_ReleasedProductRelationshipId</a>

First included in: InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReleasedProductRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultIssueWarehouseLocationRelationshipId name="Relationship_DefaultIssueWarehouseLocationRelationshipId">Relationship_DefaultIssueWarehouseLocationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultIssueWarehouseLocationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultReceiptWarehouseLocationRelationshipId name="Relationship_DefaultReceiptWarehouseLocationRelationshipId">Relationship_DefaultReceiptWarehouseLocationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultReceiptWarehouseLocationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PickingWarehouseLocationRelationshipId name="Relationship_PickingWarehouseLocationRelationshipId">Relationship_PickingWarehouseLocationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PickingWarehouseLocationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_InventoryCountingJournalHeaderRelationshipId name="Relationship_InventoryCountingJournalHeaderRelationshipId">Relationship_InventoryCountingJournalHeaderRelationshipId</a>

First included in: InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventoryCountingJournalHeaderRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductWarehouseRelationshipId name="Relationship_ProductWarehouseRelationshipId">Relationship_ProductWarehouseRelationshipId</a>

First included in: InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductWarehouseRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_InventItemLocationRelationshipId name="BackingTable_InventItemLocationRelationshipId">BackingTable_InventItemLocationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventItemLocationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/InventItemLocation.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/InventItemLocation.cdm.json/InventItemLocation</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/InventItemLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/EcoResReleasedProductWarehouseDefaultsV2Entity (this entity)  

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
