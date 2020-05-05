---
title: FreeTextInvoiceLocalizationTmp - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# FreeTextInvoiceLocalizationTmp

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/AccountsReceivable/Worksheet/FreeTextInvoiceLocalizationTmp.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FreeTextInvoiceLocalizationTmp/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[Amount](#Amount)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[AmountInWords](#AmountInWords)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[AmountInWordsEUR](#AmountInWordsEUR)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[BillingCode](#BillingCode)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[Caption](#Caption)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[CashDisc](#CashDisc)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[CashDiscAmount](#CashDiscAmount)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[CashDiscTxt_LanguageId](#CashDiscTxt_LanguageId)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[ConfigId](#ConfigId)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[ConfigIdFlag](#ConfigIdFlag)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[CorrectedInvoiceId](#CorrectedInvoiceId)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[CorrectiveReasonHeader](#CorrectiveReasonHeader)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[CorrectiveReasonLines](#CorrectiveReasonLines)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[CurrencyCode](#CurrencyCode)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[CustInvoiceJourCurrencyCode](#CustInvoiceJourCurrencyCode)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[CustInvoiceJourDueDate](#CustInvoiceJourDueDate)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[CustomerRef](#CustomerRef)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[DateOfCreation](#DateOfCreation)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[DeliveryAddress](#DeliveryAddress)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[DeliveryName](#DeliveryName)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[DiscAmount](#DiscAmount)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[DiscDate](#DiscDate)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[DiscountAmount](#DiscountAmount)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[DiscPercent](#DiscPercent)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[DoPrintTransportationDocument](#DoPrintTransportationDocument)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[DueAmount](#DueAmount)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[DueDate](#DueDate)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[EconomicActivity](#EconomicActivity)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[EndDisc](#EndDisc)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[EndDiscEuro](#EndDiscEuro)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[EndDiscMST](#EndDiscMST)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[EuroCurrencyCode](#EuroCurrencyCode)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[EUROExchangeRate](#EUROExchangeRate)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[ExchRate](#ExchRate)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[ExternalItemId](#ExternalItemId)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[FooterText](#FooterText)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[HeaderNotes](#HeaderNotes)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[HideInvoiceLine_PL](#HideInvoiceLine_PL)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[IntrastatCode](#IntrastatCode)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[InventBatchId](#InventBatchId)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[InventColorId](#InventColorId)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[InventColorIdFlag](#InventColorIdFlag)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[InventVersionId](#InventVersionId)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[InventVersionIdFlag](#InventVersionIdFlag)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[InventDimPrint](#InventDimPrint)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[InventLocationId](#InventLocationId)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[InventSerialId](#InventSerialId)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[InventSiteId](#InventSiteId)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[InventSizeId](#InventSizeId)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[InventSizeIdFlag](#InventSizeIdFlag)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[InvoiceAmount](#InvoiceAmount)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[InvoiceAmountEuro](#InvoiceAmountEuro)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[InvoiceAmountMST](#InvoiceAmountMST)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[InvoiceId](#InvoiceId)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[InvoiceName](#InvoiceName)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[InvoiceRoundOff](#InvoiceRoundOff)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[InvoiceRoundOffEuro](#InvoiceRoundOffEuro)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[InvoiceRoundOffMST](#InvoiceRoundOffMST)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[IsBankExchangeRateEnabled](#IsBankExchangeRateEnabled)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[IsTaxAmountMST](#IsTaxAmountMST)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[IsTaxAmountMSTVisible](#IsTaxAmountMSTVisible)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[ItemId](#ItemId)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[LineAmount](#LineAmount)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[LineAmountInclTax](#LineAmountInclTax)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[LineHeader](#LineHeader)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[LineNumber](#LineNumber)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[LineSign](#LineSign)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[LineTaxAmount](#LineTaxAmount)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[MandateBankIBAN](#MandateBankIBAN)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[MandateReference](#MandateReference)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[MandateSWIFTNo](#MandateSWIFTNo)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[MarkupAmount](#MarkupAmount)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[MarkupCode](#MarkupCode)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[MarkupTaxCode](#MarkupTaxCode)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[Name](#Name)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[NetAmount](#NetAmount)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[NetAmountEuro](#NetAmountEuro)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[NetAmountMST](#NetAmountMST)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[Notes](#Notes)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[OriginalInvoiceAmount](#OriginalInvoiceAmount)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[OriginalInvoiceId_CZ](#OriginalInvoiceId_CZ)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[PaymentId](#PaymentId)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[PaymentReference](#PaymentReference)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[PKWiUCode](#PKWiUCode)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[PrepaidAmount](#PrepaidAmount)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[PrepaidAmountEuro](#PrepaidAmountEuro)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[PrePaymentAmountTax](#PrePaymentAmountTax)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[PrePaymentAmountTaxEuro](#PrePaymentAmountTaxEuro)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[PrePaymentAmountTaxMST](#PrePaymentAmountTaxMST)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[PrePrintLevel](#PrePrintLevel)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[PreviousRunningTotal](#PreviousRunningTotal)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[PriceIncludeTax](#PriceIncludeTax)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[PrintCode](#PrintCode)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[PrintEuroTotals](#PrintEuroTotals)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[PrintEuroTotals1](#PrintEuroTotals1)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[Qty](#Qty)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[RemainAmountToBePaid](#RemainAmountToBePaid)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[RemainAmountToBePaidEuro](#RemainAmountToBePaidEuro)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[SalesBalance](#SalesBalance)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[SalesBalanceEuro](#SalesBalanceEuro)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[SalesBalanceMST](#SalesBalanceMST)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[SalesPrice](#SalesPrice)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[SalesTaxExchangeRate](#SalesTaxExchangeRate)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[SalesUnitTxt](#SalesUnitTxt)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[SettledAmountCur](#SettledAmountCur)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[ShipmentDate](#ShipmentDate)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[ShowCashDiscOnInvoiceControls](#ShowCashDiscOnInvoiceControls)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[ShowCustPaymSched](#ShowCustPaymSched)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[ShowCustPaymSchedLine](#ShowCustPaymSchedLine)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[ShowCustTrans](#ShowCustTrans)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[ShowMarkupTrans](#ShowMarkupTrans)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[ShowPackingMaterial](#ShowPackingMaterial)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[ShowPayment](#ShowPayment)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[ShowPrepaidTotals](#ShowPrepaidTotals)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[ShowPrepaidTotalsEuro](#ShowPrepaidTotalsEuro)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[ShowSepaNotification](#ShowSepaNotification)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[ShowTaxTrans](#ShowTaxTrans)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[ShowTotals](#ShowTotals)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[ShowTotalsEuro](#ShowTotalsEuro)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[ShowTotalsTaxBalances](#ShowTotalsTaxBalances)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[ShowTotalsTaxBalancesEuro](#ShowTotalsTaxBalancesEuro)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[SpecialFormattedDiscountDate](#SpecialFormattedDiscountDate)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[SpecialFormattedDiscountDueDate](#SpecialFormattedDiscountDueDate)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[SpecialFormattedPaymentDueDate](#SpecialFormattedPaymentDueDate)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[SpecialFormattedPrePaymentTransDate](#SpecialFormattedPrePaymentTransDate)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[SpecialFormattedTransportationLoadedDate](#SpecialFormattedTransportationLoadedDate)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[StandardCurrency](#StandardCurrency)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[SumMarkup](#SumMarkup)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[SumMarkupEuro](#SumMarkupEuro)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[SumMarkupMST](#SumMarkupMST)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[SummaryLine_PL](#SummaryLine_PL)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[SumTax](#SumTax)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[SumTaxEuro](#SumTaxEuro)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[SumTaxMST](#SumTaxMST)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TaxableBalance](#TaxableBalance)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TaxableBalanceEuro](#TaxableBalanceEuro)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TaxableBalanceMST](#TaxableBalanceMST)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TaxAmount](#TaxAmount)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TaxAmountExcluded](#TaxAmountExcluded)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TaxAmountExcludedEuro](#TaxAmountExcludedEuro)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TaxAmountMST](#TaxAmountMST)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TaxBaseAmount](#TaxBaseAmount)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TaxBaseAmountMST](#TaxBaseAmountMST)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TaxBaseQty](#TaxBaseQty)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TaxCode](#TaxCode)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TaxCurrencyCode](#TaxCurrencyCode)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TaxDirective](#TaxDirective)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TaxDocumentNumber](#TaxDocumentNumber)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TaxExcludeFromInvoice](#TaxExcludeFromInvoice)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TaxExemptDescription](#TaxExemptDescription)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TaxFreeBalance](#TaxFreeBalance)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TaxFreeBalanceEuro](#TaxFreeBalanceEuro)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TaxFreeBalanceMST](#TaxFreeBalanceMST)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TaxPrintTaxFreeBalance](#TaxPrintTaxFreeBalance)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TaxValue](#TaxValue)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TaxWriteCode](#TaxWriteCode)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TransDate](#TransDate)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TransportationCarrierAddress](#TransportationCarrierAddress)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TransportationCarrierName](#TransportationCarrierName)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TransportationContactPersonName](#TransportationContactPersonName)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TransportationContactPersonTitle](#TransportationContactPersonTitle)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TransportationDataSection](#TransportationDataSection)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TransPortationIssuedByName](#TransPortationIssuedByName)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TransportationIssuedByTitle](#TransportationIssuedByTitle)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TransportationLoadedAddress](#TransportationLoadedAddress)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TransportationLoadedDateTime](#TransportationLoadedDateTime)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TransportationLoadedName](#TransportationLoadedName)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TransportationPackageDangerDegree](#TransportationPackageDangerDegree)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TransportationPackageDescription](#TransportationPackageDescription)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TransportationVehicleDescription](#TransportationVehicleDescription)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TransportationVehicleDriverName](#TransportationVehicleDriverName)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TransportationVehiclePlateNumber](#TransportationVehiclePlateNumber)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[TransportationVehicleTrailerNumber](#TransportationVehicleTrailerNumber)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[Txt](#Txt)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[WMSLocationId](#WMSLocationId)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[DataAreaId](#DataAreaId)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[Relationship_Currency_AccountingCurrencyRelationshipId](#Relationship_Currency_AccountingCurrencyRelationshipId)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[Relationship_Currency_EuroCurrencyCodeRelationshipId](#Relationship_Currency_EuroCurrencyCodeRelationshipId)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[Relationship_Currency_PrePaymentCurrencyRelationshipId](#Relationship_Currency_PrePaymentCurrencyRelationshipId)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[Relationship_Currency_TaxCurrencyRelationshipId](#Relationship_Currency_TaxCurrencyRelationshipId)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[Relationship_Currency_TransactionCurrencyRelationshipId](#Relationship_Currency_TransactionCurrencyRelationshipId)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="FreeTextInvoiceLocalizationTmp.md" target="_blank">Worksheet/FreeTextInvoiceLocalizationTmp</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FreeTextInvoiceLocalizationTmp/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Amount name="Amount">Amount</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

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

### <a href=#AmountInWords name="AmountInWords">AmountInWords</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountInWords attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountInWordsEUR name="AmountInWordsEUR">AmountInWordsEUR</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountInWordsEUR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillingCode name="BillingCode">BillingCode</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillingCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Caption name="Caption">Caption</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Caption attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDisc name="CashDisc">CashDisc</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cash discount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDisc attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cash discount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CashDiscAmount name="CashDiscAmount">CashDiscAmount</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CashDiscTxt_LanguageId name="CashDiscTxt_LanguageId">CashDiscTxt_LanguageId</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscTxt_LanguageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConfigId name="ConfigId">ConfigId</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfigId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConfigIdFlag name="ConfigIdFlag">ConfigIdFlag</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfigIdFlag attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CorrectedInvoiceId name="CorrectedInvoiceId">CorrectedInvoiceId</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedInvoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectiveReasonHeader name="CorrectiveReasonHeader">CorrectiveReasonHeader</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectiveReasonHeader attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectiveReasonLines name="CorrectiveReasonLines">CorrectiveReasonLines</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectiveReasonLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustInvoiceJourCurrencyCode name="CustInvoiceJourCurrencyCode">CustInvoiceJourCurrencyCode</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustInvoiceJourCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustInvoiceJourDueDate name="CustInvoiceJourDueDate">CustInvoiceJourDueDate</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustInvoiceJourDueDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#CustomerRef name="CustomerRef">CustomerRef</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

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

### <a href=#DateOfCreation name="DateOfCreation">DateOfCreation</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateOfCreation attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#DeliveryAddress name="DeliveryAddress">DeliveryAddress</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

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

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

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

### <a href=#DiscAmount name="DiscAmount">DiscAmount</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DiscDate name="DiscDate">DiscDate</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#DiscountAmount name="DiscountAmount">DiscountAmount</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DiscPercent name="DiscPercent">DiscPercent</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscPercent attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DoPrintTransportationDocument name="DoPrintTransportationDocument">DoPrintTransportationDocument</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DoPrintTransportationDocument attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DueAmount name="DueAmount">DueAmount</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DueAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DueDate name="DueDate">DueDate</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DueDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#EconomicActivity name="EconomicActivity">EconomicActivity</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EconomicActivity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EndDisc name="EndDisc">EndDisc</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

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

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

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

### <a href=#EndDiscMST name="EndDiscMST">EndDiscMST</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDiscMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#EuroCurrencyCode name="EuroCurrencyCode">EuroCurrencyCode</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

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

### <a href=#EUROExchangeRate name="EUROExchangeRate">EUROExchangeRate</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EUROExchangeRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ExchRate name="ExchRate">ExchRate</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ExternalItemId name="ExternalItemId">ExternalItemId</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FooterText name="FooterText">FooterText</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FooterText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HeaderNotes name="HeaderNotes">HeaderNotes</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeaderNotes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HideInvoiceLine_PL name="HideInvoiceLine_PL">HideInvoiceLine_PL</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HideInvoiceLine_PL attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IntrastatCode name="IntrastatCode">IntrastatCode</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventBatchId name="InventBatchId">InventBatchId</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventBatchId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventColorId name="InventColorId">InventColorId</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventColorIdFlag name="InventColorIdFlag">InventColorIdFlag</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventColorIdFlag attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InventVersionId name="InventVersionId">InventVersionId</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventVersionIdFlag name="InventVersionIdFlag">InventVersionIdFlag</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventVersionIdFlag attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InventDimPrint name="InventDimPrint">InventDimPrint</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimPrint attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventLocationId name="InventLocationId">InventLocationId</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventSerialId name="InventSerialId">InventSerialId</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventSerialId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventSiteId name="InventSiteId">InventSiteId</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventSizeId name="InventSizeId">InventSizeId</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventSizeIdFlag name="InventSizeIdFlag">InventSizeIdFlag</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventSizeIdFlag attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InvoiceAmount name="InvoiceAmount">InvoiceAmount</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InvoiceAmountEuro name="InvoiceAmountEuro">InvoiceAmountEuro</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAmountEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InvoiceAmountMST name="InvoiceAmountMST">InvoiceAmountMST</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InvoiceId name="InvoiceId">InvoiceId</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceName name="InvoiceName">InvoiceName</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceRoundOff name="InvoiceRoundOff">InvoiceRoundOff</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceRoundOff attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InvoiceRoundOffEuro name="InvoiceRoundOffEuro">InvoiceRoundOffEuro</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceRoundOffEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InvoiceRoundOffMST name="InvoiceRoundOffMST">InvoiceRoundOffMST</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceRoundOffMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#IsBankExchangeRateEnabled name="IsBankExchangeRateEnabled">IsBankExchangeRateEnabled</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBankExchangeRateEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsTaxAmountMST name="IsTaxAmountMST">IsTaxAmountMST</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTaxAmountMST attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsTaxAmountMSTVisible name="IsTaxAmountMSTVisible">IsTaxAmountMSTVisible</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTaxAmountMSTVisible attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineAmount name="LineAmount">LineAmount</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LineAmountInclTax name="LineAmountInclTax">LineAmountInclTax</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineAmountInclTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LineHeader name="LineHeader">LineHeader</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineHeader attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LineSign name="LineSign">LineSign</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>char</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineSign attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#LineTaxAmount name="LineTaxAmount">LineTaxAmount</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineTaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MandateBankIBAN name="MandateBankIBAN">MandateBankIBAN</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MandateBankIBAN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MandateReference name="MandateReference">MandateReference</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MandateReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MandateSWIFTNo name="MandateSWIFTNo">MandateSWIFTNo</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MandateSWIFTNo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MarkupAmount name="MarkupAmount">MarkupAmount</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarkupAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MarkupCode name="MarkupCode">MarkupCode</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarkupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MarkupTaxCode name="MarkupTaxCode">MarkupTaxCode</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarkupTaxCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NetAmount name="NetAmount">NetAmount</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

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

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

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

### <a href=#NetAmountMST name="NetAmountMST">NetAmountMST</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Notes name="Notes">Notes</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

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

### <a href=#OriginalInvoiceAmount name="OriginalInvoiceAmount">OriginalInvoiceAmount</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalInvoiceAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#OriginalInvoiceId_CZ name="OriginalInvoiceId_CZ">OriginalInvoiceId_CZ</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalInvoiceId_CZ attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentId name="PaymentId">PaymentId</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentReference name="PaymentReference">PaymentReference</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PKWiUCode name="PKWiUCode">PKWiUCode</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PKWiUCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrepaidAmount name="PrepaidAmount">PrepaidAmount</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrepaidAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PrepaidAmountEuro name="PrepaidAmountEuro">PrepaidAmountEuro</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrepaidAmountEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PrePaymentAmountTax name="PrePaymentAmountTax">PrePaymentAmountTax</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrePaymentAmountTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PrePaymentAmountTaxEuro name="PrePaymentAmountTaxEuro">PrePaymentAmountTaxEuro</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrePaymentAmountTaxEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PrePaymentAmountTaxMST name="PrePaymentAmountTaxMST">PrePaymentAmountTaxMST</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrePaymentAmountTaxMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PrePrintLevel name="PrePrintLevel">PrePrintLevel</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

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

### <a href=#PreviousRunningTotal name="PreviousRunningTotal">PreviousRunningTotal</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreviousRunningTotal attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PriceIncludeTax name="PriceIncludeTax">PriceIncludeTax</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceIncludeTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintCode name="PrintCode">PrintCode</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintEuroTotals name="PrintEuroTotals">PrintEuroTotals</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintEuroTotals attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintEuroTotals1 name="PrintEuroTotals1">PrintEuroTotals1</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintEuroTotals1 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Qty name="Qty">Qty</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Qty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RemainAmountToBePaid name="RemainAmountToBePaid">RemainAmountToBePaid</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainAmountToBePaid attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RemainAmountToBePaidEuro name="RemainAmountToBePaidEuro">RemainAmountToBePaidEuro</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainAmountToBePaidEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesBalance name="SalesBalance">SalesBalance</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales subtotal amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesBalance attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales subtotal amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesBalanceEuro name="SalesBalanceEuro">SalesBalanceEuro</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

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

### <a href=#SalesBalanceMST name="SalesBalanceMST">SalesBalanceMST</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesBalanceMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesPrice name="SalesPrice">SalesPrice</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesTaxExchangeRate name="SalesTaxExchangeRate">SalesTaxExchangeRate</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

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

### <a href=#SalesUnitTxt name="SalesUnitTxt">SalesUnitTxt</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesUnitTxt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettledAmountCur name="SettledAmountCur">SettledAmountCur</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettledAmountCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ShipmentDate name="ShipmentDate">ShipmentDate</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipmentDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#ShowCashDiscOnInvoiceControls name="ShowCashDiscOnInvoiceControls">ShowCashDiscOnInvoiceControls</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowCashDiscOnInvoiceControls attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowCustPaymSched name="ShowCustPaymSched">ShowCustPaymSched</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowCustPaymSched attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowCustPaymSchedLine name="ShowCustPaymSchedLine">ShowCustPaymSchedLine</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowCustPaymSchedLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowCustTrans name="ShowCustTrans">ShowCustTrans</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowCustTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowMarkupTrans name="ShowMarkupTrans">ShowMarkupTrans</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowMarkupTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowPackingMaterial name="ShowPackingMaterial">ShowPackingMaterial</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowPackingMaterial attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowPayment name="ShowPayment">ShowPayment</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowPayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowPrepaidTotals name="ShowPrepaidTotals">ShowPrepaidTotals</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowPrepaidTotals attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowPrepaidTotalsEuro name="ShowPrepaidTotalsEuro">ShowPrepaidTotalsEuro</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowPrepaidTotalsEuro attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowSepaNotification name="ShowSepaNotification">ShowSepaNotification</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowSepaNotification attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowTaxTrans name="ShowTaxTrans">ShowTaxTrans</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowTaxTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowTotals name="ShowTotals">ShowTotals</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowTotals attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowTotalsEuro name="ShowTotalsEuro">ShowTotalsEuro</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowTotalsEuro attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowTotalsTaxBalances name="ShowTotalsTaxBalances">ShowTotalsTaxBalances</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowTotalsTaxBalances attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowTotalsTaxBalancesEuro name="ShowTotalsTaxBalancesEuro">ShowTotalsTaxBalancesEuro</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowTotalsTaxBalancesEuro attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SpecialFormattedDiscountDate name="SpecialFormattedDiscountDate">SpecialFormattedDiscountDate</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialFormattedDiscountDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpecialFormattedDiscountDueDate name="SpecialFormattedDiscountDueDate">SpecialFormattedDiscountDueDate</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialFormattedDiscountDueDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpecialFormattedPaymentDueDate name="SpecialFormattedPaymentDueDate">SpecialFormattedPaymentDueDate</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialFormattedPaymentDueDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpecialFormattedPrePaymentTransDate name="SpecialFormattedPrePaymentTransDate">SpecialFormattedPrePaymentTransDate</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialFormattedPrePaymentTransDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpecialFormattedTransportationLoadedDate name="SpecialFormattedTransportationLoadedDate">SpecialFormattedTransportationLoadedDate</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialFormattedTransportationLoadedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StandardCurrency name="StandardCurrency">StandardCurrency</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StandardCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SumMarkup name="SumMarkup">SumMarkup</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

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

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

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

### <a href=#SumMarkupMST name="SumMarkupMST">SumMarkupMST</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumMarkupMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SummaryLine_PL name="SummaryLine_PL">SummaryLine_PL</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SummaryLine_PL attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SumTax name="SumTax">SumTax</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SumTaxEuro name="SumTaxEuro">SumTaxEuro</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

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

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

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

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

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

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

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

### <a href=#TaxableBalanceMST name="TaxableBalanceMST">TaxableBalanceMST</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxableBalanceMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxAmount name="TaxAmount">TaxAmount</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxAmountExcluded name="TaxAmountExcluded">TaxAmountExcluded</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountExcluded attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxAmountExcludedEuro name="TaxAmountExcludedEuro">TaxAmountExcludedEuro</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountExcludedEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxAmountMST name="TaxAmountMST">TaxAmountMST</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxBaseAmount name="TaxBaseAmount">TaxBaseAmount</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxBaseAmountMST name="TaxBaseAmountMST">TaxBaseAmountMST</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBaseAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxBaseQty name="TaxBaseQty">TaxBaseQty</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBaseQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxCode name="TaxCode">TaxCode</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxCurrencyCode name="TaxCurrencyCode">TaxCurrencyCode</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxDirective name="TaxDirective">TaxDirective</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Directive</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxDirective attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Directive</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxDocumentNumber name="TaxDocumentNumber">TaxDocumentNumber</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxDocumentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxExcludeFromInvoice name="TaxExcludeFromInvoice">TaxExcludeFromInvoice</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxExcludeFromInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxExemptDescription name="TaxExemptDescription">TaxExemptDescription</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxExemptDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxFreeBalance name="TaxFreeBalance">TaxFreeBalance</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

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

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

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

### <a href=#TaxFreeBalanceMST name="TaxFreeBalanceMST">TaxFreeBalanceMST</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxFreeBalanceMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxPrintTaxFreeBalance name="TaxPrintTaxFreeBalance">TaxPrintTaxFreeBalance</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

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

### <a href=#TaxValue name="TaxValue">TaxValue</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxWriteCode name="TaxWriteCode">TaxWriteCode</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWriteCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#TransportationCarrierAddress name="TransportationCarrierAddress">TransportationCarrierAddress</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationCarrierAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationCarrierName name="TransportationCarrierName">TransportationCarrierName</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationCarrierName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationContactPersonName name="TransportationContactPersonName">TransportationContactPersonName</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationContactPersonName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationContactPersonTitle name="TransportationContactPersonTitle">TransportationContactPersonTitle</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationContactPersonTitle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationDataSection name="TransportationDataSection">TransportationDataSection</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationDataSection attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TransPortationIssuedByName name="TransPortationIssuedByName">TransPortationIssuedByName</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransPortationIssuedByName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationIssuedByTitle name="TransportationIssuedByTitle">TransportationIssuedByTitle</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationIssuedByTitle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationLoadedAddress name="TransportationLoadedAddress">TransportationLoadedAddress</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationLoadedAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationLoadedDateTime name="TransportationLoadedDateTime">TransportationLoadedDateTime</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationLoadedDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#TransportationLoadedName name="TransportationLoadedName">TransportationLoadedName</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationLoadedName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationPackageDangerDegree name="TransportationPackageDangerDegree">TransportationPackageDangerDegree</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationPackageDangerDegree attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationPackageDescription name="TransportationPackageDescription">TransportationPackageDescription</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationPackageDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationVehicleDescription name="TransportationVehicleDescription">TransportationVehicleDescription</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationVehicleDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationVehicleDriverName name="TransportationVehicleDriverName">TransportationVehicleDriverName</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationVehicleDriverName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationVehiclePlateNumber name="TransportationVehiclePlateNumber">TransportationVehiclePlateNumber</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationVehiclePlateNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationVehicleTrailerNumber name="TransportationVehicleTrailerNumber">TransportationVehicleTrailerNumber</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationVehicleTrailerNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Txt name="Txt">Txt</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Txt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WMSLocationId name="WMSLocationId">WMSLocationId</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WMSLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

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

### <a href=#Relationship_Currency_AccountingCurrencyRelationshipId name="Relationship_Currency_AccountingCurrencyRelationshipId">Relationship_Currency_AccountingCurrencyRelationshipId</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Currency_AccountingCurrencyRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_Currency_EuroCurrencyCodeRelationshipId name="Relationship_Currency_EuroCurrencyCodeRelationshipId">Relationship_Currency_EuroCurrencyCodeRelationshipId</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Currency_EuroCurrencyCodeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_Currency_PrePaymentCurrencyRelationshipId name="Relationship_Currency_PrePaymentCurrencyRelationshipId">Relationship_Currency_PrePaymentCurrencyRelationshipId</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Currency_PrePaymentCurrencyRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_Currency_TaxCurrencyRelationshipId name="Relationship_Currency_TaxCurrencyRelationshipId">Relationship_Currency_TaxCurrencyRelationshipId</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Currency_TaxCurrencyRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_Currency_TransactionCurrencyRelationshipId name="Relationship_Currency_TransactionCurrencyRelationshipId">Relationship_Currency_TransactionCurrencyRelationshipId</a>

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Currency_TransactionCurrencyRelationshipId attribute are listed below.</summary>

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

First included in: Worksheet/FreeTextInvoiceLocalizationTmp (this entity)  

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
