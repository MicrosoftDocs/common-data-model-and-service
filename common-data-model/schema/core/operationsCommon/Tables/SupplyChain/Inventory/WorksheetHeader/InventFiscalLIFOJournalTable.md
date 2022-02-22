---
title: InventFiscalLIFOJournalTable in WorksheetHeader - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Fiscal LIFO journal table in WorksheetHeader(InventFiscalLIFOJournalTable)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/InventFiscalLIFOJournalTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventFiscalLIFOJournalTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fiscal LIFO journal table</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="InventFiscalLIFOJournalTable.md" target="_blank">WorksheetHeader/InventFiscalLIFOJournalTable</a>|
|[BlockUserGroupId](#BlockUserGroupId)||<a href="InventFiscalLIFOJournalTable.md" target="_blank">WorksheetHeader/InventFiscalLIFOJournalTable</a>|
|[BlockUserId](#BlockUserId)||<a href="InventFiscalLIFOJournalTable.md" target="_blank">WorksheetHeader/InventFiscalLIFOJournalTable</a>|
|[deletePostedLines](#deletePostedLines)||<a href="InventFiscalLIFOJournalTable.md" target="_blank">WorksheetHeader/InventFiscalLIFOJournalTable</a>|
|[Description](#Description)||<a href="InventFiscalLIFOJournalTable.md" target="_blank">WorksheetHeader/InventFiscalLIFOJournalTable</a>|
|[EndDate](#EndDate)||<a href="InventFiscalLIFOJournalTable.md" target="_blank">WorksheetHeader/InventFiscalLIFOJournalTable</a>|
|[FinalReportClosed](#FinalReportClosed)||<a href="InventFiscalLIFOJournalTable.md" target="_blank">WorksheetHeader/InventFiscalLIFOJournalTable</a>|
|[IncludeWIP](#IncludeWIP)||<a href="InventFiscalLIFOJournalTable.md" target="_blank">WorksheetHeader/InventFiscalLIFOJournalTable</a>|
|[JournalId](#JournalId)||<a href="InventFiscalLIFOJournalTable.md" target="_blank">WorksheetHeader/InventFiscalLIFOJournalTable</a>|
|[JournalNameId](#JournalNameId)||<a href="InventFiscalLIFOJournalTable.md" target="_blank">WorksheetHeader/InventFiscalLIFOJournalTable</a>|
|[JournalType](#JournalType)||<a href="InventFiscalLIFOJournalTable.md" target="_blank">WorksheetHeader/InventFiscalLIFOJournalTable</a>|
|[NumOfLines](#NumOfLines)||<a href="InventFiscalLIFOJournalTable.md" target="_blank">WorksheetHeader/InventFiscalLIFOJournalTable</a>|
|[Posted](#Posted)||<a href="InventFiscalLIFOJournalTable.md" target="_blank">WorksheetHeader/InventFiscalLIFOJournalTable</a>|
|[PostedDateTime](#PostedDateTime)||<a href="InventFiscalLIFOJournalTable.md" target="_blank">WorksheetHeader/InventFiscalLIFOJournalTable</a>|
|[PostedUserId](#PostedUserId)||<a href="InventFiscalLIFOJournalTable.md" target="_blank">WorksheetHeader/InventFiscalLIFOJournalTable</a>|
|[SessionId](#SessionId)||<a href="InventFiscalLIFOJournalTable.md" target="_blank">WorksheetHeader/InventFiscalLIFOJournalTable</a>|
|[SessionLoginDateTime](#SessionLoginDateTime)||<a href="InventFiscalLIFOJournalTable.md" target="_blank">WorksheetHeader/InventFiscalLIFOJournalTable</a>|
|[StartDate](#StartDate)||<a href="InventFiscalLIFOJournalTable.md" target="_blank">WorksheetHeader/InventFiscalLIFOJournalTable</a>|
|[SystemBlocked](#SystemBlocked)||<a href="InventFiscalLIFOJournalTable.md" target="_blank">WorksheetHeader/InventFiscalLIFOJournalTable</a>|
|[UseNormalValue](#UseNormalValue)||<a href="InventFiscalLIFOJournalTable.md" target="_blank">WorksheetHeader/InventFiscalLIFOJournalTable</a>|
|[DataAreaId](#DataAreaId)||<a href="InventFiscalLIFOJournalTable.md" target="_blank">WorksheetHeader/InventFiscalLIFOJournalTable</a>|
|[Relationship_InventFiscalLIFOJournalNameRelationshipId](#Relationship_InventFiscalLIFOJournalNameRelationshipId)||<a href="InventFiscalLIFOJournalTable.md" target="_blank">WorksheetHeader/InventFiscalLIFOJournalTable</a>|
|[Relationship_JournalErrorRelationshipId](#Relationship_JournalErrorRelationshipId)||<a href="InventFiscalLIFOJournalTable.md" target="_blank">WorksheetHeader/InventFiscalLIFOJournalTable</a>|
|[Relationship_UserGroupInfoRelationshipId](#Relationship_UserGroupInfoRelationshipId)||<a href="InventFiscalLIFOJournalTable.md" target="_blank">WorksheetHeader/InventFiscalLIFOJournalTable</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="InventFiscalLIFOJournalTable.md" target="_blank">WorksheetHeader/InventFiscalLIFOJournalTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetHeader/InventFiscalLIFOJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventFiscalLIFOJournalTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BlockUserGroupId name="BlockUserGroupId">BlockUserGroupId</a>

First included in: WorksheetHeader/InventFiscalLIFOJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BlockUserGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BlockUserId name="BlockUserId">BlockUserId</a>

First included in: WorksheetHeader/InventFiscalLIFOJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BlockUserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#deletePostedLines name="deletePostedLines">deletePostedLines</a>

First included in: WorksheetHeader/InventFiscalLIFOJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the deletePostedLines attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: WorksheetHeader/InventFiscalLIFOJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndDate name="EndDate">EndDate</a>

First included in: WorksheetHeader/InventFiscalLIFOJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#FinalReportClosed name="FinalReportClosed">FinalReportClosed</a>

First included in: WorksheetHeader/InventFiscalLIFOJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinalReportClosed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IncludeWIP name="IncludeWIP">IncludeWIP</a>

First included in: WorksheetHeader/InventFiscalLIFOJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeWIP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#JournalId name="JournalId">JournalId</a>

First included in: WorksheetHeader/InventFiscalLIFOJournalTable (this entity)  

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

### <a href=#JournalNameId name="JournalNameId">JournalNameId</a>

First included in: WorksheetHeader/InventFiscalLIFOJournalTable (this entity)  

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

First included in: WorksheetHeader/InventFiscalLIFOJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#NumOfLines name="NumOfLines">NumOfLines</a>

First included in: WorksheetHeader/InventFiscalLIFOJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumOfLines attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Posted name="Posted">Posted</a>

First included in: WorksheetHeader/InventFiscalLIFOJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Closed</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Posted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Closed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PostedDateTime name="PostedDateTime">PostedDateTime</a>

First included in: WorksheetHeader/InventFiscalLIFOJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Closed on</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostedDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Closed on</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#PostedUserId name="PostedUserId">PostedUserId</a>

First included in: WorksheetHeader/InventFiscalLIFOJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Closed by</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostedUserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Closed by</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SessionId name="SessionId">SessionId</a>

First included in: WorksheetHeader/InventFiscalLIFOJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SessionId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SessionLoginDateTime name="SessionLoginDateTime">SessionLoginDateTime</a>

First included in: WorksheetHeader/InventFiscalLIFOJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SessionLoginDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#StartDate name="StartDate">StartDate</a>

First included in: WorksheetHeader/InventFiscalLIFOJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#SystemBlocked name="SystemBlocked">SystemBlocked</a>

First included in: WorksheetHeader/InventFiscalLIFOJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SystemBlocked attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#UseNormalValue name="UseNormalValue">UseNormalValue</a>

First included in: WorksheetHeader/InventFiscalLIFOJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseNormalValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetHeader/InventFiscalLIFOJournalTable (this entity)  

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

### <a href=#Relationship_InventFiscalLIFOJournalNameRelationshipId name="Relationship_InventFiscalLIFOJournalNameRelationshipId">Relationship_InventFiscalLIFOJournalNameRelationshipId</a>

First included in: WorksheetHeader/InventFiscalLIFOJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventFiscalLIFOJournalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/InventFiscalLIFOJournalName.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventFiscalLIFOJournalName.cdm.json/InventFiscalLIFOJournalName</a></td><td><a href="../Group/InventFiscalLIFOJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_JournalErrorRelationshipId name="Relationship_JournalErrorRelationshipId">Relationship_JournalErrorRelationshipId</a>

First included in: WorksheetHeader/InventFiscalLIFOJournalTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_JournalErrorRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetLine/JournalError.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetLine/JournalError.cdm.json/JournalError</a></td><td><a href="../WorksheetLine/JournalError.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_UserGroupInfoRelationshipId name="Relationship_UserGroupInfoRelationshipId">Relationship_UserGroupInfoRelationshipId</a>

First included in: WorksheetHeader/InventFiscalLIFOJournalTable (this entity)  

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

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetHeader/InventFiscalLIFOJournalTable (this entity)  

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
