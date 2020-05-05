---
title: DataManagementExecutionJobDetailEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# DMF data project execution

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/System/SystemAdministration/DataManagementExecutionJobDetailEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>DMF data project execution</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DefinitionGroupId](#DefinitionGroupId)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[EntityName](#EntityName)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[JobId](#JobId)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[StagingEndDateTime](#StagingEndDateTime)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[ExcelSheetName](#ExcelSheetName)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[ExecuteTargetStep](#ExecuteTargetStep)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[FirstRowIsHeader](#FirstRowIsHeader)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[FilePath](#FilePath)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[IgnoreError](#IgnoreError)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[StagingRecordsToBeProcessedCount](#StagingRecordsToBeProcessedCount)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[ParallelTaskCount](#ParallelTaskCount)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[StagingRecordsCreatedCount](#StagingRecordsCreatedCount)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[TargetRecordsCreatedCount](#TargetRecordsCreatedCount)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[TargetRecordsUpdatedCount](#TargetRecordsUpdatedCount)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[CreateErrorFile](#CreateErrorFile)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[RunBusinessLogic](#RunBusinessLogic)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[RunBusinessValidation](#RunBusinessValidation)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[SequenceNumber](#SequenceNumber)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[NumberOfRowsToSkip](#NumberOfRowsToSkip)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[SourceFormat](#SourceFormat)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[StagingStatus](#StagingStatus)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[StagingStartDateTime](#StagingStartDateTime)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[TargetStatus](#TargetStatus)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[TargetEndDateTime](#TargetEndDateTime)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[TargetStartDateTime](#TargetStartDateTime)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[ExecutionUnit](#ExecutionUnit)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[LevelInExecutionUnit](#LevelInExecutionUnit)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[SequenceInLevel](#SequenceInLevel)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[FailExecutionUnitOnError](#FailExecutionUnitOnError)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[FailLevelOnError](#FailLevelOnError)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|
|[Relationship_ExecutionJobDetailsRelationshipId](#Relationship_ExecutionJobDetailsRelationshipId)||<a href="DataManagementExecutionJobDetailEntity.md" target="_blank">SystemAdministration/DataManagementExecutionJobDetailEntity</a>|

### <a href=#DefinitionGroupId name="DefinitionGroupId">DefinitionGroupId</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefinitionGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EntityName name="EntityName">EntityName</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntityName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobId name="JobId">JobId</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StagingEndDateTime name="StagingEndDateTime">StagingEndDateTime</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StagingEndDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExcelSheetName name="ExcelSheetName">ExcelSheetName</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExcelSheetName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExecuteTargetStep name="ExecuteTargetStep">ExecuteTargetStep</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExecuteTargetStep attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FirstRowIsHeader name="FirstRowIsHeader">FirstRowIsHeader</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FirstRowIsHeader attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FilePath name="FilePath">FilePath</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FilePath attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IgnoreError name="IgnoreError">IgnoreError</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IgnoreError attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StagingRecordsToBeProcessedCount name="StagingRecordsToBeProcessedCount">StagingRecordsToBeProcessedCount</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StagingRecordsToBeProcessedCount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParallelTaskCount name="ParallelTaskCount">ParallelTaskCount</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParallelTaskCount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StagingRecordsCreatedCount name="StagingRecordsCreatedCount">StagingRecordsCreatedCount</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StagingRecordsCreatedCount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TargetRecordsCreatedCount name="TargetRecordsCreatedCount">TargetRecordsCreatedCount</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TargetRecordsCreatedCount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TargetRecordsUpdatedCount name="TargetRecordsUpdatedCount">TargetRecordsUpdatedCount</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TargetRecordsUpdatedCount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreateErrorFile name="CreateErrorFile">CreateErrorFile</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreateErrorFile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RunBusinessLogic name="RunBusinessLogic">RunBusinessLogic</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RunBusinessLogic attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RunBusinessValidation name="RunBusinessValidation">RunBusinessValidation</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RunBusinessValidation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SequenceNumber name="SequenceNumber">SequenceNumber</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberOfRowsToSkip name="NumberOfRowsToSkip">NumberOfRowsToSkip</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberOfRowsToSkip attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceFormat name="SourceFormat">SourceFormat</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceFormat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StagingStatus name="StagingStatus">StagingStatus</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StagingStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StagingStartDateTime name="StagingStartDateTime">StagingStartDateTime</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StagingStartDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TargetStatus name="TargetStatus">TargetStatus</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TargetStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TargetEndDateTime name="TargetEndDateTime">TargetEndDateTime</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TargetEndDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TargetStartDateTime name="TargetStartDateTime">TargetStartDateTime</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TargetStartDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExecutionUnit name="ExecutionUnit">ExecutionUnit</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExecutionUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LevelInExecutionUnit name="LevelInExecutionUnit">LevelInExecutionUnit</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LevelInExecutionUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SequenceInLevel name="SequenceInLevel">SequenceInLevel</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SequenceInLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FailExecutionUnitOnError name="FailExecutionUnitOnError">FailExecutionUnitOnError</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FailExecutionUnitOnError attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FailLevelOnError name="FailLevelOnError">FailLevelOnError</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FailLevelOnError attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ExecutionJobDetailsRelationshipId name="Relationship_ExecutionJobDetailsRelationshipId">Relationship_ExecutionJobDetailsRelationshipId</a>

First included in: SystemAdministration/DataManagementExecutionJobDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ExecutionJobDetailsRelationshipId attribute are listed below.</summary>

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
