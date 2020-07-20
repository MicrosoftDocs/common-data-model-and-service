---
title: VendInvoiceDocumentTmp in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Vendor invoice journal in Miscellaneous(VendInvoiceDocumentTmp)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/AccountsPayable/Miscellaneous/VendInvoiceDocumentTmp.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendInvoiceDocumentTmp/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor invoice journal</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[Amount](#Amount)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[AmountInWords](#AmountInWords)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[AmountInWordsInCompanyCurrency](#AmountInWordsInCompanyCurrency)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[AmountInWordsSection](#AmountInWordsSection)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CashDisc](#CashDisc)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CashDiscAmount](#CashDiscAmount)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CashDiscOnInvoice](#CashDiscOnInvoice)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CashDiscPercent](#CashDiscPercent)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CashDiscTxt](#CashDiscTxt)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CompanyAddress](#CompanyAddress)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CompanyBankAccountName](#CompanyBankAccountName)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CompanyBankAccountNum](#CompanyBankAccountNum)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CompanyBankAccountRegNum](#CompanyBankAccountRegNum)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CompanyCommercialRegister](#CompanyCommercialRegister)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CompanyCommercialRegisterInsetNumber](#CompanyCommercialRegisterInsetNumber)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CompanyCommercialRegisterSection](#CompanyCommercialRegisterSection)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CompanyCoRegNum](#CompanyCoRegNum)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CompanyCurrencyCode](#CompanyCurrencyCode)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CompanyEmail](#CompanyEmail)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CompanyEnterpriseCode](#CompanyEnterpriseCode)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CompanyEnterpriseNumber](#CompanyEnterpriseNumber)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CompanyGiro](#CompanyGiro)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CompanyLogo](#CompanyLogo)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CompanyName](#CompanyName)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CompanyPhone](#CompanyPhone)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CompanyRegNum](#CompanyRegNum)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CompanyTeleFax](#CompanyTeleFax)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CompanyVATNum](#CompanyVATNum)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[ConfigID](#ConfigID)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CorrectedInvoiceIdCtrl](#CorrectedInvoiceIdCtrl)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CorrectiveReason](#CorrectiveReason)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CorrectiveReasonLines](#CorrectiveReasonLines)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CurrencyCode](#CurrencyCode)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CurrencyCodeCompany](#CurrencyCodeCompany)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[CurrencyCodeMain](#CurrencyCodeMain)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[DeliveryAddress](#DeliveryAddress)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[DeliveryName](#DeliveryName)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[DiscAmount](#DiscAmount)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[Discount](#Discount)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[DiscPercent](#DiscPercent)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[DoPricesIncludeTax](#DoPricesIncludeTax)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[DoPrintSalesTaxExchRateSection](#DoPrintSalesTaxExchRateSection)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[DoPrintTransportationDocument](#DoPrintTransportationDocument)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[EndDisc](#EndDisc)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[EndDiscAmountMST](#EndDiscAmountMST)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[EnterpriseNumber](#EnterpriseNumber)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[ExchRate](#ExchRate)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[ExcludeInTaxTransSection](#ExcludeInTaxTransSection)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[ExternalItemNum](#ExternalItemNum)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[Footer](#Footer)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[InternalInvoiceId](#InternalInvoiceId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[IntracomInvoiceAmount](#IntracomInvoiceAmount)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[IntracomSumTax](#IntracomSumTax)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[IntracomVAT](#IntracomVAT)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[InventColorId](#InventColorId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[InventDimPrint](#InventDimPrint)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[InventDimProduct](#InventDimProduct)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[InventSizeId](#InventSizeId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[InventStyleId](#InventStyleId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[InventVersionId](#InventVersionId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[InvoiceAmount](#InvoiceAmount)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[InvoiceAmountMST](#InvoiceAmountMST)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[InvoiceDate](#InvoiceDate)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[InvoiceDateStr](#InvoiceDateStr)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[InvoiceDueDate](#InvoiceDueDate)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[InvoiceDueDateStr](#InvoiceDueDateStr)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[InvoiceNum](#InvoiceNum)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[InvoiceReturnByList](#InvoiceReturnByList)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[InvoiceRoundOff](#InvoiceRoundOff)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[InvoiceRoundOffAmountMST](#InvoiceRoundOffAmountMST)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[InvoiceText](#InvoiceText)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[InvoiceWordingUK](#InvoiceWordingUK)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[IsProforma](#IsProforma)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[IsTaxInvoice](#IsTaxInvoice)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[ItemId](#ItemId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[ItemIdOnly](#ItemIdOnly)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[JournalRecId](#JournalRecId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[LanguageTxtText](#LanguageTxtText)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[LanguageTxtTextSection](#LanguageTxtTextSection)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[LineAmount](#LineAmount)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[LocalCurrencyAmount](#LocalCurrencyAmount)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[MiscCharges](#MiscCharges)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[Name](#Name)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[NetAmount](#NetAmount)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[NetAmountMST](#NetAmountMST)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[Payment](#Payment)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[PaymentSched](#PaymentSched)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[pdsCWQty](#pdsCWQty)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[PdsCWStr](#PdsCWStr)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[pdsCWUnitId](#pdsCWUnitId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[PdsEnabled](#PdsEnabled)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[PrintCode](#PrintCode)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[PrintExternalItemNum](#PrintExternalItemNum)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[PrintFooter](#PrintFooter)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[PrintIntracomVAT](#PrintIntracomVAT)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[PrintInvoiceVATNum](#PrintInvoiceVATNum)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[PrintLogo](#PrintLogo)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[ProcurementCategoryName](#ProcurementCategoryName)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[PurchaseLineLineNumber](#PurchaseLineLineNumber)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[PurchBalance](#PurchBalance)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[PurchInvoiceTransOrTaxTrans](#PurchInvoiceTransOrTaxTrans)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[PurchNum](#PurchNum)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[PurchPrice](#PurchPrice)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[PurchTax](#PurchTax)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[PurchUnitTxt](#PurchUnitTxt)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[Qty](#Qty)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[ReverseChargeLine](#ReverseChargeLine)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[ReverseChargeJournal](#ReverseChargeJournal)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[ReverseChargeAmount](#ReverseChargeAmount)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[SalesBalance](#SalesBalance)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[SalesBalanceMST](#SalesBalanceMST)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[SalesTaxExchRate](#SalesTaxExchRate)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[SchedDiscAmount](#SchedDiscAmount)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[SchedDiscDate](#SchedDiscDate)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[SchedDiscDateStr](#SchedDiscDateStr)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[SchedDueAmount](#SchedDueAmount)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[SchedDueDate](#SchedDueDate)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[SchedDueDateStr](#SchedDueDateStr)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[sellerAddress](#sellerAddress)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[SellerEnterpriseCode](#SellerEnterpriseCode)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[SellerName](#SellerName)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[ServiceTaxReverseChargeOriginAmount_IN](#ServiceTaxReverseChargeOriginAmount_IN)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[ShowAccountingCurrencyAmounts](#ShowAccountingCurrencyAmounts)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[ShowCopy](#ShowCopy)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[ShowEnterpriseNumber](#ShowEnterpriseNumber)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[ShowGiroField](#ShowGiroField)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[ShowInventDimColor](#ShowInventDimColor)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[ShowInventDimConfigId](#ShowInventDimConfigId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[ShowInventDimSize](#ShowInventDimSize)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[ShowInventDimStyleId](#ShowInventDimStyleId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[ShowInventDimVersion](#ShowInventDimVersion)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[ShowPrePaymentDeductionSection](#ShowPrePaymentDeductionSection)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[ShowSeller](#ShowSeller)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[ShowTaxBalance](#ShowTaxBalance)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[ShowVendPaym](#ShowVendPaym)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[StandardCurrency](#StandardCurrency)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[SumMarkup](#SumMarkup)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[SumMarkupAmountMST](#SumMarkupAmountMST)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[SumTaxMST](#SumTaxMST)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TaxableBalance](#TaxableBalance)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TaxableBalanceAmountMST](#TaxableBalanceAmountMST)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TaxAmount](#TaxAmount)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TaxAmountMST](#TaxAmountMST)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TaxBaseAmount](#TaxBaseAmount)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TaxBaseAmountMST](#TaxBaseAmountMST)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TaxBaseCurrencyCode](#TaxBaseCurrencyCode)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TaxBaseQty](#TaxBaseQty)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TaxCode](#TaxCode)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TaxDocumentNum](#TaxDocumentNum)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TaxExemptDescription](#TaxExemptDescription)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TaxFreeBalance](#TaxFreeBalance)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TaxFreeBalanceAmountMST](#TaxFreeBalanceAmountMST)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TaxInvoicePurchId](#TaxInvoicePurchId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TaxPercent](#TaxPercent)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TaxPrintTaxFreeBalance](#TaxPrintTaxFreeBalance)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TaxSpecPrintLevel](#TaxSpecPrintLevel)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TaxWriteCode](#TaxWriteCode)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TotalDiscount](#TotalDiscount)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TotalGrand](#TotalGrand)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TotalMiscCharges](#TotalMiscCharges)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TotalPrepaidAmount](#TotalPrepaidAmount)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TotalRoundOff](#TotalRoundOff)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TotalSalesBalance](#TotalSalesBalance)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TotalSalesTax](#TotalSalesTax)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TotalsSumTax](#TotalsSumTax)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TotalsSumTaxAmountMST](#TotalsSumTaxAmountMST)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TotalTaxAmountExcludedCur](#TotalTaxAmountExcludedCur)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TotalTaxAmountExcludedMST](#TotalTaxAmountExcludedMST)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TotaltaxBaseAmount](#TotaltaxBaseAmount)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TransportationCarrierAddress](#TransportationCarrierAddress)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TransportationCarrierName](#TransportationCarrierName)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TransportationContactPersonName](#TransportationContactPersonName)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TransportationContactPersonTitle](#TransportationContactPersonTitle)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TransportationDataSection](#TransportationDataSection)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TransPortationIssuedByName](#TransPortationIssuedByName)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TransportationIssuedByTitle](#TransportationIssuedByTitle)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TransportationLoadedAddress](#TransportationLoadedAddress)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TransportationLoadedDateStr](#TransportationLoadedDateStr)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TransportationLoadedDateTime](#TransportationLoadedDateTime)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TransportationLoadedName](#TransportationLoadedName)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TransportationPackageDangerDegree](#TransportationPackageDangerDegree)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TransportationPackageDescription](#TransportationPackageDescription)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TransportationVehicleDescription](#TransportationVehicleDescription)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TransportationVehicleDriverName](#TransportationVehicleDriverName)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TransportationVehiclePlateNumber](#TransportationVehiclePlateNumber)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TransportationVehicleTrailerNumber](#TransportationVehicleTrailerNumber)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[VatDueDate](#VatDueDate)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[VendAddress](#VendAddress)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[VendBankAccountName](#VendBankAccountName)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[VendBankAccountNum](#VendBankAccountNum)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[VendBankAccountRegNum](#VendBankAccountRegNum)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[VendBankConstantSymbol](#VendBankConstantSymbol)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[VendBankSpecificSymbol](#VendBankSpecificSymbol)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[VendCreditInvoicing](#VendCreditInvoicing)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[VendInvoiceJourDueDate](#VendInvoiceJourDueDate)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[VendInvoiceTransLineNum](#VendInvoiceTransLineNum)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[VendName](#VendName)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[VendorEnterpriseCode](#VendorEnterpriseCode)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[VendPaymSched](#VendPaymSched)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[VendPurchReceiptDate](#VendPurchReceiptDate)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[VendRegNum](#VendRegNum)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[VendTransCurrencyCode](#VendTransCurrencyCode)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[VendTransInvoiceCurrencyCode](#VendTransInvoiceCurrencyCode)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[VendTransSettledAmountCur](#VendTransSettledAmountCur)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[VendTransSettledAmountOriginCur](#VendTransSettledAmountOriginCur)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[VendTransTransDate](#VendTransTransDate)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[VendTransTxt](#VendTransTxt)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[VendVATNum](#VendVATNum)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[GSTApprovalNumber_MY](#GSTApprovalNumber_MY)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[GSTSummaryText_MY](#GSTSummaryText_MY)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[InvoiceType_MY](#InvoiceType_MY)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[TotalAppliedAmount](#TotalAppliedAmount)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[ReverseChargeBalance](#ReverseChargeBalance)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[LanguageId](#LanguageId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[WithReducedTax_JP](#WithReducedTax_JP)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[DataAreaId](#DataAreaId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[Relationship_Currency_CompanyCurrencyCodeRelationshipId](#Relationship_Currency_CompanyCurrencyCodeRelationshipId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[Relationship_Currency_CurrencyCodeRelationshipId](#Relationship_Currency_CurrencyCodeRelationshipId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[Relationship_Currency_CurrencyCodeCompanyRelationshipId](#Relationship_Currency_CurrencyCodeCompanyRelationshipId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[Relationship_Currency_CurrencyCodeMainRelationshipId](#Relationship_Currency_CurrencyCodeMainRelationshipId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[Relationship_Currency_StandardCurrencyRelationshipId](#Relationship_Currency_StandardCurrencyRelationshipId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[Relationship_Currency_TaxBaseCurrencyCodeRelationshipId](#Relationship_Currency_TaxBaseCurrencyCodeRelationshipId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[Relationship_Currency_VendTransCurrencyCodeRelationshipId](#Relationship_Currency_VendTransCurrencyCodeRelationshipId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[Relationship_Currency_VendTransInvoiceCurrencyCodeRelationshipId](#Relationship_Currency_VendTransInvoiceCurrencyCodeRelationshipId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[Relationship_InventTableRelationshipId](#Relationship_InventTableRelationshipId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[Relationship_PaymSchedRelationshipId](#Relationship_PaymSchedRelationshipId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[Relationship_PurchTableRelationshipId](#Relationship_PurchTableRelationshipId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[Relationship_TaxTableRelationshipId](#Relationship_TaxTableRelationshipId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[Relationship_VendInvoiceJourRelationshipId](#Relationship_VendInvoiceJourRelationshipId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[Relationship_LanguageTableRelationshipId](#Relationship_LanguageTableRelationshipId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="VendInvoiceDocumentTmp.md" target="_blank">Miscellaneous/VendInvoiceDocumentTmp</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendInvoiceDocumentTmp/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Amount name="Amount">Amount</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#AmountInWordsInCompanyCurrency name="AmountInWordsInCompanyCurrency">AmountInWordsInCompanyCurrency</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountInWordsInCompanyCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountInWordsSection name="AmountInWordsSection">AmountInWordsSection</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountInWordsSection attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CashDisc name="CashDisc">CashDisc</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#CashDiscAmount name="CashDiscAmount">CashDiscAmount</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#CashDiscOnInvoice name="CashDiscOnInvoice">CashDiscOnInvoice</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#CompanyEnterpriseCode name="CompanyEnterpriseCode">CompanyEnterpriseCode</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyEnterpriseCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyEnterpriseNumber name="CompanyEnterpriseNumber">CompanyEnterpriseNumber</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#CompanyVATNum name="CompanyVATNum">CompanyVATNum</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#ConfigID name="ConfigID">ConfigID</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfigID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectedInvoiceIdCtrl name="CorrectedInvoiceIdCtrl">CorrectedInvoiceIdCtrl</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedInvoiceIdCtrl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectiveReason name="CorrectiveReason">CorrectiveReason</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectiveReason attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectiveReasonLines name="CorrectiveReasonLines">CorrectiveReasonLines</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#CurrencyCodeMain name="CurrencyCodeMain">CurrencyCodeMain</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCodeMain attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddress name="DeliveryAddress">DeliveryAddress</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#Discount name="Discount">Discount</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Discount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DiscPercent name="DiscPercent">DiscPercent</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#DoPricesIncludeTax name="DoPricesIncludeTax">DoPricesIncludeTax</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>PlaceHolder</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DoPricesIncludeTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>PlaceHolder</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DoPrintSalesTaxExchRateSection name="DoPrintSalesTaxExchRateSection">DoPrintSalesTaxExchRateSection</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DoPrintSalesTaxExchRateSection attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DoPrintTransportationDocument name="DoPrintTransportationDocument">DoPrintTransportationDocument</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#EndDisc name="EndDisc">EndDisc</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#EndDiscAmountMST name="EndDiscAmountMST">EndDiscAmountMST</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDiscAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#EnterpriseNumber name="EnterpriseNumber">EnterpriseNumber</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnterpriseNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchRate name="ExchRate">ExchRate</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#ExcludeInTaxTransSection name="ExcludeInTaxTransSection">ExcludeInTaxTransSection</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExcludeInTaxTransSection attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ExternalItemNum name="ExternalItemNum">ExternalItemNum</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalItemNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Footer name="Footer">Footer</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Footer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InternalInvoiceId name="InternalInvoiceId">InternalInvoiceId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InternalInvoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntracomInvoiceAmount name="IntracomInvoiceAmount">IntracomInvoiceAmount</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntracomInvoiceAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#IntracomSumTax name="IntracomSumTax">IntracomSumTax</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntracomSumTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#IntracomVAT name="IntracomVAT">IntracomVAT</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntracomVAT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InventColorId name="InventColorId">InventColorId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#InventDimPrint name="InventDimPrint">InventDimPrint</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#InventDimProduct name="InventDimProduct">InventDimProduct</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimProduct attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventSizeId name="InventSizeId">InventSizeId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#InventStyleId name="InventStyleId">InventStyleId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventVersionId name="InventVersionId">InventVersionId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#InvoiceAmount name="InvoiceAmount">InvoiceAmount</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InvoiceAmountMST name="InvoiceAmountMST">InvoiceAmountMST</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#InvoiceDate name="InvoiceDate">InvoiceDate</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#InvoiceDateStr name="InvoiceDateStr">InvoiceDateStr</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceDateStr attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceDueDate name="InvoiceDueDate">InvoiceDueDate</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceDueDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#InvoiceDueDateStr name="InvoiceDueDateStr">InvoiceDueDateStr</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceDueDateStr attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceNum name="InvoiceNum">InvoiceNum</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceReturnByList name="InvoiceReturnByList">InvoiceReturnByList</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceReturnByList attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceRoundOff name="InvoiceRoundOff">InvoiceRoundOff</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#InvoiceRoundOffAmountMST name="InvoiceRoundOffAmountMST">InvoiceRoundOffAmountMST</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceRoundOffAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InvoiceText name="InvoiceText">InvoiceText</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceWordingUK name="InvoiceWordingUK">InvoiceWordingUK</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceWordingUK attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProforma name="IsProforma">IsProforma</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProforma attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsTaxInvoice name="IsTaxInvoice">IsTaxInvoice</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTaxInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#ItemIdOnly name="ItemIdOnly">ItemIdOnly</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemIdOnly attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalRecId name="JournalRecId">JournalRecId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#LanguageTxtText name="LanguageTxtText">LanguageTxtText</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LanguageTxtText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LanguageTxtTextSection name="LanguageTxtTextSection">LanguageTxtTextSection</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LanguageTxtTextSection attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LineAmount name="LineAmount">LineAmount</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#LocalCurrencyAmount name="LocalCurrencyAmount">LocalCurrencyAmount</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocalCurrencyAmount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#MiscCharges name="MiscCharges">MiscCharges</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MiscCharges attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Name name="Name">Name</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#NetAmountMST name="NetAmountMST">NetAmountMST</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#Payment name="Payment">Payment</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#PaymentSched name="PaymentSched">PaymentSched</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentSched attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#pdsCWQty name="pdsCWQty">pdsCWQty</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pdsCWQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PdsCWStr name="PdsCWStr">PdsCWStr</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsCWStr attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#pdsCWUnitId name="pdsCWUnitId">pdsCWUnitId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pdsCWUnitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PdsEnabled name="PdsEnabled">PdsEnabled</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Distribution</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Process Distribution</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PrintCode name="PrintCode">PrintCode</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#PrintExternalItemNum name="PrintExternalItemNum">PrintExternalItemNum</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintExternalItemNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintFooter name="PrintFooter">PrintFooter</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintFooter attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintIntracomVAT name="PrintIntracomVAT">PrintIntracomVAT</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintIntracomVAT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintInvoiceVATNum name="PrintInvoiceVATNum">PrintInvoiceVATNum</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintInvoiceVATNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintLogo name="PrintLogo">PrintLogo</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#ProcurementCategoryName name="ProcurementCategoryName">ProcurementCategoryName</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementCategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseLineLineNumber name="PurchaseLineLineNumber">PurchaseLineLineNumber</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseLineLineNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PurchBalance name="PurchBalance">PurchBalance</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchBalance attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PurchInvoiceTransOrTaxTrans name="PurchInvoiceTransOrTaxTrans">PurchInvoiceTransOrTaxTrans</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchInvoiceTransOrTaxTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PurchNum name="PurchNum">PurchNum</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchPrice name="PurchPrice">PurchPrice</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PurchTax name="PurchTax">PurchTax</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PurchUnitTxt name="PurchUnitTxt">PurchUnitTxt</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchUnitTxt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Qty name="Qty">Qty</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#ReverseChargeLine name="ReverseChargeLine">ReverseChargeLine</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Line</td></tr><tr><td>dataFormat</td><td>char</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReverseChargeLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#ReverseChargeJournal name="ReverseChargeJournal">ReverseChargeJournal</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Journal</td></tr><tr><td>dataFormat</td><td>char</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReverseChargeJournal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Journal</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#ReverseChargeAmount name="ReverseChargeAmount">ReverseChargeAmount</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reverse charge amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReverseChargeAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reverse charge amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesBalance name="SalesBalance">SalesBalance</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#SalesBalanceMST name="SalesBalanceMST">SalesBalanceMST</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#SalesTaxExchRate name="SalesTaxExchRate">SalesTaxExchRate</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxExchRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SchedDiscAmount name="SchedDiscAmount">SchedDiscAmount</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SchedDiscAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SchedDiscDate name="SchedDiscDate">SchedDiscDate</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SchedDiscDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#SchedDiscDateStr name="SchedDiscDateStr">SchedDiscDateStr</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SchedDiscDateStr attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SchedDueAmount name="SchedDueAmount">SchedDueAmount</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SchedDueAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SchedDueDate name="SchedDueDate">SchedDueDate</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SchedDueDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#SchedDueDateStr name="SchedDueDateStr">SchedDueDateStr</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SchedDueDateStr attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#sellerAddress name="sellerAddress">sellerAddress</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the sellerAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SellerEnterpriseCode name="SellerEnterpriseCode">SellerEnterpriseCode</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SellerEnterpriseCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SellerName name="SellerName">SellerName</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SellerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceTaxReverseChargeOriginAmount_IN name="ServiceTaxReverseChargeOriginAmount_IN">ServiceTaxReverseChargeOriginAmount_IN</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Service tax reverse charge mechanism</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceTaxReverseChargeOriginAmount_IN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Service tax reverse charge mechanism</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ShowAccountingCurrencyAmounts name="ShowAccountingCurrencyAmounts">ShowAccountingCurrencyAmounts</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowAccountingCurrencyAmounts attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowCopy name="ShowCopy">ShowCopy</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowCopy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowEnterpriseNumber name="ShowEnterpriseNumber">ShowEnterpriseNumber</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowEnterpriseNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowGiroField name="ShowGiroField">ShowGiroField</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowGiroField attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowInventDimColor name="ShowInventDimColor">ShowInventDimColor</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowInventDimColor attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowInventDimConfigId name="ShowInventDimConfigId">ShowInventDimConfigId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowInventDimConfigId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowInventDimSize name="ShowInventDimSize">ShowInventDimSize</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowInventDimSize attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowInventDimStyleId name="ShowInventDimStyleId">ShowInventDimStyleId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowInventDimStyleId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowInventDimVersion name="ShowInventDimVersion">ShowInventDimVersion</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowInventDimVersion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowPrePaymentDeductionSection name="ShowPrePaymentDeductionSection">ShowPrePaymentDeductionSection</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowPrePaymentDeductionSection attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowSeller name="ShowSeller">ShowSeller</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowSeller attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowTaxBalance name="ShowTaxBalance">ShowTaxBalance</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowTaxBalance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShowVendPaym name="ShowVendPaym">ShowVendPaym</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowVendPaym attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#StandardCurrency name="StandardCurrency">StandardCurrency</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#SumMarkupAmountMST name="SumMarkupAmountMST">SumMarkupAmountMST</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumMarkupAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SumTaxMST name="SumTaxMST">SumTaxMST</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#TaxableBalanceAmountMST name="TaxableBalanceAmountMST">TaxableBalanceAmountMST</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxableBalanceAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxAmount name="TaxAmount">TaxAmount</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#TaxAmountMST name="TaxAmountMST">TaxAmountMST</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#TaxBaseCurrencyCode name="TaxBaseCurrencyCode">TaxBaseCurrencyCode</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBaseCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxBaseQty name="TaxBaseQty">TaxBaseQty</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBaseQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxCode name="TaxCode">TaxCode</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#TaxDocumentNum name="TaxDocumentNum">TaxDocumentNum</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxDocumentNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxExemptDescription name="TaxExemptDescription">TaxExemptDescription</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#TaxFreeBalanceAmountMST name="TaxFreeBalanceAmountMST">TaxFreeBalanceAmountMST</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxFreeBalanceAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxInvoicePurchId name="TaxInvoicePurchId">TaxInvoicePurchId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxInvoicePurchId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxPercent name="TaxPercent">TaxPercent</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPercent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxPrintTaxFreeBalance name="TaxPrintTaxFreeBalance">TaxPrintTaxFreeBalance</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#TaxWriteCode name="TaxWriteCode">TaxWriteCode</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#TotalDiscount name="TotalDiscount">TotalDiscount</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalGrand name="TotalGrand">TotalGrand</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalGrand attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalMiscCharges name="TotalMiscCharges">TotalMiscCharges</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalMiscCharges attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalPrepaidAmount name="TotalPrepaidAmount">TotalPrepaidAmount</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalPrepaidAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalRoundOff name="TotalRoundOff">TotalRoundOff</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalRoundOff attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalSalesBalance name="TotalSalesBalance">TotalSalesBalance</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalSalesBalance attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalSalesTax name="TotalSalesTax">TotalSalesTax</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalSalesTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalsSumTax name="TotalsSumTax">TotalsSumTax</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalsSumTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalsSumTaxAmountMST name="TotalsSumTaxAmountMST">TotalsSumTaxAmountMST</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalsSumTaxAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalTaxAmountExcludedCur name="TotalTaxAmountExcludedCur">TotalTaxAmountExcludedCur</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalTaxAmountExcludedCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalTaxAmountExcludedMST name="TotalTaxAmountExcludedMST">TotalTaxAmountExcludedMST</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalTaxAmountExcludedMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotaltaxBaseAmount name="TotaltaxBaseAmount">TotaltaxBaseAmount</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotaltaxBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransportationCarrierAddress name="TransportationCarrierAddress">TransportationCarrierAddress</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#TransportationLoadedDateStr name="TransportationLoadedDateStr">TransportationLoadedDateStr</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationLoadedDateStr attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationLoadedDateTime name="TransportationLoadedDateTime">TransportationLoadedDateTime</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#VatDueDate name="VatDueDate">VatDueDate</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VatDueDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#VendAddress name="VendAddress">VendAddress</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#VendBankAccountName name="VendBankAccountName">VendBankAccountName</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendBankAccountName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendBankAccountNum name="VendBankAccountNum">VendBankAccountNum</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendBankAccountNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendBankAccountRegNum name="VendBankAccountRegNum">VendBankAccountRegNum</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendBankAccountRegNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendBankConstantSymbol name="VendBankConstantSymbol">VendBankConstantSymbol</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendBankConstantSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendBankSpecificSymbol name="VendBankSpecificSymbol">VendBankSpecificSymbol</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendBankSpecificSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendCreditInvoicing name="VendCreditInvoicing">VendCreditInvoicing</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendCreditInvoicing attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#VendInvoiceJourDueDate name="VendInvoiceJourDueDate">VendInvoiceJourDueDate</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendInvoiceJourDueDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#VendInvoiceTransLineNum name="VendInvoiceTransLineNum">VendInvoiceTransLineNum</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendInvoiceTransLineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#VendName name="VendName">VendName</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#VendorEnterpriseCode name="VendorEnterpriseCode">VendorEnterpriseCode</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorEnterpriseCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendPaymSched name="VendPaymSched">VendPaymSched</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendPaymSched attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#VendPurchReceiptDate name="VendPurchReceiptDate">VendPurchReceiptDate</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendPurchReceiptDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#VendRegNum name="VendRegNum">VendRegNum</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#VendTransCurrencyCode name="VendTransCurrencyCode">VendTransCurrencyCode</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendTransCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendTransInvoiceCurrencyCode name="VendTransInvoiceCurrencyCode">VendTransInvoiceCurrencyCode</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendTransInvoiceCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendTransSettledAmountCur name="VendTransSettledAmountCur">VendTransSettledAmountCur</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendTransSettledAmountCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#VendTransSettledAmountOriginCur name="VendTransSettledAmountOriginCur">VendTransSettledAmountOriginCur</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendTransSettledAmountOriginCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#VendTransTransDate name="VendTransTransDate">VendTransTransDate</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendTransTransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#VendTransTxt name="VendTransTxt">VendTransTxt</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendTransTxt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendVATNum name="VendVATNum">VendVATNum</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendVATNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GSTApprovalNumber_MY name="GSTApprovalNumber_MY">GSTApprovalNumber_MY</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GSTApprovalNumber_MY attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GSTSummaryText_MY name="GSTSummaryText_MY">GSTSummaryText_MY</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>GST summary</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GSTSummaryText_MY attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>GST summary</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceType_MY name="InvoiceType_MY">InvoiceType_MY</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceType_MY attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TotalAppliedAmount name="TotalAppliedAmount">TotalAppliedAmount</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Applied prepayment amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalAppliedAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Applied prepayment amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReverseChargeBalance name="ReverseChargeBalance">ReverseChargeBalance</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reverse charge balance</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReverseChargeBalance attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reverse charge balance</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LanguageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WithReducedTax_JP name="WithReducedTax_JP">WithReducedTax_JP</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithReducedTax_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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

### <a href=#Relationship_Currency_CompanyCurrencyCodeRelationshipId name="Relationship_Currency_CompanyCurrencyCodeRelationshipId">Relationship_Currency_CompanyCurrencyCodeRelationshipId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Currency_CompanyCurrencyCodeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_Currency_CurrencyCodeRelationshipId name="Relationship_Currency_CurrencyCodeRelationshipId">Relationship_Currency_CurrencyCodeRelationshipId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Currency_CurrencyCodeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_Currency_CurrencyCodeCompanyRelationshipId name="Relationship_Currency_CurrencyCodeCompanyRelationshipId">Relationship_Currency_CurrencyCodeCompanyRelationshipId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Currency_CurrencyCodeCompanyRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_Currency_CurrencyCodeMainRelationshipId name="Relationship_Currency_CurrencyCodeMainRelationshipId">Relationship_Currency_CurrencyCodeMainRelationshipId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Currency_CurrencyCodeMainRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_Currency_StandardCurrencyRelationshipId name="Relationship_Currency_StandardCurrencyRelationshipId">Relationship_Currency_StandardCurrencyRelationshipId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Currency_StandardCurrencyRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_Currency_TaxBaseCurrencyCodeRelationshipId name="Relationship_Currency_TaxBaseCurrencyCodeRelationshipId">Relationship_Currency_TaxBaseCurrencyCodeRelationshipId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Currency_TaxBaseCurrencyCodeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_Currency_VendTransCurrencyCodeRelationshipId name="Relationship_Currency_VendTransCurrencyCodeRelationshipId">Relationship_Currency_VendTransCurrencyCodeRelationshipId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Currency_VendTransCurrencyCodeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_Currency_VendTransInvoiceCurrencyCodeRelationshipId name="Relationship_Currency_VendTransInvoiceCurrencyCodeRelationshipId">Relationship_Currency_VendTransInvoiceCurrencyCodeRelationshipId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Currency_VendTransInvoiceCurrencyCodeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_InventTableRelationshipId name="Relationship_InventTableRelationshipId">Relationship_InventTableRelationshipId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/InventTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/InventTable.cdm.json/InventTable</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/InventTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymSchedRelationshipId name="Relationship_PaymSchedRelationshipId">Relationship_PaymSchedRelationshipId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymSchedRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Group/PaymSched.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/PaymSched.cdm.json/PaymSched</a></td><td><a href="../../Bank/Group/PaymSched.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchTableRelationshipId name="Relationship_PurchTableRelationshipId">Relationship_PurchTableRelationshipId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchTable.cdm.json/PurchTable</a></td><td><a href="../../../SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxTableRelationshipId name="Relationship_TaxTableRelationshipId">Relationship_TaxTableRelationshipId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Group/TaxTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxTable.cdm.json/TaxTable</a></td><td><a href="../../Tax/Group/TaxTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendInvoiceJourRelationshipId name="Relationship_VendInvoiceJourRelationshipId">Relationship_VendInvoiceJourRelationshipId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendInvoiceJourRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/VendInvoiceJour.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Transaction/VendInvoiceJour.cdm.json/VendInvoiceJour</a></td><td><a href="../Transaction/VendInvoiceJour.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LanguageTableRelationshipId name="Relationship_LanguageTableRelationshipId">Relationship_LanguageTableRelationshipId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LanguageTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Group/LanguageTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Group/LanguageTable.cdm.json/LanguageTable</a></td><td><a href="../../../System/SystemAdministration/Group/LanguageTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/VendInvoiceDocumentTmp (this entity)  

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
