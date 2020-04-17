---
title: WrkCtrCapRes - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# WrkCtrCapRes

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/SupplyChain/MasterPlanning/Transaction/WrkCtrCapRes.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WrkCtrCapRes/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[EndTime](#EndTime)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[IntvMth](#IntvMth)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[IntvQr](#IntvQr)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[IntvWk](#IntvWk)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[JobId](#JobId)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[JobType](#JobType)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[LoadType](#LoadType)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[Locked](#Locked)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[OprNum](#OprNum)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[OprPriority](#OprPriority)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[OrigJobRecId](#OrigJobRecId)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[PlanVersion](#PlanVersion)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[PropertyId](#PropertyId)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[RefId](#RefId)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[RefType](#RefType)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[StartTime](#StartTime)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[Timestamp](#Timestamp)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[TransDate](#TransDate)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[WrkCtrId](#WrkCtrId)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[WrkCtrLoadPct](#WrkCtrLoadPct)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[WrkCtrSec](#WrkCtrSec)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[RecordState](#RecordState)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[RecordStateSessionId](#RecordStateSessionId)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[RecordStateSessionLoginDateTime](#RecordStateSessionLoginDateTime)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[DataAreaId](#DataAreaId)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[Relationship_ProdJobRelationshipId](#Relationship_ProdJobRelationshipId)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[Relationship_ProdRouteRelationshipId](#Relationship_ProdRouteRelationshipId)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[Relationship_ProdRouteJobRelationshipId](#Relationship_ProdRouteJobRelationshipId)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[Relationship_ProductionRelationshipId](#Relationship_ProductionRelationshipId)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[Relationship_ProjTableRelationshipId](#Relationship_ProjTableRelationshipId)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[Relationship_ReqPlanVersionRelationshipId](#Relationship_ReqPlanVersionRelationshipId)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[Relationship_ReqRouteRelationshipId](#Relationship_ReqRouteRelationshipId)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[Relationship_ReqRouteJobRelationshipId](#Relationship_ReqRouteJobRelationshipId)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[Relationship_WrkCtrRelationshipId](#Relationship_WrkCtrRelationshipId)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[Relationship_WrkCtrCapResPropertyRelationshipId](#Relationship_WrkCtrCapResPropertyRelationshipId)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[Relationship_WrkCtrPropertyRelationshipId](#Relationship_WrkCtrPropertyRelationshipId)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="WrkCtrCapRes.md" target="_blank">Transaction/WrkCtrCapRes</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WrkCtrCapRes/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EndTime name="EndTime">EndTime</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.dataFormat.time**  
</details>

### <a href=#IntvMth name="IntvMth">IntvMth</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntvMth attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#IntvQr name="IntvQr">IntvQr</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntvQr attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#IntvWk name="IntvWk">IntvWk</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntvWk attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#JobId name="JobId">JobId</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobType name="JobType">JobType</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LoadType name="LoadType">LoadType</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Locked name="Locked">Locked</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Locked attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OprNum name="OprNum">OprNum</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OprNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OprPriority name="OprPriority">OprPriority</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OprPriority attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OrigJobRecId name="OrigJobRecId">OrigJobRecId</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrigJobRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PlanVersion name="PlanVersion">PlanVersion</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

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

### <a href=#PropertyId name="PropertyId">PropertyId</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PropertyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefId name="RefId">RefId</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

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

### <a href=#RefType name="RefType">RefType</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StartTime name="StartTime">StartTime</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.dataFormat.time**  
</details>

### <a href=#Timestamp name="Timestamp">Timestamp</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Timestamp attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#WrkCtrId name="WrkCtrId">WrkCtrId</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WrkCtrId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WrkCtrLoadPct name="WrkCtrLoadPct">WrkCtrLoadPct</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WrkCtrLoadPct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#WrkCtrSec name="WrkCtrSec">WrkCtrSec</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WrkCtrSec attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RecordState name="RecordState">RecordState</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecordState attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#RecordStateSessionId name="RecordStateSessionId">RecordStateSessionId</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecordStateSessionId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#RecordStateSessionLoginDateTime name="RecordStateSessionLoginDateTime">RecordStateSessionLoginDateTime</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecordStateSessionLoginDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

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

### <a href=#Relationship_ProdJobRelationshipId name="Relationship_ProdJobRelationshipId">Relationship_ProdJobRelationshipId</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProdJobRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductionControl/WorksheetLine/ProdRouteJob.md" target="_blank">/core/erp/Tables/SupplyChain/ProductionControl/WorksheetLine/ProdRouteJob.cdm.json/ProdRouteJob</a></td><td><a href="../../ProductionControl/WorksheetLine/ProdRouteJob.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProdRouteRelationshipId name="Relationship_ProdRouteRelationshipId">Relationship_ProdRouteRelationshipId</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProdRouteRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductionControl/WorksheetLine/ProdRoute.md" target="_blank">/core/erp/Tables/SupplyChain/ProductionControl/WorksheetLine/ProdRoute.cdm.json/ProdRoute</a></td><td><a href="../../ProductionControl/WorksheetLine/ProdRoute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProdRouteJobRelationshipId name="Relationship_ProdRouteJobRelationshipId">Relationship_ProdRouteJobRelationshipId</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProdRouteJobRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductionControl/WorksheetLine/ProdRouteJob.md" target="_blank">/core/erp/Tables/SupplyChain/ProductionControl/WorksheetLine/ProdRouteJob.cdm.json/ProdRouteJob</a></td><td><a href="../../ProductionControl/WorksheetLine/ProdRouteJob.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProductionRelationshipId name="Relationship_ProductionRelationshipId">Relationship_ProductionRelationshipId</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductionControl/WorksheetHeader/ProdTable.md" target="_blank">/core/erp/Tables/SupplyChain/ProductionControl/WorksheetHeader/ProdTable.cdm.json/ProdTable</a></td><td><a href="../../ProductionControl/WorksheetHeader/ProdTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjTableRelationshipId name="Relationship_ProjTableRelationshipId">Relationship_ProjTableRelationshipId</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Main/ProjTable.md" target="_blank">/core/erp/Tables/ProfessionalServices/ProjectManagementAndAccounting/Main/ProjTable.cdm.json/ProjTable</a></td><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Main/ProjTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReqPlanVersionRelationshipId name="Relationship_ReqPlanVersionRelationshipId">Relationship_ReqPlanVersionRelationshipId</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReqPlanVersionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/ReqPlanVersion.md" target="_blank">/core/erp/Tables/SupplyChain/MasterPlanning/Main/ReqPlanVersion.cdm.json/ReqPlanVersion</a></td><td><a href="../Main/ReqPlanVersion.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReqRouteRelationshipId name="Relationship_ReqRouteRelationshipId">Relationship_ReqRouteRelationshipId</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetLine/ReqRoute.md" target="_blank">/core/erp/Tables/SupplyChain/MasterPlanning/WorksheetLine/ReqRoute.cdm.json/ReqRoute</a></td><td><a href="../WorksheetLine/ReqRoute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReqRouteJobRelationshipId name="Relationship_ReqRouteJobRelationshipId">Relationship_ReqRouteJobRelationshipId</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReqRouteJobRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetLine/ReqRouteJob.md" target="_blank">/core/erp/Tables/SupplyChain/MasterPlanning/WorksheetLine/ReqRouteJob.cdm.json/ReqRouteJob</a></td><td><a href="../WorksheetLine/ReqRouteJob.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WrkCtrRelationshipId name="Relationship_WrkCtrRelationshipId">Relationship_WrkCtrRelationshipId</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WrkCtrRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/Main/WrkCtrTable.md" target="_blank">/core/erp/Tables/SupplyChain/SalesAndMarketing/Main/WrkCtrTable.cdm.json/WrkCtrTable</a></td><td><a href="../../SalesAndMarketing/Main/WrkCtrTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WrkCtrCapResPropertyRelationshipId name="Relationship_WrkCtrCapResPropertyRelationshipId">Relationship_WrkCtrCapResPropertyRelationshipId</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WrkCtrCapResPropertyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WrkCtrCapResProperty.md" target="_blank">/core/erp/Tables/SupplyChain/MasterPlanning/Transaction/WrkCtrCapResProperty.cdm.json/WrkCtrCapResProperty</a></td><td><a href="WrkCtrCapResProperty.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WrkCtrPropertyRelationshipId name="Relationship_WrkCtrPropertyRelationshipId">Relationship_WrkCtrPropertyRelationshipId</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WrkCtrPropertyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/WrkCtrProperty.md" target="_blank">/core/erp/Tables/SupplyChain/MasterPlanning/Group/WrkCtrProperty.cdm.json/WrkCtrProperty</a></td><td><a href="../Group/WrkCtrProperty.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/WrkCtrCapRes (this entity)  

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
