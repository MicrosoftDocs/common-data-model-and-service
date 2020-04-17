---
title: TMSTransportationAppointmentHistoryEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# TMSTransportationAppointmentHistoryEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/SupplyChain/Transportation/TMSTransportationAppointmentHistoryEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AppointmentId](#AppointmentId)||<a href="TMSTransportationAppointmentHistoryEntity.md" target="_blank">Transportation/TMSTransportationAppointmentHistoryEntity</a>|
|[AppointmentNote](#AppointmentNote)||<a href="TMSTransportationAppointmentHistoryEntity.md" target="_blank">Transportation/TMSTransportationAppointmentHistoryEntity</a>|
|[AppointmentStatus](#AppointmentStatus)||<a href="TMSTransportationAppointmentHistoryEntity.md" target="_blank">Transportation/TMSTransportationAppointmentHistoryEntity</a>|
|[AppointmentStatusReason](#AppointmentStatusReason)||<a href="TMSTransportationAppointmentHistoryEntity.md" target="_blank">Transportation/TMSTransportationAppointmentHistoryEntity</a>|
|[IsCustomerPickupAllowed](#IsCustomerPickupAllowed)||<a href="TMSTransportationAppointmentHistoryEntity.md" target="_blank">Transportation/TMSTransportationAppointmentHistoryEntity</a>|
|[PlannedEndDateTime](#PlannedEndDateTime)||<a href="TMSTransportationAppointmentHistoryEntity.md" target="_blank">Transportation/TMSTransportationAppointmentHistoryEntity</a>|
|[PlannedStartDateTime](#PlannedStartDateTime)||<a href="TMSTransportationAppointmentHistoryEntity.md" target="_blank">Transportation/TMSTransportationAppointmentHistoryEntity</a>|
|[ProductMovementDirectionRule](#ProductMovementDirectionRule)||<a href="TMSTransportationAppointmentHistoryEntity.md" target="_blank">Transportation/TMSTransportationAppointmentHistoryEntity</a>|
|[ShippingCarrierVendorAccountNumber](#ShippingCarrierVendorAccountNumber)||<a href="TMSTransportationAppointmentHistoryEntity.md" target="_blank">Transportation/TMSTransportationAppointmentHistoryEntity</a>|
|[TractorNumber](#TractorNumber)||<a href="TMSTransportationAppointmentHistoryEntity.md" target="_blank">Transportation/TMSTransportationAppointmentHistoryEntity</a>|
|[TrailerNumber](#TrailerNumber)||<a href="TMSTransportationAppointmentHistoryEntity.md" target="_blank">Transportation/TMSTransportationAppointmentHistoryEntity</a>|
|[TransportationAppointmentHistoryEntryNumber](#TransportationAppointmentHistoryEntryNumber)||<a href="TMSTransportationAppointmentHistoryEntity.md" target="_blank">Transportation/TMSTransportationAppointmentHistoryEntity</a>|
|[TransportationAppointmentRuleId](#TransportationAppointmentRuleId)||<a href="TMSTransportationAppointmentHistoryEntity.md" target="_blank">Transportation/TMSTransportationAppointmentHistoryEntity</a>|
|[TransportationBrokerId](#TransportationBrokerId)||<a href="TMSTransportationAppointmentHistoryEntity.md" target="_blank">Transportation/TMSTransportationAppointmentHistoryEntity</a>|
|[TransportationCarrierId](#TransportationCarrierId)||<a href="TMSTransportationAppointmentHistoryEntity.md" target="_blank">Transportation/TMSTransportationAppointmentHistoryEntity</a>|
|[LoadId](#LoadId)||<a href="TMSTransportationAppointmentHistoryEntity.md" target="_blank">Transportation/TMSTransportationAppointmentHistoryEntity</a>|
|[PurchaseOrderNumber](#PurchaseOrderNumber)||<a href="TMSTransportationAppointmentHistoryEntity.md" target="_blank">Transportation/TMSTransportationAppointmentHistoryEntity</a>|
|[SalesOrderNumber](#SalesOrderNumber)||<a href="TMSTransportationAppointmentHistoryEntity.md" target="_blank">Transportation/TMSTransportationAppointmentHistoryEntity</a>|
|[BackingTable_TMSApptHistoryRelationshipId](#BackingTable_TMSApptHistoryRelationshipId)||<a href="TMSTransportationAppointmentHistoryEntity.md" target="_blank">Transportation/TMSTransportationAppointmentHistoryEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TMSTransportationAppointmentHistoryEntity.md" target="_blank">Transportation/TMSTransportationAppointmentHistoryEntity</a>|

### <a href=#AppointmentId name="AppointmentId">AppointmentId</a>

First included in: Transportation/TMSTransportationAppointmentHistoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AppointmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AppointmentNote name="AppointmentNote">AppointmentNote</a>

First included in: Transportation/TMSTransportationAppointmentHistoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AppointmentNote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AppointmentStatus name="AppointmentStatus">AppointmentStatus</a>

First included in: Transportation/TMSTransportationAppointmentHistoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AppointmentStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AppointmentStatusReason name="AppointmentStatusReason">AppointmentStatusReason</a>

First included in: Transportation/TMSTransportationAppointmentHistoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AppointmentStatusReason attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCustomerPickupAllowed name="IsCustomerPickupAllowed">IsCustomerPickupAllowed</a>

First included in: Transportation/TMSTransportationAppointmentHistoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCustomerPickupAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedEndDateTime name="PlannedEndDateTime">PlannedEndDateTime</a>

First included in: Transportation/TMSTransportationAppointmentHistoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedEndDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedStartDateTime name="PlannedStartDateTime">PlannedStartDateTime</a>

First included in: Transportation/TMSTransportationAppointmentHistoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedStartDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductMovementDirectionRule name="ProductMovementDirectionRule">ProductMovementDirectionRule</a>

First included in: Transportation/TMSTransportationAppointmentHistoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductMovementDirectionRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingCarrierVendorAccountNumber name="ShippingCarrierVendorAccountNumber">ShippingCarrierVendorAccountNumber</a>

First included in: Transportation/TMSTransportationAppointmentHistoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingCarrierVendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TractorNumber name="TractorNumber">TractorNumber</a>

First included in: Transportation/TMSTransportationAppointmentHistoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TractorNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TrailerNumber name="TrailerNumber">TrailerNumber</a>

First included in: Transportation/TMSTransportationAppointmentHistoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrailerNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationAppointmentHistoryEntryNumber name="TransportationAppointmentHistoryEntryNumber">TransportationAppointmentHistoryEntryNumber</a>

First included in: Transportation/TMSTransportationAppointmentHistoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationAppointmentHistoryEntryNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationAppointmentRuleId name="TransportationAppointmentRuleId">TransportationAppointmentRuleId</a>

First included in: Transportation/TMSTransportationAppointmentHistoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationAppointmentRuleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationBrokerId name="TransportationBrokerId">TransportationBrokerId</a>

First included in: Transportation/TMSTransportationAppointmentHistoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationBrokerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationCarrierId name="TransportationCarrierId">TransportationCarrierId</a>

First included in: Transportation/TMSTransportationAppointmentHistoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationCarrierId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoadId name="LoadId">LoadId</a>

First included in: Transportation/TMSTransportationAppointmentHistoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrderNumber name="PurchaseOrderNumber">PurchaseOrderNumber</a>

First included in: Transportation/TMSTransportationAppointmentHistoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderNumber name="SalesOrderNumber">SalesOrderNumber</a>

First included in: Transportation/TMSTransportationAppointmentHistoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TMSApptHistoryRelationshipId name="BackingTable_TMSApptHistoryRelationshipId">BackingTable_TMSApptHistoryRelationshipId</a>

First included in: Transportation/TMSTransportationAppointmentHistoryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TMSApptHistoryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Transportation/Transaction/TMSApptHistory.md" target="_blank">/core/erp/Tables/SupplyChain/Transportation/Transaction/TMSApptHistory.cdm.json/TMSApptHistory</a></td><td><a href="../../../Tables/SupplyChain/Transportation/Transaction/TMSApptHistory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Transportation/TMSTransportationAppointmentHistoryEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
