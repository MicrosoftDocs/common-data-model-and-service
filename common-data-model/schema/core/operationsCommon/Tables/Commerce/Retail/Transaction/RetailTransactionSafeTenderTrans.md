---
title: RetailTransactionSafeTenderTrans - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailTransactionSafeTenderTrans

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Transaction/RetailTransactionSafeTenderTrans.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailTransactionSafeTenderTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[AmountCur](#AmountCur)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[amountCurPOS](#amountCurPOS)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[amountMST](#amountMST)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[amountMSTPOS](#amountMSTPOS)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[AmountTendered](#AmountTendered)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[amountTenderedPOS](#amountTenderedPOS)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[businessDate](#businessDate)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[CardorAccount](#CardorAccount)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[CardTypeId](#CardTypeId)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[ChangeLine](#ChangeLine)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[Channel](#Channel)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[Counter](#Counter)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[Currency](#Currency)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[ExchRate](#ExchRate)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[exchRateMST](#exchRateMST)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[LineNum](#LineNum)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[ManagersKeyLive](#ManagersKeyLive)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[MessageNum](#MessageNum)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[Origin](#Origin)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[Qty](#Qty)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[Replicated](#Replicated)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[replicationCounterFromOrigin](#replicationCounterFromOrigin)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[Shift](#Shift)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[ShiftDate](#ShiftDate)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[Staff](#Staff)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[StatementCode](#StatementCode)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[StatementId](#StatementId)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[statusType](#statusType)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[Store](#Store)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[TenderType](#TenderType)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[Terminal](#Terminal)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[TransactionId](#TransactionId)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[TransactionStatus](#TransactionStatus)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[TransDate](#TransDate)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[TransTime](#TransTime)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[DataAreaId](#DataAreaId)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[Relationship_RetailChannelTableRelationshipId](#Relationship_RetailChannelTableRelationshipId)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[Relationship_RetailStatementLineRelationshipId](#Relationship_RetailStatementLineRelationshipId)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[Relationship_RetailStatementTableRelationshipId](#Relationship_RetailStatementTableRelationshipId)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[Relationship_RetailStatementTransRelationshipId](#Relationship_RetailStatementTransRelationshipId)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[Relationship_RetailStoreTableRelationshipId](#Relationship_RetailStoreTableRelationshipId)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[Relationship_RetailStoreWorkShiftTableRelationshipId](#Relationship_RetailStoreWorkShiftTableRelationshipId)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[Relationship_RetailTenderTypeCardTableRelationshipId](#Relationship_RetailTenderTypeCardTableRelationshipId)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[Relationship_RetailTenderTypeTableRelationshipId](#Relationship_RetailTenderTypeTableRelationshipId)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[Relationship_RetailTerminalTableRelationshipId](#Relationship_RetailTerminalTableRelationshipId)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[Relationship_RetailTransactionTableRelationshipId](#Relationship_RetailTransactionTableRelationshipId)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RetailTransactionSafeTenderTrans.md" target="_blank">Transaction/RetailTransactionSafeTenderTrans</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailTransactionSafeTenderTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AmountCur name="AmountCur">AmountCur</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#amountCurPOS name="amountCurPOS">amountCurPOS</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the amountCurPOS attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#amountMST name="amountMST">amountMST</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the amountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#amountMSTPOS name="amountMSTPOS">amountMSTPOS</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the amountMSTPOS attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AmountTendered name="AmountTendered">AmountTendered</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountTendered attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#amountTenderedPOS name="amountTenderedPOS">amountTenderedPOS</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the amountTenderedPOS attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#businessDate name="businessDate">businessDate</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the businessDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#CardorAccount name="CardorAccount">CardorAccount</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CardorAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CardTypeId name="CardTypeId">CardTypeId</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CardTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChangeLine name="ChangeLine">ChangeLine</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChangeLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Channel name="Channel">Channel</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Channel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Counter name="Counter">Counter</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Counter attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Currency name="Currency">Currency</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Currency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchRate name="ExchRate">ExchRate</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#exchRateMST name="exchRateMST">exchRateMST</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the exchRateMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ManagersKeyLive name="ManagersKeyLive">ManagersKeyLive</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManagersKeyLive attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MessageNum name="MessageNum">MessageNum</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MessageNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Origin name="Origin">Origin</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Origin attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Qty name="Qty">Qty</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

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

### <a href=#Replicated name="Replicated">Replicated</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Replicated attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#replicationCounterFromOrigin name="replicationCounterFromOrigin">replicationCounterFromOrigin</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the replicationCounterFromOrigin attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Shift name="Shift">Shift</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Shift attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShiftDate name="ShiftDate">ShiftDate</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShiftDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Staff name="Staff">Staff</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Staff attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatementCode name="StatementCode">StatementCode</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatementCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatementId name="StatementId">StatementId</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#statusType name="statusType">statusType</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the statusType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Store name="Store">Store</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Store attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TenderType name="TenderType">TenderType</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TenderType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Terminal name="Terminal">Terminal</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Terminal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionId name="TransactionId">TransactionId</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionStatus name="TransactionStatus">TransactionStatus</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#TransTime name="TransTime">TransTime</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.dataFormat.time**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

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

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailChannelTableRelationshipId name="Relationship_RetailChannelTableRelationshipId">Relationship_RetailChannelTableRelationshipId</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailChannelTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailChannelTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Main/RetailChannelTable.cdm.json/RetailChannelTable</a></td><td><a href="../Main/RetailChannelTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailStatementLineRelationshipId name="Relationship_RetailStatementLineRelationshipId">Relationship_RetailStatementLineRelationshipId</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailStatementLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetLine/RetailStatementLine.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/WorksheetLine/RetailStatementLine.cdm.json/RetailStatementLine</a></td><td><a href="../WorksheetLine/RetailStatementLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailStatementTableRelationshipId name="Relationship_RetailStatementTableRelationshipId">Relationship_RetailStatementTableRelationshipId</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailStatementTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/RetailStatementTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/WorksheetHeader/RetailStatementTable.cdm.json/RetailStatementTable</a></td><td><a href="../WorksheetHeader/RetailStatementTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailStatementTransRelationshipId name="Relationship_RetailStatementTransRelationshipId">Relationship_RetailStatementTransRelationshipId</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailStatementTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailStatementTrans.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Transaction/RetailStatementTrans.cdm.json/RetailStatementTrans</a></td><td><a href="RetailStatementTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailStoreTableRelationshipId name="Relationship_RetailStoreTableRelationshipId">Relationship_RetailStoreTableRelationshipId</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailStoreTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailStoreTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Main/RetailStoreTable.cdm.json/RetailStoreTable</a></td><td><a href="../Main/RetailStoreTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailStoreWorkShiftTableRelationshipId name="Relationship_RetailStoreWorkShiftTableRelationshipId">Relationship_RetailStoreWorkShiftTableRelationshipId</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailStoreWorkShiftTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/RetailStoreWorkShiftTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/WorksheetHeader/RetailStoreWorkShiftTable.cdm.json/RetailStoreWorkShiftTable</a></td><td><a href="../WorksheetHeader/RetailStoreWorkShiftTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTenderTypeCardTableRelationshipId name="Relationship_RetailTenderTypeCardTableRelationshipId">Relationship_RetailTenderTypeCardTableRelationshipId</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTenderTypeCardTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailTenderTypeCardTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Main/RetailTenderTypeCardTable.cdm.json/RetailTenderTypeCardTable</a></td><td><a href="../Main/RetailTenderTypeCardTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTenderTypeTableRelationshipId name="Relationship_RetailTenderTypeTableRelationshipId">Relationship_RetailTenderTypeTableRelationshipId</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTenderTypeTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailTenderTypeTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Main/RetailTenderTypeTable.cdm.json/RetailTenderTypeTable</a></td><td><a href="../Main/RetailTenderTypeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTerminalTableRelationshipId name="Relationship_RetailTerminalTableRelationshipId">Relationship_RetailTerminalTableRelationshipId</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTerminalTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailTerminalTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Main/RetailTerminalTable.cdm.json/RetailTerminalTable</a></td><td><a href="../Main/RetailTerminalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTransactionTableRelationshipId name="Relationship_RetailTransactionTableRelationshipId">Relationship_RetailTransactionTableRelationshipId</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTransactionTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailTransactionTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Transaction/RetailTransactionTable.cdm.json/RetailTransactionTable</a></td><td><a href="RetailTransactionTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/RetailTransactionSafeTenderTrans (this entity)  

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
