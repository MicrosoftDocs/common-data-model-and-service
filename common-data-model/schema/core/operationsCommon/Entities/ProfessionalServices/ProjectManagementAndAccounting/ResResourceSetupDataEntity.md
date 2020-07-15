---
title: ResResourceSetupDataEntity in ProjectManagementAndAccounting - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# Project scheduling resource details in ProjectManagementAndAccounting(ResResourceSetupDataEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/ProfessionalServices/ProjectManagementAndAccounting/ResResourceSetupDataEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project scheduling resource details</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DefaultTimeCategory](#DefaultTimeCategory)||<a href="ResResourceSetupDataEntity.md" target="_blank">ProjectManagementAndAccounting/ResResourceSetupDataEntity</a>|
|[LegalEntity](#LegalEntity)||<a href="ResResourceSetupDataEntity.md" target="_blank">ProjectManagementAndAccounting/ResResourceSetupDataEntity</a>|
|[Period](#Period)||<a href="ResResourceSetupDataEntity.md" target="_blank">ProjectManagementAndAccounting/ResResourceSetupDataEntity</a>|
|[Resource](#Resource)||<a href="ResResourceSetupDataEntity.md" target="_blank">ProjectManagementAndAccounting/ResResourceSetupDataEntity</a>|
|[MaxHoursCalendar](#MaxHoursCalendar)||<a href="ResResourceSetupDataEntity.md" target="_blank">ProjectManagementAndAccounting/ResResourceSetupDataEntity</a>|
|[DefaultTimeCategoryId](#DefaultTimeCategoryId)||<a href="ResResourceSetupDataEntity.md" target="_blank">ProjectManagementAndAccounting/ResResourceSetupDataEntity</a>|
|[ResourceLegalEntityDataArea](#ResourceLegalEntityDataArea)||<a href="ResResourceSetupDataEntity.md" target="_blank">ProjectManagementAndAccounting/ResResourceSetupDataEntity</a>|
|[PeriodId](#PeriodId)||<a href="ResResourceSetupDataEntity.md" target="_blank">ProjectManagementAndAccounting/ResResourceSetupDataEntity</a>|
|[ResourceId](#ResourceId)||<a href="ResResourceSetupDataEntity.md" target="_blank">ProjectManagementAndAccounting/ResResourceSetupDataEntity</a>|
|[ResourceName](#ResourceName)||<a href="ResResourceSetupDataEntity.md" target="_blank">ProjectManagementAndAccounting/ResResourceSetupDataEntity</a>|
|[UseResourceRate](#UseResourceRate)||<a href="ResResourceSetupDataEntity.md" target="_blank">ProjectManagementAndAccounting/ResResourceSetupDataEntity</a>|
|[ValidateProjectResource](#ValidateProjectResource)||<a href="ResResourceSetupDataEntity.md" target="_blank">ProjectManagementAndAccounting/ResResourceSetupDataEntity</a>|
|[ValidateResourceCategory](#ValidateResourceCategory)||<a href="ResResourceSetupDataEntity.md" target="_blank">ProjectManagementAndAccounting/ResResourceSetupDataEntity</a>|
|[MaxHoursCalendarId](#MaxHoursCalendarId)||<a href="ResResourceSetupDataEntity.md" target="_blank">ProjectManagementAndAccounting/ResResourceSetupDataEntity</a>|
|[MaxWorkingHours](#MaxWorkingHours)||<a href="ResResourceSetupDataEntity.md" target="_blank">ProjectManagementAndAccounting/ResResourceSetupDataEntity</a>|
|[RequireStartStopTime](#RequireStartStopTime)||<a href="ResResourceSetupDataEntity.md" target="_blank">ProjectManagementAndAccounting/ResResourceSetupDataEntity</a>|
|[BackingTable_ResourceSetupRelationshipId](#BackingTable_ResourceSetupRelationshipId)||<a href="ResResourceSetupDataEntity.md" target="_blank">ProjectManagementAndAccounting/ResResourceSetupDataEntity</a>|

### <a href=#DefaultTimeCategory name="DefaultTimeCategory">DefaultTimeCategory</a>

First included in: ProjectManagementAndAccounting/ResResourceSetupDataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultTimeCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntity name="LegalEntity">LegalEntity</a>

First included in: ProjectManagementAndAccounting/ResResourceSetupDataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Period name="Period">Period</a>

First included in: ProjectManagementAndAccounting/ResResourceSetupDataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Period attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Resource name="Resource">Resource</a>

First included in: ProjectManagementAndAccounting/ResResourceSetupDataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Resource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxHoursCalendar name="MaxHoursCalendar">MaxHoursCalendar</a>

First included in: ProjectManagementAndAccounting/ResResourceSetupDataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxHoursCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultTimeCategoryId name="DefaultTimeCategoryId">DefaultTimeCategoryId</a>

First included in: ProjectManagementAndAccounting/ResResourceSetupDataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultTimeCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceLegalEntityDataArea name="ResourceLegalEntityDataArea">ResourceLegalEntityDataArea</a>

First included in: ProjectManagementAndAccounting/ResResourceSetupDataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceLegalEntityDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodId name="PeriodId">PeriodId</a>

First included in: ProjectManagementAndAccounting/ResResourceSetupDataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceId name="ResourceId">ResourceId</a>

First included in: ProjectManagementAndAccounting/ResResourceSetupDataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceName name="ResourceName">ResourceName</a>

First included in: ProjectManagementAndAccounting/ResResourceSetupDataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseResourceRate name="UseResourceRate">UseResourceRate</a>

First included in: ProjectManagementAndAccounting/ResResourceSetupDataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseResourceRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidateProjectResource name="ValidateProjectResource">ValidateProjectResource</a>

First included in: ProjectManagementAndAccounting/ResResourceSetupDataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidateProjectResource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidateResourceCategory name="ValidateResourceCategory">ValidateResourceCategory</a>

First included in: ProjectManagementAndAccounting/ResResourceSetupDataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidateResourceCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxHoursCalendarId name="MaxHoursCalendarId">MaxHoursCalendarId</a>

First included in: ProjectManagementAndAccounting/ResResourceSetupDataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxHoursCalendarId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxWorkingHours name="MaxWorkingHours">MaxWorkingHours</a>

First included in: ProjectManagementAndAccounting/ResResourceSetupDataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxWorkingHours attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequireStartStopTime name="RequireStartStopTime">RequireStartStopTime</a>

First included in: ProjectManagementAndAccounting/ResResourceSetupDataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequireStartStopTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_ResourceSetupRelationshipId name="BackingTable_ResourceSetupRelationshipId">BackingTable_ResourceSetupRelationshipId</a>

First included in: ProjectManagementAndAccounting/ResResourceSetupDataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ResourceSetupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Main/ResourceSetup.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Main/ResourceSetup.cdm.json/ResourceSetup</a></td><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Main/ResourceSetup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
