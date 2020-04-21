---
title: DualWriteProjectConfiguration - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# DualWriteProjectConfiguration

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/DualWriteProjectConfiguration.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DualWriteProjectConfiguration/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="DualWriteProjectConfiguration.md" target="_blank">Miscellaneous/DualWriteProjectConfiguration</a>|
|[ProjectName](#ProjectName)||<a href="DualWriteProjectConfiguration.md" target="_blank">Miscellaneous/DualWriteProjectConfiguration</a>|
|[ExternalEntityName](#ExternalEntityName)||<a href="DualWriteProjectConfiguration.md" target="_blank">Miscellaneous/DualWriteProjectConfiguration</a>|
|[InternalEntityName](#InternalEntityName)||<a href="DualWriteProjectConfiguration.md" target="_blank">Miscellaneous/DualWriteProjectConfiguration</a>|
|[ExternalEnvironmentUrl](#ExternalEnvironmentUrl)||<a href="DualWriteProjectConfiguration.md" target="_blank">Miscellaneous/DualWriteProjectConfiguration</a>|
|[Status](#Status)||<a href="DualWriteProjectConfiguration.md" target="_blank">Miscellaneous/DualWriteProjectConfiguration</a>|
|[EnableBatchLookup](#EnableBatchLookup)||<a href="DualWriteProjectConfiguration.md" target="_blank">Miscellaneous/DualWriteProjectConfiguration</a>|
|[PartitionMap](#PartitionMap)||<a href="DualWriteProjectConfiguration.md" target="_blank">Miscellaneous/DualWriteProjectConfiguration</a>|
|[QueryFilterExpression](#QueryFilterExpression)||<a href="DualWriteProjectConfiguration.md" target="_blank">Miscellaneous/DualWriteProjectConfiguration</a>|
|[IntegrationKey](#IntegrationKey)||<a href="DualWriteProjectConfiguration.md" target="_blank">Miscellaneous/DualWriteProjectConfiguration</a>|
|[IsDelete](#IsDelete)||<a href="DualWriteProjectConfiguration.md" target="_blank">Miscellaneous/DualWriteProjectConfiguration</a>|
|[IsDebugMode](#IsDebugMode)||<a href="DualWriteProjectConfiguration.md" target="_blank">Miscellaneous/DualWriteProjectConfiguration</a>|
|[EnableCache](#EnableCache)||<a href="DualWriteProjectConfiguration.md" target="_blank">Miscellaneous/DualWriteProjectConfiguration</a>|
|[DisablePerfEnhancements](#DisablePerfEnhancements)||<a href="DualWriteProjectConfiguration.md" target="_blank">Miscellaneous/DualWriteProjectConfiguration</a>|
|[EnableFailureReconciliation](#EnableFailureReconciliation)||<a href="DualWriteProjectConfiguration.md" target="_blank">Miscellaneous/DualWriteProjectConfiguration</a>|
|[Relationship_DualWriteProjectFieldConfigurationRelationshipId](#Relationship_DualWriteProjectFieldConfigurationRelationshipId)||<a href="DualWriteProjectConfiguration.md" target="_blank">Miscellaneous/DualWriteProjectConfiguration</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/DualWriteProjectConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DualWriteProjectConfiguration/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProjectName name="ProjectName">ProjectName</a>

First included in: Miscellaneous/DualWriteProjectConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternalEntityName name="ExternalEntityName">ExternalEntityName</a>

First included in: Miscellaneous/DualWriteProjectConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalEntityName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InternalEntityName name="InternalEntityName">InternalEntityName</a>

First included in: Miscellaneous/DualWriteProjectConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InternalEntityName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternalEnvironmentUrl name="ExternalEnvironmentUrl">ExternalEnvironmentUrl</a>

First included in: Miscellaneous/DualWriteProjectConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalEnvironmentUrl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Miscellaneous/DualWriteProjectConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EnableBatchLookup name="EnableBatchLookup">EnableBatchLookup</a>

First included in: Miscellaneous/DualWriteProjectConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableBatchLookup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PartitionMap name="PartitionMap">PartitionMap</a>

First included in: Miscellaneous/DualWriteProjectConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartitionMap attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QueryFilterExpression name="QueryFilterExpression">QueryFilterExpression</a>

First included in: Miscellaneous/DualWriteProjectConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QueryFilterExpression attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntegrationKey name="IntegrationKey">IntegrationKey</a>

First included in: Miscellaneous/DualWriteProjectConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntegrationKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDelete name="IsDelete">IsDelete</a>

First included in: Miscellaneous/DualWriteProjectConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDelete attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsDebugMode name="IsDebugMode">IsDebugMode</a>

First included in: Miscellaneous/DualWriteProjectConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDebugMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EnableCache name="EnableCache">EnableCache</a>

First included in: Miscellaneous/DualWriteProjectConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableCache attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DisablePerfEnhancements name="DisablePerfEnhancements">DisablePerfEnhancements</a>

First included in: Miscellaneous/DualWriteProjectConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisablePerfEnhancements attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EnableFailureReconciliation name="EnableFailureReconciliation">EnableFailureReconciliation</a>

First included in: Miscellaneous/DualWriteProjectConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableFailureReconciliation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_DualWriteProjectFieldConfigurationRelationshipId name="Relationship_DualWriteProjectFieldConfigurationRelationshipId">Relationship_DualWriteProjectFieldConfigurationRelationshipId</a>

First included in: Miscellaneous/DualWriteProjectConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DualWriteProjectFieldConfigurationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="DualWriteProjectFieldConfiguration.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/DualWriteProjectFieldConfiguration.cdm.json/DualWriteProjectFieldConfiguration</a></td><td><a href="DualWriteProjectFieldConfiguration.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
