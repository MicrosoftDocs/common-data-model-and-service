---
title: VendRequestForQuotationJournalHeaderEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Request for quotation journal headers

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Request for quotation journal headers</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[PurchaseAgreementId](#PurchaseAgreementId)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[TotalRFQAmount](#TotalRFQAmount)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[VendorCashDiscountCode](#VendorCashDiscountCode)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[ContactPersonId](#ContactPersonId)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[DeliveryAddressDate](#DeliveryAddressDate)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[DeliveryAddressName](#DeliveryAddressName)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[TotalDiscountPercentage](#TotalDiscountPercentage)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[DeliveryModeCode](#DeliveryModeCode)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[DeliveryTermsCode](#DeliveryTermsCode)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[VendorEmailAddress](#VendorEmailAddress)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[TotalDiscountAmount](#TotalDiscountAmount)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[RFQExpirationDateTime](#RFQExpirationDateTime)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[ArePricesIncludingSalesTax](#ArePricesIncludingSalesTax)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[InternalRFQJournalNumber](#InternalRFQJournalNumber)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[BuyerGroupId](#BuyerGroupId)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[LanguageId](#LanguageId)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[ChargeVendorGroupId](#ChargeVendorGroupId)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[MultilineDiscountVendorGroupCode](#MultilineDiscountVendorGroupCode)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[NumberSequenceGroupId](#NumberSequenceGroupId)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[PaymentTermsName](#PaymentTermsName)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[PaymentScheduleName](#PaymentScheduleName)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[VendorPaymentMethodName](#VendorPaymentMethodName)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[VendorPaymentMethodSpecificationName](#VendorPaymentMethodSpecificationName)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[ContactPhoneNumber](#ContactPhoneNumber)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[PriceVendorGroupCode](#PriceVendorGroupCode)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[ArePricesDisplayed](#ArePricesDisplayed)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsReplySheetIncluded](#IsReplySheetIncluded)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[PurchaseOrderNumber](#PurchaseOrderNumber)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[TotalBalance](#TotalBalance)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[RFQCaseNumber](#RFQCaseNumber)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[RFQJournalDate](#RFQJournalDate)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[RFQNumber](#RFQNumber)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[RFQName](#RFQName)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsQuotationReplyHeaderCurrencyCodeDisplayed](#IsQuotationReplyHeaderCurrencyCodeDisplayed)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsQuotationReplyHeaderDeliveryDateDisplayed](#IsQuotationReplyHeaderDeliveryDateDisplayed)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsQuotationReplyHeaderDeliveryTermsDisplayed](#IsQuotationReplyHeaderDeliveryTermsDisplayed)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsQuotationReplyHeaderDocumentationDisplayed](#IsQuotationReplyHeaderDocumentationDisplayed)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsQuotationReplyHeaderTotalDiscountPercentageDisplayed](#IsQuotationReplyHeaderTotalDiscountPercentageDisplayed)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsQuotationReplyHeaderPurchaseChargeDisplayed](#IsQuotationReplyHeaderPurchaseChargeDisplayed)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsQuotationReplyHeaderPaymentTermsDisplayed](#IsQuotationReplyHeaderPaymentTermsDisplayed)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsQuotationReplyHeaderValidFromDateDisplayed](#IsQuotationReplyHeaderValidFromDateDisplayed)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsQuotationReplyHeaderValidToDateDisplayed](#IsQuotationReplyHeaderValidToDateDisplayed)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsQuotationReplyHeaderVendReferenceDisplayed](#IsQuotationReplyHeaderVendReferenceDisplayed)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsQuotationReplyLineDeliveryDateDisplayed](#IsQuotationReplyLineDeliveryDateDisplayed)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsQuotationReplyLineDocumentationDisplayed](#IsQuotationReplyLineDocumentationDisplayed)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsQuotationReplyLineExternalItemDescriptionDisplayed](#IsQuotationReplyLineExternalItemDescriptionDisplayed)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsQuotationReplyLineExternalItemNumberDisplayed](#IsQuotationReplyLineExternalItemNumberDisplayed)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsQuotationReplyLineLeadTimeDisplayed](#IsQuotationReplyLineLeadTimeDisplayed)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsQuotationReplyLineLineDiscountAmountDisplayed](#IsQuotationReplyLineLineDiscountAmountDisplayed)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsQuotationReplyLinePurchaseChargeDisplayed](#IsQuotationReplyLinePurchaseChargeDisplayed)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsQuotationReplyLineMultilineDiscountAmountDisplayed](#IsQuotationReplyLineMultilineDiscountAmountDisplayed)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsQuotationReplyLineMultilineDiscountPercentageDisplayed](#IsQuotationReplyLineMultilineDiscountPercentageDisplayed)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsQuotationReplyLineDiscountPercentDisplayed](#IsQuotationReplyLineDiscountPercentDisplayed)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsQuotationReplyLinePriceQuantityDisplayed](#IsQuotationReplyLinePriceQuantityDisplayed)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsQuotationReplyLineQuantityDisplayed](#IsQuotationReplyLineQuantityDisplayed)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsQuotationReplyLineUnitSymbolDisplayed](#IsQuotationReplyLineUnitSymbolDisplayed)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsQuotationReplyLineValidFromDateDisplayed](#IsQuotationReplyLineValidFromDateDisplayed)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsQuotationReplyLineValidToDateDisplayed](#IsQuotationReplyLineValidToDateDisplayed)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsQuotationReplyLineWorkingDaysDisplayed](#IsQuotationReplyLineWorkingDaysDisplayed)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[ResultingPurchaseDocumentType](#ResultingPurchaseDocumentType)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[TotalRoundOffAmount](#TotalRoundOffAmount)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[RFQStatus](#RFQStatus)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[TotalLineDiscountAmount](#TotalLineDiscountAmount)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[TotalChargeAmount](#TotalChargeAmount)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[TotalTaxAmount](#TotalTaxAmount)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[TaxGroupCode](#TaxGroupCode)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[ResultingPurchaseAgreementExpirationDate](#ResultingPurchaseAgreementExpirationDate)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[ResultingPurchaseAgreementEffectiveDate](#ResultingPurchaseAgreementEffectiveDate)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[TaxExemptNumber](#TaxExemptNumber)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[VendorAccountNumber](#VendorAccountNumber)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[VendorOrderReference](#VendorOrderReference)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[RequestingWorkerPersonnelNumber](#RequestingWorkerPersonnelNumber)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[VendorReasonCode](#VendorReasonCode)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[VendorReasonComment](#VendorReasonComment)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[OrderingWorkerPersonnelNumber](#OrderingWorkerPersonnelNumber)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[DeliveryPostalAddressRecId](#DeliveryPostalAddressRecId)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[DeliveryAddressLocationId](#DeliveryAddressLocationId)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[FormattedDeliveryAddress](#FormattedDeliveryAddress)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[DeliveryAddressZipCode](#DeliveryAddressZipCode)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[DeliveryAddressBuildingCompliment](#DeliveryAddressBuildingCompliment)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[DeliveryAddressCity](#DeliveryAddressCity)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[DeliveryAddressCityInKana](#DeliveryAddressCityInKana)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[DeliveryAddressCountryRegionId](#DeliveryAddressCountryRegionId)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[DeliveryAddressCountryRegionISOCode](#DeliveryAddressCountryRegionISOCode)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[DeliveryAddressCountyId](#DeliveryAddressCountyId)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[DeliveryAddressDescription](#DeliveryAddressDescription)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[DeliveryAddressDistrictName](#DeliveryAddressDistrictName)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[DeliveryAddressDunsNumber](#DeliveryAddressDunsNumber)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[DeliveryAddressLatitude](#DeliveryAddressLatitude)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[IsDeliveryAddressPrivate](#IsDeliveryAddressPrivate)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[DeliveryAddressLongitude](#DeliveryAddressLongitude)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[DeliveryAddressPostBox](#DeliveryAddressPostBox)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[DeliveryAddressStateId](#DeliveryAddressStateId)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[DeliveryAddressStreet](#DeliveryAddressStreet)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[DeliveryAddressStreetInKana](#DeliveryAddressStreetInKana)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[DeliveryAddressStreetNumber](#DeliveryAddressStreetNumber)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[DeliveryAddressValidFrom](#DeliveryAddressValidFrom)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[DeliveryAddressValidTo](#DeliveryAddressValidTo)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[DeliveryAddressTimeZone](#DeliveryAddressTimeZone)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[BidSubmittedBy](#BidSubmittedBy)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[BidSubmittingPersonPartyNumber](#BidSubmittingPersonPartyNumber)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[Relationship_OrderingWorkerRelationshipId](#Relationship_OrderingWorkerRelationshipId)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[Relationship_RequestingWorkerRelationshipId](#Relationship_RequestingWorkerRelationshipId)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[BackingTable_VendRFQJourRelationshipId](#BackingTable_VendRFQJourRelationshipId)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="VendRequestForQuotationJournalHeaderEntity.md" target="_blank">ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity</a>|

### <a href=#PurchaseAgreementId name="PurchaseAgreementId">PurchaseAgreementId</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseAgreementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalRFQAmount name="TotalRFQAmount">TotalRFQAmount</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalRFQAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorCashDiscountCode name="VendorCashDiscountCode">VendorCashDiscountCode</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorCashDiscountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPersonId name="ContactPersonId">ContactPersonId</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPersonId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

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

### <a href=#DeliveryAddressDate name="DeliveryAddressDate">DeliveryAddressDate</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressName name="DeliveryAddressName">DeliveryAddressName</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery address name </td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delivery address name </td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountPercentage name="TotalDiscountPercentage">TotalDiscountPercentage</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryModeCode name="DeliveryModeCode">DeliveryModeCode</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryModeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryTermsCode name="DeliveryTermsCode">DeliveryTermsCode</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryTermsCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorEmailAddress name="VendorEmailAddress">VendorEmailAddress</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorEmailAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountAmount name="TotalDiscountAmount">TotalDiscountAmount</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQExpirationDateTime name="RFQExpirationDateTime">RFQExpirationDateTime</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQExpirationDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArePricesIncludingSalesTax name="ArePricesIncludingSalesTax">ArePricesIncludingSalesTax</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArePricesIncludingSalesTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InternalRFQJournalNumber name="InternalRFQJournalNumber">InternalRFQJournalNumber</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Internal RFQ journal number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InternalRFQJournalNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Internal RFQ journal number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BuyerGroupId name="BuyerGroupId">BuyerGroupId</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BuyerGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LanguageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeVendorGroupId name="ChargeVendorGroupId">ChargeVendorGroupId</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeVendorGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MultilineDiscountVendorGroupCode name="MultilineDiscountVendorGroupCode">MultilineDiscountVendorGroupCode</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MultilineDiscountVendorGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceGroupId name="NumberSequenceGroupId">NumberSequenceGroupId</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentTermsName name="PaymentTermsName">PaymentTermsName</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentTermsName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentScheduleName name="PaymentScheduleName">PaymentScheduleName</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentScheduleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorPaymentMethodName name="VendorPaymentMethodName">VendorPaymentMethodName</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorPaymentMethodName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorPaymentMethodSpecificationName name="VendorPaymentMethodSpecificationName">VendorPaymentMethodSpecificationName</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorPaymentMethodSpecificationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPhoneNumber name="ContactPhoneNumber">ContactPhoneNumber</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPhoneNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceVendorGroupCode name="PriceVendorGroupCode">PriceVendorGroupCode</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceVendorGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArePricesDisplayed name="ArePricesDisplayed">ArePricesDisplayed</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArePricesDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReplySheetIncluded name="IsReplySheetIncluded">IsReplySheetIncluded</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReplySheetIncluded attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrderNumber name="PurchaseOrderNumber">PurchaseOrderNumber</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalBalance name="TotalBalance">TotalBalance</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalBalance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQCaseNumber name="RFQCaseNumber">RFQCaseNumber</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>RFQ case number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQCaseNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>RFQ case number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQJournalDate name="RFQJournalDate">RFQJournalDate</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>RFQ journal date</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQJournalDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>RFQ journal date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQNumber name="RFQNumber">RFQNumber</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQName name="RFQName">RFQName</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>RFQ name</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>RFQ name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyHeaderCurrencyCodeDisplayed name="IsQuotationReplyHeaderCurrencyCodeDisplayed">IsQuotationReplyHeaderCurrencyCodeDisplayed</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ reply header currency code displayed</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyHeaderCurrencyCodeDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ reply header currency code displayed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyHeaderDeliveryDateDisplayed name="IsQuotationReplyHeaderDeliveryDateDisplayed">IsQuotationReplyHeaderDeliveryDateDisplayed</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ reply header delivery date displayed</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyHeaderDeliveryDateDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ reply header delivery date displayed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyHeaderDeliveryTermsDisplayed name="IsQuotationReplyHeaderDeliveryTermsDisplayed">IsQuotationReplyHeaderDeliveryTermsDisplayed</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ reply header delivery terms displayed</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyHeaderDeliveryTermsDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ reply header delivery terms displayed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyHeaderDocumentationDisplayed name="IsQuotationReplyHeaderDocumentationDisplayed">IsQuotationReplyHeaderDocumentationDisplayed</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ reply header documentation displayed</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyHeaderDocumentationDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ reply header documentation displayed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyHeaderTotalDiscountPercentageDisplayed name="IsQuotationReplyHeaderTotalDiscountPercentageDisplayed">IsQuotationReplyHeaderTotalDiscountPercentageDisplayed</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ reply header total discount percentage displayed</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyHeaderTotalDiscountPercentageDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ reply header total discount percentage displayed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyHeaderPurchaseChargeDisplayed name="IsQuotationReplyHeaderPurchaseChargeDisplayed">IsQuotationReplyHeaderPurchaseChargeDisplayed</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ reply header purchase charge displayed</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyHeaderPurchaseChargeDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ reply header purchase charge displayed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyHeaderPaymentTermsDisplayed name="IsQuotationReplyHeaderPaymentTermsDisplayed">IsQuotationReplyHeaderPaymentTermsDisplayed</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ reply header payment terms displayed</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyHeaderPaymentTermsDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ reply header payment terms displayed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyHeaderValidFromDateDisplayed name="IsQuotationReplyHeaderValidFromDateDisplayed">IsQuotationReplyHeaderValidFromDateDisplayed</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ reply header valid from date displayed</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyHeaderValidFromDateDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ reply header valid from date displayed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyHeaderValidToDateDisplayed name="IsQuotationReplyHeaderValidToDateDisplayed">IsQuotationReplyHeaderValidToDateDisplayed</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ reply header valid to date displayed</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyHeaderValidToDateDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ reply header valid to date displayed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyHeaderVendReferenceDisplayed name="IsQuotationReplyHeaderVendReferenceDisplayed">IsQuotationReplyHeaderVendReferenceDisplayed</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ reply header external vendor reference displayed</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyHeaderVendReferenceDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ reply header external vendor reference displayed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineDeliveryDateDisplayed name="IsQuotationReplyLineDeliveryDateDisplayed">IsQuotationReplyLineDeliveryDateDisplayed</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ reply line delivery date displayed</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineDeliveryDateDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ reply line delivery date displayed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineDocumentationDisplayed name="IsQuotationReplyLineDocumentationDisplayed">IsQuotationReplyLineDocumentationDisplayed</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ reply line documentation displayed</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineDocumentationDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ reply line documentation displayed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineExternalItemDescriptionDisplayed name="IsQuotationReplyLineExternalItemDescriptionDisplayed">IsQuotationReplyLineExternalItemDescriptionDisplayed</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ reply line external item description displayed</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineExternalItemDescriptionDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ reply line external item description displayed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineExternalItemNumberDisplayed name="IsQuotationReplyLineExternalItemNumberDisplayed">IsQuotationReplyLineExternalItemNumberDisplayed</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ reply line external item number displayed</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineExternalItemNumberDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ reply line external item number displayed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineLeadTimeDisplayed name="IsQuotationReplyLineLeadTimeDisplayed">IsQuotationReplyLineLeadTimeDisplayed</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ reply line lead time displayed</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineLeadTimeDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ reply line lead time displayed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineLineDiscountAmountDisplayed name="IsQuotationReplyLineLineDiscountAmountDisplayed">IsQuotationReplyLineLineDiscountAmountDisplayed</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ reply line line discount amount displayed</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineLineDiscountAmountDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ reply line line discount amount displayed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLinePurchaseChargeDisplayed name="IsQuotationReplyLinePurchaseChargeDisplayed">IsQuotationReplyLinePurchaseChargeDisplayed</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ reply line purchase charge displayed</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLinePurchaseChargeDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ reply line purchase charge displayed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineMultilineDiscountAmountDisplayed name="IsQuotationReplyLineMultilineDiscountAmountDisplayed">IsQuotationReplyLineMultilineDiscountAmountDisplayed</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ reply line multiline discount amount displayed</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineMultilineDiscountAmountDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ reply line multiline discount amount displayed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineMultilineDiscountPercentageDisplayed name="IsQuotationReplyLineMultilineDiscountPercentageDisplayed">IsQuotationReplyLineMultilineDiscountPercentageDisplayed</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ reply line multiline discount percentage displayed</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineMultilineDiscountPercentageDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ reply line multiline discount percentage displayed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineDiscountPercentDisplayed name="IsQuotationReplyLineDiscountPercentDisplayed">IsQuotationReplyLineDiscountPercentDisplayed</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ reply line discount percent displayed</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineDiscountPercentDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ reply line discount percent displayed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLinePriceQuantityDisplayed name="IsQuotationReplyLinePriceQuantityDisplayed">IsQuotationReplyLinePriceQuantityDisplayed</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ reply line price quantity displayed</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLinePriceQuantityDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ reply line price quantity displayed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineQuantityDisplayed name="IsQuotationReplyLineQuantityDisplayed">IsQuotationReplyLineQuantityDisplayed</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ reply line quantity displayed</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineQuantityDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ reply line quantity displayed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineUnitSymbolDisplayed name="IsQuotationReplyLineUnitSymbolDisplayed">IsQuotationReplyLineUnitSymbolDisplayed</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ reply line unit symbol displayed</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineUnitSymbolDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ reply line unit symbol displayed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineValidFromDateDisplayed name="IsQuotationReplyLineValidFromDateDisplayed">IsQuotationReplyLineValidFromDateDisplayed</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ reply line valid from date displayed</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineValidFromDateDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ reply line valid from date displayed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineValidToDateDisplayed name="IsQuotationReplyLineValidToDateDisplayed">IsQuotationReplyLineValidToDateDisplayed</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ reply line valid to date displayed</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineValidToDateDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ reply line valid to date displayed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineWorkingDaysDisplayed name="IsQuotationReplyLineWorkingDaysDisplayed">IsQuotationReplyLineWorkingDaysDisplayed</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ reply line working days displayed</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineWorkingDaysDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ reply line working days displayed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResultingPurchaseDocumentType name="ResultingPurchaseDocumentType">ResultingPurchaseDocumentType</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResultingPurchaseDocumentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalRoundOffAmount name="TotalRoundOffAmount">TotalRoundOffAmount</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalRoundOffAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQStatus name="RFQStatus">RFQStatus</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalLineDiscountAmount name="TotalLineDiscountAmount">TotalLineDiscountAmount</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalLineDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalChargeAmount name="TotalChargeAmount">TotalChargeAmount</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalChargeAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalTaxAmount name="TotalTaxAmount">TotalTaxAmount</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total tax amount</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalTaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total tax amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxGroupCode name="TaxGroupCode">TaxGroupCode</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResultingPurchaseAgreementExpirationDate name="ResultingPurchaseAgreementExpirationDate">ResultingPurchaseAgreementExpirationDate</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResultingPurchaseAgreementExpirationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResultingPurchaseAgreementEffectiveDate name="ResultingPurchaseAgreementEffectiveDate">ResultingPurchaseAgreementEffectiveDate</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResultingPurchaseAgreementEffectiveDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxExemptNumber name="TaxExemptNumber">TaxExemptNumber</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxExemptNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAccountNumber name="VendorAccountNumber">VendorAccountNumber</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorOrderReference name="VendorOrderReference">VendorOrderReference</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorOrderReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestingWorkerPersonnelNumber name="RequestingWorkerPersonnelNumber">RequestingWorkerPersonnelNumber</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requesting worker personnel number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestingWorkerPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Requesting worker personnel number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorReasonCode name="VendorReasonCode">VendorReasonCode</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorReasonComment name="VendorReasonComment">VendorReasonComment</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorReasonComment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionDisplayValue name="DefaultDimensionDisplayValue">DefaultDimensionDisplayValue</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderingWorkerPersonnelNumber name="OrderingWorkerPersonnelNumber">OrderingWorkerPersonnelNumber</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ordering worker personnel number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderingWorkerPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ordering worker personnel number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryPostalAddressRecId name="DeliveryPostalAddressRecId">DeliveryPostalAddressRecId</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryPostalAddressRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressLocationId name="DeliveryAddressLocationId">DeliveryAddressLocationId</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormattedDeliveryAddress name="FormattedDeliveryAddress">FormattedDeliveryAddress</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormattedDeliveryAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressZipCode name="DeliveryAddressZipCode">DeliveryAddressZipCode</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressBuildingCompliment name="DeliveryAddressBuildingCompliment">DeliveryAddressBuildingCompliment</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressBuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCity name="DeliveryAddressCity">DeliveryAddressCity</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCityInKana name="DeliveryAddressCityInKana">DeliveryAddressCityInKana</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCityInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCountryRegionId name="DeliveryAddressCountryRegionId">DeliveryAddressCountryRegionId</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCountryRegionISOCode name="DeliveryAddressCountryRegionISOCode">DeliveryAddressCountryRegionISOCode</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCountryRegionISOCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCountyId name="DeliveryAddressCountyId">DeliveryAddressCountyId</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCountyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressDescription name="DeliveryAddressDescription">DeliveryAddressDescription</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery address description </td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delivery address description </td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressDistrictName name="DeliveryAddressDistrictName">DeliveryAddressDistrictName</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressDistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressDunsNumber name="DeliveryAddressDunsNumber">DeliveryAddressDunsNumber</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressDunsNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressLatitude name="DeliveryAddressLatitude">DeliveryAddressLatitude</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressLatitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDeliveryAddressPrivate name="IsDeliveryAddressPrivate">IsDeliveryAddressPrivate</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is delivery address private</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDeliveryAddressPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is delivery address private</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressLongitude name="DeliveryAddressLongitude">DeliveryAddressLongitude</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressLongitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressPostBox name="DeliveryAddressPostBox">DeliveryAddressPostBox</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressPostBox attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressStateId name="DeliveryAddressStateId">DeliveryAddressStateId</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressStreet name="DeliveryAddressStreet">DeliveryAddressStreet</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressStreetInKana name="DeliveryAddressStreetInKana">DeliveryAddressStreetInKana</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressStreetInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressStreetNumber name="DeliveryAddressStreetNumber">DeliveryAddressStreetNumber</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressStreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressValidFrom name="DeliveryAddressValidFrom">DeliveryAddressValidFrom</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressValidTo name="DeliveryAddressValidTo">DeliveryAddressValidTo</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressTimeZone name="DeliveryAddressTimeZone">DeliveryAddressTimeZone</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressTimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BidSubmittedBy name="BidSubmittedBy">BidSubmittedBy</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BidSubmittedBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BidSubmittingPersonPartyNumber name="BidSubmittingPersonPartyNumber">BidSubmittingPersonPartyNumber</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bid submitting person party number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BidSubmittingPersonPartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bid submitting person party number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OrderingWorkerRelationshipId name="Relationship_OrderingWorkerRelationshipId">Relationship_OrderingWorkerRelationshipId</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OrderingWorkerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RequestingWorkerRelationshipId name="Relationship_RequestingWorkerRelationshipId">Relationship_RequestingWorkerRelationshipId</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RequestingWorkerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_VendRFQJourRelationshipId name="BackingTable_VendRFQJourRelationshipId">BackingTable_VendRFQJourRelationshipId</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_VendRFQJourRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Transaction/VendRFQJour.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Transaction/VendRFQJour.cdm.json/VendRFQJour</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Transaction/VendRFQJour.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/VendRequestForQuotationJournalHeaderEntity (this entity)  

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
