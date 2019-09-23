---
title: Account - Common Data Model | Microsoft Docs
description: This describes the Account entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Account

Business that represents a customer or a potential customer. The company that's billed in business transactions.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/eventManagement/Account.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- [/Account](../../../../../Account.md "/core/applicationCommon/Account.cdm.json/Account")  
- [/foundationCommon/Account](../../../../Account.md "/core/applicationCommon/foundationCommon/Account.cdm.json/Account")  
- [/foundationCommon/crmCommon/Account](../../../Account.md "/core/applicationCommon/foundationCommon/crmCommon/Account.cdm.json/Account")  
- [/foundationCommon/crmCommon/accelerators/education/higherEducation/Account](../../../accelerators/education/higherEducation/Account.md "/core/applicationCommon/foundationCommon/crmCommon/accelerators/education/higherEducation/Account.cdm.json/Account")  
- [/foundationCommon/crmCommon/accelerators/financialServices/banking/Account](../../../accelerators/financialServices/banking/Account.md "/core/applicationCommon/foundationCommon/crmCommon/accelerators/financialServices/banking/Account.cdm.json/Account")  
- [/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/Account](../../../accelerators/healthCare/electronicMedicalRecords/Account.md "/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/Account.cdm.json/Account")  
- [/foundationCommon/crmCommon/accelerators/nonProfit/Account](../../../accelerators/nonProfit/Account.md "/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/Account.cdm.json/Account")  
- [/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/Account](../../../projectCommon/projectServiceAutomation/Account.md "/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/Account.cdm.json/Account")  
- /foundationCommon/crmCommon/solutions/marketing/eventManagement/Account  
- [/foundationCommon/crmCommon/solutions/portals/Account](../../portals/Account.md "/core/applicationCommon/foundationCommon/crmCommon/solutions/portals/Account.cdm.json/Account")  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[ownerIdType](#ownerIdType)||<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[ownerId](#ownerId)||<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[accountId](#accountId)|Unique identifier of the account.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[accountCategoryCode](#accountCategoryCode)|Select a category to indicate whether the customer account is standard or preferred.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[accountCategoryCode_display](#accountCategoryCode_display)||<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[customerSizeCode](#customerSizeCode)|Select the size category or range of the account for segmentation and reporting purposes.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[customerSizeCode_display](#customerSizeCode_display)||<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[preferredContactMethodCode](#preferredContactMethodCode)|Select the preferred method of contact.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[preferredContactMethodCode_display](#preferredContactMethodCode_display)||<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[customerTypeCode](#customerTypeCode)|Select the category that best describes the relationship between the account and your organization.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[customerTypeCode_display](#customerTypeCode_display)||<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[accountRatingCode](#accountRatingCode)|Select a rating to indicate the value of the customer account.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[accountRatingCode_display](#accountRatingCode_display)||<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[industryCode](#industryCode)|Select the account's primary industry for use in marketing segmentation and demographic analysis.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[industryCode_display](#industryCode_display)||<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[territoryCode](#territoryCode)|Select a region or territory for the account for use in segmentation and analysis.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[territoryCode_display](#territoryCode_display)||<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[accountClassificationCode](#accountClassificationCode)|Select a classification code to indicate the potential value of the customer account based on the projected return on investment, cooperation level, sales cycle length or other criteria.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[accountClassificationCode_display](#accountClassificationCode_display)||<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[businessTypeCode](#businessTypeCode)|Select the legal designation or other business type of the account for contracts or reporting purposes.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[businessTypeCode_display](#businessTypeCode_display)||<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[traversedPath](#traversedPath)|For internal use only.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[paymentTermsCode](#paymentTermsCode)|Select the payment terms to indicate when the customer needs to pay the total amount.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[paymentTermsCode_display](#paymentTermsCode_display)||<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[shippingMethodCode](#shippingMethodCode)|Select a shipping method for deliveries sent to the account's address to designate the preferred carrier or other delivery option.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[shippingMethodCode_display](#shippingMethodCode_display)||<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[primaryContactId](#primaryContactId)|Choose the primary contact for the account to provide quick access to contact details.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[participatesInWorkflow](#participatesInWorkflow)|For system use only. Legacy Microsoft Dynamics CRM 3.0 workflow data.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[name](#name)|Type the company or business name.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[accountNumber](#accountNumber)|Type an ID number or code for the account to quickly search and identify the account in system views.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[revenue](#revenue)|Type the annual revenue for the account, used as an indicator in financial performance analysis.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[numberOfEmployees](#numberOfEmployees)|Type the number of employees that work at the account for use in marketing segmentation and demographic analysis.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[description](#description)|Type additional information to describe the account, such as an excerpt from the company's website.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[SIC](#SIC)|Type the Standard Industrial Classification (SIC) code that indicates the account's primary industry of business, for use in marketing segmentation and demographic analysis.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[ownershipCode](#ownershipCode)|Select the account's ownership structure, such as public or private.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[ownershipCode_display](#ownershipCode_display)||<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[marketCap](#marketCap)|Type the market capitalization of the account to identify the company's equity, used as an indicator in financial performance analysis.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[sharesOutstanding](#sharesOutstanding)|Type the number of shares available to the public for the account. This number is used as an indicator in financial performance analysis.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[tickerSymbol](#tickerSymbol)|Type the stock exchange symbol for the account to track financial performance of the company. You can click the code entered in this field to access the latest trading information from MSN Money.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[stockExchange](#stockExchange)|Type the stock exchange at which the account is listed to track their stock and financial performance of the company.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[webSiteUrl](#webSiteUrl)|Type the account's website URL to get quick details about the company profile.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[ftpSiteUrl](#ftpSiteUrl)|Type the URL for the account's FTP site to enable users to access data and share documents.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[EMailAddress1](#EMailAddress1)|Type the primary email address for the account.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[EMailAddress2](#EMailAddress2)|Type the secondary email address for the account.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[EMailAddress3](#EMailAddress3)|Type an alternate email address for the account.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[doNotPhone](#doNotPhone)|Select whether the account allows phone calls. If Do Not Allow is selected, the account will be excluded from phone call activities distributed in marketing campaigns.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[doNotFax](#doNotFax)|Select whether the account allows faxes. If Do Not Allow is selected, the account will be excluded from fax activities distributed in marketing campaigns.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[telephone1](#telephone1)|Type the main phone number for this account.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[doNotEMail](#doNotEMail)|Select whether the account allows direct email sent from Microsoft Dynamics 365.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[telephone2](#telephone2)|Type a second phone number for this account.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[fax](#fax)|Type the fax number for the account.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[telephone3](#telephone3)|Type a third phone number for this account.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[doNotPostalMail](#doNotPostalMail)|Select whether the account allows direct mail. If Do Not Allow is selected, the account will be excluded from letter activities distributed in marketing campaigns.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[doNotBulkEMail](#doNotBulkEMail)|Select whether the account allows bulk email sent through campaigns. If Do Not Allow is selected, the account can be added to marketing lists, but is excluded from email.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[doNotBulkPostalMail](#doNotBulkPostalMail)|Select whether the account allows bulk postal mail sent through marketing campaigns or quick campaigns. If Do Not Allow is selected, the account can be added to marketing lists, but will be excluded from the postal mail.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[creditLimit](#creditLimit)|Type the credit limit of the account. This is a useful reference when you address invoice and accounting issues with the customer.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[creditOnHold](#creditOnHold)|Select whether the credit for the account is on hold. This is a useful reference while addressing the invoice and accounting issues with the customer.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[parentAccountId](#parentAccountId)|Choose the parent account associated with this account to show parent and child businesses in reporting and analytics.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[aging30](#aging30)|For system use only.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[stateCode](#stateCode)|Shows whether the account is active or inactive. Inactive accounts are read-only and can't be edited unless they are reactivated.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[stateCode_display](#stateCode_display)||<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[aging60](#aging60)|For system use only.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[statusCode](#statusCode)|Select the account's status.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[statusCode_display](#statusCode_display)||<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[aging90](#aging90)|For system use only.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address1AddressId](#address1AddressId)|Unique identifier for address 1.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address1AddressTypeCode](#address1AddressTypeCode)|Select the address type, such as primary or billing.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address1AddressTypeCode_display](#address1AddressTypeCode_display)||<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address1Name](#address1Name)|Type a descriptive name for the customer's address, such as Corporate Headquarters.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address1PrimaryContactName](#address1PrimaryContactName)|Type the name of the primary contact person for the customer's address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address1Line1](#address1Line1)|Type the first line of the customer's address to help identify the location.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address1Line2](#address1Line2)|Type the second line of the customer's address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address1Line3](#address1Line3)|Type the third line of the customer's address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address1City](#address1City)|Type the city for the customer's address to help identify the location.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address1StateOrProvince](#address1StateOrProvince)|Type the state or province of the customer's address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address1County](#address1County)|Type the county for the customer's address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address1Country](#address1Country)|Type the country or region for the customer's address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address1PostOfficeBox](#address1PostOfficeBox)|Type the post office box number of the customer's address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address1PostalCode](#address1PostalCode)|Type the ZIP Code or postal code for the address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address1UTCOffset](#address1UTCOffset)|Select the time zone for the address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address1FreightTermsCode](#address1FreightTermsCode)|Select the freight terms to make sure shipping charges are processed correctly.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address1FreightTermsCode_display](#address1FreightTermsCode_display)||<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address1UPSZone](#address1UPSZone)|Type the UPS zone of the customer's address to make sure shipping charges are calculated correctly and deliveries are made promptly, if shipped by UPS.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address1Latitude](#address1Latitude)|Type the latitude value for the customer's address, for use in mapping and other applications.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address1Telephone1](#address1Telephone1)|Type the primary phone number for the customer's address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address1Longitude](#address1Longitude)|Type the longitude value for the customer's address, for use in mapping and other applications.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address1ShippingMethodCode](#address1ShippingMethodCode)|Select a shipping method for deliveries sent to this address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address1ShippingMethodCode_display](#address1ShippingMethodCode_display)||<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address1Telephone2](#address1Telephone2)|Type a second phone number for the customer's address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address1Telephone3](#address1Telephone3)|Type a third phone number for the customer's address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address1Fax](#address1Fax)|Type the fax number associated with the customer's address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address1Composite](#address1Composite)|Shows the complete address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address2AddressId](#address2AddressId)|Unique identifier for address 1.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address2AddressTypeCode](#address2AddressTypeCode)|Select the address type, such as primary or billing.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address2AddressTypeCode_display](#address2AddressTypeCode_display)||<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address2Name](#address2Name)|Type a descriptive name for the customer's address, such as Corporate Headquarters.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address2PrimaryContactName](#address2PrimaryContactName)|Type the name of the primary contact person for the customer's address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address2Line1](#address2Line1)|Type the first line of the customer's address to help identify the location.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address2Line2](#address2Line2)|Type the second line of the customer's address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address2Line3](#address2Line3)|Type the third line of the customer's address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address2City](#address2City)|Type the city for the customer's address to help identify the location.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address2StateOrProvince](#address2StateOrProvince)|Type the state or province of the customer's address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address2County](#address2County)|Type the county for the customer's address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address2Country](#address2Country)|Type the country or region for the customer's address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address2PostOfficeBox](#address2PostOfficeBox)|Type the post office box number of the customer's address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address2PostalCode](#address2PostalCode)|Type the ZIP Code or postal code for the address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address2UTCOffset](#address2UTCOffset)|Select the time zone for the address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address2FreightTermsCode](#address2FreightTermsCode)|Select the freight terms to make sure shipping charges are processed correctly.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address2FreightTermsCode_display](#address2FreightTermsCode_display)||<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address2UPSZone](#address2UPSZone)|Type the UPS zone of the customer's address to make sure shipping charges are calculated correctly and deliveries are made promptly, if shipped by UPS.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address2Latitude](#address2Latitude)|Type the latitude value for the customer's address, for use in mapping and other applications.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address2Telephone1](#address2Telephone1)|Type the primary phone number for the customer's address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address2Longitude](#address2Longitude)|Type the longitude value for the customer's address, for use in mapping and other applications.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address2ShippingMethodCode](#address2ShippingMethodCode)|Select a shipping method for deliveries sent to this address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address2ShippingMethodCode_display](#address2ShippingMethodCode_display)||<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address2Telephone2](#address2Telephone2)|Type a second phone number for the customer's address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address2Telephone3](#address2Telephone3)|Type a third phone number for the customer's address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address2Fax](#address2Fax)|Type the fax number associated with the customer's address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[address2Composite](#address2Composite)|Shows the complete address.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[preferredAppointmentDayCode](#preferredAppointmentDayCode)|Select the preferred day of the week for service appointments.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[preferredAppointmentDayCode_display](#preferredAppointmentDayCode_display)||<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[preferredSystemUserId](#preferredSystemUserId)|Choose the preferred service representative for reference when you schedule service activities for the account.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[preferredAppointmentTimeCode](#preferredAppointmentTimeCode)|Select the preferred time of day for service appointments.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[preferredAppointmentTimeCode_display](#preferredAppointmentTimeCode_display)||<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[merged](#merged)|Shows whether the account has been merged with another account.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[doNotSendMM](#doNotSendMM)|Select whether the account accepts marketing materials, such as brochures or catalogs.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[masterId](#masterId)|Shows the master account that the account was merged with.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[lastUsedInCampaign](#lastUsedInCampaign)|Shows the date when the account was last included in a marketing campaign or quick campaign.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[creditLimitBase](#creditLimitBase)|Shows the credit limit converted to the system's default base currency for reporting purposes.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[aging30Base](#aging30Base)|The base currency equivalent of the aging 30 field.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[revenueBase](#revenueBase)|Shows the annual revenue converted to the system's default base currency. The calculations use the exchange rate specified in the Currencies area.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[aging90Base](#aging90Base)|The base currency equivalent of the aging 90 field.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[marketCapBase](#marketCapBase)|Shows the market capitalization converted to the system's default base currency.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[aging60Base](#aging60Base)|The base currency equivalent of the aging 60 field.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[yomiName](#yomiName)|Type the phonetic spelling of the company name, if specified in Japanese, to make sure the name is pronounced correctly in phone calls and other communications.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[stageId](#stageId)|Shows the ID of the stage.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[processId](#processId)|Shows the ID of the process.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[entityImageId](#entityImageId)|For internal use only.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[timeSpentByMeOnEmailAndMeetings](#timeSpentByMeOnEmailAndMeetings)|Total time spent for emails (read and write) and meetings by me in relation to account record.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[createdByExternalParty](#createdByExternalParty)|Shows the external party who created the record.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[modifiedByExternalParty](#modifiedByExternalParty)|Shows the external party who modified the record.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[primarySatoriId](#primarySatoriId)|Primary Satori ID for Account|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[primaryTwitterId](#primaryTwitterId)|Primary Twitter ID for Account|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[SLAId](#SLAId)|Choose the service level agreement (SLA) that you want to apply to the Account record.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[SLAInvokedId](#SLAInvokedId)|Last SLA that was applied to this case. This field is for internal use only.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[onHoldTime](#onHoldTime)|Shows how long, in minutes, that the record was on hold.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[lastOnHoldTime](#lastOnHoldTime)|Contains the date and time stamp of the last on hold time.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[followEmail](#followEmail)|Information about whether to allow following email activity like opens, attachment views and link clicks for emails sent to the account.|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[marketingOnly](#marketingOnly)|Whether is only for marketing|<a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>|
|[defaultPriceLevelId](#defaultPriceLevelId)|Choose the default price list associated with the account to make sure the correct product prices for this customer are applied in sales opportunities, quotes, and orders.|<a href="../../../../Account.md" target="_blank">foundationCommon/Account</a>|
|[originatingLeadId](#originatingLeadId)|Shows the lead that the account was created from if the account was created by converting a lead in Microsoft Dynamics 365. This is used to relate the account to data on the originating lead for use in reporting and analytics.|<a href="../../../Account.md" target="_blank">crmCommon/Account</a>|
|[preferredEquipmentId](#preferredEquipmentId)|Choose the account's preferred service facility or equipment to make sure services are scheduled correctly for the customer.|<a href="../../../Account.md" target="_blank">crmCommon/Account</a>|
|[preferredServiceId](#preferredServiceId)|Choose the account's preferred service for reference when you schedule service activities.|<a href="../../../Account.md" target="_blank">crmCommon/Account</a>|
|[territoryId](#territoryId)|Choose the sales region or territory for the account to make sure the account is assigned to the correct representative and for use in segmentation and analysis.|<a href="../../../Account.md" target="_blank">crmCommon/Account</a>|
|[openDeals](#openDeals)|Number of open opportunities against an account and its child accounts.|<a href="../../../Account.md" target="_blank">crmCommon/Account</a>|
|[openDealsDate](#openDealsDate)|Last Updated time of rollup field Open Deals.|<a href="../../../Account.md" target="_blank">crmCommon/Account</a>|
|[openDealsState](#openDealsState)|State of rollup field Open Deals.|<a href="../../../Account.md" target="_blank">crmCommon/Account</a>|
|[openRevenue](#openRevenue)|Sum of open revenue against an account and its child accounts.|<a href="../../../Account.md" target="_blank">crmCommon/Account</a>|
|[openRevenueBase](#openRevenueBase)|Value of the Open Revenue in base currency.|<a href="../../../Account.md" target="_blank">crmCommon/Account</a>|
|[openRevenueDate](#openRevenueDate)|Last Updated time of rollup field Open Revenue.|<a href="../../../Account.md" target="_blank">crmCommon/Account</a>|
|[openRevenueState](#openRevenueState)|State of rollup field Open Revenue.|<a href="../../../Account.md" target="_blank">crmCommon/Account</a>|
|[adxCreatedByIPAddress](#adxCreatedByIPAddress)||<a href="../../portals/Account.md" target="_blank">portals/Account</a>|
|[adxCreatedByUsername](#adxCreatedByUsername)||<a href="../../portals/Account.md" target="_blank">portals/Account</a>|
|[adxModifiedByIPAddress](#adxModifiedByIPAddress)||<a href="../../portals/Account.md" target="_blank">portals/Account</a>|
|[adxModifiedByUsername](#adxModifiedByUsername)||<a href="../../portals/Account.md" target="_blank">portals/Account</a>|
|[managingPartner](#managingPartner)|Unique identifier for Account associated with Account.|<a href="../../portals/Account.md" target="_blank">portals/Account</a>|
|[hotelGroup](#hotelGroup)|Whether this account belongs to hotel group or not|<a href="Account.md" target="_blank">eventManagement/Account</a>|
|[hotelGroup_display](#hotelGroup_display)||<a href="Account.md" target="_blank">eventManagement/Account</a>|
|[rentalCarProvider](#rentalCarProvider)||<a href="Account.md" target="_blank">eventManagement/Account</a>|
|[rentalCarProvider_display](#rentalCarProvider_display)||<a href="Account.md" target="_blank">eventManagement/Account</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#accountId name="accountId">accountId</a>

Unique identifier of the account.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account</td></tr><tr><td>description</td><td>Unique identifier of the account.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>accountid</td></tr></table>

### <a href=#accountCategoryCode name="accountCategoryCode">accountCategoryCode</a>

Select a category to indicate whether the customer account is standard or preferred.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Category</td></tr><tr><td>description</td><td>Select a category to indicate whether the customer account is standard or preferred.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>accountcategorycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Preferred Customer</td><td>1</td></tr><tr><td>en</td><td>Standard</td><td>2</td></tr></table></td></tr></table>

### <a href=#accountCategoryCode_display name="accountCategoryCode_display">accountCategoryCode_display</a>

First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#customerSizeCode name="customerSizeCode">customerSizeCode</a>

Select the size category or range of the account for segmentation and reporting purposes.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Size</td></tr><tr><td>description</td><td>Select the size category or range of the account for segmentation and reporting purposes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customersizecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#customerSizeCode_display name="customerSizeCode_display">customerSizeCode_display</a>

First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#preferredContactMethodCode name="preferredContactMethodCode">preferredContactMethodCode</a>

Select the preferred method of contact.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Preferred Method of Contact</td></tr><tr><td>description</td><td>Select the preferred method of contact.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>preferredcontactmethodcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Any</td><td>1</td></tr><tr><td>en</td><td>Email</td><td>2</td></tr><tr><td>en</td><td>Phone</td><td>3</td></tr><tr><td>en</td><td>Fax</td><td>4</td></tr><tr><td>en</td><td>Mail</td><td>5</td></tr></table></td></tr></table>

### <a href=#preferredContactMethodCode_display name="preferredContactMethodCode_display">preferredContactMethodCode_display</a>

First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#customerTypeCode name="customerTypeCode">customerTypeCode</a>

Select the category that best describes the relationship between the account and your organization.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Relationship Type</td></tr><tr><td>description</td><td>Select the category that best describes the relationship between the account and your organization.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customertypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Competitor</td><td>1</td></tr><tr><td>en</td><td>Consultant</td><td>2</td></tr><tr><td>en</td><td>Customer</td><td>3</td></tr><tr><td>en</td><td>Investor</td><td>4</td></tr><tr><td>en</td><td>Partner</td><td>5</td></tr><tr><td>en</td><td>Influencer</td><td>6</td></tr><tr><td>en</td><td>Press</td><td>7</td></tr><tr><td>en</td><td>Prospect</td><td>8</td></tr><tr><td>en</td><td>Reseller</td><td>9</td></tr><tr><td>en</td><td>Supplier</td><td>10</td></tr><tr><td>en</td><td>Vendor</td><td>11</td></tr><tr><td>en</td><td>Other</td><td>12</td></tr></table></td></tr></table>

### <a href=#customerTypeCode_display name="customerTypeCode_display">customerTypeCode_display</a>

First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#accountRatingCode name="accountRatingCode">accountRatingCode</a>

Select a rating to indicate the value of the customer account.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account Rating</td></tr><tr><td>description</td><td>Select a rating to indicate the value of the customer account.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>accountratingcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#accountRatingCode_display name="accountRatingCode_display">accountRatingCode_display</a>

First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#industryCode name="industryCode">industryCode</a>

Select the account's primary industry for use in marketing segmentation and demographic analysis.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Industry</td></tr><tr><td>description</td><td>Select the account's primary industry for use in marketing segmentation and demographic analysis.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>industrycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Accounting</td><td>1</td></tr><tr><td>en</td><td>Agriculture and Non-petrol Natural Resource Extraction</td><td>2</td></tr><tr><td>en</td><td>Broadcasting Printing and Publishing</td><td>3</td></tr><tr><td>en</td><td>Brokers</td><td>4</td></tr><tr><td>en</td><td>Building Supply Retail</td><td>5</td></tr><tr><td>en</td><td>Business Services</td><td>6</td></tr><tr><td>en</td><td>Consulting</td><td>7</td></tr><tr><td>en</td><td>Consumer Services</td><td>8</td></tr><tr><td>en</td><td>Design, Direction and Creative Management</td><td>9</td></tr><tr><td>en</td><td>Distributors, Dispatchers and Processors</td><td>10</td></tr><tr><td>en</td><td>Doctor's Offices and Clinics</td><td>11</td></tr><tr><td>en</td><td>Durable Manufacturing</td><td>12</td></tr><tr><td>en</td><td>Eating and Drinking Places</td><td>13</td></tr><tr><td>en</td><td>Entertainment Retail</td><td>14</td></tr><tr><td>en</td><td>Equipment Rental and Leasing</td><td>15</td></tr><tr><td>en</td><td>Financial</td><td>16</td></tr><tr><td>en</td><td>Food and Tobacco Processing</td><td>17</td></tr><tr><td>en</td><td>Inbound Capital Intensive Processing</td><td>18</td></tr><tr><td>en</td><td>Inbound Repair and Services</td><td>19</td></tr><tr><td>en</td><td>Insurance</td><td>20</td></tr><tr><td>en</td><td>Legal Services</td><td>21</td></tr><tr><td>en</td><td>Non-Durable Merchandise Retail</td><td>22</td></tr><tr><td>en</td><td>Outbound Consumer Service</td><td>23</td></tr><tr><td>en</td><td>Petrochemical Extraction and Distribution</td><td>24</td></tr><tr><td>en</td><td>Service Retail</td><td>25</td></tr><tr><td>en</td><td>SIG Affiliations</td><td>26</td></tr><tr><td>en</td><td>Social Services</td><td>27</td></tr><tr><td>en</td><td>Special Outbound Trade Contractors</td><td>28</td></tr><tr><td>en</td><td>Specialty Realty</td><td>29</td></tr><tr><td>en</td><td>Transportation</td><td>30</td></tr><tr><td>en</td><td>Utility Creation and Distribution</td><td>31</td></tr><tr><td>en</td><td>Vehicle Retail</td><td>32</td></tr><tr><td>en</td><td>Wholesale</td><td>33</td></tr></table></td></tr></table>

### <a href=#industryCode_display name="industryCode_display">industryCode_display</a>

First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#territoryCode name="territoryCode">territoryCode</a>

Select a region or territory for the account for use in segmentation and analysis.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Territory Code</td></tr><tr><td>description</td><td>Select a region or territory for the account for use in segmentation and analysis.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>territorycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#territoryCode_display name="territoryCode_display">territoryCode_display</a>

First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#accountClassificationCode name="accountClassificationCode">accountClassificationCode</a>

Select a classification code to indicate the potential value of the customer account based on the projected return on investment, cooperation level, sales cycle length or other criteria.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Classification</td></tr><tr><td>description</td><td>Select a classification code to indicate the potential value of the customer account based on the projected return on investment, cooperation level, sales cycle length or other criteria.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>accountclassificationcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#accountClassificationCode_display name="accountClassificationCode_display">accountClassificationCode_display</a>

First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#businessTypeCode name="businessTypeCode">businessTypeCode</a>

Select the legal designation or other business type of the account for contracts or reporting purposes.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Business Type</td></tr><tr><td>description</td><td>Select the legal designation or other business type of the account for contracts or reporting purposes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>businesstypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#businessTypeCode_display name="businessTypeCode_display">businessTypeCode_display</a>

First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

For internal use only.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#paymentTermsCode name="paymentTermsCode">paymentTermsCode</a>

Select the payment terms to indicate when the customer needs to pay the total amount.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment Terms</td></tr><tr><td>description</td><td>Select the payment terms to indicate when the customer needs to pay the total amount.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>paymenttermscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Net 30</td><td>1</td></tr><tr><td>en</td><td>2% 10, Net 30</td><td>2</td></tr><tr><td>en</td><td>Net 45</td><td>3</td></tr><tr><td>en</td><td>Net 60</td><td>4</td></tr></table></td></tr></table>

### <a href=#paymentTermsCode_display name="paymentTermsCode_display">paymentTermsCode_display</a>

First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#shippingMethodCode name="shippingMethodCode">shippingMethodCode</a>

Select a shipping method for deliveries sent to the account's address to designate the preferred carrier or other delivery option.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping Method</td></tr><tr><td>description</td><td>Select a shipping method for deliveries sent to the account's address to designate the preferred carrier or other delivery option.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shippingmethodcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#shippingMethodCode_display name="shippingMethodCode_display">shippingMethodCode_display</a>

First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#primaryContactId name="primaryContactId">primaryContactId</a>

Choose the primary contact for the account to provide quick access to contact details.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary Contact</td></tr><tr><td>description</td><td>Choose the primary contact for the account to provide quick access to contact details.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>primarycontactid</td></tr></table>

### <a href=#participatesInWorkflow name="participatesInWorkflow">participatesInWorkflow</a>

For system use only. Legacy Microsoft Dynamics CRM 3.0 workflow data.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Participates in Workflow</td></tr><tr><td>description</td><td>For system use only. Legacy Microsoft Dynamics CRM 3.0 workflow data.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>participatesinworkflow</td></tr></table>

### <a href=#name name="name">name</a>

Type the company or business name.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account Name</td></tr><tr><td>description</td><td>Type the company or business name.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#accountNumber name="accountNumber">accountNumber</a>

Type an ID number or code for the account to quickly search and identify the account in system views.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account Number</td></tr><tr><td>description</td><td>Type an ID number or code for the account to quickly search and identify the account in system views.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>accountnumber</td></tr></table>

### <a href=#revenue name="revenue">revenue</a>

Type the annual revenue for the account, used as an indicator in financial performance analysis.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Annual Revenue</td></tr><tr><td>description</td><td>Type the annual revenue for the account, used as an indicator in financial performance analysis.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>revenue</td></tr></table>

### <a href=#numberOfEmployees name="numberOfEmployees">numberOfEmployees</a>

Type the number of employees that work at the account for use in marketing segmentation and demographic analysis.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number of Employees</td></tr><tr><td>description</td><td>Type the number of employees that work at the account for use in marketing segmentation and demographic analysis.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>numberofemployees</td></tr></table>

### <a href=#description name="description">description</a>

Type additional information to describe the account, such as an excerpt from the company's website.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type additional information to describe the account, such as an excerpt from the company's website.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#SIC name="SIC">SIC</a>

Type the Standard Industrial Classification (SIC) code that indicates the account's primary industry of business, for use in marketing segmentation and demographic analysis.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SIC Code</td></tr><tr><td>description</td><td>Type the Standard Industrial Classification (SIC) code that indicates the account's primary industry of business, for use in marketing segmentation and demographic analysis.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sic</td></tr></table>

### <a href=#ownershipCode name="ownershipCode">ownershipCode</a>

Select the account's ownership structure, such as public or private.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ownership</td></tr><tr><td>description</td><td>Select the account's ownership structure, such as public or private.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ownershipcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Public</td><td>1</td></tr><tr><td>en</td><td>Private</td><td>2</td></tr><tr><td>en</td><td>Subsidiary</td><td>3</td></tr><tr><td>en</td><td>Other</td><td>4</td></tr></table></td></tr></table>

### <a href=#ownershipCode_display name="ownershipCode_display">ownershipCode_display</a>

First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#marketCap name="marketCap">marketCap</a>

Type the market capitalization of the account to identify the company's equity, used as an indicator in financial performance analysis.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Market Capitalization</td></tr><tr><td>description</td><td>Type the market capitalization of the account to identify the company's equity, used as an indicator in financial performance analysis.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>marketcap</td></tr></table>

### <a href=#sharesOutstanding name="sharesOutstanding">sharesOutstanding</a>

Type the number of shares available to the public for the account. This number is used as an indicator in financial performance analysis.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shares Outstanding</td></tr><tr><td>description</td><td>Type the number of shares available to the public for the account. This number is used as an indicator in financial performance analysis.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sharesoutstanding</td></tr></table>

### <a href=#tickerSymbol name="tickerSymbol">tickerSymbol</a>

Type the stock exchange symbol for the account to track financial performance of the company. You can click the code entered in this field to access the latest trading information from MSN Money.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ticker Symbol</td></tr><tr><td>description</td><td>Type the stock exchange symbol for the account to track financial performance of the company. You can click the code entered in this field to access the latest trading information from MSN Money.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>tickersymbol</td></tr></table>

### <a href=#stockExchange name="stockExchange">stockExchange</a>

Type the stock exchange at which the account is listed to track their stock and financial performance of the company.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stock Exchange</td></tr><tr><td>description</td><td>Type the stock exchange at which the account is listed to track their stock and financial performance of the company.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stockexchange</td></tr></table>

### <a href=#webSiteUrl name="webSiteUrl">webSiteUrl</a>

Type the account's website URL to get quick details about the company profile.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Website</td></tr><tr><td>description</td><td>Type the account's website URL to get quick details about the company profile.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>websiteurl</td></tr></table>

### <a href=#ftpSiteUrl name="ftpSiteUrl">ftpSiteUrl</a>

Type the URL for the account's FTP site to enable users to access data and share documents.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>FTP Site</td></tr><tr><td>description</td><td>Type the URL for the account's FTP site to enable users to access data and share documents.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ftpsiteurl</td></tr></table>

### <a href=#EMailAddress1 name="EMailAddress1">EMailAddress1</a>

Type the primary email address for the account.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email</td></tr><tr><td>description</td><td>Type the primary email address for the account.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailaddress1</td></tr></table>

### <a href=#EMailAddress2 name="EMailAddress2">EMailAddress2</a>

Type the secondary email address for the account.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Address 2</td></tr><tr><td>description</td><td>Type the secondary email address for the account.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailaddress2</td></tr></table>

### <a href=#EMailAddress3 name="EMailAddress3">EMailAddress3</a>

Type an alternate email address for the account.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Address 3</td></tr><tr><td>description</td><td>Type an alternate email address for the account.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailaddress3</td></tr></table>

### <a href=#doNotPhone name="doNotPhone">doNotPhone</a>

Select whether the account allows phone calls. If Do Not Allow is selected, the account will be excluded from phone call activities distributed in marketing campaigns.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not allow Phone Calls</td></tr><tr><td>description</td><td>Select whether the account allows phone calls. If Do Not Allow is selected, the account will be excluded from phone call activities distributed in marketing campaigns.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>donotphone</td></tr></table>

### <a href=#doNotFax name="doNotFax">doNotFax</a>

Select whether the account allows faxes. If Do Not Allow is selected, the account will be excluded from fax activities distributed in marketing campaigns.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not allow Faxes</td></tr><tr><td>description</td><td>Select whether the account allows faxes. If Do Not Allow is selected, the account will be excluded from fax activities distributed in marketing campaigns.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>donotfax</td></tr></table>

### <a href=#telephone1 name="telephone1">telephone1</a>

Type the main phone number for this account.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Main Phone</td></tr><tr><td>description</td><td>Type the main phone number for this account.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone1</td></tr></table>

### <a href=#doNotEMail name="doNotEMail">doNotEMail</a>

Select whether the account allows direct email sent from Microsoft Dynamics 365.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not allow Emails</td></tr><tr><td>description</td><td>Select whether the account allows direct email sent from Microsoft Dynamics 365.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>donotemail</td></tr></table>

### <a href=#telephone2 name="telephone2">telephone2</a>

Type a second phone number for this account.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Other Phone</td></tr><tr><td>description</td><td>Type a second phone number for this account.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone2</td></tr></table>

### <a href=#fax name="fax">fax</a>

Type the fax number for the account.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fax</td></tr><tr><td>description</td><td>Type the fax number for the account.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>fax</td></tr></table>

### <a href=#telephone3 name="telephone3">telephone3</a>

Type a third phone number for this account.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Telephone 3</td></tr><tr><td>description</td><td>Type a third phone number for this account.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone3</td></tr></table>

### <a href=#doNotPostalMail name="doNotPostalMail">doNotPostalMail</a>

Select whether the account allows direct mail. If Do Not Allow is selected, the account will be excluded from letter activities distributed in marketing campaigns.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not allow Mails</td></tr><tr><td>description</td><td>Select whether the account allows direct mail. If Do Not Allow is selected, the account will be excluded from letter activities distributed in marketing campaigns.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>donotpostalmail</td></tr></table>

### <a href=#doNotBulkEMail name="doNotBulkEMail">doNotBulkEMail</a>

Select whether the account allows bulk email sent through campaigns. If Do Not Allow is selected, the account can be added to marketing lists, but is excluded from email.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not allow Bulk Emails</td></tr><tr><td>description</td><td>Select whether the account allows bulk email sent through campaigns. If Do Not Allow is selected, the account can be added to marketing lists, but is excluded from email.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>donotbulkemail</td></tr></table>

### <a href=#doNotBulkPostalMail name="doNotBulkPostalMail">doNotBulkPostalMail</a>

Select whether the account allows bulk postal mail sent through marketing campaigns or quick campaigns. If Do Not Allow is selected, the account can be added to marketing lists, but will be excluded from the postal mail.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not allow Bulk Mails</td></tr><tr><td>description</td><td>Select whether the account allows bulk postal mail sent through marketing campaigns or quick campaigns. If Do Not Allow is selected, the account can be added to marketing lists, but will be excluded from the postal mail.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>donotbulkpostalmail</td></tr></table>

### <a href=#creditLimit name="creditLimit">creditLimit</a>

Type the credit limit of the account. This is a useful reference when you address invoice and accounting issues with the customer.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credit Limit</td></tr><tr><td>description</td><td>Type the credit limit of the account. This is a useful reference when you address invoice and accounting issues with the customer.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>creditlimit</td></tr></table>

### <a href=#creditOnHold name="creditOnHold">creditOnHold</a>

Select whether the credit for the account is on hold. This is a useful reference while addressing the invoice and accounting issues with the customer.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credit Hold</td></tr><tr><td>description</td><td>Select whether the credit for the account is on hold. This is a useful reference while addressing the invoice and accounting issues with the customer.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>creditonhold</td></tr></table>

### <a href=#parentAccountId name="parentAccountId">parentAccountId</a>

Choose the parent account associated with this account to show parent and child businesses in reporting and analytics.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent Account</td></tr><tr><td>description</td><td>Choose the parent account associated with this account to show parent and child businesses in reporting and analytics.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>parentaccountid</td></tr></table>

### <a href=#aging30 name="aging30">aging30</a>

For system use only.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aging 30</td></tr><tr><td>description</td><td>For system use only.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>aging30</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the account is active or inactive. Inactive accounts are read-only and can't be edited unless they are reactivated.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows whether the account is active or inactive. Inactive accounts are read-only and can't be edited unless they are reactivated.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#aging60 name="aging60">aging60</a>

For system use only.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aging 60</td></tr><tr><td>description</td><td>For system use only.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>aging60</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the account's status.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the account's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#aging90 name="aging90">aging90</a>

For system use only.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aging 90</td></tr><tr><td>description</td><td>For system use only.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>aging90</td></tr></table>

### <a href=#address1AddressId name="address1AddressId">address1AddressId</a>

Unique identifier for address 1.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address: ID</td></tr><tr><td>description</td><td>Unique identifier for address 1.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>addressid</td></tr></table>

### <a href=#address1AddressTypeCode name="address1AddressTypeCode">address1AddressTypeCode</a>

Select the address type, such as primary or billing.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Type</td></tr><tr><td>description</td><td>Select the address type, such as primary or billing.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>addresstypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Bill To</td><td>1</td></tr><tr><td>en</td><td>Ship To</td><td>2</td></tr><tr><td>en</td><td>Primary</td><td>3</td></tr><tr><td>en</td><td>Other</td><td>4</td></tr></table></td></tr></table>

### <a href=#address1AddressTypeCode_display name="address1AddressTypeCode_display">address1AddressTypeCode_display</a>

First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address1Name name="address1Name">address1Name</a>

Type a descriptive name for the customer's address, such as Corporate Headquarters.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Name</td></tr><tr><td>description</td><td>Type a descriptive name for the customer's address, such as Corporate Headquarters.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#address1PrimaryContactName name="address1PrimaryContactName">address1PrimaryContactName</a>

Type the name of the primary contact person for the customer's address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Contact</td></tr><tr><td>description</td><td>Type the name of the primary contact person for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>150</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>primarycontactname</td></tr></table>

### <a href=#address1Line1 name="address1Line1">address1Line1</a>

Type the first line of the customer's address to help identify the location.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 1</td></tr><tr><td>description</td><td>Type the first line of the customer's address to help identify the location.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>line1</td></tr></table>

### <a href=#address1Line2 name="address1Line2">address1Line2</a>

Type the second line of the customer's address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 2</td></tr><tr><td>description</td><td>Type the second line of the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>line2</td></tr></table>

### <a href=#address1Line3 name="address1Line3">address1Line3</a>

Type the third line of the customer's address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 3</td></tr><tr><td>description</td><td>Type the third line of the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>line3</td></tr></table>

### <a href=#address1City name="address1City">address1City</a>

Type the city for the customer's address to help identify the location.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>City</td></tr><tr><td>description</td><td>Type the city for the customer's address to help identify the location.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>city</td></tr></table>

### <a href=#address1StateOrProvince name="address1StateOrProvince">address1StateOrProvince</a>

Type the state or province of the customer's address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State/Province</td></tr><tr><td>description</td><td>Type the state or province of the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stateorprovince</td></tr></table>

### <a href=#address1County name="address1County">address1County</a>

Type the county for the customer's address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>County</td></tr><tr><td>description</td><td>Type the county for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>county</td></tr></table>

### <a href=#address1Country name="address1Country">address1Country</a>

Type the country or region for the customer's address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country/Region</td></tr><tr><td>description</td><td>Type the country or region for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>country</td></tr></table>

### <a href=#address1PostOfficeBox name="address1PostOfficeBox">address1PostOfficeBox</a>

Type the post office box number of the customer's address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Post Office Box</td></tr><tr><td>description</td><td>Type the post office box number of the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postofficebox</td></tr></table>

### <a href=#address1PostalCode name="address1PostalCode">address1PostalCode</a>

Type the ZIP Code or postal code for the address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ZIP/Postal Code</td></tr><tr><td>description</td><td>Type the ZIP Code or postal code for the address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postalcode</td></tr></table>

### <a href=#address1UTCOffset name="address1UTCOffset">address1UTCOffset</a>

Select the time zone for the address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Offset</td></tr><tr><td>description</td><td>Select the time zone for the address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumValue</td><td>1500</td></tr><tr><td>minimumValue</td><td>-1500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcoffset</td></tr></table>

### <a href=#address1FreightTermsCode name="address1FreightTermsCode">address1FreightTermsCode</a>

Select the freight terms to make sure shipping charges are processed correctly.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Freight Terms</td></tr><tr><td>description</td><td>Select the freight terms to make sure shipping charges are processed correctly.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>freighttermscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>FOB</td><td>1</td></tr><tr><td>en</td><td>No Charge</td><td>2</td></tr></table></td></tr></table>

### <a href=#address1FreightTermsCode_display name="address1FreightTermsCode_display">address1FreightTermsCode_display</a>

First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address1UPSZone name="address1UPSZone">address1UPSZone</a>

Type the UPS zone of the customer's address to make sure shipping charges are calculated correctly and deliveries are made promptly, if shipped by UPS.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UPS Zone</td></tr><tr><td>description</td><td>Type the UPS zone of the customer's address to make sure shipping charges are calculated correctly and deliveries are made promptly, if shipped by UPS.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>upszone</td></tr></table>

### <a href=#address1Latitude name="address1Latitude">address1Latitude</a>

Type the latitude value for the customer's address, for use in mapping and other applications.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Latitude</td></tr><tr><td>description</td><td>Type the latitude value for the customer's address, for use in mapping and other applications.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>90</td></tr><tr><td>minimumValue</td><td>-90</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>latitude</td></tr></table>

### <a href=#address1Telephone1 name="address1Telephone1">address1Telephone1</a>

Type the primary phone number for the customer's address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Main Phone</td></tr><tr><td>description</td><td>Type the primary phone number for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone1</td></tr></table>

### <a href=#address1Longitude name="address1Longitude">address1Longitude</a>

Type the longitude value for the customer's address, for use in mapping and other applications.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Longitude</td></tr><tr><td>description</td><td>Type the longitude value for the customer's address, for use in mapping and other applications.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>180</td></tr><tr><td>minimumValue</td><td>-180</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>longitude</td></tr></table>

### <a href=#address1ShippingMethodCode name="address1ShippingMethodCode">address1ShippingMethodCode</a>

Select a shipping method for deliveries sent to this address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping Method</td></tr><tr><td>description</td><td>Select a shipping method for deliveries sent to this address.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shippingmethodcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Airborne</td><td>1</td></tr><tr><td>en</td><td>DHL</td><td>2</td></tr><tr><td>en</td><td>FedEx</td><td>3</td></tr><tr><td>en</td><td>UPS</td><td>4</td></tr><tr><td>en</td><td>Postal Mail</td><td>5</td></tr><tr><td>en</td><td>Full Load</td><td>6</td></tr><tr><td>en</td><td>Will Call</td><td>7</td></tr></table></td></tr></table>

### <a href=#address1ShippingMethodCode_display name="address1ShippingMethodCode_display">address1ShippingMethodCode_display</a>

First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address1Telephone2 name="address1Telephone2">address1Telephone2</a>

Type a second phone number for the customer's address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Phone 2</td></tr><tr><td>description</td><td>Type a second phone number for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone2</td></tr></table>

### <a href=#address1Telephone3 name="address1Telephone3">address1Telephone3</a>

Type a third phone number for the customer's address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Telephone 3</td></tr><tr><td>description</td><td>Type a third phone number for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone3</td></tr></table>

### <a href=#address1Fax name="address1Fax">address1Fax</a>

Type the fax number associated with the customer's address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fax</td></tr><tr><td>description</td><td>Type the fax number associated with the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>fax</td></tr></table>

### <a href=#address1Composite name="address1Composite">address1Composite</a>

Shows the complete address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address</td></tr><tr><td>description</td><td>Shows the complete address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>composite</td></tr></table>

### <a href=#address2AddressId name="address2AddressId">address2AddressId</a>

Unique identifier for address 1.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address: ID</td></tr><tr><td>description</td><td>Unique identifier for address 1.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>addressid</td></tr></table>

### <a href=#address2AddressTypeCode name="address2AddressTypeCode">address2AddressTypeCode</a>

Select the address type, such as primary or billing.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Type</td></tr><tr><td>description</td><td>Select the address type, such as primary or billing.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>addresstypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Bill To</td><td>1</td></tr><tr><td>en</td><td>Ship To</td><td>2</td></tr><tr><td>en</td><td>Primary</td><td>3</td></tr><tr><td>en</td><td>Other</td><td>4</td></tr></table></td></tr></table>

### <a href=#address2AddressTypeCode_display name="address2AddressTypeCode_display">address2AddressTypeCode_display</a>

First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address2Name name="address2Name">address2Name</a>

Type a descriptive name for the customer's address, such as Corporate Headquarters.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Name</td></tr><tr><td>description</td><td>Type a descriptive name for the customer's address, such as Corporate Headquarters.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#address2PrimaryContactName name="address2PrimaryContactName">address2PrimaryContactName</a>

Type the name of the primary contact person for the customer's address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Contact</td></tr><tr><td>description</td><td>Type the name of the primary contact person for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>150</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>primarycontactname</td></tr></table>

### <a href=#address2Line1 name="address2Line1">address2Line1</a>

Type the first line of the customer's address to help identify the location.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 1</td></tr><tr><td>description</td><td>Type the first line of the customer's address to help identify the location.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>line1</td></tr></table>

### <a href=#address2Line2 name="address2Line2">address2Line2</a>

Type the second line of the customer's address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 2</td></tr><tr><td>description</td><td>Type the second line of the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>line2</td></tr></table>

### <a href=#address2Line3 name="address2Line3">address2Line3</a>

Type the third line of the customer's address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 3</td></tr><tr><td>description</td><td>Type the third line of the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>line3</td></tr></table>

### <a href=#address2City name="address2City">address2City</a>

Type the city for the customer's address to help identify the location.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>City</td></tr><tr><td>description</td><td>Type the city for the customer's address to help identify the location.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>city</td></tr></table>

### <a href=#address2StateOrProvince name="address2StateOrProvince">address2StateOrProvince</a>

Type the state or province of the customer's address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State/Province</td></tr><tr><td>description</td><td>Type the state or province of the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stateorprovince</td></tr></table>

### <a href=#address2County name="address2County">address2County</a>

Type the county for the customer's address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>County</td></tr><tr><td>description</td><td>Type the county for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>county</td></tr></table>

### <a href=#address2Country name="address2Country">address2Country</a>

Type the country or region for the customer's address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country/Region</td></tr><tr><td>description</td><td>Type the country or region for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>country</td></tr></table>

### <a href=#address2PostOfficeBox name="address2PostOfficeBox">address2PostOfficeBox</a>

Type the post office box number of the customer's address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Post Office Box</td></tr><tr><td>description</td><td>Type the post office box number of the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postofficebox</td></tr></table>

### <a href=#address2PostalCode name="address2PostalCode">address2PostalCode</a>

Type the ZIP Code or postal code for the address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ZIP/Postal Code</td></tr><tr><td>description</td><td>Type the ZIP Code or postal code for the address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postalcode</td></tr></table>

### <a href=#address2UTCOffset name="address2UTCOffset">address2UTCOffset</a>

Select the time zone for the address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Offset</td></tr><tr><td>description</td><td>Select the time zone for the address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumValue</td><td>1500</td></tr><tr><td>minimumValue</td><td>-1500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcoffset</td></tr></table>

### <a href=#address2FreightTermsCode name="address2FreightTermsCode">address2FreightTermsCode</a>

Select the freight terms to make sure shipping charges are processed correctly.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Freight Terms</td></tr><tr><td>description</td><td>Select the freight terms to make sure shipping charges are processed correctly.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>freighttermscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>FOB</td><td>1</td></tr><tr><td>en</td><td>No Charge</td><td>2</td></tr></table></td></tr></table>

### <a href=#address2FreightTermsCode_display name="address2FreightTermsCode_display">address2FreightTermsCode_display</a>

First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address2UPSZone name="address2UPSZone">address2UPSZone</a>

Type the UPS zone of the customer's address to make sure shipping charges are calculated correctly and deliveries are made promptly, if shipped by UPS.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UPS Zone</td></tr><tr><td>description</td><td>Type the UPS zone of the customer's address to make sure shipping charges are calculated correctly and deliveries are made promptly, if shipped by UPS.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>upszone</td></tr></table>

### <a href=#address2Latitude name="address2Latitude">address2Latitude</a>

Type the latitude value for the customer's address, for use in mapping and other applications.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Latitude</td></tr><tr><td>description</td><td>Type the latitude value for the customer's address, for use in mapping and other applications.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>90</td></tr><tr><td>minimumValue</td><td>-90</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>latitude</td></tr></table>

### <a href=#address2Telephone1 name="address2Telephone1">address2Telephone1</a>

Type the primary phone number for the customer's address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Main Phone</td></tr><tr><td>description</td><td>Type the primary phone number for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone1</td></tr></table>

### <a href=#address2Longitude name="address2Longitude">address2Longitude</a>

Type the longitude value for the customer's address, for use in mapping and other applications.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Longitude</td></tr><tr><td>description</td><td>Type the longitude value for the customer's address, for use in mapping and other applications.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>180</td></tr><tr><td>minimumValue</td><td>-180</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>longitude</td></tr></table>

### <a href=#address2ShippingMethodCode name="address2ShippingMethodCode">address2ShippingMethodCode</a>

Select a shipping method for deliveries sent to this address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping Method</td></tr><tr><td>description</td><td>Select a shipping method for deliveries sent to this address.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shippingmethodcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Airborne</td><td>1</td></tr><tr><td>en</td><td>DHL</td><td>2</td></tr><tr><td>en</td><td>FedEx</td><td>3</td></tr><tr><td>en</td><td>UPS</td><td>4</td></tr><tr><td>en</td><td>Postal Mail</td><td>5</td></tr><tr><td>en</td><td>Full Load</td><td>6</td></tr><tr><td>en</td><td>Will Call</td><td>7</td></tr></table></td></tr></table>

### <a href=#address2ShippingMethodCode_display name="address2ShippingMethodCode_display">address2ShippingMethodCode_display</a>

First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address2Telephone2 name="address2Telephone2">address2Telephone2</a>

Type a second phone number for the customer's address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Phone 2</td></tr><tr><td>description</td><td>Type a second phone number for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone2</td></tr></table>

### <a href=#address2Telephone3 name="address2Telephone3">address2Telephone3</a>

Type a third phone number for the customer's address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Telephone 3</td></tr><tr><td>description</td><td>Type a third phone number for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone3</td></tr></table>

### <a href=#address2Fax name="address2Fax">address2Fax</a>

Type the fax number associated with the customer's address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fax</td></tr><tr><td>description</td><td>Type the fax number associated with the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>fax</td></tr></table>

### <a href=#address2Composite name="address2Composite">address2Composite</a>

Shows the complete address.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address</td></tr><tr><td>description</td><td>Shows the complete address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>composite</td></tr></table>

### <a href=#preferredAppointmentDayCode name="preferredAppointmentDayCode">preferredAppointmentDayCode</a>

Select the preferred day of the week for service appointments.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Preferred Day</td></tr><tr><td>description</td><td>Select the preferred day of the week for service appointments.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>preferredappointmentdaycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Sunday</td><td>0</td></tr><tr><td>en</td><td>Monday</td><td>1</td></tr><tr><td>en</td><td>Tuesday</td><td>2</td></tr><tr><td>en</td><td>Wednesday</td><td>3</td></tr><tr><td>en</td><td>Thursday</td><td>4</td></tr><tr><td>en</td><td>Friday</td><td>5</td></tr><tr><td>en</td><td>Saturday</td><td>6</td></tr></table></td></tr></table>

### <a href=#preferredAppointmentDayCode_display name="preferredAppointmentDayCode_display">preferredAppointmentDayCode_display</a>

First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#preferredSystemUserId name="preferredSystemUserId">preferredSystemUserId</a>

Choose the preferred service representative for reference when you schedule service activities for the account.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Preferred User</td></tr><tr><td>description</td><td>Choose the preferred service representative for reference when you schedule service activities for the account.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>preferredsystemuserid</td></tr></table>

### <a href=#preferredAppointmentTimeCode name="preferredAppointmentTimeCode">preferredAppointmentTimeCode</a>

Select the preferred time of day for service appointments.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Preferred Time</td></tr><tr><td>description</td><td>Select the preferred time of day for service appointments.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>preferredappointmenttimecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Morning</td><td>1</td></tr><tr><td>en</td><td>Afternoon</td><td>2</td></tr><tr><td>en</td><td>Evening</td><td>3</td></tr></table></td></tr></table>

### <a href=#preferredAppointmentTimeCode_display name="preferredAppointmentTimeCode_display">preferredAppointmentTimeCode_display</a>

First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#merged name="merged">merged</a>

Shows whether the account has been merged with another account.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Merged</td></tr><tr><td>description</td><td>Shows whether the account has been merged with another account.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>merged</td></tr></table>

### <a href=#doNotSendMM name="doNotSendMM">doNotSendMM</a>

Select whether the account accepts marketing materials, such as brochures or catalogs.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Send Marketing Materials</td></tr><tr><td>description</td><td>Select whether the account accepts marketing materials, such as brochures or catalogs.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>donotsendmm</td></tr></table>

### <a href=#masterId name="masterId">masterId</a>

Shows the master account that the account was merged with.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Master ID</td></tr><tr><td>description</td><td>Shows the master account that the account was merged with.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>masterid</td></tr></table>

### <a href=#lastUsedInCampaign name="lastUsedInCampaign">lastUsedInCampaign</a>

Shows the date when the account was last included in a marketing campaign or quick campaign.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Date Included in Campaign</td></tr><tr><td>description</td><td>Shows the date when the account was last included in a marketing campaign or quick campaign.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastusedincampaign</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#creditLimitBase name="creditLimitBase">creditLimitBase</a>

Shows the credit limit converted to the system's default base currency for reporting purposes.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credit Limit (Base)</td></tr><tr><td>description</td><td>Shows the credit limit converted to the system's default base currency for reporting purposes.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>creditlimit_base</td></tr></table>

### <a href=#aging30Base name="aging30Base">aging30Base</a>

The base currency equivalent of the aging 30 field.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aging 30 (Base)</td></tr><tr><td>description</td><td>The base currency equivalent of the aging 30 field.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>aging30_base</td></tr></table>

### <a href=#revenueBase name="revenueBase">revenueBase</a>

Shows the annual revenue converted to the system's default base currency. The calculations use the exchange rate specified in the Currencies area.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Annual Revenue (Base)</td></tr><tr><td>description</td><td>Shows the annual revenue converted to the system's default base currency. The calculations use the exchange rate specified in the Currencies area.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>revenue_base</td></tr></table>

### <a href=#aging90Base name="aging90Base">aging90Base</a>

The base currency equivalent of the aging 90 field.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aging 90 (Base)</td></tr><tr><td>description</td><td>The base currency equivalent of the aging 90 field.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>aging90_base</td></tr></table>

### <a href=#marketCapBase name="marketCapBase">marketCapBase</a>

Shows the market capitalization converted to the system's default base currency.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Market Capitalization (Base)</td></tr><tr><td>description</td><td>Shows the market capitalization converted to the system's default base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>marketcap_base</td></tr></table>

### <a href=#aging60Base name="aging60Base">aging60Base</a>

The base currency equivalent of the aging 60 field.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aging 60 (Base)</td></tr><tr><td>description</td><td>The base currency equivalent of the aging 60 field.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>aging60_base</td></tr></table>

### <a href=#yomiName name="yomiName">yomiName</a>

Type the phonetic spelling of the company name, if specified in Japanese, to make sure the name is pronounced correctly in phone calls and other communications.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Yomi Account Name</td></tr><tr><td>description</td><td>Type the phonetic spelling of the company name, if specified in Japanese, to make sure the name is pronounced correctly in phone calls and other communications.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>yominame</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Shows the ID of the stage.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Stage</td></tr><tr><td>description</td><td>Shows the ID of the stage.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#processId name="processId">processId</a>

Shows the ID of the process.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process</td></tr><tr><td>description</td><td>Shows the ID of the process.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#entityImageId name="entityImageId">entityImageId</a>

For internal use only.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Entity Image Id</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entityimageid</td></tr></table>

### <a href=#timeSpentByMeOnEmailAndMeetings name="timeSpentByMeOnEmailAndMeetings">timeSpentByMeOnEmailAndMeetings</a>

Total time spent for emails (read and write) and meetings by me in relation to account record.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Spent by me</td></tr><tr><td>description</td><td>Total time spent for emails (read and write) and meetings by me in relation to account record.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timespentbymeonemailandmeetings</td></tr></table>

### <a href=#createdByExternalParty name="createdByExternalParty">createdByExternalParty</a>

Shows the external party who created the record.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (External Party)</td></tr><tr><td>description</td><td>Shows the external party who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdbyexternalparty</td></tr></table>

### <a href=#modifiedByExternalParty name="modifiedByExternalParty">modifiedByExternalParty</a>

Shows the external party who modified the record.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (External Party)</td></tr><tr><td>description</td><td>Shows the external party who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedbyexternalparty</td></tr></table>

### <a href=#primarySatoriId name="primarySatoriId">primarySatoriId</a>

Primary Satori ID for Account  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary Satori ID</td></tr><tr><td>description</td><td>Primary Satori ID for Account</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>primarysatoriid</td></tr></table>

### <a href=#primaryTwitterId name="primaryTwitterId">primaryTwitterId</a>

Primary Twitter ID for Account  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary Twitter ID</td></tr><tr><td>description</td><td>Primary Twitter ID for Account</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>128</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>primarytwitterid</td></tr></table>

### <a href=#SLAId name="SLAId">SLAId</a>

Choose the service level agreement (SLA) that you want to apply to the Account record.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SLA</td></tr><tr><td>description</td><td>Choose the service level agreement (SLA) that you want to apply to the Account record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slaid</td></tr></table>

### <a href=#SLAInvokedId name="SLAInvokedId">SLAInvokedId</a>

Last SLA that was applied to this case. This field is for internal use only.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last SLA applied</td></tr><tr><td>description</td><td>Last SLA that was applied to this case. This field is for internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slainvokedid</td></tr></table>

### <a href=#onHoldTime name="onHoldTime">onHoldTime</a>

Shows how long, in minutes, that the record was on hold.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>On Hold Time (Minutes)</td></tr><tr><td>description</td><td>Shows how long, in minutes, that the record was on hold.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>onholdtime</td></tr></table>

### <a href=#lastOnHoldTime name="lastOnHoldTime">lastOnHoldTime</a>

Contains the date and time stamp of the last on hold time.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last On Hold Time</td></tr><tr><td>description</td><td>Contains the date and time stamp of the last on hold time.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastonholdtime</td></tr></table>

### <a href=#followEmail name="followEmail">followEmail</a>

Information about whether to allow following email activity like opens, attachment views and link clicks for emails sent to the account.  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Follow Email Activity</td></tr><tr><td>description</td><td>Information about whether to allow following email activity like opens, attachment views and link clicks for emails sent to the account.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>followemail</td></tr></table>

### <a href=#marketingOnly name="marketingOnly">marketingOnly</a>

Whether is only for marketing  
First included in: <a href="../../../../../Account.md" target="_blank">applicationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Marketing Only</td></tr><tr><td>description</td><td>Whether is only for marketing</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>marketingonly</td></tr></table>

### <a href=#defaultPriceLevelId name="defaultPriceLevelId">defaultPriceLevelId</a>

Choose the default price list associated with the account to make sure the correct product prices for this customer are applied in sales opportunities, quotes, and orders.  
First included in: <a href="../../../../Account.md" target="_blank">foundationCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price List</td></tr><tr><td>description</td><td>Choose the default price list associated with the account to make sure the correct product prices for this customer are applied in sales opportunities, quotes, and orders.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>defaultpricelevelid</td></tr></table>

### <a href=#originatingLeadId name="originatingLeadId">originatingLeadId</a>

Shows the lead that the account was created from if the account was created by converting a lead in Microsoft Dynamics 365. This is used to relate the account to data on the originating lead for use in reporting and analytics.  
First included in: <a href="../../../Account.md" target="_blank">crmCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Originating Lead</td></tr><tr><td>description</td><td>Shows the lead that the account was created from if the account was created by converting a lead in Microsoft Dynamics 365. This is used to relate the account to data on the originating lead for use in reporting and analytics.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>originatingleadid</td></tr></table>

### <a href=#preferredEquipmentId name="preferredEquipmentId">preferredEquipmentId</a>

Choose the account's preferred service facility or equipment to make sure services are scheduled correctly for the customer.  
First included in: <a href="../../../Account.md" target="_blank">crmCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Preferred Facility/Equipment</td></tr><tr><td>description</td><td>Choose the account's preferred service facility or equipment to make sure services are scheduled correctly for the customer.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>preferredequipmentid</td></tr></table>

### <a href=#preferredServiceId name="preferredServiceId">preferredServiceId</a>

Choose the account's preferred service for reference when you schedule service activities.  
First included in: <a href="../../../Account.md" target="_blank">crmCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Preferred Service</td></tr><tr><td>description</td><td>Choose the account's preferred service for reference when you schedule service activities.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>preferredserviceid</td></tr></table>

### <a href=#territoryId name="territoryId">territoryId</a>

Choose the sales region or territory for the account to make sure the account is assigned to the correct representative and for use in segmentation and analysis.  
First included in: <a href="../../../Account.md" target="_blank">crmCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Territory</td></tr><tr><td>description</td><td>Choose the sales region or territory for the account to make sure the account is assigned to the correct representative and for use in segmentation and analysis.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>territoryid</td></tr></table>

### <a href=#openDeals name="openDeals">openDeals</a>

Number of open opportunities against an account and its child accounts.  
First included in: <a href="../../../Account.md" target="_blank">crmCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Open Deals</td></tr><tr><td>description</td><td>Number of open opportunities against an account and its child accounts.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>opendeals</td></tr></table>

### <a href=#openDealsDate name="openDealsDate">openDealsDate</a>

Last Updated time of rollup field Open Deals.  
First included in: <a href="../../../Account.md" target="_blank">crmCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Open Deals (Last Updated On)</td></tr><tr><td>description</td><td>Last Updated time of rollup field Open Deals.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>opendeals_date</td></tr></table>

### <a href=#openDealsState name="openDealsState">openDealsState</a>

State of rollup field Open Deals.  
First included in: <a href="../../../Account.md" target="_blank">crmCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Open Deals (State)</td></tr><tr><td>description</td><td>State of rollup field Open Deals.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>opendeals_state</td></tr></table>

### <a href=#openRevenue name="openRevenue">openRevenue</a>

Sum of open revenue against an account and its child accounts.  
First included in: <a href="../../../Account.md" target="_blank">crmCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Open Revenue</td></tr><tr><td>description</td><td>Sum of open revenue against an account and its child accounts.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>openrevenue</td></tr></table>

### <a href=#openRevenueBase name="openRevenueBase">openRevenueBase</a>

Value of the Open Revenue in base currency.  
First included in: <a href="../../../Account.md" target="_blank">crmCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Open Revenue (Base)</td></tr><tr><td>description</td><td>Value of the Open Revenue in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>openrevenue_base</td></tr></table>

### <a href=#openRevenueDate name="openRevenueDate">openRevenueDate</a>

Last Updated time of rollup field Open Revenue.  
First included in: <a href="../../../Account.md" target="_blank">crmCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Open Revenue (Last Updated On)</td></tr><tr><td>description</td><td>Last Updated time of rollup field Open Revenue.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>openrevenue_date</td></tr></table>

### <a href=#openRevenueState name="openRevenueState">openRevenueState</a>

State of rollup field Open Revenue.  
First included in: <a href="../../../Account.md" target="_blank">crmCommon/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Open Revenue (State)</td></tr><tr><td>description</td><td>State of rollup field Open Revenue.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>openrevenue_state</td></tr></table>

### <a href=#adxCreatedByIPAddress name="adxCreatedByIPAddress">adxCreatedByIPAddress</a>

First included in: <a href="../../portals/Account.md" target="_blank">portals/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (IP Address)</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_createdbyipaddress</td></tr></table>

### <a href=#adxCreatedByUsername name="adxCreatedByUsername">adxCreatedByUsername</a>

First included in: <a href="../../portals/Account.md" target="_blank">portals/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (User Name)</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_createdbyusername</td></tr></table>

### <a href=#adxModifiedByIPAddress name="adxModifiedByIPAddress">adxModifiedByIPAddress</a>

First included in: <a href="../../portals/Account.md" target="_blank">portals/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (IP Address)</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_modifiedbyipaddress</td></tr></table>

### <a href=#adxModifiedByUsername name="adxModifiedByUsername">adxModifiedByUsername</a>

First included in: <a href="../../portals/Account.md" target="_blank">portals/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (User Name)</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_modifiedbyusername</td></tr></table>

### <a href=#managingPartner name="managingPartner">managingPartner</a>

Unique identifier for Account associated with Account.  
First included in: <a href="../../portals/Account.md" target="_blank">portals/Account</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Managing Partner</td></tr><tr><td>description</td><td>Unique identifier for Account associated with Account.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msa_managingpartnerid</td></tr></table>

### <a href=#hotelGroup name="hotelGroup">hotelGroup</a>

Whether this account belongs to hotel group or not  
First included in: eventManagement/Account (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Hotel Group</td></tr><tr><td>description</td><td>Whether this account belongs to hotel group or not</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_hotelgroup</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>No</td><td>100000001</td></tr><tr><td>en</td><td>Yes</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#hotelGroup_display name="hotelGroup_display">hotelGroup_display</a>

First included in: eventManagement/Account (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#rentalCarProvider name="rentalCarProvider">rentalCarProvider</a>

First included in: eventManagement/Account (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rental Car Provider</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_rentalcarprovider</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>No</td><td>100000001</td></tr><tr><td>en</td><td>Yes</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#rentalCarProvider_display name="rentalCarProvider_display">rentalCarProvider_display</a>

First included in: eventManagement/Account (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
