---
title: WHSClusterProfile - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# WHSClusterProfile

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/SupplyChain/Inventory/Group/WHSClusterProfile.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WHSClusterProfile/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="WHSClusterProfile.md" target="_blank">Group/WHSClusterProfile</a>|
|[BreakCluster](#BreakCluster)||<a href="WHSClusterProfile.md" target="_blank">Group/WHSClusterProfile</a>|
|[ClusterNumPositions](#ClusterNumPositions)||<a href="WHSClusterProfile.md" target="_blank">Group/WHSClusterProfile</a>|
|[ClusterPositionName](#ClusterPositionName)||<a href="WHSClusterProfile.md" target="_blank">Group/WHSClusterProfile</a>|
|[ClusterPositionsActive](#ClusterPositionsActive)||<a href="WHSClusterProfile.md" target="_blank">Group/WHSClusterProfile</a>|
|[ClusterProfileId](#ClusterProfileId)||<a href="WHSClusterProfile.md" target="_blank">Group/WHSClusterProfile</a>|
|[ClusterProfileName](#ClusterProfileName)||<a href="WHSClusterProfile.md" target="_blank">Group/WHSClusterProfile</a>|
|[ClusterSortVerification](#ClusterSortVerification)||<a href="WHSClusterProfile.md" target="_blank">Group/WHSClusterProfile</a>|
|[GenerateClusterId](#GenerateClusterId)||<a href="WHSClusterProfile.md" target="_blank">Group/WHSClusterProfile</a>|
|[ClusterType](#ClusterType)||<a href="WHSClusterProfile.md" target="_blank">Group/WHSClusterProfile</a>|
|[PutawayClusterAssignmentTiming](#PutawayClusterAssignmentTiming)||<a href="WHSClusterProfile.md" target="_blank">Group/WHSClusterProfile</a>|
|[ClusterPersistParentLP](#ClusterPersistParentLP)||<a href="WHSClusterProfile.md" target="_blank">Group/WHSClusterProfile</a>|
|[PutawayClusterAssignmentRule](#PutawayClusterAssignmentRule)||<a href="WHSClusterProfile.md" target="_blank">Group/WHSClusterProfile</a>|
|[PutawayClusterLocate](#PutawayClusterLocate)||<a href="WHSClusterProfile.md" target="_blank">Group/WHSClusterProfile</a>|
|[PutawayClusterPerUser](#PutawayClusterPerUser)||<a href="WHSClusterProfile.md" target="_blank">Group/WHSClusterProfile</a>|
|[WorkUnitBreak](#WorkUnitBreak)||<a href="WHSClusterProfile.md" target="_blank">Group/WHSClusterProfile</a>|
|[UnitRestriction](#UnitRestriction)||<a href="WHSClusterProfile.md" target="_blank">Group/WHSClusterProfile</a>|
|[PackedQueryRun](#PackedQueryRun)||<a href="WHSClusterProfile.md" target="_blank">Group/WHSClusterProfile</a>|
|[LocDirHintCode](#LocDirHintCode)||<a href="WHSClusterProfile.md" target="_blank">Group/WHSClusterProfile</a>|
|[SequenceNumber](#SequenceNumber)||<a href="WHSClusterProfile.md" target="_blank">Group/WHSClusterProfile</a>|
|[DataAreaId](#DataAreaId)||<a href="WHSClusterProfile.md" target="_blank">Group/WHSClusterProfile</a>|
|[Relationship_WHSLocDirHintRelationshipId](#Relationship_WHSLocDirHintRelationshipId)||<a href="WHSClusterProfile.md" target="_blank">Group/WHSClusterProfile</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="WHSClusterProfile.md" target="_blank">Group/WHSClusterProfile</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/WHSClusterProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WHSClusterProfile/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BreakCluster name="BreakCluster">BreakCluster</a>

First included in: Group/WHSClusterProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BreakCluster attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ClusterNumPositions name="ClusterNumPositions">ClusterNumPositions</a>

First included in: Group/WHSClusterProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClusterNumPositions attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ClusterPositionName name="ClusterPositionName">ClusterPositionName</a>

First included in: Group/WHSClusterProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClusterPositionName attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ClusterPositionsActive name="ClusterPositionsActive">ClusterPositionsActive</a>

First included in: Group/WHSClusterProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClusterPositionsActive attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ClusterProfileId name="ClusterProfileId">ClusterProfileId</a>

First included in: Group/WHSClusterProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClusterProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClusterProfileName name="ClusterProfileName">ClusterProfileName</a>

First included in: Group/WHSClusterProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClusterProfileName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClusterSortVerification name="ClusterSortVerification">ClusterSortVerification</a>

First included in: Group/WHSClusterProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClusterSortVerification attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#GenerateClusterId name="GenerateClusterId">GenerateClusterId</a>

First included in: Group/WHSClusterProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GenerateClusterId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ClusterType name="ClusterType">ClusterType</a>

First included in: Group/WHSClusterProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClusterType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PutawayClusterAssignmentTiming name="PutawayClusterAssignmentTiming">PutawayClusterAssignmentTiming</a>

First included in: Group/WHSClusterProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PutawayClusterAssignmentTiming attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ClusterPersistParentLP name="ClusterPersistParentLP">ClusterPersistParentLP</a>

First included in: Group/WHSClusterProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClusterPersistParentLP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PutawayClusterAssignmentRule name="PutawayClusterAssignmentRule">PutawayClusterAssignmentRule</a>

First included in: Group/WHSClusterProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PutawayClusterAssignmentRule attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PutawayClusterLocate name="PutawayClusterLocate">PutawayClusterLocate</a>

First included in: Group/WHSClusterProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PutawayClusterLocate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PutawayClusterPerUser name="PutawayClusterPerUser">PutawayClusterPerUser</a>

First included in: Group/WHSClusterProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PutawayClusterPerUser attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#WorkUnitBreak name="WorkUnitBreak">WorkUnitBreak</a>

First included in: Group/WHSClusterProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkUnitBreak attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UnitRestriction name="UnitRestriction">UnitRestriction</a>

First included in: Group/WHSClusterProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitRestriction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackedQueryRun name="PackedQueryRun">PackedQueryRun</a>

First included in: Group/WHSClusterProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackedQueryRun attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#LocDirHintCode name="LocDirHintCode">LocDirHintCode</a>

First included in: Group/WHSClusterProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocDirHintCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SequenceNumber name="SequenceNumber">SequenceNumber</a>

First included in: Group/WHSClusterProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SequenceNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Group/WHSClusterProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSLocDirHintRelationshipId name="Relationship_WHSLocDirHintRelationshipId">Relationship_WHSLocDirHintRelationshipId</a>

First included in: Group/WHSClusterProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSLocDirHintRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WHSLocDirHint.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Group/WHSLocDirHint.cdm.json/WHSLocDirHint</a></td><td><a href="WHSLocDirHint.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Group/WHSClusterProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
