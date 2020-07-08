---
title: PurchPurchaseOrderHeader in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Show purchase order in Miscellaneous(PurchPurchaseOrderHeader)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Miscellaneous/PurchPurchaseOrderHeader.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchPurchaseOrderHeader/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Show purchase order</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[Amount](#Amount)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[AmountEuro](#AmountEuro)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[AmountPrepay](#AmountPrepay)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[CompanyAddress](#CompanyAddress)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[CompanyBankAccountName](#CompanyBankAccountName)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[CompanyBankAccountNum](#CompanyBankAccountNum)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[CompanyBankAccountRoutingNum](#CompanyBankAccountRoutingNum)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[CompanyCommercialRegister](#CompanyCommercialRegister)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[CompanyCommercialRegisterInsetNumber](#CompanyCommercialRegisterInsetNumber)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[CompanyCommercialRegisterSection](#CompanyCommercialRegisterSection)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[CompanyCoRegNum](#CompanyCoRegNum)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[CompanyEmail](#CompanyEmail)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[CompanyEnterpriseNumber](#CompanyEnterpriseNumber)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[CompanyGiro](#CompanyGiro)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[CompanyLogo](#CompanyLogo)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[CompanyName](#CompanyName)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[CompanyPhone](#CompanyPhone)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[CompanyRegNum](#CompanyRegNum)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[CompanyTeleFax](#CompanyTeleFax)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[ConfirmingPOMessage](#ConfirmingPOMessage)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[CurrencyCode](#CurrencyCode)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[CurrencyCodeCompany](#CurrencyCodeCompany)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[CurrencyCodeEuro](#CurrencyCodeEuro)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[DeliveryAddress](#DeliveryAddress)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[DeliveryName](#DeliveryName)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[DlvTerm](#DlvTerm)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[EnableAmountControls](#EnableAmountControls)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[EndDisc](#EndDisc)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[EndDiscEuro](#EndDiscEuro)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[FormLetterRemarksTxt](#FormLetterRemarksTxt)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[IsPrepay](#IsPrepay)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[JournalRecId](#JournalRecId)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[NetAmount](#NetAmount)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[NetAmountEuro](#NetAmountEuro)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[Notes](#Notes)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[PrePrintLevel](#PrePrintLevel)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[PrintLogo](#PrintLogo)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[PrintTaxAmountSalesExchangeRate](#PrintTaxAmountSalesExchangeRate)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[PrintTaxFreeBalance](#PrintTaxFreeBalance)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[PurchaseOrderId](#PurchaseOrderId)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[PurchId](#PurchId)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[PurchOrderDate](#PurchOrderDate)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[PurchOrderDocNum](#PurchOrderDocNum)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[ReqAttention](#ReqAttention)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[RoundOff](#RoundOff)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[RoundOffEuro](#RoundOffEuro)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[SalesOrderBalance](#SalesOrderBalance)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[SalesOrderBalanceEuro](#SalesOrderBalanceEuro)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[SalesTaxExchangeRate](#SalesTaxExchangeRate)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[SumMarkup](#SumMarkup)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[SumMarkupEuro](#SumMarkupEuro)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[SumTax](#SumTax)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[SumTaxEuro](#SumTaxEuro)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[SumTaxMST](#SumTaxMST)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[TaxableBalance](#TaxableBalance)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[TaxableBalanceEuro](#TaxableBalanceEuro)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[TaxFreeBalance](#TaxFreeBalance)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[TaxFreeBalanceEuro](#TaxFreeBalanceEuro)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[TaxSpecPrintLevel](#TaxSpecPrintLevel)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[VendAddress](#VendAddress)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[VendCoRegNum](#VendCoRegNum)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[VendName](#VendName)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[VendRegNum](#VendRegNum)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[CompanyVATNum](#CompanyVATNum)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[ShowCompanyVATNum](#ShowCompanyVATNum)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[Payment](#Payment)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[IsProForma](#IsProForma)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[DataAreaId](#DataAreaId)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[Relationship_CompanyCurrencyRelationshipId](#Relationship_CompanyCurrencyRelationshipId)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[Relationship_EuroCurrencyRelationshipId](#Relationship_EuroCurrencyRelationshipId)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[Relationship_PurchTableRelationshipId](#Relationship_PurchTableRelationshipId)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[Relationship_VendPurchOrderJourRelationshipId](#Relationship_VendPurchOrderJourRelationshipId)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[Relationship_PaymTermRelationshipId](#Relationship_PaymTermRelationshipId)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="PurchPurchaseOrderHeader.md" target="_blank">Miscellaneous/PurchPurchaseOrderHeader</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchPurchaseOrderHeader/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Amount name="Amount">Amount</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Amount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AmountEuro name="AmountEuro">AmountEuro</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AmountPrepay name="AmountPrepay">AmountPrepay</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountPrepay attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CompanyAddress name="CompanyAddress">CompanyAddress</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

### <a href=#CompanyBankAccountRoutingNum name="CompanyBankAccountRoutingNum">CompanyBankAccountRoutingNum</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyBankAccountRoutingNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyCommercialRegister name="CompanyCommercialRegister">CompanyCommercialRegister</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

### <a href=#CompanyEmail name="CompanyEmail">CompanyEmail</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

### <a href=#CompanyTeleFax name="CompanyTeleFax">CompanyTeleFax</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyTeleFax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConfirmingPOMessage name="ConfirmingPOMessage">ConfirmingPOMessage</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfirmingPOMessage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

### <a href=#CurrencyCodeCompany name="CurrencyCodeCompany">CurrencyCodeCompany</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCodeCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCodeEuro name="CurrencyCodeEuro">CurrencyCodeEuro</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCodeEuro attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddress name="DeliveryAddress">DeliveryAddress</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

### <a href=#DlvTerm name="DlvTerm">DlvTerm</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DlvTerm attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableAmountControls name="EnableAmountControls">EnableAmountControls</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableAmountControls attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EndDisc name="EndDisc">EndDisc</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

### <a href=#FormLetterRemarksTxt name="FormLetterRemarksTxt">FormLetterRemarksTxt</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormLetterRemarksTxt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrepay name="IsPrepay">IsPrepay</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrepay attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#JournalRecId name="JournalRecId">JournalRecId</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#NetAmount name="NetAmount">NetAmount</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

### <a href=#Notes name="Notes">Notes</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Notes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrePrintLevel name="PrePrintLevel">PrePrintLevel</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

### <a href=#PrintTaxFreeBalance name="PrintTaxFreeBalance">PrintTaxFreeBalance</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintTaxFreeBalance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PurchaseOrderId name="PurchaseOrderId">PurchaseOrderId</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchId name="PurchId">PurchId</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchOrderDate name="PurchOrderDate">PurchOrderDate</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchOrderDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#PurchOrderDocNum name="PurchOrderDocNum">PurchOrderDocNum</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchOrderDocNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReqAttention name="ReqAttention">ReqAttention</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqAttention attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoundOff name="RoundOff">RoundOff</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

### <a href=#SalesOrderBalance name="SalesOrderBalance">SalesOrderBalance</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderBalance attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesOrderBalanceEuro name="SalesOrderBalanceEuro">SalesOrderBalanceEuro</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderBalanceEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesTaxExchangeRate name="SalesTaxExchangeRate">SalesTaxExchangeRate</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

### <a href=#TaxSpecPrintLevel name="TaxSpecPrintLevel">TaxSpecPrintLevel</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

### <a href=#VendAddress name="VendAddress">VendAddress</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendCoRegNum name="VendCoRegNum">VendCoRegNum</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendCoRegNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendName name="VendName">VendName</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendRegNum name="VendRegNum">VendRegNum</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendRegNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyVATNum name="CompanyVATNum">CompanyVATNum</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

### <a href=#Payment name="Payment">Payment</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Payment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProForma name="IsProForma">IsProForma</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProForma attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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

### <a href=#Relationship_PurchTableRelationshipId name="Relationship_PurchTableRelationshipId">Relationship_PurchTableRelationshipId</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/PurchTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchTable.cdm.json/PurchTable</a></td><td><a href="../WorksheetHeader/PurchTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendPurchOrderJourRelationshipId name="Relationship_VendPurchOrderJourRelationshipId">Relationship_VendPurchOrderJourRelationshipId</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendPurchOrderJourRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/VendPurchOrderJour.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Transaction/VendPurchOrderJour.cdm.json/VendPurchOrderJour</a></td><td><a href="../Transaction/VendPurchOrderJour.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymTermRelationshipId name="Relationship_PaymTermRelationshipId">Relationship_PaymTermRelationshipId</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymTermRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Bank/Group/PaymTerm.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/PaymTerm.cdm.json/PaymTerm</a></td><td><a href="../../../Finance/Bank/Group/PaymTerm.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/PurchPurchaseOrderHeader (this entity)  

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
