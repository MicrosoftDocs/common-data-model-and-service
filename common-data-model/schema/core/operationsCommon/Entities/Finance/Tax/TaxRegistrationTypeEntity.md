---
title: TaxRegistrationTypeEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Sales tax registration types

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Tax/TaxRegistrationTypeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax registration types</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RegistrationType](#RegistrationType)||<a href="TaxRegistrationTypeEntity.md" target="_blank">Tax/TaxRegistrationTypeEntity</a>|
|[Description](#Description)||<a href="TaxRegistrationTypeEntity.md" target="_blank">Tax/TaxRegistrationTypeEntity</a>|
|[CountryRegionId](#CountryRegionId)||<a href="TaxRegistrationTypeEntity.md" target="_blank">Tax/TaxRegistrationTypeEntity</a>|
|[Format](#Format)||<a href="TaxRegistrationTypeEntity.md" target="_blank">Tax/TaxRegistrationTypeEntity</a>|
|[IsPrimaryAddressRestricted](#IsPrimaryAddressRestricted)||<a href="TaxRegistrationTypeEntity.md" target="_blank">Tax/TaxRegistrationTypeEntity</a>|
|[IsRegistrationNumberUnique](#IsRegistrationNumberUnique)||<a href="TaxRegistrationTypeEntity.md" target="_blank">Tax/TaxRegistrationTypeEntity</a>|
|[IsRegistrationNumberUpdateable](#IsRegistrationNumberUpdateable)||<a href="TaxRegistrationTypeEntity.md" target="_blank">Tax/TaxRegistrationTypeEntity</a>|
|[PartyTypeRestriction](#PartyTypeRestriction)||<a href="TaxRegistrationTypeEntity.md" target="_blank">Tax/TaxRegistrationTypeEntity</a>|
|[RegistrationAuthority](#RegistrationAuthority)||<a href="TaxRegistrationTypeEntity.md" target="_blank">Tax/TaxRegistrationTypeEntity</a>|
|[TaxRegistrationType](#TaxRegistrationType)||<a href="TaxRegistrationTypeEntity.md" target="_blank">Tax/TaxRegistrationTypeEntity</a>|
|[BackingTable_TaxRegistrationTypeApplicabilityRuleRelationshipId](#BackingTable_TaxRegistrationTypeApplicabilityRuleRelationshipId)||<a href="TaxRegistrationTypeEntity.md" target="_blank">Tax/TaxRegistrationTypeEntity</a>|

### <a href=#RegistrationType name="RegistrationType">RegistrationType</a>

First included in: Tax/TaxRegistrationTypeEntity (this entity)  

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

### <a href=#Description name="Description">Description</a>

First included in: Tax/TaxRegistrationTypeEntity (this entity)  

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

### <a href=#CountryRegionId name="CountryRegionId">CountryRegionId</a>

First included in: Tax/TaxRegistrationTypeEntity (this entity)  

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

### <a href=#Format name="Format">Format</a>

First included in: Tax/TaxRegistrationTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Format attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrimaryAddressRestricted name="IsPrimaryAddressRestricted">IsPrimaryAddressRestricted</a>

First included in: Tax/TaxRegistrationTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrimaryAddressRestricted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRegistrationNumberUnique name="IsRegistrationNumberUnique">IsRegistrationNumberUnique</a>

First included in: Tax/TaxRegistrationTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRegistrationNumberUnique attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRegistrationNumberUpdateable name="IsRegistrationNumberUpdateable">IsRegistrationNumberUpdateable</a>

First included in: Tax/TaxRegistrationTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRegistrationNumberUpdateable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PartyTypeRestriction name="PartyTypeRestriction">PartyTypeRestriction</a>

First included in: Tax/TaxRegistrationTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyTypeRestriction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RegistrationAuthority name="RegistrationAuthority">RegistrationAuthority</a>

First included in: Tax/TaxRegistrationTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegistrationAuthority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxRegistrationType name="TaxRegistrationType">TaxRegistrationType</a>

First included in: Tax/TaxRegistrationTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRegistrationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TaxRegistrationTypeApplicabilityRuleRelationshipId name="BackingTable_TaxRegistrationTypeApplicabilityRuleRelationshipId">BackingTable_TaxRegistrationTypeApplicabilityRuleRelationshipId</a>

First included in: Tax/TaxRegistrationTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TaxRegistrationTypeApplicabilityRuleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Tax/Miscellaneous/TaxRegistrationTypeApplicabilityRule.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Miscellaneous/TaxRegistrationTypeApplicabilityRule.cdm.json/TaxRegistrationTypeApplicabilityRule</a></td><td><a href="../../../Tables/Finance/Tax/Miscellaneous/TaxRegistrationTypeApplicabilityRule.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
