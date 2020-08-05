---
title: TaxAcctTaxTransTaxDocAttributeMapping in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# The mapping between taxTrans field id and tax document line attribute in Miscellaneous(TaxAcctTaxTransTaxDocAttributeMapping)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/Miscellaneous/TaxAcctTaxTransTaxDocAttributeMapping.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxAcctTaxTransTaxDocAttributeMapping/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The mapping between taxTrans field id and tax document line attribute</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxAcctTaxTransTaxDocAttributeMapping.md" target="_blank">Miscellaneous/TaxAcctTaxTransTaxDocAttributeMapping</a>|
|[AttributeName](#AttributeName)||<a href="TaxAcctTaxTransTaxDocAttributeMapping.md" target="_blank">Miscellaneous/TaxAcctTaxTransTaxDocAttributeMapping</a>|
|[AttributeSourceTableId](#AttributeSourceTableId)||<a href="TaxAcctTaxTransTaxDocAttributeMapping.md" target="_blank">Miscellaneous/TaxAcctTaxTransTaxDocAttributeMapping</a>|
|[AttributeSourceTableMethod](#AttributeSourceTableMethod)||<a href="TaxAcctTaxTransTaxDocAttributeMapping.md" target="_blank">Miscellaneous/TaxAcctTaxTransTaxDocAttributeMapping</a>|
|[IsHeaderLineAttribute](#IsHeaderLineAttribute)||<a href="TaxAcctTaxTransTaxDocAttributeMapping.md" target="_blank">Miscellaneous/TaxAcctTaxTransTaxDocAttributeMapping</a>|
|[TaxTransFieldId](#TaxTransFieldId)||<a href="TaxAcctTaxTransTaxDocAttributeMapping.md" target="_blank">Miscellaneous/TaxAcctTaxTransTaxDocAttributeMapping</a>|
|[TaxTransTableId](#TaxTransTableId)||<a href="TaxAcctTaxTransTaxDocAttributeMapping.md" target="_blank">Miscellaneous/TaxAcctTaxTransTaxDocAttributeMapping</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/TaxAcctTaxTransTaxDocAttributeMapping (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxAcctTaxTransTaxDocAttributeMapping/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AttributeName name="AttributeName">AttributeName</a>

First included in: Miscellaneous/TaxAcctTaxTransTaxDocAttributeMapping (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Attribute name</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttributeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Attribute name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AttributeSourceTableId name="AttributeSourceTableId">AttributeSourceTableId</a>

First included in: Miscellaneous/TaxAcctTaxTransTaxDocAttributeMapping (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>The table ID of the attribute table</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttributeSourceTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The table ID of the attribute table</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#AttributeSourceTableMethod name="AttributeSourceTableMethod">AttributeSourceTableMethod</a>

First included in: Miscellaneous/TaxAcctTaxTransTaxDocAttributeMapping (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttributeSourceTableMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsHeaderLineAttribute name="IsHeaderLineAttribute">IsHeaderLineAttribute</a>

First included in: Miscellaneous/TaxAcctTaxTransTaxDocAttributeMapping (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Indicates if this attribute is a header line attribute</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsHeaderLineAttribute attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indicates if this attribute is a header line attribute</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TaxTransFieldId name="TaxTransFieldId">TaxTransFieldId</a>

First included in: Miscellaneous/TaxAcctTaxTransTaxDocAttributeMapping (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>The field if of taxTrans.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxTransFieldId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The field if of taxTrans.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TaxTransTableId name="TaxTransTableId">TaxTransTableId</a>

First included in: Miscellaneous/TaxAcctTaxTransTaxDocAttributeMapping (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>The table ID of TaxTrans.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxTransTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The table ID of TaxTrans.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>
