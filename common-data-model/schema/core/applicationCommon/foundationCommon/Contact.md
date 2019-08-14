---
title: Contact - Common Data Model | Microsoft Docs
description: Person with whom a business unit has a relationship, such as a customer, a supplier, or a colleague.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Contact

Person with whom a business unit has a relationship, such as a customer, a supplier, or a colleague.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/Contact.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- [/Contact](../Contact.md "/core/applicationCommon/Contact.cdm.json/Contact")  
- /foundationCommon/Contact  
- [/foundationCommon/crmCommon/Contact](crmCommon/Contact.md "/core/applicationCommon/foundationCommon/crmCommon/Contact.cdm.json/Contact")  
- [/foundationCommon/crmCommon/accelerators/education/higherEducation/Contact](crmCommon/accelerators/education/higherEducation/Contact.md "/core/applicationCommon/foundationCommon/crmCommon/accelerators/education/higherEducation/Contact.cdm.json/Contact")  
- [/foundationCommon/crmCommon/accelerators/financialServices/banking/Contact](crmCommon/accelerators/financialServices/banking/Contact.md "/core/applicationCommon/foundationCommon/crmCommon/accelerators/financialServices/banking/Contact.cdm.json/Contact")  
- [/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/Contact](crmCommon/accelerators/healthCare/electronicMedicalRecords/Contact.md "/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/Contact.cdm.json/Contact")  
- [/foundationCommon/crmCommon/accelerators/nonProfit/Contact](crmCommon/accelerators/nonProfit/Contact.md "/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/Contact.cdm.json/Contact")  
- [/foundationCommon/crmCommon/projectCommon/Contact](crmCommon/projectCommon/Contact.md "/core/applicationCommon/foundationCommon/crmCommon/projectCommon/Contact.cdm.json/Contact")  
- [/foundationCommon/crmCommon/solutions/marketing/Contact](crmCommon/solutions/marketing/Contact.md "/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Contact.cdm.json/Contact")  
- [/foundationCommon/crmCommon/solutions/portals/Contact](crmCommon/solutions/portals/Contact.md "/core/applicationCommon/foundationCommon/crmCommon/solutions/portals/Contact.cdm.json/Contact")  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[ownerIdType](#ownerIdType)||<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[ownerId](#ownerId)||<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[contactId](#contactId)|Unique identifier of the contact.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[customerSizeCode](#customerSizeCode)|Select the size of the contact's company for segmentation and reporting purposes.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[customerSizeCode_display](#customerSizeCode_display)||<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[customerTypeCode](#customerTypeCode)|Select the category that best describes the relationship between the contact and your organization.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[customerTypeCode_display](#customerTypeCode_display)||<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[preferredContactMethodCode](#preferredContactMethodCode)|Select the preferred method of contact.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[preferredContactMethodCode_display](#preferredContactMethodCode_display)||<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[leadSourceCode](#leadSourceCode)|Select the primary marketing source that directed the contact to your organization.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[leadSourceCode_display](#leadSourceCode_display)||<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[paymentTermsCode](#paymentTermsCode)|Select the payment terms to indicate when the customer needs to pay the total amount.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[paymentTermsCode_display](#paymentTermsCode_display)||<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[shippingMethodCode](#shippingMethodCode)|Select a shipping method for deliveries sent to this address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[shippingMethodCode_display](#shippingMethodCode_display)||<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[accountId](#accountId)|Unique identifier of the account with which the contact is associated.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[participatesInWorkflow](#participatesInWorkflow)|Shows whether the contact participates in workflow rules.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[isBackofficeCustomer](#isBackofficeCustomer)|Select whether the contact exists in a separate accounting or other system, such as Microsoft Dynamics GP or another ERP database, for use in integration processes.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[salutation](#salutation)|Type the salutation of the contact to make sure the contact is addressed correctly in sales calls, email messages, and marketing campaigns.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[jobTitle](#jobTitle)|Type the job title of the contact to make sure the contact is addressed correctly in sales calls, email, and marketing campaigns.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[firstName](#firstName)|Type the contact's first name to make sure the contact is addressed correctly in sales calls, email, and marketing campaigns.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[department](#department)|Type the department or business unit where the contact works in the parent company or business.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[nickName](#nickName)|Type the contact's nickname.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[middleName](#middleName)|Type the contact's middle name or initial to make sure the contact is addressed correctly.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[lastName](#lastName)|Type the contact's last name to make sure the contact is addressed correctly in sales calls, email, and marketing campaigns.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[suffix](#suffix)|Type the suffix used in the contact's name, such as Jr. or Sr. to make sure the contact is addressed correctly in sales calls, email, and marketing campaigns.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[yomiFirstName](#yomiFirstName)|Type the phonetic spelling of the contact's first name, if the name is specified in Japanese, to make sure the name is pronounced correctly in phone calls with the contact.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[fullName](#fullName)|Combines and shows the contact's first and last names so that the full name can be displayed in views and reports.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[yomiMiddleName](#yomiMiddleName)|Type the phonetic spelling of the contact's middle name, if the name is specified in Japanese, to make sure the name is pronounced correctly in phone calls with the contact.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[yomiLastName](#yomiLastName)|Type the phonetic spelling of the contact's last name, if the name is specified in Japanese, to make sure the name is pronounced correctly in phone calls with the contact.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[anniversary](#anniversary)|Enter the date of the contact's wedding or service anniversary for use in customer gift programs or other communications.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[birthDate](#birthDate)|Enter the contact's birthday for use in customer gift programs or other communications.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[governmentId](#governmentId)|Type the passport number or other government ID for the contact for use in documents or reports.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[yomiFullName](#yomiFullName)|Shows the combined Yomi first and last names of the contact so that the full phonetic name can be displayed in views and reports.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[description](#description)|Type additional information to describe the contact, such as an excerpt from the company's website.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[employeeId](#employeeId)|Type the employee ID or number for the contact for reference in orders, service cases, or other communications with the contact's organization.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[genderCode](#genderCode)|Select the contact's gender to make sure the contact is addressed correctly in sales calls, email, and marketing campaigns.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[genderCode_display](#genderCode_display)||<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[annualIncome](#annualIncome)|Type the contact's annual income for use in profiling and financial analysis.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[hasChildrenCode](#hasChildrenCode)|Select whether the contact has any children for reference in follow-up phone calls and other communications.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[hasChildrenCode_display](#hasChildrenCode_display)||<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[educationCode](#educationCode)|Select the contact's highest level of education for use in segmentation and analysis.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[educationCode_display](#educationCode_display)||<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[webSiteUrl](#webSiteUrl)|Type the contact's professional or personal website or blog URL.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[familyStatusCode](#familyStatusCode)|Select the marital status of the contact for reference in follow-up phone calls and other communications.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[familyStatusCode_display](#familyStatusCode_display)||<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[ftpSiteUrl](#ftpSiteUrl)|Type the URL for the contact's FTP site to enable users to access data and share documents.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[EMailAddress1](#EMailAddress1)|Type the primary email address for the contact.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[spousesName](#spousesName)|Type the name of the contact's spouse or partner for reference during calls, events, or other communications with the contact.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[assistantName](#assistantName)|Type the name of the contact's assistant.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[EMailAddress2](#EMailAddress2)|Type the secondary email address for the contact.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[assistantPhone](#assistantPhone)|Type the phone number for the contact's assistant.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[EMailAddress3](#EMailAddress3)|Type an alternate email address for the contact.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[doNotPhone](#doNotPhone)|Select whether the contact accepts phone calls. If Do Not Allow is selected, the contact will be excluded from any phone call activities distributed in marketing campaigns.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[managerName](#managerName)|Type the name of the contact's manager for use in escalating issues or other follow-up communications with the contact.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[managerPhone](#managerPhone)|Type the phone number for the contact's manager.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[doNotFax](#doNotFax)|Select whether the contact allows faxes. If Do Not Allow is selected, the contact will be excluded from any fax activities distributed in marketing campaigns.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[doNotEMail](#doNotEMail)|Select whether the contact allows direct email sent from Microsoft Dynamics 365. If Do Not Allow is selected, Microsoft Dynamics 365 will not send the email.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[doNotPostalMail](#doNotPostalMail)|Select whether the contact allows direct mail. If Do Not Allow is selected, the contact will be excluded from letter activities distributed in marketing campaigns.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[doNotBulkEMail](#doNotBulkEMail)|Select whether the contact accepts bulk email sent through marketing campaigns or quick campaigns. If Do Not Allow is selected, the contact can be added to marketing lists, but will be excluded from the email.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[doNotBulkPostalMail](#doNotBulkPostalMail)|Select whether the contact accepts bulk postal mail sent through marketing campaigns or quick campaigns. If Do Not Allow is selected, the contact can be added to marketing lists, but will be excluded from the letters.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[accountRoleCode](#accountRoleCode)|Select the contact's role within the company or sales process, such as decision maker, employee, or influencer.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[accountRoleCode_display](#accountRoleCode_display)||<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[territoryCode](#territoryCode)|Select a region or territory for the contact for use in segmentation and analysis.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[territoryCode_display](#territoryCode_display)||<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[creditLimit](#creditLimit)|Type the credit limit of the contact for reference when you address invoice and accounting issues with the customer.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[creditOnHold](#creditOnHold)|Select whether the contact is on a credit hold, for reference when addressing invoice and accounting issues.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[numberOfChildren](#numberOfChildren)|Type the number of children the contact has for reference in follow-up phone calls and other communications.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[childrensNames](#childrensNames)|Type the names of the contact's children for reference in communications and client programs.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[mobilePhone](#mobilePhone)|Type the mobile phone number for the contact.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[pager](#pager)|Type the pager number for the contact.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[telephone1](#telephone1)|Type the main phone number for this contact.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[telephone2](#telephone2)|Type a second phone number for this contact.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[telephone3](#telephone3)|Type a third phone number for this contact.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[fax](#fax)|Type the fax number for the contact.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[aging30](#aging30)|For system use only.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[stateCode](#stateCode)|Shows whether the contact is active or inactive. Inactive contacts are read-only and can't be edited unless they are reactivated.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[stateCode_display](#stateCode_display)||<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[aging60](#aging60)|For system use only.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[statusCode](#statusCode)|Select the contact's status.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[statusCode_display](#statusCode_display)||<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[aging90](#aging90)|For system use only.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[parentContactId](#parentContactId)|Unique identifier of the parent contact.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address1AddressId](#address1AddressId)|Unique identifier for address n.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address1AddressTypeCode](#address1AddressTypeCode)|Select the address type, such as primary or billing.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address1AddressTypeCode_display](#address1AddressTypeCode_display)||<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address1Name](#address1Name)|Type a descriptive name for the customer's address, such as Corporate Headquarters.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address1PrimaryContactName](#address1PrimaryContactName)|Type the name of the primary contact person for the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address1Line1](#address1Line1)|Type the first line of the customer's address to help identify the location.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address1Line2](#address1Line2)|Type the second line of the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address1Line3](#address1Line3)|Type the third line of the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address1City](#address1City)|Type the city for the customer's address to help identify the location.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address1StateOrProvince](#address1StateOrProvince)|Type the state or province of the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address1County](#address1County)|Type the county for the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address1Country](#address1Country)|Type the country or region for the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address1PostOfficeBox](#address1PostOfficeBox)|Type the post office box number of the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address1PostalCode](#address1PostalCode)|Type the ZIP Code or postal code for the address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address1UTCOffset](#address1UTCOffset)|Select the time zone for the address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address1FreightTermsCode](#address1FreightTermsCode)|Select the freight terms to make sure shipping charges are processed correctly.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address1FreightTermsCode_display](#address1FreightTermsCode_display)||<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address1UPSZone](#address1UPSZone)|Type the UPS zone of the customer's address to make sure shipping charges are calculated correctly and deliveries are made promptly, if shipped by UPS.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address1Latitude](#address1Latitude)|Type the latitude value for the customer's address, for use in mapping and other applications.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address1Telephone1](#address1Telephone1)|Type the primary phone number for the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address1Longitude](#address1Longitude)|Type the longitude value for the customer's address, for use in mapping and other applications.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address1ShippingMethodCode](#address1ShippingMethodCode)|Select a shipping method for deliveries sent to this address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address1ShippingMethodCode_display](#address1ShippingMethodCode_display)||<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address1Telephone2](#address1Telephone2)|Type a second phone number for the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address1Telephone3](#address1Telephone3)|Type a third phone number for the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address1Fax](#address1Fax)|Type the fax number associated with the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address1Composite](#address1Composite)|Shows the complete address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address2AddressId](#address2AddressId)|Unique identifier for address n.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address2AddressTypeCode](#address2AddressTypeCode)|Select the address type, such as primary or billing.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address2AddressTypeCode_display](#address2AddressTypeCode_display)||<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address2Name](#address2Name)|Type a descriptive name for the customer's address, such as Corporate Headquarters.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address2PrimaryContactName](#address2PrimaryContactName)|Type the name of the primary contact person for the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address2Line1](#address2Line1)|Type the first line of the customer's address to help identify the location.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address2Line2](#address2Line2)|Type the second line of the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address2Line3](#address2Line3)|Type the third line of the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address2City](#address2City)|Type the city for the customer's address to help identify the location.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address2StateOrProvince](#address2StateOrProvince)|Type the state or province of the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address2County](#address2County)|Type the county for the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address2Country](#address2Country)|Type the country or region for the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address2PostOfficeBox](#address2PostOfficeBox)|Type the post office box number of the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address2PostalCode](#address2PostalCode)|Type the ZIP Code or postal code for the address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address2UTCOffset](#address2UTCOffset)|Select the time zone for the address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address2FreightTermsCode](#address2FreightTermsCode)|Select the freight terms to make sure shipping charges are processed correctly.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address2FreightTermsCode_display](#address2FreightTermsCode_display)||<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address2UPSZone](#address2UPSZone)|Type the UPS zone of the customer's address to make sure shipping charges are calculated correctly and deliveries are made promptly, if shipped by UPS.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address2Latitude](#address2Latitude)|Type the latitude value for the customer's address, for use in mapping and other applications.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address2Telephone1](#address2Telephone1)|Type the primary phone number for the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address2Longitude](#address2Longitude)|Type the longitude value for the customer's address, for use in mapping and other applications.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address2ShippingMethodCode](#address2ShippingMethodCode)|Select a shipping method for deliveries sent to this address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address2ShippingMethodCode_display](#address2ShippingMethodCode_display)||<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address2Telephone2](#address2Telephone2)|Type a second phone number for the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address2Telephone3](#address2Telephone3)|Type a third phone number for the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address2Fax](#address2Fax)|Type the fax number associated with the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address2Composite](#address2Composite)|Shows the complete address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address3AddressId](#address3AddressId)|Unique identifier for address n.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address3AddressTypeCode](#address3AddressTypeCode)|Select the address type, such as primary or billing.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address3AddressTypeCode_display](#address3AddressTypeCode_display)||<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address3Name](#address3Name)|Type a descriptive name for the customer's address, such as Corporate Headquarters.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address3PrimaryContactName](#address3PrimaryContactName)|Type the name of the primary contact person for the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address3Line1](#address3Line1)|Type the first line of the customer's address to help identify the location.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address3Line2](#address3Line2)|Type the second line of the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address3Line3](#address3Line3)|Type the third line of the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address3City](#address3City)|Type the city for the customer's address to help identify the location.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address3StateOrProvince](#address3StateOrProvince)|Type the state or province of the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address3County](#address3County)|Type the county for the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address3Country](#address3Country)|Type the country or region for the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address3PostOfficeBox](#address3PostOfficeBox)|Type the post office box number of the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address3PostalCode](#address3PostalCode)|Type the ZIP Code or postal code for the address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address3UTCOffset](#address3UTCOffset)|Select the time zone for the address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address3FreightTermsCode](#address3FreightTermsCode)|Select the freight terms to make sure shipping charges are processed correctly.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address3FreightTermsCode_display](#address3FreightTermsCode_display)||<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address3UPSZone](#address3UPSZone)|Type the UPS zone of the customer's address to make sure shipping charges are calculated correctly and deliveries are made promptly, if shipped by UPS.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address3Latitude](#address3Latitude)|Type the latitude value for the customer's address, for use in mapping and other applications.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address3Telephone1](#address3Telephone1)|Type the primary phone number for the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address3Longitude](#address3Longitude)|Type the longitude value for the customer's address, for use in mapping and other applications.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address3ShippingMethodCode](#address3ShippingMethodCode)|Select a shipping method for deliveries sent to this address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address3ShippingMethodCode_display](#address3ShippingMethodCode_display)||<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address3Telephone2](#address3Telephone2)|Type a second phone number for the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address3Telephone3](#address3Telephone3)|Type a third phone number for the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address3Fax](#address3Fax)|Type the fax number associated with the customer's address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[address3Composite](#address3Composite)|Shows the complete address.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[preferredSystemUserId](#preferredSystemUserId)|Choose the regular or preferred customer service representative for reference when scheduling service activities for the contact.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[masterId](#masterId)|Unique identifier of the master contact for merge.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[preferredAppointmentDayCode](#preferredAppointmentDayCode)|Select the preferred day of the week for service appointments.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[preferredAppointmentDayCode_display](#preferredAppointmentDayCode_display)||<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[preferredAppointmentTimeCode](#preferredAppointmentTimeCode)|Select the preferred time of day for service appointments.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[preferredAppointmentTimeCode_display](#preferredAppointmentTimeCode_display)||<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[doNotSendMM](#doNotSendMM)|Select whether the contact accepts marketing materials, such as brochures or catalogs. Contacts that opt out can be excluded from marketing initiatives.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[parentCustomerIdType](#parentCustomerIdType)|The type of parent customer, either Account or Contact.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[parentCustomerId](#parentCustomerId)|Select the parent account or parent contact for the contact to provide a quick link to additional details, such as financial information, activities, and opportunities.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[merged](#merged)|Shows whether the account has been merged with a master contact.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[externalUserIdentifier](#externalUserIdentifier)|Identifier for an external user.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[lastUsedInCampaign](#lastUsedInCampaign)|Shows the date when the contact was last included in a marketing campaign or quick campaign.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[annualIncomeBase](#annualIncomeBase)|Shows the Annual Income field converted to the system's default base currency. The calculations use the exchange rate specified in the Currencies area.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[creditLimitBase](#creditLimitBase)|Shows the Credit Limit field converted to the system's default base currency for reporting purposes. The calculations use the exchange rate specified in the Currencies area.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[aging60Base](#aging60Base)|Shows the Aging 60 field converted to the system's default base currency. The calculations use the exchange rate specified in the Currencies area.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[aging90Base](#aging90Base)|Shows the Aging 90 field converted to the system's default base currency. The calculations use the exchange rate specified in the Currencies area.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[aging30Base](#aging30Base)|Shows the Aging 30 field converted to the system's default base currency. The calculations use the exchange rate specified in the Currencies area.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[stageId](#stageId)|Shows the ID of the stage.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[processId](#processId)|Shows the ID of the process.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[entityImageId](#entityImageId)|For internal use only.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[traversedPath](#traversedPath)|For internal use only.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[SLAId](#SLAId)|Choose the service level agreement (SLA) that you want to apply to the Contact record.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[SLAInvokedId](#SLAInvokedId)|Last SLA that was applied to this case. This field is for internal use only.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[onHoldTime](#onHoldTime)|Shows how long, in minutes, that the record was on hold.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[lastOnHoldTime](#lastOnHoldTime)|Contains the date and time stamp of the last on hold time.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[followEmail](#followEmail)|Information about whether to allow following email activity like opens, attachment views and link clicks for emails sent to the contact.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[timeSpentByMeOnEmailAndMeetings](#timeSpentByMeOnEmailAndMeetings)|Total time spent for emails (read and write) and meetings by me in relation to the contact record.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[business2](#business2)|Type a second business phone number for this contact.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[callback](#callback)|Type a callback phone number for this contact.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[company](#company)|Type the company phone of the contact.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[home2](#home2)|Type a second home phone number for this contact.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[createdByExternalParty](#createdByExternalParty)|Shows the external party who created the record.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[modifiedByExternalParty](#modifiedByExternalParty)|Shows the external party who modified the record.|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[marketingOnly](#marketingOnly)|Whether is only for marketing|<a href="../Contact.md" target="_blank">applicationCommon/Contact</a>|
|[defaultPriceLevelId](#defaultPriceLevelId)|Choose the default price list associated with the contact to make sure the correct product prices for this customer are applied in sales opportunities, quotes, and orders.|<a href="Contact.md" target="_blank">foundationCommon/Contact</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#contactId name="contactId">contactId</a>

Unique identifier of the contact.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>description</td><td>Unique identifier of the contact.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msevtmgt_contactid</td></tr></table>

### <a href=#customerSizeCode name="customerSizeCode">customerSizeCode</a>

Select the size of the contact's company for segmentation and reporting purposes.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Size</td></tr><tr><td>description</td><td>Select the size of the contact's company for segmentation and reporting purposes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customersizecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#customerSizeCode_display name="customerSizeCode_display">customerSizeCode_display</a>

First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#customerTypeCode name="customerTypeCode">customerTypeCode</a>

Select the category that best describes the relationship between the contact and your organization.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Relationship Type</td></tr><tr><td>description</td><td>Select the category that best describes the relationship between the contact and your organization.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customertypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#customerTypeCode_display name="customerTypeCode_display">customerTypeCode_display</a>

First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#preferredContactMethodCode name="preferredContactMethodCode">preferredContactMethodCode</a>

Select the preferred method of contact.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Preferred Method of Contact</td></tr><tr><td>description</td><td>Select the preferred method of contact.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>preferredcontactmethodcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Any</td><td>1</td></tr><tr><td>en</td><td>Email</td><td>2</td></tr><tr><td>en</td><td>Phone</td><td>3</td></tr><tr><td>en</td><td>Fax</td><td>4</td></tr><tr><td>en</td><td>Mail</td><td>5</td></tr></table></td></tr></table>

### <a href=#preferredContactMethodCode_display name="preferredContactMethodCode_display">preferredContactMethodCode_display</a>

First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#leadSourceCode name="leadSourceCode">leadSourceCode</a>

Select the primary marketing source that directed the contact to your organization.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lead Source</td></tr><tr><td>description</td><td>Select the primary marketing source that directed the contact to your organization.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>leadsourcecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#leadSourceCode_display name="leadSourceCode_display">leadSourceCode_display</a>

First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#paymentTermsCode name="paymentTermsCode">paymentTermsCode</a>

Select the payment terms to indicate when the customer needs to pay the total amount.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment Terms</td></tr><tr><td>description</td><td>Select the payment terms to indicate when the customer needs to pay the total amount.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>paymenttermscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Net 30</td><td>1</td></tr><tr><td>en</td><td>2% 10, Net 30</td><td>2</td></tr><tr><td>en</td><td>Net 45</td><td>3</td></tr><tr><td>en</td><td>Net 60</td><td>4</td></tr></table></td></tr></table>

### <a href=#paymentTermsCode_display name="paymentTermsCode_display">paymentTermsCode_display</a>

First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#shippingMethodCode name="shippingMethodCode">shippingMethodCode</a>

Select a shipping method for deliveries sent to this address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping Method</td></tr><tr><td>description</td><td>Select a shipping method for deliveries sent to this address.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shippingmethodcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#shippingMethodCode_display name="shippingMethodCode_display">shippingMethodCode_display</a>

First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#accountId name="accountId">accountId</a>

Unique identifier of the account with which the contact is associated.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account</td></tr><tr><td>description</td><td>Unique identifier of the account with which the contact is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>accountid</td></tr></table>

### <a href=#participatesInWorkflow name="participatesInWorkflow">participatesInWorkflow</a>

Shows whether the contact participates in workflow rules.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Participates in Workflow</td></tr><tr><td>description</td><td>Shows whether the contact participates in workflow rules.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>participatesinworkflow</td></tr></table>

### <a href=#isBackofficeCustomer name="isBackofficeCustomer">isBackofficeCustomer</a>

Select whether the contact exists in a separate accounting or other system, such as Microsoft Dynamics GP or another ERP database, for use in integration processes.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Back Office Customer</td></tr><tr><td>description</td><td>Select whether the contact exists in a separate accounting or other system, such as Microsoft Dynamics GP or another ERP database, for use in integration processes.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isbackofficecustomer</td></tr></table>

### <a href=#salutation name="salutation">salutation</a>

Type the salutation of the contact to make sure the contact is addressed correctly in sales calls, email messages, and marketing campaigns.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Salutation</td></tr><tr><td>description</td><td>Type the salutation of the contact to make sure the contact is addressed correctly in sales calls, email messages, and marketing campaigns.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>salutation</td></tr></table>

### <a href=#jobTitle name="jobTitle">jobTitle</a>

Type the job title of the contact to make sure the contact is addressed correctly in sales calls, email, and marketing campaigns.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Job Title</td></tr><tr><td>description</td><td>Type the job title of the contact to make sure the contact is addressed correctly in sales calls, email, and marketing campaigns.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>jobtitle</td></tr></table>

### <a href=#firstName name="firstName">firstName</a>

Type the contact's first name to make sure the contact is addressed correctly in sales calls, email, and marketing campaigns.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>First Name</td></tr><tr><td>description</td><td>Type the contact's first name to make sure the contact is addressed correctly in sales calls, email, and marketing campaigns.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>firstname</td></tr></table>

### <a href=#department name="department">department</a>

Type the department or business unit where the contact works in the parent company or business.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Department</td></tr><tr><td>description</td><td>Type the department or business unit where the contact works in the parent company or business.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>department</td></tr></table>

### <a href=#nickName name="nickName">nickName</a>

Type the contact's nickname.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Nickname</td></tr><tr><td>description</td><td>Type the contact's nickname.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>nickname</td></tr></table>

### <a href=#middleName name="middleName">middleName</a>

Type the contact's middle name or initial to make sure the contact is addressed correctly.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Middle Name</td></tr><tr><td>description</td><td>Type the contact's middle name or initial to make sure the contact is addressed correctly.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>middlename</td></tr></table>

### <a href=#lastName name="lastName">lastName</a>

Type the contact's last name to make sure the contact is addressed correctly in sales calls, email, and marketing campaigns.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Name</td></tr><tr><td>description</td><td>Type the contact's last name to make sure the contact is addressed correctly in sales calls, email, and marketing campaigns.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastname</td></tr></table>

### <a href=#suffix name="suffix">suffix</a>

Type the suffix used in the contact's name, such as Jr. or Sr. to make sure the contact is addressed correctly in sales calls, email, and marketing campaigns.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Suffix</td></tr><tr><td>description</td><td>Type the suffix used in the contact's name, such as Jr. or Sr. to make sure the contact is addressed correctly in sales calls, email, and marketing campaigns.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>suffix</td></tr></table>

### <a href=#yomiFirstName name="yomiFirstName">yomiFirstName</a>

Type the phonetic spelling of the contact's first name, if the name is specified in Japanese, to make sure the name is pronounced correctly in phone calls with the contact.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Yomi First Name</td></tr><tr><td>description</td><td>Type the phonetic spelling of the contact's first name, if the name is specified in Japanese, to make sure the name is pronounced correctly in phone calls with the contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>150</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>yomifirstname</td></tr></table>

### <a href=#fullName name="fullName">fullName</a>

Combines and shows the contact's first and last names so that the full name can be displayed in views and reports.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Full Name</td></tr><tr><td>description</td><td>Combines and shows the contact's first and last names so that the full name can be displayed in views and reports.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>fullname</td></tr></table>

### <a href=#yomiMiddleName name="yomiMiddleName">yomiMiddleName</a>

Type the phonetic spelling of the contact's middle name, if the name is specified in Japanese, to make sure the name is pronounced correctly in phone calls with the contact.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Yomi Middle Name</td></tr><tr><td>description</td><td>Type the phonetic spelling of the contact's middle name, if the name is specified in Japanese, to make sure the name is pronounced correctly in phone calls with the contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>150</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>yomimiddlename</td></tr></table>

### <a href=#yomiLastName name="yomiLastName">yomiLastName</a>

Type the phonetic spelling of the contact's last name, if the name is specified in Japanese, to make sure the name is pronounced correctly in phone calls with the contact.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Yomi Last Name</td></tr><tr><td>description</td><td>Type the phonetic spelling of the contact's last name, if the name is specified in Japanese, to make sure the name is pronounced correctly in phone calls with the contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>150</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>yomilastname</td></tr></table>

### <a href=#anniversary name="anniversary">anniversary</a>

Enter the date of the contact's wedding or service anniversary for use in customer gift programs or other communications.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Anniversary</td></tr><tr><td>description</td><td>Enter the date of the contact's wedding or service anniversary for use in customer gift programs or other communications.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>anniversary</td></tr></table>

### <a href=#birthDate name="birthDate">birthDate</a>

Enter the contact's birthday for use in customer gift programs or other communications.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Birthday</td></tr><tr><td>description</td><td>Enter the contact's birthday for use in customer gift programs or other communications.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>birthdate</td></tr></table>

### <a href=#governmentId name="governmentId">governmentId</a>

Type the passport number or other government ID for the contact for use in documents or reports.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Government</td></tr><tr><td>description</td><td>Type the passport number or other government ID for the contact for use in documents or reports.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>governmentid</td></tr></table>

### <a href=#yomiFullName name="yomiFullName">yomiFullName</a>

Shows the combined Yomi first and last names of the contact so that the full phonetic name can be displayed in views and reports.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Yomi Full Name</td></tr><tr><td>description</td><td>Shows the combined Yomi first and last names of the contact so that the full phonetic name can be displayed in views and reports.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>450</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>yomifullname</td></tr></table>

### <a href=#description name="description">description</a>

Type additional information to describe the contact, such as an excerpt from the company's website.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type additional information to describe the contact, such as an excerpt from the company's website.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#employeeId name="employeeId">employeeId</a>

Type the employee ID or number for the contact for reference in orders, service cases, or other communications with the contact's organization.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Employee</td></tr><tr><td>description</td><td>Type the employee ID or number for the contact for reference in orders, service cases, or other communications with the contact's organization.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>employeeid</td></tr></table>

### <a href=#genderCode name="genderCode">genderCode</a>

Select the contact's gender to make sure the contact is addressed correctly in sales calls, email, and marketing campaigns.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Gender</td></tr><tr><td>description</td><td>Select the contact's gender to make sure the contact is addressed correctly in sales calls, email, and marketing campaigns.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>gendercode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Male</td><td>1</td></tr><tr><td>en</td><td>Female</td><td>2</td></tr></table></td></tr></table>

### <a href=#genderCode_display name="genderCode_display">genderCode_display</a>

First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#annualIncome name="annualIncome">annualIncome</a>

Type the contact's annual income for use in profiling and financial analysis.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Annual Income</td></tr><tr><td>description</td><td>Type the contact's annual income for use in profiling and financial analysis.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>annualincome</td></tr></table>

### <a href=#hasChildrenCode name="hasChildrenCode">hasChildrenCode</a>

Select whether the contact has any children for reference in follow-up phone calls and other communications.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Has Children</td></tr><tr><td>description</td><td>Select whether the contact has any children for reference in follow-up phone calls and other communications.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>haschildrencode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#hasChildrenCode_display name="hasChildrenCode_display">hasChildrenCode_display</a>

First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#educationCode name="educationCode">educationCode</a>

Select the contact's highest level of education for use in segmentation and analysis.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Education</td></tr><tr><td>description</td><td>Select the contact's highest level of education for use in segmentation and analysis.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>educationcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#educationCode_display name="educationCode_display">educationCode_display</a>

First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#webSiteUrl name="webSiteUrl">webSiteUrl</a>

Type the contact's professional or personal website or blog URL.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Website</td></tr><tr><td>description</td><td>Type the contact's professional or personal website or blog URL.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>websiteurl</td></tr></table>

### <a href=#familyStatusCode name="familyStatusCode">familyStatusCode</a>

Select the marital status of the contact for reference in follow-up phone calls and other communications.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Marital Status</td></tr><tr><td>description</td><td>Select the marital status of the contact for reference in follow-up phone calls and other communications.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>familystatuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Single</td><td>1</td></tr><tr><td>en</td><td>Married</td><td>2</td></tr><tr><td>en</td><td>Divorced</td><td>3</td></tr><tr><td>en</td><td>Widowed</td><td>4</td></tr></table></td></tr></table>

### <a href=#familyStatusCode_display name="familyStatusCode_display">familyStatusCode_display</a>

First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#ftpSiteUrl name="ftpSiteUrl">ftpSiteUrl</a>

Type the URL for the contact's FTP site to enable users to access data and share documents.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>FTP Site</td></tr><tr><td>description</td><td>Type the URL for the contact's FTP site to enable users to access data and share documents.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ftpsiteurl</td></tr></table>

### <a href=#EMailAddress1 name="EMailAddress1">EMailAddress1</a>

Type the primary email address for the contact.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email</td></tr><tr><td>description</td><td>Type the primary email address for the contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailaddress1</td></tr></table>

### <a href=#spousesName name="spousesName">spousesName</a>

Type the name of the contact's spouse or partner for reference during calls, events, or other communications with the contact.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Spouse/Partner Name</td></tr><tr><td>description</td><td>Type the name of the contact's spouse or partner for reference during calls, events, or other communications with the contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>spousesname</td></tr></table>

### <a href=#assistantName name="assistantName">assistantName</a>

Type the name of the contact's assistant.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Assistant</td></tr><tr><td>description</td><td>Type the name of the contact's assistant.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>assistantname</td></tr></table>

### <a href=#EMailAddress2 name="EMailAddress2">EMailAddress2</a>

Type the secondary email address for the contact.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Address 2</td></tr><tr><td>description</td><td>Type the secondary email address for the contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailaddress2</td></tr></table>

### <a href=#assistantPhone name="assistantPhone">assistantPhone</a>

Type the phone number for the contact's assistant.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Assistant Phone</td></tr><tr><td>description</td><td>Type the phone number for the contact's assistant.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>assistantphone</td></tr></table>

### <a href=#EMailAddress3 name="EMailAddress3">EMailAddress3</a>

Type an alternate email address for the contact.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Address 3</td></tr><tr><td>description</td><td>Type an alternate email address for the contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailaddress3</td></tr></table>

### <a href=#doNotPhone name="doNotPhone">doNotPhone</a>

Select whether the contact accepts phone calls. If Do Not Allow is selected, the contact will be excluded from any phone call activities distributed in marketing campaigns.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not allow Phone Calls</td></tr><tr><td>description</td><td>Select whether the contact accepts phone calls. If Do Not Allow is selected, the contact will be excluded from any phone call activities distributed in marketing campaigns.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>donotphone</td></tr></table>

### <a href=#managerName name="managerName">managerName</a>

Type the name of the contact's manager for use in escalating issues or other follow-up communications with the contact.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Manager</td></tr><tr><td>description</td><td>Type the name of the contact's manager for use in escalating issues or other follow-up communications with the contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>managername</td></tr></table>

### <a href=#managerPhone name="managerPhone">managerPhone</a>

Type the phone number for the contact's manager.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Manager Phone</td></tr><tr><td>description</td><td>Type the phone number for the contact's manager.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>managerphone</td></tr></table>

### <a href=#doNotFax name="doNotFax">doNotFax</a>

Select whether the contact allows faxes. If Do Not Allow is selected, the contact will be excluded from any fax activities distributed in marketing campaigns.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not allow Faxes</td></tr><tr><td>description</td><td>Select whether the contact allows faxes. If Do Not Allow is selected, the contact will be excluded from any fax activities distributed in marketing campaigns.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>donotfax</td></tr></table>

### <a href=#doNotEMail name="doNotEMail">doNotEMail</a>

Select whether the contact allows direct email sent from Microsoft Dynamics 365. If Do Not Allow is selected, Microsoft Dynamics 365 will not send the email.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not allow Emails</td></tr><tr><td>description</td><td>Select whether the contact allows direct email sent from Microsoft Dynamics 365. If Do Not Allow is selected, Microsoft Dynamics 365 will not send the email.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>donotemail</td></tr></table>

### <a href=#doNotPostalMail name="doNotPostalMail">doNotPostalMail</a>

Select whether the contact allows direct mail. If Do Not Allow is selected, the contact will be excluded from letter activities distributed in marketing campaigns.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not allow Mails</td></tr><tr><td>description</td><td>Select whether the contact allows direct mail. If Do Not Allow is selected, the contact will be excluded from letter activities distributed in marketing campaigns.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>donotpostalmail</td></tr></table>

### <a href=#doNotBulkEMail name="doNotBulkEMail">doNotBulkEMail</a>

Select whether the contact accepts bulk email sent through marketing campaigns or quick campaigns. If Do Not Allow is selected, the contact can be added to marketing lists, but will be excluded from the email.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not allow Bulk Emails</td></tr><tr><td>description</td><td>Select whether the contact accepts bulk email sent through marketing campaigns or quick campaigns. If Do Not Allow is selected, the contact can be added to marketing lists, but will be excluded from the email.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>donotbulkemail</td></tr></table>

### <a href=#doNotBulkPostalMail name="doNotBulkPostalMail">doNotBulkPostalMail</a>

Select whether the contact accepts bulk postal mail sent through marketing campaigns or quick campaigns. If Do Not Allow is selected, the contact can be added to marketing lists, but will be excluded from the letters.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not allow Bulk Mails</td></tr><tr><td>description</td><td>Select whether the contact accepts bulk postal mail sent through marketing campaigns or quick campaigns. If Do Not Allow is selected, the contact can be added to marketing lists, but will be excluded from the letters.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>donotbulkpostalmail</td></tr></table>

### <a href=#accountRoleCode name="accountRoleCode">accountRoleCode</a>

Select the contact's role within the company or sales process, such as decision maker, employee, or influencer.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Role</td></tr><tr><td>description</td><td>Select the contact's role within the company or sales process, such as decision maker, employee, or influencer.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>accountrolecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Decision Maker</td><td>1</td></tr><tr><td>en</td><td>Employee</td><td>2</td></tr><tr><td>en</td><td>Influencer</td><td>3</td></tr></table></td></tr></table>

### <a href=#accountRoleCode_display name="accountRoleCode_display">accountRoleCode_display</a>

First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#territoryCode name="territoryCode">territoryCode</a>

Select a region or territory for the contact for use in segmentation and analysis.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Territory</td></tr><tr><td>description</td><td>Select a region or territory for the contact for use in segmentation and analysis.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>territorycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#territoryCode_display name="territoryCode_display">territoryCode_display</a>

First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#creditLimit name="creditLimit">creditLimit</a>

Type the credit limit of the contact for reference when you address invoice and accounting issues with the customer.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credit Limit</td></tr><tr><td>description</td><td>Type the credit limit of the contact for reference when you address invoice and accounting issues with the customer.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>creditlimit</td></tr></table>

### <a href=#creditOnHold name="creditOnHold">creditOnHold</a>

Select whether the contact is on a credit hold, for reference when addressing invoice and accounting issues.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credit Hold</td></tr><tr><td>description</td><td>Select whether the contact is on a credit hold, for reference when addressing invoice and accounting issues.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>creditonhold</td></tr></table>

### <a href=#numberOfChildren name="numberOfChildren">numberOfChildren</a>

Type the number of children the contact has for reference in follow-up phone calls and other communications.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>No. of Children</td></tr><tr><td>description</td><td>Type the number of children the contact has for reference in follow-up phone calls and other communications.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>numberofchildren</td></tr></table>

### <a href=#childrensNames name="childrensNames">childrensNames</a>

Type the names of the contact's children for reference in communications and client programs.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Children's Names</td></tr><tr><td>description</td><td>Type the names of the contact's children for reference in communications and client programs.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>childrensnames</td></tr></table>

### <a href=#mobilePhone name="mobilePhone">mobilePhone</a>

Type the mobile phone number for the contact.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mobile Phone</td></tr><tr><td>description</td><td>Type the mobile phone number for the contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mobilephone</td></tr></table>

### <a href=#pager name="pager">pager</a>

Type the pager number for the contact.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pager</td></tr><tr><td>description</td><td>Type the pager number for the contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>pager</td></tr></table>

### <a href=#telephone1 name="telephone1">telephone1</a>

Type the main phone number for this contact.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Business Phone</td></tr><tr><td>description</td><td>Type the main phone number for this contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone1</td></tr></table>

### <a href=#telephone2 name="telephone2">telephone2</a>

Type a second phone number for this contact.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Home Phone</td></tr><tr><td>description</td><td>Type a second phone number for this contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone2</td></tr></table>

### <a href=#telephone3 name="telephone3">telephone3</a>

Type a third phone number for this contact.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Telephone 3</td></tr><tr><td>description</td><td>Type a third phone number for this contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone3</td></tr></table>

### <a href=#fax name="fax">fax</a>

Type the fax number for the contact.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fax</td></tr><tr><td>description</td><td>Type the fax number for the contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>fax</td></tr></table>

### <a href=#aging30 name="aging30">aging30</a>

For system use only.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aging 30</td></tr><tr><td>description</td><td>For system use only.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>aging30</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the contact is active or inactive. Inactive contacts are read-only and can't be edited unless they are reactivated.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows whether the contact is active or inactive. Inactive contacts are read-only and can't be edited unless they are reactivated.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#aging60 name="aging60">aging60</a>

For system use only.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aging 60</td></tr><tr><td>description</td><td>For system use only.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>aging60</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the contact's status.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the contact's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#aging90 name="aging90">aging90</a>

For system use only.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aging 90</td></tr><tr><td>description</td><td>For system use only.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>aging90</td></tr></table>

### <a href=#parentContactId name="parentContactId">parentContactId</a>

Unique identifier of the parent contact.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent Contact</td></tr><tr><td>description</td><td>Unique identifier of the parent contact.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>parentcontactid</td></tr></table>

### <a href=#address1AddressId name="address1AddressId">address1AddressId</a>

Unique identifier for address n.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address: ID</td></tr><tr><td>description</td><td>Unique identifier for address n.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>addressid</td></tr></table>

### <a href=#address1AddressTypeCode name="address1AddressTypeCode">address1AddressTypeCode</a>

Select the address type, such as primary or billing.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Type</td></tr><tr><td>description</td><td>Select the address type, such as primary or billing.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>addresstypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Bill To</td><td>1</td></tr><tr><td>en</td><td>Ship To</td><td>2</td></tr><tr><td>en</td><td>Primary</td><td>3</td></tr><tr><td>en</td><td>Other</td><td>4</td></tr></table></td></tr></table>

### <a href=#address1AddressTypeCode_display name="address1AddressTypeCode_display">address1AddressTypeCode_display</a>

First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address1Name name="address1Name">address1Name</a>

Type a descriptive name for the customer's address, such as Corporate Headquarters.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Name</td></tr><tr><td>description</td><td>Type a descriptive name for the customer's address, such as Corporate Headquarters.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#address1PrimaryContactName name="address1PrimaryContactName">address1PrimaryContactName</a>

Type the name of the primary contact person for the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Contact</td></tr><tr><td>description</td><td>Type the name of the primary contact person for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>150</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>primarycontactname</td></tr></table>

### <a href=#address1Line1 name="address1Line1">address1Line1</a>

Type the first line of the customer's address to help identify the location.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 1</td></tr><tr><td>description</td><td>Type the first line of the customer's address to help identify the location.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>line1</td></tr></table>

### <a href=#address1Line2 name="address1Line2">address1Line2</a>

Type the second line of the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 2</td></tr><tr><td>description</td><td>Type the second line of the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>line2</td></tr></table>

### <a href=#address1Line3 name="address1Line3">address1Line3</a>

Type the third line of the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 3</td></tr><tr><td>description</td><td>Type the third line of the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>line3</td></tr></table>

### <a href=#address1City name="address1City">address1City</a>

Type the city for the customer's address to help identify the location.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>City</td></tr><tr><td>description</td><td>Type the city for the customer's address to help identify the location.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>city</td></tr></table>

### <a href=#address1StateOrProvince name="address1StateOrProvince">address1StateOrProvince</a>

Type the state or province of the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State/Province</td></tr><tr><td>description</td><td>Type the state or province of the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stateorprovince</td></tr></table>

### <a href=#address1County name="address1County">address1County</a>

Type the county for the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>County</td></tr><tr><td>description</td><td>Type the county for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>county</td></tr></table>

### <a href=#address1Country name="address1Country">address1Country</a>

Type the country or region for the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country/Region</td></tr><tr><td>description</td><td>Type the country or region for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>country</td></tr></table>

### <a href=#address1PostOfficeBox name="address1PostOfficeBox">address1PostOfficeBox</a>

Type the post office box number of the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Post Office Box</td></tr><tr><td>description</td><td>Type the post office box number of the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postofficebox</td></tr></table>

### <a href=#address1PostalCode name="address1PostalCode">address1PostalCode</a>

Type the ZIP Code or postal code for the address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ZIP/Postal Code</td></tr><tr><td>description</td><td>Type the ZIP Code or postal code for the address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postalcode</td></tr></table>

### <a href=#address1UTCOffset name="address1UTCOffset">address1UTCOffset</a>

Select the time zone for the address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Offset</td></tr><tr><td>description</td><td>Select the time zone for the address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumValue</td><td>1500</td></tr><tr><td>minimumValue</td><td>-1500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcoffset</td></tr></table>

### <a href=#address1FreightTermsCode name="address1FreightTermsCode">address1FreightTermsCode</a>

Select the freight terms to make sure shipping charges are processed correctly.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Freight Terms</td></tr><tr><td>description</td><td>Select the freight terms to make sure shipping charges are processed correctly.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>freighttermscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>FOB</td><td>1</td></tr><tr><td>en</td><td>No Charge</td><td>2</td></tr></table></td></tr></table>

### <a href=#address1FreightTermsCode_display name="address1FreightTermsCode_display">address1FreightTermsCode_display</a>

First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address1UPSZone name="address1UPSZone">address1UPSZone</a>

Type the UPS zone of the customer's address to make sure shipping charges are calculated correctly and deliveries are made promptly, if shipped by UPS.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UPS Zone</td></tr><tr><td>description</td><td>Type the UPS zone of the customer's address to make sure shipping charges are calculated correctly and deliveries are made promptly, if shipped by UPS.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>upszone</td></tr></table>

### <a href=#address1Latitude name="address1Latitude">address1Latitude</a>

Type the latitude value for the customer's address, for use in mapping and other applications.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Latitude</td></tr><tr><td>description</td><td>Type the latitude value for the customer's address, for use in mapping and other applications.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>90</td></tr><tr><td>minimumValue</td><td>-90</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>latitude</td></tr></table>

### <a href=#address1Telephone1 name="address1Telephone1">address1Telephone1</a>

Type the primary phone number for the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Main Phone</td></tr><tr><td>description</td><td>Type the primary phone number for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone1</td></tr></table>

### <a href=#address1Longitude name="address1Longitude">address1Longitude</a>

Type the longitude value for the customer's address, for use in mapping and other applications.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Longitude</td></tr><tr><td>description</td><td>Type the longitude value for the customer's address, for use in mapping and other applications.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>180</td></tr><tr><td>minimumValue</td><td>-180</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>longitude</td></tr></table>

### <a href=#address1ShippingMethodCode name="address1ShippingMethodCode">address1ShippingMethodCode</a>

Select a shipping method for deliveries sent to this address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping Method</td></tr><tr><td>description</td><td>Select a shipping method for deliveries sent to this address.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shippingmethodcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Airborne</td><td>1</td></tr><tr><td>en</td><td>DHL</td><td>2</td></tr><tr><td>en</td><td>FedEx</td><td>3</td></tr><tr><td>en</td><td>UPS</td><td>4</td></tr><tr><td>en</td><td>Postal Mail</td><td>5</td></tr><tr><td>en</td><td>Full Load</td><td>6</td></tr><tr><td>en</td><td>Will Call</td><td>7</td></tr></table></td></tr></table>

### <a href=#address1ShippingMethodCode_display name="address1ShippingMethodCode_display">address1ShippingMethodCode_display</a>

First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address1Telephone2 name="address1Telephone2">address1Telephone2</a>

Type a second phone number for the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Phone 2</td></tr><tr><td>description</td><td>Type a second phone number for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone2</td></tr></table>

### <a href=#address1Telephone3 name="address1Telephone3">address1Telephone3</a>

Type a third phone number for the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Telephone 3</td></tr><tr><td>description</td><td>Type a third phone number for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone3</td></tr></table>

### <a href=#address1Fax name="address1Fax">address1Fax</a>

Type the fax number associated with the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fax</td></tr><tr><td>description</td><td>Type the fax number associated with the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>fax</td></tr></table>

### <a href=#address1Composite name="address1Composite">address1Composite</a>

Shows the complete address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address</td></tr><tr><td>description</td><td>Shows the complete address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>composite</td></tr></table>

### <a href=#address2AddressId name="address2AddressId">address2AddressId</a>

Unique identifier for address n.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address: ID</td></tr><tr><td>description</td><td>Unique identifier for address n.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>addressid</td></tr></table>

### <a href=#address2AddressTypeCode name="address2AddressTypeCode">address2AddressTypeCode</a>

Select the address type, such as primary or billing.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Type</td></tr><tr><td>description</td><td>Select the address type, such as primary or billing.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>addresstypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Bill To</td><td>1</td></tr><tr><td>en</td><td>Ship To</td><td>2</td></tr><tr><td>en</td><td>Primary</td><td>3</td></tr><tr><td>en</td><td>Other</td><td>4</td></tr></table></td></tr></table>

### <a href=#address2AddressTypeCode_display name="address2AddressTypeCode_display">address2AddressTypeCode_display</a>

First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address2Name name="address2Name">address2Name</a>

Type a descriptive name for the customer's address, such as Corporate Headquarters.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Name</td></tr><tr><td>description</td><td>Type a descriptive name for the customer's address, such as Corporate Headquarters.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#address2PrimaryContactName name="address2PrimaryContactName">address2PrimaryContactName</a>

Type the name of the primary contact person for the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Contact</td></tr><tr><td>description</td><td>Type the name of the primary contact person for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>150</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>primarycontactname</td></tr></table>

### <a href=#address2Line1 name="address2Line1">address2Line1</a>

Type the first line of the customer's address to help identify the location.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 1</td></tr><tr><td>description</td><td>Type the first line of the customer's address to help identify the location.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>line1</td></tr></table>

### <a href=#address2Line2 name="address2Line2">address2Line2</a>

Type the second line of the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 2</td></tr><tr><td>description</td><td>Type the second line of the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>line2</td></tr></table>

### <a href=#address2Line3 name="address2Line3">address2Line3</a>

Type the third line of the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 3</td></tr><tr><td>description</td><td>Type the third line of the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>line3</td></tr></table>

### <a href=#address2City name="address2City">address2City</a>

Type the city for the customer's address to help identify the location.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>City</td></tr><tr><td>description</td><td>Type the city for the customer's address to help identify the location.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>city</td></tr></table>

### <a href=#address2StateOrProvince name="address2StateOrProvince">address2StateOrProvince</a>

Type the state or province of the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State/Province</td></tr><tr><td>description</td><td>Type the state or province of the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stateorprovince</td></tr></table>

### <a href=#address2County name="address2County">address2County</a>

Type the county for the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>County</td></tr><tr><td>description</td><td>Type the county for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>county</td></tr></table>

### <a href=#address2Country name="address2Country">address2Country</a>

Type the country or region for the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country/Region</td></tr><tr><td>description</td><td>Type the country or region for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>country</td></tr></table>

### <a href=#address2PostOfficeBox name="address2PostOfficeBox">address2PostOfficeBox</a>

Type the post office box number of the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Post Office Box</td></tr><tr><td>description</td><td>Type the post office box number of the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postofficebox</td></tr></table>

### <a href=#address2PostalCode name="address2PostalCode">address2PostalCode</a>

Type the ZIP Code or postal code for the address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ZIP/Postal Code</td></tr><tr><td>description</td><td>Type the ZIP Code or postal code for the address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postalcode</td></tr></table>

### <a href=#address2UTCOffset name="address2UTCOffset">address2UTCOffset</a>

Select the time zone for the address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Offset</td></tr><tr><td>description</td><td>Select the time zone for the address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumValue</td><td>1500</td></tr><tr><td>minimumValue</td><td>-1500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcoffset</td></tr></table>

### <a href=#address2FreightTermsCode name="address2FreightTermsCode">address2FreightTermsCode</a>

Select the freight terms to make sure shipping charges are processed correctly.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Freight Terms</td></tr><tr><td>description</td><td>Select the freight terms to make sure shipping charges are processed correctly.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>freighttermscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>FOB</td><td>1</td></tr><tr><td>en</td><td>No Charge</td><td>2</td></tr></table></td></tr></table>

### <a href=#address2FreightTermsCode_display name="address2FreightTermsCode_display">address2FreightTermsCode_display</a>

First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address2UPSZone name="address2UPSZone">address2UPSZone</a>

Type the UPS zone of the customer's address to make sure shipping charges are calculated correctly and deliveries are made promptly, if shipped by UPS.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UPS Zone</td></tr><tr><td>description</td><td>Type the UPS zone of the customer's address to make sure shipping charges are calculated correctly and deliveries are made promptly, if shipped by UPS.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>upszone</td></tr></table>

### <a href=#address2Latitude name="address2Latitude">address2Latitude</a>

Type the latitude value for the customer's address, for use in mapping and other applications.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Latitude</td></tr><tr><td>description</td><td>Type the latitude value for the customer's address, for use in mapping and other applications.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>90</td></tr><tr><td>minimumValue</td><td>-90</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>latitude</td></tr></table>

### <a href=#address2Telephone1 name="address2Telephone1">address2Telephone1</a>

Type the primary phone number for the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Main Phone</td></tr><tr><td>description</td><td>Type the primary phone number for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone1</td></tr></table>

### <a href=#address2Longitude name="address2Longitude">address2Longitude</a>

Type the longitude value for the customer's address, for use in mapping and other applications.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Longitude</td></tr><tr><td>description</td><td>Type the longitude value for the customer's address, for use in mapping and other applications.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>180</td></tr><tr><td>minimumValue</td><td>-180</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>longitude</td></tr></table>

### <a href=#address2ShippingMethodCode name="address2ShippingMethodCode">address2ShippingMethodCode</a>

Select a shipping method for deliveries sent to this address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping Method</td></tr><tr><td>description</td><td>Select a shipping method for deliveries sent to this address.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shippingmethodcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Airborne</td><td>1</td></tr><tr><td>en</td><td>DHL</td><td>2</td></tr><tr><td>en</td><td>FedEx</td><td>3</td></tr><tr><td>en</td><td>UPS</td><td>4</td></tr><tr><td>en</td><td>Postal Mail</td><td>5</td></tr><tr><td>en</td><td>Full Load</td><td>6</td></tr><tr><td>en</td><td>Will Call</td><td>7</td></tr></table></td></tr></table>

### <a href=#address2ShippingMethodCode_display name="address2ShippingMethodCode_display">address2ShippingMethodCode_display</a>

First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address2Telephone2 name="address2Telephone2">address2Telephone2</a>

Type a second phone number for the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Phone 2</td></tr><tr><td>description</td><td>Type a second phone number for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone2</td></tr></table>

### <a href=#address2Telephone3 name="address2Telephone3">address2Telephone3</a>

Type a third phone number for the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Telephone 3</td></tr><tr><td>description</td><td>Type a third phone number for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone3</td></tr></table>

### <a href=#address2Fax name="address2Fax">address2Fax</a>

Type the fax number associated with the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fax</td></tr><tr><td>description</td><td>Type the fax number associated with the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>fax</td></tr></table>

### <a href=#address2Composite name="address2Composite">address2Composite</a>

Shows the complete address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address</td></tr><tr><td>description</td><td>Shows the complete address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>composite</td></tr></table>

### <a href=#address3AddressId name="address3AddressId">address3AddressId</a>

Unique identifier for address n.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address: ID</td></tr><tr><td>description</td><td>Unique identifier for address n.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>addressid</td></tr></table>

### <a href=#address3AddressTypeCode name="address3AddressTypeCode">address3AddressTypeCode</a>

Select the address type, such as primary or billing.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Type</td></tr><tr><td>description</td><td>Select the address type, such as primary or billing.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>addresstypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Bill To</td><td>1</td></tr><tr><td>en</td><td>Ship To</td><td>2</td></tr><tr><td>en</td><td>Primary</td><td>3</td></tr><tr><td>en</td><td>Other</td><td>4</td></tr></table></td></tr></table>

### <a href=#address3AddressTypeCode_display name="address3AddressTypeCode_display">address3AddressTypeCode_display</a>

First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address3Name name="address3Name">address3Name</a>

Type a descriptive name for the customer's address, such as Corporate Headquarters.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Name</td></tr><tr><td>description</td><td>Type a descriptive name for the customer's address, such as Corporate Headquarters.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#address3PrimaryContactName name="address3PrimaryContactName">address3PrimaryContactName</a>

Type the name of the primary contact person for the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Contact</td></tr><tr><td>description</td><td>Type the name of the primary contact person for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>150</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>primarycontactname</td></tr></table>

### <a href=#address3Line1 name="address3Line1">address3Line1</a>

Type the first line of the customer's address to help identify the location.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 1</td></tr><tr><td>description</td><td>Type the first line of the customer's address to help identify the location.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>line1</td></tr></table>

### <a href=#address3Line2 name="address3Line2">address3Line2</a>

Type the second line of the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 2</td></tr><tr><td>description</td><td>Type the second line of the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>line2</td></tr></table>

### <a href=#address3Line3 name="address3Line3">address3Line3</a>

Type the third line of the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 3</td></tr><tr><td>description</td><td>Type the third line of the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>line3</td></tr></table>

### <a href=#address3City name="address3City">address3City</a>

Type the city for the customer's address to help identify the location.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>City</td></tr><tr><td>description</td><td>Type the city for the customer's address to help identify the location.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>city</td></tr></table>

### <a href=#address3StateOrProvince name="address3StateOrProvince">address3StateOrProvince</a>

Type the state or province of the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State/Province</td></tr><tr><td>description</td><td>Type the state or province of the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stateorprovince</td></tr></table>

### <a href=#address3County name="address3County">address3County</a>

Type the county for the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>County</td></tr><tr><td>description</td><td>Type the county for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>county</td></tr></table>

### <a href=#address3Country name="address3Country">address3Country</a>

Type the country or region for the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country/Region</td></tr><tr><td>description</td><td>Type the country or region for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>country</td></tr></table>

### <a href=#address3PostOfficeBox name="address3PostOfficeBox">address3PostOfficeBox</a>

Type the post office box number of the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Post Office Box</td></tr><tr><td>description</td><td>Type the post office box number of the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postofficebox</td></tr></table>

### <a href=#address3PostalCode name="address3PostalCode">address3PostalCode</a>

Type the ZIP Code or postal code for the address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ZIP/Postal Code</td></tr><tr><td>description</td><td>Type the ZIP Code or postal code for the address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postalcode</td></tr></table>

### <a href=#address3UTCOffset name="address3UTCOffset">address3UTCOffset</a>

Select the time zone for the address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Offset</td></tr><tr><td>description</td><td>Select the time zone for the address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumValue</td><td>1500</td></tr><tr><td>minimumValue</td><td>-1500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcoffset</td></tr></table>

### <a href=#address3FreightTermsCode name="address3FreightTermsCode">address3FreightTermsCode</a>

Select the freight terms to make sure shipping charges are processed correctly.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Freight Terms</td></tr><tr><td>description</td><td>Select the freight terms to make sure shipping charges are processed correctly.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>freighttermscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>FOB</td><td>1</td></tr><tr><td>en</td><td>No Charge</td><td>2</td></tr></table></td></tr></table>

### <a href=#address3FreightTermsCode_display name="address3FreightTermsCode_display">address3FreightTermsCode_display</a>

First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address3UPSZone name="address3UPSZone">address3UPSZone</a>

Type the UPS zone of the customer's address to make sure shipping charges are calculated correctly and deliveries are made promptly, if shipped by UPS.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UPS Zone</td></tr><tr><td>description</td><td>Type the UPS zone of the customer's address to make sure shipping charges are calculated correctly and deliveries are made promptly, if shipped by UPS.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>upszone</td></tr></table>

### <a href=#address3Latitude name="address3Latitude">address3Latitude</a>

Type the latitude value for the customer's address, for use in mapping and other applications.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Latitude</td></tr><tr><td>description</td><td>Type the latitude value for the customer's address, for use in mapping and other applications.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>90</td></tr><tr><td>minimumValue</td><td>-90</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>latitude</td></tr></table>

### <a href=#address3Telephone1 name="address3Telephone1">address3Telephone1</a>

Type the primary phone number for the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Main Phone</td></tr><tr><td>description</td><td>Type the primary phone number for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone1</td></tr></table>

### <a href=#address3Longitude name="address3Longitude">address3Longitude</a>

Type the longitude value for the customer's address, for use in mapping and other applications.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Longitude</td></tr><tr><td>description</td><td>Type the longitude value for the customer's address, for use in mapping and other applications.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>180</td></tr><tr><td>minimumValue</td><td>-180</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>longitude</td></tr></table>

### <a href=#address3ShippingMethodCode name="address3ShippingMethodCode">address3ShippingMethodCode</a>

Select a shipping method for deliveries sent to this address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping Method</td></tr><tr><td>description</td><td>Select a shipping method for deliveries sent to this address.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shippingmethodcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Airborne</td><td>1</td></tr><tr><td>en</td><td>DHL</td><td>2</td></tr><tr><td>en</td><td>FedEx</td><td>3</td></tr><tr><td>en</td><td>UPS</td><td>4</td></tr><tr><td>en</td><td>Postal Mail</td><td>5</td></tr><tr><td>en</td><td>Full Load</td><td>6</td></tr><tr><td>en</td><td>Will Call</td><td>7</td></tr></table></td></tr></table>

### <a href=#address3ShippingMethodCode_display name="address3ShippingMethodCode_display">address3ShippingMethodCode_display</a>

First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address3Telephone2 name="address3Telephone2">address3Telephone2</a>

Type a second phone number for the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Phone 2</td></tr><tr><td>description</td><td>Type a second phone number for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone2</td></tr></table>

### <a href=#address3Telephone3 name="address3Telephone3">address3Telephone3</a>

Type a third phone number for the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Telephone 3</td></tr><tr><td>description</td><td>Type a third phone number for the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone3</td></tr></table>

### <a href=#address3Fax name="address3Fax">address3Fax</a>

Type the fax number associated with the customer's address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fax</td></tr><tr><td>description</td><td>Type the fax number associated with the customer's address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>fax</td></tr></table>

### <a href=#address3Composite name="address3Composite">address3Composite</a>

Shows the complete address.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address</td></tr><tr><td>description</td><td>Shows the complete address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>composite</td></tr></table>

### <a href=#preferredSystemUserId name="preferredSystemUserId">preferredSystemUserId</a>

Choose the regular or preferred customer service representative for reference when scheduling service activities for the contact.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Preferred User</td></tr><tr><td>description</td><td>Choose the regular or preferred customer service representative for reference when scheduling service activities for the contact.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>preferredsystemuserid</td></tr></table>

### <a href=#masterId name="masterId">masterId</a>

Unique identifier of the master contact for merge.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Master ID</td></tr><tr><td>description</td><td>Unique identifier of the master contact for merge.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>masterid</td></tr></table>

### <a href=#preferredAppointmentDayCode name="preferredAppointmentDayCode">preferredAppointmentDayCode</a>

Select the preferred day of the week for service appointments.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Preferred Day</td></tr><tr><td>description</td><td>Select the preferred day of the week for service appointments.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>preferredappointmentdaycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Sunday</td><td>0</td></tr><tr><td>en</td><td>Monday</td><td>1</td></tr><tr><td>en</td><td>Tuesday</td><td>2</td></tr><tr><td>en</td><td>Wednesday</td><td>3</td></tr><tr><td>en</td><td>Thursday</td><td>4</td></tr><tr><td>en</td><td>Friday</td><td>5</td></tr><tr><td>en</td><td>Saturday</td><td>6</td></tr></table></td></tr></table>

### <a href=#preferredAppointmentDayCode_display name="preferredAppointmentDayCode_display">preferredAppointmentDayCode_display</a>

First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#preferredAppointmentTimeCode name="preferredAppointmentTimeCode">preferredAppointmentTimeCode</a>

Select the preferred time of day for service appointments.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Preferred Time</td></tr><tr><td>description</td><td>Select the preferred time of day for service appointments.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>preferredappointmenttimecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Morning</td><td>1</td></tr><tr><td>en</td><td>Afternoon</td><td>2</td></tr><tr><td>en</td><td>Evening</td><td>3</td></tr></table></td></tr></table>

### <a href=#preferredAppointmentTimeCode_display name="preferredAppointmentTimeCode_display">preferredAppointmentTimeCode_display</a>

First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#doNotSendMM name="doNotSendMM">doNotSendMM</a>

Select whether the contact accepts marketing materials, such as brochures or catalogs. Contacts that opt out can be excluded from marketing initiatives.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Send Marketing Materials</td></tr><tr><td>description</td><td>Select whether the contact accepts marketing materials, such as brochures or catalogs. Contacts that opt out can be excluded from marketing initiatives.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>donotsendmm</td></tr></table>

### <a href=#parentCustomerIdType name="parentCustomerIdType">parentCustomerIdType</a>

The type of parent customer, either Account or Contact.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent Customer Type</td></tr><tr><td>description</td><td>The type of parent customer, either Account or Contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>parentcustomeridtype</td></tr></table>

### <a href=#parentCustomerId name="parentCustomerId">parentCustomerId</a>

Select the parent account or parent contact for the contact to provide a quick link to additional details, such as financial information, activities, and opportunities.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Company Name</td></tr><tr><td>description</td><td>Select the parent account or parent contact for the contact to provide a quick link to additional details, such as financial information, activities, and opportunities.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>parentcustomerid</td></tr></table>

### <a href=#merged name="merged">merged</a>

Shows whether the account has been merged with a master contact.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Merged</td></tr><tr><td>description</td><td>Shows whether the account has been merged with a master contact.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>merged</td></tr></table>

### <a href=#externalUserIdentifier name="externalUserIdentifier">externalUserIdentifier</a>

Identifier for an external user.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>External User Identifier</td></tr><tr><td>description</td><td>Identifier for an external user.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>externaluseridentifier</td></tr></table>

### <a href=#lastUsedInCampaign name="lastUsedInCampaign">lastUsedInCampaign</a>

Shows the date when the contact was last included in a marketing campaign or quick campaign.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Date Included in Campaign</td></tr><tr><td>description</td><td>Shows the date when the contact was last included in a marketing campaign or quick campaign.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastusedincampaign</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#annualIncomeBase name="annualIncomeBase">annualIncomeBase</a>

Shows the Annual Income field converted to the system's default base currency. The calculations use the exchange rate specified in the Currencies area.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Annual Income (Base)</td></tr><tr><td>description</td><td>Shows the Annual Income field converted to the system's default base currency. The calculations use the exchange rate specified in the Currencies area.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>annualincome_base</td></tr></table>

### <a href=#creditLimitBase name="creditLimitBase">creditLimitBase</a>

Shows the Credit Limit field converted to the system's default base currency for reporting purposes. The calculations use the exchange rate specified in the Currencies area.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credit Limit (Base)</td></tr><tr><td>description</td><td>Shows the Credit Limit field converted to the system's default base currency for reporting purposes. The calculations use the exchange rate specified in the Currencies area.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>creditlimit_base</td></tr></table>

### <a href=#aging60Base name="aging60Base">aging60Base</a>

Shows the Aging 60 field converted to the system's default base currency. The calculations use the exchange rate specified in the Currencies area.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aging 60 (Base)</td></tr><tr><td>description</td><td>Shows the Aging 60 field converted to the system's default base currency. The calculations use the exchange rate specified in the Currencies area.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>aging60_base</td></tr></table>

### <a href=#aging90Base name="aging90Base">aging90Base</a>

Shows the Aging 90 field converted to the system's default base currency. The calculations use the exchange rate specified in the Currencies area.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aging 90 (Base)</td></tr><tr><td>description</td><td>Shows the Aging 90 field converted to the system's default base currency. The calculations use the exchange rate specified in the Currencies area.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>aging90_base</td></tr></table>

### <a href=#aging30Base name="aging30Base">aging30Base</a>

Shows the Aging 30 field converted to the system's default base currency. The calculations use the exchange rate specified in the Currencies area.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aging 30 (Base)</td></tr><tr><td>description</td><td>Shows the Aging 30 field converted to the system's default base currency. The calculations use the exchange rate specified in the Currencies area.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>aging30_base</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Shows the ID of the stage.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Stage</td></tr><tr><td>description</td><td>Shows the ID of the stage.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#processId name="processId">processId</a>

Shows the ID of the process.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process</td></tr><tr><td>description</td><td>Shows the ID of the process.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#entityImageId name="entityImageId">entityImageId</a>

For internal use only.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Entity Image Id</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entityimageid</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

For internal use only.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#SLAId name="SLAId">SLAId</a>

Choose the service level agreement (SLA) that you want to apply to the Contact record.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SLA</td></tr><tr><td>description</td><td>Choose the service level agreement (SLA) that you want to apply to the Contact record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slaid</td></tr></table>

### <a href=#SLAInvokedId name="SLAInvokedId">SLAInvokedId</a>

Last SLA that was applied to this case. This field is for internal use only.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last SLA applied</td></tr><tr><td>description</td><td>Last SLA that was applied to this case. This field is for internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slainvokedid</td></tr></table>

### <a href=#onHoldTime name="onHoldTime">onHoldTime</a>

Shows how long, in minutes, that the record was on hold.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>On Hold Time (Minutes)</td></tr><tr><td>description</td><td>Shows how long, in minutes, that the record was on hold.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>onholdtime</td></tr></table>

### <a href=#lastOnHoldTime name="lastOnHoldTime">lastOnHoldTime</a>

Contains the date and time stamp of the last on hold time.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last On Hold Time</td></tr><tr><td>description</td><td>Contains the date and time stamp of the last on hold time.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastonholdtime</td></tr></table>

### <a href=#followEmail name="followEmail">followEmail</a>

Information about whether to allow following email activity like opens, attachment views and link clicks for emails sent to the contact.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Follow Email Activity</td></tr><tr><td>description</td><td>Information about whether to allow following email activity like opens, attachment views and link clicks for emails sent to the contact.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>followemail</td></tr></table>

### <a href=#timeSpentByMeOnEmailAndMeetings name="timeSpentByMeOnEmailAndMeetings">timeSpentByMeOnEmailAndMeetings</a>

Total time spent for emails (read and write) and meetings by me in relation to the contact record.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Spent by me</td></tr><tr><td>description</td><td>Total time spent for emails (read and write) and meetings by me in relation to the contact record.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timespentbymeonemailandmeetings</td></tr></table>

### <a href=#business2 name="business2">business2</a>

Type a second business phone number for this contact.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Business Phone 2</td></tr><tr><td>description</td><td>Type a second business phone number for this contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>business2</td></tr></table>

### <a href=#callback name="callback">callback</a>

Type a callback phone number for this contact.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Callback Number</td></tr><tr><td>description</td><td>Type a callback phone number for this contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>callback</td></tr></table>

### <a href=#company name="company">company</a>

Type the company phone of the contact.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Company Phone</td></tr><tr><td>description</td><td>Type the company phone of the contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>company</td></tr></table>

### <a href=#home2 name="home2">home2</a>

Type a second home phone number for this contact.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Home Phone 2</td></tr><tr><td>description</td><td>Type a second home phone number for this contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>home2</td></tr></table>

### <a href=#createdByExternalParty name="createdByExternalParty">createdByExternalParty</a>

Shows the external party who created the record.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (External Party)</td></tr><tr><td>description</td><td>Shows the external party who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdbyexternalparty</td></tr></table>

### <a href=#modifiedByExternalParty name="modifiedByExternalParty">modifiedByExternalParty</a>

Shows the external party who modified the record.  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (External Party)</td></tr><tr><td>description</td><td>Shows the external party who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedbyexternalparty</td></tr></table>

### <a href=#marketingOnly name="marketingOnly">marketingOnly</a>

Whether is only for marketing  
First included in: <a href="../Contact.md" target="_blank">applicationCommon/Contact</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Marketing Only</td></tr><tr><td>description</td><td>Whether is only for marketing</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>marketingonly</td></tr></table>

### <a href=#defaultPriceLevelId name="defaultPriceLevelId">defaultPriceLevelId</a>

Choose the default price list associated with the contact to make sure the correct product prices for this customer are applied in sales opportunities, quotes, and orders.  
First included in: foundationCommon/Contact (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price List</td></tr><tr><td>description</td><td>Choose the default price list associated with the contact to make sure the correct product prices for this customer are applied in sales opportunities, quotes, and orders.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>defaultpricelevelid</td></tr></table>
