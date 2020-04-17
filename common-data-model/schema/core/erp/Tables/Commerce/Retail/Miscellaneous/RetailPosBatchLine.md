---
title: RetailPosBatchLine - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailPosBatchLine

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailPosBatchLine.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailPosBatchLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[AddedToDrawer](#AddedToDrawer)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[BankedAmount](#BankedAmount)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[BankedAmountMST](#BankedAmountMST)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[BankedAmountStore](#BankedAmountStore)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[BatchId](#BatchId)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[BatchTerminalId](#BatchTerminalId)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[CardFeeAmount](#CardFeeAmount)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[CardTypeId](#CardTypeId)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[CashLaterReturnedAmountCur_RU](#CashLaterReturnedAmountCur_RU)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[CashLaterReturnedAmountMST_RU](#CashLaterReturnedAmountMST_RU)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[CashLaterReturnedAmountStore_RU](#CashLaterReturnedAmountStore_RU)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[ChangeTender](#ChangeTender)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[CountedAmount](#CountedAmount)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[CountedAmountMST](#CountedAmountMST)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[CountedAmountStore](#CountedAmountStore)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[CreatedOnChannel](#CreatedOnChannel)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[Currency](#Currency)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[LineNum](#LineNum)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[OrderInvoiceAmount](#OrderInvoiceAmount)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[OrderInvoiceAmountMST](#OrderInvoiceAmountMST)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[RealExchRate](#RealExchRate)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[RemovedFromDrawer](#RemovedFromDrawer)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[SafeAmount](#SafeAmount)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[SafeAmountMST](#SafeAmountMST)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[SafeAmountStore](#SafeAmountStore)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[StaffId](#StaffId)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[StatementCode](#StatementCode)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[StatementId](#StatementId)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[StoreExchRate](#StoreExchRate)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[StoreId](#StoreId)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[TenderTypeId](#TenderTypeId)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[TerminalId](#TerminalId)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[TransAmount](#TransAmount)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[TransAmountMST](#TransAmountMST)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[TransAmountStore](#TransAmountStore)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[UniqueShiftId](#UniqueShiftId)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[DataAreaId](#DataAreaId)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[Relationship_RetailPosBatchTableRelationshipId](#Relationship_RetailPosBatchTableRelationshipId)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RetailPosBatchLine.md" target="_blank">Miscellaneous/RetailPosBatchLine</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailPosBatchLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AddedToDrawer name="AddedToDrawer">AddedToDrawer</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddedToDrawer attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#BankedAmount name="BankedAmount">BankedAmount</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankedAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#BankedAmountMST name="BankedAmountMST">BankedAmountMST</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankedAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#BankedAmountStore name="BankedAmountStore">BankedAmountStore</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankedAmountStore attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#BatchId name="BatchId">BatchId</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BatchTerminalId name="BatchTerminalId">BatchTerminalId</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchTerminalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CardFeeAmount name="CardFeeAmount">CardFeeAmount</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CardFeeAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CardTypeId name="CardTypeId">CardTypeId</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CardTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashLaterReturnedAmountCur_RU name="CashLaterReturnedAmountCur_RU">CashLaterReturnedAmountCur_RU</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashLaterReturnedAmountCur_RU attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CashLaterReturnedAmountMST_RU name="CashLaterReturnedAmountMST_RU">CashLaterReturnedAmountMST_RU</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashLaterReturnedAmountMST_RU attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CashLaterReturnedAmountStore_RU name="CashLaterReturnedAmountStore_RU">CashLaterReturnedAmountStore_RU</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashLaterReturnedAmountStore_RU attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ChangeTender name="ChangeTender">ChangeTender</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChangeTender attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CountedAmount name="CountedAmount">CountedAmount</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountedAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CountedAmountMST name="CountedAmountMST">CountedAmountMST</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountedAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CountedAmountStore name="CountedAmountStore">CountedAmountStore</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountedAmountStore attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CreatedOnChannel name="CreatedOnChannel">CreatedOnChannel</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreatedOnChannel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Currency name="Currency">Currency</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Currency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#OrderInvoiceAmount name="OrderInvoiceAmount">OrderInvoiceAmount</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderInvoiceAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#OrderInvoiceAmountMST name="OrderInvoiceAmountMST">OrderInvoiceAmountMST</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderInvoiceAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RealExchRate name="RealExchRate">RealExchRate</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RealExchRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RemovedFromDrawer name="RemovedFromDrawer">RemovedFromDrawer</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemovedFromDrawer attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SafeAmount name="SafeAmount">SafeAmount</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SafeAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SafeAmountMST name="SafeAmountMST">SafeAmountMST</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SafeAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SafeAmountStore name="SafeAmountStore">SafeAmountStore</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SafeAmountStore attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#StaffId name="StaffId">StaffId</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StaffId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatementCode name="StatementCode">StatementCode</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatementCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatementId name="StatementId">StatementId</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StoreExchRate name="StoreExchRate">StoreExchRate</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreExchRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#StoreId name="StoreId">StoreId</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TenderTypeId name="TenderTypeId">TenderTypeId</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TenderTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TerminalId name="TerminalId">TerminalId</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TerminalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransAmount name="TransAmount">TransAmount</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransAmountMST name="TransAmountMST">TransAmountMST</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransAmountStore name="TransAmountStore">TransAmountStore</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransAmountStore attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#UniqueShiftId name="UniqueShiftId">UniqueShiftId</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UniqueShiftId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

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

### <a href=#Relationship_RetailPosBatchTableRelationshipId name="Relationship_RetailPosBatchTableRelationshipId">Relationship_RetailPosBatchTableRelationshipId</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailPosBatchTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/RetailPosBatchTable.md" target="_blank">/core/erp/Tables/Commerce/Retail/WorksheetHeader/RetailPosBatchTable.cdm.json/RetailPosBatchTable</a></td><td><a href="../WorksheetHeader/RetailPosBatchTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/RetailPosBatchLine (this entity)  

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
