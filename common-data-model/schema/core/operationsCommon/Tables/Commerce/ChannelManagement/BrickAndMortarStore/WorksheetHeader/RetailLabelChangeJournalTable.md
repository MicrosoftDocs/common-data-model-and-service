---
title: RetailLabelChangeJournalTable in WorksheetHeader - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Price label journal in WorksheetHeader(RetailLabelChangeJournalTable)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/WorksheetHeader/RetailLabelChangeJournalTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailLabelChangeJournalTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Price label journal</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailLabelChangeJournalTable.md" target="_blank">WorksheetHeader/RetailLabelChangeJournalTable</a>|
|[Active](#Active)||<a href="RetailLabelChangeJournalTable.md" target="_blank">WorksheetHeader/RetailLabelChangeJournalTable</a>|
|[ConfirmDate](#ConfirmDate)||<a href="RetailLabelChangeJournalTable.md" target="_blank">WorksheetHeader/RetailLabelChangeJournalTable</a>|
|[Description](#Description)||<a href="RetailLabelChangeJournalTable.md" target="_blank">WorksheetHeader/RetailLabelChangeJournalTable</a>|
|[HcmWorker](#HcmWorker)||<a href="RetailLabelChangeJournalTable.md" target="_blank">WorksheetHeader/RetailLabelChangeJournalTable</a>|
|[InitWithQtyOnHand](#InitWithQtyOnHand)||<a href="RetailLabelChangeJournalTable.md" target="_blank">WorksheetHeader/RetailLabelChangeJournalTable</a>|
|[InitWithQtyOrdered](#InitWithQtyOrdered)||<a href="RetailLabelChangeJournalTable.md" target="_blank">WorksheetHeader/RetailLabelChangeJournalTable</a>|
|[ItemQtyFilter](#ItemQtyFilter)||<a href="RetailLabelChangeJournalTable.md" target="_blank">WorksheetHeader/RetailLabelChangeJournalTable</a>|
|[JournalNum](#JournalNum)||<a href="RetailLabelChangeJournalTable.md" target="_blank">WorksheetHeader/RetailLabelChangeJournalTable</a>|
|[LabelChangeJournalTableBatch](#LabelChangeJournalTableBatch)||<a href="RetailLabelChangeJournalTable.md" target="_blank">WorksheetHeader/RetailLabelChangeJournalTable</a>|
|[PriceValidOnDate](#PriceValidOnDate)||<a href="RetailLabelChangeJournalTable.md" target="_blank">WorksheetHeader/RetailLabelChangeJournalTable</a>|
|[SourceId](#SourceId)||<a href="RetailLabelChangeJournalTable.md" target="_blank">WorksheetHeader/RetailLabelChangeJournalTable</a>|
|[SourceType](#SourceType)||<a href="RetailLabelChangeJournalTable.md" target="_blank">WorksheetHeader/RetailLabelChangeJournalTable</a>|
|[Status](#Status)||<a href="RetailLabelChangeJournalTable.md" target="_blank">WorksheetHeader/RetailLabelChangeJournalTable</a>|
|[StoreId](#StoreId)||<a href="RetailLabelChangeJournalTable.md" target="_blank">WorksheetHeader/RetailLabelChangeJournalTable</a>|
|[DataAreaId](#DataAreaId)||<a href="RetailLabelChangeJournalTable.md" target="_blank">WorksheetHeader/RetailLabelChangeJournalTable</a>|
|[Relationship_InventJournalTableRelationshipId](#Relationship_InventJournalTableRelationshipId)||<a href="RetailLabelChangeJournalTable.md" target="_blank">WorksheetHeader/RetailLabelChangeJournalTable</a>|
|[Relationship_InventTransferTableRelationshipId](#Relationship_InventTransferTableRelationshipId)||<a href="RetailLabelChangeJournalTable.md" target="_blank">WorksheetHeader/RetailLabelChangeJournalTable</a>|
|[Relationship_PriceDiscAdmTableRelationshipId](#Relationship_PriceDiscAdmTableRelationshipId)||<a href="RetailLabelChangeJournalTable.md" target="_blank">WorksheetHeader/RetailLabelChangeJournalTable</a>|
|[Relationship_PriceDiscAdmTransRelationshipId](#Relationship_PriceDiscAdmTransRelationshipId)||<a href="RetailLabelChangeJournalTable.md" target="_blank">WorksheetHeader/RetailLabelChangeJournalTable</a>|
|[Relationship_PurchTableRelationshipId](#Relationship_PurchTableRelationshipId)||<a href="RetailLabelChangeJournalTable.md" target="_blank">WorksheetHeader/RetailLabelChangeJournalTable</a>|
|[Relationship_RetailLabelChangeJournalTableBatchRelationshipId](#Relationship_RetailLabelChangeJournalTableBatchRelationshipId)||<a href="RetailLabelChangeJournalTable.md" target="_blank">WorksheetHeader/RetailLabelChangeJournalTable</a>|
|[Relationship_RetailStoreTableRelationshipId](#Relationship_RetailStoreTableRelationshipId)||<a href="RetailLabelChangeJournalTable.md" target="_blank">WorksheetHeader/RetailLabelChangeJournalTable</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RetailLabelChangeJournalTable.md" target="_blank">WorksheetHeader/RetailLabelChangeJournalTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetHeader/RetailLabelChangeJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailLabelChangeJournalTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Active name="Active">Active</a>

First included in: WorksheetHeader/RetailLabelChangeJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Active</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Active attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Active</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ConfirmDate name="ConfirmDate">ConfirmDate</a>

First included in: WorksheetHeader/RetailLabelChangeJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Confirmation date</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfirmDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Confirmation date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: WorksheetHeader/RetailLabelChangeJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HcmWorker name="HcmWorker">HcmWorker</a>

First included in: WorksheetHeader/RetailLabelChangeJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HcmWorker attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InitWithQtyOnHand name="InitWithQtyOnHand">InitWithQtyOnHand</a>

First included in: WorksheetHeader/RetailLabelChangeJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Update product label quantity from on-hand quantity</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InitWithQtyOnHand attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Update product label quantity from on-hand quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#InitWithQtyOrdered name="InitWithQtyOrdered">InitWithQtyOrdered</a>

First included in: WorksheetHeader/RetailLabelChangeJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Update product label quantity from ordered quantity</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InitWithQtyOrdered attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Update product label quantity from ordered quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ItemQtyFilter name="ItemQtyFilter">ItemQtyFilter</a>

First included in: WorksheetHeader/RetailLabelChangeJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemQtyFilter attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#JournalNum name="JournalNum">JournalNum</a>

First included in: WorksheetHeader/RetailLabelChangeJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Journal</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Journal</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LabelChangeJournalTableBatch name="LabelChangeJournalTableBatch">LabelChangeJournalTableBatch</a>

First included in: WorksheetHeader/RetailLabelChangeJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LabelChangeJournalTableBatch attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PriceValidOnDate name="PriceValidOnDate">PriceValidOnDate</a>

First included in: WorksheetHeader/RetailLabelChangeJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price date</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceValidOnDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Price date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#SourceId name="SourceId">SourceId</a>

First included in: WorksheetHeader/RetailLabelChangeJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceType name="SourceType">SourceType</a>

First included in: WorksheetHeader/RetailLabelChangeJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: WorksheetHeader/RetailLabelChangeJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#StoreId name="StoreId">StoreId</a>

First included in: WorksheetHeader/RetailLabelChangeJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetHeader/RetailLabelChangeJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventJournalTableRelationshipId name="Relationship_InventJournalTableRelationshipId">Relationship_InventJournalTableRelationshipId</a>

First included in: WorksheetHeader/RetailLabelChangeJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventJournalTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../SupplyChain/Inventory/WorksheetHeader/InventJournalTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/InventJournalTable.cdm.json/InventJournalTable</a></td><td><a href="../../../../SupplyChain/Inventory/WorksheetHeader/InventJournalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTransferTableRelationshipId name="Relationship_InventTransferTableRelationshipId">Relationship_InventTransferTableRelationshipId</a>

First included in: WorksheetHeader/RetailLabelChangeJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTransferTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../SupplyChain/Inventory/WorksheetHeader/InventTransferTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/InventTransferTable.cdm.json/InventTransferTable</a></td><td><a href="../../../../SupplyChain/Inventory/WorksheetHeader/InventTransferTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PriceDiscAdmTableRelationshipId name="Relationship_PriceDiscAdmTableRelationshipId">Relationship_PriceDiscAdmTableRelationshipId</a>

First included in: WorksheetHeader/RetailLabelChangeJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PriceDiscAdmTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../SupplyChain/SalesAndMarketing/WorksheetHeader/PriceDiscAdmTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/PriceDiscAdmTable.cdm.json/PriceDiscAdmTable</a></td><td><a href="../../../../SupplyChain/SalesAndMarketing/WorksheetHeader/PriceDiscAdmTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PriceDiscAdmTransRelationshipId name="Relationship_PriceDiscAdmTransRelationshipId">Relationship_PriceDiscAdmTransRelationshipId</a>

First included in: WorksheetHeader/RetailLabelChangeJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PriceDiscAdmTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../SupplyChain/SalesAndMarketing/WorksheetLine/PriceDiscAdmTrans.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/WorksheetLine/PriceDiscAdmTrans.cdm.json/PriceDiscAdmTrans</a></td><td><a href="../../../../SupplyChain/SalesAndMarketing/WorksheetLine/PriceDiscAdmTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchTableRelationshipId name="Relationship_PurchTableRelationshipId">Relationship_PurchTableRelationshipId</a>

First included in: WorksheetHeader/RetailLabelChangeJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchTable.cdm.json/PurchTable</a></td><td><a href="../../../../SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailLabelChangeJournalTableBatchRelationshipId name="Relationship_RetailLabelChangeJournalTableBatchRelationshipId">Relationship_RetailLabelChangeJournalTableBatchRelationshipId</a>

First included in: WorksheetHeader/RetailLabelChangeJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailLabelChangeJournalTableBatchRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailLabelChangeJournalTableBatch.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/WorksheetHeader/RetailLabelChangeJournalTableBatch.cdm.json/RetailLabelChangeJournalTableBatch</a></td><td><a href="RetailLabelChangeJournalTableBatch.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailStoreTableRelationshipId name="Relationship_RetailStoreTableRelationshipId">Relationship_RetailStoreTableRelationshipId</a>

First included in: WorksheetHeader/RetailLabelChangeJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailStoreTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailStoreTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Main/RetailStoreTable.cdm.json/RetailStoreTable</a></td><td><a href="../Main/RetailStoreTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetHeader/RetailLabelChangeJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
