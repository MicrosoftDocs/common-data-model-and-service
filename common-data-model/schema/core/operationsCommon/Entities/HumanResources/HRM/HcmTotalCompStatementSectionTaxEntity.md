---
title: HcmTotalCompStatementSectionTaxEntity in HRM - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# The tax codes in tax groups of the Total compensation statement section in HRM(HcmTotalCompStatementSectionTaxEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/HRM/HcmTotalCompStatementSectionTaxEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The tax codes in tax groups of the Total compensation statement section</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[TotalCompensationStatementSection](#TotalCompensationStatementSection)||<a href="HcmTotalCompStatementSectionTaxEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionTaxEntity</a>|
|[TaxCode](#TaxCode)||<a href="HcmTotalCompStatementSectionTaxEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionTaxEntity</a>|
|[TaxCodeGroupType](#TaxCodeGroupType)||<a href="HcmTotalCompStatementSectionTaxEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionTaxEntity</a>|
|[TaxGroup](#TaxGroup)||<a href="HcmTotalCompStatementSectionTaxEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionTaxEntity</a>|
|[StatementSectionId](#StatementSectionId)||<a href="HcmTotalCompStatementSectionTaxEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionTaxEntity</a>|
|[TaxCodeId](#TaxCodeId)||<a href="HcmTotalCompStatementSectionTaxEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionTaxEntity</a>|
|[NullableTaxCodeId](#NullableTaxCodeId)||<a href="HcmTotalCompStatementSectionTaxEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionTaxEntity</a>|
|[CountryRegionId](#CountryRegionId)||<a href="HcmTotalCompStatementSectionTaxEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionTaxEntity</a>|
|[NullableCountryRegionId](#NullableCountryRegionId)||<a href="HcmTotalCompStatementSectionTaxEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionTaxEntity</a>|
|[TaxGroupId](#TaxGroupId)||<a href="HcmTotalCompStatementSectionTaxEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionTaxEntity</a>|
|[NullableTaxGroupId](#NullableTaxGroupId)||<a href="HcmTotalCompStatementSectionTaxEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionTaxEntity</a>|
|[Relationship_HcmTotalCompStatementSectionHeaderEntityRelationshipId](#Relationship_HcmTotalCompStatementSectionHeaderEntityRelationshipId)||<a href="HcmTotalCompStatementSectionTaxEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionTaxEntity</a>|
|[BackingTable_HcmTotalCompStatementSectionTaxRelationshipId](#BackingTable_HcmTotalCompStatementSectionTaxRelationshipId)||<a href="HcmTotalCompStatementSectionTaxEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionTaxEntity</a>|

### <a href=#TotalCompensationStatementSection name="TotalCompensationStatementSection">TotalCompensationStatementSection</a>

First included in: HRM/HcmTotalCompStatementSectionTaxEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalCompensationStatementSection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxCode name="TaxCode">TaxCode</a>

First included in: HRM/HcmTotalCompStatementSectionTaxEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxCodeGroupType name="TaxCodeGroupType">TaxCodeGroupType</a>

First included in: HRM/HcmTotalCompStatementSectionTaxEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCodeGroupType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxGroup name="TaxGroup">TaxGroup</a>

First included in: HRM/HcmTotalCompStatementSectionTaxEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatementSectionId name="StatementSectionId">StatementSectionId</a>

First included in: HRM/HcmTotalCompStatementSectionTaxEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatementSectionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxCodeId name="TaxCodeId">TaxCodeId</a>

First included in: HRM/HcmTotalCompStatementSectionTaxEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NullableTaxCodeId name="NullableTaxCodeId">NullableTaxCodeId</a>

First included in: HRM/HcmTotalCompStatementSectionTaxEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NullableTaxCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountryRegionId name="CountryRegionId">CountryRegionId</a>

First included in: HRM/HcmTotalCompStatementSectionTaxEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NullableCountryRegionId name="NullableCountryRegionId">NullableCountryRegionId</a>

First included in: HRM/HcmTotalCompStatementSectionTaxEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NullableCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxGroupId name="TaxGroupId">TaxGroupId</a>

First included in: HRM/HcmTotalCompStatementSectionTaxEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NullableTaxGroupId name="NullableTaxGroupId">NullableTaxGroupId</a>

First included in: HRM/HcmTotalCompStatementSectionTaxEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NullableTaxGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_HcmTotalCompStatementSectionHeaderEntityRelationshipId name="Relationship_HcmTotalCompStatementSectionHeaderEntityRelationshipId">Relationship_HcmTotalCompStatementSectionHeaderEntityRelationshipId</a>

First included in: HRM/HcmTotalCompStatementSectionTaxEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HcmTotalCompStatementSectionHeaderEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_HcmTotalCompStatementSectionTaxRelationshipId name="BackingTable_HcmTotalCompStatementSectionTaxRelationshipId">BackingTable_HcmTotalCompStatementSectionTaxRelationshipId</a>

First included in: HRM/HcmTotalCompStatementSectionTaxEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_HcmTotalCompStatementSectionTaxRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/HumanResources/HumanResource/Group/HcmTotalCompStatementSectionTax.md" target="_blank">/core/operationsCommon/Tables/HumanResources/HumanResource/Group/HcmTotalCompStatementSectionTax.cdm.json/HcmTotalCompStatementSectionTax</a></td><td><a href="../../../Tables/HumanResources/HumanResource/Group/HcmTotalCompStatementSectionTax.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
