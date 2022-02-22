---
title: InventDestinationAddressTransportationTimeEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Destination address transportation time in InventoryAndWarehouseManagement(InventDestinationAddressTransportationTimeEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventDestinationAddressTransportationTimeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Destination address transportation time</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[OriginWarehouseId](#OriginWarehouseId)||<a href="InventDestinationAddressTransportationTimeEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDestinationAddressTransportationTimeEntity</a>|
|[DestinationAddressCountryRegionId](#DestinationAddressCountryRegionId)||<a href="InventDestinationAddressTransportationTimeEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDestinationAddressTransportationTimeEntity</a>|
|[DestinationAddressStateId](#DestinationAddressStateId)||<a href="InventDestinationAddressTransportationTimeEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDestinationAddressTransportationTimeEntity</a>|
|[DestinationAddressCountyId](#DestinationAddressCountyId)||<a href="InventDestinationAddressTransportationTimeEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDestinationAddressTransportationTimeEntity</a>|
|[DestinationAddressCity](#DestinationAddressCity)||<a href="InventDestinationAddressTransportationTimeEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDestinationAddressTransportationTimeEntity</a>|
|[DestinationAddressZipCode](#DestinationAddressZipCode)||<a href="InventDestinationAddressTransportationTimeEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDestinationAddressTransportationTimeEntity</a>|
|[DefaultTransportationDays](#DefaultTransportationDays)||<a href="InventDestinationAddressTransportationTimeEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDestinationAddressTransportationTimeEntity</a>|
|[BackingTable_CustVendTransportPointLineRelationshipId](#BackingTable_CustVendTransportPointLineRelationshipId)||<a href="InventDestinationAddressTransportationTimeEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDestinationAddressTransportationTimeEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventDestinationAddressTransportationTimeEntity.md" target="_blank">InventoryAndWarehouseManagement/InventDestinationAddressTransportationTimeEntity</a>|

### <a href=#OriginWarehouseId name="OriginWarehouseId">OriginWarehouseId</a>

First included in: InventoryAndWarehouseManagement/InventDestinationAddressTransportationTimeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationAddressCountryRegionId name="DestinationAddressCountryRegionId">DestinationAddressCountryRegionId</a>

First included in: InventoryAndWarehouseManagement/InventDestinationAddressTransportationTimeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationAddressCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationAddressStateId name="DestinationAddressStateId">DestinationAddressStateId</a>

First included in: InventoryAndWarehouseManagement/InventDestinationAddressTransportationTimeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationAddressStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationAddressCountyId name="DestinationAddressCountyId">DestinationAddressCountyId</a>

First included in: InventoryAndWarehouseManagement/InventDestinationAddressTransportationTimeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationAddressCountyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationAddressCity name="DestinationAddressCity">DestinationAddressCity</a>

First included in: InventoryAndWarehouseManagement/InventDestinationAddressTransportationTimeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationAddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationAddressZipCode name="DestinationAddressZipCode">DestinationAddressZipCode</a>

First included in: InventoryAndWarehouseManagement/InventDestinationAddressTransportationTimeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationAddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultTransportationDays name="DefaultTransportationDays">DefaultTransportationDays</a>

First included in: InventoryAndWarehouseManagement/InventDestinationAddressTransportationTimeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultTransportationDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_CustVendTransportPointLineRelationshipId name="BackingTable_CustVendTransportPointLineRelationshipId">BackingTable_CustVendTransportPointLineRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventDestinationAddressTransportationTimeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CustVendTransportPointLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Group/CustVendTransportPointLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/CustVendTransportPointLine.cdm.json/CustVendTransportPointLine</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Group/CustVendTransportPointLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventDestinationAddressTransportationTimeEntity (this entity)  

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
