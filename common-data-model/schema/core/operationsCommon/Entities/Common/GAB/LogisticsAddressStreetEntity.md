---
title: LogisticsAddressStreetEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# LogisticsAddressStreetEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Common/GAB/LogisticsAddressStreetEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[City](#City)||<a href="LogisticsAddressStreetEntity.md" target="_blank">GAB/LogisticsAddressStreetEntity</a>|
|[CountryRegion](#CountryRegion)||<a href="LogisticsAddressStreetEntity.md" target="_blank">GAB/LogisticsAddressStreetEntity</a>|
|[County](#County)||<a href="LogisticsAddressStreetEntity.md" target="_blank">GAB/LogisticsAddressStreetEntity</a>|
|[Description](#Description)||<a href="LogisticsAddressStreetEntity.md" target="_blank">GAB/LogisticsAddressStreetEntity</a>|
|[District](#District)||<a href="LogisticsAddressStreetEntity.md" target="_blank">GAB/LogisticsAddressStreetEntity</a>|
|[Name](#Name)||<a href="LogisticsAddressStreetEntity.md" target="_blank">GAB/LogisticsAddressStreetEntity</a>|
|[Properties](#Properties)||<a href="LogisticsAddressStreetEntity.md" target="_blank">GAB/LogisticsAddressStreetEntity</a>|
|[State](#State)||<a href="LogisticsAddressStreetEntity.md" target="_blank">GAB/LogisticsAddressStreetEntity</a>|
|[City_FK_Name](#City_FK_Name)||<a href="LogisticsAddressStreetEntity.md" target="_blank">GAB/LogisticsAddressStreetEntity</a>|
|[District_FK_Name](#District_FK_Name)||<a href="LogisticsAddressStreetEntity.md" target="_blank">GAB/LogisticsAddressStreetEntity</a>|
|[Properties_FK_AddressTypeTable_RU](#Properties_FK_AddressTypeTable_RU)||<a href="LogisticsAddressStreetEntity.md" target="_blank">GAB/LogisticsAddressStreetEntity</a>|
|[Properties_FK_GniCode](#Properties_FK_GniCode)||<a href="LogisticsAddressStreetEntity.md" target="_blank">GAB/LogisticsAddressStreetEntity</a>|
|[Properties_FK_IMNSDistrict](#Properties_FK_IMNSDistrict)||<a href="LogisticsAddressStreetEntity.md" target="_blank">GAB/LogisticsAddressStreetEntity</a>|
|[Properties_FK_ObjectStatus](#Properties_FK_ObjectStatus)||<a href="LogisticsAddressStreetEntity.md" target="_blank">GAB/LogisticsAddressStreetEntity</a>|
|[Properties_FK_OKATO](#Properties_FK_OKATO)||<a href="LogisticsAddressStreetEntity.md" target="_blank">GAB/LogisticsAddressStreetEntity</a>|
|[Properties_FK_ZipCode](#Properties_FK_ZipCode)||<a href="LogisticsAddressStreetEntity.md" target="_blank">GAB/LogisticsAddressStreetEntity</a>|
|[AddressTypeTable_RU_AddrTypeCode](#AddressTypeTable_RU_AddrTypeCode)||<a href="LogisticsAddressStreetEntity.md" target="_blank">GAB/LogisticsAddressStreetEntity</a>|
|[ZipCode_FK_ZipCode](#ZipCode_FK_ZipCode)||<a href="LogisticsAddressStreetEntity.md" target="_blank">GAB/LogisticsAddressStreetEntity</a>|
|[BackingTable_LogisticsAddressStreet_RURelationshipId](#BackingTable_LogisticsAddressStreet_RURelationshipId)||<a href="LogisticsAddressStreetEntity.md" target="_blank">GAB/LogisticsAddressStreetEntity</a>|

### <a href=#City name="City">City</a>

First included in: GAB/LogisticsAddressStreetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the City attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountryRegion name="CountryRegion">CountryRegion</a>

First included in: GAB/LogisticsAddressStreetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountryRegion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#County name="County">County</a>

First included in: GAB/LogisticsAddressStreetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the County attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: GAB/LogisticsAddressStreetEntity (this entity)  

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

### <a href=#District name="District">District</a>

First included in: GAB/LogisticsAddressStreetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the District attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: GAB/LogisticsAddressStreetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Properties name="Properties">Properties</a>

First included in: GAB/LogisticsAddressStreetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Properties attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#State name="State">State</a>

First included in: GAB/LogisticsAddressStreetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the State attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#City_FK_Name name="City_FK_Name">City_FK_Name</a>

First included in: GAB/LogisticsAddressStreetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the City_FK_Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#District_FK_Name name="District_FK_Name">District_FK_Name</a>

First included in: GAB/LogisticsAddressStreetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the District_FK_Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Properties_FK_AddressTypeTable_RU name="Properties_FK_AddressTypeTable_RU">Properties_FK_AddressTypeTable_RU</a>

First included in: GAB/LogisticsAddressStreetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Properties_FK_AddressTypeTable_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Properties_FK_GniCode name="Properties_FK_GniCode">Properties_FK_GniCode</a>

First included in: GAB/LogisticsAddressStreetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Properties_FK_GniCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Properties_FK_IMNSDistrict name="Properties_FK_IMNSDistrict">Properties_FK_IMNSDistrict</a>

First included in: GAB/LogisticsAddressStreetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Properties_FK_IMNSDistrict attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Properties_FK_ObjectStatus name="Properties_FK_ObjectStatus">Properties_FK_ObjectStatus</a>

First included in: GAB/LogisticsAddressStreetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Properties_FK_ObjectStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Properties_FK_OKATO name="Properties_FK_OKATO">Properties_FK_OKATO</a>

First included in: GAB/LogisticsAddressStreetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Properties_FK_OKATO attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Properties_FK_ZipCode name="Properties_FK_ZipCode">Properties_FK_ZipCode</a>

First included in: GAB/LogisticsAddressStreetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Properties_FK_ZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressTypeTable_RU_AddrTypeCode name="AddressTypeTable_RU_AddrTypeCode">AddressTypeTable_RU_AddrTypeCode</a>

First included in: GAB/LogisticsAddressStreetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressTypeTable_RU_AddrTypeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ZipCode_FK_ZipCode name="ZipCode_FK_ZipCode">ZipCode_FK_ZipCode</a>

First included in: GAB/LogisticsAddressStreetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ZipCode_FK_ZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_LogisticsAddressStreet_RURelationshipId name="BackingTable_LogisticsAddressStreet_RURelationshipId">BackingTable_LogisticsAddressStreet_RURelationshipId</a>

First included in: GAB/LogisticsAddressStreetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_LogisticsAddressStreet_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Common/GAB/Group/LogisticsAddressStreet_RU.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Group/LogisticsAddressStreet_RU.cdm.json/LogisticsAddressStreet_RU</a></td><td><a href="../../../Tables/Common/GAB/Group/LogisticsAddressStreet_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
