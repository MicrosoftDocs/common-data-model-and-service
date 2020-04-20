---
title: DocumentRoutingJob - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# DocumentRoutingJob

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/DocumentRoutingJob.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DocumentRoutingJob/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="DocumentRoutingJob.md" target="_blank">Miscellaneous/DocumentRoutingJob</a>|
|[JobId](#JobId)||<a href="DocumentRoutingJob.md" target="_blank">Miscellaneous/DocumentRoutingJob</a>|
|[ActivityId](#ActivityId)||<a href="DocumentRoutingJob.md" target="_blank">Miscellaneous/DocumentRoutingJob</a>|
|[PrinterName](#PrinterName)||<a href="DocumentRoutingJob.md" target="_blank">Miscellaneous/DocumentRoutingJob</a>|
|[PrinterPath](#PrinterPath)||<a href="DocumentRoutingJob.md" target="_blank">Miscellaneous/DocumentRoutingJob</a>|
|[ReportName](#ReportName)||<a href="DocumentRoutingJob.md" target="_blank">Miscellaneous/DocumentRoutingJob</a>|
|[JobStatus](#JobStatus)||<a href="DocumentRoutingJob.md" target="_blank">Miscellaneous/DocumentRoutingJob</a>|
|[Message](#Message)||<a href="DocumentRoutingJob.md" target="_blank">Miscellaneous/DocumentRoutingJob</a>|
|[TotalNumberOfPages](#TotalNumberOfPages)||<a href="DocumentRoutingJob.md" target="_blank">Miscellaneous/DocumentRoutingJob</a>|
|[StartProcessTime](#StartProcessTime)||<a href="DocumentRoutingJob.md" target="_blank">Miscellaneous/DocumentRoutingJob</a>|
|[EndProcessTime](#EndProcessTime)||<a href="DocumentRoutingJob.md" target="_blank">Miscellaneous/DocumentRoutingJob</a>|
|[CompanyId](#CompanyId)||<a href="DocumentRoutingJob.md" target="_blank">Miscellaneous/DocumentRoutingJob</a>|
|[PrinterId](#PrinterId)||<a href="DocumentRoutingJob.md" target="_blank">Miscellaneous/DocumentRoutingJob</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/DocumentRoutingJob (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DocumentRoutingJob/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#JobId name="JobId">JobId</a>

First included in: Miscellaneous/DocumentRoutingJob (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActivityId name="ActivityId">ActivityId</a>

First included in: Miscellaneous/DocumentRoutingJob (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrinterName name="PrinterName">PrinterName</a>

First included in: Miscellaneous/DocumentRoutingJob (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrinterName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrinterPath name="PrinterPath">PrinterPath</a>

First included in: Miscellaneous/DocumentRoutingJob (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrinterPath attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportName name="ReportName">ReportName</a>

First included in: Miscellaneous/DocumentRoutingJob (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobStatus name="JobStatus">JobStatus</a>

First included in: Miscellaneous/DocumentRoutingJob (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Message name="Message">Message</a>

First included in: Miscellaneous/DocumentRoutingJob (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Message attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalNumberOfPages name="TotalNumberOfPages">TotalNumberOfPages</a>

First included in: Miscellaneous/DocumentRoutingJob (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalNumberOfPages attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StartProcessTime name="StartProcessTime">StartProcessTime</a>

First included in: Miscellaneous/DocumentRoutingJob (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartProcessTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#EndProcessTime name="EndProcessTime">EndProcessTime</a>

First included in: Miscellaneous/DocumentRoutingJob (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndProcessTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#CompanyId name="CompanyId">CompanyId</a>

First included in: Miscellaneous/DocumentRoutingJob (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrinterId name="PrinterId">PrinterId</a>

First included in: Miscellaneous/DocumentRoutingJob (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrinterId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
