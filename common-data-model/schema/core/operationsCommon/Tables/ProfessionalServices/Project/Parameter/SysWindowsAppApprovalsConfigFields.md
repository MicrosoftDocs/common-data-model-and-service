---
title: SysWindowsAppApprovalsConfigFields - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# SysWindowsAppApprovalsConfigFields

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/ProfessionalServices/Project/Parameter/SysWindowsAppApprovalsConfigFields.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysWindowsAppApprovalsConfigFields/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="SysWindowsAppApprovalsConfigFields.md" target="_blank">Parameter/SysWindowsAppApprovalsConfigFields</a>|
|[ApprovalsConfig](#ApprovalsConfig)||<a href="SysWindowsAppApprovalsConfigFields.md" target="_blank">Parameter/SysWindowsAppApprovalsConfigFields</a>|
|[DocumentBaseType](#DocumentBaseType)||<a href="SysWindowsAppApprovalsConfigFields.md" target="_blank">Parameter/SysWindowsAppApprovalsConfigFields</a>|
|[DocumentEnumId](#DocumentEnumId)||<a href="SysWindowsAppApprovalsConfigFields.md" target="_blank">Parameter/SysWindowsAppApprovalsConfigFields</a>|
|[DocumentFieldId](#DocumentFieldId)||<a href="SysWindowsAppApprovalsConfigFields.md" target="_blank">Parameter/SysWindowsAppApprovalsConfigFields</a>|
|[DocumentFieldLabel](#DocumentFieldLabel)||<a href="SysWindowsAppApprovalsConfigFields.md" target="_blank">Parameter/SysWindowsAppApprovalsConfigFields</a>|
|[DocumentFieldName](#DocumentFieldName)||<a href="SysWindowsAppApprovalsConfigFields.md" target="_blank">Parameter/SysWindowsAppApprovalsConfigFields</a>|
|[DocumentFieldType](#DocumentFieldType)||<a href="SysWindowsAppApprovalsConfigFields.md" target="_blank">Parameter/SysWindowsAppApprovalsConfigFields</a>|
|[DocumentPlaceholderName](#DocumentPlaceholderName)||<a href="SysWindowsAppApprovalsConfigFields.md" target="_blank">Parameter/SysWindowsAppApprovalsConfigFields</a>|
|[DocumentTableId](#DocumentTableId)||<a href="SysWindowsAppApprovalsConfigFields.md" target="_blank">Parameter/SysWindowsAppApprovalsConfigFields</a>|
|[LineNum](#LineNum)||<a href="SysWindowsAppApprovalsConfigFields.md" target="_blank">Parameter/SysWindowsAppApprovalsConfigFields</a>|
|[TileFieldType](#TileFieldType)||<a href="SysWindowsAppApprovalsConfigFields.md" target="_blank">Parameter/SysWindowsAppApprovalsConfigFields</a>|
|[Relationship_SysWindowsAppApprovalsConfigRelationshipId](#Relationship_SysWindowsAppApprovalsConfigRelationshipId)||<a href="SysWindowsAppApprovalsConfigFields.md" target="_blank">Parameter/SysWindowsAppApprovalsConfigFields</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/SysWindowsAppApprovalsConfigFields (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysWindowsAppApprovalsConfigFields/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ApprovalsConfig name="ApprovalsConfig">ApprovalsConfig</a>

First included in: Parameter/SysWindowsAppApprovalsConfigFields (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApprovalsConfig attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DocumentBaseType name="DocumentBaseType">DocumentBaseType</a>

First included in: Parameter/SysWindowsAppApprovalsConfigFields (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentBaseType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DocumentEnumId name="DocumentEnumId">DocumentEnumId</a>

First included in: Parameter/SysWindowsAppApprovalsConfigFields (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentEnumId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DocumentFieldId name="DocumentFieldId">DocumentFieldId</a>

First included in: Parameter/SysWindowsAppApprovalsConfigFields (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentFieldId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DocumentFieldLabel name="DocumentFieldLabel">DocumentFieldLabel</a>

First included in: Parameter/SysWindowsAppApprovalsConfigFields (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentFieldLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentFieldName name="DocumentFieldName">DocumentFieldName</a>

First included in: Parameter/SysWindowsAppApprovalsConfigFields (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentFieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentFieldType name="DocumentFieldType">DocumentFieldType</a>

First included in: Parameter/SysWindowsAppApprovalsConfigFields (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentFieldType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DocumentPlaceholderName name="DocumentPlaceholderName">DocumentPlaceholderName</a>

First included in: Parameter/SysWindowsAppApprovalsConfigFields (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentPlaceholderName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentTableId name="DocumentTableId">DocumentTableId</a>

First included in: Parameter/SysWindowsAppApprovalsConfigFields (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: Parameter/SysWindowsAppApprovalsConfigFields (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TileFieldType name="TileFieldType">TileFieldType</a>

First included in: Parameter/SysWindowsAppApprovalsConfigFields (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TileFieldType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_SysWindowsAppApprovalsConfigRelationshipId name="Relationship_SysWindowsAppApprovalsConfigRelationshipId">Relationship_SysWindowsAppApprovalsConfigRelationshipId</a>

First included in: Parameter/SysWindowsAppApprovalsConfigFields (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SysWindowsAppApprovalsConfigRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="SysWindowsAppApprovalsConfig.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/Project/Parameter/SysWindowsAppApprovalsConfig.cdm.json/SysWindowsAppApprovalsConfig</a></td><td><a href="SysWindowsAppApprovalsConfig.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
