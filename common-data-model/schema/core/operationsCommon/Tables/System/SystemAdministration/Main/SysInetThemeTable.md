---
title: SysInetThemeTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# SysInetThemeTable

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Main/SysInetThemeTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysInetThemeTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="SysInetThemeTable.md" target="_blank">Main/SysInetThemeTable</a>|
|[BottomText](#BottomText)||<a href="SysInetThemeTable.md" target="_blank">Main/SysInetThemeTable</a>|
|[FormStyleSheet](#FormStyleSheet)||<a href="SysInetThemeTable.md" target="_blank">Main/SysInetThemeTable</a>|
|[FrameworkStylesheet](#FrameworkStylesheet)||<a href="SysInetThemeTable.md" target="_blank">Main/SysInetThemeTable</a>|
|[ImageList](#ImageList)||<a href="SysInetThemeTable.md" target="_blank">Main/SysInetThemeTable</a>|
|[MenuStyleSheet](#MenuStyleSheet)||<a href="SysInetThemeTable.md" target="_blank">Main/SysInetThemeTable</a>|
|[Name](#Name)||<a href="SysInetThemeTable.md" target="_blank">Main/SysInetThemeTable</a>|
|[ReportStyleSheet](#ReportStyleSheet)||<a href="SysInetThemeTable.md" target="_blank">Main/SysInetThemeTable</a>|
|[StyleSheet](#StyleSheet)||<a href="SysInetThemeTable.md" target="_blank">Main/SysInetThemeTable</a>|
|[ThemeType](#ThemeType)||<a href="SysInetThemeTable.md" target="_blank">Main/SysInetThemeTable</a>|
|[ToolbarStylesheet](#ToolbarStylesheet)||<a href="SysInetThemeTable.md" target="_blank">Main/SysInetThemeTable</a>|
|[TopText](#TopText)||<a href="SysInetThemeTable.md" target="_blank">Main/SysInetThemeTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/SysInetThemeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysInetThemeTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BottomText name="BottomText">BottomText</a>

First included in: Main/SysInetThemeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BottomText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormStyleSheet name="FormStyleSheet">FormStyleSheet</a>

First included in: Main/SysInetThemeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormStyleSheet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FrameworkStylesheet name="FrameworkStylesheet">FrameworkStylesheet</a>

First included in: Main/SysInetThemeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FrameworkStylesheet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ImageList name="ImageList">ImageList</a>

First included in: Main/SysInetThemeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImageList attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#MenuStyleSheet name="MenuStyleSheet">MenuStyleSheet</a>

First included in: Main/SysInetThemeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MenuStyleSheet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Main/SysInetThemeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportStyleSheet name="ReportStyleSheet">ReportStyleSheet</a>

First included in: Main/SysInetThemeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportStyleSheet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StyleSheet name="StyleSheet">StyleSheet</a>

First included in: Main/SysInetThemeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StyleSheet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThemeType name="ThemeType">ThemeType</a>

First included in: Main/SysInetThemeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThemeType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ToolbarStylesheet name="ToolbarStylesheet">ToolbarStylesheet</a>

First included in: Main/SysInetThemeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToolbarStylesheet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TopText name="TopText">TopText</a>

First included in: Main/SysInetThemeTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TopText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
