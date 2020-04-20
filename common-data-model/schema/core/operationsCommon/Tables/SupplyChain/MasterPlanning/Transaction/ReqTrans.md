---
title: ReqTrans - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# ReqTrans

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Transaction/ReqTrans.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReqTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[ActionDate](#ActionDate)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[ActionDays](#ActionDays)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[ActionMarked](#ActionMarked)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[ActionQtyAdd](#ActionQtyAdd)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[ActionType](#ActionType)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[BOMRefRecId](#BOMRefRecId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[BOMType](#BOMType)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[CovInventDimId](#CovInventDimId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[CovQty](#CovQty)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[CustAccountId](#CustAccountId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[CustGroupId](#CustGroupId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Direction](#Direction)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[FuturesDate](#FuturesDate)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[FuturesDays](#FuturesDays)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[FuturesMarked](#FuturesMarked)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[FuturesTime](#FuturesTime)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[IntercompanyPlannedOrder](#IntercompanyPlannedOrder)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[InventTransOrigin](#InventTransOrigin)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[IsDelayed](#IsDelayed)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[IsDerivedDirectly](#IsDerivedDirectly)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[IsForecastPurch](#IsForecastPurch)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[ItemBomId](#ItemBomId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[ItemId](#ItemId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[ItemRouteId](#ItemRouteId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Keep](#Keep)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[LastPlanRecId](#LastPlanRecId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Level](#Level)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[MarkingRefInventTransOrigin](#MarkingRefInventTransOrigin)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[MCRPriceTimeFence](#MCRPriceTimeFence)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[OpenStatus](#OpenStatus)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[OprNum](#OprNum)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[OriginalQuantity](#OriginalQuantity)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[PdsExpiryDate](#PdsExpiryDate)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[PdsSellableDays](#PdsSellableDays)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[PlanVersion](#PlanVersion)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[PmfActionQtyAdd](#PmfActionQtyAdd)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[PmfCoByRefRecId](#PmfCoByRefRecId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[PmfPlanGroupId](#PmfPlanGroupId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[PmfPlanGroupPrimaryIssue](#PmfPlanGroupPrimaryIssue)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[PmfPlanGroupPriority](#PmfPlanGroupPriority)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[PmfPlanningItemId](#PmfPlanningItemId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[PmfPlanPriorityCurrent](#PmfPlanPriorityCurrent)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Priority](#Priority)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Qty](#Qty)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[RefId](#RefId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[RefType](#RefType)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[ReqDate](#ReqDate)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[ReqDateDlvOrig](#ReqDateDlvOrig)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[ReqProcessId](#ReqProcessId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[ReqTime](#ReqTime)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[RequisitionLine](#RequisitionLine)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[SupplyDemandSubClassification](#SupplyDemandSubClassification)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[IsForcedItemBomId](#IsForcedItemBomId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[IsForcedItemRouteId](#IsForcedItemRouteId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[FuturesCalculated](#FuturesCalculated)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[DataAreaId](#DataAreaId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Relationship_BOMRelationshipId](#Relationship_BOMRelationshipId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Relationship_BOMLineRelationshipId](#Relationship_BOMLineRelationshipId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Relationship_BOMTableRelationshipId](#Relationship_BOMTableRelationshipId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Relationship_CustGroupRelationshipId](#Relationship_CustGroupRelationshipId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Relationship_CustTableRelationshipId](#Relationship_CustTableRelationshipId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Relationship_InventDimRelationshipId](#Relationship_InventDimRelationshipId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Relationship_InventOnhandRelationshipId](#Relationship_InventOnhandRelationshipId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Relationship_InventTransOriginRelationshipId](#Relationship_InventTransOriginRelationshipId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Relationship_ItemtableRelationshipId](#Relationship_ItemtableRelationshipId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Relationship_MarkingRefInventTransOriginRelationshipId](#Relationship_MarkingRefInventTransOriginRelationshipId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Relationship_PmfFormulaCoByRelationshipId](#Relationship_PmfFormulaCoByRelationshipId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Relationship_PmfFormulaLineRelationshipId](#Relationship_PmfFormulaLineRelationshipId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Relationship_PmfPlanGroupRelationshipId](#Relationship_PmfPlanGroupRelationshipId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Relationship_PmfPlanningItemRelationshipId](#Relationship_PmfPlanningItemRelationshipId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Relationship_PmfProdCoByRelationshipId](#Relationship_PmfProdCoByRelationshipId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Relationship_ProductionRelationshipId](#Relationship_ProductionRelationshipId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Relationship_ProductionLineRelationshipId](#Relationship_ProductionLineRelationshipId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Relationship_PurchRelationshipId](#Relationship_PurchRelationshipId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Relationship_ReqPlanVersionRelationshipId](#Relationship_ReqPlanVersionRelationshipId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Relationship_ReqPlanVersionLastPlanRelationshipId](#Relationship_ReqPlanVersionLastPlanRelationshipId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Relationship_ReqPoRelationshipId](#Relationship_ReqPoRelationshipId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Relationship_ReqPOPlannedIntercompanyDemandRelationshipId](#Relationship_ReqPOPlannedIntercompanyDemandRelationshipId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Relationship_RequisitionLineRelationshipId](#Relationship_RequisitionLineRelationshipId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Relationship_RouteTableRelationshipId](#Relationship_RouteTableRelationshipId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Relationship_SalesOrderRelationshipId](#Relationship_SalesOrderRelationshipId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="ReqTrans.md" target="_blank">Transaction/ReqTrans</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReqTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ActionDate name="ActionDate">ActionDate</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActionDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#ActionDays name="ActionDays">ActionDays</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActionDays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#ActionMarked name="ActionMarked">ActionMarked</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActionMarked attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#ActionQtyAdd name="ActionQtyAdd">ActionQtyAdd</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActionQtyAdd attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ActionType name="ActionType">ActionType</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActionType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#BOMRefRecId name="BOMRefRecId">BOMRefRecId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOMRefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BOMType name="BOMType">BOMType</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOMType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#CovInventDimId name="CovInventDimId">CovInventDimId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CovInventDimId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CovQty name="CovQty">CovQty</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CovQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CustAccountId name="CustAccountId">CustAccountId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustGroupId name="CustGroupId">CustGroupId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Direction name="Direction">Direction</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Direction attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#FuturesDate name="FuturesDate">FuturesDate</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FuturesDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#FuturesDays name="FuturesDays">FuturesDays</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FuturesDays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#FuturesMarked name="FuturesMarked">FuturesMarked</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FuturesMarked attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#FuturesTime name="FuturesTime">FuturesTime</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FuturesTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.readOnly**  
**is.dataFormat.time**  
</details>

### <a href=#IntercompanyPlannedOrder name="IntercompanyPlannedOrder">IntercompanyPlannedOrder</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntercompanyPlannedOrder attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InventTransOrigin name="InventTransOrigin">InventTransOrigin</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTransOrigin attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IsDelayed name="IsDelayed">IsDelayed</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDelayed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsDerivedDirectly name="IsDerivedDirectly">IsDerivedDirectly</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDerivedDirectly attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#IsForecastPurch name="IsForecastPurch">IsForecastPurch</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsForecastPurch attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#ItemBomId name="ItemBomId">ItemBomId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemBomId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemRouteId name="ItemRouteId">ItemRouteId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemRouteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Keep name="Keep">Keep</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Keep attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#LastPlanRecId name="LastPlanRecId">LastPlanRecId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastPlanRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Level name="Level">Level</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Level attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#MarkingRefInventTransOrigin name="MarkingRefInventTransOrigin">MarkingRefInventTransOrigin</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarkingRefInventTransOrigin attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MCRPriceTimeFence name="MCRPriceTimeFence">MCRPriceTimeFence</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRPriceTimeFence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OpenStatus name="OpenStatus">OpenStatus</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OpenStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#OprNum name="OprNum">OprNum</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OprNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#OriginalQuantity name="OriginalQuantity">OriginalQuantity</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalQuantity attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PdsExpiryDate name="PdsExpiryDate">PdsExpiryDate</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsExpiryDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#PdsSellableDays name="PdsSellableDays">PdsSellableDays</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsSellableDays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PlanVersion name="PlanVersion">PlanVersion</a>

First included in: Transaction/ReqTrans (this entity)  

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

### <a href=#PmfActionQtyAdd name="PmfActionQtyAdd">PmfActionQtyAdd</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PmfActionQtyAdd attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PmfCoByRefRecId name="PmfCoByRefRecId">PmfCoByRefRecId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PmfCoByRefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PmfPlanGroupId name="PmfPlanGroupId">PmfPlanGroupId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PmfPlanGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PmfPlanGroupPrimaryIssue name="PmfPlanGroupPrimaryIssue">PmfPlanGroupPrimaryIssue</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PmfPlanGroupPrimaryIssue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PmfPlanGroupPriority name="PmfPlanGroupPriority">PmfPlanGroupPriority</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PmfPlanGroupPriority attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PmfPlanningItemId name="PmfPlanningItemId">PmfPlanningItemId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PmfPlanningItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PmfPlanPriorityCurrent name="PmfPlanPriorityCurrent">PmfPlanPriorityCurrent</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PmfPlanPriorityCurrent attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Priority name="Priority">Priority</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Priority attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#Qty name="Qty">Qty</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Qty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RefId name="RefId">RefId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefType name="RefType">RefType</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#ReqDate name="ReqDate">ReqDate</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#ReqDateDlvOrig name="ReqDateDlvOrig">ReqDateDlvOrig</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqDateDlvOrig attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#ReqProcessId name="ReqProcessId">ReqProcessId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqProcessId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReqTime name="ReqTime">ReqTime</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.readOnly**  
**is.dataFormat.time**  
</details>

### <a href=#RequisitionLine name="RequisitionLine">RequisitionLine</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequisitionLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SupplyDemandSubClassification name="SupplyDemandSubClassification">SupplyDemandSubClassification</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SupplyDemandSubClassification attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsForcedItemBomId name="IsForcedItemBomId">IsForcedItemBomId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsForcedItemBomId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsForcedItemRouteId name="IsForcedItemRouteId">IsForcedItemRouteId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsForcedItemRouteId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FuturesCalculated name="FuturesCalculated">FuturesCalculated</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FuturesCalculated attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/ReqTrans (this entity)  

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

### <a href=#Relationship_BOMRelationshipId name="Relationship_BOMRelationshipId">Relationship_BOMRelationshipId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BOMRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductInformationManagement/Main/BOM.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/BOM.cdm.json/BOM</a></td><td><a href="../../ProductInformationManagement/Main/BOM.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BOMLineRelationshipId name="Relationship_BOMLineRelationshipId">Relationship_BOMLineRelationshipId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BOMLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/ReqPO.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/WorksheetHeader/ReqPO.cdm.json/ReqPO</a></td><td><a href="../WorksheetHeader/ReqPO.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BOMTableRelationshipId name="Relationship_BOMTableRelationshipId">Relationship_BOMTableRelationshipId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BOMTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductInformationManagement/Main/BOMTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/BOMTable.cdm.json/BOMTable</a></td><td><a href="../../ProductInformationManagement/Main/BOMTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustGroupRelationshipId name="Relationship_CustGroupRelationshipId">Relationship_CustGroupRelationshipId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountsReceivable/Group/CustGroup.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Group/CustGroup.cdm.json/CustGroup</a></td><td><a href="../../../Finance/AccountsReceivable/Group/CustGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustTableRelationshipId name="Relationship_CustTableRelationshipId">Relationship_CustTableRelationshipId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Customer/Main/CustTable.md" target="_blank">/core/operationsCommon/Tables/Common/Customer/Main/CustTable.cdm.json/CustTable</a></td><td><a href="../../../Common/Customer/Main/CustTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventDimRelationshipId name="Relationship_InventDimRelationshipId">Relationship_InventDimRelationshipId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventDimRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Main/InventDim.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/InventDim.cdm.json/InventDim</a></td><td><a href="../../Inventory/Main/InventDim.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventOnhandRelationshipId name="Relationship_InventOnhandRelationshipId">Relationship_InventOnhandRelationshipId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventOnhandRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Transaction/InventSum.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/InventSum.cdm.json/InventSum</a></td><td><a href="../../Inventory/Transaction/InventSum.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTransOriginRelationshipId name="Relationship_InventTransOriginRelationshipId">Relationship_InventTransOriginRelationshipId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTransOriginRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Transaction/InventTransOrigin.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/InventTransOrigin.cdm.json/InventTransOrigin</a></td><td><a href="../../Inventory/Transaction/InventTransOrigin.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ItemtableRelationshipId name="Relationship_ItemtableRelationshipId">Relationship_ItemtableRelationshipId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ItemtableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductInformationManagement/Main/InventTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/InventTable.cdm.json/InventTable</a></td><td><a href="../../ProductInformationManagement/Main/InventTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MarkingRefInventTransOriginRelationshipId name="Relationship_MarkingRefInventTransOriginRelationshipId">Relationship_MarkingRefInventTransOriginRelationshipId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MarkingRefInventTransOriginRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Transaction/InventTransOrigin.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/InventTransOrigin.cdm.json/InventTransOrigin</a></td><td><a href="../../Inventory/Transaction/InventTransOrigin.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PmfFormulaCoByRelationshipId name="Relationship_PmfFormulaCoByRelationshipId">Relationship_PmfFormulaCoByRelationshipId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PmfFormulaCoByRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductionControl/Main/PmfFormulaCoBy.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Main/PmfFormulaCoBy.cdm.json/PmfFormulaCoBy</a></td><td><a href="../../ProductionControl/Main/PmfFormulaCoBy.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PmfFormulaLineRelationshipId name="Relationship_PmfFormulaLineRelationshipId">Relationship_PmfFormulaLineRelationshipId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PmfFormulaLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/ReqPO.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/WorksheetHeader/ReqPO.cdm.json/ReqPO</a></td><td><a href="../WorksheetHeader/ReqPO.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PmfPlanGroupRelationshipId name="Relationship_PmfPlanGroupRelationshipId">Relationship_PmfPlanGroupRelationshipId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PmfPlanGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductionControl/Group/PmfPlanGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Group/PmfPlanGroup.cdm.json/PmfPlanGroup</a></td><td><a href="../../ProductionControl/Group/PmfPlanGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PmfPlanningItemRelationshipId name="Relationship_PmfPlanningItemRelationshipId">Relationship_PmfPlanningItemRelationshipId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PmfPlanningItemRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductInformationManagement/Main/InventTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/InventTable.cdm.json/InventTable</a></td><td><a href="../../ProductInformationManagement/Main/InventTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PmfProdCoByRelationshipId name="Relationship_PmfProdCoByRelationshipId">Relationship_PmfProdCoByRelationshipId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PmfProdCoByRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductionControl/WorksheetLine/PmfProdCoBy.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/WorksheetLine/PmfProdCoBy.cdm.json/PmfProdCoBy</a></td><td><a href="../../ProductionControl/WorksheetLine/PmfProdCoBy.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProductionRelationshipId name="Relationship_ProductionRelationshipId">Relationship_ProductionRelationshipId</a>

First included in: Transaction/ReqTrans (this entity)  

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

### <a href=#Relationship_ProductionLineRelationshipId name="Relationship_ProductionLineRelationshipId">Relationship_ProductionLineRelationshipId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductionLineRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PurchRelationshipId name="Relationship_PurchRelationshipId">Relationship_PurchRelationshipId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProcurementAndSourcing/WorksheetHeader/PurchTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchTable.cdm.json/PurchTable</a></td><td><a href="../../ProcurementAndSourcing/WorksheetHeader/PurchTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReqPlanVersionRelationshipId name="Relationship_ReqPlanVersionRelationshipId">Relationship_ReqPlanVersionRelationshipId</a>

First included in: Transaction/ReqTrans (this entity)  

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

### <a href=#Relationship_ReqPlanVersionLastPlanRelationshipId name="Relationship_ReqPlanVersionLastPlanRelationshipId">Relationship_ReqPlanVersionLastPlanRelationshipId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReqPlanVersionLastPlanRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReqPoRelationshipId name="Relationship_ReqPoRelationshipId">Relationship_ReqPoRelationshipId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReqPoRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/ReqPO.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/WorksheetHeader/ReqPO.cdm.json/ReqPO</a></td><td><a href="../WorksheetHeader/ReqPO.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReqPOPlannedIntercompanyDemandRelationshipId name="Relationship_ReqPOPlannedIntercompanyDemandRelationshipId">Relationship_ReqPOPlannedIntercompanyDemandRelationshipId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReqPOPlannedIntercompanyDemandRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/ReqPO.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/WorksheetHeader/ReqPO.cdm.json/ReqPO</a></td><td><a href="../WorksheetHeader/ReqPO.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RequisitionLineRelationshipId name="Relationship_RequisitionLineRelationshipId">Relationship_RequisitionLineRelationshipId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RequisitionLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProcurementAndSourcing/WorksheetLine/PurchReqLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetLine/PurchReqLine.cdm.json/PurchReqLine</a></td><td><a href="../../ProcurementAndSourcing/WorksheetLine/PurchReqLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RouteTableRelationshipId name="Relationship_RouteTableRelationshipId">Relationship_RouteTableRelationshipId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RouteTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductionControl/Main/RouteTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Main/RouteTable.cdm.json/RouteTable</a></td><td><a href="../../ProductionControl/Main/RouteTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesOrderRelationshipId name="Relationship_SalesOrderRelationshipId">Relationship_SalesOrderRelationshipId</a>

First included in: Transaction/ReqTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesOrderRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/WorksheetHeader/SalesTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/SalesTable.cdm.json/SalesTable</a></td><td><a href="../../SalesAndMarketing/WorksheetHeader/SalesTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/ReqTrans (this entity)  

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
