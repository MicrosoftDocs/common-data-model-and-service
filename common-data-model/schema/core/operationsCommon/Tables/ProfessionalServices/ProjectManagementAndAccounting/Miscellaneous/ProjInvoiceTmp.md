---
title: ProjInvoiceTmp - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# ProjInvoiceTmp

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Miscellaneous/ProjInvoiceTmp.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ProjInvoiceTmp/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[AccountNo1](#AccountNo1)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[AccountNo2](#AccountNo2)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[AccountNum1_FI](#AccountNum1_FI)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[AccountNum2_FI](#AccountNum2_FI)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[AccountNum3_FI](#AccountNum3_FI)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[AccountNum4_FI](#AccountNum4_FI)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[AccountNum5_FI](#AccountNum5_FI)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[AccountNum6_FI](#AccountNum6_FI)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[Amount](#Amount)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[Amount2](#Amount2)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[Amount2Dec](#Amount2Dec)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[AmountCheckId](#AmountCheckId)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[BankAccountTable_AccountNum_CH](#BankAccountTable_AccountNum_CH)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[BankAccountTable_Clearing_CH](#BankAccountTable_Clearing_CH)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[BankGroupIdName_CH1](#BankGroupIdName_CH1)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[BankZipCode_CH](#BankZipCode_CH)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[CashAccountingRegime_ES](#CashAccountingRegime_ES)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[CashDisc](#CashDisc)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[CashDiscAmount](#CashDiscAmount)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[CashDiscOnInvoice](#CashDiscOnInvoice)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[CashDiscTxt](#CashDiscTxt)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[Category](#Category)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[CompanyAddress](#CompanyAddress)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[CompanyCoRegNum](#CompanyCoRegNum)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[CompanyDebitDirectId](#CompanyDebitDirectId)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[CompanyEnterpriseNumber](#CompanyEnterpriseNumber)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[CompanyGiro](#CompanyGiro)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[CompanyLogo](#CompanyLogo)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[CompanyName](#CompanyName)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[CompanyPhone](#CompanyPhone)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[CompanyTeleFax](#CompanyTeleFax)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[CompanyVATNum](#CompanyVATNum)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[CompanyVATNumVisibility](#CompanyVATNumVisibility)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[CorrectedInvoiceId](#CorrectedInvoiceId)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[CorrectiveReason](#CorrectiveReason)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[CostInvTransCorrectInvIdVisibility](#CostInvTransCorrectInvIdVisibility)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[CostInvTransCorrectReasonVisibility](#CostInvTransCorrectReasonVisibility)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[CurrencyCode](#CurrencyCode)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[CurrencyCodeEuro](#CurrencyCodeEuro)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[CurrencyCodeISO](#CurrencyCodeISO)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[CustAccountExt](#CustAccountExt)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[CustAddress_CH](#CustAddress_CH)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[CustName_CH](#CustName_CH)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[DeliveryAddress](#DeliveryAddress)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[DeliveryName](#DeliveryName)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[Description_CH](#Description_CH)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[DiscAmount](#DiscAmount)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[DiscDate](#DiscDate)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[DiscPercent](#DiscPercent)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[DocuRefVisibility](#DocuRefVisibility)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[DueAmount](#DueAmount)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[DueDate](#DueDate)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[EmplInvTransCorrectInvIdVisibility](#EmplInvTransCorrectInvIdVisibility)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[EmplInvTransCorrectReasonVisibility](#EmplInvTransCorrectReasonVisibility)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[EndDisc](#EndDisc)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[EndDiscEuro](#EndDiscEuro)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[EnterpriseNumber](#EnterpriseNumber)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[Enterpriseregister_NO](#Enterpriseregister_NO)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[ExternalItemId](#ExternalItemId)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[ExternalItemVisibility](#ExternalItemVisibility)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[FiCreditorId](#FiCreditorId)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[Footer](#Footer)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[FormLetterTxt](#FormLetterTxt)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[GiroSection](#GiroSection)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[GiroType](#GiroType)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[InfoMessage](#InfoMessage)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[InventTransVisibility](#InventTransVisibility)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[InvoiceAccount](#InvoiceAccount)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[InvoiceAccountAddress](#InvoiceAccountAddress)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[InvoiceAmount](#InvoiceAmount)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[InvoiceAmountDecimals](#InvoiceAmountDecimals)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[InvoiceAmountEuro](#InvoiceAmountEuro)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[InvoiceAmountNoDecimals](#InvoiceAmountNoDecimals)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[InvoiceDate](#InvoiceDate)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[InvoiceName](#InvoiceName)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[InvoiceNum](#InvoiceNum)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[InvoiceReferenceNumberFI](#InvoiceReferenceNumberFI)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[InvoiceRoundOff](#InvoiceRoundOff)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[InvoiceRoundOffEuro](#InvoiceRoundOffEuro)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[InvoiceTxt](#InvoiceTxt)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[ItemId](#ItemId)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[ItemInvTransCorrectInvIdVisibility](#ItemInvTransCorrectInvIdVisibility)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[ItemInvTransCorrectReasonVisibility](#ItemInvTransCorrectReasonVisibility)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[LayoutCode_CH](#LayoutCode_CH)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[LineAmount](#LineAmount)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[MandateBankIBAN](#MandateBankIBAN)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[MandateReference](#MandateReference)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[MandateSWIFTNo](#MandateSWIFTNo)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[MarkupAmount_FI](#MarkupAmount_FI)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[MarkupCode_FI](#MarkupCode_FI)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[NetAmount](#NetAmount)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[NetAmountEuro](#NetAmountEuro)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[Notes](#Notes)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[NPIBankingPaymId](#NPIBankingPaymId)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[NPIBankingPaymIdVisibility](#NPIBankingPaymIdVisibility)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[OCRField](#OCRField)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[OCRLine_CH](#OCRLine_CH)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[OCRLine_FI](#OCRLine_FI)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[OnAccInvTransCorrectInvIdVisibility](#OnAccInvTransCorrectInvIdVisibility)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[OnAccInvTransCorrectReasonVisibility](#OnAccInvTransCorrectReasonVisibility)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[PackingSlipInfo](#PackingSlipInfo)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[PackingSlipInfoItem](#PackingSlipInfoItem)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[PackingSlipInfoVisibility](#PackingSlipInfoVisibility)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[PaymentCondition](#PaymentCondition)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[PaymentId](#PaymentId)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[PaymentId2_PaymentId3_CH](#PaymentId2_PaymentId3_CH)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[PaymentRef1_CH](#PaymentRef1_CH)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[PaymentRef2_CH](#PaymentRef2_CH)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[Periods](#Periods)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[PrepaidAmount](#PrepaidAmount)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[PrepaidAmountEuro](#PrepaidAmountEuro)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[PrepaidCurrencyCode](#PrepaidCurrencyCode)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[PrepaidCurrencyCodeEuro](#PrepaidCurrencyCodeEuro)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[PrepaidInvoiceAmount](#PrepaidInvoiceAmount)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[PrepaidInvoiceAmountEuro](#PrepaidInvoiceAmountEuro)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[PrepaidNetAmount](#PrepaidNetAmount)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[PrepaidTaxAmount](#PrepaidTaxAmount)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[PrePrintLevelShow](#PrePrintLevelShow)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[PrintCode](#PrintCode)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[PrintFooter](#PrintFooter)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[PrintFooterEuro](#PrintFooterEuro)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[PrintFooterPayment](#PrintFooterPayment)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[PrintFooterPrepaid](#PrintFooterPrepaid)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[PrintFooterPrepaidEuro](#PrintFooterPrepaidEuro)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[PrintFooterSepaNotification](#PrintFooterSepaNotification)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[PrintFooterText](#PrintFooterText)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[PrintGiro](#PrintGiro)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[PrintLogo](#PrintLogo)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[Project](#Project)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[ProjectRevenueInvoiceTransVisibility](#ProjectRevenueInvoiceTransVisibility)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[ProjInvoiceJourDueDate](#ProjInvoiceJourDueDate)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[ProjInvRefNum_FIVisibility](#ProjInvRefNum_FIVisibility)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[ProjItemTransVisibility](#ProjItemTransVisibility)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[Qty](#Qty)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[ReferenceNumber_FI](#ReferenceNumber_FI)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[ReferenceNumber_FI1](#ReferenceNumber_FI1)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[RemainAmountToBePaid](#RemainAmountToBePaid)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[RemainAmountToBePaidEuro](#RemainAmountToBePaidEuro)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[RevenueInvTransCorrectInvIdVisibility](#RevenueInvTransCorrectInvIdVisibility)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[RevenueInvTransCorrectReasonVisibility](#RevenueInvTransCorrectReasonVisibility)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[SalesBalance](#SalesBalance)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[SalesBalanceEuro](#SalesBalanceEuro)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[SalesOrdernum](#SalesOrdernum)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[SalesPrice](#SalesPrice)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[SalesTaxCode_FI](#SalesTaxCode_FI)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[SettleAmountCur](#SettleAmountCur)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[ShowCustPaymSched](#ShowCustPaymSched)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[ShowCustTransOffset](#ShowCustTransOffset)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[ShowDocuRef](#ShowDocuRef)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[ShowFormLetters](#ShowFormLetters)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[ShowInventTrans](#ShowInventTrans)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[ShowMarkupTrans](#ShowMarkupTrans)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[ShowPrepaidTotals](#ShowPrepaidTotals)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[ShowPrepaidTotalsEuro](#ShowPrepaidTotalsEuro)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[ShowProjInvoiceCost](#ShowProjInvoiceCost)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[ShowProjInvoiceEmpl](#ShowProjInvoiceEmpl)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[ShowProjInvoiceItem](#ShowProjInvoiceItem)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[ShowProjInvoiceOnAcc](#ShowProjInvoiceOnAcc)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[ShowProjInvoiceRevenue](#ShowProjInvoiceRevenue)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[ShowProjItemTrans](#ShowProjItemTrans)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[ShowTaxTrans](#ShowTaxTrans)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[SMABasePrice](#SMABasePrice)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[SMAIndex](#SMAIndex)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[SMASpecIndexCalc](#SMASpecIndexCalc)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[SMASubscriptionId](#SMASubscriptionId)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[SubRevenueInvoiceTransTxtVisibility](#SubRevenueInvoiceTransTxtVisibility)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[SubRevenueInvoiceTransVisibility](#SubRevenueInvoiceTransVisibility)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[SumMarkup](#SumMarkup)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[SumMarkupEuro](#SumMarkupEuro)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[SumTax](#SumTax)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[SumTaxEuro](#SumTaxEuro)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[TaxableBalance](#TaxableBalance)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[TaxableBalanceEuro](#TaxableBalanceEuro)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[TaxAmount](#TaxAmount)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[TaxAmountLabel](#TaxAmountLabel)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[TaxAmountMST](#TaxAmountMST)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[TaxAmountMSTLabel](#TaxAmountMSTLabel)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[TaxAmountMSTVisibility](#TaxAmountMSTVisibility)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[TaxBaseAmount](#TaxBaseAmount)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[TaxBaseQty](#TaxBaseQty)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[TaxCode](#TaxCode)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[TaxExemptDescription](#TaxExemptDescription)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[TaxFreeBalance](#TaxFreeBalance)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[TaxFreeBalanceEuro](#TaxFreeBalanceEuro)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[TaxPrintTaxFreeBalance](#TaxPrintTaxFreeBalance)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[TaxWriteCode](#TaxWriteCode)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[TransDate](#TransDate)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[Txt](#Txt)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[VATNum](#VATNum)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[VATNumVisibility](#VATNumVisibility)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[IBAN_CH](#IBAN_CH)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[InvoiceAddressLine1_CH](#InvoiceAddressLine1_CH)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[InvoiceAddressLine2_CH](#InvoiceAddressLine2_CH)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[InvoiceCountryRegionId_CH](#InvoiceCountryRegionId_CH)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[BillInformation_CH](#BillInformation_CH)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[BookableResourceName](#BookableResourceName)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[DataAreaId](#DataAreaId)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[Relationship_Currency_EuroRelationshipId](#Relationship_Currency_EuroRelationshipId)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[Relationship_Currency_PrepaidRelationshipId](#Relationship_Currency_PrepaidRelationshipId)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[Relationship_Currency_PrepaidEuroRelationshipId](#Relationship_Currency_PrepaidEuroRelationshipId)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[Relationship_CustTableRelationshipId](#Relationship_CustTableRelationshipId)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[Relationship_InventTableRelationshipId](#Relationship_InventTableRelationshipId)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[Relationship_ISOCurrencyCodeRelationshipId](#Relationship_ISOCurrencyCodeRelationshipId)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[Relationship_ProjCategoryRelationshipId](#Relationship_ProjCategoryRelationshipId)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[Relationship_ProjInvoiceJourRelationshipId](#Relationship_ProjInvoiceJourRelationshipId)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[Relationship_ProjInvoiceTableRelationshipId](#Relationship_ProjInvoiceTableRelationshipId)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[Relationship_ProjTableRelationshipId](#Relationship_ProjTableRelationshipId)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[Relationship_SMASubscriptionTableRelationshipId](#Relationship_SMASubscriptionTableRelationshipId)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[Relationship_TaxTableRelationshipId](#Relationship_TaxTableRelationshipId)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[Relationship_TaxTable_SalesTaxFIRelationshipId](#Relationship_TaxTable_SalesTaxFIRelationshipId)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="ProjInvoiceTmp.md" target="_blank">Miscellaneous/ProjInvoiceTmp</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ProjInvoiceTmp/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountNo1 name="AccountNo1">AccountNo1</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNo1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNo2 name="AccountNo2">AccountNo2</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNo2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNum1_FI name="AccountNum1_FI">AccountNum1_FI</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNum1_FI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNum2_FI name="AccountNum2_FI">AccountNum2_FI</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNum2_FI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNum3_FI name="AccountNum3_FI">AccountNum3_FI</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNum3_FI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNum4_FI name="AccountNum4_FI">AccountNum4_FI</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNum4_FI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNum5_FI name="AccountNum5_FI">AccountNum5_FI</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNum5_FI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNum6_FI name="AccountNum6_FI">AccountNum6_FI</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNum6_FI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Amount name="Amount">Amount</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#Amount2 name="Amount2">Amount2</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Amount2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Amount2Dec name="Amount2Dec">Amount2Dec</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Amount2Dec attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountCheckId name="AmountCheckId">AmountCheckId</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountCheckId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankAccountTable_AccountNum_CH name="BankAccountTable_AccountNum_CH">BankAccountTable_AccountNum_CH</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankAccountTable_AccountNum_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankAccountTable_Clearing_CH name="BankAccountTable_Clearing_CH">BankAccountTable_Clearing_CH</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankAccountTable_Clearing_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankGroupIdName_CH1 name="BankGroupIdName_CH1">BankGroupIdName_CH1</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankGroupIdName_CH1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankZipCode_CH name="BankZipCode_CH">BankZipCode_CH</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankZipCode_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashAccountingRegime_ES name="CashAccountingRegime_ES">CashAccountingRegime_ES</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashAccountingRegime_ES attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CashDisc name="CashDisc">CashDisc</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#CashDiscOnInvoice name="CashDiscOnInvoice">CashDiscOnInvoice</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscOnInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscTxt name="CashDiscTxt">CashDiscTxt</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#CompanyCoRegNum name="CompanyCoRegNum">CompanyCoRegNum</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#CompanyEnterpriseNumber name="CompanyEnterpriseNumber">CompanyEnterpriseNumber</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyEnterpriseNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyGiro name="CompanyGiro">CompanyGiro</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyGiro attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyLogo name="CompanyLogo">CompanyLogo</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#CompanyTeleFax name="CompanyTeleFax">CompanyTeleFax</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#CompanyVATNumVisibility name="CompanyVATNumVisibility">CompanyVATNumVisibility</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyVATNumVisibility attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectedInvoiceId name="CorrectedInvoiceId">CorrectedInvoiceId</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#CustAccountExt name="CustAccountExt">CustAccountExt</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustAccountExt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustAddress_CH name="CustAddress_CH">CustAddress_CH</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustAddress_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustName_CH name="CustName_CH">CustName_CH</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustName_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddress name="DeliveryAddress">DeliveryAddress</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description_CH name="Description_CH">Description_CH</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscAmount name="DiscAmount">DiscAmount</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscPercent attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DocuRefVisibility name="DocuRefVisibility">DocuRefVisibility</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#DueAmount name="DueAmount">DueAmount</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DueAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DueDate name="DueDate">DueDate</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDisc attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#EndDiscEuro name="EndDiscEuro">EndDiscEuro</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#EnterpriseNumber name="EnterpriseNumber">EnterpriseNumber</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnterpriseNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Enterpriseregister_NO name="Enterpriseregister_NO">Enterpriseregister_NO</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Enterpriseregister_NO attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternalItemId name="ExternalItemId">ExternalItemId</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#FiCreditorId name="FiCreditorId">FiCreditorId</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiCreditorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Footer name="Footer">Footer</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Footer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormLetterTxt name="FormLetterTxt">FormLetterTxt</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormLetterTxt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiroSection name="GiroSection">GiroSection</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiroSection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiroType name="GiroType">GiroType</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiroType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InfoMessage name="InfoMessage">InfoMessage</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InfoMessage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTransVisibility name="InventTransVisibility">InventTransVisibility</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#InvoiceAmount name="InvoiceAmount">InvoiceAmount</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InvoiceAmountDecimals name="InvoiceAmountDecimals">InvoiceAmountDecimals</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAmountDecimals attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAmountEuro name="InvoiceAmountEuro">InvoiceAmountEuro</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#InvoiceAmountNoDecimals name="InvoiceAmountNoDecimals">InvoiceAmountNoDecimals</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAmountNoDecimals attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceDate name="InvoiceDate">InvoiceDate</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#InvoiceName name="InvoiceName">InvoiceName</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceNum name="InvoiceNum">InvoiceNum</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#InvoiceReferenceNumberFI name="InvoiceReferenceNumberFI">InvoiceReferenceNumberFI</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceReferenceNumberFI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceRoundOff name="InvoiceRoundOff">InvoiceRoundOff</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#InvoiceTxt name="InvoiceTxt">InvoiceTxt</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceTxt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#LayoutCode_CH name="LayoutCode_CH">LayoutCode_CH</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LayoutCode_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineAmount name="LineAmount">LineAmount</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MandateBankIBAN name="MandateBankIBAN">MandateBankIBAN</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#MarkupAmount_FI name="MarkupAmount_FI">MarkupAmount_FI</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarkupAmount_FI attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MarkupCode_FI name="MarkupCode_FI">MarkupCode_FI</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarkupCode_FI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NetAmount name="NetAmount">NetAmount</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#NPIBankingPaymId name="NPIBankingPaymId">NPIBankingPaymId</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NPIBankingPaymId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NPIBankingPaymIdVisibility name="NPIBankingPaymIdVisibility">NPIBankingPaymIdVisibility</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NPIBankingPaymIdVisibility attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OCRField name="OCRField">OCRField</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OCRField attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OCRLine_CH name="OCRLine_CH">OCRLine_CH</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OCRLine_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OCRLine_FI name="OCRLine_FI">OCRLine_FI</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OCRLine_FI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnAccInvTransCorrectInvIdVisibility name="OnAccInvTransCorrectInvIdVisibility">OnAccInvTransCorrectInvIdVisibility</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#PackingSlipInfo name="PackingSlipInfo">PackingSlipInfo</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingSlipInfoVisibility attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PaymentCondition name="PaymentCondition">PaymentCondition</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#PaymentId2_PaymentId3_CH name="PaymentId2_PaymentId3_CH">PaymentId2_PaymentId3_CH</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentId2_PaymentId3_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentRef1_CH name="PaymentRef1_CH">PaymentRef1_CH</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentRef1_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentRef2_CH name="PaymentRef2_CH">PaymentRef2_CH</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentRef2_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Periods name="Periods">Periods</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#PrepaidAmount name="PrepaidAmount">PrepaidAmount</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#PrepaidCurrencyCode name="PrepaidCurrencyCode">PrepaidCurrencyCode</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrepaidCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrepaidCurrencyCodeEuro name="PrepaidCurrencyCodeEuro">PrepaidCurrencyCodeEuro</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrepaidCurrencyCodeEuro attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrepaidInvoiceAmount name="PrepaidInvoiceAmount">PrepaidInvoiceAmount</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrepaidInvoiceAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PrepaidInvoiceAmountEuro name="PrepaidInvoiceAmountEuro">PrepaidInvoiceAmountEuro</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrepaidInvoiceAmountEuro attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PrepaidNetAmount name="PrepaidNetAmount">PrepaidNetAmount</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrePrintLevelShow attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintCode name="PrintCode">PrintCode</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#PrintGiro name="PrintGiro">PrintGiro</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintGiro attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintLogo name="PrintLogo">PrintLogo</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintLogo attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Project name="Project">Project</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjInvoiceJourDueDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ProjInvRefNum_FIVisibility name="ProjInvRefNum_FIVisibility">ProjInvRefNum_FIVisibility</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjInvRefNum_FIVisibility attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjItemTransVisibility name="ProjItemTransVisibility">ProjItemTransVisibility</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#Qty name="Qty">Qty</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Qty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReferenceNumber_FI name="ReferenceNumber_FI">ReferenceNumber_FI</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReferenceNumber_FI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReferenceNumber_FI1 name="ReferenceNumber_FI1">ReferenceNumber_FI1</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReferenceNumber_FI1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemainAmountToBePaid name="RemainAmountToBePaid">RemainAmountToBePaid</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesBalance attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesBalanceEuro name="SalesBalanceEuro">SalesBalanceEuro</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#SalesOrdernum name="SalesOrdernum">SalesOrdernum</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#SalesTaxCode_FI name="SalesTaxCode_FI">SalesTaxCode_FI</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxCode_FI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettleAmountCur name="SettleAmountCur">SettleAmountCur</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettleAmountCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ShowCustPaymSched name="ShowCustPaymSched">ShowCustPaymSched</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#ShowPrepaidTotals name="ShowPrepaidTotals">ShowPrepaidTotals</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowPrepaidTotals attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowPrepaidTotalsEuro name="ShowPrepaidTotalsEuro">ShowPrepaidTotalsEuro</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowPrepaidTotalsEuro attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowProjInvoiceCost name="ShowProjInvoiceCost">ShowProjInvoiceCost</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#ShowProjItemTrans name="ShowProjItemTrans">ShowProjItemTrans</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowProjItemTrans attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowTaxTrans name="ShowTaxTrans">ShowTaxTrans</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SMASpecIndexCalc attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SMASubscriptionId name="SMASubscriptionId">SMASubscriptionId</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SumTaxEuro name="SumTaxEuro">SumTaxEuro</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#TaxableBalance name="TaxableBalance">TaxableBalance</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#TaxAmountLabel name="TaxAmountLabel">TaxAmountLabel</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#TaxBaseAmount name="TaxBaseAmount">TaxBaseAmount</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#TaxBaseQty name="TaxBaseQty">TaxBaseQty</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#TaxExemptDescription name="TaxExemptDescription">TaxExemptDescription</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPrintTaxFreeBalance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxWriteCode name="TaxWriteCode">TaxWriteCode</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#Txt name="Txt">Txt</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Txt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VATNum name="VATNum">VATNum</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#VATNumVisibility name="VATNumVisibility">VATNumVisibility</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATNumVisibility attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IBAN_CH name="IBAN_CH">IBAN_CH</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IBAN_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressLine1_CH name="InvoiceAddressLine1_CH">InvoiceAddressLine1_CH</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressLine1_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressLine2_CH name="InvoiceAddressLine2_CH">InvoiceAddressLine2_CH</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressLine2_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceCountryRegionId_CH name="InvoiceCountryRegionId_CH">InvoiceCountryRegionId_CH</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceCountryRegionId_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillInformation_CH name="BillInformation_CH">BillInformation_CH</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillInformation_CH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BookableResourceName name="BookableResourceName">BookableResourceName</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BookableResourceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#Relationship_Currency_PrepaidRelationshipId name="Relationship_Currency_PrepaidRelationshipId">Relationship_Currency_PrepaidRelationshipId</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Currency_PrepaidRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_Currency_PrepaidEuroRelationshipId name="Relationship_Currency_PrepaidEuroRelationshipId">Relationship_Currency_PrepaidEuroRelationshipId</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Currency_PrepaidEuroRelationshipId attribute are listed below.</summary>

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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

### <a href=#Relationship_TaxTable_SalesTaxFIRelationshipId name="Relationship_TaxTable_SalesTaxFIRelationshipId">Relationship_TaxTable_SalesTaxFIRelationshipId</a>

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxTable_SalesTaxFIRelationshipId attribute are listed below.</summary>

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

First included in: Miscellaneous/ProjInvoiceTmp (this entity)  

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
