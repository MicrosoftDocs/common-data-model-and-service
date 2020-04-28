---
title: SalesParameters - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Sales parameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Parameter/SalesParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SalesParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[AccesLevelInvoiced](#AccesLevelInvoiced)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[AgreementPriceDisc_RU](#AgreementPriceDisc_RU)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[ApplySmartRoundingAfterConversion](#ApplySmartRoundingAfterConversion)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[ATPApplyDemandTimeFence](#ATPApplyDemandTimeFence)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[ATPApplySupplyTimeFence](#ATPApplySupplyTimeFence)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[ATPBackwardDemandTimeFence](#ATPBackwardDemandTimeFence)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[ATPBackwardSupplyTimeFence](#ATPBackwardSupplyTimeFence)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[ATPInclPlannedOrders](#ATPInclPlannedOrders)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[ATPTimeFence](#ATPTimeFence)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[BillOfLading](#BillOfLading)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[BOLcarrierName](#BOLcarrierName)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[BOLfreightChargeTerms](#BOLfreightChargeTerms)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[BOLfreightCounted](#BOLfreightCounted)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[BOLFreightedBy](#BOLFreightedBy)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[BOLlanguageId](#BOLlanguageId)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[BOLtrailerLoaded](#BOLtrailerLoaded)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[CancelSales](#CancelSales)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[CreditNoteDocumentDateControlType_W](#CreditNoteDocumentDateControlType_W)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[CreditNoteInvoiceDateControlType_W](#CreditNoteInvoiceDateControlType_W)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[CustQuotationTypeId](#CustQuotationTypeId)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[DateOfExchRate_W](#DateOfExchRate_W)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[DeleteHeading](#DeleteHeading)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[DeleteLine](#DeleteLine)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[Delivery2Invoice](#Delivery2Invoice)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[DeliveryDateControlType](#DeliveryDateControlType)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[DeliveryDateUpdateInLines](#DeliveryDateUpdateInLines)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[Disc](#Disc)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[DocumentDateControlType_W](#DocumentDateControlType_W)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[DomesticSalesTaxGroup_PL](#DomesticSalesTaxGroup_PL)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[EmplPhoneTypeId](#EmplPhoneTypeId)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[EPSalesOriginId](#EPSalesOriginId)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[ExchangeRateType](#ExchangeRateType)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[FiscalItemPrintCode_PL](#FiscalItemPrintCode_PL)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[GenericCurrency](#GenericCurrency)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[InventBaileeSearchPriority_RU](#InventBaileeSearchPriority_RU)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[InventProfileId_RU](#InventProfileId_RU)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[InventProfileSplitLines_RU](#InventProfileSplitLines_RU)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[InventProfileUseRelated_RU](#InventProfileUseRelated_RU)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[InvoiceDateControlType_W](#InvoiceDateControlType_W)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[InvoicePostingType_RU](#InvoicePostingType_RU)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[IsMatchingAgreementSearchEnabled](#IsMatchingAgreementSearchEnabled)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[Key](#Key)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[LeadTimeSalesDefault](#LeadTimeSalesDefault)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[LineDiscCalculation_PL](#LineDiscCalculation_PL)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[MarkupHeading](#MarkupHeading)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[MarkupLine](#MarkupLine)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[MCRAcceptableSalesMargin](#MCRAcceptableSalesMargin)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[MCRAllowOutOfBalance](#MCRAllowOutOfBalance)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[MCRCheckHoldNumberOfDays](#MCRCheckHoldNumberOfDays)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[MCRCheckHoldThresholdAmt](#MCRCheckHoldThresholdAmt)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[MCRCopyNotes](#MCRCopyNotes)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[MCRDefQuoteConvHoldCode](#MCRDefQuoteConvHoldCode)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[MCREnableMarginAlert](#MCREnableMarginAlert)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[MCRHoldCodeNoteType](#MCRHoldCodeNoteType)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[MCRHoldOrderDisplayColor](#MCRHoldOrderDisplayColor)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[MCROverpaidReviewThreshold](#MCROverpaidReviewThreshold)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[MCROverUnderPaymentPrompt](#MCROverUnderPaymentPrompt)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[MCRPickStagingUseReservation](#MCRPickStagingUseReservation)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[MCRPromptForItemList](#MCRPromptForItemList)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[MCRQuestionableSalesMargin](#MCRQuestionableSalesMargin)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[MCRUnderpaidReviewThreshold](#MCRUnderpaidReviewThreshold)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[OrderBatchTaskSize](#OrderBatchTaskSize)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[OrderEntryStatistics](#OrderEntryStatistics)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[OrderType](#OrderType)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[OverDelivery](#OverDelivery)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[PackingSlipByInvent_PL](#PackingSlipByInvent_PL)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[PdsBatchAttribAutoRes](#PdsBatchAttribAutoRes)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[PickinglistDefaultLanguage](#PickinglistDefaultLanguage)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[PickRouteStatusOnUpdate](#PickRouteStatusOnUpdate)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[PostExciseInLedger_PL](#PostExciseInLedger_PL)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[PostPackingSlip](#PostPackingSlip)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[PrePrintLevelShippingLabel](#PrePrintLevelShippingLabel)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[PriceDateType](#PriceDateType)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[PromptQty](#PromptQty)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[PromptTransfer](#PromptTransfer)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[QuotationNumOfDaysExpiryDate](#QuotationNumOfDaysExpiryDate)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[QuotationNumOfDaysFollowUpDate](#QuotationNumOfDaysFollowUpDate)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[ReduceInvoice](#ReduceInvoice)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[ReducePackingSlip](#ReducePackingSlip)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[ReducePickingList](#ReducePickingList)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[Reservation](#Reservation)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[ReturnPeriodOfValidity](#ReturnPeriodOfValidity)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[SalesOriginId](#SalesOriginId)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[SalesPoolId](#SalesPoolId)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[SettleVoucher](#SettleVoucher)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[ShippingStat](#ShippingStat)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[SplitDeliveryConfirmation](#SplitDeliveryConfirmation)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[SplitDeliveryInvoice](#SplitDeliveryInvoice)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[SplitDeliveryPackingSlip](#SplitDeliveryPackingSlip)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[SplitDeliveryPickingList](#SplitDeliveryPickingList)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[SplitInventOwnerIdInvoice_RU](#SplitInventOwnerIdInvoice_RU)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[SplitInventProfileTypePackingSlip_RU](#SplitInventProfileTypePackingSlip_RU)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[SplitInvoiceByServiceCode_BR](#SplitInvoiceByServiceCode_BR)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[SplitPostingProfilePackingSlip_RU](#SplitPostingProfilePackingSlip_RU)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[SplitSiteInvoice](#SplitSiteInvoice)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[SplitSitePackingSlip](#SplitSitePackingSlip)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[SplitSitePickingList](#SplitSitePickingList)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[StructDepartment_RU](#StructDepartment_RU)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[SubDelivery](#SubDelivery)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[SummaryErrorTolerance](#SummaryErrorTolerance)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[SummaryUpdateBy](#SummaryUpdateBy)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[TaxWithholdCalculate_BR](#TaxWithholdCalculate_BR)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[TaxWithholdCalculateCrossCompany_BR](#TaxWithholdCalculateCrossCompany_BR)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[TaxWithholdCompany_BR](#TaxWithholdCompany_BR)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[TransportationDocumentOnPackingSlip](#TransportationDocumentOnPackingSlip)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[TransportInvoiceType_RU](#TransportInvoiceType_RU)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[UseSettleExchRate](#UseSettleExchRate)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[ValidDays](#ValidDays)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[CalendarDays](#CalendarDays)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[DocumentTimezonePreference](#DocumentTimezonePreference)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[InvoiceTimezonePreference](#InvoiceTimezonePreference)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[PackingSlipTimezonePreference](#PackingSlipTimezonePreference)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[ERFormatMappingSalesInvoice](#ERFormatMappingSalesInvoice)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[ERFormatMappingSalesCreditNote](#ERFormatMappingSalesCreditNote)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[ERFormatMappingProjectInvoice](#ERFormatMappingProjectInvoice)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[ERFormatMappingProjectCreditNote](#ERFormatMappingProjectCreditNote)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[ERFormatMappingCollection](#ERFormatMappingCollection)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[DeferDirectDeliveryCreation](#DeferDirectDeliveryCreation)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[CheckMultipleWareHouses](#CheckMultipleWareHouses)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[DecimalPrecisionCheckQty](#DecimalPrecisionCheckQty)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[DefaultLanguage](#DefaultLanguage)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[ASOHDefaultCheck](#ASOHDefaultCheck)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[ASOHMandatoryCheck](#ASOHMandatoryCheck)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[ASOHMandatoryHold](#ASOHMandatoryHold)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[ASOHHoldsControl](#ASOHHoldsControl)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[DataAreaId](#DataAreaId)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[Relationship_BillOfLadingLanguageTableRelationshipId](#Relationship_BillOfLadingLanguageTableRelationshipId)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[Relationship_BillOfLadingSalesCarrierRelationshipId](#Relationship_BillOfLadingSalesCarrierRelationshipId)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[Relationship_DefaultSalesOriginRelationshipId](#Relationship_DefaultSalesOriginRelationshipId)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[Relationship_DefaultSalesPoolRelationshipId](#Relationship_DefaultSalesPoolRelationshipId)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[Relationship_DeliveryToInvoicePaymTermRelationshipId](#Relationship_DeliveryToInvoicePaymTermRelationshipId)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[Relationship_DomesticSalesTaxGroupRelationshipId](#Relationship_DomesticSalesTaxGroupRelationshipId)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[Relationship_EPDefaultSalesOriginRelationshipId](#Relationship_EPDefaultSalesOriginRelationshipId)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[Relationship_ExchangeRateTypeRelationshipId](#Relationship_ExchangeRateTypeRelationshipId)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[Relationship_GenericCurrencyRelationshipId](#Relationship_GenericCurrencyRelationshipId)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[Relationship_InventProfile_RURelationshipId](#Relationship_InventProfile_RURelationshipId)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[Relationship_MCRDefQuoteConvHoldCodeRelationshipId](#Relationship_MCRDefQuoteConvHoldCodeRelationshipId)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[Relationship_MCRHoldCodeNoteTypeRelationshipId](#Relationship_MCRHoldCodeNoteTypeRelationshipId)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[Relationship_SalesQuotationTypeGroupRelationshipId](#Relationship_SalesQuotationTypeGroupRelationshipId)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="SalesParameters.md" target="_blank">Parameter/SalesParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SalesParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccesLevelInvoiced name="AccesLevelInvoiced">AccesLevelInvoiced</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccesLevelInvoiced attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AgreementPriceDisc_RU name="AgreementPriceDisc_RU">AgreementPriceDisc_RU</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementPriceDisc_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ApplySmartRoundingAfterConversion name="ApplySmartRoundingAfterConversion">ApplySmartRoundingAfterConversion</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Apply smart rounding after currency conversion</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplySmartRoundingAfterConversion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Apply smart rounding after currency conversion</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ATPApplyDemandTimeFence name="ATPApplyDemandTimeFence">ATPApplyDemandTimeFence</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ATPApplyDemandTimeFence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ATPApplySupplyTimeFence name="ATPApplySupplyTimeFence">ATPApplySupplyTimeFence</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ATPApplySupplyTimeFence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ATPBackwardDemandTimeFence name="ATPBackwardDemandTimeFence">ATPBackwardDemandTimeFence</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ATPBackwardDemandTimeFence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ATPBackwardSupplyTimeFence name="ATPBackwardSupplyTimeFence">ATPBackwardSupplyTimeFence</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ATPBackwardSupplyTimeFence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ATPInclPlannedOrders name="ATPInclPlannedOrders">ATPInclPlannedOrders</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ATPInclPlannedOrders attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ATPTimeFence name="ATPTimeFence">ATPTimeFence</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ATPTimeFence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BillOfLading name="BillOfLading">BillOfLading</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill of lading</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillOfLading attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bill of lading</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#BOLcarrierName name="BOLcarrierName">BOLcarrierName</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOLcarrierName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOLfreightChargeTerms name="BOLfreightChargeTerms">BOLfreightChargeTerms</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOLfreightChargeTerms attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BOLfreightCounted name="BOLfreightCounted">BOLfreightCounted</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOLfreightCounted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BOLFreightedBy name="BOLFreightedBy">BOLFreightedBy</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOLFreightedBy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BOLlanguageId name="BOLlanguageId">BOLlanguageId</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOLlanguageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOLtrailerLoaded name="BOLtrailerLoaded">BOLtrailerLoaded</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOLtrailerLoaded attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CancelSales name="CancelSales">CancelSales</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mark order as voided</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CancelSales attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Mark order as voided</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#CreditNoteDocumentDateControlType_W name="CreditNoteDocumentDateControlType_W">CreditNoteDocumentDateControlType_W</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Document date control</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditNoteDocumentDateControlType_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Document date control</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#CreditNoteInvoiceDateControlType_W name="CreditNoteInvoiceDateControlType_W">CreditNoteInvoiceDateControlType_W</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice date control</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditNoteInvoiceDateControlType_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoice date control</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#CustQuotationTypeId name="CustQuotationTypeId">CustQuotationTypeId</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quotation type customer</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustQuotationTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Quotation type customer</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DateOfExchRate_W name="DateOfExchRate_W">DateOfExchRate_W</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateOfExchRate_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DeleteHeading name="DeleteHeading">DeleteHeading</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delete order after invoicing</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeleteHeading attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delete order after invoicing</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DeleteLine name="DeleteLine">DeleteLine</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delete order line invoiced in total</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeleteLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delete order line invoiced in total</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Delivery2Invoice name="Delivery2Invoice">Delivery2Invoice</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time between shipping date and invoice date</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Delivery2Invoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time between shipping date and invoice date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryDateControlType name="DeliveryDateControlType">DeliveryDateControlType</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryDateControlType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DeliveryDateUpdateInLines name="DeliveryDateUpdateInLines">DeliveryDateUpdateInLines</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Update delivery dates in lines default</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryDateUpdateInLines attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Update delivery dates in lines default</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Disc name="Disc">Disc</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Disc attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DocumentDateControlType_W name="DocumentDateControlType_W">DocumentDateControlType_W</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Document date control</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentDateControlType_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Document date control</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DomesticSalesTaxGroup_PL name="DomesticSalesTaxGroup_PL">DomesticSalesTaxGroup_PL</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DomesticSalesTaxGroup_PL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmplPhoneTypeId name="EmplPhoneTypeId">EmplPhoneTypeId</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Employee communication method</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmplPhoneTypeId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Employee communication method</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#EPSalesOriginId name="EPSalesOriginId">EPSalesOriginId</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales origin from Enterprise Portal</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EPSalesOriginId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales origin from Enterprise Portal</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRateType name="ExchangeRateType">ExchangeRateType</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRateType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FiscalItemPrintCode_PL name="FiscalItemPrintCode_PL">FiscalItemPrintCode_PL</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalItemPrintCode_PL attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#GenericCurrency name="GenericCurrency">GenericCurrency</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Generic currency</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GenericCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Generic currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventBaileeSearchPriority_RU name="InventBaileeSearchPriority_RU">InventBaileeSearchPriority_RU</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventBaileeSearchPriority_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventProfileId_RU name="InventProfileId_RU">InventProfileId_RU</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventProfileId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventProfileSplitLines_RU name="InventProfileSplitLines_RU">InventProfileSplitLines_RU</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventProfileSplitLines_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventProfileUseRelated_RU name="InventProfileUseRelated_RU">InventProfileUseRelated_RU</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventProfileUseRelated_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InvoiceDateControlType_W name="InvoiceDateControlType_W">InvoiceDateControlType_W</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice date control</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceDateControlType_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoice date control</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#InvoicePostingType_RU name="InvoicePostingType_RU">InvoicePostingType_RU</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoicePostingType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsMatchingAgreementSearchEnabled name="IsMatchingAgreementSearchEnabled">IsMatchingAgreementSearchEnabled</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsMatchingAgreementSearchEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#LeadTimeSalesDefault name="LeadTimeSalesDefault">LeadTimeSalesDefault</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeadTimeSalesDefault attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LineDiscCalculation_PL name="LineDiscCalculation_PL">LineDiscCalculation_PL</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDiscCalculation_PL attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MarkupHeading name="MarkupHeading">MarkupHeading</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarkupHeading attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MarkupLine name="MarkupLine">MarkupLine</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarkupLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MCRAcceptableSalesMargin name="MCRAcceptableSalesMargin">MCRAcceptableSalesMargin</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRAcceptableSalesMargin attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MCRAllowOutOfBalance name="MCRAllowOutOfBalance">MCRAllowOutOfBalance</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow out of balance</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRAllowOutOfBalance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow out of balance</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#MCRCheckHoldNumberOfDays name="MCRCheckHoldNumberOfDays">MCRCheckHoldNumberOfDays</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRCheckHoldNumberOfDays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MCRCheckHoldThresholdAmt name="MCRCheckHoldThresholdAmt">MCRCheckHoldThresholdAmt</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRCheckHoldThresholdAmt attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MCRCopyNotes name="MCRCopyNotes">MCRCopyNotes</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Copy notes when transfering to sales order</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRCopyNotes attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Copy notes when transfering to sales order</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#MCRDefQuoteConvHoldCode name="MCRDefQuoteConvHoldCode">MCRDefQuoteConvHoldCode</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default hold code</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRDefQuoteConvHoldCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default hold code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCREnableMarginAlert name="MCREnableMarginAlert">MCREnableMarginAlert</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCREnableMarginAlert attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MCRHoldCodeNoteType name="MCRHoldCodeNoteType">MCRHoldCodeNoteType</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRHoldCodeNoteType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCRHoldOrderDisplayColor name="MCRHoldOrderDisplayColor">MCRHoldOrderDisplayColor</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRHoldOrderDisplayColor attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MCROverpaidReviewThreshold name="MCROverpaidReviewThreshold">MCROverpaidReviewThreshold</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Overpaid percentage</td></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCROverpaidReviewThreshold attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Overpaid percentage</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MCROverUnderPaymentPrompt name="MCROverUnderPaymentPrompt">MCROverUnderPaymentPrompt</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Prompt for over/under payment</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCROverUnderPaymentPrompt attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Prompt for over/under payment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#MCRPickStagingUseReservation name="MCRPickStagingUseReservation">MCRPickStagingUseReservation</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pick staging reservation</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRPickStagingUseReservation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Pick staging reservation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#MCRPromptForItemList name="MCRPromptForItemList">MCRPromptForItemList</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Prompt for item list</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRPromptForItemList attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Prompt for item list</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#MCRQuestionableSalesMargin name="MCRQuestionableSalesMargin">MCRQuestionableSalesMargin</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRQuestionableSalesMargin attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MCRUnderpaidReviewThreshold name="MCRUnderpaidReviewThreshold">MCRUnderpaidReviewThreshold</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Underpaid percentage</td></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRUnderpaidReviewThreshold attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Underpaid percentage</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#OrderBatchTaskSize name="OrderBatchTaskSize">OrderBatchTaskSize</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderBatchTaskSize attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OrderEntryStatistics name="OrderEntryStatistics">OrderEntryStatistics</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Order entry statistics</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderEntryStatistics attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Order entry statistics</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#OrderType name="OrderType">OrderType</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OverDelivery name="OverDelivery">OverDelivery</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverDelivery attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PackingSlipByInvent_PL name="PackingSlipByInvent_PL">PackingSlipByInvent_PL</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Independent delivery note numbering</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingSlipByInvent_PL attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Independent delivery note numbering</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PdsBatchAttribAutoRes name="PdsBatchAttribAutoRes">PdsBatchAttribAutoRes</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsBatchAttribAutoRes attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PickinglistDefaultLanguage name="PickinglistDefaultLanguage">PickinglistDefaultLanguage</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PickinglistDefaultLanguage attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PickRouteStatusOnUpdate name="PickRouteStatusOnUpdate">PickRouteStatusOnUpdate</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PickRouteStatusOnUpdate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PostExciseInLedger_PL name="PostExciseInLedger_PL">PostExciseInLedger_PL</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Excise posting</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostExciseInLedger_PL attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Excise posting</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PostPackingSlip name="PostPackingSlip">PostPackingSlip</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostPackingSlip attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrePrintLevelShippingLabel name="PrePrintLevelShippingLabel">PrePrintLevelShippingLabel</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrePrintLevelShippingLabel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PriceDateType name="PriceDateType">PriceDateType</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceDateType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PromptQty name="PromptQty">PromptQty</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Prompt quantity field value when posting documents</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PromptQty attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Prompt quantity field value when posting documents</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PromptTransfer name="PromptTransfer">PromptTransfer</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Prompt for customer information</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PromptTransfer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Prompt for customer information</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#QuotationNumOfDaysExpiryDate name="QuotationNumOfDaysExpiryDate">QuotationNumOfDaysExpiryDate</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Days campaign expires</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationNumOfDaysExpiryDate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Days campaign expires</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#QuotationNumOfDaysFollowUpDate name="QuotationNumOfDaysFollowUpDate">QuotationNumOfDaysFollowUpDate</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Days before follow-up</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationNumOfDaysFollowUpDate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Days before follow-up</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ReduceInvoice name="ReduceInvoice">ReduceInvoice</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Automatic reduction invoice</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReduceInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Automatic reduction invoice</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ReducePackingSlip name="ReducePackingSlip">ReducePackingSlip</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Automatic reduction, packing slip</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReducePackingSlip attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Automatic reduction, packing slip</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ReducePickingList name="ReducePickingList">ReducePickingList</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Automatic reduction, picking list</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReducePickingList attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Automatic reduction, picking list</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Reservation name="Reservation">Reservation</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Reservation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReturnPeriodOfValidity name="ReturnPeriodOfValidity">ReturnPeriodOfValidity</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnPeriodOfValidity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SalesOriginId name="SalesOriginId">SalesOriginId</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOriginId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPoolId name="SalesPoolId">SalesPoolId</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales order pool</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPoolId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales order pool</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettleVoucher name="SettleVoucher">SettleVoucher</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default settlement type for credit notes</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettleVoucher attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default settlement type for credit notes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ShippingStat name="ShippingStat">ShippingStat</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingStat attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SplitDeliveryConfirmation name="SplitDeliveryConfirmation">SplitDeliveryConfirmation</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Confirmation</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SplitDeliveryConfirmation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Confirmation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SplitDeliveryInvoice name="SplitDeliveryInvoice">SplitDeliveryInvoice</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SplitDeliveryInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoice</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SplitDeliveryPackingSlip name="SplitDeliveryPackingSlip">SplitDeliveryPackingSlip</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Packing slip</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SplitDeliveryPackingSlip attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Packing slip</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SplitDeliveryPickingList name="SplitDeliveryPickingList">SplitDeliveryPickingList</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Picking list</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SplitDeliveryPickingList attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Picking list</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SplitInventOwnerIdInvoice_RU name="SplitInventOwnerIdInvoice_RU">SplitInventOwnerIdInvoice_RU</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SplitInventOwnerIdInvoice_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoice</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SplitInventProfileTypePackingSlip_RU name="SplitInventProfileTypePackingSlip_RU">SplitInventProfileTypePackingSlip_RU</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Packing slip</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SplitInventProfileTypePackingSlip_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Packing slip</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SplitInvoiceByServiceCode_BR name="SplitInvoiceByServiceCode_BR">SplitInvoiceByServiceCode_BR</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SplitInvoiceByServiceCode_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoice</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SplitPostingProfilePackingSlip_RU name="SplitPostingProfilePackingSlip_RU">SplitPostingProfilePackingSlip_RU</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Packing slip</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SplitPostingProfilePackingSlip_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Packing slip</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SplitSiteInvoice name="SplitSiteInvoice">SplitSiteInvoice</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SplitSiteInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoice</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SplitSitePackingSlip name="SplitSitePackingSlip">SplitSitePackingSlip</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Packing slip</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SplitSitePackingSlip attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Packing slip</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SplitSitePickingList name="SplitSitePickingList">SplitSitePickingList</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Picking list</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SplitSitePickingList attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Picking list</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#StructDepartment_RU name="StructDepartment_RU">StructDepartment_RU</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StructDepartment_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubDelivery name="SubDelivery">SubDelivery</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubDelivery attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SummaryErrorTolerance name="SummaryErrorTolerance">SummaryErrorTolerance</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Order error tolerance</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SummaryErrorTolerance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Order error tolerance</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SummaryUpdateBy name="SummaryUpdateBy">SummaryUpdateBy</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default values for summary update</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SummaryUpdateBy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default values for summary update</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TaxWithholdCalculate_BR name="TaxWithholdCalculate_BR">TaxWithholdCalculate_BR</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdCalculate_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxWithholdCalculateCrossCompany_BR name="TaxWithholdCalculateCrossCompany_BR">TaxWithholdCalculateCrossCompany_BR</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdCalculateCrossCompany_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxWithholdCompany_BR name="TaxWithholdCompany_BR">TaxWithholdCompany_BR</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdCompany_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationDocumentOnPackingSlip name="TransportationDocumentOnPackingSlip">TransportationDocumentOnPackingSlip</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use transportation document information on packing slip</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationDocumentOnPackingSlip attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use transportation document information on packing slip</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TransportInvoiceType_RU name="TransportInvoiceType_RU">TransportInvoiceType_RU</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportInvoiceType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UseSettleExchRate name="UseSettleExchRate">UseSettleExchRate</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use exchange rate from source document</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseSettleExchRate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use exchange rate from source document</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ValidDays name="ValidDays">ValidDays</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidDays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CalendarDays name="CalendarDays">CalendarDays</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalendarDays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DocumentTimezonePreference name="DocumentTimezonePreference">DocumentTimezonePreference</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentTimezonePreference attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InvoiceTimezonePreference name="InvoiceTimezonePreference">InvoiceTimezonePreference</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time zone preference for invoices</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceTimezonePreference attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time zone preference for invoices</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PackingSlipTimezonePreference name="PackingSlipTimezonePreference">PackingSlipTimezonePreference</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time zone preference for packing slips</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingSlipTimezonePreference attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time zone preference for packing slips</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ERFormatMappingSalesInvoice name="ERFormatMappingSalesInvoice">ERFormatMappingSalesInvoice</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales and Free text invoice</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERFormatMappingSalesInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales and Free text invoice</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ERFormatMappingSalesCreditNote name="ERFormatMappingSalesCreditNote">ERFormatMappingSalesCreditNote</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales and Free text credit note</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERFormatMappingSalesCreditNote attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales and Free text credit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ERFormatMappingProjectInvoice name="ERFormatMappingProjectInvoice">ERFormatMappingProjectInvoice</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project invoice</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERFormatMappingProjectInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project invoice</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ERFormatMappingProjectCreditNote name="ERFormatMappingProjectCreditNote">ERFormatMappingProjectCreditNote</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project credit note</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERFormatMappingProjectCreditNote attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Project credit note</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ERFormatMappingCollection name="ERFormatMappingCollection">ERFormatMappingCollection</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Collection letter</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERFormatMappingCollection attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Collection letter</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DeferDirectDeliveryCreation name="DeferDirectDeliveryCreation">DeferDirectDeliveryCreation</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Defer creation of direct delivery chains</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeferDirectDeliveryCreation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Defer creation of direct delivery chains</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#CheckMultipleWareHouses name="CheckMultipleWareHouses">CheckMultipleWareHouses</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Check for multiple warehouses</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckMultipleWareHouses attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Check for multiple warehouses</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DecimalPrecisionCheckQty name="DecimalPrecisionCheckQty">DecimalPrecisionCheckQty</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Check quantity for decimal precision</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DecimalPrecisionCheckQty attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Check quantity for decimal precision</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DefaultLanguage name="DefaultLanguage">DefaultLanguage</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default language for sales invoices</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultLanguage attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default language for sales invoices</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ASOHDefaultCheck name="ASOHDefaultCheck">ASOHDefaultCheck</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ASOHDefaultCheck attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ASOHMandatoryCheck name="ASOHMandatoryCheck">ASOHMandatoryCheck</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ASOHMandatoryCheck attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ASOHMandatoryHold name="ASOHMandatoryHold">ASOHMandatoryHold</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ASOHMandatoryHold attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ASOHHoldsControl name="ASOHHoldsControl">ASOHHoldsControl</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ASOHHoldsControl attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/SalesParameters (this entity)  

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

### <a href=#Relationship_BillOfLadingLanguageTableRelationshipId name="Relationship_BillOfLadingLanguageTableRelationshipId">Relationship_BillOfLadingLanguageTableRelationshipId</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BillOfLadingLanguageTableRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_BillOfLadingSalesCarrierRelationshipId name="Relationship_BillOfLadingSalesCarrierRelationshipId">Relationship_BillOfLadingSalesCarrierRelationshipId</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BillOfLadingSalesCarrierRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/SalesCarrier.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/SalesCarrier.cdm.json/SalesCarrier</a></td><td><a href="../Group/SalesCarrier.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultSalesOriginRelationshipId name="Relationship_DefaultSalesOriginRelationshipId">Relationship_DefaultSalesOriginRelationshipId</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultSalesOriginRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/SalesOrigin.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/SalesOrigin.cdm.json/SalesOrigin</a></td><td><a href="../Group/SalesOrigin.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultSalesPoolRelationshipId name="Relationship_DefaultSalesPoolRelationshipId">Relationship_DefaultSalesPoolRelationshipId</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultSalesPoolRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/SalesPool.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/SalesPool.cdm.json/SalesPool</a></td><td><a href="../Group/SalesPool.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DeliveryToInvoicePaymTermRelationshipId name="Relationship_DeliveryToInvoicePaymTermRelationshipId">Relationship_DeliveryToInvoicePaymTermRelationshipId</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DeliveryToInvoicePaymTermRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DomesticSalesTaxGroupRelationshipId name="Relationship_DomesticSalesTaxGroupRelationshipId">Relationship_DomesticSalesTaxGroupRelationshipId</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DomesticSalesTaxGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_EPDefaultSalesOriginRelationshipId name="Relationship_EPDefaultSalesOriginRelationshipId">Relationship_EPDefaultSalesOriginRelationshipId</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EPDefaultSalesOriginRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/SalesOrigin.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/SalesOrigin.cdm.json/SalesOrigin</a></td><td><a href="../Group/SalesOrigin.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ExchangeRateTypeRelationshipId name="Relationship_ExchangeRateTypeRelationshipId">Relationship_ExchangeRateTypeRelationshipId</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ExchangeRateTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/ExchangeRateType.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Group/ExchangeRateType.cdm.json/ExchangeRateType</a></td><td><a href="../../../Common/Currency/Group/ExchangeRateType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_GenericCurrencyRelationshipId name="Relationship_GenericCurrencyRelationshipId">Relationship_GenericCurrencyRelationshipId</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_GenericCurrencyRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_InventProfile_RURelationshipId name="Relationship_InventProfile_RURelationshipId">Relationship_InventProfile_RURelationshipId</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventProfile_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Group/InventProfile_RU.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventProfile_RU.cdm.json/InventProfile_RU</a></td><td><a href="../../Inventory/Group/InventProfile_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MCRDefQuoteConvHoldCodeRelationshipId name="Relationship_MCRDefQuoteConvHoldCodeRelationshipId">Relationship_MCRDefQuoteConvHoldCodeRelationshipId</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MCRDefQuoteConvHoldCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/MCRHoldCodeTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/MCRHoldCodeTable.cdm.json/MCRHoldCodeTable</a></td><td><a href="../Main/MCRHoldCodeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MCRHoldCodeNoteTypeRelationshipId name="Relationship_MCRHoldCodeNoteTypeRelationshipId">Relationship_MCRHoldCodeNoteTypeRelationshipId</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MCRHoldCodeNoteTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Group/DocuType.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Group/DocuType.cdm.json/DocuType</a></td><td><a href="../../../System/SystemAdministration/Group/DocuType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesQuotationTypeGroupRelationshipId name="Relationship_SalesQuotationTypeGroupRelationshipId">Relationship_SalesQuotationTypeGroupRelationshipId</a>

First included in: Parameter/SalesParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesQuotationTypeGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/SalesQuotationTypeGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/SalesQuotationTypeGroup.cdm.json/SalesQuotationTypeGroup</a></td><td><a href="../Group/SalesQuotationTypeGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Parameter/SalesParameters (this entity)  

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
