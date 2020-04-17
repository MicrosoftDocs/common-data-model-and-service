---
title: PMFSeqReqRouteChanges - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# PMFSeqReqRouteChanges

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/SupplyChain/MasterPlanning/WorksheetLine/PMFSeqReqRouteChanges.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PMFSeqReqRouteChanges/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PMFSeqReqRouteChanges.md" target="_blank">WorksheetLine/PMFSeqReqRouteChanges</a>|
|[ActionDays](#ActionDays)||<a href="PMFSeqReqRouteChanges.md" target="_blank">WorksheetLine/PMFSeqReqRouteChanges</a>|
|[ActionType](#ActionType)||<a href="PMFSeqReqRouteChanges.md" target="_blank">WorksheetLine/PMFSeqReqRouteChanges</a>|
|[LogText](#LogText)||<a href="PMFSeqReqRouteChanges.md" target="_blank">WorksheetLine/PMFSeqReqRouteChanges</a>|
|[LogType](#LogType)||<a href="PMFSeqReqRouteChanges.md" target="_blank">WorksheetLine/PMFSeqReqRouteChanges</a>|
|[MaxDateTime](#MaxDateTime)||<a href="PMFSeqReqRouteChanges.md" target="_blank">WorksheetLine/PMFSeqReqRouteChanges</a>|
|[MinDateTime](#MinDateTime)||<a href="PMFSeqReqRouteChanges.md" target="_blank">WorksheetLine/PMFSeqReqRouteChanges</a>|
|[NewFromDateTime](#NewFromDateTime)||<a href="PMFSeqReqRouteChanges.md" target="_blank">WorksheetLine/PMFSeqReqRouteChanges</a>|
|[NewToDateTime](#NewToDateTime)||<a href="PMFSeqReqRouteChanges.md" target="_blank">WorksheetLine/PMFSeqReqRouteChanges</a>|
|[OprNum](#OprNum)||<a href="PMFSeqReqRouteChanges.md" target="_blank">WorksheetLine/PMFSeqReqRouteChanges</a>|
|[OprPriority](#OprPriority)||<a href="PMFSeqReqRouteChanges.md" target="_blank">WorksheetLine/PMFSeqReqRouteChanges</a>|
|[OrigFromDateTime](#OrigFromDateTime)||<a href="PMFSeqReqRouteChanges.md" target="_blank">WorksheetLine/PMFSeqReqRouteChanges</a>|
|[OrigToDateTime](#OrigToDateTime)||<a href="PMFSeqReqRouteChanges.md" target="_blank">WorksheetLine/PMFSeqReqRouteChanges</a>|
|[Periods](#Periods)||<a href="PMFSeqReqRouteChanges.md" target="_blank">WorksheetLine/PMFSeqReqRouteChanges</a>|
|[PlanVersion](#PlanVersion)||<a href="PMFSeqReqRouteChanges.md" target="_blank">WorksheetLine/PMFSeqReqRouteChanges</a>|
|[Ranking](#Ranking)||<a href="PMFSeqReqRouteChanges.md" target="_blank">WorksheetLine/PMFSeqReqRouteChanges</a>|
|[RefId](#RefId)||<a href="PMFSeqReqRouteChanges.md" target="_blank">WorksheetLine/PMFSeqReqRouteChanges</a>|
|[ReqRouteRecId](#ReqRouteRecId)||<a href="PMFSeqReqRouteChanges.md" target="_blank">WorksheetLine/PMFSeqReqRouteChanges</a>|
|[SequencedOp](#SequencedOp)||<a href="PMFSeqReqRouteChanges.md" target="_blank">WorksheetLine/PMFSeqReqRouteChanges</a>|
|[DataAreaId](#DataAreaId)||<a href="PMFSeqReqRouteChanges.md" target="_blank">WorksheetLine/PMFSeqReqRouteChanges</a>|
|[Relationship_ReqPORelationshipId](#Relationship_ReqPORelationshipId)||<a href="PMFSeqReqRouteChanges.md" target="_blank">WorksheetLine/PMFSeqReqRouteChanges</a>|
|[Relationship_ReqRouteRelationshipId](#Relationship_ReqRouteRelationshipId)||<a href="PMFSeqReqRouteChanges.md" target="_blank">WorksheetLine/PMFSeqReqRouteChanges</a>|
|[Relationship_ReqTransRelationshipId](#Relationship_ReqTransRelationshipId)||<a href="PMFSeqReqRouteChanges.md" target="_blank">WorksheetLine/PMFSeqReqRouteChanges</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="PMFSeqReqRouteChanges.md" target="_blank">WorksheetLine/PMFSeqReqRouteChanges</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/PMFSeqReqRouteChanges (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PMFSeqReqRouteChanges/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ActionDays name="ActionDays">ActionDays</a>

First included in: WorksheetLine/PMFSeqReqRouteChanges (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActionDays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ActionType name="ActionType">ActionType</a>

First included in: WorksheetLine/PMFSeqReqRouteChanges (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActionType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LogText name="LogText">LogText</a>

First included in: WorksheetLine/PMFSeqReqRouteChanges (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogType name="LogType">LogType</a>

First included in: WorksheetLine/PMFSeqReqRouteChanges (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MaxDateTime name="MaxDateTime">MaxDateTime</a>

First included in: WorksheetLine/PMFSeqReqRouteChanges (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#MinDateTime name="MinDateTime">MinDateTime</a>

First included in: WorksheetLine/PMFSeqReqRouteChanges (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#NewFromDateTime name="NewFromDateTime">NewFromDateTime</a>

First included in: WorksheetLine/PMFSeqReqRouteChanges (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NewFromDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#NewToDateTime name="NewToDateTime">NewToDateTime</a>

First included in: WorksheetLine/PMFSeqReqRouteChanges (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NewToDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#OprNum name="OprNum">OprNum</a>

First included in: WorksheetLine/PMFSeqReqRouteChanges (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OprNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OprPriority name="OprPriority">OprPriority</a>

First included in: WorksheetLine/PMFSeqReqRouteChanges (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OprPriority attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OrigFromDateTime name="OrigFromDateTime">OrigFromDateTime</a>

First included in: WorksheetLine/PMFSeqReqRouteChanges (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrigFromDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#OrigToDateTime name="OrigToDateTime">OrigToDateTime</a>

First included in: WorksheetLine/PMFSeqReqRouteChanges (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrigToDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Periods name="Periods">Periods</a>

First included in: WorksheetLine/PMFSeqReqRouteChanges (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Periods attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PlanVersion name="PlanVersion">PlanVersion</a>

First included in: WorksheetLine/PMFSeqReqRouteChanges (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlanVersion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Ranking name="Ranking">Ranking</a>

First included in: WorksheetLine/PMFSeqReqRouteChanges (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Ranking attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefId name="RefId">RefId</a>

First included in: WorksheetLine/PMFSeqReqRouteChanges (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReqRouteRecId name="ReqRouteRecId">ReqRouteRecId</a>

First included in: WorksheetLine/PMFSeqReqRouteChanges (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqRouteRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SequencedOp name="SequencedOp">SequencedOp</a>

First included in: WorksheetLine/PMFSeqReqRouteChanges (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SequencedOp attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/PMFSeqReqRouteChanges (this entity)  

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

### <a href=#Relationship_ReqPORelationshipId name="Relationship_ReqPORelationshipId">Relationship_ReqPORelationshipId</a>

First included in: WorksheetLine/PMFSeqReqRouteChanges (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReqPORelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/ReqPO.md" target="_blank">/core/erp/Tables/SupplyChain/MasterPlanning/WorksheetHeader/ReqPO.cdm.json/ReqPO</a></td><td><a href="../WorksheetHeader/ReqPO.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReqRouteRelationshipId name="Relationship_ReqRouteRelationshipId">Relationship_ReqRouteRelationshipId</a>

First included in: WorksheetLine/PMFSeqReqRouteChanges (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReqRouteRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="ReqRoute.md" target="_blank">/core/erp/Tables/SupplyChain/MasterPlanning/WorksheetLine/ReqRoute.cdm.json/ReqRoute</a></td><td><a href="ReqRoute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReqTransRelationshipId name="Relationship_ReqTransRelationshipId">Relationship_ReqTransRelationshipId</a>

First included in: WorksheetLine/PMFSeqReqRouteChanges (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReqTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/ReqTrans.md" target="_blank">/core/erp/Tables/SupplyChain/MasterPlanning/Transaction/ReqTrans.cdm.json/ReqTrans</a></td><td><a href="../Transaction/ReqTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/PMFSeqReqRouteChanges (this entity)  

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
