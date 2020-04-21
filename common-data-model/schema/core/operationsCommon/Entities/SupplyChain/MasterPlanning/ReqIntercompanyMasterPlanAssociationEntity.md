---
title: ReqIntercompanyMasterPlanAssociationEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# ReqIntercompanyMasterPlanAssociationEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/MasterPlanning/ReqIntercompanyMasterPlanAssociationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DownstreamCompanyId](#DownstreamCompanyId)||<a href="ReqIntercompanyMasterPlanAssociationEntity.md" target="_blank">MasterPlanning/ReqIntercompanyMasterPlanAssociationEntity</a>|
|[DownstreamMasterPlanId](#DownstreamMasterPlanId)||<a href="ReqIntercompanyMasterPlanAssociationEntity.md" target="_blank">MasterPlanning/ReqIntercompanyMasterPlanAssociationEntity</a>|
|[UpstreamCompanyId](#UpstreamCompanyId)||<a href="ReqIntercompanyMasterPlanAssociationEntity.md" target="_blank">MasterPlanning/ReqIntercompanyMasterPlanAssociationEntity</a>|
|[UpstreamMasterPlanId](#UpstreamMasterPlanId)||<a href="ReqIntercompanyMasterPlanAssociationEntity.md" target="_blank">MasterPlanning/ReqIntercompanyMasterPlanAssociationEntity</a>|
|[BackingTable_ReqIntercompanyMasterPlanMappingRelationshipId](#BackingTable_ReqIntercompanyMasterPlanMappingRelationshipId)||<a href="ReqIntercompanyMasterPlanAssociationEntity.md" target="_blank">MasterPlanning/ReqIntercompanyMasterPlanAssociationEntity</a>|

### <a href=#DownstreamCompanyId name="DownstreamCompanyId">DownstreamCompanyId</a>

First included in: MasterPlanning/ReqIntercompanyMasterPlanAssociationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DownstreamCompanyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DownstreamMasterPlanId name="DownstreamMasterPlanId">DownstreamMasterPlanId</a>

First included in: MasterPlanning/ReqIntercompanyMasterPlanAssociationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DownstreamMasterPlanId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UpstreamCompanyId name="UpstreamCompanyId">UpstreamCompanyId</a>

First included in: MasterPlanning/ReqIntercompanyMasterPlanAssociationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpstreamCompanyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UpstreamMasterPlanId name="UpstreamMasterPlanId">UpstreamMasterPlanId</a>

First included in: MasterPlanning/ReqIntercompanyMasterPlanAssociationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpstreamMasterPlanId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_ReqIntercompanyMasterPlanMappingRelationshipId name="BackingTable_ReqIntercompanyMasterPlanMappingRelationshipId">BackingTable_ReqIntercompanyMasterPlanMappingRelationshipId</a>

First included in: MasterPlanning/ReqIntercompanyMasterPlanAssociationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ReqIntercompanyMasterPlanMappingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/MasterPlanning/Main/ReqIntercompanyMasterPlanMapping.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Main/ReqIntercompanyMasterPlanMapping.cdm.json/ReqIntercompanyMasterPlanMapping</a></td><td><a href="../../../Tables/SupplyChain/MasterPlanning/Main/ReqIntercompanyMasterPlanMapping.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
