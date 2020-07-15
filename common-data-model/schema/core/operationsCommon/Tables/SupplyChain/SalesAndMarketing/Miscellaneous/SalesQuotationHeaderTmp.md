---
title: SalesQuotationHeaderTmp in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/14/2020
ms.author: nebanfic
---

# Quotations in Miscellaneous(SalesQuotationHeaderTmp)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Miscellaneous/SalesQuotationHeaderTmp.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SalesQuotationHeaderTmp/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Quotations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[CashDisc](#CashDisc)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[CashDiscEuro](#CashDiscEuro)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[CashDiscOnInvoice](#CashDiscOnInvoice)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[CashDiscPercent](#CashDiscPercent)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[CashDiscTxt](#CashDiscTxt)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[CompanyAddress](#CompanyAddress)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[CompanyBankAccountName](#CompanyBankAccountName)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[CompanyBankAccountNum](#CompanyBankAccountNum)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[CompanyBankAccountRegNum](#CompanyBankAccountRegNum)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[CompanyCommercialRegister](#CompanyCommercialRegister)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[CompanyCommercialRegisterInsetNumber](#CompanyCommercialRegisterInsetNumber)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[CompanyCommercialRegisterSection](#CompanyCommercialRegisterSection)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[CompanyCoRegNum](#CompanyCoRegNum)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[CompanyCurrencyCode](#CompanyCurrencyCode)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[CompanyEmail](#CompanyEmail)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[CompanyEnterpriseNumber](#CompanyEnterpriseNumber)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[CompanyGiro](#CompanyGiro)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[CompanyLogo](#CompanyLogo)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[CompanyName](#CompanyName)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[CompanyPhone](#CompanyPhone)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[CompanyRegNum](#CompanyRegNum)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[CompanyTelefax](#CompanyTelefax)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[CurrencyCode](#CurrencyCode)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[CustomerRef](#CustomerRef)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[DeliveryAddress](#DeliveryAddress)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[DeliveryName](#DeliveryName)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[DocuConclusion](#DocuConclusion)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[DocuIntro](#DocuIntro)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[DocuRefMainNotes](#DocuRefMainNotes)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[DocuTitle](#DocuTitle)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[EndDisc](#EndDisc)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[EndDiscEuro](#EndDiscEuro)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[Enterpriseregister_NO](#Enterpriseregister_NO)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[EuroCurrencyCode](#EuroCurrencyCode)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[FormLetterRemarks](#FormLetterRemarks)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[NetAmount](#NetAmount)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[NetAmountEuro](#NetAmountEuro)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[OrderAccountRegNum](#OrderAccountRegNum)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[OrderAccountVATNum](#OrderAccountVATNum)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[PaymentCode](#PaymentCode)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[PrePrintLevel](#PrePrintLevel)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[PrintLogo](#PrintLogo)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[PrintTaxAmountSalesExchangeRate](#PrintTaxAmountSalesExchangeRate)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[PurchaseOrder](#PurchaseOrder)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[QuotationAmount](#QuotationAmount)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[QuotationAmountEuro](#QuotationAmountEuro)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[QuotationDate](#QuotationDate)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[QuotationDocNum](#QuotationDocNum)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[QuotationId](#QuotationId)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[RespiteDate](#RespiteDate)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[RoundOff](#RoundOff)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[RoundOffEuro](#RoundOffEuro)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[SalesAdministrator](#SalesAdministrator)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[SalesBalance](#SalesBalance)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[SalesBalanceEuro](#SalesBalanceEuro)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[SalesId](#SalesId)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[SalesTaxExchangeRate](#SalesTaxExchangeRate)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[SumMarkup](#SumMarkup)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[SumMarkupEuro](#SumMarkupEuro)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[SumTax](#SumTax)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[SumTaxEuro](#SumTaxEuro)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[SumTaxMST](#SumTaxMST)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[TaxableBalance](#TaxableBalance)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[TaxableBalanceEuro](#TaxableBalanceEuro)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[TaxFreeBalance](#TaxFreeBalance)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[TaxFreeBalanceEuro](#TaxFreeBalanceEuro)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[TaxPrintTaxFreeBalance](#TaxPrintTaxFreeBalance)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[TaxSpecPrintLevel](#TaxSpecPrintLevel)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[TotalTaxBaseAmount](#TotalTaxBaseAmount)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[TotalTaxBaseAmountEuro](#TotalTaxBaseAmountEuro)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[CompanyVATNum](#CompanyVATNum)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[ShowCompanyVATNum](#ShowCompanyVATNum)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[CustQuotationConfirmJour](#CustQuotationConfirmJour)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[CustQuotationJour](#CustQuotationJour)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[DataAreaId](#DataAreaId)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[Relationship_CompanyCurrencyRelationshipId](#Relationship_CompanyCurrencyRelationshipId)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[Relationship_EuroCurrencyRelationshipId](#Relationship_EuroCurrencyRelationshipId)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[Relationship_SalesTableRelationshipId](#Relationship_SalesTableRelationshipId)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[Relationship_CustQuotationConfirmJourRelationshipId](#Relationship_CustQuotationConfirmJourRelationshipId)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[Relationship_CustQuotationJourRelationshipId](#Relationship_CustQuotationJourRelationshipId)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="SalesQuotationHeaderTmp.md" target="_blank">Miscellaneous/SalesQuotationHeaderTmp</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SalesQuotationHeaderTmp/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CashDisc name="CashDisc">CashDisc</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDisc attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CashDiscEuro name="CashDiscEuro">CashDiscEuro</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CashDiscOnInvoice name="CashDiscOnInvoice">CashDiscOnInvoice</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscOnInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CashDiscPercent name="CashDiscPercent">CashDiscPercent</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscPercent attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CashDiscTxt name="CashDiscTxt">CashDiscTxt</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscTxt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyAddress name="CompanyAddress">CompanyAddress</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyBankAccountName name="CompanyBankAccountName">CompanyBankAccountName</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyBankAccountName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyBankAccountNum name="CompanyBankAccountNum">CompanyBankAccountNum</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyBankAccountNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyBankAccountRegNum name="CompanyBankAccountRegNum">CompanyBankAccountRegNum</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyBankAccountRegNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyCommercialRegister name="CompanyCommercialRegister">CompanyCommercialRegister</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyCommercialRegister attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyCommercialRegisterInsetNumber name="CompanyCommercialRegisterInsetNumber">CompanyCommercialRegisterInsetNumber</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyCommercialRegisterInsetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyCommercialRegisterSection name="CompanyCommercialRegisterSection">CompanyCommercialRegisterSection</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyCommercialRegisterSection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyCoRegNum name="CompanyCoRegNum">CompanyCoRegNum</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyCoRegNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyCurrencyCode name="CompanyCurrencyCode">CompanyCurrencyCode</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyEmail name="CompanyEmail">CompanyEmail</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyEmail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyEnterpriseNumber name="CompanyEnterpriseNumber">CompanyEnterpriseNumber</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyEnterpriseNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyGiro name="CompanyGiro">CompanyGiro</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyGiro attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyLogo name="CompanyLogo">CompanyLogo</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyLogo attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyName name="CompanyName">CompanyName</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyPhone name="CompanyPhone">CompanyPhone</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyPhone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyRegNum name="CompanyRegNum">CompanyRegNum</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyRegNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyTelefax name="CompanyTelefax">CompanyTelefax</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyTelefax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerRef name="CustomerRef">CustomerRef</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerRef attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddress name="DeliveryAddress">DeliveryAddress</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryName name="DeliveryName">DeliveryName</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocuConclusion name="DocuConclusion">DocuConclusion</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuConclusion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocuIntro name="DocuIntro">DocuIntro</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuIntro attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocuRefMainNotes name="DocuRefMainNotes">DocuRefMainNotes</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuRefMainNotes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocuTitle name="DocuTitle">DocuTitle</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuTitle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndDisc name="EndDisc">EndDisc</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDisc attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#EndDiscEuro name="EndDiscEuro">EndDiscEuro</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDiscEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Enterpriseregister_NO name="Enterpriseregister_NO">Enterpriseregister_NO</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Enterpriseregister_NO attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EuroCurrencyCode name="EuroCurrencyCode">EuroCurrencyCode</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EuroCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormLetterRemarks name="FormLetterRemarks">FormLetterRemarks</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormLetterRemarks attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NetAmount name="NetAmount">NetAmount</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#NetAmountEuro name="NetAmountEuro">NetAmountEuro</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetAmountEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#OrderAccountRegNum name="OrderAccountRegNum">OrderAccountRegNum</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderAccountRegNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderAccountVATNum name="OrderAccountVATNum">OrderAccountVATNum</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderAccountVATNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentCode name="PaymentCode">PaymentCode</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrePrintLevel name="PrePrintLevel">PrePrintLevel</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrePrintLevel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintLogo name="PrintLogo">PrintLogo</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintLogo attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintTaxAmountSalesExchangeRate name="PrintTaxAmountSalesExchangeRate">PrintTaxAmountSalesExchangeRate</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintTaxAmountSalesExchangeRate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PurchaseOrder name="PurchaseOrder">PurchaseOrder</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationAmount name="QuotationAmount">QuotationAmount</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#QuotationAmountEuro name="QuotationAmountEuro">QuotationAmountEuro</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationAmountEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#QuotationDate name="QuotationDate">QuotationDate</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#QuotationDocNum name="QuotationDocNum">QuotationDocNum</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationDocNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationId name="QuotationId">QuotationId</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RespiteDate name="RespiteDate">RespiteDate</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RespiteDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#RoundOff name="RoundOff">RoundOff</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundOff attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RoundOffEuro name="RoundOffEuro">RoundOffEuro</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundOffEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesAdministrator name="SalesAdministrator">SalesAdministrator</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesAdministrator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesBalance name="SalesBalance">SalesBalance</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesBalance attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesBalanceEuro name="SalesBalanceEuro">SalesBalanceEuro</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesBalanceEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesId name="SalesId">SalesId</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxExchangeRate name="SalesTaxExchangeRate">SalesTaxExchangeRate</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxExchangeRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SumMarkup name="SumMarkup">SumMarkup</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumMarkup attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SumMarkupEuro name="SumMarkupEuro">SumMarkupEuro</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumMarkupEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SumTax name="SumTax">SumTax</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SumTaxEuro name="SumTaxEuro">SumTaxEuro</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumTaxEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SumTaxMST name="SumTaxMST">SumTaxMST</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumTaxMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxableBalance name="TaxableBalance">TaxableBalance</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxableBalance attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxableBalanceEuro name="TaxableBalanceEuro">TaxableBalanceEuro</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxableBalanceEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxFreeBalance name="TaxFreeBalance">TaxFreeBalance</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxFreeBalance attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxFreeBalanceEuro name="TaxFreeBalanceEuro">TaxFreeBalanceEuro</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxFreeBalanceEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxPrintTaxFreeBalance name="TaxPrintTaxFreeBalance">TaxPrintTaxFreeBalance</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPrintTaxFreeBalance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxSpecPrintLevel name="TaxSpecPrintLevel">TaxSpecPrintLevel</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxSpecPrintLevel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TotalTaxBaseAmount name="TotalTaxBaseAmount">TotalTaxBaseAmount</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalTaxBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalTaxBaseAmountEuro name="TotalTaxBaseAmountEuro">TotalTaxBaseAmountEuro</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalTaxBaseAmountEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CompanyVATNum name="CompanyVATNum">CompanyVATNum</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyVATNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowCompanyVATNum name="ShowCompanyVATNum">ShowCompanyVATNum</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowCompanyVATNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CustQuotationConfirmJour name="CustQuotationConfirmJour">CustQuotationConfirmJour</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustQuotationConfirmJour attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustQuotationJour name="CustQuotationJour">CustQuotationJour</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustQuotationJour attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

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

### <a href=#Relationship_CompanyCurrencyRelationshipId name="Relationship_CompanyCurrencyRelationshipId">Relationship_CompanyCurrencyRelationshipId</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyCurrencyRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

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

### <a href=#Relationship_EuroCurrencyRelationshipId name="Relationship_EuroCurrencyRelationshipId">Relationship_EuroCurrencyRelationshipId</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EuroCurrencyRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SalesTableRelationshipId name="Relationship_SalesTableRelationshipId">Relationship_SalesTableRelationshipId</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/SalesTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/SalesTable.cdm.json/SalesTable</a></td><td><a href="../WorksheetHeader/SalesTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustQuotationConfirmJourRelationshipId name="Relationship_CustQuotationConfirmJourRelationshipId">Relationship_CustQuotationConfirmJourRelationshipId</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustQuotationConfirmJourRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/CustQuotationConfirmJour.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Transaction/CustQuotationConfirmJour.cdm.json/CustQuotationConfirmJour</a></td><td><a href="../Transaction/CustQuotationConfirmJour.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustQuotationJourRelationshipId name="Relationship_CustQuotationJourRelationshipId">Relationship_CustQuotationJourRelationshipId</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustQuotationJourRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/CustQuotationJour.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Transaction/CustQuotationJour.cdm.json/CustQuotationJour</a></td><td><a href="../Transaction/CustQuotationJour.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/SalesQuotationHeaderTmp (this entity)  

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
