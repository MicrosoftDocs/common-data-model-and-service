---
title: TaxRegistrationTypeApplicabilityRule in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Tax registration types rules in Miscellaneous(TaxRegistrationTypeApplicabilityRule)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/Miscellaneous/TaxRegistrationTypeApplicabilityRule.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxRegistrationTypeApplicabilityRule/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax registration types rules</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxRegistrationTypeApplicabilityRule.md" target="_blank">Miscellaneous/TaxRegistrationTypeApplicabilityRule</a>|
|[CountryRegionId](#CountryRegionId)||<a href="TaxRegistrationTypeApplicabilityRule.md" target="_blank">Miscellaneous/TaxRegistrationTypeApplicabilityRule</a>|
|[Format](#Format)||<a href="TaxRegistrationTypeApplicabilityRule.md" target="_blank">Miscellaneous/TaxRegistrationTypeApplicabilityRule</a>|
|[IsPrimaryAddressRestricted](#IsPrimaryAddressRestricted)||<a href="TaxRegistrationTypeApplicabilityRule.md" target="_blank">Miscellaneous/TaxRegistrationTypeApplicabilityRule</a>|
|[IsRegistrationNumberUnique](#IsRegistrationNumberUnique)||<a href="TaxRegistrationTypeApplicabilityRule.md" target="_blank">Miscellaneous/TaxRegistrationTypeApplicabilityRule</a>|
|[IsRegistrationNumberUpdateable](#IsRegistrationNumberUpdateable)||<a href="TaxRegistrationTypeApplicabilityRule.md" target="_blank">Miscellaneous/TaxRegistrationTypeApplicabilityRule</a>|
|[PartyTypeRestriction](#PartyTypeRestriction)||<a href="TaxRegistrationTypeApplicabilityRule.md" target="_blank">Miscellaneous/TaxRegistrationTypeApplicabilityRule</a>|
|[TaxRegistrationAuthority](#TaxRegistrationAuthority)||<a href="TaxRegistrationTypeApplicabilityRule.md" target="_blank">Miscellaneous/TaxRegistrationTypeApplicabilityRule</a>|
|[TaxRegistrationType](#TaxRegistrationType)||<a href="TaxRegistrationTypeApplicabilityRule.md" target="_blank">Miscellaneous/TaxRegistrationTypeApplicabilityRule</a>|
|[Relationship_LogisticsAddressCountryRegionRelationshipId](#Relationship_LogisticsAddressCountryRegionRelationshipId)||<a href="TaxRegistrationTypeApplicabilityRule.md" target="_blank">Miscellaneous/TaxRegistrationTypeApplicabilityRule</a>|
|[Relationship_TaxAuthorityAddressRelationshipId](#Relationship_TaxAuthorityAddressRelationshipId)||<a href="TaxRegistrationTypeApplicabilityRule.md" target="_blank">Miscellaneous/TaxRegistrationTypeApplicabilityRule</a>|
|[Relationship_TaxRegstrationTypeRelationshipId](#Relationship_TaxRegstrationTypeRelationshipId)||<a href="TaxRegistrationTypeApplicabilityRule.md" target="_blank">Miscellaneous/TaxRegistrationTypeApplicabilityRule</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/TaxRegistrationTypeApplicabilityRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxRegistrationTypeApplicabilityRule/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CountryRegionId name="CountryRegionId">CountryRegionId</a>

First included in: Miscellaneous/TaxRegistrationTypeApplicabilityRule (this entity)  

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

First included in: Miscellaneous/TaxRegistrationTypeApplicabilityRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Format attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrimaryAddressRestricted name="IsPrimaryAddressRestricted">IsPrimaryAddressRestricted</a>

First included in: Miscellaneous/TaxRegistrationTypeApplicabilityRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrimaryAddressRestricted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsRegistrationNumberUnique name="IsRegistrationNumberUnique">IsRegistrationNumberUnique</a>

First included in: Miscellaneous/TaxRegistrationTypeApplicabilityRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRegistrationNumberUnique attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsRegistrationNumberUpdateable name="IsRegistrationNumberUpdateable">IsRegistrationNumberUpdateable</a>

First included in: Miscellaneous/TaxRegistrationTypeApplicabilityRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRegistrationNumberUpdateable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PartyTypeRestriction name="PartyTypeRestriction">PartyTypeRestriction</a>

First included in: Miscellaneous/TaxRegistrationTypeApplicabilityRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyTypeRestriction attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxRegistrationAuthority name="TaxRegistrationAuthority">TaxRegistrationAuthority</a>

First included in: Miscellaneous/TaxRegistrationTypeApplicabilityRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax authority</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRegistrationAuthority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax authority</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxRegistrationType name="TaxRegistrationType">TaxRegistrationType</a>

First included in: Miscellaneous/TaxRegistrationTypeApplicabilityRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRegistrationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_LogisticsAddressCountryRegionRelationshipId name="Relationship_LogisticsAddressCountryRegionRelationshipId">Relationship_LogisticsAddressCountryRegionRelationshipId</a>

First included in: Miscellaneous/TaxRegistrationTypeApplicabilityRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsAddressCountryRegionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/LogisticsAddressCountryRegion.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Group/LogisticsAddressCountryRegion.cdm.json/LogisticsAddressCountryRegion</a></td><td><a href="../../../Common/GAB/Group/LogisticsAddressCountryRegion.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxAuthorityAddressRelationshipId name="Relationship_TaxAuthorityAddressRelationshipId">Relationship_TaxAuthorityAddressRelationshipId</a>

First included in: Miscellaneous/TaxRegistrationTypeApplicabilityRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxAuthorityAddressRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/TaxAuthorityAddress.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxAuthorityAddress.cdm.json/TaxAuthorityAddress</a></td><td><a href="../Group/TaxAuthorityAddress.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxRegstrationTypeRelationshipId name="Relationship_TaxRegstrationTypeRelationshipId">Relationship_TaxRegstrationTypeRelationshipId</a>

First included in: Miscellaneous/TaxRegistrationTypeApplicabilityRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxRegstrationTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxRegistrationType.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Miscellaneous/TaxRegistrationType.cdm.json/TaxRegistrationType</a></td><td><a href="TaxRegistrationType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
