---
title: ReqIntercompanyPlanningGroupMemberEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Intercompany planning group members

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/MasterPlanning/ReqIntercompanyPlanningGroupMemberEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Intercompany planning group members</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[WillIntercompanyPlanAutomaticallyBeCopiedToDynamicPlan](#WillIntercompanyPlanAutomaticallyBeCopiedToDynamicPlan)||<a href="ReqIntercompanyPlanningGroupMemberEntity.md" target="_blank">MasterPlanning/ReqIntercompanyPlanningGroupMemberEntity</a>|
|[WillIntercompanyPlanAutomaticallyBeCopiedToStaticPlan](#WillIntercompanyPlanAutomaticallyBeCopiedToStaticPlan)||<a href="ReqIntercompanyPlanningGroupMemberEntity.md" target="_blank">MasterPlanning/ReqIntercompanyPlanningGroupMemberEntity</a>|
|[MasterPlanId](#MasterPlanId)||<a href="ReqIntercompanyPlanningGroupMemberEntity.md" target="_blank">MasterPlanning/ReqIntercompanyPlanningGroupMemberEntity</a>|
|[IntercompanyPlanningSequence](#IntercompanyPlanningSequence)||<a href="ReqIntercompanyPlanningGroupMemberEntity.md" target="_blank">MasterPlanning/ReqIntercompanyPlanningGroupMemberEntity</a>|
|[IntercompanyPlanningGroupName](#IntercompanyPlanningGroupName)||<a href="ReqIntercompanyPlanningGroupMemberEntity.md" target="_blank">MasterPlanning/ReqIntercompanyPlanningGroupMemberEntity</a>|
|[LegalEntityId](#LegalEntityId)||<a href="ReqIntercompanyPlanningGroupMemberEntity.md" target="_blank">MasterPlanning/ReqIntercompanyPlanningGroupMemberEntity</a>|
|[IntercompanyPlanDataAreaId](#IntercompanyPlanDataAreaId)||<a href="ReqIntercompanyPlanningGroupMemberEntity.md" target="_blank">MasterPlanning/ReqIntercompanyPlanningGroupMemberEntity</a>|
|[BackingTable_ReqIntercompanyPlanningGroupMemberRelationshipId](#BackingTable_ReqIntercompanyPlanningGroupMemberRelationshipId)||<a href="ReqIntercompanyPlanningGroupMemberEntity.md" target="_blank">MasterPlanning/ReqIntercompanyPlanningGroupMemberEntity</a>|

### <a href=#WillIntercompanyPlanAutomaticallyBeCopiedToDynamicPlan name="WillIntercompanyPlanAutomaticallyBeCopiedToDynamicPlan">WillIntercompanyPlanAutomaticallyBeCopiedToDynamicPlan</a>

First included in: MasterPlanning/ReqIntercompanyPlanningGroupMemberEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillIntercompanyPlanAutomaticallyBeCopiedToDynamicPlan attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillIntercompanyPlanAutomaticallyBeCopiedToStaticPlan name="WillIntercompanyPlanAutomaticallyBeCopiedToStaticPlan">WillIntercompanyPlanAutomaticallyBeCopiedToStaticPlan</a>

First included in: MasterPlanning/ReqIntercompanyPlanningGroupMemberEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillIntercompanyPlanAutomaticallyBeCopiedToStaticPlan attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MasterPlanId name="MasterPlanId">MasterPlanId</a>

First included in: MasterPlanning/ReqIntercompanyPlanningGroupMemberEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MasterPlanId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntercompanyPlanningSequence name="IntercompanyPlanningSequence">IntercompanyPlanningSequence</a>

First included in: MasterPlanning/ReqIntercompanyPlanningGroupMemberEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntercompanyPlanningSequence attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntercompanyPlanningGroupName name="IntercompanyPlanningGroupName">IntercompanyPlanningGroupName</a>

First included in: MasterPlanning/ReqIntercompanyPlanningGroupMemberEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntercompanyPlanningGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntityId name="LegalEntityId">LegalEntityId</a>

First included in: MasterPlanning/ReqIntercompanyPlanningGroupMemberEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntercompanyPlanDataAreaId name="IntercompanyPlanDataAreaId">IntercompanyPlanDataAreaId</a>

First included in: MasterPlanning/ReqIntercompanyPlanningGroupMemberEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntercompanyPlanDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_ReqIntercompanyPlanningGroupMemberRelationshipId name="BackingTable_ReqIntercompanyPlanningGroupMemberRelationshipId">BackingTable_ReqIntercompanyPlanningGroupMemberRelationshipId</a>

First included in: MasterPlanning/ReqIntercompanyPlanningGroupMemberEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ReqIntercompanyPlanningGroupMemberRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/MasterPlanning/Main/ReqIntercompanyPlanningGroupMember.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Main/ReqIntercompanyPlanningGroupMember.cdm.json/ReqIntercompanyPlanningGroupMember</a></td><td><a href="../../../Tables/SupplyChain/MasterPlanning/Main/ReqIntercompanyPlanningGroupMember.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
