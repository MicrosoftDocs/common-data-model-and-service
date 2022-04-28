---
title: ResAvailabilityViewUserSetting in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# ResAvailabilityViewUserSetting in Miscellaneous

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Miscellaneous/ResAvailabilityViewUserSetting.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ResAvailabilityViewUserSetting/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ResAvailabilityViewUserSetting.md" target="_blank">Miscellaneous/ResAvailabilityViewUserSetting</a>|
|[UserId](#UserId)||<a href="ResAvailabilityViewUserSetting.md" target="_blank">Miscellaneous/ResAvailabilityViewUserSetting</a>|
|[Coverage](#Coverage)||<a href="ResAvailabilityViewUserSetting.md" target="_blank">Miscellaneous/ResAvailabilityViewUserSetting</a>|
|[Timescale](#Timescale)||<a href="ResAvailabilityViewUserSetting.md" target="_blank">Miscellaneous/ResAvailabilityViewUserSetting</a>|
|[DisplayCapacity](#DisplayCapacity)||<a href="ResAvailabilityViewUserSetting.md" target="_blank">Miscellaneous/ResAvailabilityViewUserSetting</a>|
|[DisplayDescriptions](#DisplayDescriptions)||<a href="ResAvailabilityViewUserSetting.md" target="_blank">Miscellaneous/ResAvailabilityViewUserSetting</a>|
|[CapacityAggregation](#CapacityAggregation)||<a href="ResAvailabilityViewUserSetting.md" target="_blank">Miscellaneous/ResAvailabilityViewUserSetting</a>|
|[UserInfo](#UserInfo)||<a href="ResAvailabilityViewUserSetting.md" target="_blank">Miscellaneous/ResAvailabilityViewUserSetting</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/ResAvailabilityViewUserSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ResAvailabilityViewUserSetting/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UserId name="UserId">UserId</a>

First included in: Miscellaneous/ResAvailabilityViewUserSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Coverage name="Coverage">Coverage</a>

First included in: Miscellaneous/ResAvailabilityViewUserSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Coverage attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Timescale name="Timescale">Timescale</a>

First included in: Miscellaneous/ResAvailabilityViewUserSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Timescale attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DisplayCapacity name="DisplayCapacity">DisplayCapacity</a>

First included in: Miscellaneous/ResAvailabilityViewUserSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayCapacity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DisplayDescriptions name="DisplayDescriptions">DisplayDescriptions</a>

First included in: Miscellaneous/ResAvailabilityViewUserSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayDescriptions attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CapacityAggregation name="CapacityAggregation">CapacityAggregation</a>

First included in: Miscellaneous/ResAvailabilityViewUserSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CapacityAggregation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UserInfo name="UserInfo">UserInfo</a>

First included in: Miscellaneous/ResAvailabilityViewUserSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserInfo attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>
