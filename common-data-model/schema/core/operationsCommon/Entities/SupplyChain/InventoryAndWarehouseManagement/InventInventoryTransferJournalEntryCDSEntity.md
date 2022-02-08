---
title: InventInventoryTransferJournalEntryCDSEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# CDS inventory transfer journal headers and lines in InventoryAndWarehouseManagement(InventInventoryTransferJournalEntryCDSEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CDS inventory transfer journal headers and lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[JournalNameId](#JournalNameId)||<a href="InventInventoryTransferJournalEntryCDSEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity</a>|
|[JournalNumber](#JournalNumber)||<a href="InventInventoryTransferJournalEntryCDSEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity</a>|
|[LineNumber](#LineNumber)||<a href="InventInventoryTransferJournalEntryCDSEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity</a>|
|[ProductNumber](#ProductNumber)||<a href="InventInventoryTransferJournalEntryCDSEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="InventInventoryTransferJournalEntryCDSEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity</a>|
|[InventoryQuantity](#InventoryQuantity)||<a href="InventInventoryTransferJournalEntryCDSEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity</a>|
|[SourceInventorySiteId](#SourceInventorySiteId)||<a href="InventInventoryTransferJournalEntryCDSEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity</a>|
|[SourceWarehouseId](#SourceWarehouseId)||<a href="InventInventoryTransferJournalEntryCDSEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity</a>|
|[SourceProductSizeId](#SourceProductSizeId)||<a href="InventInventoryTransferJournalEntryCDSEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity</a>|
|[SourceProductStyleId](#SourceProductStyleId)||<a href="InventInventoryTransferJournalEntryCDSEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity</a>|
|[SourceProductVersionId](#SourceProductVersionId)||<a href="InventInventoryTransferJournalEntryCDSEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity</a>|
|[SourceProductColorId](#SourceProductColorId)||<a href="InventInventoryTransferJournalEntryCDSEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity</a>|
|[SourceProductConfigurationId](#SourceProductConfigurationId)||<a href="InventInventoryTransferJournalEntryCDSEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity</a>|
|[DestinationWarehouseId](#DestinationWarehouseId)||<a href="InventInventoryTransferJournalEntryCDSEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity</a>|
|[DestinationInventorySiteId](#DestinationInventorySiteId)||<a href="InventInventoryTransferJournalEntryCDSEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity</a>|
|[DestinationProductStyleId](#DestinationProductStyleId)||<a href="InventInventoryTransferJournalEntryCDSEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity</a>|
|[DestinationProductVersionId](#DestinationProductVersionId)||<a href="InventInventoryTransferJournalEntryCDSEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity</a>|
|[DestinationProductSizeId](#DestinationProductSizeId)||<a href="InventInventoryTransferJournalEntryCDSEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity</a>|
|[DestinationProductColorId](#DestinationProductColorId)||<a href="InventInventoryTransferJournalEntryCDSEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity</a>|
|[DestinationProductConfigurationId](#DestinationProductConfigurationId)||<a href="InventInventoryTransferJournalEntryCDSEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity</a>|
|[DefaultLedgerDimensionDisplayValue](#DefaultLedgerDimensionDisplayValue)||<a href="InventInventoryTransferJournalEntryCDSEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity</a>|
|[DefaultLedgerDimension](#DefaultLedgerDimension)||<a href="InventInventoryTransferJournalEntryCDSEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity</a>|
|[BackingTable_InventJournalTransRelationshipId](#BackingTable_InventJournalTransRelationshipId)||<a href="InventInventoryTransferJournalEntryCDSEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventInventoryTransferJournalEntryCDSEntity.md" target="_blank">InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity</a>|

### <a href=#JournalNameId name="JournalNameId">JournalNameId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalNumber name="JournalNumber">JournalNumber</a>

First included in: InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductNumber name="ProductNumber">ProductNumber</a>

First included in: InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity (this entity)  

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

### <a href=#InventoryQuantity name="InventoryQuantity">InventoryQuantity</a>

First included in: InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceInventorySiteId name="SourceInventorySiteId">SourceInventorySiteId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceInventorySiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceWarehouseId name="SourceWarehouseId">SourceWarehouseId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceProductSizeId name="SourceProductSizeId">SourceProductSizeId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceProductStyleId name="SourceProductStyleId">SourceProductStyleId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceProductVersionId name="SourceProductVersionId">SourceProductVersionId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceProductVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceProductColorId name="SourceProductColorId">SourceProductColorId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceProductConfigurationId name="SourceProductConfigurationId">SourceProductConfigurationId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationWarehouseId name="DestinationWarehouseId">DestinationWarehouseId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationInventorySiteId name="DestinationInventorySiteId">DestinationInventorySiteId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationInventorySiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationProductStyleId name="DestinationProductStyleId">DestinationProductStyleId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationProductVersionId name="DestinationProductVersionId">DestinationProductVersionId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationProductVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationProductSizeId name="DestinationProductSizeId">DestinationProductSizeId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationProductColorId name="DestinationProductColorId">DestinationProductColorId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationProductConfigurationId name="DestinationProductConfigurationId">DestinationProductConfigurationId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLedgerDimensionDisplayValue name="DefaultLedgerDimensionDisplayValue">DefaultLedgerDimensionDisplayValue</a>

First included in: InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLedgerDimension name="DefaultLedgerDimension">DefaultLedgerDimension</a>

First included in: InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity (this entity)  

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

### <a href=#BackingTable_InventJournalTransRelationshipId name="BackingTable_InventJournalTransRelationshipId">BackingTable_InventJournalTransRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventJournalTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetLine/InventJournalTrans.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetLine/InventJournalTrans.cdm.json/InventJournalTrans</a></td><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetLine/InventJournalTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventInventoryTransferJournalEntryCDSEntity (this entity)  

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
