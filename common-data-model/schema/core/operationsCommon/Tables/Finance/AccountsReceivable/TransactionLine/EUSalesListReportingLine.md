---
title: EUSalesListReportingLine - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# EU sales list reporting line

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/AccountsReceivable/TransactionLine/EUSalesListReportingLine.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EUSalesListReportingLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>EU sales list reporting line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[CountryRegionId](#CountryRegionId)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[AccountNum](#AccountNum)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[Cancelled](#Cancelled)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[Corrected](#Corrected)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[CorrectedServices_ES](#CorrectedServices_ES)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[CorrectionCountry_FI](#CorrectionCountry_FI)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[CorrectionListcode_FI](#CorrectionListcode_FI)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[CorrectionMonthOrQuarter_ES](#CorrectionMonthOrQuarter_ES)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[CorrectionMonthOrQuarterServices_ES](#CorrectionMonthOrQuarterServices_ES)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[CorrectionPeriod_ES](#CorrectionPeriod_ES)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[CorrectionPeriodServices_ES](#CorrectionPeriodServices_ES)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[CorrectionVATNum_FI](#CorrectionVATNum_FI)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[CorrectionYear_ES](#CorrectionYear_ES)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[CorrectionYearServices_ES](#CorrectionYearServices_ES)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[DeclarationMonth_FR](#DeclarationMonth_FR)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[DeliveryCode_ES](#DeliveryCode_ES)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[Direction](#Direction)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[DispatchId](#DispatchId)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[EUSalesListReportingGroup](#EUSalesListReportingGroup)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[EUSalesListTaxCode](#EUSalesListTaxCode)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[ItemAmountMST](#ItemAmountMST)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[Listcode](#Listcode)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[Name](#Name)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[NumberOfItemInvoices_CZ](#NumberOfItemInvoices_CZ)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[NumberOfPropertyMovingInvoices_CZ](#NumberOfPropertyMovingInvoices_CZ)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[NumberOfServiceInvoices_CZ](#NumberOfServiceInvoices_CZ)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[NumberOfTriangularInvoices_CZ](#NumberOfTriangularInvoices_CZ)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[PropertyMovingAmountMST_CZ](#PropertyMovingAmountMST_CZ)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[PurchasedOnBehalfAmountMST_LV](#PurchasedOnBehalfAmountMST_LV)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[ServiceAmountMST](#ServiceAmountMST)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[StrippedVATNum](#StrippedVATNum)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[TaxPeriod_NL](#TaxPeriod_NL)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[TaxRep349AmountMstPrev_ES](#TaxRep349AmountMstPrev_ES)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[TaxRep349AmountMstPrevServices_ES](#TaxRep349AmountMstPrevServices_ES)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[TriangularAmountMST](#TriangularAmountMST)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[TriangularIntermediateAmountMST_HU](#TriangularIntermediateAmountMST_HU)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[VATNum_DE](#VATNum_DE)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[DataAreaId](#DataAreaId)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[Relationship_EUSalesListReportingGroupRelationshipId](#Relationship_EUSalesListReportingGroupRelationshipId)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[Relationship_LogisticsAddressCountryRegionRelationshipId](#Relationship_LogisticsAddressCountryRegionRelationshipId)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[Relationship_LogisticsAddressCountryRegionFIRelationshipId](#Relationship_LogisticsAddressCountryRegionFIRelationshipId)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="EUSalesListReportingLine.md" target="_blank">TransactionLine/EUSalesListReportingLine</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EUSalesListReportingLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CountryRegionId name="CountryRegionId">CountryRegionId</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

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

### <a href=#AccountNum name="AccountNum">AccountNum</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

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

### <a href=#Cancelled name="Cancelled">Cancelled</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Cancelled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Corrected name="Corrected">Corrected</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Corrected</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Corrected attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Corrected</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#CorrectedServices_ES name="CorrectedServices_ES">CorrectedServices_ES</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Services</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedServices_ES attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Services</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#CorrectionCountry_FI name="CorrectionCountry_FI">CorrectionCountry_FI</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Correction country/region</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionCountry_FI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Correction country/region</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectionListcode_FI name="CorrectionListcode_FI">CorrectionListcode_FI</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Correction list code</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionListcode_FI attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Correction list code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#CorrectionMonthOrQuarter_ES name="CorrectionMonthOrQuarter_ES">CorrectionMonthOrQuarter_ES</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionMonthOrQuarter_ES attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CorrectionMonthOrQuarterServices_ES name="CorrectionMonthOrQuarterServices_ES">CorrectionMonthOrQuarterServices_ES</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionMonthOrQuarterServices_ES attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CorrectionPeriod_ES name="CorrectionPeriod_ES">CorrectionPeriod_ES</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionPeriod_ES attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CorrectionPeriodServices_ES name="CorrectionPeriodServices_ES">CorrectionPeriodServices_ES</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionPeriodServices_ES attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CorrectionVATNum_FI name="CorrectionVATNum_FI">CorrectionVATNum_FI</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Correction tax exempt number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionVATNum_FI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Correction tax exempt number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectionYear_ES name="CorrectionYear_ES">CorrectionYear_ES</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionYear_ES attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CorrectionYearServices_ES name="CorrectionYearServices_ES">CorrectionYearServices_ES</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionYearServices_ES attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DeclarationMonth_FR name="DeclarationMonth_FR">DeclarationMonth_FR</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeclarationMonth_FR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DeliveryCode_ES name="DeliveryCode_ES">DeliveryCode_ES</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryCode_ES attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Direction name="Direction">Direction</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Direction</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Direction attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Direction</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DispatchId name="DispatchId">DispatchId</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

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

### <a href=#EUSalesListReportingGroup name="EUSalesListReportingGroup">EUSalesListReportingGroup</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EUSalesListReportingGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EUSalesListTaxCode name="EUSalesListTaxCode">EUSalesListTaxCode</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EUSalesListTaxCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemAmountMST name="ItemAmountMST">ItemAmountMST</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Items value</td></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Items value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Listcode name="Listcode">Listcode</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Listcode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberOfItemInvoices_CZ name="NumberOfItemInvoices_CZ">NumberOfItemInvoices_CZ</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberOfItemInvoices_CZ attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#NumberOfPropertyMovingInvoices_CZ name="NumberOfPropertyMovingInvoices_CZ">NumberOfPropertyMovingInvoices_CZ</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberOfPropertyMovingInvoices_CZ attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#NumberOfServiceInvoices_CZ name="NumberOfServiceInvoices_CZ">NumberOfServiceInvoices_CZ</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberOfServiceInvoices_CZ attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#NumberOfTriangularInvoices_CZ name="NumberOfTriangularInvoices_CZ">NumberOfTriangularInvoices_CZ</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberOfTriangularInvoices_CZ attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PropertyMovingAmountMST_CZ name="PropertyMovingAmountMST_CZ">PropertyMovingAmountMST_CZ</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Property movement</td></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PropertyMovingAmountMST_CZ attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Property movement</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PurchasedOnBehalfAmountMST_LV name="PurchasedOnBehalfAmountMST_LV">PurchasedOnBehalfAmountMST_LV</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchased on behalf</td></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasedOnBehalfAmountMST_LV attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchased on behalf</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ServiceAmountMST name="ServiceAmountMST">ServiceAmountMST</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Services value</td></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Services value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#StrippedVATNum name="StrippedVATNum">StrippedVATNum</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StrippedVATNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxPeriod_NL name="TaxPeriod_NL">TaxPeriod_NL</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPeriod_NL attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxRep349AmountMstPrev_ES name="TaxRep349AmountMstPrev_ES">TaxRep349AmountMstPrev_ES</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRep349AmountMstPrev_ES attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxRep349AmountMstPrevServices_ES name="TaxRep349AmountMstPrevServices_ES">TaxRep349AmountMstPrevServices_ES</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRep349AmountMstPrevServices_ES attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TriangularAmountMST name="TriangularAmountMST">TriangularAmountMST</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Triangular trade</td></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TriangularAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Triangular trade</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TriangularIntermediateAmountMST_HU name="TriangularIntermediateAmountMST_HU">TriangularIntermediateAmountMST_HU</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Triangular/intermediate role</td></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TriangularIntermediateAmountMST_HU attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Triangular/intermediate role</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#VATNum_DE name="VATNum_DE">VATNum_DE</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATNum_DE attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

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

### <a href=#Relationship_EUSalesListReportingGroupRelationshipId name="Relationship_EUSalesListReportingGroupRelationshipId">Relationship_EUSalesListReportingGroupRelationshipId</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EUSalesListReportingGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../TransactionHeader/EUSalesListReportingGroup.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/TransactionHeader/EUSalesListReportingGroup.cdm.json/EUSalesListReportingGroup</a></td><td><a href="../TransactionHeader/EUSalesListReportingGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LogisticsAddressCountryRegionRelationshipId name="Relationship_LogisticsAddressCountryRegionRelationshipId">Relationship_LogisticsAddressCountryRegionRelationshipId</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

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

### <a href=#Relationship_LogisticsAddressCountryRegionFIRelationshipId name="Relationship_LogisticsAddressCountryRegionFIRelationshipId">Relationship_LogisticsAddressCountryRegionFIRelationshipId</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

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

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: TransactionLine/EUSalesListReportingLine (this entity)  

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
