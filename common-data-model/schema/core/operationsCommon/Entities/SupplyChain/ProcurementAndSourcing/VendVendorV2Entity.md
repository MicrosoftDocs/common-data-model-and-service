---
title: VendVendorV2Entity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Vendors V2 in ProcurementAndSourcing(VendVendorV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/VendVendorV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendors V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[VendorAccountNumber](#VendorAccountNumber)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[WithholdingTaxGroupCode](#WithholdingTaxGroupCode)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[DefaultPaymentTermsName](#DefaultPaymentTermsName)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[LineDiscountVendorGroupCode](#LineDiscountVendorGroupCode)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[BankAccountId](#BankAccountId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[CentralBankPurposeCode](#CentralBankPurposeCode)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[CentralBankPurposeText](#CentralBankPurposeText)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[HasOnlyTakenBids](#HasOnlyTakenBids)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[OnHoldStatus](#OnHoldStatus)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[VendorHoldReleaseDate](#VendorHoldReleaseDate)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[CashDiscountCode](#CashDiscountCode)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[IsPurchaseOrderChangeRequestOverrideAllowed](#IsPurchaseOrderChangeRequestOverrideAllowed)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[IsChangeManagementActivated](#IsChangeManagementActivated)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[IsChangeMangementOverrideByVendorAllowed](#IsChangeMangementOverrideByVendorAllowed)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[CISCompanyRegistrationNumber](#CISCompanyRegistrationNumber)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[CISNationalInsuranceNumber](#CISNationalInsuranceNumber)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[CISStatus](#CISStatus)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[CISUniqueTaxPayerReference](#CISUniqueTaxPayerReference)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[CISVerificationDate](#CISVerificationDate)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[CISVerificationNumber](#CISVerificationNumber)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[ClearingPeriodPaymentTermsId](#ClearingPeriodPaymentTermsId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[CommercialRegisterName](#CommercialRegisterName)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[CommercialRegisterInsetNumber](#CommercialRegisterInsetNumber)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[CommercialRegisterSection](#CommercialRegisterSection)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[CompanyChainName](#CompanyChainName)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[SiretNumber](#SiretNumber)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[NAFCodeRef](#NAFCodeRef)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[CompanyType](#CompanyType)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryContactPersonId](#PrimaryContactPersonId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[CreditLimit](#CreditLimit)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[CreditRating](#CreditRating)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[UniquePopulationRegistryCode](#UniquePopulationRegistryCode)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[Tax1099DoingBusinessAsName](#Tax1099DoingBusinessAsName)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[DefaultLedgerDimension](#DefaultLedgerDimension)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[DefaultInventoryStatusId](#DefaultInventoryStatusId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[DestinationCode](#DestinationCode)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[DIOTCountryCode](#DIOTCountryCode)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[IsOwnerDisabled](#IsOwnerDisabled)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[DefaultDeliveryModeId](#DefaultDeliveryModeId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[DefaultDeliveryTermsCode](#DefaultDeliveryTermsCode)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[DefaultTotalDiscountVendorGroupCode](#DefaultTotalDiscountVendorGroupCode)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[EthnicOriginId](#EthnicOriginId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[FactoringVendorAccountNumber](#FactoringVendorAccountNumber)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[IsWomanOwner](#IsWomanOwner)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[FiscalCode](#FiscalCode)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[IsForeignEntity](#IsForeignEntity)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[ForeignVendorTaxRegistrationId](#ForeignVendorTaxRegistrationId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[UPSFreightZone](#UPSFreightZone)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[IsVendorLocatedInHUBZone](#IsVendorLocatedInHUBZone)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[ArePricesIncludingSalesTax](#ArePricesIncludingSalesTax)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[DefaultProcumentWarehouseId](#DefaultProcumentWarehouseId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[DefaultPurchaseSiteId](#DefaultPurchaseSiteId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[InvoiceVendorAccountNumber](#InvoiceVendorAccountNumber)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[BuyerGroupId](#BuyerGroupId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[LineOfBusinessId](#LineOfBusinessId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[IsVendorLocallyOwned](#IsVendorLocallyOwned)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PaymentTransactionCodeRef](#PaymentTransactionCodeRef)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[MainContactWorkerPersonnelNumberRef](#MainContactWorkerPersonnelNumberRef)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[ChargeVendorGroupId](#ChargeVendorGroupId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[VendorInvoiceLineMatchingPolicy](#VendorInvoiceLineMatchingPolicy)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[Notes](#Notes)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[IsMinorityOwned](#IsMinorityOwned)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[MultilineDiscountVendorGroupCode](#MultilineDiscountVendorGroupCode)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[NameControl](#NameControl)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[Nationality](#Nationality)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[NumberSequenceGroupId](#NumberSequenceGroupId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[DefaultOffsetAccountType](#DefaultOffsetAccountType)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[DefaultOffsetLedgerAccount](#DefaultOffsetLedgerAccount)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[IsOneTimeVendor](#IsOneTimeVendor)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[DIOTOperationType](#DIOTOperationType)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[NationalRegistryNumberId](#NationalRegistryNumberId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[Party](#Party)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[DefaultPaymentDayName](#DefaultPaymentDayName)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PaymentId](#PaymentId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[DefaultVendorPaymentMethodName](#DefaultVendorPaymentMethodName)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[DefaultPaymentScheduleName](#DefaultPaymentScheduleName)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PaymentSpecificationId](#PaymentSpecificationId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PriceVendorGroupId](#PriceVendorGroupId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[WillPurchaseOrderIncludePricesAndAmounts](#WillPurchaseOrderIncludePricesAndAmounts)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PurchaseWorkCalendarId](#PurchaseWorkCalendarId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[DefaultPurchaseOrderPoolId](#DefaultPurchaseOrderPoolId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[RFCFederalTaxNumber](#RFCFederalTaxNumber)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[IsFlaggedWithSecondTIN](#IsFlaggedWithSecondTIN)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[BusinessSegmentCode](#BusinessSegmentCode)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[IsSmallBusiness](#IsSmallBusiness)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[StateInscription](#StateInscription)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[BusinessSubsegmentCode](#BusinessSubsegmentCode)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[DefaultSupplementaryProductVendorGroupId](#DefaultSupplementaryProductVendorGroupId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PurchaseRebateVendorGroupId](#PurchaseRebateVendorGroupId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[Tax1099BoxIdRef](#Tax1099BoxIdRef)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[Tax1099NameToUse](#Tax1099NameToUse)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[Tax1099FederalTaxId](#Tax1099FederalTaxId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[IsReportingTax1099](#IsReportingTax1099)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[SalesTaxGroupCode](#SalesTaxGroupCode)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[Tax1099IdType](#Tax1099IdType)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[IsWithholdingTaxCalculated](#IsWithholdingTaxCalculated)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[DefaultCashDiscountUsage](#DefaultCashDiscountUsage)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[TaxExemptNumber](#TaxExemptNumber)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[VendorExceptionGroupIdRef](#VendorExceptionGroupIdRef)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[VendorGroupId](#VendorGroupId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[InvoiceDeclarationIdRef](#InvoiceDeclarationIdRef)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[ProductDescriptionVendorGroupId](#ProductDescriptionVendorGroupId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[DIOTVendorType](#DIOTVendorType)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[VendorPriceToleranceGroupId](#VendorPriceToleranceGroupId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[IsServiceVeteranOwned](#IsServiceVeteranOwned)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[IsW9Received](#IsW9Received)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[IsW9CheckingEnabled](#IsW9CheckingEnabled)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[OurAccountNumber](#OurAccountNumber)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[NAFCode](#NAFCode)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[VendorInvoiceDeclarationId](#VendorInvoiceDeclarationId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PaymentTransactionCode](#PaymentTransactionCode)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[MainContactPersonnelNumber](#MainContactPersonnelNumber)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[Tax1099BoxId](#Tax1099BoxId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[Tax1099Type](#Tax1099Type)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[VendorExceptionGroupId](#VendorExceptionGroupId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[DefaultLedgerDimensionDisplayValue](#DefaultLedgerDimensionDisplayValue)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[DefaultOffsetLedgerAccountDisplayValue](#DefaultOffsetLedgerAccountDisplayValue)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[AddressBooks](#AddressBooks)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[AddressDescription](#AddressDescription)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[AddressCity](#AddressCity)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[AddressCountryRegionId](#AddressCountryRegionId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[AddressCountyId](#AddressCountyId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[AddressDistrictName](#AddressDistrictName)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[AddressLatitude](#AddressLatitude)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[AddressLocationId](#AddressLocationId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[AddressLocationRoles](#AddressLocationRoles)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[AddressLongitude](#AddressLongitude)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[AddressStateId](#AddressStateId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[AddressStreet](#AddressStreet)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[AddressBuildingCompliment](#AddressBuildingCompliment)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[AddressStreetNumber](#AddressStreetNumber)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[AddressTimeZone](#AddressTimeZone)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[AddressValidFrom](#AddressValidFrom)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[AddressValidTo](#AddressValidTo)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[AddressZipCode](#AddressZipCode)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[AddressCountryRegionISOCode](#AddressCountryRegionISOCode)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[AddressPostBox](#AddressPostBox)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[AddressCityInKana](#AddressCityInKana)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[AddressStreetInKana](#AddressStreetInKana)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[AddressBrazilianCNPJOrCPF](#AddressBrazilianCNPJOrCPF)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[AddressBrazilianIE](#AddressBrazilianIE)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[FormattedPrimaryAddress](#FormattedPrimaryAddress)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[VendorKnownAsName](#VendorKnownAsName)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[LanguageId](#LanguageId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[VendorOrganizationName](#VendorOrganizationName)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[VendorSearchName](#VendorSearchName)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[OrganizationABCCode](#OrganizationABCCode)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[OrganizationNumber](#OrganizationNumber)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[OrganizationEmployeeAmount](#OrganizationEmployeeAmount)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[OrganizationPhoneticName](#OrganizationPhoneticName)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[VendorPartyNumber](#VendorPartyNumber)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[VendorPartyType](#VendorPartyType)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PersonAnniversaryDay](#PersonAnniversaryDay)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PersonAnniversaryMonth](#PersonAnniversaryMonth)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PersonAnniversaryYear](#PersonAnniversaryYear)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PersonBirthDay](#PersonBirthDay)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PersonBirthMonth](#PersonBirthMonth)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PersonBirthYear](#PersonBirthYear)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PersonChildrenNames](#PersonChildrenNames)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PersonGender](#PersonGender)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PersonHobbies](#PersonHobbies)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PersonFirstName](#PersonFirstName)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PersonMiddleName](#PersonMiddleName)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PersonLastNamePrefix](#PersonLastNamePrefix)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PersonLastName](#PersonLastName)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PersonInitials](#PersonInitials)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PersonMaritalStatus](#PersonMaritalStatus)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PersonPersonalSuffix](#PersonPersonalSuffix)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PersonPersonalTitle](#PersonPersonalTitle)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PersonPhoneticFirstName](#PersonPhoneticFirstName)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PersonPhoneticLastName](#PersonPhoneticLastName)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PersonPhoneticMiddleName](#PersonPhoneticMiddleName)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PersonProfessionalSuffix](#PersonProfessionalSuffix)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PersonProfessionalTitle](#PersonProfessionalTitle)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryEmailAddress](#PrimaryEmailAddress)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryEmailAddressDescription](#PrimaryEmailAddressDescription)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[IsPrimaryEmailAddressIMEnabled](#IsPrimaryEmailAddressIMEnabled)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryEmailAddressPurpose](#PrimaryEmailAddressPurpose)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryFaxNumber](#PrimaryFaxNumber)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryFaxNumberDescription](#PrimaryFaxNumberDescription)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryFaxNumberExtension](#PrimaryFaxNumberExtension)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryFaxNumberPurpose](#PrimaryFaxNumberPurpose)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryPhoneNumber](#PrimaryPhoneNumber)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryPhoneNumberDescription](#PrimaryPhoneNumberDescription)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[IsPrimaryPhoneNumberMobile](#IsPrimaryPhoneNumberMobile)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryPhoneNumberPurpose](#PrimaryPhoneNumberPurpose)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryTelex](#PrimaryTelex)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryTelexDescription](#PrimaryTelexDescription)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryTelexPurpose](#PrimaryTelexPurpose)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryURL](#PrimaryURL)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryURLDescription](#PrimaryURLDescription)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryURLPurpose](#PrimaryURLPurpose)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryFacebook](#PrimaryFacebook)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryFacebookDescription](#PrimaryFacebookDescription)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryFacebookPurpose](#PrimaryFacebookPurpose)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryLinkedIn](#PrimaryLinkedIn)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryLinkedInDescription](#PrimaryLinkedInDescription)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryLinkedInPurpose](#PrimaryLinkedInPurpose)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryTwitter](#PrimaryTwitter)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryTwitterDescription](#PrimaryTwitterDescription)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryTwitterPurpose](#PrimaryTwitterPurpose)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[WillPurchaseOrderProcessingSummaryUpdatePurchaseOrder](#WillPurchaseOrderProcessingSummaryUpdatePurchaseOrder)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[WillProductReceiptProcessingSummaryUpdatePurchaseOrder](#WillProductReceiptProcessingSummaryUpdatePurchaseOrder)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[WillReceiptsListProcessingSummaryUpdatePurchaseOrder](#WillReceiptsListProcessingSummaryUpdatePurchaseOrder)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[WillInvoiceProcessingSummaryUpdatePurchaseOrder](#WillInvoiceProcessingSummaryUpdatePurchaseOrder)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[IsCUSIPIdentificationNumberApplicable](#IsCUSIPIdentificationNumberApplicable)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[CUSIPIdentificationNumber](#CUSIPIdentificationNumber)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[CUSIPDetails](#CUSIPDetails)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[OIDInvestorType](#OIDInvestorType)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[OIDNomineeDetails](#OIDNomineeDetails)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[ISNationalRegistryNumber](#ISNationalRegistryNumber)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[WithholdingTaxVendorType](#WithholdingTaxVendorType)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PurchaseOrderConsolidationDayOfMonth](#PurchaseOrderConsolidationDayOfMonth)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PaymentFeeGroupId](#PaymentFeeGroupId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[IsVendorPayingBankPaymentFee](#IsVendorPayingBankPaymentFee)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[BrazilianCCM](#BrazilianCCM)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[BrazilianCNPJOrCPF](#BrazilianCNPJOrCPF)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[BrazilianCNAE](#BrazilianCNAE)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[ForeignerId](#ForeignerId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[BrazilianIE](#BrazilianIE)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[BrazilianNIT](#BrazilianNIT)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[FiscalOperationPresenceType](#FiscalOperationPresenceType)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[IsServiceDeliveryAddressBased](#IsServiceDeliveryAddressBased)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[IsPurchaseConsumed](#IsPurchaseConsumed)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[BrazilianINSSCEI](#BrazilianINSSCEI)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[IsIncomingFiscalDocumentGenerated](#IsIncomingFiscalDocumentGenerated)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[IsICMSContributor](#IsICMSContributor)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[CompositionScheme](#CompositionScheme)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[ForeignVendor](#ForeignVendor)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[GTAVendor](#GTAVendor)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PreferentialVendor](#PreferentialVendor)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[SSIVendor](#SSIVendor)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[NatureOfAssessee](#NatureOfAssessee)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PANNumber](#PANNumber)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PANReferenceNumber](#PANReferenceNumber)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PANStatus](#PANStatus)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[SSIValidityDate](#SSIValidityDate)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[TCSGroup](#TCSGroup)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[TDSGroup](#TDSGroup)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[VendorPortalCollaborationMethod](#VendorPortalCollaborationMethod)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryPhoneNumberExtension](#PrimaryPhoneNumberExtension)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[ZakatRegistrationNumber](#ZakatRegistrationNumber)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[ZakatFileNumber](#ZakatFileNumber)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[IsSubcontractor](#IsSubcontractor)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[ZakatServiceType](#ZakatServiceType)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[ElectronicLocationId](#ElectronicLocationId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[VendorPaymentFineCode](#VendorPaymentFineCode)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[VendorPaymentFinancialInterestCode](#VendorPaymentFinancialInterestCode)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[BirthPlace](#BirthPlace)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[BirthCountyCode](#BirthCountyCode)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[ResidenceForeignCountryRegionId](#ResidenceForeignCountryRegionId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[FiscalDocumentIncomeCode](#FiscalDocumentIncomeCode)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[DUNSNumber](#DUNSNumber)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[IsGSTCompositionSchemeEnabled](#IsGSTCompositionSchemeEnabled)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[BankTransactionType](#BankTransactionType)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[BankOrderOfPayment](#BankOrderOfPayment)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[ForeignResident](#ForeignResident)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[InventoryProfile](#InventoryProfile)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[InventoryProfileType](#InventoryProfileType)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[SeparateDivisionId](#SeparateDivisionId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[StructureDepartment](#StructureDepartment)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[TaxOperationCode](#TaxOperationCode)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[TaxPartnerKind](#TaxPartnerKind)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[TaxAgent](#TaxAgent)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryContactFaxRecordId](#PrimaryContactFaxRecordId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryContactPhoneRecordId](#PrimaryContactPhoneRecordId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryContactEmailRecordId](#PrimaryContactEmailRecordId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[PrimaryContactURLRecordId](#PrimaryContactURLRecordId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[AddressRecordId](#AddressRecordId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[Relationship_OffsetLedgerDimensionCombinationRelationshipId](#Relationship_OffsetLedgerDimensionCombinationRelationshipId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[BackingTable_VendTableRelationshipId](#BackingTable_VendTableRelationshipId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="VendVendorV2Entity.md" target="_blank">ProcurementAndSourcing/VendVendorV2Entity</a>|

### <a href=#VendorAccountNumber name="VendorAccountNumber">VendorAccountNumber</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

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

### <a href=#WithholdingTaxGroupCode name="WithholdingTaxGroupCode">WithholdingTaxGroupCode</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingTaxGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultPaymentTermsName name="DefaultPaymentTermsName">DefaultPaymentTermsName</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultPaymentTermsName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDiscountVendorGroupCode name="LineDiscountVendorGroupCode">LineDiscountVendorGroupCode</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

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

### <a href=#BankAccountId name="BankAccountId">BankAccountId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CentralBankPurposeCode name="CentralBankPurposeCode">CentralBankPurposeCode</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CentralBankPurposeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CentralBankPurposeText name="CentralBankPurposeText">CentralBankPurposeText</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CentralBankPurposeText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HasOnlyTakenBids name="HasOnlyTakenBids">HasOnlyTakenBids</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HasOnlyTakenBids attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnHoldStatus name="OnHoldStatus">OnHoldStatus</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnHoldStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorHoldReleaseDate name="VendorHoldReleaseDate">VendorHoldReleaseDate</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorHoldReleaseDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountCode name="CashDiscountCode">CashDiscountCode</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

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

### <a href=#IsPurchaseOrderChangeRequestOverrideAllowed name="IsPurchaseOrderChangeRequestOverrideAllowed">IsPurchaseOrderChangeRequestOverrideAllowed</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPurchaseOrderChangeRequestOverrideAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsChangeManagementActivated name="IsChangeManagementActivated">IsChangeManagementActivated</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsChangeManagementActivated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsChangeMangementOverrideByVendorAllowed name="IsChangeMangementOverrideByVendorAllowed">IsChangeMangementOverrideByVendorAllowed</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsChangeMangementOverrideByVendorAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CISCompanyRegistrationNumber name="CISCompanyRegistrationNumber">CISCompanyRegistrationNumber</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CISCompanyRegistrationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CISNationalInsuranceNumber name="CISNationalInsuranceNumber">CISNationalInsuranceNumber</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CISNationalInsuranceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CISStatus name="CISStatus">CISStatus</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CISStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CISUniqueTaxPayerReference name="CISUniqueTaxPayerReference">CISUniqueTaxPayerReference</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CISUniqueTaxPayerReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CISVerificationDate name="CISVerificationDate">CISVerificationDate</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CISVerificationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CISVerificationNumber name="CISVerificationNumber">CISVerificationNumber</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CISVerificationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClearingPeriodPaymentTermsId name="ClearingPeriodPaymentTermsId">ClearingPeriodPaymentTermsId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClearingPeriodPaymentTermsId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CommercialRegisterName name="CommercialRegisterName">CommercialRegisterName</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommercialRegisterName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CommercialRegisterInsetNumber name="CommercialRegisterInsetNumber">CommercialRegisterInsetNumber</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommercialRegisterInsetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CommercialRegisterSection name="CommercialRegisterSection">CommercialRegisterSection</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommercialRegisterSection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyChainName name="CompanyChainName">CompanyChainName</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyChainName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SiretNumber name="SiretNumber">SiretNumber</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SiretNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NAFCodeRef name="NAFCodeRef">NAFCodeRef</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NAFCodeRef attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyType name="CompanyType">CompanyType</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactPersonId name="PrimaryContactPersonId">PrimaryContactPersonId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactPersonId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditLimit name="CreditLimit">CreditLimit</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

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

### <a href=#CreditRating name="CreditRating">CreditRating</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditRating attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UniquePopulationRegistryCode name="UniquePopulationRegistryCode">UniquePopulationRegistryCode</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UniquePopulationRegistryCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

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

### <a href=#Tax1099DoingBusinessAsName name="Tax1099DoingBusinessAsName">Tax1099DoingBusinessAsName</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099DoingBusinessAsName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLedgerDimension name="DefaultLedgerDimension">DefaultLedgerDimension</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

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

### <a href=#DefaultInventoryStatusId name="DefaultInventoryStatusId">DefaultInventoryStatusId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultInventoryStatusId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationCode name="DestinationCode">DestinationCode</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DIOTCountryCode name="DIOTCountryCode">DIOTCountryCode</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DIOTCountryCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOwnerDisabled name="IsOwnerDisabled">IsOwnerDisabled</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOwnerDisabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDeliveryModeId name="DefaultDeliveryModeId">DefaultDeliveryModeId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDeliveryModeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDeliveryTermsCode name="DefaultDeliveryTermsCode">DefaultDeliveryTermsCode</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDeliveryTermsCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultTotalDiscountVendorGroupCode name="DefaultTotalDiscountVendorGroupCode">DefaultTotalDiscountVendorGroupCode</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultTotalDiscountVendorGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EthnicOriginId name="EthnicOriginId">EthnicOriginId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EthnicOriginId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FactoringVendorAccountNumber name="FactoringVendorAccountNumber">FactoringVendorAccountNumber</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FactoringVendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWomanOwner name="IsWomanOwner">IsWomanOwner</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWomanOwner attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCode name="FiscalCode">FiscalCode</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsForeignEntity name="IsForeignEntity">IsForeignEntity</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsForeignEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForeignVendorTaxRegistrationId name="ForeignVendorTaxRegistrationId">ForeignVendorTaxRegistrationId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForeignVendorTaxRegistrationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UPSFreightZone name="UPSFreightZone">UPSFreightZone</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UPSFreightZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsVendorLocatedInHUBZone name="IsVendorLocatedInHUBZone">IsVendorLocatedInHUBZone</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsVendorLocatedInHUBZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArePricesIncludingSalesTax name="ArePricesIncludingSalesTax">ArePricesIncludingSalesTax</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

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

### <a href=#DefaultProcumentWarehouseId name="DefaultProcumentWarehouseId">DefaultProcumentWarehouseId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProcumentWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultPurchaseSiteId name="DefaultPurchaseSiteId">DefaultPurchaseSiteId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultPurchaseSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceVendorAccountNumber name="InvoiceVendorAccountNumber">InvoiceVendorAccountNumber</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

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

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

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

### <a href=#LineOfBusinessId name="LineOfBusinessId">LineOfBusinessId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineOfBusinessId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsVendorLocallyOwned name="IsVendorLocallyOwned">IsVendorLocallyOwned</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsVendorLocallyOwned attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentTransactionCodeRef name="PaymentTransactionCodeRef">PaymentTransactionCodeRef</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentTransactionCodeRef attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainContactWorkerPersonnelNumberRef name="MainContactWorkerPersonnelNumberRef">MainContactWorkerPersonnelNumberRef</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainContactWorkerPersonnelNumberRef attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeVendorGroupId name="ChargeVendorGroupId">ChargeVendorGroupId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

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

### <a href=#VendorInvoiceLineMatchingPolicy name="VendorInvoiceLineMatchingPolicy">VendorInvoiceLineMatchingPolicy</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorInvoiceLineMatchingPolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Notes name="Notes">Notes</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Notes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsMinorityOwned name="IsMinorityOwned">IsMinorityOwned</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsMinorityOwned attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MultilineDiscountVendorGroupCode name="MultilineDiscountVendorGroupCode">MultilineDiscountVendorGroupCode</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

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

### <a href=#NameControl name="NameControl">NameControl</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NameControl attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Nationality name="Nationality">Nationality</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Nationality attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceGroupId name="NumberSequenceGroupId">NumberSequenceGroupId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

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

### <a href=#DefaultOffsetAccountType name="DefaultOffsetAccountType">DefaultOffsetAccountType</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultOffsetAccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultOffsetLedgerAccount name="DefaultOffsetLedgerAccount">DefaultOffsetLedgerAccount</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultOffsetLedgerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOneTimeVendor name="IsOneTimeVendor">IsOneTimeVendor</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

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

### <a href=#DIOTOperationType name="DIOTOperationType">DIOTOperationType</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DIOTOperationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NationalRegistryNumberId name="NationalRegistryNumberId">NationalRegistryNumberId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NationalRegistryNumberId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Party name="Party">Party</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Party attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultPaymentDayName name="DefaultPaymentDayName">DefaultPaymentDayName</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultPaymentDayName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentId name="PaymentId">PaymentId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultVendorPaymentMethodName name="DefaultVendorPaymentMethodName">DefaultVendorPaymentMethodName</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultVendorPaymentMethodName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultPaymentScheduleName name="DefaultPaymentScheduleName">DefaultPaymentScheduleName</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultPaymentScheduleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentSpecificationId name="PaymentSpecificationId">PaymentSpecificationId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentSpecificationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceVendorGroupId name="PriceVendorGroupId">PriceVendorGroupId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceVendorGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillPurchaseOrderIncludePricesAndAmounts name="WillPurchaseOrderIncludePricesAndAmounts">WillPurchaseOrderIncludePricesAndAmounts</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillPurchaseOrderIncludePricesAndAmounts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseWorkCalendarId name="PurchaseWorkCalendarId">PurchaseWorkCalendarId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseWorkCalendarId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultPurchaseOrderPoolId name="DefaultPurchaseOrderPoolId">DefaultPurchaseOrderPoolId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultPurchaseOrderPoolId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFCFederalTaxNumber name="RFCFederalTaxNumber">RFCFederalTaxNumber</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFCFederalTaxNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFlaggedWithSecondTIN name="IsFlaggedWithSecondTIN">IsFlaggedWithSecondTIN</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFlaggedWithSecondTIN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BusinessSegmentCode name="BusinessSegmentCode">BusinessSegmentCode</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BusinessSegmentCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSmallBusiness name="IsSmallBusiness">IsSmallBusiness</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSmallBusiness attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StateInscription name="StateInscription">StateInscription</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StateInscription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BusinessSubsegmentCode name="BusinessSubsegmentCode">BusinessSubsegmentCode</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BusinessSubsegmentCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultSupplementaryProductVendorGroupId name="DefaultSupplementaryProductVendorGroupId">DefaultSupplementaryProductVendorGroupId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultSupplementaryProductVendorGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseRebateVendorGroupId name="PurchaseRebateVendorGroupId">PurchaseRebateVendorGroupId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseRebateVendorGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099BoxIdRef name="Tax1099BoxIdRef">Tax1099BoxIdRef</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099BoxIdRef attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099NameToUse name="Tax1099NameToUse">Tax1099NameToUse</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099NameToUse attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099FederalTaxId name="Tax1099FederalTaxId">Tax1099FederalTaxId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099FederalTaxId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReportingTax1099 name="IsReportingTax1099">IsReportingTax1099</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReportingTax1099 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroupCode name="SalesTaxGroupCode">SalesTaxGroupCode</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

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

### <a href=#Tax1099IdType name="Tax1099IdType">Tax1099IdType</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099IdType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWithholdingTaxCalculated name="IsWithholdingTaxCalculated">IsWithholdingTaxCalculated</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWithholdingTaxCalculated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCashDiscountUsage name="DefaultCashDiscountUsage">DefaultCashDiscountUsage</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCashDiscountUsage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxExemptNumber name="TaxExemptNumber">TaxExemptNumber</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

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

### <a href=#VendorExceptionGroupIdRef name="VendorExceptionGroupIdRef">VendorExceptionGroupIdRef</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorExceptionGroupIdRef attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorGroupId name="VendorGroupId">VendorGroupId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceDeclarationIdRef name="InvoiceDeclarationIdRef">InvoiceDeclarationIdRef</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceDeclarationIdRef attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductDescriptionVendorGroupId name="ProductDescriptionVendorGroupId">ProductDescriptionVendorGroupId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductDescriptionVendorGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DIOTVendorType name="DIOTVendorType">DIOTVendorType</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DIOTVendorType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorPriceToleranceGroupId name="VendorPriceToleranceGroupId">VendorPriceToleranceGroupId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorPriceToleranceGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsServiceVeteranOwned name="IsServiceVeteranOwned">IsServiceVeteranOwned</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsServiceVeteranOwned attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsW9Received name="IsW9Received">IsW9Received</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsW9Received attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsW9CheckingEnabled name="IsW9CheckingEnabled">IsW9CheckingEnabled</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsW9CheckingEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OurAccountNumber name="OurAccountNumber">OurAccountNumber</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OurAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NAFCode name="NAFCode">NAFCode</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NAFCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorInvoiceDeclarationId name="VendorInvoiceDeclarationId">VendorInvoiceDeclarationId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorInvoiceDeclarationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentTransactionCode name="PaymentTransactionCode">PaymentTransactionCode</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentTransactionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainContactPersonnelNumber name="MainContactPersonnelNumber">MainContactPersonnelNumber</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Employee responsible</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainContactPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Employee responsible</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099BoxId name="Tax1099BoxId">Tax1099BoxId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099BoxId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099Type name="Tax1099Type">Tax1099Type</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099Type attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorExceptionGroupId name="VendorExceptionGroupId">VendorExceptionGroupId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorExceptionGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLedgerDimensionDisplayValue name="DefaultLedgerDimensionDisplayValue">DefaultLedgerDimensionDisplayValue</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

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

### <a href=#DefaultOffsetLedgerAccountDisplayValue name="DefaultOffsetLedgerAccountDisplayValue">DefaultOffsetLedgerAccountDisplayValue</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultOffsetLedgerAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressBooks name="AddressBooks">AddressBooks</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressBooks attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressDescription name="AddressDescription">AddressDescription</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCity name="AddressCity">AddressCity</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCountryRegionId name="AddressCountryRegionId">AddressCountryRegionId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCountyId name="AddressCountyId">AddressCountyId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCountyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressDistrictName name="AddressDistrictName">AddressDistrictName</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressDistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressLatitude name="AddressLatitude">AddressLatitude</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressLatitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressLocationId name="AddressLocationId">AddressLocationId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressLocationRoles name="AddressLocationRoles">AddressLocationRoles</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressLocationRoles attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressLongitude name="AddressLongitude">AddressLongitude</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressLongitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressStateId name="AddressStateId">AddressStateId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressStreet name="AddressStreet">AddressStreet</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressBuildingCompliment name="AddressBuildingCompliment">AddressBuildingCompliment</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressBuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressStreetNumber name="AddressStreetNumber">AddressStreetNumber</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressStreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressTimeZone name="AddressTimeZone">AddressTimeZone</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressTimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressValidFrom name="AddressValidFrom">AddressValidFrom</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressValidTo name="AddressValidTo">AddressValidTo</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressZipCode name="AddressZipCode">AddressZipCode</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCountryRegionISOCode name="AddressCountryRegionISOCode">AddressCountryRegionISOCode</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCountryRegionISOCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressPostBox name="AddressPostBox">AddressPostBox</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressPostBox attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCityInKana name="AddressCityInKana">AddressCityInKana</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCityInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressStreetInKana name="AddressStreetInKana">AddressStreetInKana</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressStreetInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressBrazilianCNPJOrCPF name="AddressBrazilianCNPJOrCPF">AddressBrazilianCNPJOrCPF</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressBrazilianCNPJOrCPF attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressBrazilianIE name="AddressBrazilianIE">AddressBrazilianIE</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressBrazilianIE attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormattedPrimaryAddress name="FormattedPrimaryAddress">FormattedPrimaryAddress</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormattedPrimaryAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorKnownAsName name="VendorKnownAsName">VendorKnownAsName</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorKnownAsName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

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

### <a href=#VendorOrganizationName name="VendorOrganizationName">VendorOrganizationName</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorOrganizationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorSearchName name="VendorSearchName">VendorSearchName</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorSearchName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationABCCode name="OrganizationABCCode">OrganizationABCCode</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationABCCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationNumber name="OrganizationNumber">OrganizationNumber</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationEmployeeAmount name="OrganizationEmployeeAmount">OrganizationEmployeeAmount</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationEmployeeAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationPhoneticName name="OrganizationPhoneticName">OrganizationPhoneticName</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationPhoneticName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorPartyNumber name="VendorPartyNumber">VendorPartyNumber</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorPartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorPartyType name="VendorPartyType">VendorPartyType</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorPartyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonAnniversaryDay name="PersonAnniversaryDay">PersonAnniversaryDay</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonAnniversaryDay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonAnniversaryMonth name="PersonAnniversaryMonth">PersonAnniversaryMonth</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonAnniversaryMonth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonAnniversaryYear name="PersonAnniversaryYear">PersonAnniversaryYear</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonAnniversaryYear attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonBirthDay name="PersonBirthDay">PersonBirthDay</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonBirthDay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonBirthMonth name="PersonBirthMonth">PersonBirthMonth</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonBirthMonth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonBirthYear name="PersonBirthYear">PersonBirthYear</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonBirthYear attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonChildrenNames name="PersonChildrenNames">PersonChildrenNames</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonChildrenNames attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonGender name="PersonGender">PersonGender</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonGender attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonHobbies name="PersonHobbies">PersonHobbies</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonHobbies attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonFirstName name="PersonFirstName">PersonFirstName</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonFirstName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonMiddleName name="PersonMiddleName">PersonMiddleName</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonMiddleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonLastNamePrefix name="PersonLastNamePrefix">PersonLastNamePrefix</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonLastNamePrefix attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonLastName name="PersonLastName">PersonLastName</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonLastName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonInitials name="PersonInitials">PersonInitials</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonInitials attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonMaritalStatus name="PersonMaritalStatus">PersonMaritalStatus</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonMaritalStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonPersonalSuffix name="PersonPersonalSuffix">PersonPersonalSuffix</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Personal suffix</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonPersonalSuffix attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Personal suffix</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonPersonalTitle name="PersonPersonalTitle">PersonPersonalTitle</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Personal title</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonPersonalTitle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Personal title</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonPhoneticFirstName name="PersonPhoneticFirstName">PersonPhoneticFirstName</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonPhoneticFirstName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonPhoneticLastName name="PersonPhoneticLastName">PersonPhoneticLastName</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonPhoneticLastName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonPhoneticMiddleName name="PersonPhoneticMiddleName">PersonPhoneticMiddleName</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonPhoneticMiddleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonProfessionalSuffix name="PersonProfessionalSuffix">PersonProfessionalSuffix</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonProfessionalSuffix attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonProfessionalTitle name="PersonProfessionalTitle">PersonProfessionalTitle</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonProfessionalTitle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryEmailAddress name="PrimaryEmailAddress">PrimaryEmailAddress</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryEmailAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryEmailAddressDescription name="PrimaryEmailAddressDescription">PrimaryEmailAddressDescription</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryEmailAddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrimaryEmailAddressIMEnabled name="IsPrimaryEmailAddressIMEnabled">IsPrimaryEmailAddressIMEnabled</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrimaryEmailAddressIMEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryEmailAddressPurpose name="PrimaryEmailAddressPurpose">PrimaryEmailAddressPurpose</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryEmailAddressPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryFaxNumber name="PrimaryFaxNumber">PrimaryFaxNumber</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryFaxNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryFaxNumberDescription name="PrimaryFaxNumberDescription">PrimaryFaxNumberDescription</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryFaxNumberDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryFaxNumberExtension name="PrimaryFaxNumberExtension">PrimaryFaxNumberExtension</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryFaxNumberExtension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryFaxNumberPurpose name="PrimaryFaxNumberPurpose">PrimaryFaxNumberPurpose</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryFaxNumberPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryPhoneNumber name="PrimaryPhoneNumber">PrimaryPhoneNumber</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryPhoneNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryPhoneNumberDescription name="PrimaryPhoneNumberDescription">PrimaryPhoneNumberDescription</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryPhoneNumberDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrimaryPhoneNumberMobile name="IsPrimaryPhoneNumberMobile">IsPrimaryPhoneNumberMobile</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrimaryPhoneNumberMobile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryPhoneNumberPurpose name="PrimaryPhoneNumberPurpose">PrimaryPhoneNumberPurpose</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryPhoneNumberPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryTelex name="PrimaryTelex">PrimaryTelex</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryTelex attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryTelexDescription name="PrimaryTelexDescription">PrimaryTelexDescription</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryTelexDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryTelexPurpose name="PrimaryTelexPurpose">PrimaryTelexPurpose</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryTelexPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryURL name="PrimaryURL">PrimaryURL</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryURL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryURLDescription name="PrimaryURLDescription">PrimaryURLDescription</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryURLDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryURLPurpose name="PrimaryURLPurpose">PrimaryURLPurpose</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryURLPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryFacebook name="PrimaryFacebook">PrimaryFacebook</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryFacebook attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryFacebookDescription name="PrimaryFacebookDescription">PrimaryFacebookDescription</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryFacebookDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryFacebookPurpose name="PrimaryFacebookPurpose">PrimaryFacebookPurpose</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryFacebookPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryLinkedIn name="PrimaryLinkedIn">PrimaryLinkedIn</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryLinkedIn attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryLinkedInDescription name="PrimaryLinkedInDescription">PrimaryLinkedInDescription</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryLinkedInDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryLinkedInPurpose name="PrimaryLinkedInPurpose">PrimaryLinkedInPurpose</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryLinkedInPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryTwitter name="PrimaryTwitter">PrimaryTwitter</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryTwitter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryTwitterDescription name="PrimaryTwitterDescription">PrimaryTwitterDescription</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryTwitterDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryTwitterPurpose name="PrimaryTwitterPurpose">PrimaryTwitterPurpose</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryTwitterPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillPurchaseOrderProcessingSummaryUpdatePurchaseOrder name="WillPurchaseOrderProcessingSummaryUpdatePurchaseOrder">WillPurchaseOrderProcessingSummaryUpdatePurchaseOrder</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use automatic summary for posting purchase orders</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillPurchaseOrderProcessingSummaryUpdatePurchaseOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use automatic summary for posting purchase orders</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProductReceiptProcessingSummaryUpdatePurchaseOrder name="WillProductReceiptProcessingSummaryUpdatePurchaseOrder">WillProductReceiptProcessingSummaryUpdatePurchaseOrder</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use automatic summary for posting purchase order packing slips</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProductReceiptProcessingSummaryUpdatePurchaseOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use automatic summary for posting purchase order packing slips</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillReceiptsListProcessingSummaryUpdatePurchaseOrder name="WillReceiptsListProcessingSummaryUpdatePurchaseOrder">WillReceiptsListProcessingSummaryUpdatePurchaseOrder</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use automatic summary for posting purchase order receipts lists</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillReceiptsListProcessingSummaryUpdatePurchaseOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use automatic summary for posting purchase order receipts lists</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillInvoiceProcessingSummaryUpdatePurchaseOrder name="WillInvoiceProcessingSummaryUpdatePurchaseOrder">WillInvoiceProcessingSummaryUpdatePurchaseOrder</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use automatic summary for posting purchase order invoices</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillInvoiceProcessingSummaryUpdatePurchaseOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use automatic summary for posting purchase order invoices</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCUSIPIdentificationNumberApplicable name="IsCUSIPIdentificationNumberApplicable">IsCUSIPIdentificationNumberApplicable</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCUSIPIdentificationNumberApplicable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CUSIPIdentificationNumber name="CUSIPIdentificationNumber">CUSIPIdentificationNumber</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CUSIPIdentificationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CUSIPDetails name="CUSIPDetails">CUSIPDetails</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CUSIPDetails attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OIDInvestorType name="OIDInvestorType">OIDInvestorType</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OIDInvestorType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OIDNomineeDetails name="OIDNomineeDetails">OIDNomineeDetails</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OIDNomineeDetails attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ISNationalRegistryNumber name="ISNationalRegistryNumber">ISNationalRegistryNumber</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ISNationalRegistryNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WithholdingTaxVendorType name="WithholdingTaxVendorType">WithholdingTaxVendorType</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingTaxVendorType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrderConsolidationDayOfMonth name="PurchaseOrderConsolidationDayOfMonth">PurchaseOrderConsolidationDayOfMonth</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderConsolidationDayOfMonth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentFeeGroupId name="PaymentFeeGroupId">PaymentFeeGroupId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentFeeGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsVendorPayingBankPaymentFee name="IsVendorPayingBankPaymentFee">IsVendorPayingBankPaymentFee</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsVendorPayingBankPaymentFee attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BrazilianCCM name="BrazilianCCM">BrazilianCCM</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BrazilianCCM attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BrazilianCNPJOrCPF name="BrazilianCNPJOrCPF">BrazilianCNPJOrCPF</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BrazilianCNPJOrCPF attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BrazilianCNAE name="BrazilianCNAE">BrazilianCNAE</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BrazilianCNAE attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForeignerId name="ForeignerId">ForeignerId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForeignerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BrazilianIE name="BrazilianIE">BrazilianIE</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BrazilianIE attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BrazilianNIT name="BrazilianNIT">BrazilianNIT</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BrazilianNIT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalOperationPresenceType name="FiscalOperationPresenceType">FiscalOperationPresenceType</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalOperationPresenceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsServiceDeliveryAddressBased name="IsServiceDeliveryAddressBased">IsServiceDeliveryAddressBased</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsServiceDeliveryAddressBased attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPurchaseConsumed name="IsPurchaseConsumed">IsPurchaseConsumed</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPurchaseConsumed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BrazilianINSSCEI name="BrazilianINSSCEI">BrazilianINSSCEI</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BrazilianINSSCEI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIncomingFiscalDocumentGenerated name="IsIncomingFiscalDocumentGenerated">IsIncomingFiscalDocumentGenerated</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIncomingFiscalDocumentGenerated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsICMSContributor name="IsICMSContributor">IsICMSContributor</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsICMSContributor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompositionScheme name="CompositionScheme">CompositionScheme</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompositionScheme attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForeignVendor name="ForeignVendor">ForeignVendor</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForeignVendor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GTAVendor name="GTAVendor">GTAVendor</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GTAVendor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PreferentialVendor name="PreferentialVendor">PreferentialVendor</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreferentialVendor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SSIVendor name="SSIVendor">SSIVendor</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SSIVendor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NatureOfAssessee name="NatureOfAssessee">NatureOfAssessee</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NatureOfAssessee attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PANNumber name="PANNumber">PANNumber</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PANNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PANReferenceNumber name="PANReferenceNumber">PANReferenceNumber</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PANReferenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PANStatus name="PANStatus">PANStatus</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PANStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SSIValidityDate name="SSIValidityDate">SSIValidityDate</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SSIValidityDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TCSGroup name="TCSGroup">TCSGroup</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TCSGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TDSGroup name="TDSGroup">TDSGroup</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TDSGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorPortalCollaborationMethod name="VendorPortalCollaborationMethod">VendorPortalCollaborationMethod</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorPortalCollaborationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryPhoneNumberExtension name="PrimaryPhoneNumberExtension">PrimaryPhoneNumberExtension</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryPhoneNumberExtension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ZakatRegistrationNumber name="ZakatRegistrationNumber">ZakatRegistrationNumber</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ZakatRegistrationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ZakatFileNumber name="ZakatFileNumber">ZakatFileNumber</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ZakatFileNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSubcontractor name="IsSubcontractor">IsSubcontractor</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSubcontractor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ZakatServiceType name="ZakatServiceType">ZakatServiceType</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ZakatServiceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicLocationId name="ElectronicLocationId">ElectronicLocationId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorPaymentFineCode name="VendorPaymentFineCode">VendorPaymentFineCode</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorPaymentFineCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorPaymentFinancialInterestCode name="VendorPaymentFinancialInterestCode">VendorPaymentFinancialInterestCode</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorPaymentFinancialInterestCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BirthPlace name="BirthPlace">BirthPlace</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BirthPlace attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BirthCountyCode name="BirthCountyCode">BirthCountyCode</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BirthCountyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResidenceForeignCountryRegionId name="ResidenceForeignCountryRegionId">ResidenceForeignCountryRegionId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResidenceForeignCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentIncomeCode name="FiscalDocumentIncomeCode">FiscalDocumentIncomeCode</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentIncomeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DUNSNumber name="DUNSNumber">DUNSNumber</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DUNSNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsGSTCompositionSchemeEnabled name="IsGSTCompositionSchemeEnabled">IsGSTCompositionSchemeEnabled</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsGSTCompositionSchemeEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankTransactionType name="BankTransactionType">BankTransactionType</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankTransactionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankOrderOfPayment name="BankOrderOfPayment">BankOrderOfPayment</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankOrderOfPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForeignResident name="ForeignResident">ForeignResident</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForeignResident attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryProfile name="InventoryProfile">InventoryProfile</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

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

### <a href=#InventoryProfileType name="InventoryProfileType">InventoryProfileType</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryProfileType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SeparateDivisionId name="SeparateDivisionId">SeparateDivisionId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SeparateDivisionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StructureDepartment name="StructureDepartment">StructureDepartment</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StructureDepartment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxOperationCode name="TaxOperationCode">TaxOperationCode</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxOperationCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxPartnerKind name="TaxPartnerKind">TaxPartnerKind</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPartnerKind attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAgent name="TaxAgent">TaxAgent</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAgent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFaxRecordId name="PrimaryContactFaxRecordId">PrimaryContactFaxRecordId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFaxRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactPhoneRecordId name="PrimaryContactPhoneRecordId">PrimaryContactPhoneRecordId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactPhoneRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactEmailRecordId name="PrimaryContactEmailRecordId">PrimaryContactEmailRecordId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactEmailRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactURLRecordId name="PrimaryContactURLRecordId">PrimaryContactURLRecordId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactURLRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressRecordId name="AddressRecordId">AddressRecordId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

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

### <a href=#Relationship_OffsetLedgerDimensionCombinationRelationshipId name="Relationship_OffsetLedgerDimensionCombinationRelationshipId">Relationship_OffsetLedgerDimensionCombinationRelationshipId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OffsetLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_VendTableRelationshipId name="BackingTable_VendTableRelationshipId">BackingTable_VendTableRelationshipId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_VendTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Vendor/Main/VendTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../../Tables/SupplyChain/Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/VendVendorV2Entity (this entity)  

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
