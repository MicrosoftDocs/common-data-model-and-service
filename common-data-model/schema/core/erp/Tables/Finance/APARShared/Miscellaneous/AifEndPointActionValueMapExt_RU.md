---
title: AifEndPointActionValueMapExt_RU - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# AifEndPointActionValueMapExt_RU

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/APARShared/Miscellaneous/AifEndPointActionValueMapExt_RU.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AifEndPointActionValueMapExt_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="AifEndPointActionValueMapExt_RU.md" target="_blank">Miscellaneous/AifEndPointActionValueMapExt_RU</a>|
|[AifEndpointActionValueMap](#AifEndpointActionValueMap)||<a href="AifEndPointActionValueMapExt_RU.md" target="_blank">Miscellaneous/AifEndPointActionValueMapExt_RU</a>|
|[DataArea](#DataArea)||<a href="AifEndPointActionValueMapExt_RU.md" target="_blank">Miscellaneous/AifEndPointActionValueMapExt_RU</a>|
|[InventProfileExtCodeId](#InventProfileExtCodeId)||<a href="AifEndPointActionValueMapExt_RU.md" target="_blank">Miscellaneous/AifEndPointActionValueMapExt_RU</a>|
|[XMLMapInventProfile](#XMLMapInventProfile)||<a href="AifEndPointActionValueMapExt_RU.md" target="_blank">Miscellaneous/AifEndPointActionValueMapExt_RU</a>|
|[Relationship_AifEndpointActionValueMapRelationshipId](#Relationship_AifEndpointActionValueMapRelationshipId)||<a href="AifEndPointActionValueMapExt_RU.md" target="_blank">Miscellaneous/AifEndPointActionValueMapExt_RU</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/AifEndPointActionValueMapExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AifEndPointActionValueMapExt_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AifEndpointActionValueMap name="AifEndpointActionValueMap">AifEndpointActionValueMap</a>

First included in: Miscellaneous/AifEndPointActionValueMapExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AifEndpointActionValueMap attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataArea name="DataArea">DataArea</a>

First included in: Miscellaneous/AifEndPointActionValueMapExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventProfileExtCodeId name="InventProfileExtCodeId">InventProfileExtCodeId</a>

First included in: Miscellaneous/AifEndPointActionValueMapExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventProfileExtCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#XMLMapInventProfile name="XMLMapInventProfile">XMLMapInventProfile</a>

First included in: Miscellaneous/AifEndPointActionValueMapExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XMLMapInventProfile attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_AifEndpointActionValueMapRelationshipId name="Relationship_AifEndpointActionValueMapRelationshipId">Relationship_AifEndpointActionValueMapRelationshipId</a>

First included in: Miscellaneous/AifEndPointActionValueMapExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AifEndpointActionValueMapRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProcurementAndSourcing/Reference/AifEndpointActionValueMap.md" target="_blank">/core/erp/Tables/SupplyChain/ProcurementAndSourcing/Reference/AifEndpointActionValueMap.cdm.json/AifEndpointActionValueMap</a></td><td><a href="../../../SupplyChain/ProcurementAndSourcing/Reference/AifEndpointActionValueMap.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
