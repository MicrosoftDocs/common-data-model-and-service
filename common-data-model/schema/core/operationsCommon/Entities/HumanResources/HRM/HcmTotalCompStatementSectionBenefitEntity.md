---
title: HcmTotalCompStatementSectionBenefitEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# The benefit codes in benefit group of the Total compensation statement section

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/HRM/HcmTotalCompStatementSectionBenefitEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The benefit codes in benefit group of the Total compensation statement section</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Benefit](#Benefit)||<a href="HcmTotalCompStatementSectionBenefitEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionBenefitEntity</a>|
|[StatementSection](#StatementSection)||<a href="HcmTotalCompStatementSectionBenefitEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionBenefitEntity</a>|
|[BenefitId](#BenefitId)||<a href="HcmTotalCompStatementSectionBenefitEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionBenefitEntity</a>|
|[StatementSectionId](#StatementSectionId)||<a href="HcmTotalCompStatementSectionBenefitEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionBenefitEntity</a>|
|[Relationship_HcmTotalCompStatementSectionHeaderEntityRelationshipId](#Relationship_HcmTotalCompStatementSectionHeaderEntityRelationshipId)||<a href="HcmTotalCompStatementSectionBenefitEntity.md" target="_blank">HRM/HcmTotalCompStatementSectionBenefitEntity</a>|

### <a href=#Benefit name="Benefit">Benefit</a>

First included in: HRM/HcmTotalCompStatementSectionBenefitEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Benefit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatementSection name="StatementSection">StatementSection</a>

First included in: HRM/HcmTotalCompStatementSectionBenefitEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatementSection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BenefitId name="BenefitId">BenefitId</a>

First included in: HRM/HcmTotalCompStatementSectionBenefitEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BenefitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatementSectionId name="StatementSectionId">StatementSectionId</a>

First included in: HRM/HcmTotalCompStatementSectionBenefitEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatementSectionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_HcmTotalCompStatementSectionHeaderEntityRelationshipId name="Relationship_HcmTotalCompStatementSectionHeaderEntityRelationshipId">Relationship_HcmTotalCompStatementSectionHeaderEntityRelationshipId</a>

First included in: HRM/HcmTotalCompStatementSectionBenefitEntity (this entity)  

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
