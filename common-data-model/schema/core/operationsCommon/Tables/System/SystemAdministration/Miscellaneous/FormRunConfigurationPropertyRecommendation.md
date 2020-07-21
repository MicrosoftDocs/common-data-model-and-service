---
title: FormRunConfigurationPropertyRecommendation in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# FormRunConfigurationPropertyRecommendation in Miscellaneous

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/FormRunConfigurationPropertyRecommendation.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FormRunConfigurationPropertyRecommendation/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FormRunConfigurationPropertyRecommendation.md" target="_blank">Miscellaneous/FormRunConfigurationPropertyRecommendation</a>|
|[Owner](#Owner)||<a href="FormRunConfigurationPropertyRecommendation.md" target="_blank">Miscellaneous/FormRunConfigurationPropertyRecommendation</a>|
|[FormViewOptionType](#FormViewOptionType)||<a href="FormRunConfigurationPropertyRecommendation.md" target="_blank">Miscellaneous/FormRunConfigurationPropertyRecommendation</a>|
|[Property](#Property)||<a href="FormRunConfigurationPropertyRecommendation.md" target="_blank">Miscellaneous/FormRunConfigurationPropertyRecommendation</a>|
|[TargetControl](#TargetControl)||<a href="FormRunConfigurationPropertyRecommendation.md" target="_blank">Miscellaneous/FormRunConfigurationPropertyRecommendation</a>|
|[PropertyValue](#PropertyValue)||<a href="FormRunConfigurationPropertyRecommendation.md" target="_blank">Miscellaneous/FormRunConfigurationPropertyRecommendation</a>|
|[WeightedValue](#WeightedValue)||<a href="FormRunConfigurationPropertyRecommendation.md" target="_blank">Miscellaneous/FormRunConfigurationPropertyRecommendation</a>|
|[SystemVersion](#SystemVersion)||<a href="FormRunConfigurationPropertyRecommendation.md" target="_blank">Miscellaneous/FormRunConfigurationPropertyRecommendation</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/FormRunConfigurationPropertyRecommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FormRunConfigurationPropertyRecommendation/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Owner name="Owner">Owner</a>

First included in: Miscellaneous/FormRunConfigurationPropertyRecommendation (this entity)  

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

### <a href=#FormViewOptionType name="FormViewOptionType">FormViewOptionType</a>

First included in: Miscellaneous/FormRunConfigurationPropertyRecommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormViewOptionType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Property name="Property">Property</a>

First included in: Miscellaneous/FormRunConfigurationPropertyRecommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Property attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TargetControl name="TargetControl">TargetControl</a>

First included in: Miscellaneous/FormRunConfigurationPropertyRecommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Control</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TargetControl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Control</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PropertyValue name="PropertyValue">PropertyValue</a>

First included in: Miscellaneous/FormRunConfigurationPropertyRecommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PropertyValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WeightedValue name="WeightedValue">WeightedValue</a>

First included in: Miscellaneous/FormRunConfigurationPropertyRecommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WeightedValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SystemVersion name="SystemVersion">SystemVersion</a>

First included in: Miscellaneous/FormRunConfigurationPropertyRecommendation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SystemVersion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>
