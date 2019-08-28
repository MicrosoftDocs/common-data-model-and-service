---
title: KYC - Common Data Model | Microsoft Docs
description: This describes the KYC entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# KYC

A KYC or Know Your Customer is used to gather information on the customer in a regular interval. The KYCs collect information such as where they live, collecting their updated or different ID information, and their risk level at that point in time.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/financialServices/banking/KYC.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/financialServices/banking/KYC  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[ownerId](#ownerId)|Owner Id|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[additionalNationality](#additionalNationality)|The person’s second nationality (if he/she has dual nationality).|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[businessLicenseExpiryDate](#businessLicenseExpiryDate)|The company’s trade license/commercial registration expiry date.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[businessLicenseNumber](#businessLicenseNumber)|The company’s trade license/commercial registration number.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[controllingUSCitizenOrTaxResident](#controllingUSCitizenOrTaxResident)|Indication of whether the customer is a citizen of the United States or a tax resident.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[countryOfBirth](#countryOfBirth)|The person’s country of birth as per the identification document.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[countryOfResidence](#countryOfResidence)|The country in which the person primarily resides.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[customerIdType](#customerIdType)|The type of customer, either Account or Contact.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[customerId](#customerId)|The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[dateOfBirth](#dateOfBirth)|The person’s date of birth as per the identification document.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[email](#email)|The primary e-mail address of the person.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[firstName](#firstName)|First name of the person.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[IDExpiryDate](#IDExpiryDate)|The date of expiry of the identification document provided by the person.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[IDNumber](#IDNumber)|The number of the identification document provided by the person such as the passport number or the national ID card number.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[IDType](#IDType)|The type of identification document that the person has provided to the bank such as passport or national ID card.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[IDType_display](#IDType_display)||<a href="KYC.md" target="_blank">banking/KYC</a>|
|[KYCCountry](#KYCCountry)|Country for which KYC has been performed against the customer. Each country may have different set of fields for KYC. This flag drives the system to show or hide the necessary fields.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[KYCId](#KYCId)|Unique identifier for entity instances|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[KYCPreparedOn](#KYCPreparedOn)|Date on which KYC check was performed.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[lastName](#lastName)|Last name of the person.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[middleName](#middleName)|Middle name of the person.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[mobileNumber](#mobileNumber)|The primary mobile phone number for the person.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[name](#name)|The name of the custom entity.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[nationality](#nationality)|The person’s primary nationality.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[natureOfBusiness](#natureOfBusiness)|Nature of the company’s business|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[phoneNumber](#phoneNumber)|The primary phone number of the company|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[placeOfBirth](#placeOfBirth)|The person’s place of birth as per the identification document.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[primaryContactId](#primaryContactId)|The person who is the main contact person at the company.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[reviewFrequency](#reviewFrequency)|The frequency based on which customer must be reviewed.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[reviewFrequency_display](#reviewFrequency_display)||<a href="KYC.md" target="_blank">banking/KYC</a>|
|[riskLevel](#riskLevel)|The general risk level of the customer.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[riskLevel_display](#riskLevel_display)||<a href="KYC.md" target="_blank">banking/KYC</a>|
|[processId](#processId)|Contains the id of the process associated with the entity.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[deprecatedStageId](#deprecatedStageId)|Contains the id of the stage where the entity is located.|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[stateCode](#stateCode)|Status of the KYC|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[stateCode_display](#stateCode_display)||<a href="KYC.md" target="_blank">banking/KYC</a>|
|[statusCode](#statusCode)|Reason for the status of the KYC|<a href="KYC.md" target="_blank">banking/KYC</a>|
|[statusCode_display](#statusCode_display)||<a href="KYC.md" target="_blank">banking/KYC</a>|
|[deprecatedTraversedPath](#deprecatedTraversedPath)|A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.|<a href="KYC.md" target="_blank">banking/KYC</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#additionalNationality name="additionalNationality">additionalNationality</a>

The person’s second nationality (if he/she has dual nationality).  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Additional Nationality</td></tr><tr><td>description</td><td>The person’s second nationality (if he/she has dual nationality).</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msfsi_additionalnationality</td></tr></table>

### <a href=#businessLicenseExpiryDate name="businessLicenseExpiryDate">businessLicenseExpiryDate</a>

The company’s trade license/commercial registration expiry date.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Business License Expiry Date</td></tr><tr><td>description</td><td>The company’s trade license/commercial registration expiry date.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msfsi_businesslicenseexpirydate</td></tr></table>

### <a href=#businessLicenseNumber name="businessLicenseNumber">businessLicenseNumber</a>

The company’s trade license/commercial registration number.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Business License Number</td></tr><tr><td>description</td><td>The company’s trade license/commercial registration number.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msfsi_businesslicensenumber</td></tr></table>

### <a href=#controllingUSCitizenOrTaxResident name="controllingUSCitizenOrTaxResident">controllingUSCitizenOrTaxResident</a>

Indication of whether the customer is a citizen of the United States or a tax resident.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Controlling US Citizen or Tax Resident</td></tr><tr><td>description</td><td>Indication of whether the customer is a citizen of the United States or a tax resident.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>msfsi_controllinguscitizenortaxresident</td></tr></table>

### <a href=#countryOfBirth name="countryOfBirth">countryOfBirth</a>

The person’s country of birth as per the identification document.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country of Birth</td></tr><tr><td>description</td><td>The person’s country of birth as per the identification document.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msfsi_countryofbirth</td></tr></table>

### <a href=#countryOfResidence name="countryOfResidence">countryOfResidence</a>

The country in which the person primarily resides.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country of Residence</td></tr><tr><td>description</td><td>The country in which the person primarily resides.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msfsi_countryofresidence</td></tr></table>

### <a href=#customerIdType name="customerIdType">customerIdType</a>

The type of customer, either Account or Contact.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Type</td></tr><tr><td>description</td><td>The type of customer, either Account or Contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>customeridtype</td></tr></table>

### <a href=#customerId name="customerId">customerId</a>

The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>description</td><td>The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customerid</td></tr></table>

### <a href=#dateOfBirth name="dateOfBirth">dateOfBirth</a>

The person’s date of birth as per the identification document.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date of Birth</td></tr><tr><td>description</td><td>The person’s date of birth as per the identification document.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msfsi_dateofbirth</td></tr></table>

### <a href=#email name="email">email</a>

The primary e-mail address of the person.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email</td></tr><tr><td>description</td><td>The primary e-mail address of the person.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msfsi_email</td></tr></table>

### <a href=#firstName name="firstName">firstName</a>

First name of the person.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>First Name</td></tr><tr><td>description</td><td>First name of the person.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>sourceName</td><td>msfsi_firstname</td></tr></table>

### <a href=#IDExpiryDate name="IDExpiryDate">IDExpiryDate</a>

The date of expiry of the identification document provided by the person.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ID Expiry Date</td></tr><tr><td>description</td><td>The date of expiry of the identification document provided by the person.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msfsi_idexpirydate</td></tr></table>

### <a href=#IDNumber name="IDNumber">IDNumber</a>

The number of the identification document provided by the person such as the passport number or the national ID card number.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ID Number</td></tr><tr><td>description</td><td>The number of the identification document provided by the person such as the passport number or the national ID card number.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msfsi_idnumber</td></tr></table>

### <a href=#IDType name="IDType">IDType</a>

The type of identification document that the person has provided to the bank such as passport or national ID card.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ID Type</td></tr><tr><td>description</td><td>The type of identification document that the person has provided to the bank such as passport or national ID card.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msfsi_idtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#IDType_display name="IDType_display">IDType_display</a>

First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#KYCCountry name="KYCCountry">KYCCountry</a>

Country for which KYC has been performed against the customer. Each country may have different set of fields for KYC. This flag drives the system to show or hide the necessary fields.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>KYC Country</td></tr><tr><td>description</td><td>Country for which KYC has been performed against the customer. Each country may have different set of fields for KYC. This flag drives the system to show or hide the necessary fields.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msfsi_kyccountry</td></tr></table>

### <a href=#KYCId name="KYCId">KYCId</a>

Unique identifier for entity instances  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>KYC</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msfsi_kycid</td></tr></table>

### <a href=#KYCPreparedOn name="KYCPreparedOn">KYCPreparedOn</a>

Date on which KYC check was performed.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>KYC Prepared On</td></tr><tr><td>description</td><td>Date on which KYC check was performed.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msfsi_kycpreparedon</td></tr></table>

### <a href=#lastName name="lastName">lastName</a>

Last name of the person.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Name</td></tr><tr><td>description</td><td>Last name of the person.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>sourceName</td><td>msfsi_lastname</td></tr></table>

### <a href=#middleName name="middleName">middleName</a>

Middle name of the person.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Middle Name</td></tr><tr><td>description</td><td>Middle name of the person.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>sourceName</td><td>msfsi_middlename</td></tr></table>

### <a href=#mobileNumber name="mobileNumber">mobileNumber</a>

The primary mobile phone number for the person.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mobile Number</td></tr><tr><td>description</td><td>The primary mobile phone number for the person.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>sourceName</td><td>msfsi_mobilenumber</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msfsi_name</td></tr></table>

### <a href=#nationality name="nationality">nationality</a>

The person’s primary nationality.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Nationality</td></tr><tr><td>description</td><td>The person’s primary nationality.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msfsi_nationality</td></tr></table>

### <a href=#natureOfBusiness name="natureOfBusiness">natureOfBusiness</a>

Nature of the company’s business  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Nature of Business</td></tr><tr><td>description</td><td>Nature of the company’s business</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msfsi_natureofbusiness</td></tr></table>

### <a href=#phoneNumber name="phoneNumber">phoneNumber</a>

The primary phone number of the company  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Phone Number</td></tr><tr><td>description</td><td>The primary phone number of the company</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>sourceName</td><td>msfsi_phonenumber</td></tr></table>

### <a href=#placeOfBirth name="placeOfBirth">placeOfBirth</a>

The person’s place of birth as per the identification document.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Place of Birth</td></tr><tr><td>description</td><td>The person’s place of birth as per the identification document.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msfsi_placeofbirth</td></tr></table>

### <a href=#primaryContactId name="primaryContactId">primaryContactId</a>

The person who is the main contact person at the company.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary Contact</td></tr><tr><td>description</td><td>The person who is the main contact person at the company.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msfsi_primarycontact</td></tr></table>

### <a href=#reviewFrequency name="reviewFrequency">reviewFrequency</a>

The frequency based on which customer must be reviewed.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Review Frequency</td></tr><tr><td>description</td><td>The frequency based on which customer must be reviewed.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msfsi_reviewfrequency</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#reviewFrequency_display name="reviewFrequency_display">reviewFrequency_display</a>

First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#riskLevel name="riskLevel">riskLevel</a>

The general risk level of the customer.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Risk Level</td></tr><tr><td>description</td><td>The general risk level of the customer.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msfsi_risklevel</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#riskLevel_display name="riskLevel_display">riskLevel_display</a>

First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#processId name="processId">processId</a>

Contains the id of the process associated with the entity.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Id</td></tr><tr><td>description</td><td>Contains the id of the process associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#deprecatedStageId name="deprecatedStageId">deprecatedStageId</a>

Contains the id of the stage where the entity is located.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>(Deprecated) Stage Id</td></tr><tr><td>description</td><td>Contains the id of the stage where the entity is located.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the KYC  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the KYC</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the KYC  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the KYC</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#deprecatedTraversedPath name="deprecatedTraversedPath">deprecatedTraversedPath</a>

A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.  
First included in: banking/KYC (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>(Deprecated) Traversed Path</td></tr><tr><td>description</td><td>A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>
