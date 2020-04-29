---
title: EESecurityRightsUpdateLog - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Security rights change log

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Transaction/EESecurityRightsUpdateLog.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EESecurityRightsUpdateLog/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Security rights change log</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="EESecurityRightsUpdateLog.md" target="_blank">Transaction/EESecurityRightsUpdateLog</a>|
|[AccessType](#AccessType)||<a href="EESecurityRightsUpdateLog.md" target="_blank">Transaction/EESecurityRightsUpdateLog</a>|
|[OMInternalOrganization](#OMInternalOrganization)||<a href="EESecurityRightsUpdateLog.md" target="_blank">Transaction/EESecurityRightsUpdateLog</a>|
|[SecurityRole](#SecurityRole)||<a href="EESecurityRightsUpdateLog.md" target="_blank">Transaction/EESecurityRightsUpdateLog</a>|
|[UserId](#UserId)||<a href="EESecurityRightsUpdateLog.md" target="_blank">Transaction/EESecurityRightsUpdateLog</a>|
|[ChangedBy](#ChangedBy)||<a href="EESecurityRightsUpdateLog.md" target="_blank">Transaction/EESecurityRightsUpdateLog</a>|
|[SecurityPrivilege](#SecurityPrivilege)||<a href="EESecurityRightsUpdateLog.md" target="_blank">Transaction/EESecurityRightsUpdateLog</a>|
|[ResourceType](#ResourceType)||<a href="EESecurityRightsUpdateLog.md" target="_blank">Transaction/EESecurityRightsUpdateLog</a>|
|[ResourceName](#ResourceName)||<a href="EESecurityRightsUpdateLog.md" target="_blank">Transaction/EESecurityRightsUpdateLog</a>|
|[PreviousAccessType](#PreviousAccessType)||<a href="EESecurityRightsUpdateLog.md" target="_blank">Transaction/EESecurityRightsUpdateLog</a>|
|[AccessChangedDateTime](#AccessChangedDateTime)||<a href="EESecurityRightsUpdateLog.md" target="_blank">Transaction/EESecurityRightsUpdateLog</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/EESecurityRightsUpdateLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EESecurityRightsUpdateLog/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccessType name="AccessType">AccessType</a>

First included in: Transaction/EESecurityRightsUpdateLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>New access</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccessType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>New access</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#OMInternalOrganization name="OMInternalOrganization">OMInternalOrganization</a>

First included in: Transaction/EESecurityRightsUpdateLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OMInternalOrganization attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SecurityRole name="SecurityRole">SecurityRole</a>

First included in: Transaction/EESecurityRightsUpdateLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecurityRole attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UserId name="UserId">UserId</a>

First included in: Transaction/EESecurityRightsUpdateLog (this entity)  

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

### <a href=#ChangedBy name="ChangedBy">ChangedBy</a>

First included in: Transaction/EESecurityRightsUpdateLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChangedBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecurityPrivilege name="SecurityPrivilege">SecurityPrivilege</a>

First included in: Transaction/EESecurityRightsUpdateLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecurityPrivilege attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceType name="ResourceType">ResourceType</a>

First included in: Transaction/EESecurityRightsUpdateLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceName name="ResourceName">ResourceName</a>

First included in: Transaction/EESecurityRightsUpdateLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PreviousAccessType name="PreviousAccessType">PreviousAccessType</a>

First included in: Transaction/EESecurityRightsUpdateLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreviousAccessType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AccessChangedDateTime name="AccessChangedDateTime">AccessChangedDateTime</a>

First included in: Transaction/EESecurityRightsUpdateLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccessChangedDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>
