---
title: InventOperationalSiteEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# Sites in InventoryAndWarehouseManagement(InventOperationalSiteEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventOperationalSiteEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sites</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[SiteId](#SiteId)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[SiteName](#SiteName)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[SiteTimezone](#SiteTimezone)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[OrderEntryDeadlineGroupId](#OrderEntryDeadlineGroupId)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[WillMasterPlannedIntraSiteMovementsUseTransferJournals](#WillMasterPlannedIntraSiteMovementsUseTransferJournals)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[DefaultInventoryStatusId](#DefaultInventoryStatusId)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[IsReceivingWarehouseOverrideAllowed](#IsReceivingWarehouseOverrideAllowed)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[InventSiteDefaultDimension](#InventSiteDefaultDimension)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[DefaultFinancialDimensionValue](#DefaultFinancialDimensionValue)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[FiscalEstablishmentId](#FiscalEstablishmentId)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[FiscalEstablishment](#FiscalEstablishment)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[PrimaryAddressDescription](#PrimaryAddressDescription)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[PrimaryAddressCity](#PrimaryAddressCity)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[PrimaryAddressCityInKana](#PrimaryAddressCityInKana)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[PrimaryAddressCountryRegionId](#PrimaryAddressCountryRegionId)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[PrimaryAddressCountyId](#PrimaryAddressCountyId)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[PrimaryAddressDistrictName](#PrimaryAddressDistrictName)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[PrimaryAddressLatitude](#PrimaryAddressLatitude)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[PrimaryAddressLocationRoles](#PrimaryAddressLocationRoles)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[PrimaryAddressLocationSalesTaxGroupCode](#PrimaryAddressLocationSalesTaxGroupCode)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[PrimaryAddressLongitude](#PrimaryAddressLongitude)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[PrimaryAddressStateId](#PrimaryAddressStateId)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[PrimaryAddressStreet](#PrimaryAddressStreet)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[PrimaryAddressStreetInKana](#PrimaryAddressStreetInKana)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[PrimaryAddressStreetNumber](#PrimaryAddressStreetNumber)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[PrimaryAddressTimeZone](#PrimaryAddressTimeZone)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[PrimaryAddressZipCode](#PrimaryAddressZipCode)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[PrimaryAddressPostBox](#PrimaryAddressPostBox)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[PrimaryAddressBuildingCompliment](#PrimaryAddressBuildingCompliment)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[FormattedPrimaryAddress](#FormattedPrimaryAddress)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[PrimaryAddressValidFrom](#PrimaryAddressValidFrom)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[PrimaryAddressValidTo](#PrimaryAddressValidTo)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[IsPrimaryAddressAssigned](#IsPrimaryAddressAssigned)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[TaxBranchCode](#TaxBranchCode)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[Relationship_FiscalEstablishmentRelationshipId](#Relationship_FiscalEstablishmentRelationshipId)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[Relationship_DefaultDimensionRelationshipId](#Relationship_DefaultDimensionRelationshipId)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[Relationship_DefaultInventoryStatusRelationshipId](#Relationship_DefaultInventoryStatusRelationshipId)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[Relationship_TaxBranchRelationshipId](#Relationship_TaxBranchRelationshipId)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[Relationship_OrderEntryDeadlineGroupRelationshipId](#Relationship_OrderEntryDeadlineGroupRelationshipId)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[BackingTable_InventSiteRelationshipId](#BackingTable_InventSiteRelationshipId)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventOperationalSiteEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOperationalSiteEntity</a>|

### <a href=#SiteId name="SiteId">SiteId</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SiteName name="SiteName">SiteName</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SiteName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SiteTimezone name="SiteTimezone">SiteTimezone</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SiteTimezone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderEntryDeadlineGroupId name="OrderEntryDeadlineGroupId">OrderEntryDeadlineGroupId</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderEntryDeadlineGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillMasterPlannedIntraSiteMovementsUseTransferJournals name="WillMasterPlannedIntraSiteMovementsUseTransferJournals">WillMasterPlannedIntraSiteMovementsUseTransferJournals</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillMasterPlannedIntraSiteMovementsUseTransferJournals attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultInventoryStatusId name="DefaultInventoryStatusId">DefaultInventoryStatusId</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultInventoryStatusId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReceivingWarehouseOverrideAllowed name="IsReceivingWarehouseOverrideAllowed">IsReceivingWarehouseOverrideAllowed</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReceivingWarehouseOverrideAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventSiteDefaultDimension name="InventSiteDefaultDimension">InventSiteDefaultDimension</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventSiteDefaultDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultFinancialDimensionValue name="DefaultFinancialDimensionValue">DefaultFinancialDimensionValue</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultFinancialDimensionValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentId name="FiscalEstablishmentId">FiscalEstablishmentId</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishment name="FiscalEstablishment">FiscalEstablishment</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressDescription name="PrimaryAddressDescription">PrimaryAddressDescription</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address name or description</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Address name or description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressCity name="PrimaryAddressCity">PrimaryAddressCity</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressCityInKana name="PrimaryAddressCityInKana">PrimaryAddressCityInKana</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressCityInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressCountryRegionId name="PrimaryAddressCountryRegionId">PrimaryAddressCountryRegionId</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressCountyId name="PrimaryAddressCountyId">PrimaryAddressCountyId</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressCountyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressDistrictName name="PrimaryAddressDistrictName">PrimaryAddressDistrictName</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressDistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressLatitude name="PrimaryAddressLatitude">PrimaryAddressLatitude</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressLatitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressLocationRoles name="PrimaryAddressLocationRoles">PrimaryAddressLocationRoles</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressLocationRoles attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressLocationSalesTaxGroupCode name="PrimaryAddressLocationSalesTaxGroupCode">PrimaryAddressLocationSalesTaxGroupCode</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressLocationSalesTaxGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressLongitude name="PrimaryAddressLongitude">PrimaryAddressLongitude</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressLongitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressStateId name="PrimaryAddressStateId">PrimaryAddressStateId</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressStreet name="PrimaryAddressStreet">PrimaryAddressStreet</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressStreetInKana name="PrimaryAddressStreetInKana">PrimaryAddressStreetInKana</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressStreetInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressStreetNumber name="PrimaryAddressStreetNumber">PrimaryAddressStreetNumber</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressStreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressTimeZone name="PrimaryAddressTimeZone">PrimaryAddressTimeZone</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary address time zone</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressTimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Primary address time zone</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressZipCode name="PrimaryAddressZipCode">PrimaryAddressZipCode</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressPostBox name="PrimaryAddressPostBox">PrimaryAddressPostBox</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressPostBox attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressBuildingCompliment name="PrimaryAddressBuildingCompliment">PrimaryAddressBuildingCompliment</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressBuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormattedPrimaryAddress name="FormattedPrimaryAddress">FormattedPrimaryAddress</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormattedPrimaryAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressValidFrom name="PrimaryAddressValidFrom">PrimaryAddressValidFrom</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressValidTo name="PrimaryAddressValidTo">PrimaryAddressValidTo</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrimaryAddressAssigned name="IsPrimaryAddressAssigned">IsPrimaryAddressAssigned</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrimaryAddressAssigned attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxBranchCode name="TaxBranchCode">TaxBranchCode</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBranchCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalEstablishmentRelationshipId name="Relationship_FiscalEstablishmentRelationshipId">Relationship_FiscalEstablishmentRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalEstablishmentRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultDimensionRelationshipId name="Relationship_DefaultDimensionRelationshipId">Relationship_DefaultDimensionRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultInventoryStatusRelationshipId name="Relationship_DefaultInventoryStatusRelationshipId">Relationship_DefaultInventoryStatusRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultInventoryStatusRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TaxBranchRelationshipId name="Relationship_TaxBranchRelationshipId">Relationship_TaxBranchRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxBranchRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_OrderEntryDeadlineGroupRelationshipId name="Relationship_OrderEntryDeadlineGroupRelationshipId">Relationship_OrderEntryDeadlineGroupRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OrderEntryDeadlineGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_InventSiteRelationshipId name="BackingTable_InventSiteRelationshipId">BackingTable_InventSiteRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventSiteRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Group/InventSite.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventSite.cdm.json/InventSite</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Group/InventSite.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventOperationalSiteEntity (this entity)  

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
