---
title: PurchPurchaseOrderConfirmationHeaderEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Purchase order confirmation headers in ProcurementAndSourcing(PurchPurchaseOrderConfirmationHeaderEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase order confirmation headers</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[PurchaseOrderStatus](#PurchaseOrderStatus)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[BankDocumentType](#BankDocumentType)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[CashDiscountPercentage](#CashDiscountPercentage)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[OrderVendorAccountNumber](#OrderVendorAccountNumber)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[LineDiscountVendorGroupCode](#LineDiscountVendorGroupCode)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[AccountingDate](#AccountingDate)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[AccountingDistributionTemplateName](#AccountingDistributionTemplateName)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[CashDiscountCode](#CashDiscountCode)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[ContactPersonId](#ContactPersonId)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[RequestedDeliveryDate](#RequestedDeliveryDate)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DeliveryAddressName](#DeliveryAddressName)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[TotalDiscountPercentage](#TotalDiscountPercentage)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DeliveryModeId](#DeliveryModeId)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DeliveryTermsId](#DeliveryTermsId)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[EmailAddress](#EmailAddress)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[TotalDiscountVendorGroupCode](#TotalDiscountVendorGroupCode)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[FixedDueDate](#FixedDueDate)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[ArePricesIncludingSalesTax](#ArePricesIncludingSalesTax)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DefaultReceivingWarehouseId](#DefaultReceivingWarehouseId)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DefaultReceivingSiteId](#DefaultReceivingSiteId)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[InvoiceVendorAccountNumber](#InvoiceVendorAccountNumber)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[BuyerGroupId](#BuyerGroupId)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[LanguageId](#LanguageId)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[ChargeVendorGroupId](#ChargeVendorGroupId)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[MultilineDiscountVendorGroupCode](#MultilineDiscountVendorGroupCode)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[NumberSequenceGroupId](#NumberSequenceGroupId)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[IsOneTimeVendor](#IsOneTimeVendor)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[PaymentTermsName](#PaymentTermsName)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[PaymentScheduleName](#PaymentScheduleName)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[VendorPaymentMethodName](#VendorPaymentMethodName)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[VendorPaymentMethodSpecificationName](#VendorPaymentMethodSpecificationName)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[VendorPostingProfileId](#VendorPostingProfileId)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[PriceVendorGroupCode](#PriceVendorGroupCode)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[PurchaseOrderNumber](#PurchaseOrderNumber)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[PurchaseOrderName](#PurchaseOrderName)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[PurchaseOrderPoolId](#PurchaseOrderPoolId)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[AttentionInformation](#AttentionInformation)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[VendorTransactionSettlementType](#VendorTransactionSettlementType)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[SalesTaxGroupCode](#SalesTaxGroupCode)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[EUSalesListCode](#EUSalesListCode)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[IntrastatStatisticsProcedureCode](#IntrastatStatisticsProcedureCode)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[IntrastatPortId](#IntrastatPortId)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[IntrastatTransactionCode](#IntrastatTransactionCode)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[IntrastatTransportModeCode](#IntrastatTransportModeCode)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[URL](#URL)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[TaxExemptNumber](#TaxExemptNumber)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[VendorOrderReference](#VendorOrderReference)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[ConfirmingPurchaseOrderCode](#ConfirmingPurchaseOrderCode)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[ConfirmingPurchaseOrderCodeLanguageId](#ConfirmingPurchaseOrderCodeLanguageId)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[VendorInvoiceDeclarationId](#VendorInvoiceDeclarationId)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DefaultLedgerDimensionDisplayValue](#DefaultLedgerDimensionDisplayValue)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[ReasonCode](#ReasonCode)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[ReasonComment](#ReasonComment)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DeliveryAddressLocationId](#DeliveryAddressLocationId)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[FormattedDeliveryAddress](#FormattedDeliveryAddress)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DeliveryAddressBuildingCompliment](#DeliveryAddressBuildingCompliment)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DeliveryAddressCity](#DeliveryAddressCity)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DeliveryAddressCityInKana](#DeliveryAddressCityInKana)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DeliveryAddressCountryRegionId](#DeliveryAddressCountryRegionId)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DeliveryAddressCountryRegionISOCode](#DeliveryAddressCountryRegionISOCode)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DeliveryAddressCountyId](#DeliveryAddressCountyId)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DeliveryAddressDescription](#DeliveryAddressDescription)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DeliveryAddressDistrictName](#DeliveryAddressDistrictName)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DeliveryAddressDunsNumber](#DeliveryAddressDunsNumber)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DeliveryAddressLatitude](#DeliveryAddressLatitude)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[IsDeliveryAddressPrivate](#IsDeliveryAddressPrivate)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DeliveryAddressLongitude](#DeliveryAddressLongitude)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DeliveryAddressPostBox](#DeliveryAddressPostBox)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DeliveryAddressStateId](#DeliveryAddressStateId)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DeliveryAddressStreet](#DeliveryAddressStreet)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DeliveryAddressStreetInKana](#DeliveryAddressStreetInKana)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DeliveryAddressStreetNumber](#DeliveryAddressStreetNumber)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DeliveryAddressValidFrom](#DeliveryAddressValidFrom)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DeliveryAddressValidTo](#DeliveryAddressValidTo)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DeliveryAddressTimeZone](#DeliveryAddressTimeZone)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DeliveryAddressZipCode](#DeliveryAddressZipCode)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[OrdererPersonnelNumber](#OrdererPersonnelNumber)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[RequesterPersonnelNumber](#RequesterPersonnelNumber)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[ProjectId](#ProjectId)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[PurchaseOrderHeaderCreationMethod](#PurchaseOrderHeaderCreationMethod)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[TransportationDocumentLineId](#TransportationDocumentLineId)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[DocumentApprovalStatus](#DocumentApprovalStatus)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[TotalConfirmedAmount](#TotalConfirmedAmount)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[PrepaymentAmount](#PrepaymentAmount)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[TotalDiscountAmount](#TotalDiscountAmount)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[FixedExchangeRate](#FixedExchangeRate)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[FixedSecondaryExchangeRate](#FixedSecondaryExchangeRate)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[IsPrepayment](#IsPrepayment)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[ConfirmationNumber](#ConfirmationNumber)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[ConfirmationVoucherNumber](#ConfirmationVoucherNumber)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[ConfirmationDate](#ConfirmationDate)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[PurchaseOrderDocumentReference](#PurchaseOrderDocumentReference)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[TotalQuantity](#TotalQuantity)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[TotalRoundOffAmount](#TotalRoundOffAmount)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[SubTotalAmount](#SubTotalAmount)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[TotalLineDiscountAmount](#TotalLineDiscountAmount)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[TotalChargeAmount](#TotalChargeAmount)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[TotalTaxAmount](#TotalTaxAmount)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[TotalNetVolume](#TotalNetVolume)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[TotalNetWeight](#TotalNetWeight)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[Relationship_ProjectRelationshipId](#Relationship_ProjectRelationshipId)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[Relationship_OrderVendorRelationshipId](#Relationship_OrderVendorRelationshipId)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[Relationship_InvoiceVendorRelationshipId](#Relationship_InvoiceVendorRelationshipId)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[BackingTable_VendPurchOrderJourRelationshipId](#BackingTable_VendPurchOrderJourRelationshipId)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PurchPurchaseOrderConfirmationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity</a>|

### <a href=#PurchaseOrderStatus name="PurchaseOrderStatus">PurchaseOrderStatus</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankDocumentType name="BankDocumentType">BankDocumentType</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#CashDiscountPercentage name="CashDiscountPercentage">CashDiscountPercentage</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#OrderVendorAccountNumber name="OrderVendorAccountNumber">OrderVendorAccountNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderVendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDiscountVendorGroupCode name="LineDiscountVendorGroupCode">LineDiscountVendorGroupCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDiscountVendorGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountingDate name="AccountingDate">AccountingDate</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountingDistributionTemplateName name="AccountingDistributionTemplateName">AccountingDistributionTemplateName</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDistributionTemplateName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountCode name="CashDiscountCode">CashDiscountCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#RequestedDeliveryDate name="RequestedDeliveryDate">RequestedDeliveryDate</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedDeliveryDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressName name="DeliveryAddressName">DeliveryAddressName</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#DeliveryModeId name="DeliveryModeId">DeliveryModeId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryModeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryTermsId name="DeliveryTermsId">DeliveryTermsId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryTermsId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmailAddress name="EmailAddress">EmailAddress</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmailAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountVendorGroupCode name="TotalDiscountVendorGroupCode">TotalDiscountVendorGroupCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscountVendorGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedDueDate name="FixedDueDate">FixedDueDate</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#ArePricesIncludingSalesTax name="ArePricesIncludingSalesTax">ArePricesIncludingSalesTax</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#DefaultReceivingWarehouseId name="DefaultReceivingWarehouseId">DefaultReceivingWarehouseId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultReceivingWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultReceivingSiteId name="DefaultReceivingSiteId">DefaultReceivingSiteId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultReceivingSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceVendorAccountNumber name="InvoiceVendorAccountNumber">InvoiceVendorAccountNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceVendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BuyerGroupId name="BuyerGroupId">BuyerGroupId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BuyerGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#ChargeVendorGroupId name="ChargeVendorGroupId">ChargeVendorGroupId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeVendorGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MultilineDiscountVendorGroupCode name="MultilineDiscountVendorGroupCode">MultilineDiscountVendorGroupCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MultilineDiscountVendorGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceGroupId name="NumberSequenceGroupId">NumberSequenceGroupId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#IsOneTimeVendor name="IsOneTimeVendor">IsOneTimeVendor</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOneTimeVendor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentTermsName name="PaymentTermsName">PaymentTermsName</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#PaymentScheduleName name="PaymentScheduleName">PaymentScheduleName</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentScheduleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorPaymentMethodName name="VendorPaymentMethodName">VendorPaymentMethodName</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorPaymentMethodName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorPaymentMethodSpecificationName name="VendorPaymentMethodSpecificationName">VendorPaymentMethodSpecificationName</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorPaymentMethodSpecificationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorPostingProfileId name="VendorPostingProfileId">VendorPostingProfileId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorPostingProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceVendorGroupCode name="PriceVendorGroupCode">PriceVendorGroupCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceVendorGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrderNumber name="PurchaseOrderNumber">PurchaseOrderNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrderName name="PurchaseOrderName">PurchaseOrderName</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrderPoolId name="PurchaseOrderPoolId">PurchaseOrderPoolId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderPoolId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AttentionInformation name="AttentionInformation">AttentionInformation</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttentionInformation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorTransactionSettlementType name="VendorTransactionSettlementType">VendorTransactionSettlementType</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorTransactionSettlementType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroupCode name="SalesTaxGroupCode">SalesTaxGroupCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#EUSalesListCode name="EUSalesListCode">EUSalesListCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#IntrastatStatisticsProcedureCode name="IntrastatStatisticsProcedureCode">IntrastatStatisticsProcedureCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#IntrastatPortId name="IntrastatPortId">IntrastatPortId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#IntrastatTransactionCode name="IntrastatTransactionCode">IntrastatTransactionCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#VendorOrderReference name="VendorOrderReference">VendorOrderReference</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorOrderReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConfirmingPurchaseOrderCode name="ConfirmingPurchaseOrderCode">ConfirmingPurchaseOrderCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Confirming PO</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfirmingPurchaseOrderCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Confirming PO</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConfirmingPurchaseOrderCodeLanguageId name="ConfirmingPurchaseOrderCodeLanguageId">ConfirmingPurchaseOrderCodeLanguageId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Confirming PO language</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfirmingPurchaseOrderCodeLanguageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Confirming PO language</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorInvoiceDeclarationId name="VendorInvoiceDeclarationId">VendorInvoiceDeclarationId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice declaration</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorInvoiceDeclarationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoice declaration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLedgerDimensionDisplayValue name="DefaultLedgerDimensionDisplayValue">DefaultLedgerDimensionDisplayValue</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Financial dimensions</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Financial dimensions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReasonCode name="ReasonCode">ReasonCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReasonComment name="ReasonComment">ReasonComment</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReasonComment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressLocationId name="DeliveryAddressLocationId">DeliveryAddressLocationId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#FormattedDeliveryAddress name="FormattedDeliveryAddress">FormattedDeliveryAddress</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#DeliveryAddressBuildingCompliment name="DeliveryAddressBuildingCompliment">DeliveryAddressBuildingCompliment</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressBuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCity name="DeliveryAddressCity">DeliveryAddressCity</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#DeliveryAddressCityInKana name="DeliveryAddressCityInKana">DeliveryAddressCityInKana</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#DeliveryAddressCountryRegionId name="DeliveryAddressCountryRegionId">DeliveryAddressCountryRegionId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery address description </td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delivery address description </td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressDistrictName name="DeliveryAddressDistrictName">DeliveryAddressDistrictName</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#DeliveryAddressLatitude name="DeliveryAddressLatitude">DeliveryAddressLatitude</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#IsDeliveryAddressPrivate name="IsDeliveryAddressPrivate">IsDeliveryAddressPrivate</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#DeliveryAddressLongitude name="DeliveryAddressLongitude">DeliveryAddressLongitude</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#DeliveryAddressStreetInKana name="DeliveryAddressStreetInKana">DeliveryAddressStreetInKana</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#DeliveryAddressStreetNumber name="DeliveryAddressStreetNumber">DeliveryAddressStreetNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#DeliveryAddressValidFrom name="DeliveryAddressValidFrom">DeliveryAddressValidFrom</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressValidTo name="DeliveryAddressValidTo">DeliveryAddressValidTo</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressTimeZone name="DeliveryAddressTimeZone">DeliveryAddressTimeZone</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#OrdererPersonnelNumber name="OrdererPersonnelNumber">OrdererPersonnelNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Orderer</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrdererPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Orderer</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequesterPersonnelNumber name="RequesterPersonnelNumber">RequesterPersonnelNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requester</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequesterPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Requester</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectId name="ProjectId">ProjectId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrderHeaderCreationMethod name="PurchaseOrderHeaderCreationMethod">PurchaseOrderHeaderCreationMethod</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderHeaderCreationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationDocumentLineId name="TransportationDocumentLineId">TransportationDocumentLineId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationDocumentLineId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentApprovalStatus name="DocumentApprovalStatus">DocumentApprovalStatus</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentApprovalStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalConfirmedAmount name="TotalConfirmedAmount">TotalConfirmedAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total amount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalConfirmedAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrepaymentAmount name="PrepaymentAmount">PrepaymentAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Prepayment amount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrepaymentAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Prepayment amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountAmount name="TotalDiscountAmount">TotalDiscountAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#FixedExchangeRate name="FixedExchangeRate">FixedExchangeRate</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#FixedSecondaryExchangeRate name="FixedSecondaryExchangeRate">FixedSecondaryExchangeRate</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedSecondaryExchangeRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrepayment name="IsPrepayment">IsPrepayment</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrepayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConfirmationNumber name="ConfirmationNumber">ConfirmationNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfirmationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConfirmationVoucherNumber name="ConfirmationVoucherNumber">ConfirmationVoucherNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfirmationVoucherNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConfirmationDate name="ConfirmationDate">ConfirmationDate</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Confirmation date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfirmationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Confirmation date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrderDocumentReference name="PurchaseOrderDocumentReference">PurchaseOrderDocumentReference</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderDocumentReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalQuantity name="TotalQuantity">TotalQuantity</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total purchase quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total purchase quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalRoundOffAmount name="TotalRoundOffAmount">TotalRoundOffAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalRoundOffAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubTotalAmount name="SubTotalAmount">SubTotalAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subtotal amount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubTotalAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Subtotal amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalLineDiscountAmount name="TotalLineDiscountAmount">TotalLineDiscountAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalLineDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalChargeAmount name="TotalChargeAmount">TotalChargeAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalChargeAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalTaxAmount name="TotalTaxAmount">TotalTaxAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalTaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalNetVolume name="TotalNetVolume">TotalNetVolume</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalNetVolume attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalNetWeight name="TotalNetWeight">TotalNetWeight</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalNetWeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjectRelationshipId name="Relationship_ProjectRelationshipId">Relationship_ProjectRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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

### <a href=#Relationship_OrderVendorRelationshipId name="Relationship_OrderVendorRelationshipId">Relationship_OrderVendorRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InvoiceVendorRelationshipId name="Relationship_InvoiceVendorRelationshipId">Relationship_InvoiceVendorRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_VendPurchOrderJourRelationshipId name="BackingTable_VendPurchOrderJourRelationshipId">BackingTable_VendPurchOrderJourRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_VendPurchOrderJourRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Transaction/VendPurchOrderJour.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Transaction/VendPurchOrderJour.cdm.json/VendPurchOrderJour</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Transaction/VendPurchOrderJour.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderConfirmationHeaderEntity (this entity)  

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
