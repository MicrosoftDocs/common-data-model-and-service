---
title: DataManagementDefinitionGroupDetailEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/30/2020
ms.author: nebanfic
---

# Entities for a processing group

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/System/SystemAdministration/DataManagementDefinitionGroupDetailEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Entities for a processing group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DefinitionGroupId](#DefinitionGroupId)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[EntityName](#EntityName)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[ExcelSheetName](#ExcelSheetName)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[RunBusinessLogic](#RunBusinessLogic)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[RunBusinessValidation](#RunBusinessValidation)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[SampleFilePath](#SampleFilePath)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[InputFilePath](#InputFilePath)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[SourceFormat](#SourceFormat)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[ValidationStatus](#ValidationStatus)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[ExecutionUnit](#ExecutionUnit)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[LevelInExecutionUnit](#LevelInExecutionUnit)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[SequenceInLevel](#SequenceInLevel)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[FailLevelOnError](#FailLevelOnError)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[FailExecutionUnitOnError](#FailExecutionUnitOnError)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[Disable](#Disable)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[QueryData](#QueryData)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[SysModule](#SysModule)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[Tags](#Tags)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[EntityCategory](#EntityCategory)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[ParentEntityName](#ParentEntityName)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[AutoGenerateMapping](#AutoGenerateMapping)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[QueryForODBC](#QueryForODBC)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[RunValidateField](#RunValidateField)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[EntityXMLName](#EntityXMLName)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[IsTransformed](#IsTransformed)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[SampleFilePathOriginal](#SampleFilePathOriginal)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[SkipStaging](#SkipStaging)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[PackageFilePath](#PackageFilePath)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[DefaultRefreshType](#DefaultRefreshType)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|
|[Relationship_DefinitionGroupDetailsRelationshipId](#Relationship_DefinitionGroupDetailsRelationshipId)||<a href="DataManagementDefinitionGroupDetailEntity.md" target="_blank">SystemAdministration/DataManagementDefinitionGroupDetailEntity</a>|

### <a href=#DefinitionGroupId name="DefinitionGroupId">DefinitionGroupId</a>

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

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

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

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

### <a href=#ExcelSheetName name="ExcelSheetName">ExcelSheetName</a>

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

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

### <a href=#RunBusinessLogic name="RunBusinessLogic">RunBusinessLogic</a>

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

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

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

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

### <a href=#SampleFilePath name="SampleFilePath">SampleFilePath</a>

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SampleFilePath attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InputFilePath name="InputFilePath">InputFilePath</a>

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InputFilePath attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceFormat name="SourceFormat">SourceFormat</a>

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

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

### <a href=#ValidationStatus name="ValidationStatus">ValidationStatus</a>

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidationStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExecutionUnit name="ExecutionUnit">ExecutionUnit</a>

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

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

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

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

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

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

### <a href=#FailLevelOnError name="FailLevelOnError">FailLevelOnError</a>

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

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

### <a href=#FailExecutionUnitOnError name="FailExecutionUnitOnError">FailExecutionUnitOnError</a>

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

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

### <a href=#Disable name="Disable">Disable</a>

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Disable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QueryData name="QueryData">QueryData</a>

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QueryData attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SysModule name="SysModule">SysModule</a>

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SysModule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tags name="Tags">Tags</a>

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tags attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EntityCategory name="EntityCategory">EntityCategory</a>

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntityCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParentEntityName name="ParentEntityName">ParentEntityName</a>

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentEntityName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AutoGenerateMapping name="AutoGenerateMapping">AutoGenerateMapping</a>

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Generate mapping</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutoGenerateMapping attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Generate mapping</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QueryForODBC name="QueryForODBC">QueryForODBC</a>

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QueryForODBC attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RunValidateField name="RunValidateField">RunValidateField</a>

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RunValidateField attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EntityXMLName name="EntityXMLName">EntityXMLName</a>

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntityXMLName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTransformed name="IsTransformed">IsTransformed</a>

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTransformed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SampleFilePathOriginal name="SampleFilePathOriginal">SampleFilePathOriginal</a>

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SampleFilePathOriginal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SkipStaging name="SkipStaging">SkipStaging</a>

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SkipStaging attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackageFilePath name="PackageFilePath">PackageFilePath</a>

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackageFilePath attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultRefreshType name="DefaultRefreshType">DefaultRefreshType</a>

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultRefreshType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefinitionGroupDetailsRelationshipId name="Relationship_DefinitionGroupDetailsRelationshipId">Relationship_DefinitionGroupDetailsRelationshipId</a>

First included in: SystemAdministration/DataManagementDefinitionGroupDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefinitionGroupDetailsRelationshipId attribute are listed below.</summary>

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
