---
title: HcmApplicantTrustedPositionEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# HcmApplicantTrustedPositionEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/HRM/HcmApplicantTrustedPositionEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ApplicantId](#ApplicantId)||<a href="HcmApplicantTrustedPositionEntity.md" target="_blank">HRM/HcmApplicantTrustedPositionEntity</a>|
|[Employer](#Employer)||<a href="HcmApplicantTrustedPositionEntity.md" target="_blank">HRM/HcmApplicantTrustedPositionEntity</a>|
|[Note](#Note)||<a href="HcmApplicantTrustedPositionEntity.md" target="_blank">HRM/HcmApplicantTrustedPositionEntity</a>|
|[Position](#Position)||<a href="HcmApplicantTrustedPositionEntity.md" target="_blank">HRM/HcmApplicantTrustedPositionEntity</a>|
|[StartDate](#StartDate)||<a href="HcmApplicantTrustedPositionEntity.md" target="_blank">HRM/HcmApplicantTrustedPositionEntity</a>|
|[EndDate](#EndDate)||<a href="HcmApplicantTrustedPositionEntity.md" target="_blank">HRM/HcmApplicantTrustedPositionEntity</a>|
|[BackingTable_HcmPersonTrustedPositionEntityRelationshipId](#BackingTable_HcmPersonTrustedPositionEntityRelationshipId)||<a href="HcmApplicantTrustedPositionEntity.md" target="_blank">HRM/HcmApplicantTrustedPositionEntity</a>|

### <a href=#ApplicantId name="ApplicantId">ApplicantId</a>

First included in: HRM/HcmApplicantTrustedPositionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplicantId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Employer name="Employer">Employer</a>

First included in: HRM/HcmApplicantTrustedPositionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Employer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Note name="Note">Note</a>

First included in: HRM/HcmApplicantTrustedPositionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Note attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Position name="Position">Position</a>

First included in: HRM/HcmApplicantTrustedPositionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Position attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartDate name="StartDate">StartDate</a>

First included in: HRM/HcmApplicantTrustedPositionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndDate name="EndDate">EndDate</a>

First included in: HRM/HcmApplicantTrustedPositionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_HcmPersonTrustedPositionEntityRelationshipId name="BackingTable_HcmPersonTrustedPositionEntityRelationshipId">BackingTable_HcmPersonTrustedPositionEntityRelationshipId</a>

First included in: HRM/HcmApplicantTrustedPositionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_HcmPersonTrustedPositionEntityRelationshipId attribute are listed below.</summary>

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
