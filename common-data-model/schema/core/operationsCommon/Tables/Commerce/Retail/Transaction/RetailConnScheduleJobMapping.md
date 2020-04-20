---
title: RetailConnScheduleJobMapping - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailConnScheduleJobMapping

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Transaction/RetailConnScheduleJobMapping.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailConnScheduleJobMapping/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailConnScheduleJobMapping.md" target="_blank">Transaction/RetailConnScheduleJobMapping</a>|
|[enabled](#enabled)||<a href="RetailConnScheduleJobMapping.md" target="_blank">Transaction/RetailConnScheduleJobMapping</a>|
|[lastCheckedDate](#lastCheckedDate)||<a href="RetailConnScheduleJobMapping.md" target="_blank">Transaction/RetailConnScheduleJobMapping</a>|
|[lastCheckedTime](#lastCheckedTime)||<a href="RetailConnScheduleJobMapping.md" target="_blank">Transaction/RetailConnScheduleJobMapping</a>|
|[ScheduleRecId](#ScheduleRecId)||<a href="RetailConnScheduleJobMapping.md" target="_blank">Transaction/RetailConnScheduleJobMapping</a>|
|[SchedulerJobId](#SchedulerJobId)||<a href="RetailConnScheduleJobMapping.md" target="_blank">Transaction/RetailConnScheduleJobMapping</a>|
|[Relationship_RetailConnScheduleRelationshipId](#Relationship_RetailConnScheduleRelationshipId)||<a href="RetailConnScheduleJobMapping.md" target="_blank">Transaction/RetailConnScheduleJobMapping</a>|
|[Relationship_RetailConnSchedulerJobTableRelationshipId](#Relationship_RetailConnSchedulerJobTableRelationshipId)||<a href="RetailConnScheduleJobMapping.md" target="_blank">Transaction/RetailConnScheduleJobMapping</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/RetailConnScheduleJobMapping (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailConnScheduleJobMapping/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#enabled name="enabled">enabled</a>

First included in: Transaction/RetailConnScheduleJobMapping (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the enabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#lastCheckedDate name="lastCheckedDate">lastCheckedDate</a>

First included in: Transaction/RetailConnScheduleJobMapping (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the lastCheckedDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#lastCheckedTime name="lastCheckedTime">lastCheckedTime</a>

First included in: Transaction/RetailConnScheduleJobMapping (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr></table>

#### Traits

<details>
<summary>List of traits for the lastCheckedTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.dataFormat.time**  
</details>

### <a href=#ScheduleRecId name="ScheduleRecId">ScheduleRecId</a>

First included in: Transaction/RetailConnScheduleJobMapping (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScheduleRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SchedulerJobId name="SchedulerJobId">SchedulerJobId</a>

First included in: Transaction/RetailConnScheduleJobMapping (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SchedulerJobId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailConnScheduleRelationshipId name="Relationship_RetailConnScheduleRelationshipId">Relationship_RetailConnScheduleRelationshipId</a>

First included in: Transaction/RetailConnScheduleJobMapping (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailConnScheduleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailConnSchedule.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailConnSchedule.cdm.json/RetailConnSchedule</a></td><td><a href="../Miscellaneous/RetailConnSchedule.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailConnSchedulerJobTableRelationshipId name="Relationship_RetailConnSchedulerJobTableRelationshipId">Relationship_RetailConnSchedulerJobTableRelationshipId</a>

First included in: Transaction/RetailConnScheduleJobMapping (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailConnSchedulerJobTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailConnSchedulerJobTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Main/RetailConnSchedulerJobTable.cdm.json/RetailConnSchedulerJobTable</a></td><td><a href="../Main/RetailConnSchedulerJobTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
