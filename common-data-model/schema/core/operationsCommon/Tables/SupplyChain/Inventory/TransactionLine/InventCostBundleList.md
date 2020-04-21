---
title: InventCostBundleList - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# InventCostBundleList

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/TransactionLine/InventCostBundleList.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventCostBundleList/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|
|[EndTime](#EndTime)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|
|[InventClosing](#InventClosing)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|
|[Level](#Level)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|
|[LoadCount](#LoadCount)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|
|[LoadTime](#LoadTime)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|
|[LoadTransferOrderCount](#LoadTransferOrderCount)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|
|[LoadTransferOrderTime](#LoadTransferOrderTime)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|
|[PreCloseNonFinancialCount](#PreCloseNonFinancialCount)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|
|[PreCloseNonFinancialTime](#PreCloseNonFinancialTime)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|
|[PreCloseTransferOrderCount](#PreCloseTransferOrderCount)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|
|[PreCloseTransferOrderTime](#PreCloseTransferOrderTime)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|
|[ProcessingState](#ProcessingState)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|
|[StartTime](#StartTime)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|
|[UpdateLevelAdjustmentCount](#UpdateLevelAdjustmentCount)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|
|[UpdateLevelAdjustmentTime](#UpdateLevelAdjustmentTime)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|
|[UpdateMarkingCount](#UpdateMarkingCount)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|
|[UpdateMarkingTime](#UpdateMarkingTime)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|
|[UpdateModelCount](#UpdateModelCount)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|
|[UpdateModelTime](#UpdateModelTime)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|
|[UpdateReceiptAdjustmentCount](#UpdateReceiptAdjustmentCount)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|
|[UpdateReceiptAdjustmentTime](#UpdateReceiptAdjustmentTime)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|
|[UpdateReturnAdjustmentsCount](#UpdateReturnAdjustmentsCount)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|
|[UpdateReturnAdjustmentsTime](#UpdateReturnAdjustmentsTime)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|
|[Batch](#Batch)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|
|[DataAreaId](#DataAreaId)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|
|[Relationship_InventClosingRelationshipId](#Relationship_InventClosingRelationshipId)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="InventCostBundleList.md" target="_blank">TransactionLine/InventCostBundleList</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventCostBundleList/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EndTime name="EndTime">EndTime</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#InventClosing name="InventClosing">InventClosing</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventClosing attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Level name="Level">Level</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Level attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LoadCount name="LoadCount">LoadCount</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadCount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LoadTime name="LoadTime">LoadTime</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LoadTransferOrderCount name="LoadTransferOrderCount">LoadTransferOrderCount</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadTransferOrderCount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LoadTransferOrderTime name="LoadTransferOrderTime">LoadTransferOrderTime</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadTransferOrderTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PreCloseNonFinancialCount name="PreCloseNonFinancialCount">PreCloseNonFinancialCount</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreCloseNonFinancialCount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PreCloseNonFinancialTime name="PreCloseNonFinancialTime">PreCloseNonFinancialTime</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreCloseNonFinancialTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PreCloseTransferOrderCount name="PreCloseTransferOrderCount">PreCloseTransferOrderCount</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreCloseTransferOrderCount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PreCloseTransferOrderTime name="PreCloseTransferOrderTime">PreCloseTransferOrderTime</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreCloseTransferOrderTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProcessingState name="ProcessingState">ProcessingState</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessingState attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StartTime name="StartTime">StartTime</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#UpdateLevelAdjustmentCount name="UpdateLevelAdjustmentCount">UpdateLevelAdjustmentCount</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpdateLevelAdjustmentCount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UpdateLevelAdjustmentTime name="UpdateLevelAdjustmentTime">UpdateLevelAdjustmentTime</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpdateLevelAdjustmentTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UpdateMarkingCount name="UpdateMarkingCount">UpdateMarkingCount</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpdateMarkingCount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UpdateMarkingTime name="UpdateMarkingTime">UpdateMarkingTime</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpdateMarkingTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UpdateModelCount name="UpdateModelCount">UpdateModelCount</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpdateModelCount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UpdateModelTime name="UpdateModelTime">UpdateModelTime</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpdateModelTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UpdateReceiptAdjustmentCount name="UpdateReceiptAdjustmentCount">UpdateReceiptAdjustmentCount</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpdateReceiptAdjustmentCount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UpdateReceiptAdjustmentTime name="UpdateReceiptAdjustmentTime">UpdateReceiptAdjustmentTime</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpdateReceiptAdjustmentTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UpdateReturnAdjustmentsCount name="UpdateReturnAdjustmentsCount">UpdateReturnAdjustmentsCount</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpdateReturnAdjustmentsCount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UpdateReturnAdjustmentsTime name="UpdateReturnAdjustmentsTime">UpdateReturnAdjustmentsTime</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpdateReturnAdjustmentsTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Batch name="Batch">Batch</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Batch attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

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

### <a href=#Relationship_InventClosingRelationshipId name="Relationship_InventClosingRelationshipId">Relationship_InventClosingRelationshipId</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventClosingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../TransactionHeader/InventClosing.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/TransactionHeader/InventClosing.cdm.json/InventClosing</a></td><td><a href="../TransactionHeader/InventClosing.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: TransactionLine/InventCostBundleList (this entity)  

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
