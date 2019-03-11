---
title: User - Common Data Model | Microsoft Docs
description: Person with access to the Microsoft CRM system and who owns objects in the Microsoft CRM database.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# User

Person with access to the Microsoft CRM system and who owns objects in the Microsoft CRM database.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/User.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /User  
- [/foundationCommon/crmCommon/service/User](foundationCommon/crmCommon/service/User.md "/core/applicationCommon/foundationCommon/crmCommon/service/User.cdm.json/User")  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[systemUserId](#systemUserId)|Unique identifier for the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[organizationId](#organizationId)|Unique identifier of the organization associated with the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[businessUnitId](#businessUnitId)|Unique identifier of the business unit with which the user is associated.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[parentSystemUserId](#parentSystemUserId)|Unique identifier of the manager of the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[firstName](#firstName)|First name of the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[salutation](#salutation)|Salutation for correspondence with the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[middleName](#middleName)|Middle name of the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[lastName](#lastName)|Last name of the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[personalEMailAddress](#personalEMailAddress)|Personal email address of the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[fullName](#fullName)|Full name of the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[nickName](#nickName)|Nickname of the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[title](#title)|Title of the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[internalEMailAddress](#internalEMailAddress)|Internal email address for the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[jobTitle](#jobTitle)|Job title of the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[mobileAlertEMail](#mobileAlertEMail)|Mobile alert email address for the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[preferredEmailCode](#preferredEmailCode)|Preferred email address for the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[preferredEmailCode_display](#preferredEmailCode_display)||<a href="User.md" target="_blank">applicationCommon/User</a>|
|[homePhone](#homePhone)|Home phone number for the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[mobilePhone](#mobilePhone)|Mobile phone number for the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[preferredPhoneCode](#preferredPhoneCode)|Preferred phone number for the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[preferredPhoneCode_display](#preferredPhoneCode_display)||<a href="User.md" target="_blank">applicationCommon/User</a>|
|[preferredAddressCode](#preferredAddressCode)|Preferred address for the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[preferredAddressCode_display](#preferredAddressCode_display)||<a href="User.md" target="_blank">applicationCommon/User</a>|
|[photoUrl](#photoUrl)|URL for the Website on which a photo of the user is located.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[domainName](#domainName)|Active Directory domain of which the user is a member.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[passportLo](#passportLo)|For internal use only.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[createdOn](#createdOn)|Date and time when the user was created.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[passportHi](#passportHi)|For internal use only.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[disabledReason](#disabledReason)|Reason for disabling the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[modifiedOn](#modifiedOn)|Date and time when the user was last modified.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[employeeId](#employeeId)|Employee identifier for the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who last modified the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[isDisabled](#isDisabled)|Information about whether the user is enabled.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[governmentId](#governmentId)|Government identifier for the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[versionNumber](#versionNumber)|Version number of the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address1AddressId](#address1AddressId)|Unique identifier for address 1.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address1AddressTypeCode](#address1AddressTypeCode)|Type of address for address 1, such as billing, shipping, or primary address.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address1AddressTypeCode_display](#address1AddressTypeCode_display)||<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address1Name](#address1Name)|Name to enter for address 1.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address1Line1](#address1Line1)|First line for entering address 1 information.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address1Line2](#address1Line2)|Second line for entering address 1 information.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address1Line3](#address1Line3)|Third line for entering address 1 information.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address1City](#address1City)|City name for address 1.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address1StateOrProvince](#address1StateOrProvince)|State or province for address 1.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address1County](#address1County)|County name for address 1.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address1Country](#address1Country)|Country/region name in address 1.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address1PostOfficeBox](#address1PostOfficeBox)|Post office box number for address 1.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address1PostalCode](#address1PostalCode)|ZIP Code or postal code for address 1.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address1UTCOffset](#address1UTCOffset)|UTC offset for address 1. This is the difference between local time and standard Coordinated Universal Time.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address1UPSZone](#address1UPSZone)|United Parcel Service (UPS) zone for address 1.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address1Latitude](#address1Latitude)|Latitude for address 1.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address1Telephone1](#address1Telephone1)|First telephone number associated with address 1.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address1Longitude](#address1Longitude)|Longitude for address 1.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address1ShippingMethodCode](#address1ShippingMethodCode)|Method of shipment for address 1.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address1ShippingMethodCode_display](#address1ShippingMethodCode_display)||<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address1Telephone2](#address1Telephone2)|Second telephone number associated with address 1.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address1Telephone3](#address1Telephone3)|Third telephone number associated with address 1.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address1Fax](#address1Fax)|Fax number for address 1.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address2AddressId](#address2AddressId)|Unique identifier for address 2.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address2AddressTypeCode](#address2AddressTypeCode)|Type of address for address 2, such as billing, shipping, or primary address.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address2AddressTypeCode_display](#address2AddressTypeCode_display)||<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address2Name](#address2Name)|Name to enter for address 2.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address2Line1](#address2Line1)|First line for entering address 2 information.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address2Line2](#address2Line2)|Second line for entering address 2 information.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address2Line3](#address2Line3)|Third line for entering address 2 information.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address2City](#address2City)|City name for address 2.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address2StateOrProvince](#address2StateOrProvince)|State or province for address 2.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address2County](#address2County)|County name for address 2.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address2Country](#address2Country)|Country/region name in address 2.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address2PostOfficeBox](#address2PostOfficeBox)|Post office box number for address 2.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address2PostalCode](#address2PostalCode)|ZIP Code or postal code for address 2.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address2UTCOffset](#address2UTCOffset)|UTC offset for address 2. This is the difference between local time and standard Coordinated Universal Time.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address2UPSZone](#address2UPSZone)|United Parcel Service (UPS) zone for address 2.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address2Latitude](#address2Latitude)|Latitude for address 2.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address2Telephone1](#address2Telephone1)|First telephone number associated with address 2.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address2Longitude](#address2Longitude)|Longitude for address 2.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address2ShippingMethodCode](#address2ShippingMethodCode)|Method of shipment for address 2.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address2ShippingMethodCode_display](#address2ShippingMethodCode_display)||<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address2Telephone2](#address2Telephone2)|Second telephone number associated with address 2.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address2Telephone3](#address2Telephone3)|Third telephone number associated with address 2.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address2Fax](#address2Fax)|Fax number for address 2.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[skills](#skills)|Skill set of the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[displayInServiceViews](#displayInServiceViews)|Whether to display the user in service views.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[calendarId](#calendarId)|Fiscal calendar associated with the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[setupUser](#setupUser)|Check if user is a setup user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[windowsLiveID](#windowsLiveID)|Windows Live ID|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[incomingEmailDeliveryMethod](#incomingEmailDeliveryMethod)|Incoming email delivery method for the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[incomingEmailDeliveryMethod_display](#incomingEmailDeliveryMethod_display)||<a href="User.md" target="_blank">applicationCommon/User</a>|
|[outgoingEmailDeliveryMethod](#outgoingEmailDeliveryMethod)|Outgoing email delivery method for the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[outgoingEmailDeliveryMethod_display](#outgoingEmailDeliveryMethod_display)||<a href="User.md" target="_blank">applicationCommon/User</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[accessMode](#accessMode)|Type of user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[accessMode_display](#accessMode_display)||<a href="User.md" target="_blank">applicationCommon/User</a>|
|[inviteStatusCode](#inviteStatusCode)|User invitation status.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[inviteStatusCode_display](#inviteStatusCode_display)||<a href="User.md" target="_blank">applicationCommon/User</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[yomiFullName](#yomiFullName)|Pronunciation of the full name of the user, written in phonetic hiragana or katakana characters.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[yomiLastName](#yomiLastName)|Pronunciation of the last name of the user, written in phonetic hiragana or katakana characters.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[yomiMiddleName](#yomiMiddleName)|Pronunciation of the middle name of the user, written in phonetic hiragana or katakana characters.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[yomiFirstName](#yomiFirstName)|Pronunciation of the first name of the user, written in phonetic hiragana or katakana characters.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[isIntegrationUser](#isIntegrationUser)|Check if user is an integration user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[defaultFiltersPopulated](#defaultFiltersPopulated)|Indicates if default outlook filters have been populated.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the systemuser.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[queueId](#queueId)|Unique identifier of the default queue for the user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who last modified the systemuser.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[emailRouterAccessApproval](#emailRouterAccessApproval)|Shows the status of the primary email address.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[emailRouterAccessApproval_display](#emailRouterAccessApproval_display)||<a href="User.md" target="_blank">applicationCommon/User</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the systemuser.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the systemuser with respect to the base currency.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[CALType](#CALType)|License type of user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[CALType_display](#CALType_display)||<a href="User.md" target="_blank">applicationCommon/User</a>|
|[isLicensed](#isLicensed)|Information about whether the user is licensed.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[isSyncWithDirectory](#isSyncWithDirectory)|Information about whether the user is synced with the directory.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[yammerEmailAddress](#yammerEmailAddress)|User's Yammer login email address|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[yammerUserId](#yammerUserId)|User's Yammer ID|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[defaultMailbox](#defaultMailbox)|Select the mailbox associated with this user.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[userLicenseType](#userLicenseType)|Shows the type of user license.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[entityImageId](#entityImageId)|For internal use only.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address2Composite](#address2Composite)|Shows the complete secondary address.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[address1Composite](#address1Composite)|Shows the complete primary address.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[processId](#processId)|Shows the ID of the process.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[stageId](#stageId)|Shows the ID of the stage.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[isEmailAddressApprovedByO365Admin](#isEmailAddressApprovedByO365Admin)|Shows the status of approval of the email address by O365 Admin.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[positionId](#positionId)|User's position in hierarchical security model.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[traversedPath](#traversedPath)|For internal use only.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[sharePointEmailAddress](#sharePointEmailAddress)|SharePoint Work Email Address|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[mobileOfflineProfileId](#mobileOfflineProfileId)|Items contained with a particular SystemUser.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[defaultOdbFolderName](#defaultOdbFolderName)|Type a default folder name for the user's OneDrive For Business location.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[applicationId](#applicationId)|The identifier for the application. This is used to access data in another application.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[applicationIdUri](#applicationIdUri)|The URI used as a unique logical identifier for the external app. This can be used to validate the application.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[azureActiveDirectoryObjectId](#azureActiveDirectoryObjectId)|This is the application directory object Id.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[identityId](#identityId)|For internal use only.|<a href="User.md" target="_blank">applicationCommon/User</a>|
|[territoryId](#territoryId)|Unique identifier of the territory to which the user is assigned.|<a href="User.md" target="_blank">applicationCommon/User</a>|

### <a href=#systemUserId name="systemUserId">systemUserId</a>

Unique identifier for the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>User</td></tr><tr><td>description</td><td>Unique identifier for the user.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>systemuserid</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier of the organization associated with the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization </td></tr><tr><td>description</td><td>Unique identifier of the organization associated with the user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#businessUnitId name="businessUnitId">businessUnitId</a>

Unique identifier of the business unit with which the user is associated.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Business Unit</td></tr><tr><td>description</td><td>Unique identifier of the business unit with which the user is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>businessunitid</td></tr></table>

### <a href=#parentSystemUserId name="parentSystemUserId">parentSystemUserId</a>

Unique identifier of the manager of the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Manager</td></tr><tr><td>description</td><td>Unique identifier of the manager of the user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>parentsystemuserid</td></tr></table>

### <a href=#firstName name="firstName">firstName</a>

First name of the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>First Name</td></tr><tr><td>description</td><td>First name of the user.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>firstname</td></tr></table>

### <a href=#salutation name="salutation">salutation</a>

Salutation for correspondence with the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Salutation</td></tr><tr><td>description</td><td>Salutation for correspondence with the user.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>salutation</td></tr></table>

### <a href=#middleName name="middleName">middleName</a>

Middle name of the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Middle Name</td></tr><tr><td>description</td><td>Middle name of the user.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>middlename</td></tr></table>

### <a href=#lastName name="lastName">lastName</a>

Last name of the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Name</td></tr><tr><td>description</td><td>Last name of the user.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastname</td></tr></table>

### <a href=#personalEMailAddress name="personalEMailAddress">personalEMailAddress</a>

Personal email address of the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email 2</td></tr><tr><td>description</td><td>Personal email address of the user.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>personalemailaddress</td></tr></table>

### <a href=#fullName name="fullName">fullName</a>

Full name of the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Full Name</td></tr><tr><td>description</td><td>Full name of the user.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>fullname</td></tr></table>

### <a href=#nickName name="nickName">nickName</a>

Nickname of the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Nickname</td></tr><tr><td>description</td><td>Nickname of the user.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>nickname</td></tr></table>

### <a href=#title name="title">title</a>

Title of the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Title</td></tr><tr><td>description</td><td>Title of the user.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>128</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>title</td></tr></table>

### <a href=#internalEMailAddress name="internalEMailAddress">internalEMailAddress</a>

Internal email address for the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary Email</td></tr><tr><td>description</td><td>Internal email address for the user.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>internalemailaddress</td></tr></table>

### <a href=#jobTitle name="jobTitle">jobTitle</a>

Job title of the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Job Title</td></tr><tr><td>description</td><td>Job title of the user.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>jobtitle</td></tr></table>

### <a href=#mobileAlertEMail name="mobileAlertEMail">mobileAlertEMail</a>

Mobile alert email address for the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mobile Alert Email</td></tr><tr><td>description</td><td>Mobile alert email address for the user.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mobilealertemail</td></tr></table>

### <a href=#preferredEmailCode name="preferredEmailCode">preferredEmailCode</a>

Preferred email address for the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Preferred Email</td></tr><tr><td>description</td><td>Preferred email address for the user.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>preferredemailcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#preferredEmailCode_display name="preferredEmailCode_display">preferredEmailCode_display</a>

First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#homePhone name="homePhone">homePhone</a>

Home phone number for the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Home Phone</td></tr><tr><td>description</td><td>Home phone number for the user.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>homephone</td></tr></table>

### <a href=#mobilePhone name="mobilePhone">mobilePhone</a>

Mobile phone number for the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mobile Phone</td></tr><tr><td>description</td><td>Mobile phone number for the user.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mobilephone</td></tr></table>

### <a href=#preferredPhoneCode name="preferredPhoneCode">preferredPhoneCode</a>

Preferred phone number for the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Preferred Phone</td></tr><tr><td>description</td><td>Preferred phone number for the user.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>preferredphonecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Main Phone</td><td>1</td></tr><tr><td>en</td><td>Other Phone</td><td>2</td></tr><tr><td>en</td><td>Home Phone</td><td>3</td></tr><tr><td>en</td><td>Mobile Phone</td><td>4</td></tr></table></td></tr></table>

### <a href=#preferredPhoneCode_display name="preferredPhoneCode_display">preferredPhoneCode_display</a>

First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#preferredAddressCode name="preferredAddressCode">preferredAddressCode</a>

Preferred address for the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Preferred Address</td></tr><tr><td>description</td><td>Preferred address for the user.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>preferredaddresscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Mailing Address</td><td>1</td></tr><tr><td>en</td><td>Other Address</td><td>2</td></tr></table></td></tr></table>

### <a href=#preferredAddressCode_display name="preferredAddressCode_display">preferredAddressCode_display</a>

First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#photoUrl name="photoUrl">photoUrl</a>

URL for the Website on which a photo of the user is located.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Photo URL</td></tr><tr><td>description</td><td>URL for the Website on which a photo of the user is located.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>photourl</td></tr></table>

### <a href=#domainName name="domainName">domainName</a>

Active Directory domain of which the user is a member.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>User Name</td></tr><tr><td>description</td><td>Active Directory domain of which the user is a member.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>sourceName</td><td>domainname</td></tr></table>

### <a href=#passportLo name="passportLo">passportLo</a>

For internal use only.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Passport Lo</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>passportlo</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the user was created.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the user was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#passportHi name="passportHi">passportHi</a>

For internal use only.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Passport Hi</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>passporthi</td></tr></table>

### <a href=#disabledReason name="disabledReason">disabledReason</a>

Reason for disabling the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Disabled Reason</td></tr><tr><td>description</td><td>Reason for disabling the user.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>disabledreason</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the user was last modified.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the user was last modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#employeeId name="employeeId">employeeId</a>

Employee identifier for the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Employee</td></tr><tr><td>description</td><td>Employee identifier for the user.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>employeeid</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who last modified the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who last modified the user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#isDisabled name="isDisabled">isDisabled</a>

Information about whether the user is enabled.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Information about whether the user is enabled.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isdisabled</td></tr></table>

### <a href=#governmentId name="governmentId">governmentId</a>

Government identifier for the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Government</td></tr><tr><td>description</td><td>Government identifier for the user.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>governmentid</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version number of the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version number</td></tr><tr><td>description</td><td>Version number of the user.</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#address1AddressId name="address1AddressId">address1AddressId</a>

Unique identifier for address 1.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: ID</td></tr><tr><td>description</td><td>Unique identifier for address 1.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_addressid</td></tr></table>

### <a href=#address1AddressTypeCode name="address1AddressTypeCode">address1AddressTypeCode</a>

Type of address for address 1, such as billing, shipping, or primary address.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Address Type</td></tr><tr><td>description</td><td>Type of address for address 1, such as billing, shipping, or primary address.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_addresstypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#address1AddressTypeCode_display name="address1AddressTypeCode_display">address1AddressTypeCode_display</a>

First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address1Name name="address1Name">address1Name</a>

Name to enter for address 1.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Name</td></tr><tr><td>description</td><td>Name to enter for address 1.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_name</td></tr></table>

### <a href=#address1Line1 name="address1Line1">address1Line1</a>

First line for entering address 1 information.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 1</td></tr><tr><td>description</td><td>First line for entering address 1 information.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_line1</td></tr></table>

### <a href=#address1Line2 name="address1Line2">address1Line2</a>

Second line for entering address 1 information.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 2</td></tr><tr><td>description</td><td>Second line for entering address 1 information.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_line2</td></tr></table>

### <a href=#address1Line3 name="address1Line3">address1Line3</a>

Third line for entering address 1 information.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 3</td></tr><tr><td>description</td><td>Third line for entering address 1 information.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_line3</td></tr></table>

### <a href=#address1City name="address1City">address1City</a>

City name for address 1.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>City</td></tr><tr><td>description</td><td>City name for address 1.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>128</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_city</td></tr></table>

### <a href=#address1StateOrProvince name="address1StateOrProvince">address1StateOrProvince</a>

State or province for address 1.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State/Province</td></tr><tr><td>description</td><td>State or province for address 1.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>128</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_stateorprovince</td></tr></table>

### <a href=#address1County name="address1County">address1County</a>

County name for address 1.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: County</td></tr><tr><td>description</td><td>County name for address 1.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>128</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_county</td></tr></table>

### <a href=#address1Country name="address1Country">address1Country</a>

Country/region name in address 1.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country/Region</td></tr><tr><td>description</td><td>Country/region name in address 1.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>128</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_country</td></tr></table>

### <a href=#address1PostOfficeBox name="address1PostOfficeBox">address1PostOfficeBox</a>

Post office box number for address 1.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Post Office Box</td></tr><tr><td>description</td><td>Post office box number for address 1.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>40</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_postofficebox</td></tr></table>

### <a href=#address1PostalCode name="address1PostalCode">address1PostalCode</a>

ZIP Code or postal code for address 1.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ZIP/Postal Code</td></tr><tr><td>description</td><td>ZIP Code or postal code for address 1.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>40</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_postalcode</td></tr></table>

### <a href=#address1UTCOffset name="address1UTCOffset">address1UTCOffset</a>

UTC offset for address 1. This is the difference between local time and standard Coordinated Universal Time.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: UTC Offset</td></tr><tr><td>description</td><td>UTC offset for address 1. This is the difference between local time and standard Coordinated Universal Time.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumValue</td><td>1500</td></tr><tr><td>minimumValue</td><td>-1500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_utcoffset</td></tr></table>

### <a href=#address1UPSZone name="address1UPSZone">address1UPSZone</a>

United Parcel Service (UPS) zone for address 1.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: UPS Zone</td></tr><tr><td>description</td><td>United Parcel Service (UPS) zone for address 1.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_upszone</td></tr></table>

### <a href=#address1Latitude name="address1Latitude">address1Latitude</a>

Latitude for address 1.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Latitude</td></tr><tr><td>description</td><td>Latitude for address 1.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>90</td></tr><tr><td>minimumValue</td><td>-90</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_latitude</td></tr></table>

### <a href=#address1Telephone1 name="address1Telephone1">address1Telephone1</a>

First telephone number associated with address 1.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Main Phone</td></tr><tr><td>description</td><td>First telephone number associated with address 1.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_telephone1</td></tr></table>

### <a href=#address1Longitude name="address1Longitude">address1Longitude</a>

Longitude for address 1.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Longitude</td></tr><tr><td>description</td><td>Longitude for address 1.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>180</td></tr><tr><td>minimumValue</td><td>-180</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_longitude</td></tr></table>

### <a href=#address1ShippingMethodCode name="address1ShippingMethodCode">address1ShippingMethodCode</a>

Method of shipment for address 1.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Shipping Method</td></tr><tr><td>description</td><td>Method of shipment for address 1.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_shippingmethodcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#address1ShippingMethodCode_display name="address1ShippingMethodCode_display">address1ShippingMethodCode_display</a>

First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address1Telephone2 name="address1Telephone2">address1Telephone2</a>

Second telephone number associated with address 1.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Other Phone</td></tr><tr><td>description</td><td>Second telephone number associated with address 1.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_telephone2</td></tr></table>

### <a href=#address1Telephone3 name="address1Telephone3">address1Telephone3</a>

Third telephone number associated with address 1.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pager</td></tr><tr><td>description</td><td>Third telephone number associated with address 1.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_telephone3</td></tr></table>

### <a href=#address1Fax name="address1Fax">address1Fax</a>

Fax number for address 1.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Fax</td></tr><tr><td>description</td><td>Fax number for address 1.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_fax</td></tr></table>

### <a href=#address2AddressId name="address2AddressId">address2AddressId</a>

Unique identifier for address 2.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: ID</td></tr><tr><td>description</td><td>Unique identifier for address 2.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_addressid</td></tr></table>

### <a href=#address2AddressTypeCode name="address2AddressTypeCode">address2AddressTypeCode</a>

Type of address for address 2, such as billing, shipping, or primary address.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Address Type</td></tr><tr><td>description</td><td>Type of address for address 2, such as billing, shipping, or primary address.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_addresstypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#address2AddressTypeCode_display name="address2AddressTypeCode_display">address2AddressTypeCode_display</a>

First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address2Name name="address2Name">address2Name</a>

Name to enter for address 2.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Name</td></tr><tr><td>description</td><td>Name to enter for address 2.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_name</td></tr></table>

### <a href=#address2Line1 name="address2Line1">address2Line1</a>

First line for entering address 2 information.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Other Street 1</td></tr><tr><td>description</td><td>First line for entering address 2 information.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_line1</td></tr></table>

### <a href=#address2Line2 name="address2Line2">address2Line2</a>

Second line for entering address 2 information.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Other Street 2</td></tr><tr><td>description</td><td>Second line for entering address 2 information.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_line2</td></tr></table>

### <a href=#address2Line3 name="address2Line3">address2Line3</a>

Third line for entering address 2 information.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Other Street 3</td></tr><tr><td>description</td><td>Third line for entering address 2 information.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_line3</td></tr></table>

### <a href=#address2City name="address2City">address2City</a>

City name for address 2.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Other City</td></tr><tr><td>description</td><td>City name for address 2.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>128</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_city</td></tr></table>

### <a href=#address2StateOrProvince name="address2StateOrProvince">address2StateOrProvince</a>

State or province for address 2.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Other State/Province</td></tr><tr><td>description</td><td>State or province for address 2.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>128</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_stateorprovince</td></tr></table>

### <a href=#address2County name="address2County">address2County</a>

County name for address 2.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: County</td></tr><tr><td>description</td><td>County name for address 2.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>128</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_county</td></tr></table>

### <a href=#address2Country name="address2Country">address2Country</a>

Country/region name in address 2.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Other Country/Region</td></tr><tr><td>description</td><td>Country/region name in address 2.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>128</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_country</td></tr></table>

### <a href=#address2PostOfficeBox name="address2PostOfficeBox">address2PostOfficeBox</a>

Post office box number for address 2.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Post Office Box</td></tr><tr><td>description</td><td>Post office box number for address 2.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>40</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_postofficebox</td></tr></table>

### <a href=#address2PostalCode name="address2PostalCode">address2PostalCode</a>

ZIP Code or postal code for address 2.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Other ZIP/Postal Code</td></tr><tr><td>description</td><td>ZIP Code or postal code for address 2.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>40</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_postalcode</td></tr></table>

### <a href=#address2UTCOffset name="address2UTCOffset">address2UTCOffset</a>

UTC offset for address 2. This is the difference between local time and standard Coordinated Universal Time.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: UTC Offset</td></tr><tr><td>description</td><td>UTC offset for address 2. This is the difference between local time and standard Coordinated Universal Time.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumValue</td><td>1500</td></tr><tr><td>minimumValue</td><td>-1500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_utcoffset</td></tr></table>

### <a href=#address2UPSZone name="address2UPSZone">address2UPSZone</a>

United Parcel Service (UPS) zone for address 2.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: UPS Zone</td></tr><tr><td>description</td><td>United Parcel Service (UPS) zone for address 2.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_upszone</td></tr></table>

### <a href=#address2Latitude name="address2Latitude">address2Latitude</a>

Latitude for address 2.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Latitude</td></tr><tr><td>description</td><td>Latitude for address 2.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>90</td></tr><tr><td>minimumValue</td><td>-90</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_latitude</td></tr></table>

### <a href=#address2Telephone1 name="address2Telephone1">address2Telephone1</a>

First telephone number associated with address 2.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Telephone 1</td></tr><tr><td>description</td><td>First telephone number associated with address 2.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_telephone1</td></tr></table>

### <a href=#address2Longitude name="address2Longitude">address2Longitude</a>

Longitude for address 2.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Longitude</td></tr><tr><td>description</td><td>Longitude for address 2.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>180</td></tr><tr><td>minimumValue</td><td>-180</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_longitude</td></tr></table>

### <a href=#address2ShippingMethodCode name="address2ShippingMethodCode">address2ShippingMethodCode</a>

Method of shipment for address 2.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Shipping Method</td></tr><tr><td>description</td><td>Method of shipment for address 2.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_shippingmethodcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#address2ShippingMethodCode_display name="address2ShippingMethodCode_display">address2ShippingMethodCode_display</a>

First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address2Telephone2 name="address2Telephone2">address2Telephone2</a>

Second telephone number associated with address 2.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Telephone 2</td></tr><tr><td>description</td><td>Second telephone number associated with address 2.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_telephone2</td></tr></table>

### <a href=#address2Telephone3 name="address2Telephone3">address2Telephone3</a>

Third telephone number associated with address 2.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Telephone 3</td></tr><tr><td>description</td><td>Third telephone number associated with address 2.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_telephone3</td></tr></table>

### <a href=#address2Fax name="address2Fax">address2Fax</a>

Fax number for address 2.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Fax</td></tr><tr><td>description</td><td>Fax number for address 2.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_fax</td></tr></table>

### <a href=#skills name="skills">skills</a>

Skill set of the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Skills</td></tr><tr><td>description</td><td>Skill set of the user.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>skills</td></tr></table>

### <a href=#displayInServiceViews name="displayInServiceViews">displayInServiceViews</a>

Whether to display the user in service views.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Display in Service Views</td></tr><tr><td>description</td><td>Whether to display the user in service views.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>displayinserviceviews</td></tr></table>

### <a href=#calendarId name="calendarId">calendarId</a>

Fiscal calendar associated with the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Calendar</td></tr><tr><td>description</td><td>Fiscal calendar associated with the user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>calendarid</td></tr></table>

### <a href=#setupUser name="setupUser">setupUser</a>

Check if user is a setup user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Restricted Access Mode</td></tr><tr><td>description</td><td>Check if user is a setup user.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>setupuser</td></tr></table>

### <a href=#windowsLiveID name="windowsLiveID">windowsLiveID</a>

Windows Live ID  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Windows Live ID</td></tr><tr><td>description</td><td>Windows Live ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>windowsliveid</td></tr></table>

### <a href=#incomingEmailDeliveryMethod name="incomingEmailDeliveryMethod">incomingEmailDeliveryMethod</a>

Incoming email delivery method for the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Incoming Email Delivery Method</td></tr><tr><td>description</td><td>Incoming email delivery method for the user.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>incomingemaildeliverymethod</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>None</td><td>0</td></tr><tr><td>en</td><td>Microsoft Dynamics 365 for Outlook</td><td>1</td></tr><tr><td>en</td><td>Server-Side Synchronization or Email Router</td><td>2</td></tr><tr><td>en</td><td>Forward Mailbox</td><td>3</td></tr></table></td></tr></table>

### <a href=#incomingEmailDeliveryMethod_display name="incomingEmailDeliveryMethod_display">incomingEmailDeliveryMethod_display</a>

First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#outgoingEmailDeliveryMethod name="outgoingEmailDeliveryMethod">outgoingEmailDeliveryMethod</a>

Outgoing email delivery method for the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Outgoing Email Delivery Method</td></tr><tr><td>description</td><td>Outgoing email delivery method for the user.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>outgoingemaildeliverymethod</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>None</td><td>0</td></tr><tr><td>en</td><td>Microsoft Dynamics 365 for Outlook</td><td>1</td></tr><tr><td>en</td><td>Server-Side Synchronization or Email Router</td><td>2</td></tr></table></td></tr></table>

### <a href=#outgoingEmailDeliveryMethod_display name="outgoingEmailDeliveryMethod_display">outgoingEmailDeliveryMethod_display</a>

First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#accessMode name="accessMode">accessMode</a>

Type of user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Access Mode</td></tr><tr><td>description</td><td>Type of user.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>accessmode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Read-Write</td><td>0</td></tr><tr><td>en</td><td>Administrative</td><td>1</td></tr><tr><td>en</td><td>Read</td><td>2</td></tr><tr><td>en</td><td>Support User</td><td>3</td></tr><tr><td>en</td><td>Non-interactive</td><td>4</td></tr><tr><td>en</td><td>Delegated Admin</td><td>5</td></tr></table></td></tr></table>

### <a href=#accessMode_display name="accessMode_display">accessMode_display</a>

First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#inviteStatusCode name="inviteStatusCode">inviteStatusCode</a>

User invitation status.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invitation Status</td></tr><tr><td>description</td><td>User invitation status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>invitestatuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Invitation Not Sent</td><td>0</td></tr><tr><td>en</td><td>Invited</td><td>1</td></tr><tr><td>en</td><td>Invitation Near Expired</td><td>2</td></tr><tr><td>en</td><td>Invitation Expired</td><td>3</td></tr><tr><td>en</td><td>Invitation Accepted</td><td>4</td></tr><tr><td>en</td><td>Invitation Rejected</td><td>5</td></tr><tr><td>en</td><td>Invitation Revoked</td><td>6</td></tr></table></td></tr></table>

### <a href=#inviteStatusCode_display name="inviteStatusCode_display">inviteStatusCode_display</a>

First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#yomiFullName name="yomiFullName">yomiFullName</a>

Pronunciation of the full name of the user, written in phonetic hiragana or katakana characters.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Yomi Full Name</td></tr><tr><td>description</td><td>Pronunciation of the full name of the user, written in phonetic hiragana or katakana characters.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>yomifullname</td></tr></table>

### <a href=#yomiLastName name="yomiLastName">yomiLastName</a>

Pronunciation of the last name of the user, written in phonetic hiragana or katakana characters.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Yomi Last Name</td></tr><tr><td>description</td><td>Pronunciation of the last name of the user, written in phonetic hiragana or katakana characters.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>yomilastname</td></tr></table>

### <a href=#yomiMiddleName name="yomiMiddleName">yomiMiddleName</a>

Pronunciation of the middle name of the user, written in phonetic hiragana or katakana characters.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Yomi Middle Name</td></tr><tr><td>description</td><td>Pronunciation of the middle name of the user, written in phonetic hiragana or katakana characters.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>yomimiddlename</td></tr></table>

### <a href=#yomiFirstName name="yomiFirstName">yomiFirstName</a>

Pronunciation of the first name of the user, written in phonetic hiragana or katakana characters.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Yomi First Name</td></tr><tr><td>description</td><td>Pronunciation of the first name of the user, written in phonetic hiragana or katakana characters.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>yomifirstname</td></tr></table>

### <a href=#isIntegrationUser name="isIntegrationUser">isIntegrationUser</a>

Check if user is an integration user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Integration user mode</td></tr><tr><td>description</td><td>Check if user is an integration user.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isintegrationuser</td></tr></table>

### <a href=#defaultFiltersPopulated name="defaultFiltersPopulated">defaultFiltersPopulated</a>

Indicates if default outlook filters have been populated.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default Filters Populated</td></tr><tr><td>description</td><td>Indicates if default outlook filters have been populated.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>defaultfilterspopulated</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the systemuser.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the systemuser.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#queueId name="queueId">queueId</a>

Unique identifier of the default queue for the user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default Queue</td></tr><tr><td>description</td><td>Unique identifier of the default queue for the user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>queueid</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who last modified the systemuser.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who last modified the systemuser.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#emailRouterAccessApproval name="emailRouterAccessApproval">emailRouterAccessApproval</a>

Shows the status of the primary email address.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary Email Status</td></tr><tr><td>description</td><td>Shows the status of the primary email address.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>emailrouteraccessapproval</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Empty</td><td>0</td></tr><tr><td>en</td><td>Approved</td><td>1</td></tr><tr><td>en</td><td>Pending Approval</td><td>2</td></tr><tr><td>en</td><td>Rejected</td><td>3</td></tr></table></td></tr></table>

### <a href=#emailRouterAccessApproval_display name="emailRouterAccessApproval_display">emailRouterAccessApproval_display</a>

First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the systemuser.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the systemuser.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the systemuser with respect to the base currency.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the systemuser with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#CALType name="CALType">CALType</a>

License type of user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>License Type</td></tr><tr><td>description</td><td>License type of user.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>caltype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Professional</td><td>0</td></tr><tr><td>en</td><td>Administrative</td><td>1</td></tr><tr><td>en</td><td>Basic</td><td>2</td></tr><tr><td>en</td><td>Device Professional</td><td>3</td></tr><tr><td>en</td><td>Device Basic</td><td>4</td></tr><tr><td>en</td><td>Essential</td><td>5</td></tr><tr><td>en</td><td>Device Essential</td><td>6</td></tr><tr><td>en</td><td>Enterprise</td><td>7</td></tr><tr><td>en</td><td>Device Enterprise</td><td>8</td></tr><tr><td>en</td><td>Sales</td><td>9</td></tr><tr><td>en</td><td>Service</td><td>10</td></tr><tr><td>en</td><td>Field Service</td><td>11</td></tr><tr><td>en</td><td>Project Service</td><td>12</td></tr></table></td></tr></table>

### <a href=#CALType_display name="CALType_display">CALType_display</a>

First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#isLicensed name="isLicensed">isLicensed</a>

Information about whether the user is licensed.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>User Licensed</td></tr><tr><td>description</td><td>Information about whether the user is licensed.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>islicensed</td></tr></table>

### <a href=#isSyncWithDirectory name="isSyncWithDirectory">isSyncWithDirectory</a>

Information about whether the user is synced with the directory.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>User Synced</td></tr><tr><td>description</td><td>Information about whether the user is synced with the directory.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>issyncwithdirectory</td></tr></table>

### <a href=#yammerEmailAddress name="yammerEmailAddress">yammerEmailAddress</a>

User's Yammer login email address  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Yammer Email</td></tr><tr><td>description</td><td>User's Yammer login email address</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>yammeremailaddress</td></tr></table>

### <a href=#yammerUserId name="yammerUserId">yammerUserId</a>

User's Yammer ID  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Yammer User ID</td></tr><tr><td>description</td><td>User's Yammer ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>128</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>yammeruserid</td></tr></table>

### <a href=#defaultMailbox name="defaultMailbox">defaultMailbox</a>

Select the mailbox associated with this user.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mailbox</td></tr><tr><td>description</td><td>Select the mailbox associated with this user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>defaultmailbox</td></tr></table>

### <a href=#userLicenseType name="userLicenseType">userLicenseType</a>

Shows the type of user license.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>User License Type</td></tr><tr><td>description</td><td>Shows the type of user license.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>sourceName</td><td>userlicensetype</td></tr></table>

### <a href=#entityImageId name="entityImageId">entityImageId</a>

For internal use only.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Entity Image Id</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entityimageid</td></tr></table>

### <a href=#address2Composite name="address2Composite">address2Composite</a>

Shows the complete secondary address.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Other Address</td></tr><tr><td>description</td><td>Shows the complete secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_composite</td></tr></table>

### <a href=#address1Composite name="address1Composite">address1Composite</a>

Shows the complete primary address.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address</td></tr><tr><td>description</td><td>Shows the complete primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_composite</td></tr></table>

### <a href=#processId name="processId">processId</a>

Shows the ID of the process.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process</td></tr><tr><td>description</td><td>Shows the ID of the process.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Shows the ID of the stage.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Stage</td></tr><tr><td>description</td><td>Shows the ID of the stage.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#isEmailAddressApprovedByO365Admin name="isEmailAddressApprovedByO365Admin">isEmailAddressApprovedByO365Admin</a>

Shows the status of approval of the email address by O365 Admin.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Address O365 Admin Approval Status</td></tr><tr><td>description</td><td>Shows the status of approval of the email address by O365 Admin.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isemailaddressapprovedbyo365admin</td></tr></table>

### <a href=#positionId name="positionId">positionId</a>

User's position in hierarchical security model.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Position</td></tr><tr><td>description</td><td>User's position in hierarchical security model.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>positionid</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

For internal use only.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#sharePointEmailAddress name="sharePointEmailAddress">sharePointEmailAddress</a>

SharePoint Work Email Address  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SharePoint Email Address</td></tr><tr><td>description</td><td>SharePoint Work Email Address</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sharepointemailaddress</td></tr></table>

### <a href=#mobileOfflineProfileId name="mobileOfflineProfileId">mobileOfflineProfileId</a>

Items contained with a particular SystemUser.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mobile Offline Profile</td></tr><tr><td>description</td><td>Items contained with a particular SystemUser.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mobileofflineprofileid</td></tr></table>

### <a href=#defaultOdbFolderName name="defaultOdbFolderName">defaultOdbFolderName</a>

Type a default folder name for the user's OneDrive For Business location.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default OneDrive for Business Folder Name</td></tr><tr><td>description</td><td>Type a default folder name for the user's OneDrive For Business location.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>sourceName</td><td>defaultodbfoldername</td></tr></table>

### <a href=#applicationId name="applicationId">applicationId</a>

The identifier for the application. This is used to access data in another application.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Application ID</td></tr><tr><td>description</td><td>The identifier for the application. This is used to access data in another application.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>applicationid</td></tr></table>

### <a href=#applicationIdUri name="applicationIdUri">applicationIdUri</a>

The URI used as a unique logical identifier for the external app. This can be used to validate the application.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Application ID URI</td></tr><tr><td>description</td><td>The URI used as a unique logical identifier for the external app. This can be used to validate the application.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>applicationiduri</td></tr></table>

### <a href=#azureActiveDirectoryObjectId name="azureActiveDirectoryObjectId">azureActiveDirectoryObjectId</a>

This is the application directory object Id.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Azure AD Object ID</td></tr><tr><td>description</td><td>This is the application directory object Id.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>azureactivedirectoryobjectid</td></tr></table>

### <a href=#identityId name="identityId">identityId</a>

For internal use only.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unique user identity id</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>sourceName</td><td>identityid</td></tr></table>

### <a href=#territoryId name="territoryId">territoryId</a>

Unique identifier of the territory to which the user is assigned.  
First included in: applicationCommon/User (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Territory</td></tr><tr><td>description</td><td>Unique identifier of the territory to which the user is assigned.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>territoryid</td></tr></table>
