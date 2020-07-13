---
title: DimensionAttribute in Reference - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Dimension in Reference(DimensionAttribute)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FinancialDimensions/Reference/DimensionAttribute.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DimensionAttribute/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Dimension</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[BackingEntityKeyFieldId](#BackingEntityKeyFieldId)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[BackingEntityKeyFieldName](#BackingEntityKeyFieldName)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[BackingEntityTableId](#BackingEntityTableId)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[BackingEntityTableName](#BackingEntityTableName)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[BackingEntityType](#BackingEntityType)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[BackingEntityValueFieldId](#BackingEntityValueFieldId)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[BackingEntityValueFieldName](#BackingEntityValueFieldName)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[HashKey](#HashKey)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[KeyAttribute](#KeyAttribute)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[Name](#Name)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[NameAttribute](#NameAttribute)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[ReportColumnName](#ReportColumnName)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[TranslationKeyFieldId](#TranslationKeyFieldId)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[TranslationKeyFieldName](#TranslationKeyFieldName)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[TranslationLanguageIdFieldId](#TranslationLanguageIdFieldId)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[TranslationLanguageIdFieldName](#TranslationLanguageIdFieldName)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[TranslationNameFieldId](#TranslationNameFieldId)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[TranslationNameFieldName](#TranslationNameFieldName)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[TranslationTableId](#TranslationTableId)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[TranslationTableName](#TranslationTableName)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[Type](#Type)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[UseTranslationNameMethod](#UseTranslationNameMethod)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[ValueAttribute](#ValueAttribute)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[ViewName](#ViewName)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[TranslationViewKeyFieldName](#TranslationViewKeyFieldName)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[TranslationViewLanguageIdFieldName](#TranslationViewLanguageIdFieldName)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[TranslationViewName](#TranslationViewName)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[TranslationViewNameFieldName](#TranslationViewNameFieldName)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[TranslationViewSystemLanguageIdFieldName](#TranslationViewSystemLanguageIdFieldName)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[TranslationViewTranslatedNameFieldName](#TranslationViewTranslatedNameFieldName)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[TranslationViewValueFieldName](#TranslationViewValueFieldName)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[TranslationViewId](#TranslationViewId)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[TranslationViewKeyFieldId](#TranslationViewKeyFieldId)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[TranslationViewLanguageIdFieldId](#TranslationViewLanguageIdFieldId)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[TranslationViewNameFieldId](#TranslationViewNameFieldId)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[TranslationViewSystemLanguageIdFieldId](#TranslationViewSystemLanguageIdFieldId)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[TranslationViewTranslatedNameFieldId](#TranslationViewTranslatedNameFieldId)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[TranslationViewValueFieldId](#TranslationViewValueFieldId)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[DimensionKeyColumnName](#DimensionKeyColumnName)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[DimensionValueColumnName](#DimensionValueColumnName)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[CopyValuesOnCreate](#CopyValuesOnCreate)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[GiveDerivedDimensionsPrecedence](#GiveDerivedDimensionsPrecedence)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[IsBalancing_PSN](#IsBalancing_PSN)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|
|[BalancingDimension_PSN](#BalancingDimension_PSN)||<a href="DimensionAttribute.md" target="_blank">Reference/DimensionAttribute</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DimensionAttribute/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BackingEntityKeyFieldId name="BackingEntityKeyFieldId">BackingEntityKeyFieldId</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingEntityKeyFieldId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#BackingEntityKeyFieldName name="BackingEntityKeyFieldName">BackingEntityKeyFieldName</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingEntityKeyFieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingEntityTableId name="BackingEntityTableId">BackingEntityTableId</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingEntityTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#BackingEntityTableName name="BackingEntityTableName">BackingEntityTableName</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingEntityTableName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingEntityType name="BackingEntityType">BackingEntityType</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingEntityType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BackingEntityValueFieldId name="BackingEntityValueFieldId">BackingEntityValueFieldId</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingEntityValueFieldId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#BackingEntityValueFieldName name="BackingEntityValueFieldName">BackingEntityValueFieldName</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingEntityValueFieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HashKey name="HashKey">HashKey</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HashKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KeyAttribute name="KeyAttribute">KeyAttribute</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Key field</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KeyAttribute attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Key field</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Dimension name</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Dimension name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NameAttribute name="NameAttribute">NameAttribute</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name field</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NameAttribute attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Name field</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ReportColumnName name="ReportColumnName">ReportColumnName</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportColumnName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TranslationKeyFieldId name="TranslationKeyFieldId">TranslationKeyFieldId</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Translation key field</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslationKeyFieldId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Translation key field</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TranslationKeyFieldName name="TranslationKeyFieldName">TranslationKeyFieldName</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Translation key field name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslationKeyFieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Translation key field name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TranslationLanguageIdFieldId name="TranslationLanguageIdFieldId">TranslationLanguageIdFieldId</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Translation language ID field</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslationLanguageIdFieldId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Translation language ID field</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TranslationLanguageIdFieldName name="TranslationLanguageIdFieldName">TranslationLanguageIdFieldName</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Translation language ID field name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslationLanguageIdFieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Translation language ID field name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TranslationNameFieldId name="TranslationNameFieldId">TranslationNameFieldId</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Translation name field</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslationNameFieldId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Translation name field</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TranslationNameFieldName name="TranslationNameFieldName">TranslationNameFieldName</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Translation name field name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslationNameFieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Translation name field name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TranslationTableId name="TranslationTableId">TranslationTableId</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Translation table ID</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslationTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Translation table ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TranslationTableName name="TranslationTableName">TranslationTableName</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Translation table name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslationTableName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Translation table name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Type name="Type">Type</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Type attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#UseTranslationNameMethod name="UseTranslationNameMethod">UseTranslationNameMethod</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use the translation name method</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseTranslationNameMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use the translation name method</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ValueAttribute name="ValueAttribute">ValueAttribute</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Value field</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValueAttribute attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value field</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ViewName name="ViewName">ViewName</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TranslationViewKeyFieldName name="TranslationViewKeyFieldName">TranslationViewKeyFieldName</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslationViewKeyFieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TranslationViewLanguageIdFieldName name="TranslationViewLanguageIdFieldName">TranslationViewLanguageIdFieldName</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslationViewLanguageIdFieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TranslationViewName name="TranslationViewName">TranslationViewName</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslationViewName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TranslationViewNameFieldName name="TranslationViewNameFieldName">TranslationViewNameFieldName</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslationViewNameFieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TranslationViewSystemLanguageIdFieldName name="TranslationViewSystemLanguageIdFieldName">TranslationViewSystemLanguageIdFieldName</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslationViewSystemLanguageIdFieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TranslationViewTranslatedNameFieldName name="TranslationViewTranslatedNameFieldName">TranslationViewTranslatedNameFieldName</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslationViewTranslatedNameFieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TranslationViewValueFieldName name="TranslationViewValueFieldName">TranslationViewValueFieldName</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslationViewValueFieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TranslationViewId name="TranslationViewId">TranslationViewId</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslationViewId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TranslationViewKeyFieldId name="TranslationViewKeyFieldId">TranslationViewKeyFieldId</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslationViewKeyFieldId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TranslationViewLanguageIdFieldId name="TranslationViewLanguageIdFieldId">TranslationViewLanguageIdFieldId</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslationViewLanguageIdFieldId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TranslationViewNameFieldId name="TranslationViewNameFieldId">TranslationViewNameFieldId</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslationViewNameFieldId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TranslationViewSystemLanguageIdFieldId name="TranslationViewSystemLanguageIdFieldId">TranslationViewSystemLanguageIdFieldId</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslationViewSystemLanguageIdFieldId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TranslationViewTranslatedNameFieldId name="TranslationViewTranslatedNameFieldId">TranslationViewTranslatedNameFieldId</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslationViewTranslatedNameFieldId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TranslationViewValueFieldId name="TranslationViewValueFieldId">TranslationViewValueFieldId</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslationViewValueFieldId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DimensionKeyColumnName name="DimensionKeyColumnName">DimensionKeyColumnName</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>The name of the column that contains the specific instance of the backing entity for the dimension attribute value.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionKeyColumnName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The name of the column that contains the specific instance of the backing entity for the dimension attribute value.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionValueColumnName name="DimensionValueColumnName">DimensionValueColumnName</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>The name of the column that contains the value for the dimension attribute value.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionValueColumnName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The name of the column that contains the value for the dimension attribute value.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CopyValuesOnCreate name="CopyValuesOnCreate">CopyValuesOnCreate</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Copy values on dimension value creation</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CopyValuesOnCreate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Copy values on dimension value creation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#GiveDerivedDimensionsPrecedence name="GiveDerivedDimensionsPrecedence">GiveDerivedDimensionsPrecedence</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Replace existing dimension values with derived values </td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiveDerivedDimensionsPrecedence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Replace existing dimension values with derived values </td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsBalancing_PSN name="IsBalancing_PSN">IsBalancing_PSN</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Require the dimension to be balanced</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBalancing_PSN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Require the dimension to be balanced</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#BalancingDimension_PSN name="BalancingDimension_PSN">BalancingDimension_PSN</a>

First included in: Reference/DimensionAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Require values for the dimension to be balanced with</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BalancingDimension_PSN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Require values for the dimension to be balanced with</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>
