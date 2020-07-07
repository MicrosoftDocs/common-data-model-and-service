---
title: PdsProductSafetyDataSheetValidityEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Product safety data sheet validity in InventoryAndWarehouseManagement

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/PdsProductSafetyDataSheetValidityEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product safety data sheet validity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ApplicableCountryRegionId](#ApplicableCountryRegionId)||<a href="PdsProductSafetyDataSheetValidityEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSafetyDataSheetValidityEntity</a>|
|[ExpirationDays](#ExpirationDays)||<a href="PdsProductSafetyDataSheetValidityEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSafetyDataSheetValidityEntity</a>|
|[ValidityDays](#ValidityDays)||<a href="PdsProductSafetyDataSheetValidityEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSafetyDataSheetValidityEntity</a>|
|[IsMinorRevisionEnforced](#IsMinorRevisionEnforced)||<a href="PdsProductSafetyDataSheetValidityEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSafetyDataSheetValidityEntity</a>|
|[BackingTable_PdsMRCValidityIntervalByCountryRelationshipId](#BackingTable_PdsMRCValidityIntervalByCountryRelationshipId)||<a href="PdsProductSafetyDataSheetValidityEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSafetyDataSheetValidityEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PdsProductSafetyDataSheetValidityEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSafetyDataSheetValidityEntity</a>|

### <a href=#ApplicableCountryRegionId name="ApplicableCountryRegionId">ApplicableCountryRegionId</a>

First included in: InventoryAndWarehouseManagement/PdsProductSafetyDataSheetValidityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplicableCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpirationDays name="ExpirationDays">ExpirationDays</a>

First included in: InventoryAndWarehouseManagement/PdsProductSafetyDataSheetValidityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpirationDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidityDays name="ValidityDays">ValidityDays</a>

First included in: InventoryAndWarehouseManagement/PdsProductSafetyDataSheetValidityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidityDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsMinorRevisionEnforced name="IsMinorRevisionEnforced">IsMinorRevisionEnforced</a>

First included in: InventoryAndWarehouseManagement/PdsProductSafetyDataSheetValidityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsMinorRevisionEnforced attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PdsMRCValidityIntervalByCountryRelationshipId name="BackingTable_PdsMRCValidityIntervalByCountryRelationshipId">BackingTable_PdsMRCValidityIntervalByCountryRelationshipId</a>

First included in: InventoryAndWarehouseManagement/PdsProductSafetyDataSheetValidityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PdsMRCValidityIntervalByCountryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/PdsMRCValidityIntervalByCountry.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/PdsMRCValidityIntervalByCountry.cdm.json/PdsMRCValidityIntervalByCountry</a></td><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/PdsMRCValidityIntervalByCountry.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/PdsProductSafetyDataSheetValidityEntity (this entity)  

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
