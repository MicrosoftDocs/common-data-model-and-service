---
title: InventDestinationAddressDeliveryModeTransportationTimeEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Destination address delivery mode transportation time in InventoryAndWarehouseManagement(InventDestinationAddressDeliveryModeTransportationTimeEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventDestinationAddressDeliveryModeTransportationTimeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Destination address delivery mode transportation time</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DestinationAddressTransportationTimeOriginWarehouseId](#DestinationAddressTransportationTimeOriginWarehouseId)||<a href="InventDestinationAddressDeliveryModeTransportationTimeEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDestinationAddressDeliveryModeTransportationTimeEntity</a>|
|[DestinationAddressTransportationTimeDestinationAddressCountryRegionId](#DestinationAddressTransportationTimeDestinationAddressCountryRegionId)||<a href="InventDestinationAddressDeliveryModeTransportationTimeEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDestinationAddressDeliveryModeTransportationTimeEntity</a>|
|[DestinationAddressTransportationTimeDestinationAddressStateId](#DestinationAddressTransportationTimeDestinationAddressStateId)||<a href="InventDestinationAddressDeliveryModeTransportationTimeEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDestinationAddressDeliveryModeTransportationTimeEntity</a>|
|[DestinationAddressTransportationTimeDestinationAddressCountyId](#DestinationAddressTransportationTimeDestinationAddressCountyId)||<a href="InventDestinationAddressDeliveryModeTransportationTimeEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDestinationAddressDeliveryModeTransportationTimeEntity</a>|
|[DestinationAddressTransportationTimeDestinationAddressZipCode](#DestinationAddressTransportationTimeDestinationAddressZipCode)||<a href="InventDestinationAddressDeliveryModeTransportationTimeEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDestinationAddressDeliveryModeTransportationTimeEntity</a>|
|[DeliveryModeCode](#DeliveryModeCode)||<a href="InventDestinationAddressDeliveryModeTransportationTimeEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDestinationAddressDeliveryModeTransportationTimeEntity</a>|
|[TransportationDays](#TransportationDays)||<a href="InventDestinationAddressDeliveryModeTransportationTimeEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDestinationAddressDeliveryModeTransportationTimeEntity</a>|
|[IsDefaultDeliveryMode](#IsDefaultDeliveryMode)||<a href="InventDestinationAddressDeliveryModeTransportationTimeEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDestinationAddressDeliveryModeTransportationTimeEntity</a>|
|[TransportPointLineRecId](#TransportPointLineRecId)||<a href="InventDestinationAddressDeliveryModeTransportationTimeEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDestinationAddressDeliveryModeTransportationTimeEntity</a>|
|[BackingTable_CustVendTransportTimeRelationshipId](#BackingTable_CustVendTransportTimeRelationshipId)||<a href="InventDestinationAddressDeliveryModeTransportationTimeEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDestinationAddressDeliveryModeTransportationTimeEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventDestinationAddressDeliveryModeTransportationTimeEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDestinationAddressDeliveryModeTransportationTimeEntity</a>|

### <a href=#DestinationAddressTransportationTimeOriginWarehouseId name="DestinationAddressTransportationTimeOriginWarehouseId">DestinationAddressTransportationTimeOriginWarehouseId</a>

First included in: InventoryAndWarehouseManagement/InventDestinationAddressDeliveryModeTransportationTimeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationAddressTransportationTimeOriginWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationAddressTransportationTimeDestinationAddressCountryRegionId name="DestinationAddressTransportationTimeDestinationAddressCountryRegionId">DestinationAddressTransportationTimeDestinationAddressCountryRegionId</a>

First included in: InventoryAndWarehouseManagement/InventDestinationAddressDeliveryModeTransportationTimeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationAddressTransportationTimeDestinationAddressCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationAddressTransportationTimeDestinationAddressStateId name="DestinationAddressTransportationTimeDestinationAddressStateId">DestinationAddressTransportationTimeDestinationAddressStateId</a>

First included in: InventoryAndWarehouseManagement/InventDestinationAddressDeliveryModeTransportationTimeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationAddressTransportationTimeDestinationAddressStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationAddressTransportationTimeDestinationAddressCountyId name="DestinationAddressTransportationTimeDestinationAddressCountyId">DestinationAddressTransportationTimeDestinationAddressCountyId</a>

First included in: InventoryAndWarehouseManagement/InventDestinationAddressDeliveryModeTransportationTimeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationAddressTransportationTimeDestinationAddressCountyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationAddressTransportationTimeDestinationAddressZipCode name="DestinationAddressTransportationTimeDestinationAddressZipCode">DestinationAddressTransportationTimeDestinationAddressZipCode</a>

First included in: InventoryAndWarehouseManagement/InventDestinationAddressDeliveryModeTransportationTimeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationAddressTransportationTimeDestinationAddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryModeCode name="DeliveryModeCode">DeliveryModeCode</a>

First included in: InventoryAndWarehouseManagement/InventDestinationAddressDeliveryModeTransportationTimeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryModeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationDays name="TransportationDays">TransportationDays</a>

First included in: InventoryAndWarehouseManagement/InventDestinationAddressDeliveryModeTransportationTimeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDefaultDeliveryMode name="IsDefaultDeliveryMode">IsDefaultDeliveryMode</a>

First included in: InventoryAndWarehouseManagement/InventDestinationAddressDeliveryModeTransportationTimeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDefaultDeliveryMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportPointLineRecId name="TransportPointLineRecId">TransportPointLineRecId</a>

First included in: InventoryAndWarehouseManagement/InventDestinationAddressDeliveryModeTransportationTimeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportPointLineRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_CustVendTransportTimeRelationshipId name="BackingTable_CustVendTransportTimeRelationshipId">BackingTable_CustVendTransportTimeRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventDestinationAddressDeliveryModeTransportationTimeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CustVendTransportTimeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Group/CustVendTransportTime.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/CustVendTransportTime.cdm.json/CustVendTransportTime</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Group/CustVendTransportTime.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventDestinationAddressDeliveryModeTransportationTimeEntity (this entity)  

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
