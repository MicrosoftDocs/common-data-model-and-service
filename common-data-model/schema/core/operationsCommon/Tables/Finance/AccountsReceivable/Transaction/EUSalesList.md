---
title: EUSalesList - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# EUSalesList

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/AccountsReceivable/Transaction/EUSalesList.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EUSalesList/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[AccountNum](#AccountNum)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[AmountMST](#AmountMST)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[ClosingDate](#ClosingDate)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[Corrected](#Corrected)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[CorrectedServices](#CorrectedServices)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[CorrectionDeclarationType_BE](#CorrectionDeclarationType_BE)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[CorrectionMonthOrQuarter](#CorrectionMonthOrQuarter)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[CorrectionMonthOrQuarterServices](#CorrectionMonthOrQuarterServices)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[CorrectionPeriod](#CorrectionPeriod)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[CorrectionPeriodServices](#CorrectionPeriodServices)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[CorrectionSign](#CorrectionSign)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[CorrectionSignServices](#CorrectionSignServices)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[CorrectionWrongAmount_HU](#CorrectionWrongAmount_HU)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[CorrectionWrongPeriod_HU](#CorrectionWrongPeriod_HU)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[CorrectionWrongRegNum_HU](#CorrectionWrongRegNum_HU)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[CorrectionYear](#CorrectionYear)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[CorrectionYearServices](#CorrectionYearServices)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[CountryRegionId](#CountryRegionId)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[DeliveryCode_ES](#DeliveryCode_ES)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[Direction](#Direction)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[DispatchId](#DispatchId)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[InvestmentAmountMST](#InvestmentAmountMST)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[Invoice](#Invoice)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[IsSettlement](#IsSettlement)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[Listcode](#Listcode)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[Log](#Log)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[NotAssignedAmountMST](#NotAssignedAmountMST)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[OriginalRecId](#OriginalRecId)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[SeqNum](#SeqNum)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[ServiceAmountMST](#ServiceAmountMST)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[Status](#Status)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[TaxRep349AmountMstPrev](#TaxRep349AmountMstPrev)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[TaxRep349AmountMstPrevServices](#TaxRep349AmountMstPrevServices)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[TransDate](#TransDate)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[TransQuarter](#TransQuarter)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[TransYear](#TransYear)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[VATNum](#VATNum)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[TaxID](#TaxID)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[TaxReportingCurrencyCode](#TaxReportingCurrencyCode)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[DataAreaId](#DataAreaId)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[Relationship_CustTable_AccountNumRelationshipId](#Relationship_CustTable_AccountNumRelationshipId)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[Relationship_LogisticsAddressCountryRegionRelationshipId](#Relationship_LogisticsAddressCountryRegionRelationshipId)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[Relationship_VendTable_AccountNumRelationshipId](#Relationship_VendTable_AccountNumRelationshipId)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[Relationship_LogisticsAddressCountryRegionFIRelationshipId](#Relationship_LogisticsAddressCountryRegionFIRelationshipId)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[Relationship_TaxIDRelationshipId](#Relationship_TaxIDRelationshipId)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[Relationship_ReportingCurrencyCodeRelationshipId](#Relationship_ReportingCurrencyCodeRelationshipId)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="EUSalesList.md" target="_blank">Transaction/EUSalesList</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EUSalesList/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountNum name="AccountNum">AccountNum</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountMST name="AmountMST">AmountMST</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ClosingDate name="ClosingDate">ClosingDate</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClosingDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Corrected name="Corrected">Corrected</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Corrected attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CorrectedServices name="CorrectedServices">CorrectedServices</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedServices attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CorrectionDeclarationType_BE name="CorrectionDeclarationType_BE">CorrectionDeclarationType_BE</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionDeclarationType_BE attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CorrectionMonthOrQuarter name="CorrectionMonthOrQuarter">CorrectionMonthOrQuarter</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionMonthOrQuarter attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CorrectionMonthOrQuarterServices name="CorrectionMonthOrQuarterServices">CorrectionMonthOrQuarterServices</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionMonthOrQuarterServices attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CorrectionPeriod name="CorrectionPeriod">CorrectionPeriod</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionPeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CorrectionPeriodServices name="CorrectionPeriodServices">CorrectionPeriodServices</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionPeriodServices attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CorrectionSign name="CorrectionSign">CorrectionSign</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionSign attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CorrectionSignServices name="CorrectionSignServices">CorrectionSignServices</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionSignServices attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CorrectionWrongAmount_HU name="CorrectionWrongAmount_HU">CorrectionWrongAmount_HU</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionWrongAmount_HU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CorrectionWrongPeriod_HU name="CorrectionWrongPeriod_HU">CorrectionWrongPeriod_HU</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionWrongPeriod_HU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CorrectionWrongRegNum_HU name="CorrectionWrongRegNum_HU">CorrectionWrongRegNum_HU</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionWrongRegNum_HU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CorrectionYear name="CorrectionYear">CorrectionYear</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionYear attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CorrectionYearServices name="CorrectionYearServices">CorrectionYearServices</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionYearServices attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CountryRegionId name="CountryRegionId">CountryRegionId</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryCode_ES name="DeliveryCode_ES">DeliveryCode_ES</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryCode_ES attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Direction name="Direction">Direction</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Direction attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DispatchId name="DispatchId">DispatchId</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DispatchId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvestmentAmountMST name="InvestmentAmountMST">InvestmentAmountMST</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvestmentAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Invoice name="Invoice">Invoice</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Invoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSettlement name="IsSettlement">IsSettlement</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSettlement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Listcode name="Listcode">Listcode</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Listcode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Log name="Log">Log</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Log attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NotAssignedAmountMST name="NotAssignedAmountMST">NotAssignedAmountMST</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NotAssignedAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#OriginalRecId name="OriginalRecId">OriginalRecId</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SeqNum name="SeqNum">SeqNum</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SeqNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ServiceAmountMST name="ServiceAmountMST">ServiceAmountMST</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Status name="Status">Status</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxRep349AmountMstPrev name="TaxRep349AmountMstPrev">TaxRep349AmountMstPrev</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRep349AmountMstPrev attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxRep349AmountMstPrevServices name="TaxRep349AmountMstPrevServices">TaxRep349AmountMstPrevServices</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRep349AmountMstPrevServices attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#TransQuarter name="TransQuarter">TransQuarter</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransQuarter attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TransYear name="TransYear">TransYear</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransYear attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VATNum name="VATNum">VATNum</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxID name="TaxID">TaxID</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxID attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxReportingCurrencyCode name="TaxReportingCurrencyCode">TaxReportingCurrencyCode</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReportingCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/EUSalesList (this entity)  

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

### <a href=#Relationship_CustTable_AccountNumRelationshipId name="Relationship_CustTable_AccountNumRelationshipId">Relationship_CustTable_AccountNumRelationshipId</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTable_AccountNumRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LogisticsAddressCountryRegionRelationshipId name="Relationship_LogisticsAddressCountryRegionRelationshipId">Relationship_LogisticsAddressCountryRegionRelationshipId</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsAddressCountryRegionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/LogisticsAddressCountryRegion.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Group/LogisticsAddressCountryRegion.cdm.json/LogisticsAddressCountryRegion</a></td><td><a href="../../../Common/GAB/Group/LogisticsAddressCountryRegion.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTable_AccountNumRelationshipId name="Relationship_VendTable_AccountNumRelationshipId">Relationship_VendTable_AccountNumRelationshipId</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTable_AccountNumRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LogisticsAddressCountryRegionFIRelationshipId name="Relationship_LogisticsAddressCountryRegionFIRelationshipId">Relationship_LogisticsAddressCountryRegionFIRelationshipId</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsAddressCountryRegionFIRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/LogisticsAddressCountryRegion.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Group/LogisticsAddressCountryRegion.cdm.json/LogisticsAddressCountryRegion</a></td><td><a href="../../../Common/GAB/Group/LogisticsAddressCountryRegion.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxIDRelationshipId name="Relationship_TaxIDRelationshipId">Relationship_TaxIDRelationshipId</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxIDRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Miscellaneous/TaxRegistration.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Miscellaneous/TaxRegistration.cdm.json/TaxRegistration</a></td><td><a href="../../Tax/Miscellaneous/TaxRegistration.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReportingCurrencyCodeRelationshipId name="Relationship_ReportingCurrencyCodeRelationshipId">Relationship_ReportingCurrencyCodeRelationshipId</a>

First included in: Transaction/EUSalesList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportingCurrencyCodeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/EUSalesList (this entity)  

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
