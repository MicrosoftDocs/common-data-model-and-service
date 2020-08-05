---
title: RetailConnSchedulerSubjobFieldList in Parameter - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Retail Scheduler subjob field list in Parameter(RetailConnSchedulerSubjobFieldList)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/ChannelManagement/Parameter/RetailConnSchedulerSubjobFieldList.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailConnSchedulerSubjobFieldList/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Retail Scheduler subjob field list</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailConnSchedulerSubjobFieldList.md" target="_blank">Parameter/RetailConnSchedulerSubjobFieldList</a>|
|[conversionType](#conversionType)||<a href="RetailConnSchedulerSubjobFieldList.md" target="_blank">Parameter/RetailConnSchedulerSubjobFieldList</a>|
|[conversionValue](#conversionValue)||<a href="RetailConnSchedulerSubjobFieldList.md" target="_blank">Parameter/RetailConnSchedulerSubjobFieldList</a>|
|[fieldValue](#fieldValue)||<a href="RetailConnSchedulerSubjobFieldList.md" target="_blank">Parameter/RetailConnSchedulerSubjobFieldList</a>|
|[fromFieldName](#fromFieldName)||<a href="RetailConnSchedulerSubjobFieldList.md" target="_blank">Parameter/RetailConnSchedulerSubjobFieldList</a>|
|[subjobId](#subjobId)||<a href="RetailConnSchedulerSubjobFieldList.md" target="_blank">Parameter/RetailConnSchedulerSubjobFieldList</a>|
|[toFieldName](#toFieldName)||<a href="RetailConnSchedulerSubjobFieldList.md" target="_blank">Parameter/RetailConnSchedulerSubjobFieldList</a>|
|[Relationship_RetailConnSchedulerSubjobTableRelationshipId](#Relationship_RetailConnSchedulerSubjobTableRelationshipId)||<a href="RetailConnSchedulerSubjobFieldList.md" target="_blank">Parameter/RetailConnSchedulerSubjobFieldList</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/RetailConnSchedulerSubjobFieldList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailConnSchedulerSubjobFieldList/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#conversionType name="conversionType">conversionType</a>

First included in: Parameter/RetailConnSchedulerSubjobFieldList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the conversionType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#conversionValue name="conversionValue">conversionValue</a>

First included in: Parameter/RetailConnSchedulerSubjobFieldList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the conversionValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#fieldValue name="fieldValue">fieldValue</a>

First included in: Parameter/RetailConnSchedulerSubjobFieldList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the fieldValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#fromFieldName name="fromFieldName">fromFieldName</a>

First included in: Parameter/RetailConnSchedulerSubjobFieldList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>From field</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the fromFieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>From field</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#subjobId name="subjobId">subjobId</a>

First included in: Parameter/RetailConnSchedulerSubjobFieldList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the subjobId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#toFieldName name="toFieldName">toFieldName</a>

First included in: Parameter/RetailConnSchedulerSubjobFieldList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>To field</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the toFieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>To field</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailConnSchedulerSubjobTableRelationshipId name="Relationship_RetailConnSchedulerSubjobTableRelationshipId">Relationship_RetailConnSchedulerSubjobTableRelationshipId</a>

First included in: Parameter/RetailConnSchedulerSubjobFieldList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailConnSchedulerSubjobTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailConnSchedulerSubjobTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/Main/RetailConnSchedulerSubjobTable.cdm.json/RetailConnSchedulerSubjobTable</a></td><td><a href="../Main/RetailConnSchedulerSubjobTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
