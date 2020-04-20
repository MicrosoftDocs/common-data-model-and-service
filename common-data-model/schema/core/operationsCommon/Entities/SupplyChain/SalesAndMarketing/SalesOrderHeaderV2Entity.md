---
title: SalesOrderHeaderV2Entity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# SalesOrderHeaderV2Entity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/SalesOrderHeaderV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[SalesOrderNumber](#SalesOrderNumber)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[SalesOrderStatus](#SalesOrderStatus)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[OrderingCustomerAccountNumber](#OrderingCustomerAccountNumber)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[InvoiceCustomerAccountNumber](#InvoiceCustomerAccountNumber)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[LineDiscountCustomerGroupCode](#LineDiscountCustomerGroupCode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[CashDiscountCode](#CashDiscountCode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[PaymentTermsBaseDate](#PaymentTermsBaseDate)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[CommissionCustomerGroupId](#CommissionCustomerGroupId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[ContactPersonId](#ContactPersonId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[CustomersOrderReference](#CustomersOrderReference)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DefaultLedgerDimension](#DefaultLedgerDimension)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[SalesOrderPromisingMethod](#SalesOrderPromisingMethod)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DeliveryAddressName](#DeliveryAddressName)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DirectDebitMandate](#DirectDebitMandate)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[TotalDiscountPercentage](#TotalDiscountPercentage)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DeliveryModeCode](#DeliveryModeCode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DeliveryReasonCode](#DeliveryReasonCode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DeliveryTermsCode](#DeliveryTermsCode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[Email](#Email)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[TotalDiscountCustomerGroupCode](#TotalDiscountCustomerGroupCode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[ExportReason](#ExportReason)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[FixedDueDate](#FixedDueDate)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[FixedExchangeRate](#FixedExchangeRate)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[InvoicePaymentAttachmentType](#InvoicePaymentAttachmentType)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[ArePricesIncludingSalesTax](#ArePricesIncludingSalesTax)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DefaultShippingWarehouseId](#DefaultShippingWarehouseId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DefaultShippingSiteId](#DefaultShippingSiteId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[LanguageId](#LanguageId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[EUSalesListCode](#EUSalesListCode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[ChargeCustomerGroupId](#ChargeCustomerGroupId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[SalesAgreementNumber](#SalesAgreementNumber)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[IsSalesProcessingStopped](#IsSalesProcessingStopped)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[MultilineDiscountCustomerGroupCode](#MultilineDiscountCustomerGroupCode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[NumberSequenceGroupId](#NumberSequenceGroupId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[IsOneTimeCustomer](#IsOneTimeCustomer)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[PaymentTermsName](#PaymentTermsName)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[PaymentScheduleName](#PaymentScheduleName)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[CustomerPaymentMethodName](#CustomerPaymentMethodName)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[CustomerPaymentMethodSpecificationName](#CustomerPaymentMethodSpecificationName)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[WillAutomaticInventoryReservationConsiderBatchAttributes](#WillAutomaticInventoryReservationConsiderBatchAttributes)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[SalesRebateCustomerGroupId](#SalesRebateCustomerGroupId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[TMACustomerGroupId](#TMACustomerGroupId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[IntrastatPortId](#IntrastatPortId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[CustomerPostingProfileId](#CustomerPostingProfileId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[PriceCustomerGroupCode](#PriceCustomerGroupCode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[CustomerRequisitionNumber](#CustomerRequisitionNumber)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[QuotationNumber](#QuotationNumber)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[ConfirmedReceiptDate](#ConfirmedReceiptDate)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[RequestedReceiptDate](#RequestedReceiptDate)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[InventoryReservationMethod](#InventoryReservationMethod)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[CommissionSalesRepresentativeGroupId](#CommissionSalesRepresentativeGroupId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[SalesOrderName](#SalesOrderName)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[SalesOrderOriginCode](#SalesOrderOriginCode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[SalesOrderPoolId](#SalesOrderPoolId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[SalesUnitId](#SalesUnitId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[CustomerTransactionSettlementType](#CustomerTransactionSettlementType)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[ConfirmedShippingDate](#ConfirmedShippingDate)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[RequestedShippingDate](#RequestedShippingDate)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[SalesTaker](#SalesTaker)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[CampaignId](#CampaignId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[IntrastatStatisticsProcedureCode](#IntrastatStatisticsProcedureCode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[SalesTaxGroupCode](#SalesTaxGroupCode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[IntrastatTransactionCode](#IntrastatTransactionCode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[IntrastatTransportModeCode](#IntrastatTransportModeCode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[URL](#URL)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[TaxExemptNumber](#TaxExemptNumber)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[SalesResponsible](#SalesResponsible)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DirectDebitMandateId](#DirectDebitMandateId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[OrderResponsiblePersonnelNumber](#OrderResponsiblePersonnelNumber)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[OrderTakerPersonnelNumber](#OrderTakerPersonnelNumber)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DefaultLedgerDimensionDisplayValue](#DefaultLedgerDimensionDisplayValue)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[IsEntryCertificateRequired](#IsEntryCertificateRequired)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[IsOwnEntryCertificateIssued](#IsOwnEntryCertificateIssued)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[InvoiceType](#InvoiceType)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[TransportationBrokerId](#TransportationBrokerId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[ShippingCarrierId](#ShippingCarrierId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[ShippingCarrierServiceGroupId](#ShippingCarrierServiceGroupId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[ShippingCarrierServiceId](#ShippingCarrierServiceId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[TransportationModeId](#TransportationModeId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[TransportationRoutePlanId](#TransportationRoutePlanId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[TransportationTemplateId](#TransportationTemplateId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DeliveryPostalAddressRecId](#DeliveryPostalAddressRecId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[IsDeliveryAddressOrderSpecific](#IsDeliveryAddressOrderSpecific)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[FormattedDelveryAddress](#FormattedDelveryAddress)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DeliveryBuildingCompliment](#DeliveryBuildingCompliment)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DeliveryAddressCity](#DeliveryAddressCity)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DeliveryAddressCountryRegionId](#DeliveryAddressCountryRegionId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DeliveryAddressCountryRegionISOCode](#DeliveryAddressCountryRegionISOCode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DeliveryAddressCountyId](#DeliveryAddressCountyId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DeliveryAddressDescription](#DeliveryAddressDescription)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DeliveryAddressDistrictName](#DeliveryAddressDistrictName)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DeliveryAddressDunsNumber](#DeliveryAddressDunsNumber)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[IsDeliveryAddressPrivate](#IsDeliveryAddressPrivate)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DeliveryAddressLatitude](#DeliveryAddressLatitude)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DeliveryAddressLocationId](#DeliveryAddressLocationId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DeliveryAddressLongitude](#DeliveryAddressLongitude)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DeliveryAddressPostBox](#DeliveryAddressPostBox)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DeliveryAddressStateId](#DeliveryAddressStateId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DeliveryAddressStreet](#DeliveryAddressStreet)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DeliveryAddressStreetNumber](#DeliveryAddressStreetNumber)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DeliveryValidFrom](#DeliveryValidFrom)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DeliveryValidTo](#DeliveryValidTo)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DeliveryAddressTimeZone](#DeliveryAddressTimeZone)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DeliveryAddressZipCode](#DeliveryAddressZipCode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DeliveryAddressCityInKana](#DeliveryAddressCityInKana)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[DeliveryAddressStreetInKana](#DeliveryAddressStreetInKana)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[IsConsolidatedInvoiceTarget](#IsConsolidatedInvoiceTarget)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[EInvoiceDimensionAccountCode](#EInvoiceDimensionAccountCode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[IsEInvoiceDimensionAccountCodeSpecifiedPerLine](#IsEInvoiceDimensionAccountCodeSpecifiedPerLine)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[CreditNoteReasonCode](#CreditNoteReasonCode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[IsExportSale](#IsExportSale)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[BankConstantSymbol](#BankConstantSymbol)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[BankSpecificSymbol](#BankSpecificSymbol)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[CFPSCode](#CFPSCode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[IsFinalUser](#IsFinalUser)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[CustomerPaymentFineCode](#CustomerPaymentFineCode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[FiscalDocumentTypeRecId](#FiscalDocumentTypeRecId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[CustomerPaymentFinancialInterestCode](#CustomerPaymentFinancialInterestCode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[FiscalOperationPresenceType](#FiscalOperationPresenceType)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[SalesPurchOperationTypeRecId](#SalesPurchOperationTypeRecId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[IsServiceDeliveryAddressBased](#IsServiceDeliveryAddressBased)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[ServiceFiscalInformationCode](#ServiceFiscalInformationCode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[FiscalDocumentOperationTypeId](#FiscalDocumentOperationTypeId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[FiscalDocumentTypeId](#FiscalDocumentTypeId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[InvoiceAddressStreet](#InvoiceAddressStreet)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[FormattedInvoiceAddress](#FormattedInvoiceAddress)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[InvoiceBuildingCompliment](#InvoiceBuildingCompliment)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[InvoiceAddressCity](#InvoiceAddressCity)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[InvoiceAddressCountryRegionId](#InvoiceAddressCountryRegionId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[InvoiceAddressCountyId](#InvoiceAddressCountyId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[InvoiceAddressDistrictName](#InvoiceAddressDistrictName)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[IsInvoiceAddressPrivate](#IsInvoiceAddressPrivate)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[InvoiceAddressLatitude](#InvoiceAddressLatitude)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[InvoiceAddressLongitude](#InvoiceAddressLongitude)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[InvoiceAddressPostBox](#InvoiceAddressPostBox)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[InvoiceAddressStateId](#InvoiceAddressStateId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[InvoiceAddressStreetNumber](#InvoiceAddressStreetNumber)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[InvoiceAddressTimeZone](#InvoiceAddressTimeZone)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[InvoiceAddressZipCode](#InvoiceAddressZipCode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[InvoiceAddressCityInKana](#InvoiceAddressCityInKana)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[InvoiceAddressStreetInKana](#InvoiceAddressStreetInKana)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[OrderTotalAmount](#OrderTotalAmount)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[OrderTotalChargesAmount](#OrderTotalChargesAmount)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[OrderTotalDiscountAmount](#OrderTotalDiscountAmount)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[OrderTotalTaxAmount](#OrderTotalTaxAmount)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[OrderHeaderTaxAmount](#OrderHeaderTaxAmount)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[TotalDiscountAmount](#TotalDiscountAmount)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[SalesOrderProcessingStatus](#SalesOrderProcessingStatus)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[AreTotalsCalculated](#AreTotalsCalculated)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[TransportationDocumentLineId](#TransportationDocumentLineId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[InvoiceValidTo](#InvoiceValidTo)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[InvoiceValidFrom](#InvoiceValidFrom)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[OrderCreationDateTime](#OrderCreationDateTime)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[InvoiceAddressCountryRegionISOCode](#InvoiceAddressCountryRegionISOCode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[ProjectId](#ProjectId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[SkipCreateAutoCharges](#SkipCreateAutoCharges)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[BaseDocumentDate](#BaseDocumentDate)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[CIPEcode](#CIPEcode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[BaseDocumentNumber](#BaseDocumentNumber)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[BaseDocumentType](#BaseDocumentType)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[BaseDocumentItemNumber](#BaseDocumentItemNumber)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[BaseDocumentLineNumber](#BaseDocumentLineNumber)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[OrderOrAgreementCode](#OrderOrAgreementCode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[TenderCode](#TenderCode)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[ReportingCurrencyFixedExchangeRate](#ReportingCurrencyFixedExchangeRate)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[ShippingCarrierCustomerAccountNumber](#ShippingCarrierCustomerAccountNumber)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[RevRecFollowOriginalPricingMethod](#RevRecFollowOriginalPricingMethod)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[RevRecContractEndDate](#RevRecContractEndDate)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[RevRecContractStartDate](#RevRecContractStartDate)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[RevRecLatestReverseJournal](#RevRecLatestReverseJournal)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[RevRecMultipleSOReallocation](#RevRecMultipleSOReallocation)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[RevRecReallocationId](#RevRecReallocationId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[Relationship_SalesOrderOriginRelationshipId](#Relationship_SalesOrderOriginRelationshipId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[Relationship_ProjectRelationshipId](#Relationship_ProjectRelationshipId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[BackingTable_SalesTableRelationshipId](#BackingTable_SalesTableRelationshipId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SalesOrderHeaderV2Entity.md" target="_blank">SalesAndMarketing/SalesOrderHeaderV2Entity</a>|

### <a href=#SalesOrderNumber name="SalesOrderNumber">SalesOrderNumber</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderStatus name="SalesOrderStatus">SalesOrderStatus</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderingCustomerAccountNumber name="OrderingCustomerAccountNumber">OrderingCustomerAccountNumber</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderingCustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceCustomerAccountNumber name="InvoiceCustomerAccountNumber">InvoiceCustomerAccountNumber</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceCustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDiscountCustomerGroupCode name="LineDiscountCustomerGroupCode">LineDiscountCustomerGroupCode</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDiscountCustomerGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountCode name="CashDiscountCode">CashDiscountCode</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentTermsBaseDate name="PaymentTermsBaseDate">PaymentTermsBaseDate</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentTermsBaseDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CommissionCustomerGroupId name="CommissionCustomerGroupId">CommissionCustomerGroupId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommissionCustomerGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPersonId name="ContactPersonId">ContactPersonId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

### <a href=#CustomersOrderReference name="CustomersOrderReference">CustomersOrderReference</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomersOrderReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLedgerDimension name="DefaultLedgerDimension">DefaultLedgerDimension</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderPromisingMethod name="SalesOrderPromisingMethod">SalesOrderPromisingMethod</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderPromisingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressName name="DeliveryAddressName">DeliveryAddressName</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DirectDebitMandate name="DirectDebitMandate">DirectDebitMandate</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirectDebitMandate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountPercentage name="TotalDiscountPercentage">TotalDiscountPercentage</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

### <a href=#DeliveryReasonCode name="DeliveryReasonCode">DeliveryReasonCode</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryTermsCode name="DeliveryTermsCode">DeliveryTermsCode</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

### <a href=#Email name="Email">Email</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Email attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountCustomerGroupCode name="TotalDiscountCustomerGroupCode">TotalDiscountCustomerGroupCode</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscountCustomerGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExportReason name="ExportReason">ExportReason</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExportReason attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedDueDate name="FixedDueDate">FixedDueDate</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedDueDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedExchangeRate name="FixedExchangeRate">FixedExchangeRate</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedExchangeRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoicePaymentAttachmentType name="InvoicePaymentAttachmentType">InvoicePaymentAttachmentType</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoicePaymentAttachmentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArePricesIncludingSalesTax name="ArePricesIncludingSalesTax">ArePricesIncludingSalesTax</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

### <a href=#DefaultShippingWarehouseId name="DefaultShippingWarehouseId">DefaultShippingWarehouseId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultShippingWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultShippingSiteId name="DefaultShippingSiteId">DefaultShippingSiteId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultShippingSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

### <a href=#EUSalesListCode name="EUSalesListCode">EUSalesListCode</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EUSalesListCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeCustomerGroupId name="ChargeCustomerGroupId">ChargeCustomerGroupId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeCustomerGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesAgreementNumber name="SalesAgreementNumber">SalesAgreementNumber</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesAgreementNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesProcessingStopped name="IsSalesProcessingStopped">IsSalesProcessingStopped</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesProcessingStopped attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MultilineDiscountCustomerGroupCode name="MultilineDiscountCustomerGroupCode">MultilineDiscountCustomerGroupCode</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MultilineDiscountCustomerGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceGroupId name="NumberSequenceGroupId">NumberSequenceGroupId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

### <a href=#IsOneTimeCustomer name="IsOneTimeCustomer">IsOneTimeCustomer</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOneTimeCustomer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentTermsName name="PaymentTermsName">PaymentTermsName</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

### <a href=#CustomerPaymentMethodName name="CustomerPaymentMethodName">CustomerPaymentMethodName</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerPaymentMethodName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerPaymentMethodSpecificationName name="CustomerPaymentMethodSpecificationName">CustomerPaymentMethodSpecificationName</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerPaymentMethodSpecificationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillAutomaticInventoryReservationConsiderBatchAttributes name="WillAutomaticInventoryReservationConsiderBatchAttributes">WillAutomaticInventoryReservationConsiderBatchAttributes</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillAutomaticInventoryReservationConsiderBatchAttributes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesRebateCustomerGroupId name="SalesRebateCustomerGroupId">SalesRebateCustomerGroupId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesRebateCustomerGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TMACustomerGroupId name="TMACustomerGroupId">TMACustomerGroupId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TMACustomerGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatPortId name="IntrastatPortId">IntrastatPortId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatPortId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerPostingProfileId name="CustomerPostingProfileId">CustomerPostingProfileId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerPostingProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceCustomerGroupCode name="PriceCustomerGroupCode">PriceCustomerGroupCode</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceCustomerGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerRequisitionNumber name="CustomerRequisitionNumber">CustomerRequisitionNumber</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerRequisitionNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationNumber name="QuotationNumber">QuotationNumber</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConfirmedReceiptDate name="ConfirmedReceiptDate">ConfirmedReceiptDate</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfirmedReceiptDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedReceiptDate name="RequestedReceiptDate">RequestedReceiptDate</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedReceiptDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryReservationMethod name="InventoryReservationMethod">InventoryReservationMethod</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryReservationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CommissionSalesRepresentativeGroupId name="CommissionSalesRepresentativeGroupId">CommissionSalesRepresentativeGroupId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommissionSalesRepresentativeGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderName name="SalesOrderName">SalesOrderName</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderOriginCode name="SalesOrderOriginCode">SalesOrderOriginCode</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderOriginCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderPoolId name="SalesOrderPoolId">SalesOrderPoolId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderPoolId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesUnitId name="SalesUnitId">SalesUnitId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesUnitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerTransactionSettlementType name="CustomerTransactionSettlementType">CustomerTransactionSettlementType</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerTransactionSettlementType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConfirmedShippingDate name="ConfirmedShippingDate">ConfirmedShippingDate</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfirmedShippingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedShippingDate name="RequestedShippingDate">RequestedShippingDate</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedShippingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaker name="SalesTaker">SalesTaker</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaker attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CampaignId name="CampaignId">CampaignId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CampaignId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatStatisticsProcedureCode name="IntrastatStatisticsProcedureCode">IntrastatStatisticsProcedureCode</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatStatisticsProcedureCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroupCode name="SalesTaxGroupCode">SalesTaxGroupCode</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatTransactionCode name="IntrastatTransactionCode">IntrastatTransactionCode</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatTransactionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatTransportModeCode name="IntrastatTransportModeCode">IntrastatTransportModeCode</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatTransportModeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#URL name="URL">URL</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the URL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxExemptNumber name="TaxExemptNumber">TaxExemptNumber</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

### <a href=#SalesResponsible name="SalesResponsible">SalesResponsible</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

### <a href=#DirectDebitMandateId name="DirectDebitMandateId">DirectDebitMandateId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirectDebitMandateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderResponsiblePersonnelNumber name="OrderResponsiblePersonnelNumber">OrderResponsiblePersonnelNumber</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderResponsiblePersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderTakerPersonnelNumber name="OrderTakerPersonnelNumber">OrderTakerPersonnelNumber</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderTakerPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLedgerDimensionDisplayValue name="DefaultLedgerDimensionDisplayValue">DefaultLedgerDimensionDisplayValue</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsEntryCertificateRequired name="IsEntryCertificateRequired">IsEntryCertificateRequired</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsEntryCertificateRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOwnEntryCertificateIssued name="IsOwnEntryCertificateIssued">IsOwnEntryCertificateIssued</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOwnEntryCertificateIssued attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceType name="InvoiceType">InvoiceType</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationBrokerId name="TransportationBrokerId">TransportationBrokerId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationBrokerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingCarrierId name="ShippingCarrierId">ShippingCarrierId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingCarrierId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingCarrierServiceGroupId name="ShippingCarrierServiceGroupId">ShippingCarrierServiceGroupId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingCarrierServiceGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingCarrierServiceId name="ShippingCarrierServiceId">ShippingCarrierServiceId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingCarrierServiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationModeId name="TransportationModeId">TransportationModeId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationModeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationRoutePlanId name="TransportationRoutePlanId">TransportationRoutePlanId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationRoutePlanId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationTemplateId name="TransportationTemplateId">TransportationTemplateId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryPostalAddressRecId name="DeliveryPostalAddressRecId">DeliveryPostalAddressRecId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

### <a href=#IsDeliveryAddressOrderSpecific name="IsDeliveryAddressOrderSpecific">IsDeliveryAddressOrderSpecific</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDeliveryAddressOrderSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormattedDelveryAddress name="FormattedDelveryAddress">FormattedDelveryAddress</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormattedDelveryAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryBuildingCompliment name="DeliveryBuildingCompliment">DeliveryBuildingCompliment</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryBuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCity name="DeliveryAddressCity">DeliveryAddressCity</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

### <a href=#DeliveryAddressCountryRegionId name="DeliveryAddressCountryRegionId">DeliveryAddressCountryRegionId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressDistrictName name="DeliveryAddressDistrictName">DeliveryAddressDistrictName</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

### <a href=#IsDeliveryAddressPrivate name="IsDeliveryAddressPrivate">IsDeliveryAddressPrivate</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDeliveryAddressPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressLatitude name="DeliveryAddressLatitude">DeliveryAddressLatitude</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

### <a href=#DeliveryAddressLocationId name="DeliveryAddressLocationId">DeliveryAddressLocationId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

### <a href=#DeliveryAddressLongitude name="DeliveryAddressLongitude">DeliveryAddressLongitude</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

### <a href=#DeliveryAddressStreetNumber name="DeliveryAddressStreetNumber">DeliveryAddressStreetNumber</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

### <a href=#DeliveryValidFrom name="DeliveryValidFrom">DeliveryValidFrom</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryValidTo name="DeliveryValidTo">DeliveryValidTo</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressTimeZone name="DeliveryAddressTimeZone">DeliveryAddressTimeZone</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

### <a href=#DeliveryAddressZipCode name="DeliveryAddressZipCode">DeliveryAddressZipCode</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

### <a href=#DeliveryAddressCityInKana name="DeliveryAddressCityInKana">DeliveryAddressCityInKana</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

### <a href=#DeliveryAddressStreetInKana name="DeliveryAddressStreetInKana">DeliveryAddressStreetInKana</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

### <a href=#IsConsolidatedInvoiceTarget name="IsConsolidatedInvoiceTarget">IsConsolidatedInvoiceTarget</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsConsolidatedInvoiceTarget attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EInvoiceDimensionAccountCode name="EInvoiceDimensionAccountCode">EInvoiceDimensionAccountCode</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EInvoiceDimensionAccountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsEInvoiceDimensionAccountCodeSpecifiedPerLine name="IsEInvoiceDimensionAccountCodeSpecifiedPerLine">IsEInvoiceDimensionAccountCodeSpecifiedPerLine</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsEInvoiceDimensionAccountCodeSpecifiedPerLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditNoteReasonCode name="CreditNoteReasonCode">CreditNoteReasonCode</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditNoteReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsExportSale name="IsExportSale">IsExportSale</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExportSale attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankConstantSymbol name="BankConstantSymbol">BankConstantSymbol</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankConstantSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankSpecificSymbol name="BankSpecificSymbol">BankSpecificSymbol</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankSpecificSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFPSCode name="CFPSCode">CFPSCode</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFPSCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFinalUser name="IsFinalUser">IsFinalUser</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFinalUser attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerPaymentFineCode name="CustomerPaymentFineCode">CustomerPaymentFineCode</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerPaymentFineCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentTypeRecId name="FiscalDocumentTypeRecId">FiscalDocumentTypeRecId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentTypeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerPaymentFinancialInterestCode name="CustomerPaymentFinancialInterestCode">CustomerPaymentFinancialInterestCode</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerPaymentFinancialInterestCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalOperationPresenceType name="FiscalOperationPresenceType">FiscalOperationPresenceType</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalOperationPresenceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPurchOperationTypeRecId name="SalesPurchOperationTypeRecId">SalesPurchOperationTypeRecId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPurchOperationTypeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsServiceDeliveryAddressBased name="IsServiceDeliveryAddressBased">IsServiceDeliveryAddressBased</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsServiceDeliveryAddressBased attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceFiscalInformationCode name="ServiceFiscalInformationCode">ServiceFiscalInformationCode</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceFiscalInformationCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentOperationTypeId name="FiscalDocumentOperationTypeId">FiscalDocumentOperationTypeId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentOperationTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentTypeId name="FiscalDocumentTypeId">FiscalDocumentTypeId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressStreet name="InvoiceAddressStreet">InvoiceAddressStreet</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormattedInvoiceAddress name="FormattedInvoiceAddress">FormattedInvoiceAddress</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormattedInvoiceAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceBuildingCompliment name="InvoiceBuildingCompliment">InvoiceBuildingCompliment</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceBuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressCity name="InvoiceAddressCity">InvoiceAddressCity</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressCountryRegionId name="InvoiceAddressCountryRegionId">InvoiceAddressCountryRegionId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressCountyId name="InvoiceAddressCountyId">InvoiceAddressCountyId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressCountyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressDistrictName name="InvoiceAddressDistrictName">InvoiceAddressDistrictName</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressDistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInvoiceAddressPrivate name="IsInvoiceAddressPrivate">IsInvoiceAddressPrivate</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInvoiceAddressPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressLatitude name="InvoiceAddressLatitude">InvoiceAddressLatitude</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressLatitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressLongitude name="InvoiceAddressLongitude">InvoiceAddressLongitude</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressLongitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressPostBox name="InvoiceAddressPostBox">InvoiceAddressPostBox</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressPostBox attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressStateId name="InvoiceAddressStateId">InvoiceAddressStateId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressStreetNumber name="InvoiceAddressStreetNumber">InvoiceAddressStreetNumber</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressStreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressTimeZone name="InvoiceAddressTimeZone">InvoiceAddressTimeZone</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressTimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressZipCode name="InvoiceAddressZipCode">InvoiceAddressZipCode</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressCityInKana name="InvoiceAddressCityInKana">InvoiceAddressCityInKana</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressCityInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressStreetInKana name="InvoiceAddressStreetInKana">InvoiceAddressStreetInKana</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressStreetInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderTotalAmount name="OrderTotalAmount">OrderTotalAmount</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderTotalAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderTotalChargesAmount name="OrderTotalChargesAmount">OrderTotalChargesAmount</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderTotalChargesAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderTotalDiscountAmount name="OrderTotalDiscountAmount">OrderTotalDiscountAmount</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderTotalDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderTotalTaxAmount name="OrderTotalTaxAmount">OrderTotalTaxAmount</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderTotalTaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderHeaderTaxAmount name="OrderHeaderTaxAmount">OrderHeaderTaxAmount</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderHeaderTaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountAmount name="TotalDiscountAmount">TotalDiscountAmount</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

### <a href=#SalesOrderProcessingStatus name="SalesOrderProcessingStatus">SalesOrderProcessingStatus</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderProcessingStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreTotalsCalculated name="AreTotalsCalculated">AreTotalsCalculated</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreTotalsCalculated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationDocumentLineId name="TransportationDocumentLineId">TransportationDocumentLineId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationDocumentLineId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceValidTo name="InvoiceValidTo">InvoiceValidTo</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceValidFrom name="InvoiceValidFrom">InvoiceValidFrom</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderCreationDateTime name="OrderCreationDateTime">OrderCreationDateTime</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderCreationDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressCountryRegionISOCode name="InvoiceAddressCountryRegionISOCode">InvoiceAddressCountryRegionISOCode</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressCountryRegionISOCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectId name="ProjectId">ProjectId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SkipCreateAutoCharges name="SkipCreateAutoCharges">SkipCreateAutoCharges</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SkipCreateAutoCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BaseDocumentDate name="BaseDocumentDate">BaseDocumentDate</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BaseDocumentDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CIPEcode name="CIPEcode">CIPEcode</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CIPEcode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BaseDocumentNumber name="BaseDocumentNumber">BaseDocumentNumber</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BaseDocumentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BaseDocumentType name="BaseDocumentType">BaseDocumentType</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BaseDocumentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BaseDocumentItemNumber name="BaseDocumentItemNumber">BaseDocumentItemNumber</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BaseDocumentItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BaseDocumentLineNumber name="BaseDocumentLineNumber">BaseDocumentLineNumber</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BaseDocumentLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderOrAgreementCode name="OrderOrAgreementCode">OrderOrAgreementCode</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderOrAgreementCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TenderCode name="TenderCode">TenderCode</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TenderCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportingCurrencyFixedExchangeRate name="ReportingCurrencyFixedExchangeRate">ReportingCurrencyFixedExchangeRate</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCurrencyFixedExchangeRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingCarrierCustomerAccountNumber name="ShippingCarrierCustomerAccountNumber">ShippingCarrierCustomerAccountNumber</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingCarrierCustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevRecFollowOriginalPricingMethod name="RevRecFollowOriginalPricingMethod">RevRecFollowOriginalPricingMethod</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecFollowOriginalPricingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevRecContractEndDate name="RevRecContractEndDate">RevRecContractEndDate</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecContractEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevRecContractStartDate name="RevRecContractStartDate">RevRecContractStartDate</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecContractStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevRecLatestReverseJournal name="RevRecLatestReverseJournal">RevRecLatestReverseJournal</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecLatestReverseJournal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevRecMultipleSOReallocation name="RevRecMultipleSOReallocation">RevRecMultipleSOReallocation</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecMultipleSOReallocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RevRecReallocationId name="RevRecReallocationId">RevRecReallocationId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevRecReallocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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

### <a href=#Relationship_SalesOrderOriginRelationshipId name="Relationship_SalesOrderOriginRelationshipId">Relationship_SalesOrderOriginRelationshipId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesOrderOriginRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProjectRelationshipId name="Relationship_ProjectRelationshipId">Relationship_ProjectRelationshipId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjectRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_SalesTableRelationshipId name="BackingTable_SalesTableRelationshipId">BackingTable_SalesTableRelationshipId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_SalesTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/SalesTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/SalesTable.cdm.json/SalesTable</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/SalesTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/SalesOrderHeaderV2Entity (this entity)  

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
