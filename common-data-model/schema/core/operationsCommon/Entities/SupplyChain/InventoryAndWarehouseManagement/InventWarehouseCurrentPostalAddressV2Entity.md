---
title: InventWarehouseCurrentPostalAddressV2Entity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Warehouse current postal addresses V2 in InventoryAndWarehouseManagement

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Warehouse current postal addresses V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IsPrimaryAddress](#IsPrimaryAddress)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[WarehouseLegalEntityId](#WarehouseLegalEntityId)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[WarehouseId](#WarehouseId)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[AddressLocationId](#AddressLocationId)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[AddressDescription](#AddressDescription)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[AddressLocationSalesTaxGroupCode](#AddressLocationSalesTaxGroupCode)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[ValidFrom](#ValidFrom)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[ValidTo](#ValidTo)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[FormattedAddress](#FormattedAddress)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[AddressCity](#AddressCity)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[AddressCityInKana](#AddressCityInKana)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[AddressCountryRegionId](#AddressCountryRegionId)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[AddressCountyId](#AddressCountyId)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[AddressDistrictName](#AddressDistrictName)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[AddressLatitude](#AddressLatitude)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[AddressLongitude](#AddressLongitude)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[AddressStateId](#AddressStateId)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[AddressStreet](#AddressStreet)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[AddressStreetInKana](#AddressStreetInKana)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[AddressStreetNumber](#AddressStreetNumber)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[AddressTimeZone](#AddressTimeZone)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[AddressZipCode](#AddressZipCode)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[AddressBuildingCompliment](#AddressBuildingCompliment)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[AddressPostBox](#AddressPostBox)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[AddressLocationRoles](#AddressLocationRoles)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[Relationship_WarehouseRelationshipId](#Relationship_WarehouseRelationshipId)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[Relationship_AddressLocationSalesTaxGroupRelationshipId](#Relationship_AddressLocationSalesTaxGroupRelationshipId)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[Relationship_AddressCountryRegionRelationshipId](#Relationship_AddressCountryRegionRelationshipId)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[Relationship_AddressCityRelationshipId](#Relationship_AddressCityRelationshipId)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[Relationship_AddressCountyRelationshipId](#Relationship_AddressCountyRelationshipId)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[Relationship_AddressStateRelationshipId](#Relationship_AddressStateRelationshipId)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[BackingTable_InventWarehousePostalAddressEntityRelationshipId](#BackingTable_InventWarehousePostalAddressEntityRelationshipId)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventWarehouseCurrentPostalAddressV2Entity.md" target="_blank">InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity</a>|

### <a href=#IsPrimaryAddress name="IsPrimaryAddress">IsPrimaryAddress</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrimaryAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseLegalEntityId name="WarehouseLegalEntityId">WarehouseLegalEntityId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseLegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseId name="WarehouseId">WarehouseId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressLocationId name="AddressLocationId">AddressLocationId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressDescription name="AddressDescription">AddressDescription</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressLocationSalesTaxGroupCode name="AddressLocationSalesTaxGroupCode">AddressLocationSalesTaxGroupCode</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressLocationSalesTaxGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormattedAddress name="FormattedAddress">FormattedAddress</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormattedAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCity name="AddressCity">AddressCity</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCityInKana name="AddressCityInKana">AddressCityInKana</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCityInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCountryRegionId name="AddressCountryRegionId">AddressCountryRegionId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCountyId name="AddressCountyId">AddressCountyId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCountyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressDistrictName name="AddressDistrictName">AddressDistrictName</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressDistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressLatitude name="AddressLatitude">AddressLatitude</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressLatitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressLongitude name="AddressLongitude">AddressLongitude</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressLongitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressStateId name="AddressStateId">AddressStateId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressStreet name="AddressStreet">AddressStreet</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressStreetInKana name="AddressStreetInKana">AddressStreetInKana</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressStreetInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressStreetNumber name="AddressStreetNumber">AddressStreetNumber</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressStreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressTimeZone name="AddressTimeZone">AddressTimeZone</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressTimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressZipCode name="AddressZipCode">AddressZipCode</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressBuildingCompliment name="AddressBuildingCompliment">AddressBuildingCompliment</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressBuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressPostBox name="AddressPostBox">AddressPostBox</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressPostBox attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressLocationRoles name="AddressLocationRoles">AddressLocationRoles</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressLocationRoles attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WarehouseRelationshipId name="Relationship_WarehouseRelationshipId">Relationship_WarehouseRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AddressLocationSalesTaxGroupRelationshipId name="Relationship_AddressLocationSalesTaxGroupRelationshipId">Relationship_AddressLocationSalesTaxGroupRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AddressLocationSalesTaxGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AddressCountryRegionRelationshipId name="Relationship_AddressCountryRegionRelationshipId">Relationship_AddressCountryRegionRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AddressCountryRegionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AddressCityRelationshipId name="Relationship_AddressCityRelationshipId">Relationship_AddressCityRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AddressCityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AddressCountyRelationshipId name="Relationship_AddressCountyRelationshipId">Relationship_AddressCountyRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AddressCountyRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AddressStateRelationshipId name="Relationship_AddressStateRelationshipId">Relationship_AddressStateRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AddressStateRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_InventWarehousePostalAddressEntityRelationshipId name="BackingTable_InventWarehousePostalAddressEntityRelationshipId">BackingTable_InventWarehousePostalAddressEntityRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventWarehousePostalAddressEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventWarehouseCurrentPostalAddressV2Entity (this entity)  

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
