---
title: InventQualityOrderTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# InventQualityOrderTable

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/SupplyChain/Inventory/WorksheetHeader/InventQualityOrderTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventQualityOrderTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[AcceptableQualityLevel](#AcceptableQualityLevel)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[AccountRelation](#AccountRelation)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[ApplyIndiaTaxes_IN](#ApplyIndiaTaxes_IN)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[BlockingQty](#BlockingQty)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[CompleteBlocking](#CompleteBlocking)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[DefaultDimension](#DefaultDimension)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[FailedInventStatusId](#FailedInventStatusId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[InventDimId](#InventDimId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[InventRefId](#InventRefId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[InventRefTransId](#InventRefTransId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[InventTransId](#InventTransId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[ItemId](#ItemId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[ItemName](#ItemName)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[ItemSamplingId](#ItemSamplingId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[OprNum](#OprNum)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[OrderStatus](#OrderStatus)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[PassedInventStatusId](#PassedInventStatusId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[PdsCWBlockingQty](#PdsCWBlockingQty)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[PdsCWQty](#PdsCWQty)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[PdsFailedQualityDispositionCode](#PdsFailedQualityDispositionCode)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[PdsPassQualityDispositionCode](#PdsPassQualityDispositionCode)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[PdsUpdateBatchDisp](#PdsUpdateBatchDisp)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[PdsUpdateInvBatchAttributes](#PdsUpdateInvBatchAttributes)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[Qty](#Qty)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[QualityOrderId](#QualityOrderId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[QuarantineOnFailure](#QuarantineOnFailure)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[ReferenceType](#ReferenceType)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[RouteId](#RouteId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[RouteOprId](#RouteOprId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[TestDestructive](#TestDestructive)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[TestGroupId](#TestGroupId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[UpdateInventStatus](#UpdateInventStatus)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[ValidateDate_IN](#ValidateDate_IN)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[ValidatedByWorker](#ValidatedByWorker)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[ValidatedDateTime](#ValidatedDateTime)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[WrkCtrId](#WrkCtrId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[DataAreaId](#DataAreaId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[Relationship_CustTableRelationshipId](#Relationship_CustTableRelationshipId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[Relationship_DefaultDimensionRelationshipId](#Relationship_DefaultDimensionRelationshipId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[Relationship_FailedInventStatusRelationshipId](#Relationship_FailedInventStatusRelationshipId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[Relationship_InventDimRelationshipId](#Relationship_InventDimRelationshipId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[Relationship_InventItemSamplingRelationshipId](#Relationship_InventItemSamplingRelationshipId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[Relationship_InventQuarantineOrderRelationshipId](#Relationship_InventQuarantineOrderRelationshipId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[Relationship_InventTableRelationshipId](#Relationship_InventTableRelationshipId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[Relationship_InventTestGroupRelationshipId](#Relationship_InventTestGroupRelationshipId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[Relationship_InventTransOriginRelationshipId](#Relationship_InventTransOriginRelationshipId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[Relationship_PassedInventStatusRelationshipId](#Relationship_PassedInventStatusRelationshipId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[Relationship_PdsFailedDispositionCodeRelationshipId](#Relationship_PdsFailedDispositionCodeRelationshipId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[Relationship_PdsPassDispositionCodeRelationshipId](#Relationship_PdsPassDispositionCodeRelationshipId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[Relationship_PmfProdCoByRelationshipId](#Relationship_PmfProdCoByRelationshipId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[Relationship_ProdRouteRelationshipId](#Relationship_ProdRouteRelationshipId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[Relationship_ProdTableRelationshipId](#Relationship_ProdTableRelationshipId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[Relationship_PurchLineRelationshipId](#Relationship_PurchLineRelationshipId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[Relationship_PurchParmLineRelationshipId](#Relationship_PurchParmLineRelationshipId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[Relationship_PurchTableRelationshipId](#Relationship_PurchTableRelationshipId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[Relationship_RouteOprTableRelationshipId](#Relationship_RouteOprTableRelationshipId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[Relationship_RouteTableRelationshipId](#Relationship_RouteTableRelationshipId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[Relationship_SalesLineRelationshipId](#Relationship_SalesLineRelationshipId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[Relationship_SalesTableRelationshipId](#Relationship_SalesTableRelationshipId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[Relationship_VendTableRelationshipId](#Relationship_VendTableRelationshipId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[Relationship_WrkCtrTableRelationshipId](#Relationship_WrkCtrTableRelationshipId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[Relationship_TaxEngineQualityOrderTableHeaderRelationshipId](#Relationship_TaxEngineQualityOrderTableHeaderRelationshipId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="InventQualityOrderTable.md" target="_blank">WorksheetHeader/InventQualityOrderTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventQualityOrderTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AcceptableQualityLevel name="AcceptableQualityLevel">AcceptableQualityLevel</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceptableQualityLevel attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AccountRelation name="AccountRelation">AccountRelation</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApplyIndiaTaxes_IN name="ApplyIndiaTaxes_IN">ApplyIndiaTaxes_IN</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplyIndiaTaxes_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BlockingQty name="BlockingQty">BlockingQty</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BlockingQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CompleteBlocking name="CompleteBlocking">CompleteBlocking</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompleteBlocking attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FailedInventStatusId name="FailedInventStatusId">FailedInventStatusId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FailedInventStatusId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventDimId name="InventDimId">InventDimId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventRefId name="InventRefId">InventRefId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventRefId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventRefTransId name="InventRefTransId">InventRefTransId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventRefTransId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTransId name="InventTransId">InventTransId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTransId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemName name="ItemName">ItemName</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSamplingId name="ItemSamplingId">ItemSamplingId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSamplingId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OprNum name="OprNum">OprNum</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OprNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OrderStatus name="OrderStatus">OrderStatus</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PassedInventStatusId name="PassedInventStatusId">PassedInventStatusId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PassedInventStatusId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PdsCWBlockingQty name="PdsCWBlockingQty">PdsCWBlockingQty</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsCWBlockingQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PdsCWQty name="PdsCWQty">PdsCWQty</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsCWQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PdsFailedQualityDispositionCode name="PdsFailedQualityDispositionCode">PdsFailedQualityDispositionCode</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsFailedQualityDispositionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PdsPassQualityDispositionCode name="PdsPassQualityDispositionCode">PdsPassQualityDispositionCode</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsPassQualityDispositionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PdsUpdateBatchDisp name="PdsUpdateBatchDisp">PdsUpdateBatchDisp</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsUpdateBatchDisp attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PdsUpdateInvBatchAttributes name="PdsUpdateInvBatchAttributes">PdsUpdateInvBatchAttributes</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsUpdateInvBatchAttributes attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Qty name="Qty">Qty</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Qty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#QualityOrderId name="QualityOrderId">QualityOrderId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualityOrderId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuarantineOnFailure name="QuarantineOnFailure">QuarantineOnFailure</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuarantineOnFailure attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReferenceType name="ReferenceType">ReferenceType</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReferenceType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RouteId name="RouteId">RouteId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteOprId name="RouteOprId">RouteOprId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteOprId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TestDestructive name="TestDestructive">TestDestructive</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TestDestructive attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TestGroupId name="TestGroupId">TestGroupId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TestGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UpdateInventStatus name="UpdateInventStatus">UpdateInventStatus</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpdateInventStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ValidateDate_IN name="ValidateDate_IN">ValidateDate_IN</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidateDate_IN attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#ValidatedByWorker name="ValidatedByWorker">ValidatedByWorker</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidatedByWorker attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ValidatedDateTime name="ValidatedDateTime">ValidatedDateTime</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidatedDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#WrkCtrId name="WrkCtrId">WrkCtrId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WrkCtrId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

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

### <a href=#Relationship_CustTableRelationshipId name="Relationship_CustTableRelationshipId">Relationship_CustTableRelationshipId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Customer/Main/CustTable.md" target="_blank">/core/erp/Tables/Common/Customer/Main/CustTable.cdm.json/CustTable</a></td><td><a href="../../../Common/Customer/Main/CustTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionRelationshipId name="Relationship_DefaultDimensionRelationshipId">Relationship_DefaultDimensionRelationshipId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FailedInventStatusRelationshipId name="Relationship_FailedInventStatusRelationshipId">Relationship_FailedInventStatusRelationshipId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FailedInventStatusRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/WHSInventStatus.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Main/WHSInventStatus.cdm.json/WHSInventStatus</a></td><td><a href="../Main/WHSInventStatus.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventDimRelationshipId name="Relationship_InventDimRelationshipId">Relationship_InventDimRelationshipId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/InventDim.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Main/InventDim.cdm.json/InventDim</a></td><td><a href="../Main/InventDim.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventItemSamplingRelationshipId name="Relationship_InventItemSamplingRelationshipId">Relationship_InventItemSamplingRelationshipId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventItemSamplingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/InventItemSampling.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Group/InventItemSampling.cdm.json/InventItemSampling</a></td><td><a href="../Group/InventItemSampling.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventQuarantineOrderRelationshipId name="Relationship_InventQuarantineOrderRelationshipId">Relationship_InventQuarantineOrderRelationshipId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventQuarantineOrderRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetLine/InventQuarantineOrder.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/WorksheetLine/InventQuarantineOrder.cdm.json/InventQuarantineOrder</a></td><td><a href="../WorksheetLine/InventQuarantineOrder.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTableRelationshipId name="Relationship_InventTableRelationshipId">Relationship_InventTableRelationshipId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductInformationManagement/Main/InventTable.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/InventTable.cdm.json/InventTable</a></td><td><a href="../../ProductInformationManagement/Main/InventTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTestGroupRelationshipId name="Relationship_InventTestGroupRelationshipId">Relationship_InventTestGroupRelationshipId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTestGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/InventTestGroup.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Group/InventTestGroup.cdm.json/InventTestGroup</a></td><td><a href="../Group/InventTestGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTransOriginRelationshipId name="Relationship_InventTransOriginRelationshipId">Relationship_InventTransOriginRelationshipId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/InventTransOrigin.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Transaction/InventTransOrigin.cdm.json/InventTransOrigin</a></td><td><a href="../Transaction/InventTransOrigin.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PassedInventStatusRelationshipId name="Relationship_PassedInventStatusRelationshipId">Relationship_PassedInventStatusRelationshipId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PassedInventStatusRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/WHSInventStatus.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Main/WHSInventStatus.cdm.json/WHSInventStatus</a></td><td><a href="../Main/WHSInventStatus.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PdsFailedDispositionCodeRelationshipId name="Relationship_PdsFailedDispositionCodeRelationshipId">Relationship_PdsFailedDispositionCodeRelationshipId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PdsFailedDispositionCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/PdsDispositionMaster.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Group/PdsDispositionMaster.cdm.json/PdsDispositionMaster</a></td><td><a href="../Group/PdsDispositionMaster.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PdsPassDispositionCodeRelationshipId name="Relationship_PdsPassDispositionCodeRelationshipId">Relationship_PdsPassDispositionCodeRelationshipId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PdsPassDispositionCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/PdsDispositionMaster.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Group/PdsDispositionMaster.cdm.json/PdsDispositionMaster</a></td><td><a href="../Group/PdsDispositionMaster.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PmfProdCoByRelationshipId name="Relationship_PmfProdCoByRelationshipId">Relationship_PmfProdCoByRelationshipId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductionControl/WorksheetLine/PmfProdCoBy.md" target="_blank">/core/erp/Tables/SupplyChain/ProductionControl/WorksheetLine/PmfProdCoBy.cdm.json/PmfProdCoBy</a></td><td><a href="../../ProductionControl/WorksheetLine/PmfProdCoBy.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProdRouteRelationshipId name="Relationship_ProdRouteRelationshipId">Relationship_ProdRouteRelationshipId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

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

### <a href=#Relationship_ProdTableRelationshipId name="Relationship_ProdTableRelationshipId">Relationship_ProdTableRelationshipId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProdTableRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PurchLineRelationshipId name="Relationship_PurchLineRelationshipId">Relationship_PurchLineRelationshipId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProcurementAndSourcing/WorksheetLine/PurchLine.md" target="_blank">/core/erp/Tables/SupplyChain/ProcurementAndSourcing/WorksheetLine/PurchLine.cdm.json/PurchLine</a></td><td><a href="../../ProcurementAndSourcing/WorksheetLine/PurchLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchParmLineRelationshipId name="Relationship_PurchParmLineRelationshipId">Relationship_PurchParmLineRelationshipId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchParmLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProcurementAndSourcing/WorksheetLine/PurchParmLine.md" target="_blank">/core/erp/Tables/SupplyChain/ProcurementAndSourcing/WorksheetLine/PurchParmLine.cdm.json/PurchParmLine</a></td><td><a href="../../ProcurementAndSourcing/WorksheetLine/PurchParmLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchTableRelationshipId name="Relationship_PurchTableRelationshipId">Relationship_PurchTableRelationshipId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProcurementAndSourcing/WorksheetHeader/PurchTable.md" target="_blank">/core/erp/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchTable.cdm.json/PurchTable</a></td><td><a href="../../ProcurementAndSourcing/WorksheetHeader/PurchTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RouteOprTableRelationshipId name="Relationship_RouteOprTableRelationshipId">Relationship_RouteOprTableRelationshipId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RouteOprTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductionControl/Main/RouteOprTable.md" target="_blank">/core/erp/Tables/SupplyChain/ProductionControl/Main/RouteOprTable.cdm.json/RouteOprTable</a></td><td><a href="../../ProductionControl/Main/RouteOprTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RouteTableRelationshipId name="Relationship_RouteTableRelationshipId">Relationship_RouteTableRelationshipId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductionControl/Main/RouteTable.md" target="_blank">/core/erp/Tables/SupplyChain/ProductionControl/Main/RouteTable.cdm.json/RouteTable</a></td><td><a href="../../ProductionControl/Main/RouteTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesLineRelationshipId name="Relationship_SalesLineRelationshipId">Relationship_SalesLineRelationshipId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/WorksheetLine/SalesLine.md" target="_blank">/core/erp/Tables/SupplyChain/SalesAndMarketing/WorksheetLine/SalesLine.cdm.json/SalesLine</a></td><td><a href="../../SalesAndMarketing/WorksheetLine/SalesLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesTableRelationshipId name="Relationship_SalesTableRelationshipId">Relationship_SalesTableRelationshipId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/WorksheetHeader/SalesTable.md" target="_blank">/core/erp/Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/SalesTable.cdm.json/SalesTable</a></td><td><a href="../../SalesAndMarketing/WorksheetHeader/SalesTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTableRelationshipId name="Relationship_VendTableRelationshipId">Relationship_VendTableRelationshipId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Vendor/Main/VendTable.md" target="_blank">/core/erp/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WrkCtrTableRelationshipId name="Relationship_WrkCtrTableRelationshipId">Relationship_WrkCtrTableRelationshipId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WrkCtrTableRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TaxEngineQualityOrderTableHeaderRelationshipId name="Relationship_TaxEngineQualityOrderTableHeaderRelationshipId">Relationship_TaxEngineQualityOrderTableHeaderRelationshipId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxEngineQualityOrderTableHeaderRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Miscellaneous/TaxEngineQualityOrderTableHeader.md" target="_blank">/core/erp/Tables/Finance/Tax/Miscellaneous/TaxEngineQualityOrderTableHeader.cdm.json/TaxEngineQualityOrderTableHeader</a></td><td><a href="../../../Finance/Tax/Miscellaneous/TaxEngineQualityOrderTableHeader.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetHeader/InventQualityOrderTable (this entity)  

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
