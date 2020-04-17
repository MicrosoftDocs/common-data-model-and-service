---
title: FormRunConfigurationOptions - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# FormRunConfigurationOptions

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/System/SystemAdministration/Miscellaneous/FormRunConfigurationOptions.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FormRunConfigurationOptions/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FormRunConfigurationOptions.md" target="_blank">Miscellaneous/FormRunConfigurationOptions</a>|
|[Owner](#Owner)||<a href="FormRunConfigurationOptions.md" target="_blank">Miscellaneous/FormRunConfigurationOptions</a>|
|[Enabled](#Enabled)||<a href="FormRunConfigurationOptions.md" target="_blank">Miscellaneous/FormRunConfigurationOptions</a>|
|[User](#User)||<a href="FormRunConfigurationOptions.md" target="_blank">Miscellaneous/FormRunConfigurationOptions</a>|
|[EnabledExplicitPersonalization](#EnabledExplicitPersonalization)||<a href="FormRunConfigurationOptions.md" target="_blank">Miscellaneous/FormRunConfigurationOptions</a>|
|[StoreUsageData](#StoreUsageData)||<a href="FormRunConfigurationOptions.md" target="_blank">Miscellaneous/FormRunConfigurationOptions</a>|
|[UpgradeUsageData](#UpgradeUsageData)||<a href="FormRunConfigurationOptions.md" target="_blank">Miscellaneous/FormRunConfigurationOptions</a>|
|[StoreFilterData](#StoreFilterData)||<a href="FormRunConfigurationOptions.md" target="_blank">Miscellaneous/FormRunConfigurationOptions</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/FormRunConfigurationOptions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FormRunConfigurationOptions/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Owner name="Owner">Owner</a>

First included in: Miscellaneous/FormRunConfigurationOptions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Owner attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Enabled name="Enabled">Enabled</a>

First included in: Miscellaneous/FormRunConfigurationOptions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Enabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#User name="User">User</a>

First included in: Miscellaneous/FormRunConfigurationOptions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the User attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnabledExplicitPersonalization name="EnabledExplicitPersonalization">EnabledExplicitPersonalization</a>

First included in: Miscellaneous/FormRunConfigurationOptions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnabledExplicitPersonalization attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StoreUsageData name="StoreUsageData">StoreUsageData</a>

First included in: Miscellaneous/FormRunConfigurationOptions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreUsageData attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UpgradeUsageData name="UpgradeUsageData">UpgradeUsageData</a>

First included in: Miscellaneous/FormRunConfigurationOptions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpgradeUsageData attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StoreFilterData name="StoreFilterData">StoreFilterData</a>

First included in: Miscellaneous/FormRunConfigurationOptions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreFilterData attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>
