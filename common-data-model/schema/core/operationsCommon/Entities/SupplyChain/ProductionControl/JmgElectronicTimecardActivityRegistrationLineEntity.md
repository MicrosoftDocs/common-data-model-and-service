---
title: JmgElectronicTimecardActivityRegistrationLineEntity in ProductionControl - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Electronic timecard lines in ProductionControl(JmgElectronicTimecardActivityRegistrationLineEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Electronic timecard lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IsWorkInProgress](#IsWorkInProgress)||<a href="JmgElectronicTimecardActivityRegistrationLineEntity.md" target="_blank">ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity</a>|
|[IsJobFinished](#IsJobFinished)||<a href="JmgElectronicTimecardActivityRegistrationLineEntity.md" target="_blank">ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity</a>|
|[TimeAndAttendanceJobId](#TimeAndAttendanceJobId)||<a href="JmgElectronicTimecardActivityRegistrationLineEntity.md" target="_blank">ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity</a>|
|[AbsenceCodeTimeAndAttendanceJobId](#AbsenceCodeTimeAndAttendanceJobId)||<a href="JmgElectronicTimecardActivityRegistrationLineEntity.md" target="_blank">ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity</a>|
|[JournalRegistrationType](#JournalRegistrationType)||<a href="JmgElectronicTimecardActivityRegistrationLineEntity.md" target="_blank">ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity</a>|
|[LineNumber](#LineNumber)||<a href="JmgElectronicTimecardActivityRegistrationLineEntity.md" target="_blank">ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity</a>|
|[OnCallTimeAndAttendanceJobId](#OnCallTimeAndAttendanceJobId)||<a href="JmgElectronicTimecardActivityRegistrationLineEntity.md" target="_blank">ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity</a>|
|[TimeProfileDate](#TimeProfileDate)||<a href="JmgElectronicTimecardActivityRegistrationLineEntity.md" target="_blank">ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity</a>|
|[ProjectCategoryId](#ProjectCategoryId)||<a href="JmgElectronicTimecardActivityRegistrationLineEntity.md" target="_blank">ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity</a>|
|[CalculatedTimeSeconds](#CalculatedTimeSeconds)||<a href="JmgElectronicTimecardActivityRegistrationLineEntity.md" target="_blank">ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity</a>|
|[StartDateTime](#StartDateTime)||<a href="JmgElectronicTimecardActivityRegistrationLineEntity.md" target="_blank">ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity</a>|
|[StopDateTime](#StopDateTime)||<a href="JmgElectronicTimecardActivityRegistrationLineEntity.md" target="_blank">ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity</a>|
|[OperationsResourceId](#OperationsResourceId)||<a href="JmgElectronicTimecardActivityRegistrationLineEntity.md" target="_blank">ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity</a>|
|[OperationsResourcePilotId](#OperationsResourcePilotId)||<a href="JmgElectronicTimecardActivityRegistrationLineEntity.md" target="_blank">ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity</a>|
|[ElectronicTimecardActivityRegistrationEntryNumber](#ElectronicTimecardActivityRegistrationEntryNumber)||<a href="JmgElectronicTimecardActivityRegistrationLineEntity.md" target="_blank">ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity</a>|
|[WorkerPersonnelNumber](#WorkerPersonnelNumber)||<a href="JmgElectronicTimecardActivityRegistrationLineEntity.md" target="_blank">ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity</a>|
|[PilotPersonnelNumber](#PilotPersonnelNumber)||<a href="JmgElectronicTimecardActivityRegistrationLineEntity.md" target="_blank">ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity</a>|
|[ProductionOrderNumber](#ProductionOrderNumber)||<a href="JmgElectronicTimecardActivityRegistrationLineEntity.md" target="_blank">ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity</a>|
|[ProjectId](#ProjectId)||<a href="JmgElectronicTimecardActivityRegistrationLineEntity.md" target="_blank">ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity</a>|
|[AbsenceCodeId](#AbsenceCodeId)||<a href="JmgElectronicTimecardActivityRegistrationLineEntity.md" target="_blank">ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity</a>|
|[IndirectActivityCategoryId](#IndirectActivityCategoryId)||<a href="JmgElectronicTimecardActivityRegistrationLineEntity.md" target="_blank">ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity</a>|
|[Relationship_ElectronicTimecardActivityRegistrationHeaderRelationshipId](#Relationship_ElectronicTimecardActivityRegistrationHeaderRelationshipId)||<a href="JmgElectronicTimecardActivityRegistrationLineEntity.md" target="_blank">ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity</a>|
|[BackingTable_JmgTimecardTransRelationshipId](#BackingTable_JmgTimecardTransRelationshipId)||<a href="JmgElectronicTimecardActivityRegistrationLineEntity.md" target="_blank">ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="JmgElectronicTimecardActivityRegistrationLineEntity.md" target="_blank">ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity</a>|

### <a href=#IsWorkInProgress name="IsWorkInProgress">IsWorkInProgress</a>

First included in: ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWorkInProgress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsJobFinished name="IsJobFinished">IsJobFinished</a>

First included in: ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsJobFinished attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeAndAttendanceJobId name="TimeAndAttendanceJobId">TimeAndAttendanceJobId</a>

First included in: ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeAndAttendanceJobId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AbsenceCodeTimeAndAttendanceJobId name="AbsenceCodeTimeAndAttendanceJobId">AbsenceCodeTimeAndAttendanceJobId</a>

First included in: ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AbsenceCodeTimeAndAttendanceJobId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalRegistrationType name="JournalRegistrationType">JournalRegistrationType</a>

First included in: ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalRegistrationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnCallTimeAndAttendanceJobId name="OnCallTimeAndAttendanceJobId">OnCallTimeAndAttendanceJobId</a>

First included in: ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnCallTimeAndAttendanceJobId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeProfileDate name="TimeProfileDate">TimeProfileDate</a>

First included in: ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeProfileDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectCategoryId name="ProjectCategoryId">ProjectCategoryId</a>

First included in: ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalculatedTimeSeconds name="CalculatedTimeSeconds">CalculatedTimeSeconds</a>

First included in: ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculatedTimeSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartDateTime name="StartDateTime">StartDateTime</a>

First included in: ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StopDateTime name="StopDateTime">StopDateTime</a>

First included in: ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StopDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationsResourceId name="OperationsResourceId">OperationsResourceId</a>

First included in: ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationsResourceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationsResourcePilotId name="OperationsResourcePilotId">OperationsResourcePilotId</a>

First included in: ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationsResourcePilotId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicTimecardActivityRegistrationEntryNumber name="ElectronicTimecardActivityRegistrationEntryNumber">ElectronicTimecardActivityRegistrationEntryNumber</a>

First included in: ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Electronic timecard activity registration entry number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicTimecardActivityRegistrationEntryNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Electronic timecard activity registration entry number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerPersonnelNumber name="WorkerPersonnelNumber">WorkerPersonnelNumber</a>

First included in: ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Worker personnel number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Worker personnel number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PilotPersonnelNumber name="PilotPersonnelNumber">PilotPersonnelNumber</a>

First included in: ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pilot personnel number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PilotPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Pilot personnel number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionOrderNumber name="ProductionOrderNumber">ProductionOrderNumber</a>

First included in: ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Production order number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Production order number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectId name="ProjectId">ProjectId</a>

First included in: ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project id</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AbsenceCodeId name="AbsenceCodeId">AbsenceCodeId</a>

First included in: ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Absence code id</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AbsenceCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Absence code id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IndirectActivityCategoryId name="IndirectActivityCategoryId">IndirectActivityCategoryId</a>

First included in: ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Indirect activity category Id</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IndirectActivityCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indirect activity category Id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ElectronicTimecardActivityRegistrationHeaderRelationshipId name="Relationship_ElectronicTimecardActivityRegistrationHeaderRelationshipId">Relationship_ElectronicTimecardActivityRegistrationHeaderRelationshipId</a>

First included in: ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ElectronicTimecardActivityRegistrationHeaderRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_JmgTimecardTransRelationshipId name="BackingTable_JmgTimecardTransRelationshipId">BackingTable_JmgTimecardTransRelationshipId</a>

First included in: ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_JmgTimecardTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/WorksheetLine/JmgTimecardTrans.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/WorksheetLine/JmgTimecardTrans.cdm.json/JmgTimecardTrans</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/WorksheetLine/JmgTimecardTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/JmgElectronicTimecardActivityRegistrationLineEntity (this entity)  

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
