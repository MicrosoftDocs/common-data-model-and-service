---
title: JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity in ProductionControl - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Planned time and attendance absence registrations in ProductionControl(JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Planned time and attendance absence registrations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IsTimeAndAttendanceActivityRegistration](#IsTimeAndAttendanceActivityRegistration)||<a href="JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity.md" target="_blank">ProductionControl/JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity</a>|
|[IsPlannedAbsenceInterruptionAllowed](#IsPlannedAbsenceInterruptionAllowed)||<a href="JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity.md" target="_blank">ProductionControl/JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity</a>|
|[IsPlannedAbsenceInterrupted](#IsPlannedAbsenceInterrupted)||<a href="JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity.md" target="_blank">ProductionControl/JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity</a>|
|[StartDateTime](#StartDateTime)||<a href="JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity.md" target="_blank">ProductionControl/JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity</a>|
|[TimeAndAttendanceJobId](#TimeAndAttendanceJobId)||<a href="JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity.md" target="_blank">ProductionControl/JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity</a>|
|[CalculatedTimeSeconds](#CalculatedTimeSeconds)||<a href="JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity.md" target="_blank">ProductionControl/JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity</a>|
|[EndDateTime](#EndDateTime)||<a href="JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity.md" target="_blank">ProductionControl/JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity</a>|
|[WorkerPersonnelNumber](#WorkerPersonnelNumber)||<a href="JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity.md" target="_blank">ProductionControl/JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity</a>|
|[PlannedAbsenceRegistrationEntryNumber](#PlannedAbsenceRegistrationEntryNumber)||<a href="JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity.md" target="_blank">ProductionControl/JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity</a>|
|[Relationship_WorkerRelationshipId](#Relationship_WorkerRelationshipId)||<a href="JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity.md" target="_blank">ProductionControl/JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity</a>|
|[BackingTable_JmgAbsenceCalendarRelationshipId](#BackingTable_JmgAbsenceCalendarRelationshipId)||<a href="JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity.md" target="_blank">ProductionControl/JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity.md" target="_blank">ProductionControl/JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity</a>|

### <a href=#IsTimeAndAttendanceActivityRegistration name="IsTimeAndAttendanceActivityRegistration">IsTimeAndAttendanceActivityRegistration</a>

First included in: ProductionControl/JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is time and attendance activity registered</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTimeAndAttendanceActivityRegistration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is time and attendance activity registered</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPlannedAbsenceInterruptionAllowed name="IsPlannedAbsenceInterruptionAllowed">IsPlannedAbsenceInterruptionAllowed</a>

First included in: ProductionControl/JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPlannedAbsenceInterruptionAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPlannedAbsenceInterrupted name="IsPlannedAbsenceInterrupted">IsPlannedAbsenceInterrupted</a>

First included in: ProductionControl/JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPlannedAbsenceInterrupted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartDateTime name="StartDateTime">StartDateTime</a>

First included in: ProductionControl/JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity (this entity)  

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

### <a href=#TimeAndAttendanceJobId name="TimeAndAttendanceJobId">TimeAndAttendanceJobId</a>

First included in: ProductionControl/JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity (this entity)  

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

### <a href=#CalculatedTimeSeconds name="CalculatedTimeSeconds">CalculatedTimeSeconds</a>

First included in: ProductionControl/JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Calculated time in seconds</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculatedTimeSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Calculated time in seconds</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndDateTime name="EndDateTime">EndDateTime</a>

First included in: ProductionControl/JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerPersonnelNumber name="WorkerPersonnelNumber">WorkerPersonnelNumber</a>

First included in: ProductionControl/JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity (this entity)  

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

### <a href=#PlannedAbsenceRegistrationEntryNumber name="PlannedAbsenceRegistrationEntryNumber">PlannedAbsenceRegistrationEntryNumber</a>

First included in: ProductionControl/JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Planned absence registration number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedAbsenceRegistrationEntryNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Planned absence registration number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkerRelationshipId name="Relationship_WorkerRelationshipId">Relationship_WorkerRelationshipId</a>

First included in: ProductionControl/JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkerRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_JmgAbsenceCalendarRelationshipId name="BackingTable_JmgAbsenceCalendarRelationshipId">BackingTable_JmgAbsenceCalendarRelationshipId</a>

First included in: ProductionControl/JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_JmgAbsenceCalendarRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/Main/JmgAbsenceCalendar.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Main/JmgAbsenceCalendar.cdm.json/JmgAbsenceCalendar</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/Main/JmgAbsenceCalendar.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/JmgPlannedTimeAndAttendanceAbsenceRegistrationEntity (this entity)  

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
