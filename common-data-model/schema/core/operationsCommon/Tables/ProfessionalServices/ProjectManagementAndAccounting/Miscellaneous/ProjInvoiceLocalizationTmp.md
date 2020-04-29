---
title: ProjInvoiceLocalizationTmp - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Project invoice

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Miscellaneous/ProjInvoiceLocalizationTmp.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ProjInvoiceLocalizationTmp/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project invoice</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[AccountingCurrency](#AccountingCurrency)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[AccountingCurrencyAmountVisibility](#AccountingCurrencyAmountVisibility)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[Amount](#Amount)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[AmountInWords](#AmountInWords)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[BuyerAddress](#BuyerAddress)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[BuyerEnterpriseCode](#BuyerEnterpriseCode)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[BuyerName](#BuyerName)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[BuyerRegNum_W](#BuyerRegNum_W)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[BuyerVATNum](#BuyerVATNum)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CashDisc](#CashDisc)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CashDiscAmount](#CashDiscAmount)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CashDiscTxt](#CashDiscTxt)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[Category](#Category)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CompanyAddress](#CompanyAddress)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CompanyBankAccountName](#CompanyBankAccountName)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CompanyBankAccountNum](#CompanyBankAccountNum)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CompanyBankAccountRegNum](#CompanyBankAccountRegNum)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CompanyBankSpecificSymbol](#CompanyBankSpecificSymbol)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CompanyCommercialRegister](#CompanyCommercialRegister)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CompanyCommercialRegisterInsetNumber](#CompanyCommercialRegisterInsetNumber)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CompanyCommercialRegisterSection](#CompanyCommercialRegisterSection)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CompanyCoRegNum](#CompanyCoRegNum)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CompanyDebitDirectId](#CompanyDebitDirectId)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CompanyEmail](#CompanyEmail)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CompanyEnterpriseCode](#CompanyEnterpriseCode)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CompanyLogo](#CompanyLogo)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CompanyName](#CompanyName)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CompanyPhone](#CompanyPhone)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CompanyRegNum](#CompanyRegNum)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CompanyTeleFax](#CompanyTeleFax)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CompanyVATNum](#CompanyVATNum)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[ConstantSymbol](#ConstantSymbol)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CorrectedInvoiceId](#CorrectedInvoiceId)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CorrectiveReason](#CorrectiveReason)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CostInvTransCorrectInvIdVisibility](#CostInvTransCorrectInvIdVisibility)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CostInvTransCorrectReasonVisibility](#CostInvTransCorrectReasonVisibility)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CreditNoteReasonComment](#CreditNoteReasonComment)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CurrencyCode](#CurrencyCode)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CurrencyCodeEuro](#CurrencyCodeEuro)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[CurrencyCodeISO](#CurrencyCodeISO)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[DeliveryAddress](#DeliveryAddress)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[DeliveryName](#DeliveryName)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[DiscAmount](#DiscAmount)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[DiscDate](#DiscDate)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[DiscPercent](#DiscPercent)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[DocumentDate](#DocumentDate)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[DocuRefVisibility](#DocuRefVisibility)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[DoPrintTransportationDocument](#DoPrintTransportationDocument)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[DueAmount](#DueAmount)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[DueDate](#DueDate)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[EmplInvTransCorrectInvIdVisibility](#EmplInvTransCorrectInvIdVisibility)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[EmplInvTransCorrectReasonVisibility](#EmplInvTransCorrectReasonVisibility)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[EndDisc](#EndDisc)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[EndDiscEuro](#EndDiscEuro)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[ExchangeRate](#ExchangeRate)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[ExternalItemId](#ExternalItemId)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[ExternalItemVisibility](#ExternalItemVisibility)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[FormLetterTxt](#FormLetterTxt)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[IBAN](#IBAN)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[Intracode](#Intracode)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[InventTransVisibility](#InventTransVisibility)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[InvoiceAccount](#InvoiceAccount)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[InvoiceAccountAddress](#InvoiceAccountAddress)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[InvoiceAccountName](#InvoiceAccountName)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[InvoiceAccountVATNum](#InvoiceAccountVATNum)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[InvoiceAccountVisibility](#InvoiceAccountVisibility)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[InvoiceAmount](#InvoiceAmount)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[InvoiceAmountAccountingCurrency](#InvoiceAmountAccountingCurrency)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[InvoiceAmountEuro](#InvoiceAmountEuro)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[InvoiceDate](#InvoiceDate)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[InvoiceDateInWords](#InvoiceDateInWords)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[InvoiceNum](#InvoiceNum)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[InvoiceRoundOff](#InvoiceRoundOff)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[InvoiceRoundOffEuro](#InvoiceRoundOffEuro)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[InvoiceVATNumVisibility](#InvoiceVATNumVisibility)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[ItemId](#ItemId)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[ItemInvTransCorrectInvIdVisibility](#ItemInvTransCorrectInvIdVisibility)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[ItemInvTransCorrectReasonVisibility](#ItemInvTransCorrectReasonVisibility)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[ItemName](#ItemName)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[ItemPriceAfterDiscount](#ItemPriceAfterDiscount)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[LineAmount](#LineAmount)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[LineNumber](#LineNumber)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[LineSign](#LineSign)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[LineTaxAmount](#LineTaxAmount)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[MandateBankIBAN](#MandateBankIBAN)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[MandateReference](#MandateReference)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[MandateSWIFTNo](#MandateSWIFTNo)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[NetAmount](#NetAmount)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[NetAmountEuro](#NetAmountEuro)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[Notes](#Notes)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[OnAccInvTransCorrectInvIdVisibility](#OnAccInvTransCorrectInvIdVisibility)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[OnAccInvTransCorrectReasonVisibility](#OnAccInvTransCorrectReasonVisibility)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[OriginalInvoiceId_CZ](#OriginalInvoiceId_CZ)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[OriginalInvoiceReference](#OriginalInvoiceReference)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[PackingSlipInfo](#PackingSlipInfo)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[PackingSlipInfoItem](#PackingSlipInfoItem)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[PackingSlipInfoVisibility](#PackingSlipInfoVisibility)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[PaymentCondition](#PaymentCondition)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[PaymentId](#PaymentId)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[Periods](#Periods)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[PKWiUCode_PL](#PKWiUCode_PL)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[PrepaidAmount](#PrepaidAmount)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[PrepaidAmountEuro](#PrepaidAmountEuro)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[PrepaidNetAmount](#PrepaidNetAmount)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[PrepaidTaxAmount](#PrepaidTaxAmount)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[PrePrintLevelShow](#PrePrintLevelShow)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[PrintCode](#PrintCode)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[PrintFooter](#PrintFooter)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[PrintFooterEuro](#PrintFooterEuro)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[PrintFooterPayment](#PrintFooterPayment)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[PrintFooterPrepaid](#PrintFooterPrepaid)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[PrintFooterPrepaidEuro](#PrintFooterPrepaidEuro)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[PrintFooterSepaNotification](#PrintFooterSepaNotification)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[PrintFooterText](#PrintFooterText)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[PrintLogo](#PrintLogo)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[Project](#Project)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[ProjectRevenueInvoiceTransVisibility](#ProjectRevenueInvoiceTransVisibility)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[ProjInvoiceJourDueDate](#ProjInvoiceJourDueDate)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[ProjItemTransVisibility](#ProjItemTransVisibility)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[ProposalId](#ProposalId)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[Qty](#Qty)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[RemainAmountToBePaid](#RemainAmountToBePaid)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[RemainAmountToBePaidEuro](#RemainAmountToBePaidEuro)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[RevenueInvTransCorrectInvIdVisibility](#RevenueInvTransCorrectInvIdVisibility)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[RevenueInvTransCorrectReasonVisibility](#RevenueInvTransCorrectReasonVisibility)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[SalesBalance](#SalesBalance)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[SalesBalanceAccountingCurrency](#SalesBalanceAccountingCurrency)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[SalesBalanceEuro](#SalesBalanceEuro)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[SalesDate](#SalesDate)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[SalesOrdernum](#SalesOrdernum)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[SalesPrice](#SalesPrice)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[SalesResponsible](#SalesResponsible)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[SalesResponsibleEmail](#SalesResponsibleEmail)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[SalesResponsiblePhone](#SalesResponsiblePhone)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[SalesTaxExchangeRate](#SalesTaxExchangeRate)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[SalesUnit](#SalesUnit)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[SettleAmountCur](#SettleAmountCur)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[ShowCustPaymSched](#ShowCustPaymSched)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[ShowCustTransOffset](#ShowCustTransOffset)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[ShowDocuRef](#ShowDocuRef)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[ShowFormLetters](#ShowFormLetters)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[ShowInventTrans](#ShowInventTrans)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[ShowMarkupTrans](#ShowMarkupTrans)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[ShowProjInvoiceCost](#ShowProjInvoiceCost)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[ShowProjInvoiceEmpl](#ShowProjInvoiceEmpl)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[ShowProjInvoiceItem](#ShowProjInvoiceItem)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[ShowProjInvoiceOnAcc](#ShowProjInvoiceOnAcc)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[ShowProjInvoiceRevenue](#ShowProjInvoiceRevenue)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[ShowTaxTrans](#ShowTaxTrans)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[SMABasePrice](#SMABasePrice)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[SMAIndex](#SMAIndex)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[SMASpecIndexCalc](#SMASpecIndexCalc)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[SMASubscriptionId](#SMASubscriptionId)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[SubRevenueInvoiceTransTxtVisibility](#SubRevenueInvoiceTransTxtVisibility)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[SubRevenueInvoiceTransVisibility](#SubRevenueInvoiceTransVisibility)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[SumMarkup](#SumMarkup)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[SumMarkupEuro](#SumMarkupEuro)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[SumTax](#SumTax)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[SumTaxAccountingCurrency](#SumTaxAccountingCurrency)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[SumTaxEuro](#SumTaxEuro)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[SWIFTNo](#SWIFTNo)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TaxableBalance](#TaxableBalance)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TaxableBalanceEuro](#TaxableBalanceEuro)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TaxAmount](#TaxAmount)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TaxAmountBaseWLabel](#TaxAmountBaseWLabel)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TaxAmountBaseWVisibility](#TaxAmountBaseWVisibility)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TaxAmountEuro](#TaxAmountEuro)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TaxAmountExcluded](#TaxAmountExcluded)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TaxAmountLabel](#TaxAmountLabel)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TaxAmountMST](#TaxAmountMST)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TaxAmountMSTLabel](#TaxAmountMSTLabel)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TaxAmountMSTVisibility](#TaxAmountMSTVisibility)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TaxAmountTotalWLabel](#TaxAmountTotalWLabel)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TaxBaseAmount](#TaxBaseAmount)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TaxBaseAmount_W](#TaxBaseAmount_W)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TaxBaseQty](#TaxBaseQty)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TaxCode](#TaxCode)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TaxDirective](#TaxDirective)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TaxExcludeFromInvoice](#TaxExcludeFromInvoice)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TaxExemptDescription](#TaxExemptDescription)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TaxFreeBalance](#TaxFreeBalance)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TaxFreeBalanceEuro](#TaxFreeBalanceEuro)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TaxPrintTaxFreeBalance](#TaxPrintTaxFreeBalance)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TaxValue](#TaxValue)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TaxWriteCode](#TaxWriteCode)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TransDate](#TransDate)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TransportationCarrierAddress](#TransportationCarrierAddress)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TransportationCarrierName](#TransportationCarrierName)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TransportationContactPersonName](#TransportationContactPersonName)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TransportationContactPersonTitle](#TransportationContactPersonTitle)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TransportationDataSection](#TransportationDataSection)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TransPortationIssuedByName](#TransPortationIssuedByName)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TransportationIssuedByTitle](#TransportationIssuedByTitle)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TransportationLoadedAddress](#TransportationLoadedAddress)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TransportationLoadedDateTime](#TransportationLoadedDateTime)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TransportationLoadedName](#TransportationLoadedName)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TransportationPackageDangerDegree](#TransportationPackageDangerDegree)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TransportationPackageDescription](#TransportationPackageDescription)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TransportationVehicleDescription](#TransportationVehicleDescription)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TransportationVehicleDriverName](#TransportationVehicleDriverName)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TransportationVehiclePlateNumber](#TransportationVehiclePlateNumber)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[TransportationVehicleTrailerNumber](#TransportationVehicleTrailerNumber)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[Txt](#Txt)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[VatDueDate_W](#VatDueDate_W)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[VATNum](#VATNum)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[DataAreaId](#DataAreaId)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[Relationship_AccountingCurrencyRelationshipId](#Relationship_AccountingCurrencyRelationshipId)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[Relationship_Currency_EuroRelationshipId](#Relationship_Currency_EuroRelationshipId)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[Relationship_CustTableRelationshipId](#Relationship_CustTableRelationshipId)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[Relationship_InventTableRelationshipId](#Relationship_InventTableRelationshipId)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[Relationship_ISOCurrencyCodeRelationshipId](#Relationship_ISOCurrencyCodeRelationshipId)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[Relationship_ProjCategoryRelationshipId](#Relationship_ProjCategoryRelationshipId)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[Relationship_ProjInvoiceJourRelationshipId](#Relationship_ProjInvoiceJourRelationshipId)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[Relationship_ProjInvoiceTableRelationshipId](#Relationship_ProjInvoiceTableRelationshipId)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[Relationship_ProjTableRelationshipId](#Relationship_ProjTableRelationshipId)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[Relationship_SMASubscriptionTableRelationshipId](#Relationship_SMASubscriptionTableRelationshipId)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[Relationship_TaxTableRelationshipId](#Relationship_TaxTableRelationshipId)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="ProjInvoiceLocalizationTmp.md" target="_blank">Miscellaneous/ProjInvoiceLocalizationTmp</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ProjInvoiceLocalizationTmp/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountingCurrency name="AccountingCurrency">AccountingCurrency</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountingCurrencyAmountVisibility name="AccountingCurrencyAmountVisibility">AccountingCurrencyAmountVisibility</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingCurrencyAmountVisibility attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Amount name="Amount">Amount</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Amount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AmountInWords name="AmountInWords">AmountInWords</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountInWords attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BuyerAddress name="BuyerAddress">BuyerAddress</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BuyerAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BuyerEnterpriseCode name="BuyerEnterpriseCode">BuyerEnterpriseCode</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BuyerEnterpriseCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BuyerName name="BuyerName">BuyerName</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BuyerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BuyerRegNum_W name="BuyerRegNum_W">BuyerRegNum_W</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BuyerRegNum_W attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BuyerVATNum name="BuyerVATNum">BuyerVATNum</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BuyerVATNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDisc name="CashDisc">CashDisc</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDisc attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CashDiscAmount name="CashDiscAmount">CashDiscAmount</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CashDiscTxt name="CashDiscTxt">CashDiscTxt</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscTxt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Category name="Category">Category</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Category attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyAddress name="CompanyAddress">CompanyAddress</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyBankAccountName name="CompanyBankAccountName">CompanyBankAccountName</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyBankAccountName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyBankAccountNum name="CompanyBankAccountNum">CompanyBankAccountNum</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyBankAccountNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyBankAccountRegNum name="CompanyBankAccountRegNum">CompanyBankAccountRegNum</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyBankAccountRegNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyBankSpecificSymbol name="CompanyBankSpecificSymbol">CompanyBankSpecificSymbol</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyBankSpecificSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyCommercialRegister name="CompanyCommercialRegister">CompanyCommercialRegister</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyCommercialRegister attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyCommercialRegisterInsetNumber name="CompanyCommercialRegisterInsetNumber">CompanyCommercialRegisterInsetNumber</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyCommercialRegisterInsetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyCommercialRegisterSection name="CompanyCommercialRegisterSection">CompanyCommercialRegisterSection</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyCommercialRegisterSection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyCoRegNum name="CompanyCoRegNum">CompanyCoRegNum</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyCoRegNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyDebitDirectId name="CompanyDebitDirectId">CompanyDebitDirectId</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyDebitDirectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyEmail name="CompanyEmail">CompanyEmail</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyEmail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyEnterpriseCode name="CompanyEnterpriseCode">CompanyEnterpriseCode</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyEnterpriseCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyLogo name="CompanyLogo">CompanyLogo</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyLogo attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyName name="CompanyName">CompanyName</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyPhone name="CompanyPhone">CompanyPhone</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyPhone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyRegNum name="CompanyRegNum">CompanyRegNum</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyRegNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyTeleFax name="CompanyTeleFax">CompanyTeleFax</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyTeleFax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyVATNum name="CompanyVATNum">CompanyVATNum</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyVATNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConstantSymbol name="ConstantSymbol">ConstantSymbol</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConstantSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectedInvoiceId name="CorrectedInvoiceId">CorrectedInvoiceId</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedInvoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectiveReason name="CorrectiveReason">CorrectiveReason</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectiveReason attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostInvTransCorrectInvIdVisibility name="CostInvTransCorrectInvIdVisibility">CostInvTransCorrectInvIdVisibility</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostInvTransCorrectInvIdVisibility attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostInvTransCorrectReasonVisibility name="CostInvTransCorrectReasonVisibility">CostInvTransCorrectReasonVisibility</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostInvTransCorrectReasonVisibility attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditNoteReasonComment name="CreditNoteReasonComment">CreditNoteReasonComment</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditNoteReasonComment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

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

### <a href=#CurrencyCodeEuro name="CurrencyCodeEuro">CurrencyCodeEuro</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCodeEuro attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCodeISO name="CurrencyCodeISO">CurrencyCodeISO</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCodeISO attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddress name="DeliveryAddress">DeliveryAddress</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryName name="DeliveryName">DeliveryName</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delivery name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscAmount name="DiscAmount">DiscAmount</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DiscDate name="DiscDate">DiscDate</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DiscPercent name="DiscPercent">DiscPercent</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Discount in percentage</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscPercent attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Discount in percentage</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DocumentDate name="DocumentDate">DocumentDate</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DocuRefVisibility name="DocuRefVisibility">DocuRefVisibility</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuRefVisibility attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DoPrintTransportationDocument name="DoPrintTransportationDocument">DoPrintTransportationDocument</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DoPrintTransportationDocument attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DueAmount name="DueAmount">DueAmount</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DueAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoice amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DueDate name="DueDate">DueDate</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DueDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#EmplInvTransCorrectInvIdVisibility name="EmplInvTransCorrectInvIdVisibility">EmplInvTransCorrectInvIdVisibility</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmplInvTransCorrectInvIdVisibility attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmplInvTransCorrectReasonVisibility name="EmplInvTransCorrectReasonVisibility">EmplInvTransCorrectReasonVisibility</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmplInvTransCorrectReasonVisibility attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndDisc name="EndDisc">EndDisc</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total discount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDisc attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total discount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#EndDiscEuro name="EndDiscEuro">EndDiscEuro</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDiscEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ExchangeRate name="ExchangeRate">ExchangeRate</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ExternalItemId name="ExternalItemId">ExternalItemId</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternalItemVisibility name="ExternalItemVisibility">ExternalItemVisibility</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalItemVisibility attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormLetterTxt name="FormLetterTxt">FormLetterTxt</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormLetterTxt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IBAN name="IBAN">IBAN</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IBAN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Intracode name="Intracode">Intracode</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Intracode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTransVisibility name="InventTransVisibility">InventTransVisibility</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTransVisibility attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAccount name="InvoiceAccount">InvoiceAccount</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAccountAddress name="InvoiceAccountAddress">InvoiceAccountAddress</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAccountAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAccountName name="InvoiceAccountName">InvoiceAccountName</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAccountName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAccountVATNum name="InvoiceAccountVATNum">InvoiceAccountVATNum</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAccountVATNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAccountVisibility name="InvoiceAccountVisibility">InvoiceAccountVisibility</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAccountVisibility attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InvoiceAmount name="InvoiceAmount">InvoiceAmount</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoice amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InvoiceAmountAccountingCurrency name="InvoiceAmountAccountingCurrency">InvoiceAmountAccountingCurrency</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAmountAccountingCurrency attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InvoiceAmountEuro name="InvoiceAmountEuro">InvoiceAmountEuro</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAmountEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InvoiceDate name="InvoiceDate">InvoiceDate</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#InvoiceDateInWords name="InvoiceDateInWords">InvoiceDateInWords</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceDateInWords attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceNum name="InvoiceNum">InvoiceNum</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceRoundOff name="InvoiceRoundOff">InvoiceRoundOff</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceRoundOff attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InvoiceRoundOffEuro name="InvoiceRoundOffEuro">InvoiceRoundOffEuro</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceRoundOffEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InvoiceVATNumVisibility name="InvoiceVATNumVisibility">InvoiceVATNumVisibility</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceVATNumVisibility attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemInvTransCorrectInvIdVisibility name="ItemInvTransCorrectInvIdVisibility">ItemInvTransCorrectInvIdVisibility</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemInvTransCorrectInvIdVisibility attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemInvTransCorrectReasonVisibility name="ItemInvTransCorrectReasonVisibility">ItemInvTransCorrectReasonVisibility</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemInvTransCorrectReasonVisibility attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemName name="ItemName">ItemName</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemPriceAfterDiscount name="ItemPriceAfterDiscount">ItemPriceAfterDiscount</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemPriceAfterDiscount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LineAmount name="LineAmount">LineAmount</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Line amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Line amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LineSign name="LineSign">LineSign</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>char</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineSign attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#LineTaxAmount name="LineTaxAmount">LineTaxAmount</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineTaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MandateBankIBAN name="MandateBankIBAN">MandateBankIBAN</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MandateBankIBAN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MandateReference name="MandateReference">MandateReference</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MandateReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MandateSWIFTNo name="MandateSWIFTNo">MandateSWIFTNo</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MandateSWIFTNo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NetAmount name="NetAmount">NetAmount</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#NetAmountEuro name="NetAmountEuro">NetAmountEuro</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetAmountEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Notes name="Notes">Notes</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Notes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnAccInvTransCorrectInvIdVisibility name="OnAccInvTransCorrectInvIdVisibility">OnAccInvTransCorrectInvIdVisibility</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnAccInvTransCorrectInvIdVisibility attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnAccInvTransCorrectReasonVisibility name="OnAccInvTransCorrectReasonVisibility">OnAccInvTransCorrectReasonVisibility</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnAccInvTransCorrectReasonVisibility attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginalInvoiceId_CZ name="OriginalInvoiceId_CZ">OriginalInvoiceId_CZ</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalInvoiceId_CZ attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginalInvoiceReference name="OriginalInvoiceReference">OriginalInvoiceReference</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalInvoiceReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackingSlipInfo name="PackingSlipInfo">PackingSlipInfo</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingSlipInfo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackingSlipInfoItem name="PackingSlipInfoItem">PackingSlipInfoItem</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingSlipInfoItem attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackingSlipInfoVisibility name="PackingSlipInfoVisibility">PackingSlipInfoVisibility</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Visibility</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingSlipInfoVisibility attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Visibility</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PaymentCondition name="PaymentCondition">PaymentCondition</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentCondition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentId name="PaymentId">PaymentId</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Periods name="Periods">Periods</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Periods attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PKWiUCode_PL name="PKWiUCode_PL">PKWiUCode_PL</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PKWiUCode_PL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrepaidAmount name="PrepaidAmount">PrepaidAmount</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrepaidAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PrepaidAmountEuro name="PrepaidAmountEuro">PrepaidAmountEuro</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrepaidAmountEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PrepaidNetAmount name="PrepaidNetAmount">PrepaidNetAmount</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrepaidNetAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PrepaidTaxAmount name="PrepaidTaxAmount">PrepaidTaxAmount</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrepaidTaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PrePrintLevelShow name="PrePrintLevelShow">PrePrintLevelShow</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrePrintLevelShow attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintCode name="PrintCode">PrintCode</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintFooter name="PrintFooter">PrintFooter</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintFooter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintFooterEuro name="PrintFooterEuro">PrintFooterEuro</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintFooterEuro attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintFooterPayment name="PrintFooterPayment">PrintFooterPayment</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintFooterPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintFooterPrepaid name="PrintFooterPrepaid">PrintFooterPrepaid</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintFooterPrepaid attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintFooterPrepaidEuro name="PrintFooterPrepaidEuro">PrintFooterPrepaidEuro</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintFooterPrepaidEuro attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintFooterSepaNotification name="PrintFooterSepaNotification">PrintFooterSepaNotification</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintFooterSepaNotification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintFooterText name="PrintFooterText">PrintFooterText</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintFooterText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintLogo name="PrintLogo">PrintLogo</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintLogo attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Project name="Project">Project</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Project attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectRevenueInvoiceTransVisibility name="ProjectRevenueInvoiceTransVisibility">ProjectRevenueInvoiceTransVisibility</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectRevenueInvoiceTransVisibility attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjInvoiceJourDueDate name="ProjInvoiceJourDueDate">ProjInvoiceJourDueDate</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjInvoiceJourDueDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ProjItemTransVisibility name="ProjItemTransVisibility">ProjItemTransVisibility</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjItemTransVisibility attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProposalId name="ProposalId">ProposalId</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProposalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Qty name="Qty">Qty</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Deliver now</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Qty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Deliver now</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RemainAmountToBePaid name="RemainAmountToBePaid">RemainAmountToBePaid</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainAmountToBePaid attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RemainAmountToBePaidEuro name="RemainAmountToBePaidEuro">RemainAmountToBePaidEuro</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainAmountToBePaidEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RevenueInvTransCorrectInvIdVisibility name="RevenueInvTransCorrectInvIdVisibility">RevenueInvTransCorrectInvIdVisibility</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevenueInvTransCorrectInvIdVisibility attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevenueInvTransCorrectReasonVisibility name="RevenueInvTransCorrectReasonVisibility">RevenueInvTransCorrectReasonVisibility</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevenueInvTransCorrectReasonVisibility attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesBalance name="SalesBalance">SalesBalance</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales subtotal amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesBalance attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales subtotal amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesBalanceAccountingCurrency name="SalesBalanceAccountingCurrency">SalesBalanceAccountingCurrency</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesBalanceAccountingCurrency attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesBalanceEuro name="SalesBalanceEuro">SalesBalanceEuro</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesBalanceEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesDate name="SalesDate">SalesDate</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#SalesOrdernum name="SalesOrdernum">SalesOrdernum</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrdernum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPrice name="SalesPrice">SalesPrice</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesResponsible name="SalesResponsible">SalesResponsible</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesResponsible attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesResponsibleEmail name="SalesResponsibleEmail">SalesResponsibleEmail</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesResponsibleEmail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesResponsiblePhone name="SalesResponsiblePhone">SalesResponsiblePhone</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesResponsiblePhone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxExchangeRate name="SalesTaxExchangeRate">SalesTaxExchangeRate</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxExchangeRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesUnit name="SalesUnit">SalesUnit</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettleAmountCur name="SettleAmountCur">SettleAmountCur</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Settled currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettleAmountCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Settled currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ShowCustPaymSched name="ShowCustPaymSched">ShowCustPaymSched</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowCustPaymSched attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowCustTransOffset name="ShowCustTransOffset">ShowCustTransOffset</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowCustTransOffset attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowDocuRef name="ShowDocuRef">ShowDocuRef</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowDocuRef attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowFormLetters name="ShowFormLetters">ShowFormLetters</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowFormLetters attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowInventTrans name="ShowInventTrans">ShowInventTrans</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowInventTrans attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowMarkupTrans name="ShowMarkupTrans">ShowMarkupTrans</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowMarkupTrans attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowProjInvoiceCost name="ShowProjInvoiceCost">ShowProjInvoiceCost</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowProjInvoiceCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowProjInvoiceEmpl name="ShowProjInvoiceEmpl">ShowProjInvoiceEmpl</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowProjInvoiceEmpl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowProjInvoiceItem name="ShowProjInvoiceItem">ShowProjInvoiceItem</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowProjInvoiceItem attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowProjInvoiceOnAcc name="ShowProjInvoiceOnAcc">ShowProjInvoiceOnAcc</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowProjInvoiceOnAcc attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowProjInvoiceRevenue name="ShowProjInvoiceRevenue">ShowProjInvoiceRevenue</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowProjInvoiceRevenue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowTaxTrans name="ShowTaxTrans">ShowTaxTrans</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowTaxTrans attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SMABasePrice name="SMABasePrice">SMABasePrice</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SMABasePrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SMAIndex name="SMAIndex">SMAIndex</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SMAIndex attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SMASpecIndexCalc name="SMASpecIndexCalc">SMASpecIndexCalc</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SMASpecIndexCalc attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SMASubscriptionId name="SMASubscriptionId">SMASubscriptionId</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SMASubscriptionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubRevenueInvoiceTransTxtVisibility name="SubRevenueInvoiceTransTxtVisibility">SubRevenueInvoiceTransTxtVisibility</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubRevenueInvoiceTransTxtVisibility attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubRevenueInvoiceTransVisibility name="SubRevenueInvoiceTransVisibility">SubRevenueInvoiceTransVisibility</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubRevenueInvoiceTransVisibility attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SumMarkup name="SumMarkup">SumMarkup</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumMarkup attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SumMarkupEuro name="SumMarkupEuro">SumMarkupEuro</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumMarkupEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SumTax name="SumTax">SumTax</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SumTaxAccountingCurrency name="SumTaxAccountingCurrency">SumTaxAccountingCurrency</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumTaxAccountingCurrency attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SumTaxEuro name="SumTaxEuro">SumTaxEuro</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumTaxEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SWIFTNo name="SWIFTNo">SWIFTNo</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SWIFTNo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxableBalance name="TaxableBalance">TaxableBalance</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxableBalance attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxableBalanceEuro name="TaxableBalanceEuro">TaxableBalanceEuro</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxableBalanceEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxAmount name="TaxAmount">TaxAmount</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxAmountBaseWLabel name="TaxAmountBaseWLabel">TaxAmountBaseWLabel</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountBaseWLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmountBaseWVisibility name="TaxAmountBaseWVisibility">TaxAmountBaseWVisibility</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountBaseWVisibility attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmountEuro name="TaxAmountEuro">TaxAmountEuro</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxAmountExcluded name="TaxAmountExcluded">TaxAmountExcluded</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountExcluded attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxAmountLabel name="TaxAmountLabel">TaxAmountLabel</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmountMST name="TaxAmountMST">TaxAmountMST</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxAmountMSTLabel name="TaxAmountMSTLabel">TaxAmountMSTLabel</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountMSTLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmountMSTVisibility name="TaxAmountMSTVisibility">TaxAmountMSTVisibility</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountMSTVisibility attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmountTotalWLabel name="TaxAmountTotalWLabel">TaxAmountTotalWLabel</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountTotalWLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxBaseAmount name="TaxBaseAmount">TaxBaseAmount</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxBaseAmount_W name="TaxBaseAmount_W">TaxBaseAmount_W</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBaseAmount_W attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxBaseQty name="TaxBaseQty">TaxBaseQty</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBaseQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxCode name="TaxCode">TaxCode</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxDirective name="TaxDirective">TaxDirective</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Directive</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxDirective attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Directive</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxExcludeFromInvoice name="TaxExcludeFromInvoice">TaxExcludeFromInvoice</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxExcludeFromInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxExemptDescription name="TaxExemptDescription">TaxExemptDescription</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxExemptDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxFreeBalance name="TaxFreeBalance">TaxFreeBalance</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxFreeBalance attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxFreeBalanceEuro name="TaxFreeBalanceEuro">TaxFreeBalanceEuro</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxFreeBalanceEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxPrintTaxFreeBalance name="TaxPrintTaxFreeBalance">TaxPrintTaxFreeBalance</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPrintTaxFreeBalance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxValue name="TaxValue">TaxValue</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxWriteCode name="TaxWriteCode">TaxWriteCode</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWriteCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationCarrierAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationCarrierName name="TransportationCarrierName">TransportationCarrierName</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationCarrierName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationContactPersonName name="TransportationContactPersonName">TransportationContactPersonName</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationContactPersonName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationContactPersonTitle name="TransportationContactPersonTitle">TransportationContactPersonTitle</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationContactPersonTitle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationDataSection name="TransportationDataSection">TransportationDataSection</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transportation invoices</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationDataSection attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transportation invoices</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TransPortationIssuedByName name="TransPortationIssuedByName">TransPortationIssuedByName</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransPortationIssuedByName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationIssuedByTitle name="TransportationIssuedByTitle">TransportationIssuedByTitle</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationIssuedByTitle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationLoadedAddress name="TransportationLoadedAddress">TransportationLoadedAddress</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationLoadedAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationLoadedDateTime name="TransportationLoadedDateTime">TransportationLoadedDateTime</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationLoadedDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#TransportationLoadedName name="TransportationLoadedName">TransportationLoadedName</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationLoadedName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationPackageDangerDegree name="TransportationPackageDangerDegree">TransportationPackageDangerDegree</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationPackageDangerDegree attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationPackageDescription name="TransportationPackageDescription">TransportationPackageDescription</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationPackageDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationVehicleDescription name="TransportationVehicleDescription">TransportationVehicleDescription</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationVehicleDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationVehicleDriverName name="TransportationVehicleDriverName">TransportationVehicleDriverName</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationVehicleDriverName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationVehiclePlateNumber name="TransportationVehiclePlateNumber">TransportationVehiclePlateNumber</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationVehiclePlateNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationVehicleTrailerNumber name="TransportationVehicleTrailerNumber">TransportationVehicleTrailerNumber</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationVehicleTrailerNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Txt name="Txt">Txt</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Txt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VatDueDate_W name="VatDueDate_W">VatDueDate_W</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VatDueDate_W attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#VATNum name="VATNum">VATNum</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

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

### <a href=#Relationship_AccountingCurrencyRelationshipId name="Relationship_AccountingCurrencyRelationshipId">Relationship_AccountingCurrencyRelationshipId</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AccountingCurrencyRelationshipId attribute are listed below.</summary>

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

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

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

### <a href=#Relationship_Currency_EuroRelationshipId name="Relationship_Currency_EuroRelationshipId">Relationship_Currency_EuroRelationshipId</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Currency_EuroRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CustTableRelationshipId name="Relationship_CustTableRelationshipId">Relationship_CustTableRelationshipId</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTableRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_InventTableRelationshipId name="Relationship_InventTableRelationshipId">Relationship_InventTableRelationshipId</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

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

### <a href=#Relationship_ISOCurrencyCodeRelationshipId name="Relationship_ISOCurrencyCodeRelationshipId">Relationship_ISOCurrencyCodeRelationshipId</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ISOCurrencyCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Reference/ISOCurrencyCode.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Reference/ISOCurrencyCode.cdm.json/ISOCurrencyCode</a></td><td><a href="../../../Common/Currency/Reference/ISOCurrencyCode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjCategoryRelationshipId name="Relationship_ProjCategoryRelationshipId">Relationship_ProjCategoryRelationshipId</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjCategoryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ProjCategory.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjCategory.cdm.json/ProjCategory</a></td><td><a href="../Group/ProjCategory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjInvoiceJourRelationshipId name="Relationship_ProjInvoiceJourRelationshipId">Relationship_ProjInvoiceJourRelationshipId</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjInvoiceJourRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/ProjInvoiceJour.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjInvoiceJour.cdm.json/ProjInvoiceJour</a></td><td><a href="../Transaction/ProjInvoiceJour.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjInvoiceTableRelationshipId name="Relationship_ProjInvoiceTableRelationshipId">Relationship_ProjInvoiceTableRelationshipId</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjInvoiceTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/ProjInvoiceTable.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Main/ProjInvoiceTable.cdm.json/ProjInvoiceTable</a></td><td><a href="../Main/ProjInvoiceTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjTableRelationshipId name="Relationship_ProjTableRelationshipId">Relationship_ProjTableRelationshipId</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/ProjTable.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Main/ProjTable.cdm.json/ProjTable</a></td><td><a href="../Main/ProjTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SMASubscriptionTableRelationshipId name="Relationship_SMASubscriptionTableRelationshipId">Relationship_SMASubscriptionTableRelationshipId</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SMASubscriptionTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ServiceManagement/Main/SMASubscriptionTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ServiceManagement/Main/SMASubscriptionTable.cdm.json/SMASubscriptionTable</a></td><td><a href="../../../SupplyChain/ServiceManagement/Main/SMASubscriptionTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxTableRelationshipId name="Relationship_TaxTableRelationshipId">Relationship_TaxTableRelationshipId</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Group/TaxTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxTable.cdm.json/TaxTable</a></td><td><a href="../../../Finance/Tax/Group/TaxTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/ProjInvoiceLocalizationTmp (this entity)  

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
