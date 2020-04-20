---
title: SysIndexRebuildActivityDetails - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# SysIndexRebuildActivityDetails

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/SysIndexRebuildActivityDetails.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysIndexRebuildActivityDetails/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="SysIndexRebuildActivityDetails.md" target="_blank">Miscellaneous/SysIndexRebuildActivityDetails</a>|
|[SysIndexRecId](#SysIndexRecId)||<a href="SysIndexRebuildActivityDetails.md" target="_blank">Miscellaneous/SysIndexRebuildActivityDetails</a>|
|[ActivityStatus](#ActivityStatus)||<a href="SysIndexRebuildActivityDetails.md" target="_blank">Miscellaneous/SysIndexRebuildActivityDetails</a>|
|[ActivityId](#ActivityId)||<a href="SysIndexRebuildActivityDetails.md" target="_blank">Miscellaneous/SysIndexRebuildActivityDetails</a>|
|[FragmentationBefore](#FragmentationBefore)||<a href="SysIndexRebuildActivityDetails.md" target="_blank">Miscellaneous/SysIndexRebuildActivityDetails</a>|
|[FragmentationAfter](#FragmentationAfter)||<a href="SysIndexRebuildActivityDetails.md" target="_blank">Miscellaneous/SysIndexRebuildActivityDetails</a>|
|[PageCountBefore](#PageCountBefore)||<a href="SysIndexRebuildActivityDetails.md" target="_blank">Miscellaneous/SysIndexRebuildActivityDetails</a>|
|[PageCountAfter](#PageCountAfter)||<a href="SysIndexRebuildActivityDetails.md" target="_blank">Miscellaneous/SysIndexRebuildActivityDetails</a>|
|[PageSpaceUsedBefore](#PageSpaceUsedBefore)||<a href="SysIndexRebuildActivityDetails.md" target="_blank">Miscellaneous/SysIndexRebuildActivityDetails</a>|
|[PageSpaceUsedAfter](#PageSpaceUsedAfter)||<a href="SysIndexRebuildActivityDetails.md" target="_blank">Miscellaneous/SysIndexRebuildActivityDetails</a>|
|[Relationship_IndexDetailsRelationshipId](#Relationship_IndexDetailsRelationshipId)||<a href="SysIndexRebuildActivityDetails.md" target="_blank">Miscellaneous/SysIndexRebuildActivityDetails</a>|
|[Relationship_DefragmentationRunDateRelationshipId](#Relationship_DefragmentationRunDateRelationshipId)||<a href="SysIndexRebuildActivityDetails.md" target="_blank">Miscellaneous/SysIndexRebuildActivityDetails</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/SysIndexRebuildActivityDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysIndexRebuildActivityDetails/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SysIndexRecId name="SysIndexRecId">SysIndexRecId</a>

First included in: Miscellaneous/SysIndexRebuildActivityDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SysIndexRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ActivityStatus name="ActivityStatus">ActivityStatus</a>

First included in: Miscellaneous/SysIndexRebuildActivityDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ActivityId name="ActivityId">ActivityId</a>

First included in: Miscellaneous/SysIndexRebuildActivityDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FragmentationBefore name="FragmentationBefore">FragmentationBefore</a>

First included in: Miscellaneous/SysIndexRebuildActivityDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FragmentationBefore attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FragmentationAfter name="FragmentationAfter">FragmentationAfter</a>

First included in: Miscellaneous/SysIndexRebuildActivityDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FragmentationAfter attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PageCountBefore name="PageCountBefore">PageCountBefore</a>

First included in: Miscellaneous/SysIndexRebuildActivityDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PageCountBefore attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PageCountAfter name="PageCountAfter">PageCountAfter</a>

First included in: Miscellaneous/SysIndexRebuildActivityDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PageCountAfter attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PageSpaceUsedBefore name="PageSpaceUsedBefore">PageSpaceUsedBefore</a>

First included in: Miscellaneous/SysIndexRebuildActivityDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PageSpaceUsedBefore attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PageSpaceUsedAfter name="PageSpaceUsedAfter">PageSpaceUsedAfter</a>

First included in: Miscellaneous/SysIndexRebuildActivityDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PageSpaceUsedAfter attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_IndexDetailsRelationshipId name="Relationship_IndexDetailsRelationshipId">Relationship_IndexDetailsRelationshipId</a>

First included in: Miscellaneous/SysIndexRebuildActivityDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IndexDetailsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="SysIndexDetails.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/SysIndexDetails.cdm.json/SysIndexDetails</a></td><td><a href="SysIndexDetails.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefragmentationRunDateRelationshipId name="Relationship_DefragmentationRunDateRelationshipId">Relationship_DefragmentationRunDateRelationshipId</a>

First included in: Miscellaneous/SysIndexRebuildActivityDetails (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefragmentationRunDateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="SysIndexRebuildActivityLog.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/SysIndexRebuildActivityLog.cdm.json/SysIndexRebuildActivityLog</a></td><td><a href="SysIndexRebuildActivityLog.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
