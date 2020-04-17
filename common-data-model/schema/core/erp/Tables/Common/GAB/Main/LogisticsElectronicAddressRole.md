---
title: LogisticsElectronicAddressRole - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# LogisticsElectronicAddressRole

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Common/GAB/Main/LogisticsElectronicAddressRole.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LogisticsElectronicAddressRole/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="LogisticsElectronicAddressRole.md" target="_blank">Main/LogisticsElectronicAddressRole</a>|
|[ElectronicAddress](#ElectronicAddress)||<a href="LogisticsElectronicAddressRole.md" target="_blank">Main/LogisticsElectronicAddressRole</a>|
|[LocationRole](#LocationRole)||<a href="LogisticsElectronicAddressRole.md" target="_blank">Main/LogisticsElectronicAddressRole</a>|
|[SkipUpdateElectronicAddressRoles](#SkipUpdateElectronicAddressRoles)||<a href="LogisticsElectronicAddressRole.md" target="_blank">Main/LogisticsElectronicAddressRole</a>|
|[Relationship_LogisticsElectronicAddress_FKRelationshipId](#Relationship_LogisticsElectronicAddress_FKRelationshipId)||<a href="LogisticsElectronicAddressRole.md" target="_blank">Main/LogisticsElectronicAddressRole</a>|
|[Relationship_LogisticsLocationRole_FKRelationshipId](#Relationship_LogisticsLocationRole_FKRelationshipId)||<a href="LogisticsElectronicAddressRole.md" target="_blank">Main/LogisticsElectronicAddressRole</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/LogisticsElectronicAddressRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LogisticsElectronicAddressRole/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ElectronicAddress name="ElectronicAddress">ElectronicAddress</a>

First included in: Main/LogisticsElectronicAddressRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicAddress attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LocationRole name="LocationRole">LocationRole</a>

First included in: Main/LogisticsElectronicAddressRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocationRole attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SkipUpdateElectronicAddressRoles name="SkipUpdateElectronicAddressRoles">SkipUpdateElectronicAddressRoles</a>

First included in: Main/LogisticsElectronicAddressRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SkipUpdateElectronicAddressRoles attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_LogisticsElectronicAddress_FKRelationshipId name="Relationship_LogisticsElectronicAddress_FKRelationshipId">Relationship_LogisticsElectronicAddress_FKRelationshipId</a>

First included in: Main/LogisticsElectronicAddressRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsElectronicAddress_FKRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="LogisticsElectronicAddress.md" target="_blank">/core/erp/Tables/Common/GAB/Main/LogisticsElectronicAddress.cdm.json/LogisticsElectronicAddress</a></td><td><a href="LogisticsElectronicAddress.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LogisticsLocationRole_FKRelationshipId name="Relationship_LogisticsLocationRole_FKRelationshipId">Relationship_LogisticsLocationRole_FKRelationshipId</a>

First included in: Main/LogisticsElectronicAddressRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsLocationRole_FKRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Reference/LogisticsLocationRole.md" target="_blank">/core/erp/Tables/Common/GAB/Reference/LogisticsLocationRole.cdm.json/LogisticsLocationRole</a></td><td><a href="../Reference/LogisticsLocationRole.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
