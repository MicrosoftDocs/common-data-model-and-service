---
title: SalesQuotationHeaderV2Entity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Sales quotation headers V2 in SalesAndMarketing(SalesQuotationHeaderV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/SalesQuotationHeaderV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales quotation headers V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[SalesQuotationNumber](#SalesQuotationNumber)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[SalesQuotationStatus](#SalesQuotationStatus)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[SalesQuotationTypeId](#SalesQuotationTypeId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[SalesQuotationExpiryDate](#SalesQuotationExpiryDate)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[QuotationFollowUpActivity](#QuotationFollowUpActivity)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[SalesQuotationFollowUpDate](#SalesQuotationFollowUpDate)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[BankDocumentType](#BankDocumentType)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[AddressRefTableId](#AddressRefTableId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[AddressRefRecId](#AddressRefRecId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[RequestingCustomerAccountNumber](#RequestingCustomerAccountNumber)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[InvoiceCustomerAccountNumber](#InvoiceCustomerAccountNumber)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[LineDiscountCustomerGroupCode](#LineDiscountCustomerGroupCode)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[CashDiscountCode](#CashDiscountCode)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[ContactPersonId](#ContactPersonId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[CustomersReference](#CustomersReference)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DefaultLedgerDimension](#DefaultLedgerDimension)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[SalesOrderPromisingMethod](#SalesOrderPromisingMethod)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DeliveryAddressName](#DeliveryAddressName)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[TotalDiscountPercentage](#TotalDiscountPercentage)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DeliveryModeCode](#DeliveryModeCode)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DeliveryReasonCode](#DeliveryReasonCode)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DeliveryTermsCode](#DeliveryTermsCode)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[Email](#Email)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[TotalDiscountCustomerGroupCode](#TotalDiscountCustomerGroupCode)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[ExportReason](#ExportReason)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[FixedDueDate](#FixedDueDate)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[FixedExchangeRate](#FixedExchangeRate)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[ArePricesIncludingSalesTax](#ArePricesIncludingSalesTax)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DefaultShippingWarehouseId](#DefaultShippingWarehouseId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DefaultShippingSiteId](#DefaultShippingSiteId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[LanguageId](#LanguageId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[EUSalesListCode](#EUSalesListCode)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[ChargeCustomerGroupId](#ChargeCustomerGroupId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[MultilineDiscountCustomerGroupCode](#MultilineDiscountCustomerGroupCode)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[NumberSequenceGroupId](#NumberSequenceGroupId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[PaymentTermsName](#PaymentTermsName)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[CustomerPaymentMethodName](#CustomerPaymentMethodName)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[CustomerPaymentMethodSpecificationName](#CustomerPaymentMethodSpecificationName)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[IntrastatPortId](#IntrastatPortId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[CustomerPostingProfileId](#CustomerPostingProfileId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[PriceCustomerGroupCode](#PriceCustomerGroupCode)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[ReceiptDateRequested](#ReceiptDateRequested)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[SalesQuotationName](#SalesQuotationName)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[CommissionSalesRepresentativeGroupId](#CommissionSalesRepresentativeGroupId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[SalesOrderOriginCode](#SalesOrderOriginCode)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[SalesOrderPoolId](#SalesOrderPoolId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[SalesUnitId](#SalesUnitId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[CustomerTransactionSettlementType](#CustomerTransactionSettlementType)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[RequestedShippingDate](#RequestedShippingDate)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[IntrastatStatisticsProcedureCode](#IntrastatStatisticsProcedureCode)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[SalesTaxGroupCode](#SalesTaxGroupCode)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[IntrastatTransactionCode](#IntrastatTransactionCode)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[IntrastatTransportModeCode](#IntrastatTransportModeCode)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[URL](#URL)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[TaxExemptNumber](#TaxExemptNumber)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[SalesResponsible](#SalesResponsible)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[SalesTaker](#SalesTaker)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[QuotationResponsiblePersonnelNumber](#QuotationResponsiblePersonnelNumber)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[QuotationTakerPersonnelNumber](#QuotationTakerPersonnelNumber)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DefaultLedgerDimensionDisplayValue](#DefaultLedgerDimensionDisplayValue)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[ProspectId](#ProspectId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[CashDiscountPercentage](#CashDiscountPercentage)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[CampaignId](#CampaignId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[CommissionCustomerGroupId](#CommissionCustomerGroupId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[SalesQuotationConfirmationDate](#SalesQuotationConfirmationDate)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[ManualEntryChangepolicy](#ManualEntryChangepolicy)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[TeleMarketingCallListId](#TeleMarketingCallListId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[IsCustomerFinalUser](#IsCustomerFinalUser)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[CustomerRequisitionNumber](#CustomerRequisitionNumber)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[CustomerPaymentFineCode](#CustomerPaymentFineCode)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[CustomerPaymentFinancialInterestCode](#CustomerPaymentFinancialInterestCode)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[OpportunityId](#OpportunityId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DeliveryPostalAddressRecId](#DeliveryPostalAddressRecId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[IsDeliveryAddressOrderSpecific](#IsDeliveryAddressOrderSpecific)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[FormattedDeliveryAddress](#FormattedDeliveryAddress)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DeliveryBuildingCompliment](#DeliveryBuildingCompliment)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DeliveryAddressCity](#DeliveryAddressCity)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DeliveryAddressCountryRegionId](#DeliveryAddressCountryRegionId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DeliveryAddressCountryRegionISOCode](#DeliveryAddressCountryRegionISOCode)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DeliveryAddressCountyId](#DeliveryAddressCountyId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DeliveryAddressDescription](#DeliveryAddressDescription)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DeliveryAddressDistrictName](#DeliveryAddressDistrictName)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DeliveryAddressDunsNumber](#DeliveryAddressDunsNumber)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[IsDeliveryAddressPrivate](#IsDeliveryAddressPrivate)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DeliveryAddressLatitude](#DeliveryAddressLatitude)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DeliveryAddressLocationId](#DeliveryAddressLocationId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DeliveryAddressLongitude](#DeliveryAddressLongitude)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DeliveryAddressPostBox](#DeliveryAddressPostBox)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DeliveryAddressStateId](#DeliveryAddressStateId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DeliveryAddressStreet](#DeliveryAddressStreet)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DeliveryAddressStreetNumber](#DeliveryAddressStreetNumber)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DeliveryValidFrom](#DeliveryValidFrom)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DeliveryValidTo](#DeliveryValidTo)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DeliveryAddressTimeZone](#DeliveryAddressTimeZone)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DeliveryAddressZipCode](#DeliveryAddressZipCode)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DeliveryAddressCityInKana](#DeliveryAddressCityInKana)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[DeliveryAddressStreetInKana](#DeliveryAddressStreetInKana)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[GeneratedSalesOrderNumber](#GeneratedSalesOrderNumber)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[ServiceAgreementId](#ServiceAgreementId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[QuotationDocumentConclusionName](#QuotationDocumentConclusionName)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[QuotationDocumentIntroductionName](#QuotationDocumentIntroductionName)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[QuotationDocumentTitleName](#QuotationDocumentTitleName)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[IsSalesQuotationTemplateActive](#IsSalesQuotationTemplateActive)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[SalesQuotationTemplateGroupId](#SalesQuotationTemplateGroupId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[SalesQuotationTemplateName](#SalesQuotationTemplateName)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[QuotationReasonCode](#QuotationReasonCode)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[SalesPurchOperationTypeRecId](#SalesPurchOperationTypeRecId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[FiscalDocumentOperationTypeId](#FiscalDocumentOperationTypeId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[InvoiceAddressStreet](#InvoiceAddressStreet)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[FormattedInvoiceAddress](#FormattedInvoiceAddress)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[InvoiceBuildingCompliment](#InvoiceBuildingCompliment)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[InvoiceAddressCity](#InvoiceAddressCity)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[InvoiceAddressCountryRegionId](#InvoiceAddressCountryRegionId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[InvoiceAddressCountyId](#InvoiceAddressCountyId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[InvoiceAddressDistrictName](#InvoiceAddressDistrictName)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[IsInvoiceAddressPrivate](#IsInvoiceAddressPrivate)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[InvoiceAddressLatitude](#InvoiceAddressLatitude)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[InvoiceAddressLongitude](#InvoiceAddressLongitude)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[InvoiceAddressPostBox](#InvoiceAddressPostBox)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[InvoiceAddressStateId](#InvoiceAddressStateId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[InvoiceAddressStreetNumber](#InvoiceAddressStreetNumber)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[InvoiceAddressTimeZone](#InvoiceAddressTimeZone)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[InvoiceAddressZipCode](#InvoiceAddressZipCode)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[InvoiceAddressStreetInKana](#InvoiceAddressStreetInKana)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[InvoiceAddressCityInKana](#InvoiceAddressCityInKana)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[QuotationTotalAmount](#QuotationTotalAmount)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[QuotationTotalChargesAmount](#QuotationTotalChargesAmount)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[QuotationTotalDiscountAmount](#QuotationTotalDiscountAmount)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[QuotationTotalTaxAmount](#QuotationTotalTaxAmount)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[QuotationHeaderTaxAmount](#QuotationHeaderTaxAmount)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[TotalDiscountAmount](#TotalDiscountAmount)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[AreTotalsCalculated](#AreTotalsCalculated)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[InvoiceValidTo](#InvoiceValidTo)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[InvoiceValidFrom](#InvoiceValidFrom)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[InvoiceAddressCountryRegionISOCode](#InvoiceAddressCountryRegionISOCode)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[ReportingCurrencyFixedExchangeRate](#ReportingCurrencyFixedExchangeRate)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[SalesQuotationCalculatedTotalsRecId](#SalesQuotationCalculatedTotalsRecId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[BackingTable_SalesQuotationTableRelationshipId](#BackingTable_SalesQuotationTableRelationshipId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SalesQuotationHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderV2Entity</a>|

### <a href=#SalesQuotationNumber name="SalesQuotationNumber">SalesQuotationNumber</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesQuotationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesQuotationStatus name="SalesQuotationStatus">SalesQuotationStatus</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesQuotationStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesQuotationTypeId name="SalesQuotationTypeId">SalesQuotationTypeId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesQuotationTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesQuotationExpiryDate name="SalesQuotationExpiryDate">SalesQuotationExpiryDate</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesQuotationExpiryDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationFollowUpActivity name="QuotationFollowUpActivity">QuotationFollowUpActivity</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationFollowUpActivity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesQuotationFollowUpDate name="SalesQuotationFollowUpDate">SalesQuotationFollowUpDate</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesQuotationFollowUpDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankDocumentType name="BankDocumentType">BankDocumentType</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankDocumentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressRefTableId name="AddressRefTableId">AddressRefTableId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressRefTableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressRefRecId name="AddressRefRecId">AddressRefRecId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressRefRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestingCustomerAccountNumber name="RequestingCustomerAccountNumber">RequestingCustomerAccountNumber</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestingCustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceCustomerAccountNumber name="InvoiceCustomerAccountNumber">InvoiceCustomerAccountNumber</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceCustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDiscountCustomerGroupCode name="LineDiscountCustomerGroupCode">LineDiscountCustomerGroupCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDiscountCustomerGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountCode name="CashDiscountCode">CashDiscountCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPersonId name="ContactPersonId">ContactPersonId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPersonId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

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

### <a href=#CustomersReference name="CustomersReference">CustomersReference</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomersReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLedgerDimension name="DefaultLedgerDimension">DefaultLedgerDimension</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderPromisingMethod name="SalesOrderPromisingMethod">SalesOrderPromisingMethod</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderPromisingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressName name="DeliveryAddressName">DeliveryAddressName</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery address name </td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delivery address name </td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountPercentage name="TotalDiscountPercentage">TotalDiscountPercentage</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryModeCode name="DeliveryModeCode">DeliveryModeCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryModeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryReasonCode name="DeliveryReasonCode">DeliveryReasonCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryTermsCode name="DeliveryTermsCode">DeliveryTermsCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryTermsCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Email name="Email">Email</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Email attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountCustomerGroupCode name="TotalDiscountCustomerGroupCode">TotalDiscountCustomerGroupCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscountCustomerGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExportReason name="ExportReason">ExportReason</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExportReason attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedDueDate name="FixedDueDate">FixedDueDate</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedDueDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedExchangeRate name="FixedExchangeRate">FixedExchangeRate</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedExchangeRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArePricesIncludingSalesTax name="ArePricesIncludingSalesTax">ArePricesIncludingSalesTax</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArePricesIncludingSalesTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultShippingWarehouseId name="DefaultShippingWarehouseId">DefaultShippingWarehouseId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultShippingWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultShippingSiteId name="DefaultShippingSiteId">DefaultShippingSiteId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultShippingSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

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

### <a href=#EUSalesListCode name="EUSalesListCode">EUSalesListCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EUSalesListCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeCustomerGroupId name="ChargeCustomerGroupId">ChargeCustomerGroupId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeCustomerGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MultilineDiscountCustomerGroupCode name="MultilineDiscountCustomerGroupCode">MultilineDiscountCustomerGroupCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MultilineDiscountCustomerGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceGroupId name="NumberSequenceGroupId">NumberSequenceGroupId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentTermsName name="PaymentTermsName">PaymentTermsName</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentTermsName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerPaymentMethodName name="CustomerPaymentMethodName">CustomerPaymentMethodName</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerPaymentMethodName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerPaymentMethodSpecificationName name="CustomerPaymentMethodSpecificationName">CustomerPaymentMethodSpecificationName</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerPaymentMethodSpecificationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatPortId name="IntrastatPortId">IntrastatPortId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatPortId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerPostingProfileId name="CustomerPostingProfileId">CustomerPostingProfileId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerPostingProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceCustomerGroupCode name="PriceCustomerGroupCode">PriceCustomerGroupCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceCustomerGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptDateRequested name="ReceiptDateRequested">ReceiptDateRequested</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptDateRequested attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesQuotationName name="SalesQuotationName">SalesQuotationName</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesQuotationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CommissionSalesRepresentativeGroupId name="CommissionSalesRepresentativeGroupId">CommissionSalesRepresentativeGroupId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommissionSalesRepresentativeGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderOriginCode name="SalesOrderOriginCode">SalesOrderOriginCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderOriginCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderPoolId name="SalesOrderPoolId">SalesOrderPoolId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderPoolId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesUnitId name="SalesUnitId">SalesUnitId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesUnitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerTransactionSettlementType name="CustomerTransactionSettlementType">CustomerTransactionSettlementType</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerTransactionSettlementType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedShippingDate name="RequestedShippingDate">RequestedShippingDate</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedShippingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatStatisticsProcedureCode name="IntrastatStatisticsProcedureCode">IntrastatStatisticsProcedureCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatStatisticsProcedureCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroupCode name="SalesTaxGroupCode">SalesTaxGroupCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatTransactionCode name="IntrastatTransactionCode">IntrastatTransactionCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatTransactionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatTransportModeCode name="IntrastatTransportModeCode">IntrastatTransportModeCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatTransportModeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#URL name="URL">URL</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the URL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxExemptNumber name="TaxExemptNumber">TaxExemptNumber</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxExemptNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesResponsible name="SalesResponsible">SalesResponsible</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesResponsible attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaker name="SalesTaker">SalesTaker</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaker attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationResponsiblePersonnelNumber name="QuotationResponsiblePersonnelNumber">QuotationResponsiblePersonnelNumber</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales responsible</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationResponsiblePersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales responsible</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationTakerPersonnelNumber name="QuotationTakerPersonnelNumber">QuotationTakerPersonnelNumber</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales taker</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationTakerPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales taker</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLedgerDimensionDisplayValue name="DefaultLedgerDimensionDisplayValue">DefaultLedgerDimensionDisplayValue</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProspectId name="ProspectId">ProspectId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProspectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountPercentage name="CashDiscountPercentage">CashDiscountPercentage</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CampaignId name="CampaignId">CampaignId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CampaignId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CommissionCustomerGroupId name="CommissionCustomerGroupId">CommissionCustomerGroupId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommissionCustomerGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesQuotationConfirmationDate name="SalesQuotationConfirmationDate">SalesQuotationConfirmationDate</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesQuotationConfirmationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManualEntryChangepolicy name="ManualEntryChangepolicy">ManualEntryChangepolicy</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManualEntryChangepolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TeleMarketingCallListId name="TeleMarketingCallListId">TeleMarketingCallListId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TeleMarketingCallListId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCustomerFinalUser name="IsCustomerFinalUser">IsCustomerFinalUser</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCustomerFinalUser attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerRequisitionNumber name="CustomerRequisitionNumber">CustomerRequisitionNumber</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerRequisitionNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerPaymentFineCode name="CustomerPaymentFineCode">CustomerPaymentFineCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerPaymentFineCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerPaymentFinancialInterestCode name="CustomerPaymentFinancialInterestCode">CustomerPaymentFinancialInterestCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerPaymentFinancialInterestCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OpportunityId name="OpportunityId">OpportunityId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OpportunityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryPostalAddressRecId name="DeliveryPostalAddressRecId">DeliveryPostalAddressRecId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryPostalAddressRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDeliveryAddressOrderSpecific name="IsDeliveryAddressOrderSpecific">IsDeliveryAddressOrderSpecific</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>One time delivery address</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDeliveryAddressOrderSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>One time delivery address</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormattedDeliveryAddress name="FormattedDeliveryAddress">FormattedDeliveryAddress</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormattedDeliveryAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryBuildingCompliment name="DeliveryBuildingCompliment">DeliveryBuildingCompliment</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryBuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCity name="DeliveryAddressCity">DeliveryAddressCity</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCountryRegionId name="DeliveryAddressCountryRegionId">DeliveryAddressCountryRegionId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCountryRegionISOCode name="DeliveryAddressCountryRegionISOCode">DeliveryAddressCountryRegionISOCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCountryRegionISOCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCountyId name="DeliveryAddressCountyId">DeliveryAddressCountyId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCountyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressDescription name="DeliveryAddressDescription">DeliveryAddressDescription</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressDistrictName name="DeliveryAddressDistrictName">DeliveryAddressDistrictName</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressDistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressDunsNumber name="DeliveryAddressDunsNumber">DeliveryAddressDunsNumber</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressDunsNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDeliveryAddressPrivate name="IsDeliveryAddressPrivate">IsDeliveryAddressPrivate</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is delivery address private</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDeliveryAddressPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is delivery address private</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressLatitude name="DeliveryAddressLatitude">DeliveryAddressLatitude</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressLatitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressLocationId name="DeliveryAddressLocationId">DeliveryAddressLocationId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressLongitude name="DeliveryAddressLongitude">DeliveryAddressLongitude</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressLongitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressPostBox name="DeliveryAddressPostBox">DeliveryAddressPostBox</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressPostBox attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressStateId name="DeliveryAddressStateId">DeliveryAddressStateId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressStreet name="DeliveryAddressStreet">DeliveryAddressStreet</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressStreetNumber name="DeliveryAddressStreetNumber">DeliveryAddressStreetNumber</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressStreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryValidFrom name="DeliveryValidFrom">DeliveryValidFrom</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryValidTo name="DeliveryValidTo">DeliveryValidTo</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressTimeZone name="DeliveryAddressTimeZone">DeliveryAddressTimeZone</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressTimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressZipCode name="DeliveryAddressZipCode">DeliveryAddressZipCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCityInKana name="DeliveryAddressCityInKana">DeliveryAddressCityInKana</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCityInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressStreetInKana name="DeliveryAddressStreetInKana">DeliveryAddressStreetInKana</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressStreetInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneratedSalesOrderNumber name="GeneratedSalesOrderNumber">GeneratedSalesOrderNumber</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneratedSalesOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceAgreementId name="ServiceAgreementId">ServiceAgreementId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceAgreementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationDocumentConclusionName name="QuotationDocumentConclusionName">QuotationDocumentConclusionName</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationDocumentConclusionName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationDocumentIntroductionName name="QuotationDocumentIntroductionName">QuotationDocumentIntroductionName</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationDocumentIntroductionName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationDocumentTitleName name="QuotationDocumentTitleName">QuotationDocumentTitleName</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationDocumentTitleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesQuotationTemplateActive name="IsSalesQuotationTemplateActive">IsSalesQuotationTemplateActive</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesQuotationTemplateActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesQuotationTemplateGroupId name="SalesQuotationTemplateGroupId">SalesQuotationTemplateGroupId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesQuotationTemplateGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesQuotationTemplateName name="SalesQuotationTemplateName">SalesQuotationTemplateName</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesQuotationTemplateName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationReasonCode name="QuotationReasonCode">QuotationReasonCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPurchOperationTypeRecId name="SalesPurchOperationTypeRecId">SalesPurchOperationTypeRecId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPurchOperationTypeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentOperationTypeId name="FiscalDocumentOperationTypeId">FiscalDocumentOperationTypeId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentOperationTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressStreet name="InvoiceAddressStreet">InvoiceAddressStreet</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormattedInvoiceAddress name="FormattedInvoiceAddress">FormattedInvoiceAddress</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormattedInvoiceAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceBuildingCompliment name="InvoiceBuildingCompliment">InvoiceBuildingCompliment</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceBuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressCity name="InvoiceAddressCity">InvoiceAddressCity</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressCountryRegionId name="InvoiceAddressCountryRegionId">InvoiceAddressCountryRegionId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressCountyId name="InvoiceAddressCountyId">InvoiceAddressCountyId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressCountyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressDistrictName name="InvoiceAddressDistrictName">InvoiceAddressDistrictName</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressDistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInvoiceAddressPrivate name="IsInvoiceAddressPrivate">IsInvoiceAddressPrivate</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInvoiceAddressPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressLatitude name="InvoiceAddressLatitude">InvoiceAddressLatitude</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressLatitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressLongitude name="InvoiceAddressLongitude">InvoiceAddressLongitude</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressLongitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressPostBox name="InvoiceAddressPostBox">InvoiceAddressPostBox</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressPostBox attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressStateId name="InvoiceAddressStateId">InvoiceAddressStateId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressStreetNumber name="InvoiceAddressStreetNumber">InvoiceAddressStreetNumber</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressStreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressTimeZone name="InvoiceAddressTimeZone">InvoiceAddressTimeZone</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressTimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressZipCode name="InvoiceAddressZipCode">InvoiceAddressZipCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressStreetInKana name="InvoiceAddressStreetInKana">InvoiceAddressStreetInKana</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressStreetInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressCityInKana name="InvoiceAddressCityInKana">InvoiceAddressCityInKana</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressCityInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationTotalAmount name="QuotationTotalAmount">QuotationTotalAmount</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationTotalAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationTotalChargesAmount name="QuotationTotalChargesAmount">QuotationTotalChargesAmount</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationTotalChargesAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationTotalDiscountAmount name="QuotationTotalDiscountAmount">QuotationTotalDiscountAmount</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationTotalDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationTotalTaxAmount name="QuotationTotalTaxAmount">QuotationTotalTaxAmount</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationTotalTaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationHeaderTaxAmount name="QuotationHeaderTaxAmount">QuotationHeaderTaxAmount</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationHeaderTaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountAmount name="TotalDiscountAmount">TotalDiscountAmount</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreTotalsCalculated name="AreTotalsCalculated">AreTotalsCalculated</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreTotalsCalculated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceValidTo name="InvoiceValidTo">InvoiceValidTo</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceValidFrom name="InvoiceValidFrom">InvoiceValidFrom</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressCountryRegionISOCode name="InvoiceAddressCountryRegionISOCode">InvoiceAddressCountryRegionISOCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressCountryRegionISOCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCurrencyFixedExchangeRate name="ReportingCurrencyFixedExchangeRate">ReportingCurrencyFixedExchangeRate</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCurrencyFixedExchangeRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesQuotationCalculatedTotalsRecId name="SalesQuotationCalculatedTotalsRecId">SalesQuotationCalculatedTotalsRecId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesQuotationCalculatedTotalsRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_SalesQuotationTableRelationshipId name="BackingTable_SalesQuotationTableRelationshipId">BackingTable_SalesQuotationTableRelationshipId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_SalesQuotationTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/SalesQuotationTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/SalesQuotationTable.cdm.json/SalesQuotationTable</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/SalesQuotationTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderV2Entity (this entity)  

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
