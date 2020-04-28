---
title: ProjJournalTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Project journal table

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/WorksheetHeader/ProjJournalTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ProjJournalTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project journal table</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[BlockUserGroupId](#BlockUserGroupId)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[BlockUserId](#BlockUserId)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[CategoryId](#CategoryId)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[DeletePostedLines](#DeletePostedLines)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[Description](#Description)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[DetailSummary](#DetailSummary)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[JournalId](#JournalId)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[JournalIdOriginal](#JournalIdOriginal)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[JournalNameId](#JournalNameId)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[JournalType](#JournalType)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[LinePropertyId](#LinePropertyId)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[NumOfLines](#NumOfLines)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[Posted](#Posted)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[PostedDateTime](#PostedDateTime)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[PostedUserId](#PostedUserId)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[PostPayroll](#PostPayroll)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[PostPL](#PostPL)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[PostWIP](#PostWIP)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[ProjId](#ProjId)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[ProjQty](#ProjQty)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[ProjTransDate](#ProjTransDate)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[PSAPeriodEnd](#PSAPeriodEnd)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[PSAPeriodStart](#PSAPeriodStart)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[Resource](#Resource)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[SalesPrice](#SalesPrice)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[SessionId](#SessionId)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[SessionLoginDateTime](#SessionLoginDateTime)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[Status](#Status)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[StatusNameId](#StatusNameId)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[SystemBlocked](#SystemBlocked)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[TimesheetNbr](#TimesheetNbr)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[Txt](#Txt)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[VoucherChange](#VoucherChange)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[VoucherDateChange](#VoucherDateChange)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[VoucherDraw](#VoucherDraw)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[VoucherNumberSequenceTable](#VoucherNumberSequenceTable)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[Worker](#Worker)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[DataAreaId](#DataAreaId)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[Relationship_NumberSequenceTableRelationshipId](#Relationship_NumberSequenceTableRelationshipId)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[Relationship_ProjCategoryRelationshipId](#Relationship_ProjCategoryRelationshipId)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[Relationship_ProjJournalNameRelationshipId](#Relationship_ProjJournalNameRelationshipId)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[Relationship_ProjJournalStatusTableRelationshipId](#Relationship_ProjJournalStatusTableRelationshipId)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[Relationship_ProjLinePropertyRelationshipId](#Relationship_ProjLinePropertyRelationshipId)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[Relationship_ProjTableRelationshipId](#Relationship_ProjTableRelationshipId)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[Relationship_UserGroupInfoRelationshipId](#Relationship_UserGroupInfoRelationshipId)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[Relationship_ResourceTableRelationshipId](#Relationship_ResourceTableRelationshipId)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="ProjJournalTable.md" target="_blank">WorksheetHeader/ProjJournalTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ProjJournalTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BlockUserGroupId name="BlockUserGroupId">BlockUserGroupId</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BlockUserGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BlockUserId name="BlockUserId">BlockUserId</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BlockUserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryId name="CategoryId">CategoryId</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeletePostedLines name="DeletePostedLines">DeletePostedLines</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeletePostedLines attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DetailSummary name="DetailSummary">DetailSummary</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DetailSummary attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#JournalId name="JournalId">JournalId</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalIdOriginal name="JournalIdOriginal">JournalIdOriginal</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalIdOriginal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalNameId name="JournalNameId">JournalNameId</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalType name="JournalType">JournalType</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#LinePropertyId name="LinePropertyId">LinePropertyId</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LinePropertyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumOfLines name="NumOfLines">NumOfLines</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumOfLines attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#Posted name="Posted">Posted</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Posted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#PostedDateTime name="PostedDateTime">PostedDateTime</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostedDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#PostedUserId name="PostedUserId">PostedUserId</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostedUserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostPayroll name="PostPayroll">PostPayroll</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostPayroll attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PostPL name="PostPL">PostPL</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostPL attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PostWIP name="PostWIP">PostWIP</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostWIP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProjId name="ProjId">ProjId</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjQty name="ProjQty">ProjQty</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ProjTransDate name="ProjTransDate">ProjTransDate</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjTransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#PSAPeriodEnd name="PSAPeriodEnd">PSAPeriodEnd</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Period Ending</td></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSAPeriodEnd attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Period Ending</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#PSAPeriodStart name="PSAPeriodStart">PSAPeriodStart</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Period Start</td></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSAPeriodStart attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Period Start</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#Resource name="Resource">Resource</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Resource attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SalesPrice name="SalesPrice">SalesPrice</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SessionId name="SessionId">SessionId</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SessionId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#SessionLoginDateTime name="SessionLoginDateTime">SessionLoginDateTime</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SessionLoginDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatusNameId name="StatusNameId">StatusNameId</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatusNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SystemBlocked name="SystemBlocked">SystemBlocked</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SystemBlocked attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TimesheetNbr name="TimesheetNbr">TimesheetNbr</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimesheetNbr attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Txt name="Txt">Txt</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Txt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoucherChange name="VoucherChange">VoucherChange</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherChange attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VoucherDateChange name="VoucherDateChange">VoucherDateChange</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherDateChange attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VoucherDraw name="VoucherDraw">VoucherDraw</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherDraw attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VoucherNumberSequenceTable name="VoucherNumberSequenceTable">VoucherNumberSequenceTable</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherNumberSequenceTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Worker name="Worker">Worker</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Worker attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_NumberSequenceTableRelationshipId name="Relationship_NumberSequenceTableRelationshipId">Relationship_NumberSequenceTableRelationshipId</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_NumberSequenceTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Framework/NumberSequenceTable.cdm.json/NumberSequenceTable</a></td><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjCategoryRelationshipId name="Relationship_ProjCategoryRelationshipId">Relationship_ProjCategoryRelationshipId</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjCategoryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ProjCategory.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjCategory.cdm.json/ProjCategory</a></td><td><a href="../Group/ProjCategory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjJournalNameRelationshipId name="Relationship_ProjJournalNameRelationshipId">Relationship_ProjJournalNameRelationshipId</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjJournalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ProjJournalName.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjJournalName.cdm.json/ProjJournalName</a></td><td><a href="../Group/ProjJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjJournalStatusTableRelationshipId name="Relationship_ProjJournalStatusTableRelationshipId">Relationship_ProjJournalStatusTableRelationshipId</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjJournalStatusTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ProjJournalStatusTable.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjJournalStatusTable.cdm.json/ProjJournalStatusTable</a></td><td><a href="../Group/ProjJournalStatusTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjLinePropertyRelationshipId name="Relationship_ProjLinePropertyRelationshipId">Relationship_ProjLinePropertyRelationshipId</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjLinePropertyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ProjLineProperty.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjLineProperty.cdm.json/ProjLineProperty</a></td><td><a href="../Group/ProjLineProperty.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjTableRelationshipId name="Relationship_ProjTableRelationshipId">Relationship_ProjTableRelationshipId</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/ProjTable.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Main/ProjTable.cdm.json/ProjTable</a></td><td><a href="../Main/ProjTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_UserGroupInfoRelationshipId name="Relationship_UserGroupInfoRelationshipId">Relationship_UserGroupInfoRelationshipId</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UserGroupInfoRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Main/UserGroupInfo.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Main/UserGroupInfo.cdm.json/UserGroupInfo</a></td><td><a href="../../../System/SystemAdministration/Main/UserGroupInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ResourceTableRelationshipId name="Relationship_ResourceTableRelationshipId">Relationship_ResourceTableRelationshipId</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ResourceTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/ResResourceIdentifier.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Miscellaneous/ResResourceIdentifier.cdm.json/ResResourceIdentifier</a></td><td><a href="../Miscellaneous/ResResourceIdentifier.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetHeader/ProjJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
