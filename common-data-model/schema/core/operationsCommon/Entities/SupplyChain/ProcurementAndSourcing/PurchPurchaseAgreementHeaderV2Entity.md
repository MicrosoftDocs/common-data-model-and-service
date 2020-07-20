---
title: PurchPurchaseAgreementHeaderV2Entity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Purchase agreements V2 in ProcurementAndSourcing(PurchPurchaseAgreementHeaderV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase agreements V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[BuyingLegalEntityRecId](#BuyingLegalEntityRecId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[BuyingLegalEntityId](#BuyingLegalEntityId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[PurchaseAgreementId](#PurchaseAgreementId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[AgreementVendorAccountNumber](#AgreementVendorAccountNumber)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[VendorReference](#VendorReference)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[PurchaseAgreementClassificationRecId](#PurchaseAgreementClassificationRecId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[PurchaseAgreementClassificationName](#PurchaseAgreementClassificationName)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[AgreementStatus](#AgreementStatus)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DefaultEffectiveDate](#DefaultEffectiveDate)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DefaultExpirationDate](#DefaultExpirationDate)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DefaultCommitmentType](#DefaultCommitmentType)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DefaultLedgerDimension](#DefaultLedgerDimension)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DefaultLedgerDimensionDisplayValue](#DefaultLedgerDimensionDisplayValue)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[ExternalDocumentReference](#ExternalDocumentReference)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DocumentTitle](#DocumentTitle)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[LanguageId](#LanguageId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[PreparerRecId](#PreparerRecId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[PreparerPersonPartyNumber](#PreparerPersonPartyNumber)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[IsInterestBasedOnCentralEuropeanBank](#IsInterestBasedOnCentralEuropeanBank)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[MaximumContractAmount](#MaximumContractAmount)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[MinimumContractAmount](#MinimumContractAmount)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[ProcurementClassification](#ProcurementClassification)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[PurchasingProcedureType](#PurchasingProcedureType)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[PurchasingPurpose](#PurchasingPurpose)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[IsAgreementRenewable](#IsAgreementRenewable)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[AgreementWorkflowStatus](#AgreementWorkflowStatus)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[BuyerGroupId](#BuyerGroupId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[VendorPaymentMethodName](#VendorPaymentMethodName)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[VendorPaymentMethodSpecificationName](#VendorPaymentMethodSpecificationName)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[PurchaseOrderPoolId](#PurchaseOrderPoolId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[VendorBankAccountId](#VendorBankAccountId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[InvoiceVendorAccountNumber](#InvoiceVendorAccountNumber)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[CashDiscountCode](#CashDiscountCode)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[ContactPersonId](#ContactPersonId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DeliveryModeCode](#DeliveryModeCode)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DeliveryTermsCode](#DeliveryTermsCode)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[ChargeVendorGroupId](#ChargeVendorGroupId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[PaymentScheduleName](#PaymentScheduleName)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[PaymentTermsName](#PaymentTermsName)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[ProjectId](#ProjectId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[ShippingCarrierId](#ShippingCarrierId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[ShippingCarrierServiceGroupId](#ShippingCarrierServiceGroupId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[ShippingCarrierServiceId](#ShippingCarrierServiceId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[TransportationModeId](#TransportationModeId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[TransportationRoutePlanId](#TransportationRoutePlanId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[TransportationTemplateId](#TransportationTemplateId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DeliveryName](#DeliveryName)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DeliveryPostalAddressRecId](#DeliveryPostalAddressRecId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DeliveryAddressLocationId](#DeliveryAddressLocationId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[IsDeliveryAddressAgreementSpecific](#IsDeliveryAddressAgreementSpecific)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[FormattedDeliveryAddress](#FormattedDeliveryAddress)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DeliveryAddressZipCode](#DeliveryAddressZipCode)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DeliveryBuildingCompliment](#DeliveryBuildingCompliment)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DeliveryAddressCity](#DeliveryAddressCity)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DeliveryCityInKana](#DeliveryCityInKana)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DeliveryAddressCountryRegionId](#DeliveryAddressCountryRegionId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DeliveryAddressCountryRegionISOCode](#DeliveryAddressCountryRegionISOCode)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DeliveryAddressCountyId](#DeliveryAddressCountyId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DeliveryAddressDescription](#DeliveryAddressDescription)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DeliveryAddressDistrictName](#DeliveryAddressDistrictName)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DeliveryAddressDunsNumber](#DeliveryAddressDunsNumber)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DeliveryAddressLatitude](#DeliveryAddressLatitude)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[IsDeliveryAddressPrivate](#IsDeliveryAddressPrivate)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DeliveryAddressLongitude](#DeliveryAddressLongitude)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DeliveryAddressPostBox](#DeliveryAddressPostBox)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DeliveryAddressStateId](#DeliveryAddressStateId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DeliveryAddressStreet](#DeliveryAddressStreet)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DeliveryStreetInKana](#DeliveryStreetInKana)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DeliveryAddressStreetNumber](#DeliveryAddressStreetNumber)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DeliveryValidFrom](#DeliveryValidFrom)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DeliveryValidTo](#DeliveryValidTo)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DeliveryAddressTimeZone](#DeliveryAddressTimeZone)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[DeliveryPostalAddress](#DeliveryPostalAddress)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[AgreementHeaderRecId](#AgreementHeaderRecId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[CommissionAgreement](#CommissionAgreement)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[AgreementSum](#AgreementSum)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[AgreementDate](#AgreementDate)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[SubjectOfAnAgreement](#SubjectOfAnAgreement)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[AgreementVatAmount](#AgreementVatAmount)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[MobilePhone](#MobilePhone)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[CreditLimit](#CreditLimit)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[InventoryProfile](#InventoryProfile)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[KindOfActivity](#KindOfActivity)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[LineOfBusiness](#LineOfBusiness)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[PaymDay](#PaymDay)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Telephone](#Telephone)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Extension](#Extension)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Fax](#Fax)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[TelexNumber](#TelexNumber)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[InternetAddress](#InternetAddress)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[AmountDifferenceInTaxAccounting](#AmountDifferenceInTaxAccounting)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[ExcludeFromReserveInBusinessAccounting](#ExcludeFromReserveInBusinessAccounting)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[ExcludeFromReserveInTaxAccounting](#ExcludeFromReserveInTaxAccounting)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[VATCharge](#VATCharge)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[VATOperationCode](#VATOperationCode)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[PostingProfile](#PostingProfile)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[PostingProfileWithPrepaymentJournalVoucher](#PostingProfileWithPrepaymentJournalVoucher)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[PurchaseResponsible](#PurchaseResponsible)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[PrimaryResponsibleWorkerRecId](#PrimaryResponsibleWorkerRecId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[SecondaryResponsibleWorkerRecId](#SecondaryResponsibleWorkerRecId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[PrimaryResponsibleWorkerName](#PrimaryResponsibleWorkerName)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[SecondaryResponsibleWorkerName](#SecondaryResponsibleWorkerName)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[MatchingPolicy](#MatchingPolicy)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Relationship_DefaultLedgerDimensionDimensionSetRelationshipId](#Relationship_DefaultLedgerDimensionDimensionSetRelationshipId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Relationship_AgreementVendorRelationshipId](#Relationship_AgreementVendorRelationshipId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Relationship_InvoiceVendorRelationshipId](#Relationship_InvoiceVendorRelationshipId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Relationship_BuyerGroupRelationshipId](#Relationship_BuyerGroupRelationshipId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Relationship_VendorPaymentMethodRelationshipId](#Relationship_VendorPaymentMethodRelationshipId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Relationship_VendorPaymentMethodSpecificationRelationshipId](#Relationship_VendorPaymentMethodSpecificationRelationshipId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Relationship_PurchaseOrderPoolRelationshipId](#Relationship_PurchaseOrderPoolRelationshipId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Relationship_VendorBankAccountIdRelationshipId](#Relationship_VendorBankAccountIdRelationshipId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Relationship_ContactPersonRelationshipId](#Relationship_ContactPersonRelationshipId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Relationship_DeliveryModeRelationshipId](#Relationship_DeliveryModeRelationshipId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Relationship_DeliveryTermsRelationshipId](#Relationship_DeliveryTermsRelationshipId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Relationship_ChargeVendorGroupRelationshipId](#Relationship_ChargeVendorGroupRelationshipId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Relationship_CashDiscountRelationshipId](#Relationship_CashDiscountRelationshipId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Relationship_PaymentScheduleRelationshipId](#Relationship_PaymentScheduleRelationshipId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Relationship_PaymentTermsRelationshipId](#Relationship_PaymentTermsRelationshipId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Relationship_ProjectRelationshipId](#Relationship_ProjectRelationshipId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Relationship_ShippingCarrierRelationshipId](#Relationship_ShippingCarrierRelationshipId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Relationship_ShippingCarrierServiceRelationshipId](#Relationship_ShippingCarrierServiceRelationshipId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Relationship_ShippingCarrierServiceGroupRelationshipId](#Relationship_ShippingCarrierServiceGroupRelationshipId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Relationship_TransportationRoutePlanRelationshipId](#Relationship_TransportationRoutePlanRelationshipId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Relationship_DefaultLedgerDimensionRelationshipId](#Relationship_DefaultLedgerDimensionRelationshipId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Relationship_HcmWorkerPrimaryRelationshipId](#Relationship_HcmWorkerPrimaryRelationshipId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Relationship_HcmWorkerSecondaryRelationshipId](#Relationship_HcmWorkerSecondaryRelationshipId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[BackingTable_PurchAgreementHeaderRelationshipId](#BackingTable_PurchAgreementHeaderRelationshipId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PurchPurchaseAgreementHeaderV2Entity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity</a>|

### <a href=#BuyingLegalEntityRecId name="BuyingLegalEntityRecId">BuyingLegalEntityRecId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BuyingLegalEntityRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BuyingLegalEntityId name="BuyingLegalEntityId">BuyingLegalEntityId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Buying legal entity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BuyingLegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Buying legal entity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseAgreementId name="PurchaseAgreementId">PurchaseAgreementId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseAgreementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgreementVendorAccountNumber name="AgreementVendorAccountNumber">AgreementVendorAccountNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementVendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorReference name="VendorReference">VendorReference</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor reference</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor reference</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseAgreementClassificationRecId name="PurchaseAgreementClassificationRecId">PurchaseAgreementClassificationRecId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseAgreementClassificationRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseAgreementClassificationName name="PurchaseAgreementClassificationName">PurchaseAgreementClassificationName</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase agreement classification</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseAgreementClassificationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase agreement classification</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgreementStatus name="AgreementStatus">AgreementStatus</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

### <a href=#DefaultEffectiveDate name="DefaultEffectiveDate">DefaultEffectiveDate</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultEffectiveDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultExpirationDate name="DefaultExpirationDate">DefaultExpirationDate</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultExpirationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCommitmentType name="DefaultCommitmentType">DefaultCommitmentType</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCommitmentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLedgerDimension name="DefaultLedgerDimension">DefaultLedgerDimension</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

### <a href=#DefaultLedgerDimensionDisplayValue name="DefaultLedgerDimensionDisplayValue">DefaultLedgerDimensionDisplayValue</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

### <a href=#ExternalDocumentReference name="ExternalDocumentReference">ExternalDocumentReference</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalDocumentReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentTitle name="DocumentTitle">DocumentTitle</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentTitle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

### <a href=#PreparerRecId name="PreparerRecId">PreparerRecId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreparerRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PreparerPersonPartyNumber name="PreparerPersonPartyNumber">PreparerPersonPartyNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Preparer</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreparerPersonPartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Preparer</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInterestBasedOnCentralEuropeanBank name="IsInterestBasedOnCentralEuropeanBank">IsInterestBasedOnCentralEuropeanBank</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInterestBasedOnCentralEuropeanBank attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumContractAmount name="MaximumContractAmount">MaximumContractAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumContractAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumContractAmount name="MinimumContractAmount">MinimumContractAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumContractAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcurementClassification name="ProcurementClassification">ProcurementClassification</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementClassification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchasingProcedureType name="PurchasingProcedureType">PurchasingProcedureType</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasingProcedureType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchasingPurpose name="PurchasingPurpose">PurchasingPurpose</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasingPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAgreementRenewable name="IsAgreementRenewable">IsAgreementRenewable</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAgreementRenewable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgreementWorkflowStatus name="AgreementWorkflowStatus">AgreementWorkflowStatus</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementWorkflowStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BuyerGroupId name="BuyerGroupId">BuyerGroupId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

### <a href=#VendorPaymentMethodName name="VendorPaymentMethodName">VendorPaymentMethodName</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

### <a href=#PurchaseOrderPoolId name="PurchaseOrderPoolId">PurchaseOrderPoolId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

### <a href=#VendorBankAccountId name="VendorBankAccountId">VendorBankAccountId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorBankAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceVendorAccountNumber name="InvoiceVendorAccountNumber">InvoiceVendorAccountNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

### <a href=#CashDiscountCode name="CashDiscountCode">CashDiscountCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

### <a href=#DeliveryModeCode name="DeliveryModeCode">DeliveryModeCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

### <a href=#ChargeVendorGroupId name="ChargeVendorGroupId">ChargeVendorGroupId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

### <a href=#PaymentScheduleName name="PaymentScheduleName">PaymentScheduleName</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

### <a href=#PaymentTermsName name="PaymentTermsName">PaymentTermsName</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

### <a href=#ProjectId name="ProjectId">ProjectId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

### <a href=#ShippingCarrierId name="ShippingCarrierId">ShippingCarrierId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingCarrierId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingCarrierServiceGroupId name="ShippingCarrierServiceGroupId">ShippingCarrierServiceGroupId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingCarrierServiceGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingCarrierServiceId name="ShippingCarrierServiceId">ShippingCarrierServiceId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingCarrierServiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationModeId name="TransportationModeId">TransportationModeId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transportation mode</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationModeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transportation mode</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationRoutePlanId name="TransportationRoutePlanId">TransportationRoutePlanId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationRoutePlanId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationTemplateId name="TransportationTemplateId">TransportationTemplateId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryName name="DeliveryName">DeliveryName</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryPostalAddressRecId name="DeliveryPostalAddressRecId">DeliveryPostalAddressRecId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

### <a href=#DeliveryAddressLocationId name="DeliveryAddressLocationId">DeliveryAddressLocationId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

### <a href=#IsDeliveryAddressAgreementSpecific name="IsDeliveryAddressAgreementSpecific">IsDeliveryAddressAgreementSpecific</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>One time delivery address</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDeliveryAddressAgreementSpecific attribute are listed below.</summary>

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

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

### <a href=#DeliveryBuildingCompliment name="DeliveryBuildingCompliment">DeliveryBuildingCompliment</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

### <a href=#DeliveryCityInKana name="DeliveryCityInKana">DeliveryCityInKana</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryCityInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCountryRegionId name="DeliveryAddressCountryRegionId">DeliveryAddressCountryRegionId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

### <a href=#DeliveryStreetInKana name="DeliveryStreetInKana">DeliveryStreetInKana</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryStreetInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressStreetNumber name="DeliveryAddressStreetNumber">DeliveryAddressStreetNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

### <a href=#DeliveryPostalAddress name="DeliveryPostalAddress">DeliveryPostalAddress</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryPostalAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgreementHeaderRecId name="AgreementHeaderRecId">AgreementHeaderRecId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementHeaderRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CommissionAgreement name="CommissionAgreement">CommissionAgreement</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommissionAgreement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgreementSum name="AgreementSum">AgreementSum</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementSum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgreementDate name="AgreementDate">AgreementDate</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubjectOfAnAgreement name="SubjectOfAnAgreement">SubjectOfAnAgreement</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubjectOfAnAgreement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgreementVatAmount name="AgreementVatAmount">AgreementVatAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementVatAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MobilePhone name="MobilePhone">MobilePhone</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MobilePhone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditLimit name="CreditLimit">CreditLimit</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryProfile name="InventoryProfile">InventoryProfile</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KindOfActivity name="KindOfActivity">KindOfActivity</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KindOfActivity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineOfBusiness name="LineOfBusiness">LineOfBusiness</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineOfBusiness attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymDay name="PaymDay">PaymDay</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymDay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Telephone name="Telephone">Telephone</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Telephone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Extension name="Extension">Extension</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Extension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Fax name="Fax">Fax</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Fax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TelexNumber name="TelexNumber">TelexNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TelexNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InternetAddress name="InternetAddress">InternetAddress</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InternetAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountDifferenceInTaxAccounting name="AmountDifferenceInTaxAccounting">AmountDifferenceInTaxAccounting</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountDifferenceInTaxAccounting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExcludeFromReserveInBusinessAccounting name="ExcludeFromReserveInBusinessAccounting">ExcludeFromReserveInBusinessAccounting</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExcludeFromReserveInBusinessAccounting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExcludeFromReserveInTaxAccounting name="ExcludeFromReserveInTaxAccounting">ExcludeFromReserveInTaxAccounting</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExcludeFromReserveInTaxAccounting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VATCharge name="VATCharge">VATCharge</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATCharge attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VATOperationCode name="VATOperationCode">VATOperationCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATOperationCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingProfile name="PostingProfile">PostingProfile</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingProfileWithPrepaymentJournalVoucher name="PostingProfileWithPrepaymentJournalVoucher">PostingProfileWithPrepaymentJournalVoucher</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfileWithPrepaymentJournalVoucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseResponsible name="PurchaseResponsible">PurchaseResponsible</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseResponsible attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryResponsibleWorkerRecId name="PrimaryResponsibleWorkerRecId">PrimaryResponsibleWorkerRecId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryResponsibleWorkerRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecondaryResponsibleWorkerRecId name="SecondaryResponsibleWorkerRecId">SecondaryResponsibleWorkerRecId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecondaryResponsibleWorkerRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryResponsibleWorkerName name="PrimaryResponsibleWorkerName">PrimaryResponsibleWorkerName</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary responsible worker</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryResponsibleWorkerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Primary responsible worker</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecondaryResponsibleWorkerName name="SecondaryResponsibleWorkerName">SecondaryResponsibleWorkerName</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Secondary responsible worker</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecondaryResponsibleWorkerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Secondary responsible worker</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MatchingPolicy name="MatchingPolicy">MatchingPolicy</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MatchingPolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultLedgerDimensionDimensionSetRelationshipId name="Relationship_DefaultLedgerDimensionDimensionSetRelationshipId">Relationship_DefaultLedgerDimensionDimensionSetRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultLedgerDimensionDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AgreementVendorRelationshipId name="Relationship_AgreementVendorRelationshipId">Relationship_AgreementVendorRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AgreementVendorRelationshipId attribute are listed below.</summary>

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

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BuyerGroupRelationshipId name="Relationship_BuyerGroupRelationshipId">Relationship_BuyerGroupRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BuyerGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_VendorPaymentMethodRelationshipId name="Relationship_VendorPaymentMethodRelationshipId">Relationship_VendorPaymentMethodRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendorPaymentMethodRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_VendorPaymentMethodSpecificationRelationshipId name="Relationship_VendorPaymentMethodSpecificationRelationshipId">Relationship_VendorPaymentMethodSpecificationRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendorPaymentMethodSpecificationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PurchaseOrderPoolRelationshipId name="Relationship_PurchaseOrderPoolRelationshipId">Relationship_PurchaseOrderPoolRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchaseOrderPoolRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_VendorBankAccountIdRelationshipId name="Relationship_VendorBankAccountIdRelationshipId">Relationship_VendorBankAccountIdRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendorBankAccountIdRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ContactPersonRelationshipId name="Relationship_ContactPersonRelationshipId">Relationship_ContactPersonRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ContactPersonRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DeliveryModeRelationshipId name="Relationship_DeliveryModeRelationshipId">Relationship_DeliveryModeRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DeliveryModeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DeliveryTermsRelationshipId name="Relationship_DeliveryTermsRelationshipId">Relationship_DeliveryTermsRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DeliveryTermsRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ChargeVendorGroupRelationshipId name="Relationship_ChargeVendorGroupRelationshipId">Relationship_ChargeVendorGroupRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ChargeVendorGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CashDiscountRelationshipId name="Relationship_CashDiscountRelationshipId">Relationship_CashDiscountRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CashDiscountRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PaymentScheduleRelationshipId name="Relationship_PaymentScheduleRelationshipId">Relationship_PaymentScheduleRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentScheduleRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PaymentTermsRelationshipId name="Relationship_PaymentTermsRelationshipId">Relationship_PaymentTermsRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentTermsRelationshipId attribute are listed below.</summary>

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

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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

### <a href=#Relationship_ShippingCarrierRelationshipId name="Relationship_ShippingCarrierRelationshipId">Relationship_ShippingCarrierRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ShippingCarrierRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ShippingCarrierServiceRelationshipId name="Relationship_ShippingCarrierServiceRelationshipId">Relationship_ShippingCarrierServiceRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ShippingCarrierServiceRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ShippingCarrierServiceGroupRelationshipId name="Relationship_ShippingCarrierServiceGroupRelationshipId">Relationship_ShippingCarrierServiceGroupRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ShippingCarrierServiceGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TransportationRoutePlanRelationshipId name="Relationship_TransportationRoutePlanRelationshipId">Relationship_TransportationRoutePlanRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TransportationRoutePlanRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DefaultLedgerDimensionRelationshipId name="Relationship_DefaultLedgerDimensionRelationshipId">Relationship_DefaultLedgerDimensionRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultLedgerDimensionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_HcmWorkerPrimaryRelationshipId name="Relationship_HcmWorkerPrimaryRelationshipId">Relationship_HcmWorkerPrimaryRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HcmWorkerPrimaryRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_HcmWorkerSecondaryRelationshipId name="Relationship_HcmWorkerSecondaryRelationshipId">Relationship_HcmWorkerSecondaryRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HcmWorkerSecondaryRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_PurchAgreementHeaderRelationshipId name="BackingTable_PurchAgreementHeaderRelationshipId">BackingTable_PurchAgreementHeaderRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PurchAgreementHeaderRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchAgreementHeader.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchAgreementHeader.cdm.json/PurchAgreementHeader</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchAgreementHeader.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseAgreementHeaderV2Entity (this entity)  

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
