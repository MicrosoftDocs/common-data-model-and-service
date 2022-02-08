---
title: TaxInfoManagementOnCustomerEntity in Tax - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Tax information on customer in Tax(TaxInfoManagementOnCustomerEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Tax/TaxInfoManagementOnCustomerEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax information on customer</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CustomerId](#CustomerId)||<a href="TaxInfoManagementOnCustomerEntity.md" target="_blank">Tax/TaxInfoManagementOnCustomerEntity</a>|
|[Name](#Name)||<a href="TaxInfoManagementOnCustomerEntity.md" target="_blank">Tax/TaxInfoManagementOnCustomerEntity</a>|
|[IsPrimary](#IsPrimary)||<a href="TaxInfoManagementOnCustomerEntity.md" target="_blank">Tax/TaxInfoManagementOnCustomerEntity</a>|
|[GSTNumber](#GSTNumber)||<a href="TaxInfoManagementOnCustomerEntity.md" target="_blank">Tax/TaxInfoManagementOnCustomerEntity</a>|
|[Range](#Range)||<a href="TaxInfoManagementOnCustomerEntity.md" target="_blank">Tax/TaxInfoManagementOnCustomerEntity</a>|
|[ManufacturerECCNumber](#ManufacturerECCNumber)||<a href="TaxInfoManagementOnCustomerEntity.md" target="_blank">Tax/TaxInfoManagementOnCustomerEntity</a>|
|[Commissionarate](#Commissionarate)||<a href="TaxInfoManagementOnCustomerEntity.md" target="_blank">Tax/TaxInfoManagementOnCustomerEntity</a>|
|[Division](#Division)||<a href="TaxInfoManagementOnCustomerEntity.md" target="_blank">Tax/TaxInfoManagementOnCustomerEntity</a>|
|[TraderECCNumber](#TraderECCNumber)||<a href="TaxInfoManagementOnCustomerEntity.md" target="_blank">Tax/TaxInfoManagementOnCustomerEntity</a>|
|[LargeTaxpayerUnitCode](#LargeTaxpayerUnitCode)||<a href="TaxInfoManagementOnCustomerEntity.md" target="_blank">Tax/TaxInfoManagementOnCustomerEntity</a>|
|[IECNumber](#IECNumber)||<a href="TaxInfoManagementOnCustomerEntity.md" target="_blank">Tax/TaxInfoManagementOnCustomerEntity</a>|
|[STCNumber](#STCNumber)||<a href="TaxInfoManagementOnCustomerEntity.md" target="_blank">Tax/TaxInfoManagementOnCustomerEntity</a>|
|[SalesTaxRegistrationNumber](#SalesTaxRegistrationNumber)||<a href="TaxInfoManagementOnCustomerEntity.md" target="_blank">Tax/TaxInfoManagementOnCustomerEntity</a>|
|[TaxIdentificationNumber](#TaxIdentificationNumber)||<a href="TaxInfoManagementOnCustomerEntity.md" target="_blank">Tax/TaxInfoManagementOnCustomerEntity</a>|
|[TaxAccountNumber](#TaxAccountNumber)||<a href="TaxInfoManagementOnCustomerEntity.md" target="_blank">Tax/TaxInfoManagementOnCustomerEntity</a>|
|[RegistrationType](#RegistrationType)||<a href="TaxInfoManagementOnCustomerEntity.md" target="_blank">Tax/TaxInfoManagementOnCustomerEntity</a>|
|[BackingTable_TaxInfoManagementEntityRelationshipId](#BackingTable_TaxInfoManagementEntityRelationshipId)||<a href="TaxInfoManagementOnCustomerEntity.md" target="_blank">Tax/TaxInfoManagementOnCustomerEntity</a>|

### <a href=#CustomerId name="CustomerId">CustomerId</a>

First included in: Tax/TaxInfoManagementOnCustomerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Tax/TaxInfoManagementOnCustomerEntity (this entity)  

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

### <a href=#IsPrimary name="IsPrimary">IsPrimary</a>

First included in: Tax/TaxInfoManagementOnCustomerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrimary attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GSTNumber name="GSTNumber">GSTNumber</a>

First included in: Tax/TaxInfoManagementOnCustomerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GSTNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Range name="Range">Range</a>

First included in: Tax/TaxInfoManagementOnCustomerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Range attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManufacturerECCNumber name="ManufacturerECCNumber">ManufacturerECCNumber</a>

First included in: Tax/TaxInfoManagementOnCustomerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManufacturerECCNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Commissionarate name="Commissionarate">Commissionarate</a>

First included in: Tax/TaxInfoManagementOnCustomerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Commissionarate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Division name="Division">Division</a>

First included in: Tax/TaxInfoManagementOnCustomerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Division attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TraderECCNumber name="TraderECCNumber">TraderECCNumber</a>

First included in: Tax/TaxInfoManagementOnCustomerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TraderECCNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LargeTaxpayerUnitCode name="LargeTaxpayerUnitCode">LargeTaxpayerUnitCode</a>

First included in: Tax/TaxInfoManagementOnCustomerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LargeTaxpayerUnitCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IECNumber name="IECNumber">IECNumber</a>

First included in: Tax/TaxInfoManagementOnCustomerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IECNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#STCNumber name="STCNumber">STCNumber</a>

First included in: Tax/TaxInfoManagementOnCustomerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the STCNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxRegistrationNumber name="SalesTaxRegistrationNumber">SalesTaxRegistrationNumber</a>

First included in: Tax/TaxInfoManagementOnCustomerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxRegistrationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxIdentificationNumber name="TaxIdentificationNumber">TaxIdentificationNumber</a>

First included in: Tax/TaxInfoManagementOnCustomerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxIdentificationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAccountNumber name="TaxAccountNumber">TaxAccountNumber</a>

First included in: Tax/TaxInfoManagementOnCustomerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RegistrationType name="RegistrationType">RegistrationType</a>

First included in: Tax/TaxInfoManagementOnCustomerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegistrationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TaxInfoManagementEntityRelationshipId name="BackingTable_TaxInfoManagementEntityRelationshipId">BackingTable_TaxInfoManagementEntityRelationshipId</a>

First included in: Tax/TaxInfoManagementOnCustomerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TaxInfoManagementEntityRelationshipId attribute are listed below.</summary>

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
