---
title: HcmBICourseEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# HcmBICourseEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/HRM/HcmBICourseEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[Course](#Course)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[Company](#Company)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[CourseDescription](#CourseDescription)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[CourseType](#CourseType)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[CourseLocation](#CourseLocation)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[CourseLocationDescription](#CourseLocationDescription)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[CourseRoom](#CourseRoom)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[CourseRoomDescription](#CourseRoomDescription)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[CourseRoomMaxAttendees](#CourseRoomMaxAttendees)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[CourseRoomMaxOccupancy](#CourseRoomMaxOccupancy)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[EmployeeSelfServiceRegistrationEnabled](#EmployeeSelfServiceRegistrationEnabled)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[RegistrationDeadline](#RegistrationDeadline)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[MaxAttendees](#MaxAttendees)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[MinAttendees](#MinAttendees)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[Note](#Note)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[StartDateTime](#StartDateTime)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[EndDateTime](#EndDateTime)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[Setup](#Setup)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[Status](#Status)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[TrainingHours](#TrainingHours)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[CourseInstructor](#CourseInstructor)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[CourseInstructorName](#CourseInstructorName)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[Configuration](#Configuration)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[QuestionaireSchedule](#QuestionaireSchedule)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[GeographicLocation](#GeographicLocation)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[GeographicLocationValidFrom](#GeographicLocationValidFrom)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[GeographicLocationValidTo](#GeographicLocationValidTo)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="HcmBICourseEntity.md" target="_blank">HRM/HcmBICourseEntity</a>|

### <a href=#Course name="Course">Course</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Course attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Company name="Company">Company</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Company attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CourseDescription name="CourseDescription">CourseDescription</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CourseDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CourseType name="CourseType">CourseType</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CourseType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CourseLocation name="CourseLocation">CourseLocation</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CourseLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CourseLocationDescription name="CourseLocationDescription">CourseLocationDescription</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CourseLocationDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CourseRoom name="CourseRoom">CourseRoom</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CourseRoom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CourseRoomDescription name="CourseRoomDescription">CourseRoomDescription</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CourseRoomDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CourseRoomMaxAttendees name="CourseRoomMaxAttendees">CourseRoomMaxAttendees</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CourseRoomMaxAttendees attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CourseRoomMaxOccupancy name="CourseRoomMaxOccupancy">CourseRoomMaxOccupancy</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CourseRoomMaxOccupancy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmployeeSelfServiceRegistrationEnabled name="EmployeeSelfServiceRegistrationEnabled">EmployeeSelfServiceRegistrationEnabled</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmployeeSelfServiceRegistrationEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RegistrationDeadline name="RegistrationDeadline">RegistrationDeadline</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegistrationDeadline attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxAttendees name="MaxAttendees">MaxAttendees</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxAttendees attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinAttendees name="MinAttendees">MinAttendees</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinAttendees attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Note name="Note">Note</a>

First included in: HRM/HcmBICourseEntity (this entity)  

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

### <a href=#StartDateTime name="StartDateTime">StartDateTime</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndDateTime name="EndDateTime">EndDateTime</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Setup name="Setup">Setup</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Setup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TrainingHours name="TrainingHours">TrainingHours</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrainingHours attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CourseInstructor name="CourseInstructor">CourseInstructor</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CourseInstructor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CourseInstructorName name="CourseInstructorName">CourseInstructorName</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CourseInstructorName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Configuration name="Configuration">Configuration</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Configuration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuestionaireSchedule name="QuestionaireSchedule">QuestionaireSchedule</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuestionaireSchedule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionDisplayValue name="DefaultDimensionDisplayValue">DefaultDimensionDisplayValue</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeographicLocation name="GeographicLocation">GeographicLocation</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeographicLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeographicLocationValidFrom name="GeographicLocationValidFrom">GeographicLocationValidFrom</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeographicLocationValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeographicLocationValidTo name="GeographicLocationValidTo">GeographicLocationValidTo</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeographicLocationValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: HRM/HcmBICourseEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
