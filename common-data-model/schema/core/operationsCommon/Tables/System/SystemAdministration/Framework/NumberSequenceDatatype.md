---
title: NumberSequenceDatatype in Framework - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Datatype number sequence properties in Framework(NumberSequenceDatatype)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Framework/NumberSequenceDatatype.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[NumberSequenceDatatype/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Datatype number sequence properties</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="NumberSequenceDatatype.md" target="_blank">Framework/NumberSequenceDatatype</a>|
|[configurationKeyId](#configurationKeyId)||<a href="NumberSequenceDatatype.md" target="_blank">Framework/NumberSequenceDatatype</a>|
|[DatatypeId](#DatatypeId)||<a href="NumberSequenceDatatype.md" target="_blank">Framework/NumberSequenceDatatype</a>|
|[DataTypeSameAsId](#DataTypeSameAsId)||<a href="NumberSequenceDatatype.md" target="_blank">Framework/NumberSequenceDatatype</a>|
|[GroupEnabled](#GroupEnabled)||<a href="NumberSequenceDatatype.md" target="_blank">Framework/NumberSequenceDatatype</a>|
|[ReferenceHelp](#ReferenceHelp)||<a href="NumberSequenceDatatype.md" target="_blank">Framework/NumberSequenceDatatype</a>|
|[ReferenceLabel](#ReferenceLabel)||<a href="NumberSequenceDatatype.md" target="_blank">Framework/NumberSequenceDatatype</a>|
|[ScopeType](#ScopeType)||<a href="NumberSequenceDatatype.md" target="_blank">Framework/NumberSequenceDatatype</a>|
|[SortField](#SortField)||<a href="NumberSequenceDatatype.md" target="_blank">Framework/NumberSequenceDatatype</a>|
|[WizardAllowChangeDown](#WizardAllowChangeDown)||<a href="NumberSequenceDatatype.md" target="_blank">Framework/NumberSequenceDatatype</a>|
|[WizardAllowChangeUp](#WizardAllowChangeUp)||<a href="NumberSequenceDatatype.md" target="_blank">Framework/NumberSequenceDatatype</a>|
|[WizardContinuous](#WizardContinuous)||<a href="NumberSequenceDatatype.md" target="_blank">Framework/NumberSequenceDatatype</a>|
|[WizardFetchAheadQty](#WizardFetchAheadQty)||<a href="NumberSequenceDatatype.md" target="_blank">Framework/NumberSequenceDatatype</a>|
|[WizardHighest](#WizardHighest)||<a href="NumberSequenceDatatype.md" target="_blank">Framework/NumberSequenceDatatype</a>|
|[WizardLowest](#WizardLowest)||<a href="NumberSequenceDatatype.md" target="_blank">Framework/NumberSequenceDatatype</a>|
|[WizardManual](#WizardManual)||<a href="NumberSequenceDatatype.md" target="_blank">Framework/NumberSequenceDatatype</a>|
|[WizardDefaultRangeSizePerDeployment](#WizardDefaultRangeSizePerDeployment)||<a href="NumberSequenceDatatype.md" target="_blank">Framework/NumberSequenceDatatype</a>|
|[Module](#Module)||<a href="NumberSequenceDatatype.md" target="_blank">Framework/NumberSequenceDatatype</a>|
|[ReferenceTableId](#ReferenceTableId)||<a href="NumberSequenceDatatype.md" target="_blank">Framework/NumberSequenceDatatype</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Framework/NumberSequenceDatatype (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[NumberSequenceDatatype/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#configurationKeyId name="configurationKeyId">configurationKeyId</a>

First included in: Framework/NumberSequenceDatatype (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the configurationKeyId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DatatypeId name="DatatypeId">DatatypeId</a>

First included in: Framework/NumberSequenceDatatype (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Data type</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DatatypeId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Data type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DataTypeSameAsId name="DataTypeSameAsId">DataTypeSameAsId</a>

First included in: Framework/NumberSequenceDatatype (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataTypeSameAsId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#GroupEnabled name="GroupEnabled">GroupEnabled</a>

First included in: Framework/NumberSequenceDatatype (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReferenceHelp name="ReferenceHelp">ReferenceHelp</a>

First included in: Framework/NumberSequenceDatatype (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReferenceHelp attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReferenceLabel name="ReferenceLabel">ReferenceLabel</a>

First included in: Framework/NumberSequenceDatatype (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReferenceLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScopeType name="ScopeType">ScopeType</a>

First included in: Framework/NumberSequenceDatatype (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scope type</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScopeType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Scope type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SortField name="SortField">SortField</a>

First included in: Framework/NumberSequenceDatatype (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sorting</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortField attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sorting</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#WizardAllowChangeDown name="WizardAllowChangeDown">WizardAllowChangeDown</a>

First included in: Framework/NumberSequenceDatatype (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WizardAllowChangeDown attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#WizardAllowChangeUp name="WizardAllowChangeUp">WizardAllowChangeUp</a>

First included in: Framework/NumberSequenceDatatype (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WizardAllowChangeUp attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#WizardContinuous name="WizardContinuous">WizardContinuous</a>

First included in: Framework/NumberSequenceDatatype (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WizardContinuous attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#WizardFetchAheadQty name="WizardFetchAheadQty">WizardFetchAheadQty</a>

First included in: Framework/NumberSequenceDatatype (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WizardFetchAheadQty attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#WizardHighest name="WizardHighest">WizardHighest</a>

First included in: Framework/NumberSequenceDatatype (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WizardHighest attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#WizardLowest name="WizardLowest">WizardLowest</a>

First included in: Framework/NumberSequenceDatatype (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WizardLowest attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#WizardManual name="WizardManual">WizardManual</a>

First included in: Framework/NumberSequenceDatatype (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WizardManual attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#WizardDefaultRangeSizePerDeployment name="WizardDefaultRangeSizePerDeployment">WizardDefaultRangeSizePerDeployment</a>

First included in: Framework/NumberSequenceDatatype (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WizardDefaultRangeSizePerDeployment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Module name="Module">Module</a>

First included in: Framework/NumberSequenceDatatype (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Module attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReferenceTableId name="ReferenceTableId">ReferenceTableId</a>

First included in: Framework/NumberSequenceDatatype (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Table</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReferenceTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Table</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>
