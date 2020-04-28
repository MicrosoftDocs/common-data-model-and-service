---
title: PMFSeqWrkCtrCapRes - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Capacity reservations

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Transaction/PMFSeqWrkCtrCapRes.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PMFSeqWrkCtrCapRes/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Capacity reservations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[EndTime](#EndTime)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[IntvMth](#IntvMth)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[IntvQr](#IntvQr)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[IntvWk](#IntvWk)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[JobId](#JobId)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[JobType](#JobType)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[LoadType](#LoadType)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[Locked](#Locked)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[OprNum](#OprNum)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[OprPriority](#OprPriority)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[OrigCapResRefRecId](#OrigCapResRefRecId)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[OrigJobRecId](#OrigJobRecId)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[PlanVersion](#PlanVersion)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[PropertyId](#PropertyId)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[RefId](#RefId)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[RefType](#RefType)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[StartTime](#StartTime)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[Timestamp](#Timestamp)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[TransDate](#TransDate)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[WrkCtrId](#WrkCtrId)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[WrkCtrLoadPct](#WrkCtrLoadPct)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[WrkCtrSec](#WrkCtrSec)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[DataAreaId](#DataAreaId)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[Relationship_PMFSeqReqRouteChangesRelationshipId](#Relationship_PMFSeqReqRouteChangesRelationshipId)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[Relationship_ProdJobRelationshipId](#Relationship_ProdJobRelationshipId)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[Relationship_ProdRouteRelationshipId](#Relationship_ProdRouteRelationshipId)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[Relationship_ProductionRelationshipId](#Relationship_ProductionRelationshipId)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[Relationship_ProjTableRelationshipId](#Relationship_ProjTableRelationshipId)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[Relationship_ReqPlanVersionRelationshipId](#Relationship_ReqPlanVersionRelationshipId)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[Relationship_ReqRouteRelationshipId](#Relationship_ReqRouteRelationshipId)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[Relationship_ReqRouteJobRelationshipId](#Relationship_ReqRouteJobRelationshipId)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[Relationship_WrkCtrRelationshipId](#Relationship_WrkCtrRelationshipId)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[Relationship_WrkCtrCapResRelationshipId](#Relationship_WrkCtrCapResRelationshipId)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[Relationship_WrkCtrCapResOrigRelationshipId](#Relationship_WrkCtrCapResOrigRelationshipId)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[Relationship_WrkCtrPropertyRelationshipId](#Relationship_WrkCtrPropertyRelationshipId)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="PMFSeqWrkCtrCapRes.md" target="_blank">Transaction/PMFSeqWrkCtrCapRes</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PMFSeqWrkCtrCapRes/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EndTime name="EndTime">EndTime</a>

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

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

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

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

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

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

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

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

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

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

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Job type</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Job type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#LoadType name="LoadType">LoadType</a>

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Locked name="Locked">Locked</a>

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Locked attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OprNum name="OprNum">OprNum</a>

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OprNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OprPriority name="OprPriority">OprPriority</a>

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OprPriority attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OrigCapResRefRecId name="OrigCapResRefRecId">OrigCapResRefRecId</a>

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrigCapResRefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OrigJobRecId name="OrigJobRecId">OrigJobRecId</a>

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

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

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

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

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

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

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

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

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StartTime name="StartTime">StartTime</a>

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

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

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

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

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date</td></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#WrkCtrId name="WrkCtrId">WrkCtrId</a>

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

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

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

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

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

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

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

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

### <a href=#Relationship_PMFSeqReqRouteChangesRelationshipId name="Relationship_PMFSeqReqRouteChangesRelationshipId">Relationship_PMFSeqReqRouteChangesRelationshipId</a>

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PMFSeqReqRouteChangesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetLine/PMFSeqReqRouteChanges.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/WorksheetLine/PMFSeqReqRouteChanges.cdm.json/PMFSeqReqRouteChanges</a></td><td><a href="../WorksheetLine/PMFSeqReqRouteChanges.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProdJobRelationshipId name="Relationship_ProdJobRelationshipId">Relationship_ProdJobRelationshipId</a>

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductionControl/WorksheetLine/ProdRouteJob.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/WorksheetLine/ProdRouteJob.cdm.json/ProdRouteJob</a></td><td><a href="../../ProductionControl/WorksheetLine/ProdRouteJob.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProdRouteRelationshipId name="Relationship_ProdRouteRelationshipId">Relationship_ProdRouteRelationshipId</a>

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductionControl/WorksheetLine/ProdRoute.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/WorksheetLine/ProdRoute.cdm.json/ProdRoute</a></td><td><a href="../../ProductionControl/WorksheetLine/ProdRoute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProductionRelationshipId name="Relationship_ProductionRelationshipId">Relationship_ProductionRelationshipId</a>

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductionControl/WorksheetHeader/ProdTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/WorksheetHeader/ProdTable.cdm.json/ProdTable</a></td><td><a href="../../ProductionControl/WorksheetHeader/ProdTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjTableRelationshipId name="Relationship_ProjTableRelationshipId">Relationship_ProjTableRelationshipId</a>

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Main/ProjTable.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Main/ProjTable.cdm.json/ProjTable</a></td><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Main/ProjTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReqPlanVersionRelationshipId name="Relationship_ReqPlanVersionRelationshipId">Relationship_ReqPlanVersionRelationshipId</a>

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/ReqPlanVersion.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Main/ReqPlanVersion.cdm.json/ReqPlanVersion</a></td><td><a href="../Main/ReqPlanVersion.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReqRouteRelationshipId name="Relationship_ReqRouteRelationshipId">Relationship_ReqRouteRelationshipId</a>

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetLine/ReqRoute.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/WorksheetLine/ReqRoute.cdm.json/ReqRoute</a></td><td><a href="../WorksheetLine/ReqRoute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReqRouteJobRelationshipId name="Relationship_ReqRouteJobRelationshipId">Relationship_ReqRouteJobRelationshipId</a>

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetLine/ReqRouteJob.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/WorksheetLine/ReqRouteJob.cdm.json/ReqRouteJob</a></td><td><a href="../WorksheetLine/ReqRouteJob.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WrkCtrRelationshipId name="Relationship_WrkCtrRelationshipId">Relationship_WrkCtrRelationshipId</a>

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/Main/WrkCtrTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/WrkCtrTable.cdm.json/WrkCtrTable</a></td><td><a href="../../SalesAndMarketing/Main/WrkCtrTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WrkCtrCapResRelationshipId name="Relationship_WrkCtrCapResRelationshipId">Relationship_WrkCtrCapResRelationshipId</a>

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WrkCtrCapResRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WrkCtrCapRes.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Transaction/WrkCtrCapRes.cdm.json/WrkCtrCapRes</a></td><td><a href="WrkCtrCapRes.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WrkCtrCapResOrigRelationshipId name="Relationship_WrkCtrCapResOrigRelationshipId">Relationship_WrkCtrCapResOrigRelationshipId</a>

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WrkCtrCapResOrigRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WrkCtrCapRes.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Transaction/WrkCtrCapRes.cdm.json/WrkCtrCapRes</a></td><td><a href="WrkCtrCapRes.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WrkCtrPropertyRelationshipId name="Relationship_WrkCtrPropertyRelationshipId">Relationship_WrkCtrPropertyRelationshipId</a>

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/WrkCtrProperty.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Group/WrkCtrProperty.cdm.json/WrkCtrProperty</a></td><td><a href="../Group/WrkCtrProperty.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/PMFSeqWrkCtrCapRes (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
