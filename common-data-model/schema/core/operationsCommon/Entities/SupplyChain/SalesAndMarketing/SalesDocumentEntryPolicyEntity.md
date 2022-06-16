---
title: SalesDocumentEntryPolicyEntity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Sales type document entry policies in SalesAndMarketing(SalesDocumentEntryPolicyEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/SalesDocumentEntryPolicyEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales type document entry policies</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AcceptablePriceMarginPercentage](#AcceptablePriceMarginPercentage)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[WillDocumentEntryAutomaticallyAllocateHeaderLevelCharges](#WillDocumentEntryAutomaticallyAllocateHeaderLevelCharges)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[WillDocumentEntryAutomaticallyAllocateLineLevelCharges](#WillDocumentEntryAutomaticallyAllocateLineLevelCharges)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[AreNoteTypeDocumentAttachmentsCopied](#AreNoteTypeDocumentAttachmentsCopied)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[WillDocumentEntryDisplayPriceMarginAlerts](#WillDocumentEntryDisplayPriceMarginAlerts)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[AreSalesOrderEntryStatisticsRecorded](#AreSalesOrderEntryStatisticsRecorded)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[BaseSalesPriceConversionExchangeRateTypeName](#BaseSalesPriceConversionExchangeRateTypeName)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[BaseSalesPriceConversionExchangeRateTypeRecId](#BaseSalesPriceConversionExchangeRateTypeRecId)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[BaseSalesPriceGenericCurrencyCode](#BaseSalesPriceGenericCurrencyCode)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[GeneralATPBackwardDemandTimeFenceDays](#GeneralATPBackwardDemandTimeFenceDays)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[GeneralATPBackwardSupplyTimeFenceDays](#GeneralATPBackwardSupplyTimeFenceDays)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[GeneralATPDelayedDemandOffsetDays](#GeneralATPDelayedDemandOffsetDays)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[GeneralATPDelayedSupplyOffsetDays](#GeneralATPDelayedSupplyOffsetDays)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[GeneralATPTimeFenceDays](#GeneralATPTimeFenceDays)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[GeneralSalesLeadTimeDays](#GeneralSalesLeadTimeDays)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[GeneralSalesOrderPromisingMethod](#GeneralSalesOrderPromisingMethod)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[InvoicedSalesOrderMaintenanceRule](#InvoicedSalesOrderMaintenanceRule)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[IsATPGenerallyIncludingPlannedOrders](#IsATPGenerallyIncludingPlannedOrders)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[WillBaseSalesPriceConversionApplySmartRoundingRules](#WillBaseSalesPriceConversionApplySmartRoundingRules)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[IsCustomerInformationTransferBeingPrompted](#IsCustomerInformationTransferBeingPrompted)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[WillSalesOrderDeletionVoidOrder](#WillSalesOrderDeletionVoidOrder)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[IsSalesOrderPromissingUsingWorkingDays](#IsSalesOrderPromissingUsingWorkingDays)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[IsSalesProductListBeingPrompted](#IsSalesProductListBeingPrompted)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[LineLevelDiscountCalculationRule](#LineLevelDiscountCalculationRule)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[OnHoldSalesOrderDisplayedRGBColor](#OnHoldSalesOrderDisplayedRGBColor)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[QuestionablePriceMarginPercentage](#QuestionablePriceMarginPercentage)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[SalesOrderHoldCommentDocumentAttachmentTypeCode](#SalesOrderHoldCommentDocumentAttachmentTypeCode)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[SalesOrderLineDeliveryDateUpdateRule](#SalesOrderLineDeliveryDateUpdateRule)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[TradeAgreementSearchDateType](#TradeAgreementSearchDateType)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[IsSalesAgreementCustomerAccountNumberUniquenessRequired](#IsSalesAgreementCustomerAccountNumberUniquenessRequired)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[IsSalesAgreementClassificationUniquenessRequired](#IsSalesAgreementClassificationUniquenessRequired)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[IsSalesAgreementCurrencyUniquenessRequired](#IsSalesAgreementCurrencyUniquenessRequired)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[IsSalesAgreementDocumentTitleUniquenessRequired](#IsSalesAgreementDocumentTitleUniquenessRequired)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[IsSalesAgreementExternalDocumentReferenceUniquenessRequired](#IsSalesAgreementExternalDocumentReferenceUniquenessRequired)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[IsSalesAgreementYearUniquenessRequired](#IsSalesAgreementYearUniquenessRequired)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[ExcisePosting](#ExcisePosting)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[DomesticSalesTaxGroupCode](#DomesticSalesTaxGroupCode)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[BackingTable_SalesParametersRelationshipId](#BackingTable_SalesParametersRelationshipId)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SalesDocumentEntryPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEntryPolicyEntity</a>|

### <a href=#AcceptablePriceMarginPercentage name="AcceptablePriceMarginPercentage">AcceptablePriceMarginPercentage</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceptablePriceMarginPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillDocumentEntryAutomaticallyAllocateHeaderLevelCharges name="WillDocumentEntryAutomaticallyAllocateHeaderLevelCharges">WillDocumentEntryAutomaticallyAllocateHeaderLevelCharges</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillDocumentEntryAutomaticallyAllocateHeaderLevelCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillDocumentEntryAutomaticallyAllocateLineLevelCharges name="WillDocumentEntryAutomaticallyAllocateLineLevelCharges">WillDocumentEntryAutomaticallyAllocateLineLevelCharges</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillDocumentEntryAutomaticallyAllocateLineLevelCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreNoteTypeDocumentAttachmentsCopied name="AreNoteTypeDocumentAttachmentsCopied">AreNoteTypeDocumentAttachmentsCopied</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreNoteTypeDocumentAttachmentsCopied attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillDocumentEntryDisplayPriceMarginAlerts name="WillDocumentEntryDisplayPriceMarginAlerts">WillDocumentEntryDisplayPriceMarginAlerts</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillDocumentEntryDisplayPriceMarginAlerts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSalesOrderEntryStatisticsRecorded name="AreSalesOrderEntryStatisticsRecorded">AreSalesOrderEntryStatisticsRecorded</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSalesOrderEntryStatisticsRecorded attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BaseSalesPriceConversionExchangeRateTypeName name="BaseSalesPriceConversionExchangeRateTypeName">BaseSalesPriceConversionExchangeRateTypeName</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BaseSalesPriceConversionExchangeRateTypeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BaseSalesPriceConversionExchangeRateTypeRecId name="BaseSalesPriceConversionExchangeRateTypeRecId">BaseSalesPriceConversionExchangeRateTypeRecId</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BaseSalesPriceConversionExchangeRateTypeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BaseSalesPriceGenericCurrencyCode name="BaseSalesPriceGenericCurrencyCode">BaseSalesPriceGenericCurrencyCode</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BaseSalesPriceGenericCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneralATPBackwardDemandTimeFenceDays name="GeneralATPBackwardDemandTimeFenceDays">GeneralATPBackwardDemandTimeFenceDays</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralATPBackwardDemandTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneralATPBackwardSupplyTimeFenceDays name="GeneralATPBackwardSupplyTimeFenceDays">GeneralATPBackwardSupplyTimeFenceDays</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralATPBackwardSupplyTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneralATPDelayedDemandOffsetDays name="GeneralATPDelayedDemandOffsetDays">GeneralATPDelayedDemandOffsetDays</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralATPDelayedDemandOffsetDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneralATPDelayedSupplyOffsetDays name="GeneralATPDelayedSupplyOffsetDays">GeneralATPDelayedSupplyOffsetDays</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralATPDelayedSupplyOffsetDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneralATPTimeFenceDays name="GeneralATPTimeFenceDays">GeneralATPTimeFenceDays</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralATPTimeFenceDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneralSalesLeadTimeDays name="GeneralSalesLeadTimeDays">GeneralSalesLeadTimeDays</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralSalesLeadTimeDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneralSalesOrderPromisingMethod name="GeneralSalesOrderPromisingMethod">GeneralSalesOrderPromisingMethod</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralSalesOrderPromisingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoicedSalesOrderMaintenanceRule name="InvoicedSalesOrderMaintenanceRule">InvoicedSalesOrderMaintenanceRule</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoicedSalesOrderMaintenanceRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsATPGenerallyIncludingPlannedOrders name="IsATPGenerallyIncludingPlannedOrders">IsATPGenerallyIncludingPlannedOrders</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsATPGenerallyIncludingPlannedOrders attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillBaseSalesPriceConversionApplySmartRoundingRules name="WillBaseSalesPriceConversionApplySmartRoundingRules">WillBaseSalesPriceConversionApplySmartRoundingRules</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillBaseSalesPriceConversionApplySmartRoundingRules attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCustomerInformationTransferBeingPrompted name="IsCustomerInformationTransferBeingPrompted">IsCustomerInformationTransferBeingPrompted</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCustomerInformationTransferBeingPrompted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSalesOrderDeletionVoidOrder name="WillSalesOrderDeletionVoidOrder">WillSalesOrderDeletionVoidOrder</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSalesOrderDeletionVoidOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesOrderPromissingUsingWorkingDays name="IsSalesOrderPromissingUsingWorkingDays">IsSalesOrderPromissingUsingWorkingDays</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesOrderPromissingUsingWorkingDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesProductListBeingPrompted name="IsSalesProductListBeingPrompted">IsSalesProductListBeingPrompted</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesProductListBeingPrompted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineLevelDiscountCalculationRule name="LineLevelDiscountCalculationRule">LineLevelDiscountCalculationRule</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineLevelDiscountCalculationRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnHoldSalesOrderDisplayedRGBColor name="OnHoldSalesOrderDisplayedRGBColor">OnHoldSalesOrderDisplayedRGBColor</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnHoldSalesOrderDisplayedRGBColor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuestionablePriceMarginPercentage name="QuestionablePriceMarginPercentage">QuestionablePriceMarginPercentage</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuestionablePriceMarginPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderHoldCommentDocumentAttachmentTypeCode name="SalesOrderHoldCommentDocumentAttachmentTypeCode">SalesOrderHoldCommentDocumentAttachmentTypeCode</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderHoldCommentDocumentAttachmentTypeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderLineDeliveryDateUpdateRule name="SalesOrderLineDeliveryDateUpdateRule">SalesOrderLineDeliveryDateUpdateRule</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderLineDeliveryDateUpdateRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TradeAgreementSearchDateType name="TradeAgreementSearchDateType">TradeAgreementSearchDateType</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TradeAgreementSearchDateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesAgreementCustomerAccountNumberUniquenessRequired name="IsSalesAgreementCustomerAccountNumberUniquenessRequired">IsSalesAgreementCustomerAccountNumberUniquenessRequired</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesAgreementCustomerAccountNumberUniquenessRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesAgreementClassificationUniquenessRequired name="IsSalesAgreementClassificationUniquenessRequired">IsSalesAgreementClassificationUniquenessRequired</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesAgreementClassificationUniquenessRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesAgreementCurrencyUniquenessRequired name="IsSalesAgreementCurrencyUniquenessRequired">IsSalesAgreementCurrencyUniquenessRequired</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesAgreementCurrencyUniquenessRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesAgreementDocumentTitleUniquenessRequired name="IsSalesAgreementDocumentTitleUniquenessRequired">IsSalesAgreementDocumentTitleUniquenessRequired</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesAgreementDocumentTitleUniquenessRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesAgreementExternalDocumentReferenceUniquenessRequired name="IsSalesAgreementExternalDocumentReferenceUniquenessRequired">IsSalesAgreementExternalDocumentReferenceUniquenessRequired</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesAgreementExternalDocumentReferenceUniquenessRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesAgreementYearUniquenessRequired name="IsSalesAgreementYearUniquenessRequired">IsSalesAgreementYearUniquenessRequired</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesAgreementYearUniquenessRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExcisePosting name="ExcisePosting">ExcisePosting</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExcisePosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DomesticSalesTaxGroupCode name="DomesticSalesTaxGroupCode">DomesticSalesTaxGroupCode</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DomesticSalesTaxGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_SalesParametersRelationshipId name="BackingTable_SalesParametersRelationshipId">BackingTable_SalesParametersRelationshipId</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_SalesParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Parameter/SalesParameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Parameter/SalesParameters.cdm.json/SalesParameters</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Parameter/SalesParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/SalesDocumentEntryPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
