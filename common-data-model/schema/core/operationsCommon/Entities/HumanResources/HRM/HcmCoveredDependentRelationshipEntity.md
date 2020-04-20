---
title: HcmCoveredDependentRelationshipEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# HcmCoveredDependentRelationshipEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/HRM/HcmCoveredDependentRelationshipEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[PartyRelationship](#PartyRelationship)||<a href="HcmCoveredDependentRelationshipEntity.md" target="_blank">HRM/HcmCoveredDependentRelationshipEntity</a>|
|[ValidFrom](#ValidFrom)||<a href="HcmCoveredDependentRelationshipEntity.md" target="_blank">HRM/HcmCoveredDependentRelationshipEntity</a>|
|[ValidTo](#ValidTo)||<a href="HcmCoveredDependentRelationshipEntity.md" target="_blank">HRM/HcmCoveredDependentRelationshipEntity</a>|
|[WorkerEnrolledBenefit](#WorkerEnrolledBenefit)||<a href="HcmCoveredDependentRelationshipEntity.md" target="_blank">HRM/HcmCoveredDependentRelationshipEntity</a>|
|[ChildParty](#ChildParty)||<a href="HcmCoveredDependentRelationshipEntity.md" target="_blank">HRM/HcmCoveredDependentRelationshipEntity</a>|
|[PartyRelationshipDataAreaId](#PartyRelationshipDataAreaId)||<a href="HcmCoveredDependentRelationshipEntity.md" target="_blank">HRM/HcmCoveredDependentRelationshipEntity</a>|
|[ParentParty](#ParentParty)||<a href="HcmCoveredDependentRelationshipEntity.md" target="_blank">HRM/HcmCoveredDependentRelationshipEntity</a>|
|[RelationshipTypeId](#RelationshipTypeId)||<a href="HcmCoveredDependentRelationshipEntity.md" target="_blank">HRM/HcmCoveredDependentRelationshipEntity</a>|
|[PartyRelationshipValidFrom](#PartyRelationshipValidFrom)||<a href="HcmCoveredDependentRelationshipEntity.md" target="_blank">HRM/HcmCoveredDependentRelationshipEntity</a>|
|[PartyRelationshipValidTo](#PartyRelationshipValidTo)||<a href="HcmCoveredDependentRelationshipEntity.md" target="_blank">HRM/HcmCoveredDependentRelationshipEntity</a>|
|[ChildPartyId](#ChildPartyId)||<a href="HcmCoveredDependentRelationshipEntity.md" target="_blank">HRM/HcmCoveredDependentRelationshipEntity</a>|
|[ParentPartyId](#ParentPartyId)||<a href="HcmCoveredDependentRelationshipEntity.md" target="_blank">HRM/HcmCoveredDependentRelationshipEntity</a>|
|[Benefit](#Benefit)||<a href="HcmCoveredDependentRelationshipEntity.md" target="_blank">HRM/HcmCoveredDependentRelationshipEntity</a>|
|[EnrollmentStart](#EnrollmentStart)||<a href="HcmCoveredDependentRelationshipEntity.md" target="_blank">HRM/HcmCoveredDependentRelationshipEntity</a>|
|[EnrollmentEnd](#EnrollmentEnd)||<a href="HcmCoveredDependentRelationshipEntity.md" target="_blank">HRM/HcmCoveredDependentRelationshipEntity</a>|
|[Worker](#Worker)||<a href="HcmCoveredDependentRelationshipEntity.md" target="_blank">HRM/HcmCoveredDependentRelationshipEntity</a>|
|[BenefitId](#BenefitId)||<a href="HcmCoveredDependentRelationshipEntity.md" target="_blank">HRM/HcmCoveredDependentRelationshipEntity</a>|
|[PersonnelNumber](#PersonnelNumber)||<a href="HcmCoveredDependentRelationshipEntity.md" target="_blank">HRM/HcmCoveredDependentRelationshipEntity</a>|
|[Relationship_WorkerEnrolledBenefitRelationshipId](#Relationship_WorkerEnrolledBenefitRelationshipId)||<a href="HcmCoveredDependentRelationshipEntity.md" target="_blank">HRM/HcmCoveredDependentRelationshipEntity</a>|

### <a href=#PartyRelationship name="PartyRelationship">PartyRelationship</a>

First included in: HRM/HcmCoveredDependentRelationshipEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyRelationship attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: HRM/HcmCoveredDependentRelationshipEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: HRM/HcmCoveredDependentRelationshipEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerEnrolledBenefit name="WorkerEnrolledBenefit">WorkerEnrolledBenefit</a>

First included in: HRM/HcmCoveredDependentRelationshipEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerEnrolledBenefit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChildParty name="ChildParty">ChildParty</a>

First included in: HRM/HcmCoveredDependentRelationshipEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChildParty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PartyRelationshipDataAreaId name="PartyRelationshipDataAreaId">PartyRelationshipDataAreaId</a>

First included in: HRM/HcmCoveredDependentRelationshipEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyRelationshipDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParentParty name="ParentParty">ParentParty</a>

First included in: HRM/HcmCoveredDependentRelationshipEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentParty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RelationshipTypeId name="RelationshipTypeId">RelationshipTypeId</a>

First included in: HRM/HcmCoveredDependentRelationshipEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RelationshipTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PartyRelationshipValidFrom name="PartyRelationshipValidFrom">PartyRelationshipValidFrom</a>

First included in: HRM/HcmCoveredDependentRelationshipEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyRelationshipValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PartyRelationshipValidTo name="PartyRelationshipValidTo">PartyRelationshipValidTo</a>

First included in: HRM/HcmCoveredDependentRelationshipEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyRelationshipValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChildPartyId name="ChildPartyId">ChildPartyId</a>

First included in: HRM/HcmCoveredDependentRelationshipEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChildPartyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParentPartyId name="ParentPartyId">ParentPartyId</a>

First included in: HRM/HcmCoveredDependentRelationshipEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentPartyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Benefit name="Benefit">Benefit</a>

First included in: HRM/HcmCoveredDependentRelationshipEntity (this entity)  

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

### <a href=#EnrollmentStart name="EnrollmentStart">EnrollmentStart</a>

First included in: HRM/HcmCoveredDependentRelationshipEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnrollmentStart attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnrollmentEnd name="EnrollmentEnd">EnrollmentEnd</a>

First included in: HRM/HcmCoveredDependentRelationshipEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnrollmentEnd attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Worker name="Worker">Worker</a>

First included in: HRM/HcmCoveredDependentRelationshipEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Worker attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BenefitId name="BenefitId">BenefitId</a>

First included in: HRM/HcmCoveredDependentRelationshipEntity (this entity)  

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

### <a href=#PersonnelNumber name="PersonnelNumber">PersonnelNumber</a>

First included in: HRM/HcmCoveredDependentRelationshipEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkerEnrolledBenefitRelationshipId name="Relationship_WorkerEnrolledBenefitRelationshipId">Relationship_WorkerEnrolledBenefitRelationshipId</a>

First included in: HRM/HcmCoveredDependentRelationshipEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkerEnrolledBenefitRelationshipId attribute are listed below.</summary>

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
