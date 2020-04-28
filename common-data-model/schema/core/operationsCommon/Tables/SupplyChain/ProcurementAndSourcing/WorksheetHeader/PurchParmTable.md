---
title: PurchParmTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Purchase order - update table

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchParmTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchParmTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase order - update table</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[OrderAccount](#OrderAccount)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[BankLCImportLine](#BankLCImportLine)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[BatchAdministration](#BatchAdministration)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[CashDisc](#CashDisc)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[CashDiscCode](#CashDiscCode)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[CashDiscDate](#CashDiscDate)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[CashDiscPercent](#CashDiscPercent)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[ConsignmentNoteNum_IN](#ConsignmentNoteNum_IN)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[CountyOrigDest](#CountyOrigDest)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[CurrencyCode](#CurrencyCode)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[CustomsBillOfEntryNumberTable_IN](#CustomsBillOfEntryNumberTable_IN)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[CustomsImportInvoiceNumberTable_IN](#CustomsImportInvoiceNumberTable_IN)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[DeliveryName](#DeliveryName)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[DeliveryPostalAddress](#DeliveryPostalAddress)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Description](#Description)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[DocumentDate](#DocumentDate)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[DocumentNum](#DocumentNum)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[DocumentOrigin](#DocumentOrigin)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[ElectronicInvoice_BR](#ElectronicInvoice_BR)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[EndDateTime](#EndDateTime)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[EndDisc](#EndDisc)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[EnterpriseNumber](#EnterpriseNumber)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[EUROTriangulation](#EUROTriangulation)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[ExchRate](#ExchRate)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[ExchRateSecondary](#ExchRateSecondary)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[FiscalDocumentModel_BR](#FiscalDocumentModel_BR)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[FiscalDocumentSeries_BR](#FiscalDocumentSeries_BR)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[FiscalDocumentSpecie_BR](#FiscalDocumentSpecie_BR)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[FiscalDocumentType_BR](#FiscalDocumentType_BR)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[FixedDueDate](#FixedDueDate)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[FixedExchRate](#FixedExchRate)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Hold](#Hold)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[IgnoreCalculatedSalesTax](#IgnoreCalculatedSalesTax)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[InclTax](#InclTax)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[InventProfileType_RU](#InventProfileType_RU)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[InvoiceAccount](#InvoiceAccount)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[InvoiceReleaseDate](#InvoiceReleaseDate)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[InvoiceRoundOff](#InvoiceRoundOff)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[LastMatchVariance](#LastMatchVariance)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Log](#Log)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Num](#Num)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[NumberSequenceGroup](#NumberSequenceGroup)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[OffReportType_RU](#OffReportType_RU)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[OffSessionId_RU](#OffSessionId_RU)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Ordering](#Ordering)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[PackingSlipIdForUpdate_W](#PackingSlipIdForUpdate_W)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[ParmId](#ParmId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[ParmJobStatus](#ParmJobStatus)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Payment](#Payment)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[PaymentSched](#PaymentSched)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[PaymId](#PaymId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[PaymMode](#PaymMode)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[PaymSpec](#PaymSpec)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Port](#Port)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[PostingProfile](#PostingProfile)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[PurchId](#PurchId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[PurchName](#PurchName)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[ReasonTableRef_BR](#ReasonTableRef_BR)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[ReCalculate](#ReCalculate)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[ReleaseDateComment](#ReleaseDateComment)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[RemittanceLocation](#RemittanceLocation)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[ServiceCodeOnDlvAddress_BR](#ServiceCodeOnDlvAddress_BR)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[SettleVoucher](#SettleVoucher)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[StartDateTime](#StartDateTime)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[StatProcId](#StatProcId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Storno](#Storno)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[StornoPhysical_RU](#StornoPhysical_RU)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[TableRefId](#TableRefId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[TaxGroup](#TaxGroup)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[TaxInformation_IN](#TaxInformation_IN)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[TaxRoundOff](#TaxRoundOff)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[TransactionCode](#TransactionCode)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[TransDate](#TransDate)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Transport](#Transport)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[VarianceApproved](#VarianceApproved)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[VarianceApprovedDateTime](#VarianceApprovedDateTime)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[VarianceComment](#VarianceComment)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[VATNum](#VATNum)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[VendBankAccountID](#VendBankAccountID)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[VendFinalUser_BR](#VendFinalUser_BR)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[VendInvoiceGroup](#VendInvoiceGroup)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[VendInvoiceSaveStatus](#VendInvoiceSaveStatus)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[VendPackingSlipJour](#VendPackingSlipJour)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[VendPaymentGroup](#VendPaymentGroup)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[WorkflowState](#WorkflowState)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[PresenceType_BR](#PresenceType_BR)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[DocAutoNumbering_LT](#DocAutoNumbering_LT)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[ReportingCurrencyExchangeRate](#ReportingCurrencyExchangeRate)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[LoadId](#LoadId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[DataAreaId](#DataAreaId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_BankLCImportLineRelationshipId](#Relationship_BankLCImportLineRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_CashDiscRelationshipId](#Relationship_CashDiscRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_CountyOrigDestRelationshipId](#Relationship_CountyOrigDestRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_CustomsBillOfEntryNumberTable_INRelationshipId](#Relationship_CustomsBillOfEntryNumberTable_INRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_CustomsImportInvoiceNumberTable_INRelationshipId](#Relationship_CustomsImportInvoiceNumberTable_INRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_DeliveryPostalAddress_FKRelationshipId](#Relationship_DeliveryPostalAddress_FKRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_FiscalDocModel_BRRelationshipId](#Relationship_FiscalDocModel_BRRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_FiscalDocumentType_BRRelationshipId](#Relationship_FiscalDocumentType_BRRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_IntrastatPortRelationshipId](#Relationship_IntrastatPortRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_IntrastatStatProcRelationshipId](#Relationship_IntrastatStatProcRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_IntrastatTransactionCodeRelationshipId](#Relationship_IntrastatTransactionCodeRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_IntrastatTransportModeRelationshipId](#Relationship_IntrastatTransportModeRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_InvoiceVendorRelationshipId](#Relationship_InvoiceVendorRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_NumberSequenceGroupRelationshipId](#Relationship_NumberSequenceGroupRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_OfficialsTrans_RURelationshipId](#Relationship_OfficialsTrans_RURelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_OrderVendorRelationshipId](#Relationship_OrderVendorRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_PaymSchedRelationshipId](#Relationship_PaymSchedRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_PaymTermRelationshipId](#Relationship_PaymTermRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_PurchParmUpdateRelationshipId](#Relationship_PurchParmUpdateRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_PurchTableRelationshipId](#Relationship_PurchTableRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_ReasonTableRefRelationshipId](#Relationship_ReasonTableRefRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_RemittanceLocation_FKRelationshipId](#Relationship_RemittanceLocation_FKRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_TaxGroupHeadingRelationshipId](#Relationship_TaxGroupHeadingRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_TaxInformation_INRelationshipId](#Relationship_TaxInformation_INRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_TaxWorkRegulationRelationshipId](#Relationship_TaxWorkRegulationRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_VendBankAccountRelationshipId](#Relationship_VendBankAccountRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_VendLedgerRelationshipId](#Relationship_VendLedgerRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_VendPackingSlipJourRelationshipId](#Relationship_VendPackingSlipJourRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_VendPaymentModeSpecRelationshipId](#Relationship_VendPaymentModeSpecRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_VendPaymModeTableRelationshipId](#Relationship_VendPaymModeTableRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_WHSLoadTableRelationshipId](#Relationship_WHSLoadTableRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="PurchParmTable.md" target="_blank">WorksheetHeader/PurchParmTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchParmTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OrderAccount name="OrderAccount">OrderAccount</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankLCImportLine name="BankLCImportLine">BankLCImportLine</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankLCImportLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BatchAdministration name="BatchAdministration">BatchAdministration</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchAdministration attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CashDisc name="CashDisc">CashDisc</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cash discount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDisc attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cash discount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CashDiscCode name="CashDiscCode">CashDiscCode</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscDate name="CashDiscDate">CashDiscDate</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#CashDiscPercent name="CashDiscPercent">CashDiscPercent</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscPercent attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ConsignmentNoteNum_IN name="ConsignmentNoteNum_IN">ConsignmentNoteNum_IN</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsignmentNoteNum_IN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountyOrigDest name="CountyOrigDest">CountyOrigDest</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountyOrigDest attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomsBillOfEntryNumberTable_IN name="CustomsBillOfEntryNumberTable_IN">CustomsBillOfEntryNumberTable_IN</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsBillOfEntryNumberTable_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustomsImportInvoiceNumberTable_IN name="CustomsImportInvoiceNumberTable_IN">CustomsImportInvoiceNumberTable_IN</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import invoice number</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsImportInvoiceNumberTable_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Import invoice number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DeliveryName name="DeliveryName">DeliveryName</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery name</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delivery name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryPostalAddress name="DeliveryPostalAddress">DeliveryPostalAddress</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryPostalAddress attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentDate name="DocumentDate">DocumentDate</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DocumentNum name="DocumentNum">DocumentNum</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Document number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Document number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentOrigin name="DocumentOrigin">DocumentOrigin</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentOrigin attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ElectronicInvoice_BR name="ElectronicInvoice_BR">ElectronicInvoice_BR</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicInvoice_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EndDateTime name="EndDateTime">EndDateTime</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#EndDisc name="EndDisc">EndDisc</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDisc attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#EnterpriseNumber name="EnterpriseNumber">EnterpriseNumber</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

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

### <a href=#EUROTriangulation name="EUROTriangulation">EUROTriangulation</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EUROTriangulation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExchRate name="ExchRate">ExchRate</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ExchRateSecondary name="ExchRateSecondary">ExchRateSecondary</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRateSecondary attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FiscalDocumentModel_BR name="FiscalDocumentModel_BR">FiscalDocumentModel_BR</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentModel_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentSeries_BR name="FiscalDocumentSeries_BR">FiscalDocumentSeries_BR</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentSeries_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentSpecie_BR name="FiscalDocumentSpecie_BR">FiscalDocumentSpecie_BR</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentSpecie_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FiscalDocumentType_BR name="FiscalDocumentType_BR">FiscalDocumentType_BR</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentType_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FixedDueDate name="FixedDueDate">FixedDueDate</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedDueDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#FixedExchRate name="FixedExchRate">FixedExchRate</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedExchRate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Hold name="Hold">Hold</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Hold attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IgnoreCalculatedSalesTax name="IgnoreCalculatedSalesTax">IgnoreCalculatedSalesTax</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ignore calculated sales tax</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IgnoreCalculatedSalesTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ignore calculated sales tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#InclTax name="InclTax">InclTax</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InclTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventProfileType_RU name="InventProfileType_RU">InventProfileType_RU</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventProfileType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#InvoiceAccount name="InvoiceAccount">InvoiceAccount</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceReleaseDate name="InvoiceReleaseDate">InvoiceReleaseDate</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceReleaseDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#InvoiceRoundOff name="InvoiceRoundOff">InvoiceRoundOff</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceRoundOff attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LastMatchVariance name="LastMatchVariance">LastMatchVariance</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastMatchVariance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Log name="Log">Log</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

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

### <a href=#Num name="Num">Num</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Num attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceGroup name="NumberSequenceGroup">NumberSequenceGroup</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffReportType_RU name="OffReportType_RU">OffReportType_RU</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffReportType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OffSessionId_RU name="OffSessionId_RU">OffSessionId_RU</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffSessionId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Ordering name="Ordering">Ordering</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Update</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Ordering attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Update</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PackingSlipIdForUpdate_W name="PackingSlipIdForUpdate_W">PackingSlipIdForUpdate_W</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingSlipIdForUpdate_W attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParmId name="ParmId">ParmId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParmId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParmJobStatus name="ParmJobStatus">ParmJobStatus</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParmJobStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Payment name="Payment">Payment</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Payment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentSched name="PaymentSched">PaymentSched</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentSched attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymId name="PaymId">PaymId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymMode name="PaymMode">PaymMode</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymSpec name="PaymSpec">PaymSpec</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymSpec attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Port name="Port">Port</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Port attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingProfile name="PostingProfile">PostingProfile</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchId name="PurchId">PurchId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

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

### <a href=#PurchName name="PurchName">PurchName</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReasonTableRef_BR name="ReasonTableRef_BR">ReasonTableRef_BR</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReasonTableRef_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ReCalculate name="ReCalculate">ReCalculate</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recalculation</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReCalculate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Recalculation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ReleaseDateComment name="ReleaseDateComment">ReleaseDateComment</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReleaseDateComment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemittanceLocation name="RemittanceLocation">RemittanceLocation</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemittanceLocation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ServiceCodeOnDlvAddress_BR name="ServiceCodeOnDlvAddress_BR">ServiceCodeOnDlvAddress_BR</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceCodeOnDlvAddress_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SettleVoucher name="SettleVoucher">SettleVoucher</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettleVoucher attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StartDateTime name="StartDateTime">StartDateTime</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#StatProcId name="StatProcId">StatProcId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatProcId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Storno name="Storno">Storno</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credit correction</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Storno attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Credit correction</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#StornoPhysical_RU name="StornoPhysical_RU">StornoPhysical_RU</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credit correction (physical)</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StornoPhysical_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Credit correction (physical)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TableRefId name="TableRefId">TableRefId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TableRefId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxGroup name="TaxGroup">TaxGroup</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxInformation_IN name="TaxInformation_IN">TaxInformation_IN</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxInformation_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxRoundOff name="TaxRoundOff">TaxRoundOff</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax rounding</td></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRoundOff attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax rounding</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransactionCode name="TransactionCode">TransactionCode</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Transport name="Transport">Transport</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Transport attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VarianceApproved name="VarianceApproved">VarianceApproved</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VarianceApproved attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VarianceApprovedDateTime name="VarianceApprovedDateTime">VarianceApprovedDateTime</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VarianceApprovedDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#VarianceComment name="VarianceComment">VarianceComment</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VarianceComment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VATNum name="VATNum">VATNum</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

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

### <a href=#VendBankAccountID name="VendBankAccountID">VendBankAccountID</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendBankAccountID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendFinalUser_BR name="VendFinalUser_BR">VendFinalUser_BR</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendFinalUser_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VendInvoiceGroup name="VendInvoiceGroup">VendInvoiceGroup</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendInvoiceGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendInvoiceSaveStatus name="VendInvoiceSaveStatus">VendInvoiceSaveStatus</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendInvoiceSaveStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VendPackingSlipJour name="VendPackingSlipJour">VendPackingSlipJour</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendPackingSlipJour attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#VendPaymentGroup name="VendPaymentGroup">VendPaymentGroup</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendPaymentGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkflowState name="WorkflowState">WorkflowState</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowState attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PresenceType_BR name="PresenceType_BR">PresenceType_BR</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PresenceType_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DocAutoNumbering_LT name="DocAutoNumbering_LT">DocAutoNumbering_LT</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocAutoNumbering_LT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReportingCurrencyExchangeRate name="ReportingCurrencyExchangeRate">ReportingCurrencyExchangeRate</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCurrencyExchangeRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LoadId name="LoadId">LoadId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

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

### <a href=#Relationship_BankLCImportLineRelationshipId name="Relationship_BankLCImportLineRelationshipId">Relationship_BankLCImportLineRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankLCImportLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Bank/WorksheetLine/BankLCImportLine.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/WorksheetLine/BankLCImportLine.cdm.json/BankLCImportLine</a></td><td><a href="../../../Finance/Bank/WorksheetLine/BankLCImportLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CashDiscRelationshipId name="Relationship_CashDiscRelationshipId">Relationship_CashDiscRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CashDiscRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Bank/Group/CashDisc.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/CashDisc.cdm.json/CashDisc</a></td><td><a href="../../../Finance/Bank/Group/CashDisc.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CountyOrigDestRelationshipId name="Relationship_CountyOrigDestRelationshipId">Relationship_CountyOrigDestRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CountyOrigDestRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/LogisticsAddressCounty.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Group/LogisticsAddressCounty.cdm.json/LogisticsAddressCounty</a></td><td><a href="../../../Common/GAB/Group/LogisticsAddressCounty.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

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

### <a href=#Relationship_CustomsBillOfEntryNumberTable_INRelationshipId name="Relationship_CustomsBillOfEntryNumberTable_INRelationshipId">Relationship_CustomsBillOfEntryNumberTable_INRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustomsBillOfEntryNumberTable_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountsReceivable/Main/CustomsBillOfEntryNumberTable_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Main/CustomsBillOfEntryNumberTable_IN.cdm.json/CustomsBillOfEntryNumberTable_IN</a></td><td><a href="../../../Finance/AccountsReceivable/Main/CustomsBillOfEntryNumberTable_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustomsImportInvoiceNumberTable_INRelationshipId name="Relationship_CustomsImportInvoiceNumberTable_INRelationshipId">Relationship_CustomsImportInvoiceNumberTable_INRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustomsImportInvoiceNumberTable_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountsReceivable/Main/CustomsImportInvoiceNumberTable_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Main/CustomsImportInvoiceNumberTable_IN.cdm.json/CustomsImportInvoiceNumberTable_IN</a></td><td><a href="../../../Finance/AccountsReceivable/Main/CustomsImportInvoiceNumberTable_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DeliveryPostalAddress_FKRelationshipId name="Relationship_DeliveryPostalAddress_FKRelationshipId">Relationship_DeliveryPostalAddress_FKRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DeliveryPostalAddress_FKRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/LogisticsPostalAddress.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/LogisticsPostalAddress.cdm.json/LogisticsPostalAddress</a></td><td><a href="../../../Common/GAB/Main/LogisticsPostalAddress.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalDocModel_BRRelationshipId name="Relationship_FiscalDocModel_BRRelationshipId">Relationship_FiscalDocModel_BRRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalDocModel_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FiscalBooksBrazil/Group/FiscalDocModel_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Group/FiscalDocModel_BR.cdm.json/FiscalDocModel_BR</a></td><td><a href="../../../Finance/FiscalBooksBrazil/Group/FiscalDocModel_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalDocumentType_BRRelationshipId name="Relationship_FiscalDocumentType_BRRelationshipId">Relationship_FiscalDocumentType_BRRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalDocumentType_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FiscalBooksBrazil/Parameter/FiscalDocumentType_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Parameter/FiscalDocumentType_BR.cdm.json/FiscalDocumentType_BR</a></td><td><a href="../../../Finance/FiscalBooksBrazil/Parameter/FiscalDocumentType_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_IntrastatPortRelationshipId name="Relationship_IntrastatPortRelationshipId">Relationship_IntrastatPortRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IntrastatPortRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Intrastat/Group/IntrastatPort.md" target="_blank">/core/operationsCommon/Tables/Common/Intrastat/Group/IntrastatPort.cdm.json/IntrastatPort</a></td><td><a href="../../../Common/Intrastat/Group/IntrastatPort.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_IntrastatStatProcRelationshipId name="Relationship_IntrastatStatProcRelationshipId">Relationship_IntrastatStatProcRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IntrastatStatProcRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Intrastat/Group/IntrastatStatProc.md" target="_blank">/core/operationsCommon/Tables/Common/Intrastat/Group/IntrastatStatProc.cdm.json/IntrastatStatProc</a></td><td><a href="../../../Common/Intrastat/Group/IntrastatStatProc.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_IntrastatTransactionCodeRelationshipId name="Relationship_IntrastatTransactionCodeRelationshipId">Relationship_IntrastatTransactionCodeRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IntrastatTransactionCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Intrastat/Group/IntrastatTransactionCode.md" target="_blank">/core/operationsCommon/Tables/Common/Intrastat/Group/IntrastatTransactionCode.cdm.json/IntrastatTransactionCode</a></td><td><a href="../../../Common/Intrastat/Group/IntrastatTransactionCode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_IntrastatTransportModeRelationshipId name="Relationship_IntrastatTransportModeRelationshipId">Relationship_IntrastatTransportModeRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IntrastatTransportModeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Intrastat/Group/IntrastatTransportMode.md" target="_blank">/core/operationsCommon/Tables/Common/Intrastat/Group/IntrastatTransportMode.cdm.json/IntrastatTransportMode</a></td><td><a href="../../../Common/Intrastat/Group/IntrastatTransportMode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InvoiceVendorRelationshipId name="Relationship_InvoiceVendorRelationshipId">Relationship_InvoiceVendorRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InvoiceVendorRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Vendor/Main/VendTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_NumberSequenceGroupRelationshipId name="Relationship_NumberSequenceGroupRelationshipId">Relationship_NumberSequenceGroupRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_NumberSequenceGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceGroup.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Framework/NumberSequenceGroup.cdm.json/NumberSequenceGroup</a></td><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OfficialsTrans_RURelationshipId name="Relationship_OfficialsTrans_RURelationshipId">Relationship_OfficialsTrans_RURelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OfficialsTrans_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/APARShared/Transaction/OfficialsTrans_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/APARShared/Transaction/OfficialsTrans_RU.cdm.json/OfficialsTrans_RU</a></td><td><a href="../../../Finance/APARShared/Transaction/OfficialsTrans_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OrderVendorRelationshipId name="Relationship_OrderVendorRelationshipId">Relationship_OrderVendorRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OrderVendorRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Vendor/Main/VendTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymSchedRelationshipId name="Relationship_PaymSchedRelationshipId">Relationship_PaymSchedRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Bank/Group/PaymSched.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/PaymSched.cdm.json/PaymSched</a></td><td><a href="../../../Finance/Bank/Group/PaymSched.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymTermRelationshipId name="Relationship_PaymTermRelationshipId">Relationship_PaymTermRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

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

### <a href=#Relationship_PurchParmUpdateRelationshipId name="Relationship_PurchParmUpdateRelationshipId">Relationship_PurchParmUpdateRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchParmUpdateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/PurchParmUpdate.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Transaction/PurchParmUpdate.cdm.json/PurchParmUpdate</a></td><td><a href="../Transaction/PurchParmUpdate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchTableRelationshipId name="Relationship_PurchTableRelationshipId">Relationship_PurchTableRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="PurchTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchTable.cdm.json/PurchTable</a></td><td><a href="PurchTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReasonTableRefRelationshipId name="Relationship_ReasonTableRefRelationshipId">Relationship_ReasonTableRefRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReasonTableRefRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Transaction/ReasonTableRef.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Transaction/ReasonTableRef.cdm.json/ReasonTableRef</a></td><td><a href="../../../Finance/Ledger/Transaction/ReasonTableRef.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RemittanceLocation_FKRelationshipId name="Relationship_RemittanceLocation_FKRelationshipId">Relationship_RemittanceLocation_FKRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RemittanceLocation_FKRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/LogisticsLocation.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/LogisticsLocation.cdm.json/LogisticsLocation</a></td><td><a href="../../../Common/GAB/Main/LogisticsLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxGroupHeadingRelationshipId name="Relationship_TaxGroupHeadingRelationshipId">Relationship_TaxGroupHeadingRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxGroupHeadingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Group/TaxGroupHeading.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxGroupHeading.cdm.json/TaxGroupHeading</a></td><td><a href="../../../Finance/Tax/Group/TaxGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxInformation_INRelationshipId name="Relationship_TaxInformation_INRelationshipId">Relationship_TaxInformation_INRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxInformation_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Miscellaneous/TaxInformation_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Miscellaneous/TaxInformation_IN.cdm.json/TaxInformation_IN</a></td><td><a href="../../../Finance/Tax/Miscellaneous/TaxInformation_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWorkRegulationRelationshipId name="Relationship_TaxWorkRegulationRelationshipId">Relationship_TaxWorkRegulationRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWorkRegulationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/WorksheetLine/TaxWorkRegulation.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/WorksheetLine/TaxWorkRegulation.cdm.json/TaxWorkRegulation</a></td><td><a href="../../../Finance/Tax/WorksheetLine/TaxWorkRegulation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendBankAccountRelationshipId name="Relationship_VendBankAccountRelationshipId">Relationship_VendBankAccountRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendBankAccountRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Vendor/Main/VendBankAccount.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendBankAccount.cdm.json/VendBankAccount</a></td><td><a href="../../Vendor/Main/VendBankAccount.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendLedgerRelationshipId name="Relationship_VendLedgerRelationshipId">Relationship_VendLedgerRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendLedgerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountsPayable/Group/VendLedger.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Group/VendLedger.cdm.json/VendLedger</a></td><td><a href="../../../Finance/AccountsPayable/Group/VendLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendPackingSlipJourRelationshipId name="Relationship_VendPackingSlipJourRelationshipId">Relationship_VendPackingSlipJourRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendPackingSlipJourRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/VendPackingSlipJour.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Transaction/VendPackingSlipJour.cdm.json/VendPackingSlipJour</a></td><td><a href="../Transaction/VendPackingSlipJour.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendPaymentModeSpecRelationshipId name="Relationship_VendPaymentModeSpecRelationshipId">Relationship_VendPaymentModeSpecRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendPaymentModeSpecRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Bank/Group/VendPaymModeSpec.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/VendPaymModeSpec.cdm.json/VendPaymModeSpec</a></td><td><a href="../../../Finance/Bank/Group/VendPaymModeSpec.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendPaymModeTableRelationshipId name="Relationship_VendPaymModeTableRelationshipId">Relationship_VendPaymModeTableRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendPaymModeTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Bank/Group/VendPaymModeTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/VendPaymModeTable.cdm.json/VendPaymModeTable</a></td><td><a href="../../../Finance/Bank/Group/VendPaymModeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSLoadTableRelationshipId name="Relationship_WHSLoadTableRelationshipId">Relationship_WHSLoadTableRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSLoadTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/WorksheetHeader/WHSLoadTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/WHSLoadTable.cdm.json/WHSLoadTable</a></td><td><a href="../../Inventory/WorksheetHeader/WHSLoadTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetHeader/PurchParmTable (this entity)  

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
