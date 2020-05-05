---
title: WMSItemArrivalJournalHeaderV2Entity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Item arrival journal headers V2

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WMSItemArrivalJournalHeaderV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item arrival journal headers V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[JournalNumber](#JournalNumber)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[JournalNameId](#JournalNameId)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[JournalDescription](#JournalDescription)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[DefaultReceivingSiteId](#DefaultReceivingSiteId)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[DefaultReceivingWarehouseId](#DefaultReceivingWarehouseId)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[DefaultReceivingWarehouseLocationId](#DefaultReceivingWarehouseLocationId)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[DefaultReceivingInventoryStatusId](#DefaultReceivingInventoryStatusId)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[DefaultReceivingLicensePlateNumber](#DefaultReceivingLicensePlateNumber)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[DefaultTransactionReferenceType](#DefaultTransactionReferenceType)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[DefaultTransactionReferenceNumber](#DefaultTransactionReferenceNumber)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[IsItemMovedToDefaultItemPickingWarehouseLocation](#IsItemMovedToDefaultItemPickingWarehouseLocation)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[IsQuarantineOrderCreatedForReceivedItem](#IsQuarantineOrderCreatedForReceivedItem)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[PackingSlipId](#PackingSlipId)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[DefaultReturnDispositionCodeId](#DefaultReturnDispositionCodeId)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[DefaultReturnItemNumber](#DefaultReturnItemNumber)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[DefaultAccountNumber](#DefaultAccountNumber)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[IsPosted](#IsPosted)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[PostedDateTime](#PostedDateTime)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[PostedUserId](#PostedUserId)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[AreLinesDeletedAfterPosting](#AreLinesDeletedAfterPosting)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[Relationship_ItemArrivalJournalNameRelationshipId](#Relationship_ItemArrivalJournalNameRelationshipId)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[Relationship_DefaultReceivingSiteRelationshipId](#Relationship_DefaultReceivingSiteRelationshipId)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[Relationship_DefaultReceivingWarehouseLocationRelationshipId](#Relationship_DefaultReceivingWarehouseLocationRelationshipId)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[Relationship_DefaultReceivingInventoryStatusRelationshipId](#Relationship_DefaultReceivingInventoryStatusRelationshipId)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[Relationship_DefaultReceivingLicensePlateRelationshipId](#Relationship_DefaultReceivingLicensePlateRelationshipId)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[Relationship_DefaultReturnDispositionCodeRelationshipId](#Relationship_DefaultReturnDispositionCodeRelationshipId)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[Relationship_DefaultVendorV2RelationshipId](#Relationship_DefaultVendorV2RelationshipId)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[Relationship_PostedUserRelationshipId](#Relationship_PostedUserRelationshipId)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[Relationship_DefaultReceivingWarehouseRelationshipId](#Relationship_DefaultReceivingWarehouseRelationshipId)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[BackingTable_WMSJournalTableRelationshipId](#BackingTable_WMSJournalTableRelationshipId)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WMSItemArrivalJournalHeaderV2Entity.md" target="_blank">WMS/WMSItemArrivalJournalHeaderV2Entity</a>|

### <a href=#JournalNumber name="JournalNumber">JournalNumber</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalNameId name="JournalNameId">JournalNameId</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

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

### <a href=#JournalDescription name="JournalDescription">JournalDescription</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultReceivingSiteId name="DefaultReceivingSiteId">DefaultReceivingSiteId</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultReceivingSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultReceivingWarehouseId name="DefaultReceivingWarehouseId">DefaultReceivingWarehouseId</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultReceivingWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultReceivingWarehouseLocationId name="DefaultReceivingWarehouseLocationId">DefaultReceivingWarehouseLocationId</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultReceivingWarehouseLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultReceivingInventoryStatusId name="DefaultReceivingInventoryStatusId">DefaultReceivingInventoryStatusId</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultReceivingInventoryStatusId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultReceivingLicensePlateNumber name="DefaultReceivingLicensePlateNumber">DefaultReceivingLicensePlateNumber</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultReceivingLicensePlateNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultTransactionReferenceType name="DefaultTransactionReferenceType">DefaultTransactionReferenceType</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultTransactionReferenceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultTransactionReferenceNumber name="DefaultTransactionReferenceNumber">DefaultTransactionReferenceNumber</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultTransactionReferenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsItemMovedToDefaultItemPickingWarehouseLocation name="IsItemMovedToDefaultItemPickingWarehouseLocation">IsItemMovedToDefaultItemPickingWarehouseLocation</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsItemMovedToDefaultItemPickingWarehouseLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuarantineOrderCreatedForReceivedItem name="IsQuarantineOrderCreatedForReceivedItem">IsQuarantineOrderCreatedForReceivedItem</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuarantineOrderCreatedForReceivedItem attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackingSlipId name="PackingSlipId">PackingSlipId</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingSlipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultReturnDispositionCodeId name="DefaultReturnDispositionCodeId">DefaultReturnDispositionCodeId</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultReturnDispositionCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultReturnItemNumber name="DefaultReturnItemNumber">DefaultReturnItemNumber</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultReturnItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultAccountNumber name="DefaultAccountNumber">DefaultAccountNumber</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPosted name="IsPosted">IsPosted</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPosted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostedDateTime name="PostedDateTime">PostedDateTime</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostedDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostedUserId name="PostedUserId">PostedUserId</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostedUserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreLinesDeletedAfterPosting name="AreLinesDeletedAfterPosting">AreLinesDeletedAfterPosting</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreLinesDeletedAfterPosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ItemArrivalJournalNameRelationshipId name="Relationship_ItemArrivalJournalNameRelationshipId">Relationship_ItemArrivalJournalNameRelationshipId</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ItemArrivalJournalNameRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultReceivingSiteRelationshipId name="Relationship_DefaultReceivingSiteRelationshipId">Relationship_DefaultReceivingSiteRelationshipId</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultReceivingSiteRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultReceivingWarehouseLocationRelationshipId name="Relationship_DefaultReceivingWarehouseLocationRelationshipId">Relationship_DefaultReceivingWarehouseLocationRelationshipId</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultReceivingWarehouseLocationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultReceivingInventoryStatusRelationshipId name="Relationship_DefaultReceivingInventoryStatusRelationshipId">Relationship_DefaultReceivingInventoryStatusRelationshipId</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultReceivingInventoryStatusRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultReceivingLicensePlateRelationshipId name="Relationship_DefaultReceivingLicensePlateRelationshipId">Relationship_DefaultReceivingLicensePlateRelationshipId</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultReceivingLicensePlateRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultReturnDispositionCodeRelationshipId name="Relationship_DefaultReturnDispositionCodeRelationshipId">Relationship_DefaultReturnDispositionCodeRelationshipId</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultReturnDispositionCodeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultVendorV2RelationshipId name="Relationship_DefaultVendorV2RelationshipId">Relationship_DefaultVendorV2RelationshipId</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultVendorV2RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PostedUserRelationshipId name="Relationship_PostedUserRelationshipId">Relationship_PostedUserRelationshipId</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PostedUserRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultReceivingWarehouseRelationshipId name="Relationship_DefaultReceivingWarehouseRelationshipId">Relationship_DefaultReceivingWarehouseRelationshipId</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultReceivingWarehouseRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_WMSJournalTableRelationshipId name="BackingTable_WMSJournalTableRelationshipId">BackingTable_WMSJournalTableRelationshipId</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WMSJournalTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetHeader/WMSJournalTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/WMSJournalTable.cdm.json/WMSJournalTable</a></td><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetHeader/WMSJournalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WMSItemArrivalJournalHeaderV2Entity (this entity)  

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
