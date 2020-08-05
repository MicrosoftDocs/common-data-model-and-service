---
title: CustCustomerDetailV2Entity in AccountsReceivable - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Customer details V2 in AccountsReceivable(CustCustomerDetailV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/CustCustomerDetailV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Customer details V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CustomerAccount](#CustomerAccount)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[IsOneTimeCustomer](#IsOneTimeCustomer)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[StatisticsGroupId](#StatisticsGroupId)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[AccountStatement](#AccountStatement)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[IdentificationNumber](#IdentificationNumber)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[VendorAccount](#VendorAccount)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[FederalIndicator](#FederalIndicator)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[FederalAgencyLocationCode](#FederalAgencyLocationCode)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[FederalComments](#FederalComments)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[IRS1099CIndicator](#IRS1099CIndicator)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[ContactPersonId](#ContactPersonId)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[LineOfBusinessId](#LineOfBusinessId)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[EmployeeResponsibleNumber](#EmployeeResponsibleNumber)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[MainContactWorker](#MainContactWorker)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[SalesSegmentId](#SalesSegmentId)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[SalesSubsegmentId](#SalesSubsegmentId)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[SalesDistrict](#SalesDistrict)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[CompanyChain](#CompanyChain)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[SalesMemo](#SalesMemo)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[OnHoldStatus](#OnHoldStatus)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[CreditLimitIsMandatory](#CreditLimitIsMandatory)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[CreditRating](#CreditRating)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[CreditLimit](#CreditLimit)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[CollectionsContactPersonId](#CollectionsContactPersonId)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[IsExcludedFromInterestChargeCalculation](#IsExcludedFromInterestChargeCalculation)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[IsExcludedFromCollectionFeeCalculation](#IsExcludedFromCollectionFeeCalculation)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[ChargesGroupId](#ChargesGroupId)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[SiteId](#SiteId)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[WarehouseId](#WarehouseId)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[ItemCustomerGroupId](#ItemCustomerGroupId)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[CommissionCustomerGroupId](#CommissionCustomerGroupId)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[CommissionSalesGroupId](#CommissionSalesGroupId)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[SalesOrderPoolId](#SalesOrderPoolId)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[SalesAccountNumber](#SalesAccountNumber)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[OrderEntryDeadline](#OrderEntryDeadline)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[MultiLineDiscountCode](#MultiLineDiscountCode)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[TotalDiscountCode](#TotalDiscountCode)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[DiscountPriceGroupId](#DiscountPriceGroupId)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[LineDiscountCode](#LineDiscountCode)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[CustomerRebateGroupId](#CustomerRebateGroupId)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[CustomerTMAGroupId](#CustomerTMAGroupId)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[SupplementaryItemGroupId](#SupplementaryItemGroupId)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[PaymentTerms](#PaymentTerms)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[PaymentMethod](#PaymentMethod)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[PaymentSpecification](#PaymentSpecification)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[PaymentSchedule](#PaymentSchedule)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[PaymentDay](#PaymentDay)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[PaymentCashDiscount](#PaymentCashDiscount)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[PaymentTermsBaseDays](#PaymentTermsBaseDays)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[PaymentBankAccount](#PaymentBankAccount)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[PaymentFactoringAccount](#PaymentFactoringAccount)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[PaymentIdType](#PaymentIdType)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[PaymentUseCashDiscount](#PaymentUseCashDiscount)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[CentralBankPurposeCode](#CentralBankPurposeCode)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[CentralBankPurposeNotes](#CentralBankPurposeNotes)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[CreditCardAddressVerification](#CreditCardAddressVerification)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[CreditCardAddressVerificationIsAuthorizationVoidedOnFailure](#CreditCardAddressVerificationIsAuthorizationVoidedOnFailure)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[CreditCardAddressVerificationLevel](#CreditCardAddressVerificationLevel)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[CreditCardCVC](#CreditCardCVC)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[WarehouseIsASNGenerated](#WarehouseIsASNGenerated)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[WarehouseIsEntireShipmentFilled](#WarehouseIsEntireShipmentFilled)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[DefaultInventoryStatusId](#DefaultInventoryStatusId)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[InvoiceAccount](#InvoiceAccount)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[InvoiceAddress](#InvoiceAddress)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[NumberSequenceGroup](#NumberSequenceGroup)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[GiroType](#GiroType)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[GiroTypeFreeTextInvoice](#GiroTypeFreeTextInvoice)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[GiroTypeInterestNote](#GiroTypeInterestNote)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[GiroTypeCollectionletter](#GiroTypeCollectionletter)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[GiroTypeProjInvoice](#GiroTypeProjInvoice)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[GiroTypeAccountStatement](#GiroTypeAccountStatement)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[DeliveryFreightZone](#DeliveryFreightZone)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[DeliveryTerms](#DeliveryTerms)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[DeliveryMode](#DeliveryMode)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[DeliveryReason](#DeliveryReason)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[DestinationCode](#DestinationCode)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[ReceiptCalendar](#ReceiptCalendar)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[IsFuelSurchargeApplied](#IsFuelSurchargeApplied)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[SalesTaxGroup](#SalesTaxGroup)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[TaxExemptNumber](#TaxExemptNumber)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[IsSalesTaxIncludedInPrices](#IsSalesTaxIncludedInPrices)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[PackingDutyLicense](#PackingDutyLicense)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[FiscalCode](#FiscalCode)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[PackingMaterialFeeLicenseNumber](#PackingMaterialFeeLicenseNumber)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[IsElectronicInvoice](#IsElectronicInvoice)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[ElectronicInvoiceEAN](#ElectronicInvoiceEAN)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[IsFreightAccrued](#IsFreightAccrued)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[IsExpressBillOfLadingAccepted](#IsExpressBillOfLadingAccepted)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[IsTransactionPostedAsShipment](#IsTransactionPostedAsShipment)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[IsOrderNumberReferenceUsed](#IsOrderNumberReferenceUsed)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[SalesReturnTaxGroup](#SalesReturnTaxGroup)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[ReceiptEmail](#ReceiptEmail)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[ReceiptOption](#ReceiptOption)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[IsWithholdingTaxCalculated](#IsWithholdingTaxCalculated)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[WithholdingTaxGroupCode](#WithholdingTaxGroupCode)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[FrenchSiret](#FrenchSiret)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[CompanyType](#CompanyType)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[CURPNumber](#CURPNumber)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[RFCNumber](#RFCNumber)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[StateInscription](#StateInscription)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[TaxRegistrationId](#TaxRegistrationId)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[ConsolidationDay](#ConsolidationDay)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[NationalRegistryNumber](#NationalRegistryNumber)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[DefaultDimension](#DefaultDimension)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[CalculateWithholdingTax](#CalculateWithholdingTax)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[ForeignCustomer](#ForeignCustomer)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[TCSGroup](#TCSGroup)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[TDSGroup](#TDSGroup)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[PreferentialCustomer](#PreferentialCustomer)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[NatureOfAssessee](#NatureOfAssessee)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[PANNumber](#PANNumber)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[PANReferenceNumber](#PANReferenceNumber)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[PanStatus](#PanStatus)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[CustomerPaymentFineCode](#CustomerPaymentFineCode)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[CustomerPaymentFinancialInterestCode](#CustomerPaymentFinancialInterestCode)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[BrazilianCCM](#BrazilianCCM)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[BrazilianCNAE](#BrazilianCNAE)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[BrazilianCNPJOrCPF](#BrazilianCNPJOrCPF)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[IsFinalUser](#IsFinalUser)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[CustomerWithholdingContributionType](#CustomerWithholdingContributionType)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[IsIncomingFiscalDocumentGenerated](#IsIncomingFiscalDocumentGenerated)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[IsICMSContributor](#IsICMSContributor)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[BrazilianIE](#BrazilianIE)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[BrazilianINSSCEI](#BrazilianINSSCEI)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[BrazilianNIT](#BrazilianNIT)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[IsServiceDeliveryAddressBased](#IsServiceDeliveryAddressBased)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[IsInSuframaRegion](#IsInSuframaRegion)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[SuframaNumber](#SuframaNumber)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[HasSuframaDiscountPISandCOFINS](#HasSuframaDiscountPISandCOFINS)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[ForeignerId](#ForeignerId)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[TransactionPresenceType](#TransactionPresenceType)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[WriteOffCompany](#WriteOffCompany)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[WriteoffReason](#WriteoffReason)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[ExportSale](#ExportSale)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[BirthCountyCode](#BirthCountyCode)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[BirthPlace](#BirthPlace)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[ResidenceForeignCountryRegionId](#ResidenceForeignCountryRegionId)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[IsPurchRequestUsed](#IsPurchRequestUsed)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[NAFCodeId](#NAFCodeId)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[ReliefGroupId](#ReliefGroupId)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[NAFCode](#NAFCode)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[ReliefGroup](#ReliefGroup)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[FulfillmentPolicyName](#FulfillmentPolicyName)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[FulfillmentPolicy](#FulfillmentPolicy)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[IsAllowCreateIndirectOrderLines](#IsAllowCreateIndirectOrderLines)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[CollectionLetterCode](#CollectionLetterCode)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[Relationship_CustWriteOffSetupRelationshipId](#Relationship_CustWriteOffSetupRelationshipId)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[BackingTable_CustTableRelationshipId](#BackingTable_CustTableRelationshipId)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="CustCustomerDetailV2Entity.md" target="_blank">AccountsReceivable/CustCustomerDetailV2Entity</a>|

### <a href=#CustomerAccount name="CustomerAccount">CustomerAccount</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOneTimeCustomer name="IsOneTimeCustomer">IsOneTimeCustomer</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOneTimeCustomer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatisticsGroupId name="StatisticsGroupId">StatisticsGroupId</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatisticsGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountStatement name="AccountStatement">AccountStatement</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStatement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IdentificationNumber name="IdentificationNumber">IdentificationNumber</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IdentificationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAccount name="VendorAccount">VendorAccount</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FederalIndicator name="FederalIndicator">FederalIndicator</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FederalIndicator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FederalAgencyLocationCode name="FederalAgencyLocationCode">FederalAgencyLocationCode</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FederalAgencyLocationCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FederalComments name="FederalComments">FederalComments</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FederalComments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IRS1099CIndicator name="IRS1099CIndicator">IRS1099CIndicator</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IRS1099CIndicator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPersonId name="ContactPersonId">ContactPersonId</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#LineOfBusinessId name="LineOfBusinessId">LineOfBusinessId</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#EmployeeResponsibleNumber name="EmployeeResponsibleNumber">EmployeeResponsibleNumber</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Employee responsible</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmployeeResponsibleNumber attribute are listed below.</summary>

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

### <a href=#MainContactWorker name="MainContactWorker">MainContactWorker</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainContactWorker attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesSegmentId name="SalesSegmentId">SalesSegmentId</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesSegmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesSubsegmentId name="SalesSubsegmentId">SalesSubsegmentId</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesSubsegmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesDistrict name="SalesDistrict">SalesDistrict</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesDistrict attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyChain name="CompanyChain">CompanyChain</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyChain attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesMemo name="SalesMemo">SalesMemo</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesMemo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnHoldStatus name="OnHoldStatus">OnHoldStatus</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#CreditLimitIsMandatory name="CreditLimitIsMandatory">CreditLimitIsMandatory</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditLimitIsMandatory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditRating name="CreditRating">CreditRating</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#CreditLimit name="CreditLimit">CreditLimit</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#CollectionsContactPersonId name="CollectionsContactPersonId">CollectionsContactPersonId</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionsContactPersonId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsExcludedFromInterestChargeCalculation name="IsExcludedFromInterestChargeCalculation">IsExcludedFromInterestChargeCalculation</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExcludedFromInterestChargeCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsExcludedFromCollectionFeeCalculation name="IsExcludedFromCollectionFeeCalculation">IsExcludedFromCollectionFeeCalculation</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExcludedFromCollectionFeeCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargesGroupId name="ChargesGroupId">ChargesGroupId</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargesGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SiteId name="SiteId">SiteId</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseId name="WarehouseId">WarehouseId</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemCustomerGroupId name="ItemCustomerGroupId">ItemCustomerGroupId</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemCustomerGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CommissionCustomerGroupId name="CommissionCustomerGroupId">CommissionCustomerGroupId</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#CommissionSalesGroupId name="CommissionSalesGroupId">CommissionSalesGroupId</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommissionSalesGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderPoolId name="SalesOrderPoolId">SalesOrderPoolId</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#SalesAccountNumber name="SalesAccountNumber">SalesAccountNumber</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderEntryDeadline name="OrderEntryDeadline">OrderEntryDeadline</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderEntryDeadline attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MultiLineDiscountCode name="MultiLineDiscountCode">MultiLineDiscountCode</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MultiLineDiscountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountCode name="TotalDiscountCode">TotalDiscountCode</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountPriceGroupId name="DiscountPriceGroupId">DiscountPriceGroupId</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountPriceGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDiscountCode name="LineDiscountCode">LineDiscountCode</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDiscountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerRebateGroupId name="CustomerRebateGroupId">CustomerRebateGroupId</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerRebateGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerTMAGroupId name="CustomerTMAGroupId">CustomerTMAGroupId</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerTMAGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SupplementaryItemGroupId name="SupplementaryItemGroupId">SupplementaryItemGroupId</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SupplementaryItemGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentTerms name="PaymentTerms">PaymentTerms</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentTerms attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentMethod name="PaymentMethod">PaymentMethod</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentSpecification name="PaymentSpecification">PaymentSpecification</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentSpecification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentSchedule name="PaymentSchedule">PaymentSchedule</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentSchedule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentDay name="PaymentDay">PaymentDay</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentDay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentCashDiscount name="PaymentCashDiscount">PaymentCashDiscount</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentCashDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentTermsBaseDays name="PaymentTermsBaseDays">PaymentTermsBaseDays</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentTermsBaseDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentBankAccount name="PaymentBankAccount">PaymentBankAccount</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentBankAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentFactoringAccount name="PaymentFactoringAccount">PaymentFactoringAccount</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentFactoringAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentIdType name="PaymentIdType">PaymentIdType</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentIdType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentUseCashDiscount name="PaymentUseCashDiscount">PaymentUseCashDiscount</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentUseCashDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CentralBankPurposeCode name="CentralBankPurposeCode">CentralBankPurposeCode</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#CentralBankPurposeNotes name="CentralBankPurposeNotes">CentralBankPurposeNotes</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CentralBankPurposeNotes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditCardAddressVerification name="CreditCardAddressVerification">CreditCardAddressVerification</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardAddressVerification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditCardAddressVerificationIsAuthorizationVoidedOnFailure name="CreditCardAddressVerificationIsAuthorizationVoidedOnFailure">CreditCardAddressVerificationIsAuthorizationVoidedOnFailure</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardAddressVerificationIsAuthorizationVoidedOnFailure attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditCardAddressVerificationLevel name="CreditCardAddressVerificationLevel">CreditCardAddressVerificationLevel</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardAddressVerificationLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditCardCVC name="CreditCardCVC">CreditCardCVC</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardCVC attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseIsASNGenerated name="WarehouseIsASNGenerated">WarehouseIsASNGenerated</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseIsASNGenerated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseIsEntireShipmentFilled name="WarehouseIsEntireShipmentFilled">WarehouseIsEntireShipmentFilled</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseIsEntireShipmentFilled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultInventoryStatusId name="DefaultInventoryStatusId">DefaultInventoryStatusId</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#InvoiceAccount name="InvoiceAccount">InvoiceAccount</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddress name="InvoiceAddress">InvoiceAddress</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceGroup name="NumberSequenceGroup">NumberSequenceGroup</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiroType name="GiroType">GiroType</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiroType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiroTypeFreeTextInvoice name="GiroTypeFreeTextInvoice">GiroTypeFreeTextInvoice</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiroTypeFreeTextInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiroTypeInterestNote name="GiroTypeInterestNote">GiroTypeInterestNote</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiroTypeInterestNote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiroTypeCollectionletter name="GiroTypeCollectionletter">GiroTypeCollectionletter</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiroTypeCollectionletter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiroTypeProjInvoice name="GiroTypeProjInvoice">GiroTypeProjInvoice</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiroTypeProjInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiroTypeAccountStatement name="GiroTypeAccountStatement">GiroTypeAccountStatement</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiroTypeAccountStatement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryFreightZone name="DeliveryFreightZone">DeliveryFreightZone</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryFreightZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryTerms name="DeliveryTerms">DeliveryTerms</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryTerms attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryMode name="DeliveryMode">DeliveryMode</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryReason name="DeliveryReason">DeliveryReason</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryReason attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationCode name="DestinationCode">DestinationCode</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#ReceiptCalendar name="ReceiptCalendar">ReceiptCalendar</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFuelSurchargeApplied name="IsFuelSurchargeApplied">IsFuelSurchargeApplied</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFuelSurchargeApplied attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroup name="SalesTaxGroup">SalesTaxGroup</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxExemptNumber name="TaxExemptNumber">TaxExemptNumber</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#IsSalesTaxIncludedInPrices name="IsSalesTaxIncludedInPrices">IsSalesTaxIncludedInPrices</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesTaxIncludedInPrices attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackingDutyLicense name="PackingDutyLicense">PackingDutyLicense</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingDutyLicense attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCode name="FiscalCode">FiscalCode</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#PackingMaterialFeeLicenseNumber name="PackingMaterialFeeLicenseNumber">PackingMaterialFeeLicenseNumber</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingMaterialFeeLicenseNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsElectronicInvoice name="IsElectronicInvoice">IsElectronicInvoice</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsElectronicInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicInvoiceEAN name="ElectronicInvoiceEAN">ElectronicInvoiceEAN</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicInvoiceEAN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFreightAccrued name="IsFreightAccrued">IsFreightAccrued</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFreightAccrued attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsExpressBillOfLadingAccepted name="IsExpressBillOfLadingAccepted">IsExpressBillOfLadingAccepted</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExpressBillOfLadingAccepted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTransactionPostedAsShipment name="IsTransactionPostedAsShipment">IsTransactionPostedAsShipment</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTransactionPostedAsShipment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOrderNumberReferenceUsed name="IsOrderNumberReferenceUsed">IsOrderNumberReferenceUsed</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOrderNumberReferenceUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesReturnTaxGroup name="SalesReturnTaxGroup">SalesReturnTaxGroup</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesReturnTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptEmail name="ReceiptEmail">ReceiptEmail</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptEmail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptOption name="ReceiptOption">ReceiptOption</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptOption attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWithholdingTaxCalculated name="IsWithholdingTaxCalculated">IsWithholdingTaxCalculated</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#WithholdingTaxGroupCode name="WithholdingTaxGroupCode">WithholdingTaxGroupCode</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#FrenchSiret name="FrenchSiret">FrenchSiret</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FrenchSiret attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyType name="CompanyType">CompanyType</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#CURPNumber name="CURPNumber">CURPNumber</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CURPNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFCNumber name="RFCNumber">RFCNumber</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFCNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StateInscription name="StateInscription">StateInscription</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#TaxRegistrationId name="TaxRegistrationId">TaxRegistrationId</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRegistrationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsolidationDay name="ConsolidationDay">ConsolidationDay</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsolidationDay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NationalRegistryNumber name="NationalRegistryNumber">NationalRegistryNumber</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NationalRegistryNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#DefaultDimensionDisplayValue name="DefaultDimensionDisplayValue">DefaultDimensionDisplayValue</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#CalculateWithholdingTax name="CalculateWithholdingTax">CalculateWithholdingTax</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculateWithholdingTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForeignCustomer name="ForeignCustomer">ForeignCustomer</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForeignCustomer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TCSGroup name="TCSGroup">TCSGroup</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#PreferentialCustomer name="PreferentialCustomer">PreferentialCustomer</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreferentialCustomer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NatureOfAssessee name="NatureOfAssessee">NatureOfAssessee</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#PanStatus name="PanStatus">PanStatus</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PanStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerPaymentFineCode name="CustomerPaymentFineCode">CustomerPaymentFineCode</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#BrazilianCCM name="BrazilianCCM">BrazilianCCM</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#BrazilianCNAE name="BrazilianCNAE">BrazilianCNAE</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#BrazilianCNPJOrCPF name="BrazilianCNPJOrCPF">BrazilianCNPJOrCPF</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#IsFinalUser name="IsFinalUser">IsFinalUser</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFinalUser attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerWithholdingContributionType name="CustomerWithholdingContributionType">CustomerWithholdingContributionType</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerWithholdingContributionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIncomingFiscalDocumentGenerated name="IsIncomingFiscalDocumentGenerated">IsIncomingFiscalDocumentGenerated</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#BrazilianIE name="BrazilianIE">BrazilianIE</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#BrazilianINSSCEI name="BrazilianINSSCEI">BrazilianINSSCEI</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#BrazilianNIT name="BrazilianNIT">BrazilianNIT</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#IsServiceDeliveryAddressBased name="IsServiceDeliveryAddressBased">IsServiceDeliveryAddressBased</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#IsInSuframaRegion name="IsInSuframaRegion">IsInSuframaRegion</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInSuframaRegion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SuframaNumber name="SuframaNumber">SuframaNumber</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SuframaNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HasSuframaDiscountPISandCOFINS name="HasSuframaDiscountPISandCOFINS">HasSuframaDiscountPISandCOFINS</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HasSuframaDiscountPISandCOFINS attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForeignerId name="ForeignerId">ForeignerId</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#TransactionPresenceType name="TransactionPresenceType">TransactionPresenceType</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionPresenceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WriteOffCompany name="WriteOffCompany">WriteOffCompany</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WriteOffCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WriteoffReason name="WriteoffReason">WriteoffReason</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WriteoffReason attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExportSale name="ExportSale">ExportSale</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExportSale attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BirthCountyCode name="BirthCountyCode">BirthCountyCode</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#BirthPlace name="BirthPlace">BirthPlace</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#ResidenceForeignCountryRegionId name="ResidenceForeignCountryRegionId">ResidenceForeignCountryRegionId</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#IsPurchRequestUsed name="IsPurchRequestUsed">IsPurchRequestUsed</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPurchRequestUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NAFCodeId name="NAFCodeId">NAFCodeId</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NAFCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReliefGroupId name="ReliefGroupId">ReliefGroupId</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReliefGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NAFCode name="NAFCode">NAFCode</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#ReliefGroup name="ReliefGroup">ReliefGroup</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReliefGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FulfillmentPolicyName name="FulfillmentPolicyName">FulfillmentPolicyName</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FulfillmentPolicyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FulfillmentPolicy name="FulfillmentPolicy">FulfillmentPolicy</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FulfillmentPolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAllowCreateIndirectOrderLines name="IsAllowCreateIndirectOrderLines">IsAllowCreateIndirectOrderLines</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAllowCreateIndirectOrderLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectionLetterCode name="CollectionLetterCode">CollectionLetterCode</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionLetterCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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

### <a href=#Relationship_CustWriteOffSetupRelationshipId name="Relationship_CustWriteOffSetupRelationshipId">Relationship_CustWriteOffSetupRelationshipId</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustWriteOffSetupRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_CustTableRelationshipId name="BackingTable_CustTableRelationshipId">BackingTable_CustTableRelationshipId</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CustTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Common/Customer/Main/CustTable.md" target="_blank">/core/operationsCommon/Tables/Common/Customer/Main/CustTable.cdm.json/CustTable</a></td><td><a href="../../../Tables/Common/Customer/Main/CustTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsReceivable/CustCustomerDetailV2Entity (this entity)  

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
