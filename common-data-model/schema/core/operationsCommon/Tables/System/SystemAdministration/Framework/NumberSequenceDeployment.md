---
title: NumberSequenceDeployment - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# NumberSequenceDeployment

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Framework/NumberSequenceDeployment.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[NumberSequenceDeployment/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="NumberSequenceDeployment.md" target="_blank">Framework/NumberSequenceDeployment</a>|
|[NumberSequence](#NumberSequence)||<a href="NumberSequenceDeployment.md" target="_blank">Framework/NumberSequenceDeployment</a>|
|[Deployment](#Deployment)||<a href="NumberSequenceDeployment.md" target="_blank">Framework/NumberSequenceDeployment</a>|
|[Lowest](#Lowest)||<a href="NumberSequenceDeployment.md" target="_blank">Framework/NumberSequenceDeployment</a>|
|[Highest](#Highest)||<a href="NumberSequenceDeployment.md" target="_blank">Framework/NumberSequenceDeployment</a>|
|[NextRec](#NextRec)||<a href="NumberSequenceDeployment.md" target="_blank">Framework/NumberSequenceDeployment</a>|
|[InUse](#InUse)||<a href="NumberSequenceDeployment.md" target="_blank">Framework/NumberSequenceDeployment</a>|
|[Active](#Active)||<a href="NumberSequenceDeployment.md" target="_blank">Framework/NumberSequenceDeployment</a>|
|[IsNumberSequenceContinuous](#IsNumberSequenceContinuous)||<a href="NumberSequenceDeployment.md" target="_blank">Framework/NumberSequenceDeployment</a>|
|[LatestCleanDateTime](#LatestCleanDateTime)||<a href="NumberSequenceDeployment.md" target="_blank">Framework/NumberSequenceDeployment</a>|
|[Relationship_NumberSequenceTableRelationshipId](#Relationship_NumberSequenceTableRelationshipId)||<a href="NumberSequenceDeployment.md" target="_blank">Framework/NumberSequenceDeployment</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Framework/NumberSequenceDeployment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[NumberSequenceDeployment/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#NumberSequence name="NumberSequence">NumberSequence</a>

First included in: Framework/NumberSequenceDeployment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Deployment name="Deployment">Deployment</a>

First included in: Framework/NumberSequenceDeployment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Deployment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Lowest name="Lowest">Lowest</a>

First included in: Framework/NumberSequenceDeployment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Lowest attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Highest name="Highest">Highest</a>

First included in: Framework/NumberSequenceDeployment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Highest attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#NextRec name="NextRec">NextRec</a>

First included in: Framework/NumberSequenceDeployment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NextRec attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InUse name="InUse">InUse</a>

First included in: Framework/NumberSequenceDeployment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InUse attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#Active name="Active">Active</a>

First included in: Framework/NumberSequenceDeployment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Active attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsNumberSequenceContinuous name="IsNumberSequenceContinuous">IsNumberSequenceContinuous</a>

First included in: Framework/NumberSequenceDeployment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsNumberSequenceContinuous attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LatestCleanDateTime name="LatestCleanDateTime">LatestCleanDateTime</a>

First included in: Framework/NumberSequenceDeployment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LatestCleanDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#Relationship_NumberSequenceTableRelationshipId name="Relationship_NumberSequenceTableRelationshipId">Relationship_NumberSequenceTableRelationshipId</a>

First included in: Framework/NumberSequenceDeployment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_NumberSequenceTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="NumberSequenceTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Framework/NumberSequenceTable.cdm.json/NumberSequenceTable</a></td><td><a href="NumberSequenceTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
