---
title: DirPartyTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Global address book

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Common/GAB/Main/DirPartyTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DirPartyTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Global address book</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[KnownAs](#KnownAs)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[LanguageId](#LanguageId)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[Name](#Name)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[NameAlias](#NameAlias)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[PartyNumber](#PartyNumber)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[PrimaryAddressLocation](#PrimaryAddressLocation)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[PrimaryContactEmail](#PrimaryContactEmail)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[PrimaryContactFax](#PrimaryContactFax)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[PrimaryContactPhone](#PrimaryContactPhone)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[PrimaryContactTelex](#PrimaryContactTelex)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[PrimaryContactURL](#PrimaryContactURL)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[PrimaryContactFacebook](#PrimaryContactFacebook)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[PrimaryContactTwitter](#PrimaryContactTwitter)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[PrimaryContactLinkedIn](#PrimaryContactLinkedIn)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[AddressBookNames](#AddressBookNames)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[LegacyInstanceRelationType](#LegacyInstanceRelationType)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[Relationship_LanguageTableRelationshipId](#Relationship_LanguageTableRelationshipId)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[Relationship_LogisticsElectronicAddress_EmailRelationshipId](#Relationship_LogisticsElectronicAddress_EmailRelationshipId)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[Relationship_LogisticsElectronicAddress_FaxRelationshipId](#Relationship_LogisticsElectronicAddress_FaxRelationshipId)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[Relationship_LogisticsElectronicAddress_PhoneRelationshipId](#Relationship_LogisticsElectronicAddress_PhoneRelationshipId)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[Relationship_LogisticsElectronicAddress_TelexRelationshipId](#Relationship_LogisticsElectronicAddress_TelexRelationshipId)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[Relationship_LogisticsElectronicAddress_URLRelationshipId](#Relationship_LogisticsElectronicAddress_URLRelationshipId)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[Relationship_LogisticsElectronicAddress_FacebookRelationshipId](#Relationship_LogisticsElectronicAddress_FacebookRelationshipId)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[Relationship_LogisticsElectronicAddress_TwitterRelationshipId](#Relationship_LogisticsElectronicAddress_TwitterRelationshipId)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[Relationship_LogisticsElectronicAddress_LinkedInRelationshipId](#Relationship_LogisticsElectronicAddress_LinkedInRelationshipId)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[Relationship_LogisticsLocation_PrimaryAddressRelationshipId](#Relationship_LogisticsLocation_PrimaryAddressRelationshipId)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|
|[Relationship_LogisticsPostalAddressRelationshipId](#Relationship_LogisticsPostalAddressRelationshipId)||<a href="DirPartyTable.md" target="_blank">Main/DirPartyTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DirPartyTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Party type</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Party type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#KnownAs name="KnownAs">KnownAs</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Known as</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KnownAs attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Known as</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LanguageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Main/DirPartyTable (this entity)  

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

### <a href=#NameAlias name="NameAlias">NameAlias</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NameAlias attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PartyNumber name="PartyNumber">PartyNumber</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryAddressLocation name="PrimaryAddressLocation">PrimaryAddressLocation</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryAddressLocation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PrimaryContactEmail name="PrimaryContactEmail">PrimaryContactEmail</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email address</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactEmail attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Email address</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PrimaryContactFax name="PrimaryContactFax">PrimaryContactFax</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fax</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PrimaryContactPhone name="PrimaryContactPhone">PrimaryContactPhone</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Phone</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactPhone attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Phone</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PrimaryContactTelex name="PrimaryContactTelex">PrimaryContactTelex</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Telex</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactTelex attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Telex</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PrimaryContactURL name="PrimaryContactURL">PrimaryContactURL</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>URL</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactURL attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>URL</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PrimaryContactFacebook name="PrimaryContactFacebook">PrimaryContactFacebook</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Facebook</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFacebook attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Facebook</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PrimaryContactTwitter name="PrimaryContactTwitter">PrimaryContactTwitter</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Twitter</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactTwitter attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Twitter</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PrimaryContactLinkedIn name="PrimaryContactLinkedIn">PrimaryContactLinkedIn</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactLinkedIn attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>LinkedIn</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AddressBookNames name="AddressBookNames">AddressBookNames</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressBookNames attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegacyInstanceRelationType name="LegacyInstanceRelationType">LegacyInstanceRelationType</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegacyInstanceRelationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_LanguageTableRelationshipId name="Relationship_LanguageTableRelationshipId">Relationship_LanguageTableRelationshipId</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LanguageTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Group/LanguageTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Group/LanguageTable.cdm.json/LanguageTable</a></td><td><a href="../../../System/SystemAdministration/Group/LanguageTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LogisticsElectronicAddress_EmailRelationshipId name="Relationship_LogisticsElectronicAddress_EmailRelationshipId">Relationship_LogisticsElectronicAddress_EmailRelationshipId</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsElectronicAddress_EmailRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="LogisticsElectronicAddress.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/LogisticsElectronicAddress.cdm.json/LogisticsElectronicAddress</a></td><td><a href="LogisticsElectronicAddress.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LogisticsElectronicAddress_FaxRelationshipId name="Relationship_LogisticsElectronicAddress_FaxRelationshipId">Relationship_LogisticsElectronicAddress_FaxRelationshipId</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsElectronicAddress_FaxRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="LogisticsElectronicAddress.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/LogisticsElectronicAddress.cdm.json/LogisticsElectronicAddress</a></td><td><a href="LogisticsElectronicAddress.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LogisticsElectronicAddress_PhoneRelationshipId name="Relationship_LogisticsElectronicAddress_PhoneRelationshipId">Relationship_LogisticsElectronicAddress_PhoneRelationshipId</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsElectronicAddress_PhoneRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="LogisticsElectronicAddress.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/LogisticsElectronicAddress.cdm.json/LogisticsElectronicAddress</a></td><td><a href="LogisticsElectronicAddress.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LogisticsElectronicAddress_TelexRelationshipId name="Relationship_LogisticsElectronicAddress_TelexRelationshipId">Relationship_LogisticsElectronicAddress_TelexRelationshipId</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsElectronicAddress_TelexRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="LogisticsElectronicAddress.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/LogisticsElectronicAddress.cdm.json/LogisticsElectronicAddress</a></td><td><a href="LogisticsElectronicAddress.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LogisticsElectronicAddress_URLRelationshipId name="Relationship_LogisticsElectronicAddress_URLRelationshipId">Relationship_LogisticsElectronicAddress_URLRelationshipId</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsElectronicAddress_URLRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="LogisticsElectronicAddress.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/LogisticsElectronicAddress.cdm.json/LogisticsElectronicAddress</a></td><td><a href="LogisticsElectronicAddress.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LogisticsElectronicAddress_FacebookRelationshipId name="Relationship_LogisticsElectronicAddress_FacebookRelationshipId">Relationship_LogisticsElectronicAddress_FacebookRelationshipId</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsElectronicAddress_FacebookRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="LogisticsElectronicAddress.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/LogisticsElectronicAddress.cdm.json/LogisticsElectronicAddress</a></td><td><a href="LogisticsElectronicAddress.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LogisticsElectronicAddress_TwitterRelationshipId name="Relationship_LogisticsElectronicAddress_TwitterRelationshipId">Relationship_LogisticsElectronicAddress_TwitterRelationshipId</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsElectronicAddress_TwitterRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="LogisticsElectronicAddress.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/LogisticsElectronicAddress.cdm.json/LogisticsElectronicAddress</a></td><td><a href="LogisticsElectronicAddress.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LogisticsElectronicAddress_LinkedInRelationshipId name="Relationship_LogisticsElectronicAddress_LinkedInRelationshipId">Relationship_LogisticsElectronicAddress_LinkedInRelationshipId</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsElectronicAddress_LinkedInRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="LogisticsElectronicAddress.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/LogisticsElectronicAddress.cdm.json/LogisticsElectronicAddress</a></td><td><a href="LogisticsElectronicAddress.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LogisticsLocation_PrimaryAddressRelationshipId name="Relationship_LogisticsLocation_PrimaryAddressRelationshipId">Relationship_LogisticsLocation_PrimaryAddressRelationshipId</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsLocation_PrimaryAddressRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="LogisticsLocation.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/LogisticsLocation.cdm.json/LogisticsLocation</a></td><td><a href="LogisticsLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LogisticsPostalAddressRelationshipId name="Relationship_LogisticsPostalAddressRelationshipId">Relationship_LogisticsPostalAddressRelationshipId</a>

First included in: Main/DirPartyTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsPostalAddressRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="LogisticsPostalAddress.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/LogisticsPostalAddress.cdm.json/LogisticsPostalAddress</a></td><td><a href="LogisticsPostalAddress.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
