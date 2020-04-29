---
title: InventSiteGateEntryHeaderEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Gate entry

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Gate entry</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ApproverEmployee](#ApproverEmployee)||<a href="InventSiteGateEntryHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity</a>|
|[ArrivalDateAndTime](#ArrivalDateAndTime)||<a href="InventSiteGateEntryHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity</a>|
|[ChallanDate](#ChallanDate)||<a href="InventSiteGateEntryHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity</a>|
|[ChallanNumber](#ChallanNumber)||<a href="InventSiteGateEntryHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity</a>|
|[Description](#Description)||<a href="InventSiteGateEntryHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity</a>|
|[DriverMobilePhone](#DriverMobilePhone)||<a href="InventSiteGateEntryHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity</a>|
|[GateEntry](#GateEntry)||<a href="InventSiteGateEntryHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity</a>|
|[ExitDateAndTime](#ExitDateAndTime)||<a href="InventSiteGateEntryHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity</a>|
|[InventLocationId](#InventLocationId)||<a href="InventSiteGateEntryHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity</a>|
|[InventSiteGate](#InventSiteGate)||<a href="InventSiteGateEntryHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity</a>|
|[Origin](#Origin)||<a href="InventSiteGateEntryHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity</a>|
|[ReferenceDocumentType](#ReferenceDocumentType)||<a href="InventSiteGateEntryHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity</a>|
|[ReferenceParty](#ReferenceParty)||<a href="InventSiteGateEntryHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity</a>|
|[RGPNumber](#RGPNumber)||<a href="InventSiteGateEntryHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity</a>|
|[SkipMeasurement](#SkipMeasurement)||<a href="InventSiteGateEntryHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity</a>|
|[Status](#Status)||<a href="InventSiteGateEntryHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity</a>|
|[Transporter](#Transporter)||<a href="InventSiteGateEntryHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity</a>|
|[DriverName](#DriverName)||<a href="InventSiteGateEntryHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity</a>|
|[TransportationReceiptDate](#TransportationReceiptDate)||<a href="InventSiteGateEntryHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity</a>|
|[TransportationReceiptNumber](#TransportationReceiptNumber)||<a href="InventSiteGateEntryHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity</a>|
|[GateEntryType](#GateEntryType)||<a href="InventSiteGateEntryHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity</a>|
|[VehicleNumber](#VehicleNumber)||<a href="InventSiteGateEntryHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity</a>|
|[Worker](#Worker)||<a href="InventSiteGateEntryHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity</a>|
|[FactoryGate](#FactoryGate)||<a href="InventSiteGateEntryHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity</a>|
|[Site](#Site)||<a href="InventSiteGateEntryHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity</a>|
|[BackingTable_InventSiteGateEntry_INRelationshipId](#BackingTable_InventSiteGateEntry_INRelationshipId)||<a href="InventSiteGateEntryHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventSiteGateEntryHeaderEntity.md" target="_blank">InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity</a>|

### <a href=#ApproverEmployee name="ApproverEmployee">ApproverEmployee</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApproverEmployee attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArrivalDateAndTime name="ArrivalDateAndTime">ArrivalDateAndTime</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArrivalDateAndTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChallanDate name="ChallanDate">ChallanDate</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChallanDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChallanNumber name="ChallanNumber">ChallanNumber</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChallanNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DriverMobilePhone name="DriverMobilePhone">DriverMobilePhone</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DriverMobilePhone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GateEntry name="GateEntry">GateEntry</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GateEntry attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExitDateAndTime name="ExitDateAndTime">ExitDateAndTime</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExitDateAndTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventLocationId name="InventLocationId">InventLocationId</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventSiteGate name="InventSiteGate">InventSiteGate</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventSiteGate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Origin name="Origin">Origin</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Origin attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReferenceDocumentType name="ReferenceDocumentType">ReferenceDocumentType</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReferenceDocumentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReferenceParty name="ReferenceParty">ReferenceParty</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReferenceParty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RGPNumber name="RGPNumber">RGPNumber</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RGPNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SkipMeasurement name="SkipMeasurement">SkipMeasurement</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SkipMeasurement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Transporter name="Transporter">Transporter</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Transporter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DriverName name="DriverName">DriverName</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DriverName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationReceiptDate name="TransportationReceiptDate">TransportationReceiptDate</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationReceiptDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationReceiptNumber name="TransportationReceiptNumber">TransportationReceiptNumber</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationReceiptNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GateEntryType name="GateEntryType">GateEntryType</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GateEntryType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VehicleNumber name="VehicleNumber">VehicleNumber</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VehicleNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Worker name="Worker">Worker</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Worker attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FactoryGate name="FactoryGate">FactoryGate</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FactoryGate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Site name="Site">Site</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Site attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_InventSiteGateEntry_INRelationshipId name="BackingTable_InventSiteGateEntry_INRelationshipId">BackingTable_InventSiteGateEntry_INRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventSiteGateEntry_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetHeader/InventSiteGateEntry_IN.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/InventSiteGateEntry_IN.cdm.json/InventSiteGateEntry_IN</a></td><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetHeader/InventSiteGateEntry_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventSiteGateEntryHeaderEntity (this entity)  

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
