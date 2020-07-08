---
title: FiscalOrganizationFiscalAuditorEntity in GeneralLedger - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Fiscal auditor entity in GeneralLedger(FiscalOrganizationFiscalAuditorEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/FiscalOrganizationFiscalAuditorEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fiscal auditor entity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CVMNumber](#CVMNumber)||<a href="FiscalOrganizationFiscalAuditorEntity.md" target="_blank">GeneralLedger/FiscalOrganizationFiscalAuditorEntity</a>|
|[Name](#Name)||<a href="FiscalOrganizationFiscalAuditorEntity.md" target="_blank">GeneralLedger/FiscalOrganizationFiscalAuditorEntity</a>|
|[RootFiscalEstablishmentDataArea](#RootFiscalEstablishmentDataArea)||<a href="FiscalOrganizationFiscalAuditorEntity.md" target="_blank">GeneralLedger/FiscalOrganizationFiscalAuditorEntity</a>|
|[RootFiscalEstablishment](#RootFiscalEstablishment)||<a href="FiscalOrganizationFiscalAuditorEntity.md" target="_blank">GeneralLedger/FiscalOrganizationFiscalAuditorEntity</a>|
|[BackingTable_FBFiscalAuditor_BRRelationshipId](#BackingTable_FBFiscalAuditor_BRRelationshipId)||<a href="FiscalOrganizationFiscalAuditorEntity.md" target="_blank">GeneralLedger/FiscalOrganizationFiscalAuditorEntity</a>|

### <a href=#CVMNumber name="CVMNumber">CVMNumber</a>

First included in: GeneralLedger/FiscalOrganizationFiscalAuditorEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CVMNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: GeneralLedger/FiscalOrganizationFiscalAuditorEntity (this entity)  

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

### <a href=#RootFiscalEstablishmentDataArea name="RootFiscalEstablishmentDataArea">RootFiscalEstablishmentDataArea</a>

First included in: GeneralLedger/FiscalOrganizationFiscalAuditorEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Root company</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RootFiscalEstablishmentDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Root company</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RootFiscalEstablishment name="RootFiscalEstablishment">RootFiscalEstablishment</a>

First included in: GeneralLedger/FiscalOrganizationFiscalAuditorEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RootFiscalEstablishment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_FBFiscalAuditor_BRRelationshipId name="BackingTable_FBFiscalAuditor_BRRelationshipId">BackingTable_FBFiscalAuditor_BRRelationshipId</a>

First included in: GeneralLedger/FiscalOrganizationFiscalAuditorEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_FBFiscalAuditor_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FiscalBooksBrazil/Main/FBFiscalAuditor_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBFiscalAuditor_BR.cdm.json/FBFiscalAuditor_BR</a></td><td><a href="../../../Tables/Finance/FiscalBooksBrazil/Main/FBFiscalAuditor_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
