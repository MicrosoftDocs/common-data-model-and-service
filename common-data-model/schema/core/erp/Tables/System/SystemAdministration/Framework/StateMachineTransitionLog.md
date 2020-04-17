---
title: StateMachineTransitionLog - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# StateMachineTransitionLog

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/System/SystemAdministration/Framework/StateMachineTransitionLog.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[StateMachineTransitionLog/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="StateMachineTransitionLog.md" target="_blank">Framework/StateMachineTransitionLog</a>|
|[StateMachineLogId](#StateMachineLogId)||<a href="StateMachineTransitionLog.md" target="_blank">Framework/StateMachineTransitionLog</a>|
|[EnterState](#EnterState)||<a href="StateMachineTransitionLog.md" target="_blank">Framework/StateMachineTransitionLog</a>|
|[ExitState](#ExitState)||<a href="StateMachineTransitionLog.md" target="_blank">Framework/StateMachineTransitionLog</a>|
|[DateTickCount](#DateTickCount)||<a href="StateMachineTransitionLog.md" target="_blank">Framework/StateMachineTransitionLog</a>|
|[EnterStateDescriptionLabelId](#EnterStateDescriptionLabelId)||<a href="StateMachineTransitionLog.md" target="_blank">Framework/StateMachineTransitionLog</a>|
|[EnterStateLabelId](#EnterStateLabelId)||<a href="StateMachineTransitionLog.md" target="_blank">Framework/StateMachineTransitionLog</a>|
|[EnterStateKind](#EnterStateKind)||<a href="StateMachineTransitionLog.md" target="_blank">Framework/StateMachineTransitionLog</a>|
|[ExitStateDescriptionLabelId](#ExitStateDescriptionLabelId)||<a href="StateMachineTransitionLog.md" target="_blank">Framework/StateMachineTransitionLog</a>|
|[ExitStateLabelId](#ExitStateLabelId)||<a href="StateMachineTransitionLog.md" target="_blank">Framework/StateMachineTransitionLog</a>|
|[ExitStateKind](#ExitStateKind)||<a href="StateMachineTransitionLog.md" target="_blank">Framework/StateMachineTransitionLog</a>|
|[TransitionDescriptionLabelId](#TransitionDescriptionLabelId)||<a href="StateMachineTransitionLog.md" target="_blank">Framework/StateMachineTransitionLog</a>|
|[TransitionLabelId](#TransitionLabelId)||<a href="StateMachineTransitionLog.md" target="_blank">Framework/StateMachineTransitionLog</a>|
|[Relationship_StateMachineLogRelationshipId](#Relationship_StateMachineLogRelationshipId)||<a href="StateMachineTransitionLog.md" target="_blank">Framework/StateMachineTransitionLog</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Framework/StateMachineTransitionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[StateMachineTransitionLog/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#StateMachineLogId name="StateMachineLogId">StateMachineLogId</a>

First included in: Framework/StateMachineTransitionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StateMachineLogId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EnterState name="EnterState">EnterState</a>

First included in: Framework/StateMachineTransitionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnterState attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExitState name="ExitState">ExitState</a>

First included in: Framework/StateMachineTransitionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExitState attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DateTickCount name="DateTickCount">DateTickCount</a>

First included in: Framework/StateMachineTransitionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateTickCount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EnterStateDescriptionLabelId name="EnterStateDescriptionLabelId">EnterStateDescriptionLabelId</a>

First included in: Framework/StateMachineTransitionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnterStateDescriptionLabelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnterStateLabelId name="EnterStateLabelId">EnterStateLabelId</a>

First included in: Framework/StateMachineTransitionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnterStateLabelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnterStateKind name="EnterStateKind">EnterStateKind</a>

First included in: Framework/StateMachineTransitionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnterStateKind attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExitStateDescriptionLabelId name="ExitStateDescriptionLabelId">ExitStateDescriptionLabelId</a>

First included in: Framework/StateMachineTransitionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExitStateDescriptionLabelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExitStateLabelId name="ExitStateLabelId">ExitStateLabelId</a>

First included in: Framework/StateMachineTransitionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExitStateLabelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExitStateKind name="ExitStateKind">ExitStateKind</a>

First included in: Framework/StateMachineTransitionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExitStateKind attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TransitionDescriptionLabelId name="TransitionDescriptionLabelId">TransitionDescriptionLabelId</a>

First included in: Framework/StateMachineTransitionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransitionDescriptionLabelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransitionLabelId name="TransitionLabelId">TransitionLabelId</a>

First included in: Framework/StateMachineTransitionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransitionLabelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_StateMachineLogRelationshipId name="Relationship_StateMachineLogRelationshipId">Relationship_StateMachineLogRelationshipId</a>

First included in: Framework/StateMachineTransitionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_StateMachineLogRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="StateMachineLog.md" target="_blank">/core/erp/Tables/System/SystemAdministration/Framework/StateMachineLog.cdm.json/StateMachineLog</a></td><td><a href="StateMachineLog.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
