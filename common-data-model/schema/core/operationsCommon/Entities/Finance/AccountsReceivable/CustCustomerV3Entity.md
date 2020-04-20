---
title: CustCustomerV3Entity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# CustCustomerV3Entity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/CustCustomerV3Entity.cdm.json" target="_blank">GitHub</a>.  

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
|[CustomerAccount](#CustomerAccount)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PartyType](#PartyType)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[OrganizationName](#OrganizationName)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[NameAlias](#NameAlias)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[KnownAs](#KnownAs)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CustomerGroupId](#CustomerGroupId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[OrganizationNumber](#OrganizationNumber)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[OrganizationNumberOfEmployees](#OrganizationNumberOfEmployees)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[OrganizationABCCode](#OrganizationABCCode)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[OrganizationPhoneticName](#OrganizationPhoneticName)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PersonInitials](#PersonInitials)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PersonFirstName](#PersonFirstName)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PersonMiddleName](#PersonMiddleName)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PersonLastNamePrefix](#PersonLastNamePrefix)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PersonLastName](#PersonLastName)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PersonProfessionalTitle](#PersonProfessionalTitle)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PersonProfessionalSuffix](#PersonProfessionalSuffix)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PersonPhoneticFirstName](#PersonPhoneticFirstName)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PersonPhoneticLastName](#PersonPhoneticLastName)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PersonPhoneticMiddleName](#PersonPhoneticMiddleName)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PersonGender](#PersonGender)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PersonMaritalStatus](#PersonMaritalStatus)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PersonAnniversaryDay](#PersonAnniversaryDay)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PersonAnniversaryMonth](#PersonAnniversaryMonth)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PersonAnniversaryYear](#PersonAnniversaryYear)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PersonChildrenNames](#PersonChildrenNames)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PersonHobbies](#PersonHobbies)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PartyNumber](#PartyNumber)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[AddressBooks](#AddressBooks)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[LanguageId](#LanguageId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[FullPrimaryAddress](#FullPrimaryAddress)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[AddressDescription](#AddressDescription)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[AddressZipCode](#AddressZipCode)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[AddressCity](#AddressCity)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[AddressCountryRegionId](#AddressCountryRegionId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[AddressCountryRegionISOCode](#AddressCountryRegionISOCode)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[AddressCounty](#AddressCounty)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[AddressDistrictName](#AddressDistrictName)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[AddressLatitude](#AddressLatitude)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[AddressLocationId](#AddressLocationId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[AddressLocationRoles](#AddressLocationRoles)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[AddressLongitude](#AddressLongitude)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[AddressState](#AddressState)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[AddressStreet](#AddressStreet)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[AddressStreetNumber](#AddressStreetNumber)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[AddressTimeZone](#AddressTimeZone)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[AddressBuildingComplement](#AddressBuildingComplement)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[AddressValidFrom](#AddressValidFrom)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[AddressValidTo](#AddressValidTo)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[AddressBrazilianCNPJOrCPF](#AddressBrazilianCNPJOrCPF)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[AddressBrazilianIE](#AddressBrazilianIE)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactEmail](#PrimaryContactEmail)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactEmailDescription](#PrimaryContactEmailDescription)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactEmailIsIM](#PrimaryContactEmailIsIM)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactEmailPurpose](#PrimaryContactEmailPurpose)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactFax](#PrimaryContactFax)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactFaxDescription](#PrimaryContactFaxDescription)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactFaxExtension](#PrimaryContactFaxExtension)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactFaxPurpose](#PrimaryContactFaxPurpose)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactPhone](#PrimaryContactPhone)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactPhoneDescription](#PrimaryContactPhoneDescription)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactPhoneExtension](#PrimaryContactPhoneExtension)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactPhoneIsMobile](#PrimaryContactPhoneIsMobile)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactPhonePurpose](#PrimaryContactPhonePurpose)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactTelex](#PrimaryContactTelex)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactTelexDescription](#PrimaryContactTelexDescription)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactTelexPurpose](#PrimaryContactTelexPurpose)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactURL](#PrimaryContactURL)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactURLDescription](#PrimaryContactURLDescription)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactURLPurpose](#PrimaryContactURLPurpose)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactFacebook](#PrimaryContactFacebook)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactFacebookDescription](#PrimaryContactFacebookDescription)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactFacebookPurpose](#PrimaryContactFacebookPurpose)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactLinkedIn](#PrimaryContactLinkedIn)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactLinkedInDescription](#PrimaryContactLinkedInDescription)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactLinkedInPurpose](#PrimaryContactLinkedInPurpose)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactTwitterDescription](#PrimaryContactTwitterDescription)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactTwitter](#PrimaryContactTwitter)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactTwitterPurpose](#PrimaryContactTwitterPurpose)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[IsOneTimeCustomer](#IsOneTimeCustomer)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[StatisticsGroupId](#StatisticsGroupId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[AccountStatement](#AccountStatement)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[IdentificationNumber](#IdentificationNumber)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PartyCountry](#PartyCountry)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PartyState](#PartyState)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[VendorAccount](#VendorAccount)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[FederalIndicator](#FederalIndicator)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[FederalAgencyLocationCode](#FederalAgencyLocationCode)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[FederalComments](#FederalComments)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[IRS1099CIndicator](#IRS1099CIndicator)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[ContactPersonId](#ContactPersonId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[LineOfBusinessId](#LineOfBusinessId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[EmployeeResponsibleNumber](#EmployeeResponsibleNumber)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[MainContactWorker](#MainContactWorker)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[SalesSegmentId](#SalesSegmentId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[SalesSubsegmentId](#SalesSubsegmentId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[SalesDistrict](#SalesDistrict)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CompanyChain](#CompanyChain)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[SalesCurrencyCode](#SalesCurrencyCode)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[SalesMemo](#SalesMemo)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[OnHoldStatus](#OnHoldStatus)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CreditLimitIsMandatory](#CreditLimitIsMandatory)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CreditRating](#CreditRating)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CreditLimit](#CreditLimit)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CollectionsContactPersonId](#CollectionsContactPersonId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[IsExcludedFromInterestChargeCalculation](#IsExcludedFromInterestChargeCalculation)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[IsExcludedFromCollectionFeeCalculation](#IsExcludedFromCollectionFeeCalculation)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[ChargesGroupId](#ChargesGroupId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[SiteId](#SiteId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[WarehouseId](#WarehouseId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[ItemCustomerGroupId](#ItemCustomerGroupId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CommissionCustomerGroupId](#CommissionCustomerGroupId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CommissionSalesGroupId](#CommissionSalesGroupId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[SalesOrderPoolId](#SalesOrderPoolId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[SalesAccountNumber](#SalesAccountNumber)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[OrderEntryDeadline](#OrderEntryDeadline)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[MultiLineDiscountCode](#MultiLineDiscountCode)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[TotalDiscountCode](#TotalDiscountCode)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DiscountPriceGroupId](#DiscountPriceGroupId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[LineDiscountCode](#LineDiscountCode)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CustomerRebateGroupId](#CustomerRebateGroupId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CustomerTMAGroupId](#CustomerTMAGroupId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[SupplementaryItemGroupId](#SupplementaryItemGroupId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PaymentTerms](#PaymentTerms)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PaymentMethod](#PaymentMethod)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PaymentSpecification](#PaymentSpecification)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PaymentSchedule](#PaymentSchedule)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PaymentDay](#PaymentDay)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PaymentCashDiscount](#PaymentCashDiscount)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PaymentTermsBaseDays](#PaymentTermsBaseDays)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PaymentBankAccount](#PaymentBankAccount)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PaymentFactoringAccount](#PaymentFactoringAccount)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PaymentIdType](#PaymentIdType)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PaymentUseCashDiscount](#PaymentUseCashDiscount)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CentralBankPurposeCode](#CentralBankPurposeCode)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CentralBankPurposeNotes](#CentralBankPurposeNotes)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CreditCardAddressVerification](#CreditCardAddressVerification)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CreditCardAddressVerificationIsAuthorizationVoidedOnFailure](#CreditCardAddressVerificationIsAuthorizationVoidedOnFailure)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CreditCardAddressVerificationLevel](#CreditCardAddressVerificationLevel)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CreditCardCVC](#CreditCardCVC)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[WarehouseIsASNGenerated](#WarehouseIsASNGenerated)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[WarehouseIsEntireShipmentFilled](#WarehouseIsEntireShipmentFilled)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DefaultInventoryStatusId](#DefaultInventoryStatusId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[InvoiceAccount](#InvoiceAccount)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[InvoiceAddress](#InvoiceAddress)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[NumberSequenceGroup](#NumberSequenceGroup)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[GiroType](#GiroType)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[GiroTypeFreeTextInvoice](#GiroTypeFreeTextInvoice)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[GiroTypeInterestNote](#GiroTypeInterestNote)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[GiroTypeCollectionletter](#GiroTypeCollectionletter)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[GiroTypeProjInvoice](#GiroTypeProjInvoice)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[GiroTypeAccountStatement](#GiroTypeAccountStatement)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DeliveryFreightZone](#DeliveryFreightZone)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DeliveryTerms](#DeliveryTerms)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DeliveryMode](#DeliveryMode)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DeliveryReason](#DeliveryReason)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DestinationCode](#DestinationCode)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[ReceiptCalendar](#ReceiptCalendar)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[IsFuelSurchargeApplied](#IsFuelSurchargeApplied)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[SalesTaxGroup](#SalesTaxGroup)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[TaxExemptNumber](#TaxExemptNumber)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[IsSalesTaxIncludedInPrices](#IsSalesTaxIncludedInPrices)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PackingDutyLicense](#PackingDutyLicense)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[FiscalCode](#FiscalCode)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PackingMaterialFeeLicenseNumber](#PackingMaterialFeeLicenseNumber)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[IsElectronicInvoice](#IsElectronicInvoice)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[ElectronicInvoiceEAN](#ElectronicInvoiceEAN)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[IsFreightAccrued](#IsFreightAccrued)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[IsExpressBillOfLadingAccepted](#IsExpressBillOfLadingAccepted)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[IsTransactionPostedAsShipment](#IsTransactionPostedAsShipment)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[IsOrderNumberReferenceUsed](#IsOrderNumberReferenceUsed)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[SalesReturnTaxGroup](#SalesReturnTaxGroup)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[ReceiptEmail](#ReceiptEmail)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[ReceiptOption](#ReceiptOption)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[IsWithholdingTaxCalculated](#IsWithholdingTaxCalculated)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[WithholdingTaxGroupCode](#WithholdingTaxGroupCode)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[FrenchSiret](#FrenchSiret)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[NAFCode](#NAFCode)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CompanyType](#CompanyType)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CURPNumber](#CURPNumber)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[RFCNumber](#RFCNumber)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[StateInscription](#StateInscription)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[TaxRegistrationId](#TaxRegistrationId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[ConsolidationDay](#ConsolidationDay)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[NationalRegistryNumber](#NationalRegistryNumber)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[ReliefGroupId](#ReliefGroupId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DefaultDimension](#DefaultDimension)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CalculateWithholdingTax](#CalculateWithholdingTax)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[ForeignCustomer](#ForeignCustomer)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[TCSGroup](#TCSGroup)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[TDSGroup](#TDSGroup)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PreferentialCustomer](#PreferentialCustomer)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[NatureOfAssessee](#NatureOfAssessee)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PANNumber](#PANNumber)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PANReferenceNumber](#PANReferenceNumber)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PanStatus](#PanStatus)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[ElectronicLocationId](#ElectronicLocationId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CustomerPaymentFineCode](#CustomerPaymentFineCode)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CustomerPaymentFinancialInterestCode](#CustomerPaymentFinancialInterestCode)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[BrazilianCCM](#BrazilianCCM)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[BrazilianCNAE](#BrazilianCNAE)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[BrazilianCNPJOrCPF](#BrazilianCNPJOrCPF)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[IsFinalUser](#IsFinalUser)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CustomerWithholdingContributionType](#CustomerWithholdingContributionType)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[IsIncomingFiscalDocumentGenerated](#IsIncomingFiscalDocumentGenerated)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[IsICMSContributor](#IsICMSContributor)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[BrazilianIE](#BrazilianIE)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[BrazilianINSSCEI](#BrazilianINSSCEI)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[BrazilianNIT](#BrazilianNIT)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[IsServiceDeliveryAddressBased](#IsServiceDeliveryAddressBased)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[IsInSuframaRegion](#IsInSuframaRegion)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[SuframaNumber](#SuframaNumber)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[HasSuframaDiscountPISandCOFINS](#HasSuframaDiscountPISandCOFINS)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[ForeignerId](#ForeignerId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[TransactionPresenceType](#TransactionPresenceType)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[WriteOffCompany](#WriteOffCompany)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[WriteoffReason](#WriteoffReason)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[ExportSale](#ExportSale)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[BirthCountyCode](#BirthCountyCode)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[BirthPlace](#BirthPlace)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[ResidenceForeignCountryRegionId](#ResidenceForeignCountryRegionId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[IsPurchRequestUsed](#IsPurchRequestUsed)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DeliveryAddressDescription](#DeliveryAddressDescription)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DeliveryAddressZipCode](#DeliveryAddressZipCode)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DeliveryAddressTimeZone](#DeliveryAddressTimeZone)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DeliveryAddressCity](#DeliveryAddressCity)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DeliveryAddressCountryRegionId](#DeliveryAddressCountryRegionId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DeliveryAddressCountryRegionISOCode](#DeliveryAddressCountryRegionISOCode)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DeliveryAddressCounty](#DeliveryAddressCounty)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DeliveryAddressDistrictName](#DeliveryAddressDistrictName)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DeliveryAddressLatitude](#DeliveryAddressLatitude)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DeliveryAddressLongitude](#DeliveryAddressLongitude)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DeliveryAddressLocationId](#DeliveryAddressLocationId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DeliveryAddressState](#DeliveryAddressState)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DeliveryAddressStreet](#DeliveryAddressStreet)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DeliveryAddressStreetNumber](#DeliveryAddressStreetNumber)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DeliveryAddressBuildingComplement](#DeliveryAddressBuildingComplement)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DeliveryAddressValidFrom](#DeliveryAddressValidFrom)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DeliveryAddressValidTo](#DeliveryAddressValidTo)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[InvoiceAddressDescription](#InvoiceAddressDescription)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[InvoiceAddressZipCode](#InvoiceAddressZipCode)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[InvoiceAddressTimeZone](#InvoiceAddressTimeZone)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[InvoiceAddressCity](#InvoiceAddressCity)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[InvoiceAddressCountryRegionId](#InvoiceAddressCountryRegionId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[InvoiceAddressCountryRegionISOCode](#InvoiceAddressCountryRegionISOCode)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[InvoiceAddressCounty](#InvoiceAddressCounty)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[InvoiceAddressDistrictName](#InvoiceAddressDistrictName)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[InvoiceAddressLatitude](#InvoiceAddressLatitude)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[InvoiceAddressLongitude](#InvoiceAddressLongitude)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[InvoiceAddressLocationId](#InvoiceAddressLocationId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[InvoiceAddressState](#InvoiceAddressState)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[InvoiceAddressStreet](#InvoiceAddressStreet)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[InvoiceAddressStreetNumber](#InvoiceAddressStreetNumber)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[InvoiceAddressBuildingComplement](#InvoiceAddressBuildingComplement)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[InvoiceAddressValidFrom](#InvoiceAddressValidFrom)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[InvoiceAddressValidTo](#InvoiceAddressValidTo)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[IsExternallyMaintained](#IsExternallyMaintained)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[MerchantID](#MerchantID)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DefaultECommerceOperator](#DefaultECommerceOperator)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CustomerType](#CustomerType)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[FulfillmentPolicyName](#FulfillmentPolicyName)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[FulfillmentPolicy](#FulfillmentPolicy)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[AddressPostbox](#AddressPostbox)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CustClassificationId](#CustClassificationId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[IsAllowCreateIndirectOrderLines](#IsAllowCreateIndirectOrderLines)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactEmailRecordId](#PrimaryContactEmailRecordId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactFaxRecordId](#PrimaryContactFaxRecordId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactPhoneRecordId](#PrimaryContactPhoneRecordId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PrimaryContactURLRecordId](#PrimaryContactURLRecordId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[AddressRecordId](#AddressRecordId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CollectionLetterCode](#CollectionLetterCode)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[EInvoiceRegister](#EInvoiceRegister)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[AuthorityOffice](#AuthorityOffice)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[EInvoiceAttachment](#EInvoiceAttachment)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[Priority](#Priority)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DeliveryAddressRecordId](#DeliveryAddressRecordId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[InvoiceAddressRecordId](#InvoiceAddressRecordId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[DirPartyLocationRecordId](#DirPartyLocationRecordId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[PartyRecordId](#PartyRecordId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[InvoicePostingType](#InvoicePostingType)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[ForeignResident](#ForeignResident)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[InterCompanyAutoCreateOrders](#InterCompanyAutoCreateOrders)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CredManAccountStatusId](#CredManAccountStatusId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CredManBusinessStarted](#CredManBusinessStarted)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CredManCollectionGroupId](#CredManCollectionGroupId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CredManCreditLimitDate](#CredManCreditLimitDate)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CredManCreditLimitExpiryDate](#CredManCreditLimitExpiryDate)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CredManCustCreditMaxAlt](#CredManCustCreditMaxAlt)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CredManCustomerSince](#CredManCustomerSince)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CredManEligibleCreditLimitCurrency](#CredManEligibleCreditLimitCurrency)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CredManEligibleCreditLimitDate](#CredManEligibleCreditLimitDate)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CredManEligibleCreditMax](#CredManEligibleCreditMax)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CredManExclude](#CredManExclude)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CredManGroupId](#CredManGroupId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CredManNotes](#CredManNotes)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CredManStatusReasonId](#CredManStatusReasonId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CredManTitleHeld](#CredManTitleHeld)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CredManWithAgency](#CredManWithAgency)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CredManLastReviewDate](#CredManLastReviewDate)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CredManNextSchedReviewDate](#CredManNextSchedReviewDate)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[CredManCustUnlimitedCredit](#CredManCustUnlimitedCredit)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[Relationship_CustWriteOffSetupRelationshipId](#Relationship_CustWriteOffSetupRelationshipId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[Relationship_CustClassificationGroupRelationshipId](#Relationship_CustClassificationGroupRelationshipId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[BackingTable_CustTableRelationshipId](#BackingTable_CustTableRelationshipId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="CustCustomerV3Entity.md" target="_blank">AccountsReceivable/CustCustomerV3Entity</a>|

### <a href=#CustomerAccount name="CustomerAccount">CustomerAccount</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#PartyType name="PartyType">PartyType</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationName name="OrganizationName">OrganizationName</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NameAlias name="NameAlias">NameAlias</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NameAlias attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KnownAs name="KnownAs">KnownAs</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KnownAs attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerGroupId name="CustomerGroupId">CustomerGroupId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationNumber name="OrganizationNumber">OrganizationNumber</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationNumberOfEmployees name="OrganizationNumberOfEmployees">OrganizationNumberOfEmployees</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationNumberOfEmployees attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationABCCode name="OrganizationABCCode">OrganizationABCCode</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationABCCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationPhoneticName name="OrganizationPhoneticName">OrganizationPhoneticName</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationPhoneticName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonInitials name="PersonInitials">PersonInitials</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonInitials attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonFirstName name="PersonFirstName">PersonFirstName</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonFirstName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonMiddleName name="PersonMiddleName">PersonMiddleName</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonMiddleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonLastNamePrefix name="PersonLastNamePrefix">PersonLastNamePrefix</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonLastNamePrefix attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonLastName name="PersonLastName">PersonLastName</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonLastName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonProfessionalTitle name="PersonProfessionalTitle">PersonProfessionalTitle</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonProfessionalTitle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonProfessionalSuffix name="PersonProfessionalSuffix">PersonProfessionalSuffix</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonProfessionalSuffix attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonPhoneticFirstName name="PersonPhoneticFirstName">PersonPhoneticFirstName</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonPhoneticFirstName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonPhoneticLastName name="PersonPhoneticLastName">PersonPhoneticLastName</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonPhoneticLastName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonPhoneticMiddleName name="PersonPhoneticMiddleName">PersonPhoneticMiddleName</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonPhoneticMiddleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonGender name="PersonGender">PersonGender</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonGender attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonMaritalStatus name="PersonMaritalStatus">PersonMaritalStatus</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonMaritalStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonAnniversaryDay name="PersonAnniversaryDay">PersonAnniversaryDay</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonAnniversaryDay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonAnniversaryMonth name="PersonAnniversaryMonth">PersonAnniversaryMonth</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonAnniversaryMonth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonAnniversaryYear name="PersonAnniversaryYear">PersonAnniversaryYear</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonAnniversaryYear attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonChildrenNames name="PersonChildrenNames">PersonChildrenNames</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonChildrenNames attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonHobbies name="PersonHobbies">PersonHobbies</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonHobbies attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PartyNumber name="PartyNumber">PartyNumber</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressBooks name="AddressBooks">AddressBooks</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressBooks attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#FullPrimaryAddress name="FullPrimaryAddress">FullPrimaryAddress</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FullPrimaryAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressDescription name="AddressDescription">AddressDescription</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressZipCode name="AddressZipCode">AddressZipCode</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCity name="AddressCity">AddressCity</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCountryRegionId name="AddressCountryRegionId">AddressCountryRegionId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCountryRegionISOCode name="AddressCountryRegionISOCode">AddressCountryRegionISOCode</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCountryRegionISOCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressCounty name="AddressCounty">AddressCounty</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressCounty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressDistrictName name="AddressDistrictName">AddressDistrictName</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressDistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressLatitude name="AddressLatitude">AddressLatitude</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressLatitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressLocationId name="AddressLocationId">AddressLocationId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressLocationRoles name="AddressLocationRoles">AddressLocationRoles</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressLocationRoles attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressLongitude name="AddressLongitude">AddressLongitude</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressLongitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressState name="AddressState">AddressState</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressStreet name="AddressStreet">AddressStreet</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressStreetNumber name="AddressStreetNumber">AddressStreetNumber</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressStreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressTimeZone name="AddressTimeZone">AddressTimeZone</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressTimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressBuildingComplement name="AddressBuildingComplement">AddressBuildingComplement</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressBuildingComplement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressValidFrom name="AddressValidFrom">AddressValidFrom</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressValidTo name="AddressValidTo">AddressValidTo</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressBrazilianCNPJOrCPF name="AddressBrazilianCNPJOrCPF">AddressBrazilianCNPJOrCPF</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressBrazilianCNPJOrCPF attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressBrazilianIE name="AddressBrazilianIE">AddressBrazilianIE</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressBrazilianIE attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactEmail name="PrimaryContactEmail">PrimaryContactEmail</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactEmail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactEmailDescription name="PrimaryContactEmailDescription">PrimaryContactEmailDescription</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactEmailDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactEmailIsIM name="PrimaryContactEmailIsIM">PrimaryContactEmailIsIM</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactEmailIsIM attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactEmailPurpose name="PrimaryContactEmailPurpose">PrimaryContactEmailPurpose</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactEmailPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFax name="PrimaryContactFax">PrimaryContactFax</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFaxDescription name="PrimaryContactFaxDescription">PrimaryContactFaxDescription</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFaxDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFaxExtension name="PrimaryContactFaxExtension">PrimaryContactFaxExtension</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFaxExtension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFaxPurpose name="PrimaryContactFaxPurpose">PrimaryContactFaxPurpose</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFaxPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactPhone name="PrimaryContactPhone">PrimaryContactPhone</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactPhone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactPhoneDescription name="PrimaryContactPhoneDescription">PrimaryContactPhoneDescription</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactPhoneDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactPhoneExtension name="PrimaryContactPhoneExtension">PrimaryContactPhoneExtension</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactPhoneExtension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactPhoneIsMobile name="PrimaryContactPhoneIsMobile">PrimaryContactPhoneIsMobile</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactPhoneIsMobile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactPhonePurpose name="PrimaryContactPhonePurpose">PrimaryContactPhonePurpose</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactPhonePurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactTelex name="PrimaryContactTelex">PrimaryContactTelex</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactTelex attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactTelexDescription name="PrimaryContactTelexDescription">PrimaryContactTelexDescription</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactTelexDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactTelexPurpose name="PrimaryContactTelexPurpose">PrimaryContactTelexPurpose</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactTelexPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactURL name="PrimaryContactURL">PrimaryContactURL</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactURL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactURLDescription name="PrimaryContactURLDescription">PrimaryContactURLDescription</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactURLDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactURLPurpose name="PrimaryContactURLPurpose">PrimaryContactURLPurpose</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactURLPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFacebook name="PrimaryContactFacebook">PrimaryContactFacebook</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFacebook attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFacebookDescription name="PrimaryContactFacebookDescription">PrimaryContactFacebookDescription</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFacebookDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFacebookPurpose name="PrimaryContactFacebookPurpose">PrimaryContactFacebookPurpose</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFacebookPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactLinkedIn name="PrimaryContactLinkedIn">PrimaryContactLinkedIn</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactLinkedIn attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactLinkedInDescription name="PrimaryContactLinkedInDescription">PrimaryContactLinkedInDescription</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactLinkedInDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactLinkedInPurpose name="PrimaryContactLinkedInPurpose">PrimaryContactLinkedInPurpose</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactLinkedInPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactTwitterDescription name="PrimaryContactTwitterDescription">PrimaryContactTwitterDescription</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactTwitterDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactTwitter name="PrimaryContactTwitter">PrimaryContactTwitter</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactTwitter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactTwitterPurpose name="PrimaryContactTwitterPurpose">PrimaryContactTwitterPurpose</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactTwitterPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOneTimeCustomer name="IsOneTimeCustomer">IsOneTimeCustomer</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#StatisticsGroupId name="StatisticsGroupId">StatisticsGroupId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatisticsGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountStatement name="AccountStatement">AccountStatement</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStatement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IdentificationNumber name="IdentificationNumber">IdentificationNumber</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IdentificationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PartyCountry name="PartyCountry">PartyCountry</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyCountry attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PartyState name="PartyState">PartyState</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAccount name="VendorAccount">VendorAccount</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FederalIndicator name="FederalIndicator">FederalIndicator</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FederalIndicator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FederalAgencyLocationCode name="FederalAgencyLocationCode">FederalAgencyLocationCode</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FederalAgencyLocationCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FederalComments name="FederalComments">FederalComments</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FederalComments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IRS1099CIndicator name="IRS1099CIndicator">IRS1099CIndicator</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IRS1099CIndicator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPersonId name="ContactPersonId">ContactPersonId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#LineOfBusinessId name="LineOfBusinessId">LineOfBusinessId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineOfBusinessId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmployeeResponsibleNumber name="EmployeeResponsibleNumber">EmployeeResponsibleNumber</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmployeeResponsibleNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainContactWorker name="MainContactWorker">MainContactWorker</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainContactWorker attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesSegmentId name="SalesSegmentId">SalesSegmentId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesSegmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesSubsegmentId name="SalesSubsegmentId">SalesSubsegmentId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesSubsegmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesDistrict name="SalesDistrict">SalesDistrict</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesDistrict attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyChain name="CompanyChain">CompanyChain</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyChain attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesCurrencyCode name="SalesCurrencyCode">SalesCurrencyCode</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesMemo name="SalesMemo">SalesMemo</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesMemo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnHoldStatus name="OnHoldStatus">OnHoldStatus</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnHoldStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditLimitIsMandatory name="CreditLimitIsMandatory">CreditLimitIsMandatory</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditLimitIsMandatory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditRating name="CreditRating">CreditRating</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditRating attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditLimit name="CreditLimit">CreditLimit</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectionsContactPersonId name="CollectionsContactPersonId">CollectionsContactPersonId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionsContactPersonId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsExcludedFromInterestChargeCalculation name="IsExcludedFromInterestChargeCalculation">IsExcludedFromInterestChargeCalculation</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExcludedFromInterestChargeCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsExcludedFromCollectionFeeCalculation name="IsExcludedFromCollectionFeeCalculation">IsExcludedFromCollectionFeeCalculation</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExcludedFromCollectionFeeCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargesGroupId name="ChargesGroupId">ChargesGroupId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargesGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SiteId name="SiteId">SiteId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseId name="WarehouseId">WarehouseId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemCustomerGroupId name="ItemCustomerGroupId">ItemCustomerGroupId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemCustomerGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CommissionCustomerGroupId name="CommissionCustomerGroupId">CommissionCustomerGroupId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#CommissionSalesGroupId name="CommissionSalesGroupId">CommissionSalesGroupId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommissionSalesGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderPoolId name="SalesOrderPoolId">SalesOrderPoolId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#SalesAccountNumber name="SalesAccountNumber">SalesAccountNumber</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderEntryDeadline name="OrderEntryDeadline">OrderEntryDeadline</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderEntryDeadline attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MultiLineDiscountCode name="MultiLineDiscountCode">MultiLineDiscountCode</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MultiLineDiscountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountCode name="TotalDiscountCode">TotalDiscountCode</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountPriceGroupId name="DiscountPriceGroupId">DiscountPriceGroupId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountPriceGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDiscountCode name="LineDiscountCode">LineDiscountCode</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDiscountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerRebateGroupId name="CustomerRebateGroupId">CustomerRebateGroupId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerRebateGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerTMAGroupId name="CustomerTMAGroupId">CustomerTMAGroupId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerTMAGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SupplementaryItemGroupId name="SupplementaryItemGroupId">SupplementaryItemGroupId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SupplementaryItemGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentTerms name="PaymentTerms">PaymentTerms</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentTerms attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentMethod name="PaymentMethod">PaymentMethod</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentSpecification name="PaymentSpecification">PaymentSpecification</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentSpecification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentSchedule name="PaymentSchedule">PaymentSchedule</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentSchedule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentDay name="PaymentDay">PaymentDay</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentDay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentCashDiscount name="PaymentCashDiscount">PaymentCashDiscount</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentCashDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentTermsBaseDays name="PaymentTermsBaseDays">PaymentTermsBaseDays</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentTermsBaseDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentBankAccount name="PaymentBankAccount">PaymentBankAccount</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentBankAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentFactoringAccount name="PaymentFactoringAccount">PaymentFactoringAccount</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentFactoringAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentIdType name="PaymentIdType">PaymentIdType</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentIdType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentUseCashDiscount name="PaymentUseCashDiscount">PaymentUseCashDiscount</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentUseCashDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CentralBankPurposeCode name="CentralBankPurposeCode">CentralBankPurposeCode</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CentralBankPurposeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CentralBankPurposeNotes name="CentralBankPurposeNotes">CentralBankPurposeNotes</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CentralBankPurposeNotes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditCardAddressVerification name="CreditCardAddressVerification">CreditCardAddressVerification</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardAddressVerification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditCardAddressVerificationIsAuthorizationVoidedOnFailure name="CreditCardAddressVerificationIsAuthorizationVoidedOnFailure">CreditCardAddressVerificationIsAuthorizationVoidedOnFailure</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardAddressVerificationIsAuthorizationVoidedOnFailure attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditCardAddressVerificationLevel name="CreditCardAddressVerificationLevel">CreditCardAddressVerificationLevel</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardAddressVerificationLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditCardCVC name="CreditCardCVC">CreditCardCVC</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardCVC attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseIsASNGenerated name="WarehouseIsASNGenerated">WarehouseIsASNGenerated</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseIsASNGenerated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseIsEntireShipmentFilled name="WarehouseIsEntireShipmentFilled">WarehouseIsEntireShipmentFilled</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseIsEntireShipmentFilled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultInventoryStatusId name="DefaultInventoryStatusId">DefaultInventoryStatusId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultInventoryStatusId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAccount name="InvoiceAccount">InvoiceAccount</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddress name="InvoiceAddress">InvoiceAddress</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceGroup name="NumberSequenceGroup">NumberSequenceGroup</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiroType name="GiroType">GiroType</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiroType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiroTypeFreeTextInvoice name="GiroTypeFreeTextInvoice">GiroTypeFreeTextInvoice</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiroTypeFreeTextInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiroTypeInterestNote name="GiroTypeInterestNote">GiroTypeInterestNote</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiroTypeInterestNote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiroTypeCollectionletter name="GiroTypeCollectionletter">GiroTypeCollectionletter</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiroTypeCollectionletter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiroTypeProjInvoice name="GiroTypeProjInvoice">GiroTypeProjInvoice</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiroTypeProjInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiroTypeAccountStatement name="GiroTypeAccountStatement">GiroTypeAccountStatement</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiroTypeAccountStatement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryFreightZone name="DeliveryFreightZone">DeliveryFreightZone</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryFreightZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryTerms name="DeliveryTerms">DeliveryTerms</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryTerms attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryMode name="DeliveryMode">DeliveryMode</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryReason name="DeliveryReason">DeliveryReason</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryReason attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationCode name="DestinationCode">DestinationCode</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptCalendar name="ReceiptCalendar">ReceiptCalendar</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFuelSurchargeApplied name="IsFuelSurchargeApplied">IsFuelSurchargeApplied</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFuelSurchargeApplied attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroup name="SalesTaxGroup">SalesTaxGroup</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxExemptNumber name="TaxExemptNumber">TaxExemptNumber</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#IsSalesTaxIncludedInPrices name="IsSalesTaxIncludedInPrices">IsSalesTaxIncludedInPrices</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesTaxIncludedInPrices attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackingDutyLicense name="PackingDutyLicense">PackingDutyLicense</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingDutyLicense attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCode name="FiscalCode">FiscalCode</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackingMaterialFeeLicenseNumber name="PackingMaterialFeeLicenseNumber">PackingMaterialFeeLicenseNumber</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingMaterialFeeLicenseNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsElectronicInvoice name="IsElectronicInvoice">IsElectronicInvoice</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsElectronicInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicInvoiceEAN name="ElectronicInvoiceEAN">ElectronicInvoiceEAN</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicInvoiceEAN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFreightAccrued name="IsFreightAccrued">IsFreightAccrued</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFreightAccrued attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsExpressBillOfLadingAccepted name="IsExpressBillOfLadingAccepted">IsExpressBillOfLadingAccepted</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExpressBillOfLadingAccepted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTransactionPostedAsShipment name="IsTransactionPostedAsShipment">IsTransactionPostedAsShipment</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTransactionPostedAsShipment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOrderNumberReferenceUsed name="IsOrderNumberReferenceUsed">IsOrderNumberReferenceUsed</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOrderNumberReferenceUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesReturnTaxGroup name="SalesReturnTaxGroup">SalesReturnTaxGroup</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesReturnTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptEmail name="ReceiptEmail">ReceiptEmail</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptEmail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptOption name="ReceiptOption">ReceiptOption</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptOption attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWithholdingTaxCalculated name="IsWithholdingTaxCalculated">IsWithholdingTaxCalculated</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWithholdingTaxCalculated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WithholdingTaxGroupCode name="WithholdingTaxGroupCode">WithholdingTaxGroupCode</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingTaxGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FrenchSiret name="FrenchSiret">FrenchSiret</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FrenchSiret attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NAFCode name="NAFCode">NAFCode</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NAFCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyType name="CompanyType">CompanyType</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CURPNumber name="CURPNumber">CURPNumber</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CURPNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFCNumber name="RFCNumber">RFCNumber</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFCNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StateInscription name="StateInscription">StateInscription</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StateInscription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxRegistrationId name="TaxRegistrationId">TaxRegistrationId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRegistrationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsolidationDay name="ConsolidationDay">ConsolidationDay</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsolidationDay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NationalRegistryNumber name="NationalRegistryNumber">NationalRegistryNumber</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NationalRegistryNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReliefGroupId name="ReliefGroupId">ReliefGroupId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReliefGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionDisplayValue name="DefaultDimensionDisplayValue">DefaultDimensionDisplayValue</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#CalculateWithholdingTax name="CalculateWithholdingTax">CalculateWithholdingTax</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculateWithholdingTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForeignCustomer name="ForeignCustomer">ForeignCustomer</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForeignCustomer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TCSGroup name="TCSGroup">TCSGroup</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TCSGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TDSGroup name="TDSGroup">TDSGroup</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TDSGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PreferentialCustomer name="PreferentialCustomer">PreferentialCustomer</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreferentialCustomer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NatureOfAssessee name="NatureOfAssessee">NatureOfAssessee</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NatureOfAssessee attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PANNumber name="PANNumber">PANNumber</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PANNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PANReferenceNumber name="PANReferenceNumber">PANReferenceNumber</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PANReferenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PanStatus name="PanStatus">PanStatus</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PanStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicLocationId name="ElectronicLocationId">ElectronicLocationId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerPaymentFineCode name="CustomerPaymentFineCode">CustomerPaymentFineCode</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#CustomerPaymentFinancialInterestCode name="CustomerPaymentFinancialInterestCode">CustomerPaymentFinancialInterestCode</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#BrazilianCCM name="BrazilianCCM">BrazilianCCM</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BrazilianCCM attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BrazilianCNAE name="BrazilianCNAE">BrazilianCNAE</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BrazilianCNAE attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BrazilianCNPJOrCPF name="BrazilianCNPJOrCPF">BrazilianCNPJOrCPF</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BrazilianCNPJOrCPF attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFinalUser name="IsFinalUser">IsFinalUser</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#CustomerWithholdingContributionType name="CustomerWithholdingContributionType">CustomerWithholdingContributionType</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerWithholdingContributionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIncomingFiscalDocumentGenerated name="IsIncomingFiscalDocumentGenerated">IsIncomingFiscalDocumentGenerated</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIncomingFiscalDocumentGenerated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsICMSContributor name="IsICMSContributor">IsICMSContributor</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsICMSContributor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BrazilianIE name="BrazilianIE">BrazilianIE</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BrazilianIE attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BrazilianINSSCEI name="BrazilianINSSCEI">BrazilianINSSCEI</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BrazilianINSSCEI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BrazilianNIT name="BrazilianNIT">BrazilianNIT</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BrazilianNIT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsServiceDeliveryAddressBased name="IsServiceDeliveryAddressBased">IsServiceDeliveryAddressBased</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#IsInSuframaRegion name="IsInSuframaRegion">IsInSuframaRegion</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInSuframaRegion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SuframaNumber name="SuframaNumber">SuframaNumber</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SuframaNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HasSuframaDiscountPISandCOFINS name="HasSuframaDiscountPISandCOFINS">HasSuframaDiscountPISandCOFINS</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HasSuframaDiscountPISandCOFINS attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForeignerId name="ForeignerId">ForeignerId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForeignerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionPresenceType name="TransactionPresenceType">TransactionPresenceType</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionPresenceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WriteOffCompany name="WriteOffCompany">WriteOffCompany</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WriteOffCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WriteoffReason name="WriteoffReason">WriteoffReason</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WriteoffReason attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExportSale name="ExportSale">ExportSale</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExportSale attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BirthCountyCode name="BirthCountyCode">BirthCountyCode</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BirthCountyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BirthPlace name="BirthPlace">BirthPlace</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BirthPlace attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResidenceForeignCountryRegionId name="ResidenceForeignCountryRegionId">ResidenceForeignCountryRegionId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResidenceForeignCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPurchRequestUsed name="IsPurchRequestUsed">IsPurchRequestUsed</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPurchRequestUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressDescription name="DeliveryAddressDescription">DeliveryAddressDescription</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#DeliveryAddressZipCode name="DeliveryAddressZipCode">DeliveryAddressZipCode</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#DeliveryAddressTimeZone name="DeliveryAddressTimeZone">DeliveryAddressTimeZone</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#DeliveryAddressCity name="DeliveryAddressCity">DeliveryAddressCity</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#DeliveryAddressCounty name="DeliveryAddressCounty">DeliveryAddressCounty</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCounty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressDistrictName name="DeliveryAddressDistrictName">DeliveryAddressDistrictName</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#DeliveryAddressLatitude name="DeliveryAddressLatitude">DeliveryAddressLatitude</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#DeliveryAddressLongitude name="DeliveryAddressLongitude">DeliveryAddressLongitude</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#DeliveryAddressLocationId name="DeliveryAddressLocationId">DeliveryAddressLocationId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#DeliveryAddressState name="DeliveryAddressState">DeliveryAddressState</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressStreet name="DeliveryAddressStreet">DeliveryAddressStreet</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#DeliveryAddressBuildingComplement name="DeliveryAddressBuildingComplement">DeliveryAddressBuildingComplement</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressBuildingComplement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressValidFrom name="DeliveryAddressValidFrom">DeliveryAddressValidFrom</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#InvoiceAddressDescription name="InvoiceAddressDescription">InvoiceAddressDescription</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressZipCode name="InvoiceAddressZipCode">InvoiceAddressZipCode</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#InvoiceAddressTimeZone name="InvoiceAddressTimeZone">InvoiceAddressTimeZone</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#InvoiceAddressCity name="InvoiceAddressCity">InvoiceAddressCity</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#InvoiceAddressCountryRegionISOCode name="InvoiceAddressCountryRegionISOCode">InvoiceAddressCountryRegionISOCode</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#InvoiceAddressCounty name="InvoiceAddressCounty">InvoiceAddressCounty</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressCounty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressDistrictName name="InvoiceAddressDistrictName">InvoiceAddressDistrictName</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#InvoiceAddressLatitude name="InvoiceAddressLatitude">InvoiceAddressLatitude</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#InvoiceAddressLocationId name="InvoiceAddressLocationId">InvoiceAddressLocationId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressState name="InvoiceAddressState">InvoiceAddressState</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressStreet name="InvoiceAddressStreet">InvoiceAddressStreet</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#InvoiceAddressStreetNumber name="InvoiceAddressStreetNumber">InvoiceAddressStreetNumber</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#InvoiceAddressBuildingComplement name="InvoiceAddressBuildingComplement">InvoiceAddressBuildingComplement</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressBuildingComplement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressValidFrom name="InvoiceAddressValidFrom">InvoiceAddressValidFrom</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressValidTo name="InvoiceAddressValidTo">InvoiceAddressValidTo</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsExternallyMaintained name="IsExternallyMaintained">IsExternallyMaintained</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExternallyMaintained attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MerchantID name="MerchantID">MerchantID</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MerchantID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultECommerceOperator name="DefaultECommerceOperator">DefaultECommerceOperator</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultECommerceOperator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerType name="CustomerType">CustomerType</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FulfillmentPolicyName name="FulfillmentPolicyName">FulfillmentPolicyName</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FulfillmentPolicyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FulfillmentPolicy name="FulfillmentPolicy">FulfillmentPolicy</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FulfillmentPolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressPostbox name="AddressPostbox">AddressPostbox</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressPostbox attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustClassificationId name="CustClassificationId">CustClassificationId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustClassificationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAllowCreateIndirectOrderLines name="IsAllowCreateIndirectOrderLines">IsAllowCreateIndirectOrderLines</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAllowCreateIndirectOrderLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactEmailRecordId name="PrimaryContactEmailRecordId">PrimaryContactEmailRecordId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactEmailRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactFaxRecordId name="PrimaryContactFaxRecordId">PrimaryContactFaxRecordId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactFaxRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactPhoneRecordId name="PrimaryContactPhoneRecordId">PrimaryContactPhoneRecordId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactPhoneRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryContactURLRecordId name="PrimaryContactURLRecordId">PrimaryContactURLRecordId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryContactURLRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressRecordId name="AddressRecordId">AddressRecordId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectionLetterCode name="CollectionLetterCode">CollectionLetterCode</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionLetterCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EInvoiceRegister name="EInvoiceRegister">EInvoiceRegister</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EInvoiceRegister attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AuthorityOffice name="AuthorityOffice">AuthorityOffice</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AuthorityOffice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EInvoiceAttachment name="EInvoiceAttachment">EInvoiceAttachment</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EInvoiceAttachment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Priority name="Priority">Priority</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Priority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressRecordId name="DeliveryAddressRecordId">DeliveryAddressRecordId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressRecordId name="InvoiceAddressRecordId">InvoiceAddressRecordId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DirPartyLocationRecordId name="DirPartyLocationRecordId">DirPartyLocationRecordId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirPartyLocationRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PartyRecordId name="PartyRecordId">PartyRecordId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoicePostingType name="InvoicePostingType">InvoicePostingType</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoicePostingType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForeignResident name="ForeignResident">ForeignResident</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForeignResident attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InterCompanyAutoCreateOrders name="InterCompanyAutoCreateOrders">InterCompanyAutoCreateOrders</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterCompanyAutoCreateOrders attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CredManAccountStatusId name="CredManAccountStatusId">CredManAccountStatusId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CredManAccountStatusId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CredManBusinessStarted name="CredManBusinessStarted">CredManBusinessStarted</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CredManBusinessStarted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CredManCollectionGroupId name="CredManCollectionGroupId">CredManCollectionGroupId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CredManCollectionGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CredManCreditLimitDate name="CredManCreditLimitDate">CredManCreditLimitDate</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CredManCreditLimitDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CredManCreditLimitExpiryDate name="CredManCreditLimitExpiryDate">CredManCreditLimitExpiryDate</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CredManCreditLimitExpiryDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CredManCustCreditMaxAlt name="CredManCustCreditMaxAlt">CredManCustCreditMaxAlt</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CredManCustCreditMaxAlt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CredManCustomerSince name="CredManCustomerSince">CredManCustomerSince</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CredManCustomerSince attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CredManEligibleCreditLimitCurrency name="CredManEligibleCreditLimitCurrency">CredManEligibleCreditLimitCurrency</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CredManEligibleCreditLimitCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CredManEligibleCreditLimitDate name="CredManEligibleCreditLimitDate">CredManEligibleCreditLimitDate</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CredManEligibleCreditLimitDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CredManEligibleCreditMax name="CredManEligibleCreditMax">CredManEligibleCreditMax</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CredManEligibleCreditMax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CredManExclude name="CredManExclude">CredManExclude</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CredManExclude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CredManGroupId name="CredManGroupId">CredManGroupId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CredManGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CredManNotes name="CredManNotes">CredManNotes</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CredManNotes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CredManStatusReasonId name="CredManStatusReasonId">CredManStatusReasonId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CredManStatusReasonId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CredManTitleHeld name="CredManTitleHeld">CredManTitleHeld</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CredManTitleHeld attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CredManWithAgency name="CredManWithAgency">CredManWithAgency</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CredManWithAgency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CredManLastReviewDate name="CredManLastReviewDate">CredManLastReviewDate</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CredManLastReviewDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CredManNextSchedReviewDate name="CredManNextSchedReviewDate">CredManNextSchedReviewDate</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CredManNextSchedReviewDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CredManCustUnlimitedCredit name="CredManCustUnlimitedCredit">CredManCustUnlimitedCredit</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CredManCustUnlimitedCredit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

### <a href=#Relationship_CustClassificationGroupRelationshipId name="Relationship_CustClassificationGroupRelationshipId">Relationship_CustClassificationGroupRelationshipId</a>

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustClassificationGroupRelationshipId attribute are listed below.</summary>

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

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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

First included in: AccountsReceivable/CustCustomerV3Entity (this entity)  

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
