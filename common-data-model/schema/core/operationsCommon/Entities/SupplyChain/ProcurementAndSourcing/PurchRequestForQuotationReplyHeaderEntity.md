---
title: PurchRequestForQuotationReplyHeaderEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# Request for quotation reply headers in ProcurementAndSourcing(PurchRequestForQuotationReplyHeaderEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Request for quotation reply headers</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ResultingPurchaseAgreementId](#ResultingPurchaseAgreementId)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[RFQBidType](#RFQBidType)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[VendorCashDiscountCode](#VendorCashDiscountCode)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[ContactPersonId](#ContactPersonId)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[RequestedDeliveryDate](#RequestedDeliveryDate)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[DeliveryAddressName](#DeliveryAddressName)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[TotalDiscountPercentage](#TotalDiscountPercentage)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[DeliveryModeCode](#DeliveryModeCode)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[DeliveryTermsCode](#DeliveryTermsCode)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[VendorEmailAddress](#VendorEmailAddress)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[TotalDiscountVendorGroupCode](#TotalDiscountVendorGroupCode)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[RFQExpirationDateTime](#RFQExpirationDateTime)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[ArePricesIncludingSalesTax](#ArePricesIncludingSalesTax)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[ReceivingWarehouseId](#ReceivingWarehouseId)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[ReceivingSiteId](#ReceivingSiteId)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[BuyerGroupId](#BuyerGroupId)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[LanguageId](#LanguageId)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[LineDiscountVendorGroupCode](#LineDiscountVendorGroupCode)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[ChargeVendorGroupId](#ChargeVendorGroupId)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[MultiLineDiscountVendorGroupCode](#MultiLineDiscountVendorGroupCode)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[RFQCaseTitle](#RFQCaseTitle)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[NumberSequenceGroupId](#NumberSequenceGroupId)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[PaymentTermsName](#PaymentTermsName)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[PaymentScheduleName](#PaymentScheduleName)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[VendorPaymentMethodName](#VendorPaymentMethodName)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[VendorPaymentMethodSpecificationName](#VendorPaymentMethodSpecificationName)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[ContactPhoneNumber](#ContactPhoneNumber)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[PriceVendorGroupCode](#PriceVendorGroupCode)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[ProjectId](#ProjectId)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[ResultingPurchaseOrderNumber](#ResultingPurchaseOrderNumber)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[OrderingWorkeId](#OrderingWorkeId)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[RequestingWorkerId](#RequestingWorkerId)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[RFQCaseNumber](#RFQCaseNumber)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[RFQNumber](#RFQNumber)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[RFQName](#RFQName)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[RFQType](#RFQType)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[RFQReplyURLAddress](#RFQReplyURLAddress)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[HighestRFQStatus](#HighestRFQStatus)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[LowestRFQStatus](#LowestRFQStatus)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[SalesTaxGroupCode](#SalesTaxGroupCode)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[ResultingPurchaseAgreementExpirationDate](#ResultingPurchaseAgreementExpirationDate)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[ResultingPurchaseAgreementEffectiveDate](#ResultingPurchaseAgreementEffectiveDate)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[TaxExemptNumber](#TaxExemptNumber)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[VendorAccountNumber](#VendorAccountNumber)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[VendorReplySubmissionDateTime](#VendorReplySubmissionDateTime)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[ReplySubmittedBy](#ReplySubmittedBy)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[RequestingDepartmentName](#RequestingDepartmentName)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[IsRFQBidInProgress](#IsRFQBidInProgress)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[OrderingWorkerPersonnelNumber](#OrderingWorkerPersonnelNumber)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[RequestingWorkerPersonnelNumber](#RequestingWorkerPersonnelNumber)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[BidSubmittingPersonPartyNumber](#BidSubmittingPersonPartyNumber)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[VendorReasonCode](#VendorReasonCode)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[VendorReasonComment](#VendorReasonComment)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[RFQSolicitationTypeName](#RFQSolicitationTypeName)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[AccountingDistributionTemplateId](#AccountingDistributionTemplateId)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[AccountingDistributionLegalEntityId](#AccountingDistributionLegalEntityId)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[AccountingDistributionTemplateLegalEntityPartyNumber](#AccountingDistributionTemplateLegalEntityPartyNumber)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[IsRFQAccepted](#IsRFQAccepted)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[IsRFQSealed](#IsRFQSealed)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[VendorOrderReference](#VendorOrderReference)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[TotalRFQScore](#TotalRFQScore)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[RFQScoreRank](#RFQScoreRank)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[DeliveryAddressLocationId](#DeliveryAddressLocationId)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[FormattedDeliveryAddress](#FormattedDeliveryAddress)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[DeliveryAddressZipCode](#DeliveryAddressZipCode)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[DeliveryAddressBuildingCompliment](#DeliveryAddressBuildingCompliment)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[DeliveryAddressCity](#DeliveryAddressCity)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[DeliveryAddressCityInKana](#DeliveryAddressCityInKana)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[DeliveryAddressCountryRegionId](#DeliveryAddressCountryRegionId)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[DeliveryAddressCountryRegionISOCode](#DeliveryAddressCountryRegionISOCode)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[DeliveryAddressCountyId](#DeliveryAddressCountyId)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[DeliveryAddressDescription](#DeliveryAddressDescription)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[DeliveryAddressDistrictName](#DeliveryAddressDistrictName)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[DeliveryAddressDunsNumber](#DeliveryAddressDunsNumber)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[DeliveryAddressLatitude](#DeliveryAddressLatitude)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[IsDeliveryAddressPrivate](#IsDeliveryAddressPrivate)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[DeliveryAddressLongitude](#DeliveryAddressLongitude)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[DeliveryAddressPostBox](#DeliveryAddressPostBox)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[DeliveryAddressStateId](#DeliveryAddressStateId)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[DeliveryAddressStreet](#DeliveryAddressStreet)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[DeliveryAddressStreetInKana](#DeliveryAddressStreetInKana)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[DeliveryAddressStreetNumber](#DeliveryAddressStreetNumber)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[DeliveryAddressValidFrom](#DeliveryAddressValidFrom)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[DeliveryAddressValidTo](#DeliveryAddressValidTo)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[DeliveryAddressTimeZone](#DeliveryAddressTimeZone)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[DefaultDimension](#DefaultDimension)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[IsDeliveryAddressOrderSpecific](#IsDeliveryAddressOrderSpecific)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[BackingTable_PurchRFQTableRelationshipId](#BackingTable_PurchRFQTableRelationshipId)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PurchRequestForQuotationReplyHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity</a>|

### <a href=#ResultingPurchaseAgreementId name="ResultingPurchaseAgreementId">ResultingPurchaseAgreementId</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResultingPurchaseAgreementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQBidType name="RFQBidType">RFQBidType</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQBidType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorCashDiscountCode name="VendorCashDiscountCode">VendorCashDiscountCode</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorCashDiscountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPersonId name="ContactPersonId">ContactPersonId</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

### <a href=#DeliveryTermsCode name="DeliveryTermsCode">DeliveryTermsCode</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

### <a href=#VendorEmailAddress name="VendorEmailAddress">VendorEmailAddress</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorEmailAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountVendorGroupCode name="TotalDiscountVendorGroupCode">TotalDiscountVendorGroupCode</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

### <a href=#RFQExpirationDateTime name="RFQExpirationDateTime">RFQExpirationDateTime</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQExpirationDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArePricesIncludingSalesTax name="ArePricesIncludingSalesTax">ArePricesIncludingSalesTax</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

### <a href=#ReceivingWarehouseId name="ReceivingWarehouseId">ReceivingWarehouseId</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingSiteId name="ReceivingSiteId">ReceivingSiteId</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BuyerGroupId name="BuyerGroupId">BuyerGroupId</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

### <a href=#LineDiscountVendorGroupCode name="LineDiscountVendorGroupCode">LineDiscountVendorGroupCode</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

### <a href=#ChargeVendorGroupId name="ChargeVendorGroupId">ChargeVendorGroupId</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

### <a href=#MultiLineDiscountVendorGroupCode name="MultiLineDiscountVendorGroupCode">MultiLineDiscountVendorGroupCode</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MultiLineDiscountVendorGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQCaseTitle name="RFQCaseTitle">RFQCaseTitle</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQCaseTitle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceGroupId name="NumberSequenceGroupId">NumberSequenceGroupId</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

### <a href=#ContactPhoneNumber name="ContactPhoneNumber">ContactPhoneNumber</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPhoneNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceVendorGroupCode name="PriceVendorGroupCode">PriceVendorGroupCode</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

### <a href=#ProjectId name="ProjectId">ProjectId</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

### <a href=#ResultingPurchaseOrderNumber name="ResultingPurchaseOrderNumber">ResultingPurchaseOrderNumber</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResultingPurchaseOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderingWorkeId name="OrderingWorkeId">OrderingWorkeId</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderingWorkeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestingWorkerId name="RequestingWorkerId">RequestingWorkerId</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestingWorkerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQCaseNumber name="RFQCaseNumber">RFQCaseNumber</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQCaseNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQNumber name="RFQNumber">RFQNumber</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>RFQ name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>RFQ name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQType name="RFQType">RFQType</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQReplyURLAddress name="RFQReplyURLAddress">RFQReplyURLAddress</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQReplyURLAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HighestRFQStatus name="HighestRFQStatus">HighestRFQStatus</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HighestRFQStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LowestRFQStatus name="LowestRFQStatus">LowestRFQStatus</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LowestRFQStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroupCode name="SalesTaxGroupCode">SalesTaxGroupCode</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

### <a href=#ResultingPurchaseAgreementExpirationDate name="ResultingPurchaseAgreementExpirationDate">ResultingPurchaseAgreementExpirationDate</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resulting purchase agreement expiration date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResultingPurchaseAgreementExpirationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Resulting purchase agreement expiration date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResultingPurchaseAgreementEffectiveDate name="ResultingPurchaseAgreementEffectiveDate">ResultingPurchaseAgreementEffectiveDate</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resulting purchase agreement effective date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResultingPurchaseAgreementEffectiveDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Resulting purchase agreement effective date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxExemptNumber name="TaxExemptNumber">TaxExemptNumber</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

### <a href=#VendorAccountNumber name="VendorAccountNumber">VendorAccountNumber</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorReplySubmissionDateTime name="VendorReplySubmissionDateTime">VendorReplySubmissionDateTime</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorReplySubmissionDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplySubmittedBy name="ReplySubmittedBy">ReplySubmittedBy</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplySubmittedBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestingDepartmentName name="RequestingDepartmentName">RequestingDepartmentName</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestingDepartmentName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRFQBidInProgress name="IsRFQBidInProgress">IsRFQBidInProgress</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ bid in progress</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRFQBidInProgress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ bid in progress</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderingWorkerPersonnelNumber name="OrderingWorkerPersonnelNumber">OrderingWorkerPersonnelNumber</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ordering worker personnel number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderingWorkerPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ordering worker personnel number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestingWorkerPersonnelNumber name="RequestingWorkerPersonnelNumber">RequestingWorkerPersonnelNumber</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requesting worker personnel number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestingWorkerPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Requesting worker personnel number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BidSubmittingPersonPartyNumber name="BidSubmittingPersonPartyNumber">BidSubmittingPersonPartyNumber</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bid submitting person party number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BidSubmittingPersonPartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bid submitting person party number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionDisplayValue name="DefaultDimensionDisplayValue">DefaultDimensionDisplayValue</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorReasonCode name="VendorReasonCode">VendorReasonCode</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorReasonComment name="VendorReasonComment">VendorReasonComment</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorReasonComment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQSolicitationTypeName name="RFQSolicitationTypeName">RFQSolicitationTypeName</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Solicitation type name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQSolicitationTypeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Solicitation type name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountingDistributionTemplateId name="AccountingDistributionTemplateId">AccountingDistributionTemplateId</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accounting distribution template name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDistributionTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Accounting distribution template name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountingDistributionLegalEntityId name="AccountingDistributionLegalEntityId">AccountingDistributionLegalEntityId</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accounting distribution template legal entity Id</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDistributionLegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Accounting distribution template legal entity Id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountingDistributionTemplateLegalEntityPartyNumber name="AccountingDistributionTemplateLegalEntityPartyNumber">AccountingDistributionTemplateLegalEntityPartyNumber</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accounting distribution template legal entity party number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDistributionTemplateLegalEntityPartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Accounting distribution template legal entity party number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRFQAccepted name="IsRFQAccepted">IsRFQAccepted</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is RFQ accepted</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRFQAccepted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is RFQ accepted</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRFQSealed name="IsRFQSealed">IsRFQSealed</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRFQSealed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorOrderReference name="VendorOrderReference">VendorOrderReference</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

### <a href=#TotalRFQScore name="TotalRFQScore">TotalRFQScore</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalRFQScore attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQScoreRank name="RFQScoreRank">RFQScoreRank</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>RFQ score rank</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQScoreRank attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>RFQ score rank</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressLocationId name="DeliveryAddressLocationId">DeliveryAddressLocationId</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

### <a href=#DeliveryAddressZipCode name="DeliveryAddressZipCode">DeliveryAddressZipCode</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

### <a href=#DeliveryAddressBuildingCompliment name="DeliveryAddressBuildingCompliment">DeliveryAddressBuildingCompliment</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDeliveryAddressOrderSpecific name="IsDeliveryAddressOrderSpecific">IsDeliveryAddressOrderSpecific</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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

### <a href=#BackingTable_PurchRFQTableRelationshipId name="BackingTable_PurchRFQTableRelationshipId">BackingTable_PurchRFQTableRelationshipId</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PurchRFQTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchRFQTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchRFQTable.cdm.json/PurchRFQTable</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchRFQTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyHeaderEntity (this entity)  

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
