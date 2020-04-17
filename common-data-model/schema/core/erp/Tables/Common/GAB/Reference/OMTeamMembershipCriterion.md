---
title: OMTeamMembershipCriterion - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# OMTeamMembershipCriterion

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Common/GAB/Reference/OMTeamMembershipCriterion.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[OMTeamMembershipCriterion/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="OMTeamMembershipCriterion.md" target="_blank">Reference/OMTeamMembershipCriterion</a>|
|[AllowContact](#AllowContact)||<a href="OMTeamMembershipCriterion.md" target="_blank">Reference/OMTeamMembershipCriterion</a>|
|[AllowContractor](#AllowContractor)||<a href="OMTeamMembershipCriterion.md" target="_blank">Reference/OMTeamMembershipCriterion</a>|
|[AllowCustomer](#AllowCustomer)||<a href="OMTeamMembershipCriterion.md" target="_blank">Reference/OMTeamMembershipCriterion</a>|
|[AllowEmployee](#AllowEmployee)||<a href="OMTeamMembershipCriterion.md" target="_blank">Reference/OMTeamMembershipCriterion</a>|
|[AllowVendor](#AllowVendor)||<a href="OMTeamMembershipCriterion.md" target="_blank">Reference/OMTeamMembershipCriterion</a>|
|[IsSystemCriterion](#IsSystemCriterion)||<a href="OMTeamMembershipCriterion.md" target="_blank">Reference/OMTeamMembershipCriterion</a>|
|[Name](#Name)||<a href="OMTeamMembershipCriterion.md" target="_blank">Reference/OMTeamMembershipCriterion</a>|
|[RequiresAXUser](#RequiresAXUser)||<a href="OMTeamMembershipCriterion.md" target="_blank">Reference/OMTeamMembershipCriterion</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Reference/OMTeamMembershipCriterion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[OMTeamMembershipCriterion/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AllowContact name="AllowContact">AllowContact</a>

First included in: Reference/OMTeamMembershipCriterion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowContact attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowContractor name="AllowContractor">AllowContractor</a>

First included in: Reference/OMTeamMembershipCriterion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowContractor attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowCustomer name="AllowCustomer">AllowCustomer</a>

First included in: Reference/OMTeamMembershipCriterion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowCustomer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowEmployee name="AllowEmployee">AllowEmployee</a>

First included in: Reference/OMTeamMembershipCriterion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowEmployee attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowVendor name="AllowVendor">AllowVendor</a>

First included in: Reference/OMTeamMembershipCriterion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowVendor attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsSystemCriterion name="IsSystemCriterion">IsSystemCriterion</a>

First included in: Reference/OMTeamMembershipCriterion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSystemCriterion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Reference/OMTeamMembershipCriterion (this entity)  

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

### <a href=#RequiresAXUser name="RequiresAXUser">RequiresAXUser</a>

First included in: Reference/OMTeamMembershipCriterion (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiresAXUser attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>
