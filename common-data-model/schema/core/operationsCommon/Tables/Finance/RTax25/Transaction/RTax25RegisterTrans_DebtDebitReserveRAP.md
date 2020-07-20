---
title: RTax25RegisterTrans_DebtDebitReserveRAP in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Tax register line in Transaction(RTax25RegisterTrans_DebtDebitReserveRAP)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/RTax25/Transaction/RTax25RegisterTrans_DebtDebitReserveRAP.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RTax25RegisterTrans_DebtDebitReserveRAP/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax register line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[BlockType](#BlockType)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[Corrected](#Corrected)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[Expend](#Expend)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[From90](#From90)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[JournalTransRefRecId](#JournalTransRefRecId)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[Life45_90](#Life45_90)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[LineDescription](#LineDescription)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[LineNumber](#LineNumber)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[ManualInput](#ManualInput)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[PercentFromReceipt](#PercentFromReceipt)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[ProfitAmount](#ProfitAmount)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[ReceivableAmount](#ReceivableAmount)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[RefRecId](#RefRecId)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[RefTableId](#RefTableId)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[Remainder](#Remainder)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[ReservationVoucher](#ReservationVoucher)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[Reserve](#Reserve)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[Revenue](#Revenue)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[RTax25ProfitTable](#RTax25ProfitTable)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[SaleReceipt](#SaleReceipt)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[TransDate](#TransDate)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[DebtReserved](#DebtReserved)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[From0](#From0)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[Hopeless](#Hopeless)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[DataAreaId](#DataAreaId)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[Relationship_CustTransRelationshipId](#Relationship_CustTransRelationshipId)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[Relationship_RTax25ProfitTableRelationshipId](#Relationship_RTax25ProfitTableRelationshipId)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[Relationship_RTax25RegisterJournalTransRecIdRelationshipId](#Relationship_RTax25RegisterJournalTransRecIdRelationshipId)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RTax25RegisterTrans_DebtDebitReserveRAP.md" target="_blank">Transaction/RTax25RegisterTrans_DebtDebitReserveRAP</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RTax25RegisterTrans_DebtDebitReserveRAP/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BlockType name="BlockType">BlockType</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Line type</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BlockType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Line type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Corrected name="Corrected">Corrected</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Corrected</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Corrected attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Corrected</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Expend name="Expend">Expend</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expense</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Expend attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Expense</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#From90 name="From90">From90</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the From90 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#JournalTransRefRecId name="JournalTransRefRecId">JournalTransRefRecId</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalTransRefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Life45_90 name="Life45_90">Life45_90</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Life45_90 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LineDescription name="LineDescription">LineDescription</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ManualInput name="ManualInput">ManualInput</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Manual data input</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManualInput attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Manual data input</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PercentFromReceipt name="PercentFromReceipt">PercentFromReceipt</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Percent from receipt</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PercentFromReceipt attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Percent from receipt</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ProfitAmount name="ProfitAmount">ProfitAmount</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfitAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReceivableAmount name="ReceivableAmount">ReceivableAmount</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accounts receivable amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivableAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Accounts receivable amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RefRecId name="RefRecId">RefRecId</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RefTableId name="RefTableId">RefTableId</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Remainder name="Remainder">Remainder</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Remainder</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Remainder attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Remainder</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReservationVoucher name="ReservationVoucher">ReservationVoucher</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReservationVoucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Reserve name="Reserve">Reserve</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reserve</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Reserve attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reserve</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Revenue name="Revenue">Revenue</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reserve limit</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Revenue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reserve limit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RTax25ProfitTable name="RTax25ProfitTable">RTax25ProfitTable</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SaleReceipt name="SaleReceipt">SaleReceipt</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Revenue</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SaleReceipt attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Revenue</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#DebtReserved name="DebtReserved">DebtReserved</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DebtReserved attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#From0 name="From0">From0</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the From0 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Hopeless name="Hopeless">Hopeless</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Hopeless attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

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

### <a href=#Relationship_CustTransRelationshipId name="Relationship_CustTransRelationshipId">Relationship_CustTransRelationshipId</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Transaction/CustTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Transaction/CustTrans.cdm.json/CustTrans</a></td><td><a href="../../AccountsReceivable/Transaction/CustTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25ProfitTableRelationshipId name="Relationship_RTax25ProfitTableRelationshipId">Relationship_RTax25ProfitTableRelationshipId</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25ProfitTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/RTax25ProfitTable.md" target="_blank">/core/operationsCommon/Tables/Finance/RTax25/Group/RTax25ProfitTable.cdm.json/RTax25ProfitTable</a></td><td><a href="../Group/RTax25ProfitTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25RegisterJournalTransRecIdRelationshipId name="Relationship_RTax25RegisterJournalTransRecIdRelationshipId">Relationship_RTax25RegisterJournalTransRecIdRelationshipId</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25RegisterJournalTransRecIdRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetLine/RTax25RegisterJournalTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/RTax25/WorksheetLine/RTax25RegisterJournalTrans.cdm.json/RTax25RegisterJournalTrans</a></td><td><a href="../WorksheetLine/RTax25RegisterJournalTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/RTax25RegisterTrans_DebtDebitReserveRAP (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
