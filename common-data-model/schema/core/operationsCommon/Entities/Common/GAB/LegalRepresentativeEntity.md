---
title: LegalRepresentativeEntity in GAB - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Legal representative entity in GAB(LegalRepresentativeEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Common/GAB/LegalRepresentativeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Legal representative entity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[FiscalOrganization](#FiscalOrganization)||<a href="LegalRepresentativeEntity.md" target="_blank">GAB/LegalRepresentativeEntity</a>|
|[FiscalOrganizationRootFiscalEstablishmentDataArea](#FiscalOrganizationRootFiscalEstablishmentDataArea)||<a href="LegalRepresentativeEntity.md" target="_blank">GAB/LegalRepresentativeEntity</a>|
|[FiscalOrganizationRootFiscalEstablishment](#FiscalOrganizationRootFiscalEstablishment)||<a href="LegalRepresentativeEntity.md" target="_blank">GAB/LegalRepresentativeEntity</a>|
|[CPF](#CPF)||<a href="LegalRepresentativeEntity.md" target="_blank">GAB/LegalRepresentativeEntity</a>|
|[Name](#Name)||<a href="LegalRepresentativeEntity.md" target="_blank">GAB/LegalRepresentativeEntity</a>|
|[Role](#Role)||<a href="LegalRepresentativeEntity.md" target="_blank">GAB/LegalRepresentativeEntity</a>|
|[Location](#Location)||<a href="LegalRepresentativeEntity.md" target="_blank">GAB/LegalRepresentativeEntity</a>|
|[ValidatedInRFBAuthority](#ValidatedInRFBAuthority)||<a href="LegalRepresentativeEntity.md" target="_blank">GAB/LegalRepresentativeEntity</a>|
|[CRCState](#CRCState)||<a href="LegalRepresentativeEntity.md" target="_blank">GAB/LegalRepresentativeEntity</a>|
|[CRC](#CRC)||<a href="LegalRepresentativeEntity.md" target="_blank">GAB/LegalRepresentativeEntity</a>|
|[CRCExpirationDate](#CRCExpirationDate)||<a href="LegalRepresentativeEntity.md" target="_blank">GAB/LegalRepresentativeEntity</a>|
|[BackingTable_LegalRepresentative_BRRelationshipId](#BackingTable_LegalRepresentative_BRRelationshipId)||<a href="LegalRepresentativeEntity.md" target="_blank">GAB/LegalRepresentativeEntity</a>|

### <a href=#FiscalOrganization name="FiscalOrganization">FiscalOrganization</a>

First included in: GAB/LegalRepresentativeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalOrganization attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalOrganizationRootFiscalEstablishmentDataArea name="FiscalOrganizationRootFiscalEstablishmentDataArea">FiscalOrganizationRootFiscalEstablishmentDataArea</a>

First included in: GAB/LegalRepresentativeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Root company</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalOrganizationRootFiscalEstablishmentDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Root company</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalOrganizationRootFiscalEstablishment name="FiscalOrganizationRootFiscalEstablishment">FiscalOrganizationRootFiscalEstablishment</a>

First included in: GAB/LegalRepresentativeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalOrganizationRootFiscalEstablishment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CPF name="CPF">CPF</a>

First included in: GAB/LegalRepresentativeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CPF attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: GAB/LegalRepresentativeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Role name="Role">Role</a>

First included in: GAB/LegalRepresentativeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Role attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Location name="Location">Location</a>

First included in: GAB/LegalRepresentativeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Location attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidatedInRFBAuthority name="ValidatedInRFBAuthority">ValidatedInRFBAuthority</a>

First included in: GAB/LegalRepresentativeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidatedInRFBAuthority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CRCState name="CRCState">CRCState</a>

First included in: GAB/LegalRepresentativeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CRCState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CRC name="CRC">CRC</a>

First included in: GAB/LegalRepresentativeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CRC attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CRCExpirationDate name="CRCExpirationDate">CRCExpirationDate</a>

First included in: GAB/LegalRepresentativeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CRCExpirationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_LegalRepresentative_BRRelationshipId name="BackingTable_LegalRepresentative_BRRelationshipId">BackingTable_LegalRepresentative_BRRelationshipId</a>

First included in: GAB/LegalRepresentativeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_LegalRepresentative_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Bank/Miscellaneous/LegalRepresentative_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Miscellaneous/LegalRepresentative_BR.cdm.json/LegalRepresentative_BR</a></td><td><a href="../../../Tables/Finance/Bank/Miscellaneous/LegalRepresentative_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
