---
title: RetailStatementTrans in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Statement journal transactions in Transaction(RetailStatementTrans)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Transaction/RetailStatementTrans.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailStatementTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Statement journal transactions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[addedToDrawer](#addedToDrawer)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[bankedAmount](#bankedAmount)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[bankedAmountMST](#bankedAmountMST)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[bankedAmountStore](#bankedAmountStore)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[cardFeeAmount](#cardFeeAmount)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[cardTypeId](#cardTypeId)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[CashLaterReturnedAmountCur_RU](#CashLaterReturnedAmountCur_RU)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[changeTender](#changeTender)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[countedAmount](#countedAmount)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[countedAmountMST](#countedAmountMST)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[countedAmountStore](#countedAmountStore)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[currency](#currency)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[DefaultDimension](#DefaultDimension)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[differenceAmount](#differenceAmount)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[differenceAmountMST](#differenceAmountMST)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[differenceAmountStore](#differenceAmountStore)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[inDrawerAtEndOfDay](#inDrawerAtEndOfDay)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[lineNum](#lineNum)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[orderInvoiceAmount](#orderInvoiceAmount)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[orderInvoiceAmountMST](#orderInvoiceAmountMST)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[postedDate](#postedDate)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[realExchRate](#realExchRate)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[removedFromDrawer](#removedFromDrawer)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[replicationCounter](#replicationCounter)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[safeAmount](#safeAmount)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[safeAmountMST](#safeAmountMST)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[safeAmountStore](#safeAmountStore)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[staffId](#staffId)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[statementCode](#statementCode)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[statementId](#statementId)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[storeExchRate](#storeExchRate)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[storeId](#storeId)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[tenderTypeId](#tenderTypeId)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[terminalId](#terminalId)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[transAmount](#transAmount)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[transAmountInMST](#transAmountInMST)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[transAmountStore](#transAmountStore)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[uniqueShiftId](#uniqueShiftId)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[DataAreaId](#DataAreaId)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[Relationship_DimensionAttributeValueSetRelationshipId](#Relationship_DimensionAttributeValueSetRelationshipId)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[Relationship_RetailCashDeclarationRelationshipId](#Relationship_RetailCashDeclarationRelationshipId)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[Relationship_RetailStatementTableRelationshipId](#Relationship_RetailStatementTableRelationshipId)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[Relationship_RetailStoreTableRelationshipId](#Relationship_RetailStoreTableRelationshipId)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[Relationship_RetailTenderTypeCardTableRelationshipId](#Relationship_RetailTenderTypeCardTableRelationshipId)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[Relationship_RetailTenderTypeTableRelationshipId](#Relationship_RetailTenderTypeTableRelationshipId)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[Relationship_RetailTerminalTableRelationshipId](#Relationship_RetailTerminalTableRelationshipId)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RetailStatementTrans.md" target="_blank">Transaction/RetailStatementTrans</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailStatementTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#addedToDrawer name="addedToDrawer">addedToDrawer</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the addedToDrawer attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#bankedAmount name="bankedAmount">bankedAmount</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the bankedAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#bankedAmountMST name="bankedAmountMST">bankedAmountMST</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the bankedAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#bankedAmountStore name="bankedAmountStore">bankedAmountStore</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the bankedAmountStore attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#cardFeeAmount name="cardFeeAmount">cardFeeAmount</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the cardFeeAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#cardTypeId name="cardTypeId">cardTypeId</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the cardTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashLaterReturnedAmountCur_RU name="CashLaterReturnedAmountCur_RU">CashLaterReturnedAmountCur_RU</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Returned amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashLaterReturnedAmountCur_RU attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Returned amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#changeTender name="changeTender">changeTender</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the changeTender attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#countedAmount name="countedAmount">countedAmount</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the countedAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#countedAmountMST name="countedAmountMST">countedAmountMST</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the countedAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#countedAmountStore name="countedAmountStore">countedAmountStore</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the countedAmountStore attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#currency name="currency">currency</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the currency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#differenceAmount name="differenceAmount">differenceAmount</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the differenceAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#differenceAmountMST name="differenceAmountMST">differenceAmountMST</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the differenceAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#differenceAmountStore name="differenceAmountStore">differenceAmountStore</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the differenceAmountStore attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#inDrawerAtEndOfDay name="inDrawerAtEndOfDay">inDrawerAtEndOfDay</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the inDrawerAtEndOfDay attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#lineNum name="lineNum">lineNum</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the lineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#orderInvoiceAmount name="orderInvoiceAmount">orderInvoiceAmount</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the orderInvoiceAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#orderInvoiceAmountMST name="orderInvoiceAmountMST">orderInvoiceAmountMST</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the orderInvoiceAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#postedDate name="postedDate">postedDate</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the postedDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#realExchRate name="realExchRate">realExchRate</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the realExchRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#removedFromDrawer name="removedFromDrawer">removedFromDrawer</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the removedFromDrawer attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#replicationCounter name="replicationCounter">replicationCounter</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the replicationCounter attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#safeAmount name="safeAmount">safeAmount</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the safeAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#safeAmountMST name="safeAmountMST">safeAmountMST</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the safeAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#safeAmountStore name="safeAmountStore">safeAmountStore</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the safeAmountStore attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#staffId name="staffId">staffId</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the staffId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#statementCode name="statementCode">statementCode</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the statementCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#statementId name="statementId">statementId</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the statementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#storeExchRate name="storeExchRate">storeExchRate</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the storeExchRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#storeId name="storeId">storeId</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the storeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#tenderTypeId name="tenderTypeId">tenderTypeId</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the tenderTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#terminalId name="terminalId">terminalId</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the terminalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#transAmount name="transAmount">transAmount</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the transAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#transAmountInMST name="transAmountInMST">transAmountInMST</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the transAmountInMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#transAmountStore name="transAmountStore">transAmountStore</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the transAmountStore attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#uniqueShiftId name="uniqueShiftId">uniqueShiftId</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the uniqueShiftId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/RetailStatementTrans (this entity)  

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

First included in: Transaction/RetailStatementTrans (this entity)  

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

### <a href=#Relationship_DimensionAttributeValueSetRelationshipId name="Relationship_DimensionAttributeValueSetRelationshipId">Relationship_DimensionAttributeValueSetRelationshipId</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionAttributeValueSetRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailCashDeclarationRelationshipId name="Relationship_RetailCashDeclarationRelationshipId">Relationship_RetailCashDeclarationRelationshipId</a>

First included in: Transaction/RetailStatementTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailCashDeclarationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailCashDeclaration.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Transaction/RetailCashDeclaration.cdm.json/RetailCashDeclaration</a></td><td><a href="RetailCashDeclaration.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailStatementTableRelationshipId name="Relationship_RetailStatementTableRelationshipId">Relationship_RetailStatementTableRelationshipId</a>

First included in: Transaction/RetailStatementTrans (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/RetailStatementTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/WorksheetHeader/RetailStatementTable.cdm.json/RetailStatementTable</a></td><td><a href="../WorksheetHeader/RetailStatementTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailStoreTableRelationshipId name="Relationship_RetailStoreTableRelationshipId">Relationship_RetailStoreTableRelationshipId</a>

First included in: Transaction/RetailStatementTrans (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ChannelManagement/BrickAndMortarStore/Main/RetailStoreTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Main/RetailStoreTable.cdm.json/RetailStoreTable</a></td><td><a href="../../ChannelManagement/BrickAndMortarStore/Main/RetailStoreTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTenderTypeCardTableRelationshipId name="Relationship_RetailTenderTypeCardTableRelationshipId">Relationship_RetailTenderTypeCardTableRelationshipId</a>

First included in: Transaction/RetailStatementTrans (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Payments/Main/RetailTenderTypeCardTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Payments/Main/RetailTenderTypeCardTable.cdm.json/RetailTenderTypeCardTable</a></td><td><a href="../../Payments/Main/RetailTenderTypeCardTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTenderTypeTableRelationshipId name="Relationship_RetailTenderTypeTableRelationshipId">Relationship_RetailTenderTypeTableRelationshipId</a>

First included in: Transaction/RetailStatementTrans (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Payments/Main/RetailTenderTypeTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Payments/Main/RetailTenderTypeTable.cdm.json/RetailTenderTypeTable</a></td><td><a href="../../Payments/Main/RetailTenderTypeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTerminalTableRelationshipId name="Relationship_RetailTerminalTableRelationshipId">Relationship_RetailTerminalTableRelationshipId</a>

First included in: Transaction/RetailStatementTrans (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ChannelManagement/BrickAndMortarStore/Main/RetailTerminalTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Main/RetailTerminalTable.cdm.json/RetailTerminalTable</a></td><td><a href="../../ChannelManagement/BrickAndMortarStore/Main/RetailTerminalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/RetailStatementTrans (this entity)  

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
