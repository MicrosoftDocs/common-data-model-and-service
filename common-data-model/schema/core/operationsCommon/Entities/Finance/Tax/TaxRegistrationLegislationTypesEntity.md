---
title: TaxRegistrationLegislationTypesEntity in Tax - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# Sales tax legislative registration types in Tax(TaxRegistrationLegislationTypesEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Tax/TaxRegistrationLegislationTypesEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax legislative registration types</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[TaxRegistrationTypeApplicabilityRule](#TaxRegistrationTypeApplicabilityRule)||<a href="TaxRegistrationLegislationTypesEntity.md" target="_blank">Tax/TaxRegistrationLegislationTypesEntity</a>|
|[RegistrationTypesList](#RegistrationTypesList)||<a href="TaxRegistrationLegislationTypesEntity.md" target="_blank">Tax/TaxRegistrationLegislationTypesEntity</a>|
|[CountryRegionId](#CountryRegionId)||<a href="TaxRegistrationLegislationTypesEntity.md" target="_blank">Tax/TaxRegistrationLegislationTypesEntity</a>|
|[TaxRegistrationTypeApplicabilityRule_TaxRegistrationType](#TaxRegistrationTypeApplicabilityRule_TaxRegistrationType)||<a href="TaxRegistrationLegislationTypesEntity.md" target="_blank">Tax/TaxRegistrationLegislationTypesEntity</a>|
|[RegistrationType](#RegistrationType)||<a href="TaxRegistrationLegislationTypesEntity.md" target="_blank">Tax/TaxRegistrationLegislationTypesEntity</a>|
|[BackingTable_TaxRegistrationLegislationTypesRelationshipId](#BackingTable_TaxRegistrationLegislationTypesRelationshipId)||<a href="TaxRegistrationLegislationTypesEntity.md" target="_blank">Tax/TaxRegistrationLegislationTypesEntity</a>|

### <a href=#TaxRegistrationTypeApplicabilityRule name="TaxRegistrationTypeApplicabilityRule">TaxRegistrationTypeApplicabilityRule</a>

First included in: Tax/TaxRegistrationLegislationTypesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRegistrationTypeApplicabilityRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RegistrationTypesList name="RegistrationTypesList">RegistrationTypesList</a>

First included in: Tax/TaxRegistrationLegislationTypesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegistrationTypesList attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountryRegionId name="CountryRegionId">CountryRegionId</a>

First included in: Tax/TaxRegistrationLegislationTypesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxRegistrationTypeApplicabilityRule_TaxRegistrationType name="TaxRegistrationTypeApplicabilityRule_TaxRegistrationType">TaxRegistrationTypeApplicabilityRule_TaxRegistrationType</a>

First included in: Tax/TaxRegistrationLegislationTypesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRegistrationTypeApplicabilityRule_TaxRegistrationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RegistrationType name="RegistrationType">RegistrationType</a>

First included in: Tax/TaxRegistrationLegislationTypesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegistrationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TaxRegistrationLegislationTypesRelationshipId name="BackingTable_TaxRegistrationLegislationTypesRelationshipId">BackingTable_TaxRegistrationLegislationTypesRelationshipId</a>

First included in: Tax/TaxRegistrationLegislationTypesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TaxRegistrationLegislationTypesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Tax/Parameter/TaxRegistrationLegislationTypes.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Parameter/TaxRegistrationLegislationTypes.cdm.json/TaxRegistrationLegislationTypes</a></td><td><a href="../../../Tables/Finance/Tax/Parameter/TaxRegistrationLegislationTypes.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
