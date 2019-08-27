---
title: CustomerProfile - Common Data Model | Microsoft Docs
description: A person or organization that either performed or has the potential to engage in a business activity. 
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Customer Profile

A person or organization that either performed or has the potential to engage in a business activity.   
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/customerInsights/CustomerProfile.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/customerInsights/CustomerProfile  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[ownerId](#ownerId)|Owner Id|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[accountNumber](#accountNumber)|Type an ID number or code for the customer to quickly search and identify the customer in system views.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[affiliations](#affiliations)|Different affiliations associated with the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[alumniOf](#alumniOf)|Alumni customer is a part of.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[anniversary](#anniversary)|Date of the customer's wedding or service anniversary for use in customer gift programs or other communications.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[assistantName](#assistantName)|Name of the customer's assistant.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[awards](#awards)|List of award(s) received by the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[billingAddress](#billingAddress)|Billing address of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[birthDate](#birthDate)||<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[childrenNames](#childrenNames)|Customer's children name(s).|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[churnScore](#churnScore)|Churn score of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[companyName](#companyName)|Company name of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[countryOrRegion](#countryOrRegion)||<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[culture](#culture)|The culture of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[currencyName](#currencyName)||<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[customerIdType](#customerIdType)|The type of customer, either Account or Contact.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[customerId](#customerId)|The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[customerProfileId](#customerProfileId)|Unique identifier for entity instances|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[customerProfileNumber](#customerProfileNumber)||<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[department](#department)|The department or business unit where the customer works in the parent company or business.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[description](#description)|Additional information to describe the customer, such as an excerpt from the company's website.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[donotBulkEmail](#donotBulkEmail)|Select whether the customer accepts bulk email sent through marketing campaigns or quick campaigns. If Do Not Allow is selected, the customer can be added to marketing lists, but will be excluded from the email.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[doNotBulkPostalMail](#doNotBulkPostalMail)|Select whether the customer accepts bulk postal mail sent through marketing campaigns or quick campaigns. If Do Not Allow is selected, the customer can be added to marketing lists, but will be excluded from the letters.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[donotContact](#donotContact)|Select whether the customer allows direct contact from Microsoft Dynamics 365 Customer Insights. If Do Not Contact is selected, Microsoft Dynamics 365 Customer Insights will not contact the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[doNotEmail](#doNotEmail)|Select whether the customer allows direct email sent from Microsoft Dynamics 365 Customer Insights. If Do Not Allow is selected, Microsoft Dynamics 365 Customer Insights will not send the email.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[doNotFax](#doNotFax)|Select whether the customer allows faxes. If Do Not Allow is selected, the customer will be excluded from any fax activities distributed in marketing campaigns.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[doNotPhone](#doNotPhone)|Select whether the customer accepts phone calls. If Do Not Allow is selected, the customer will be excluded from any phone call activities distributed in marketing campaigns.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[doNotPostalMail](#doNotPostalMail)|Select whether the customer allows direct mail. If Do Not Allow is selected, the customer will be excluded from letter activities distributed in marketing campaigns.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[educationCode](#educationCode)|Highest level of education of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[employeeIdentifier](#employeeIdentifier)|The employee ID or number for the customer for reference in orders, service cases, or other communications with the customer's organization.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[employmentStartDate](#employmentStartDate)|Employment start date of the customer for reference in with the customer's organization.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[engagementScore](#engagementScore)|Engagement score of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[facebookProfile](#facebookProfile)|Facebook profile url of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[familyStatus](#familyStatus)||<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[familyStatus_display](#familyStatus_display)||<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[fax](#fax)|Fax number to send fax to the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[firstName](#firstName)|The customer's first name to make sure the customer is addressed correctly in sales calls, email, and marketing campaigns.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[firstNamePronunciation](#firstNamePronunciation)|The customer's first name pronunciation to make sure the customer is pronounced correctly in sales calls, email, and marketing campaigns.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[fraudScore](#fraudScore)|Calculated fraud score of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[fTPSiteUrl](#fTPSiteUrl)|The URL for the contact's FTP site to enable users to access data and share documents.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[gamerTag](#gamerTag)|The gamertag from the Xbox world of the  customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[gender](#gender)|The customer's gender to make sure the contact is addressed correctly in sales calls, email, and marketing campaigns.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[gender_display](#gender_display)||<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[hasChildren](#hasChildren)|Specify whether the customer has any children for reference in follow-up phone calls and other communications.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[hasPets](#hasPets)|Specify whether the customer has any pets for reference in follow-up phone calls and other communications.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[hobbies](#hobbies)|List down the hobbies of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[homeOwnershipType](#homeOwnershipType)|Specify the type of home owned by the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[homePhone](#homePhone)|Home phone number for this customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[industryCode](#industryCode)|Select the customer's primary industry for use in marketing segmentation and demographic analysis.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[industryCode_display](#industryCode_display)||<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[influencerScore](#influencerScore)|Calculated influencer score of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[instagramHandle](#instagramHandle)|Instagram handle of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[interests](#interests)|List down all the interests of this customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[isGovernment](#isGovernment)|Specify if the customer belongs to or works for government.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[isLead](#isLead)||<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[isPublicSector](#isPublicSector)|Specify if the customer works in public sector.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[jobTitle](#jobTitle)|The job title of the customer to make sure the customer is addressed correctly in sales calls, email, and marketing campaigns.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[knownSince](#knownSince)|Specify the date since when the customer is known.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[language](#language)|Specify the language(s) the customer can interact with.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[lastName](#lastName)|The customer's last name to make sure the customer is addressed correctly in sales calls, email, and marketing campaigns.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[lastNamePronunciation](#lastNamePronunciation)|The customer's last name pronunciation to make sure the customer is pronounced correctly in sales calls, email, and marketing campaigns.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[lifeTimeValue](#lifeTimeValue)|Calculated life time value of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[linkedinProfile](#linkedinProfile)|LinkedIn profile url of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[mailingAddress](#mailingAddress)|Mailing address of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[middleName](#middleName)|The customer's middle name or initial to make sure the customer is addressed correctly.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[middleNamePronunciation](#middleNamePronunciation)|The customer's middle name or initial pronunciation to make sure the customer is pronounced correctly.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[mobilePhone](#mobilePhone)|The mobile phone number for the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[nameAlias](#nameAlias)|Alternate name of the customer that can be used as their alias.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[namePrefix](#namePrefix)|Any prefix assigned to the customer's name.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[nameSuffix](#nameSuffix)|Any suffix assigned to the customer's name.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[nationality](#nationality)|Nationality of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[nickName](#nickName)|Nick name of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[notes](#notes)|Any additional information about the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[numberOfChildren](#numberOfChildren)|The number of children the customer has for reference in follow-up phone calls and other communications.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[pinterestId](#pinterestId)|Pinterest identifier of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[poBoxAddress](#poBoxAddress)|PO Box address of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[postalCode](#postalCode)|Postal code of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[preferredCallTime](#preferredCallTime)||<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[preferredCallTime_display](#preferredCallTime_display)||<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[preferredContactMethodCode](#preferredContactMethodCode)||<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[preferredContactMethodCode_display](#preferredContactMethodCode_display)||<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[preferredName](#preferredName)|Preferred name of the customer to be used in communication.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[primaryEmail](#primaryEmail)|Primary email address of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[primaryPhone](#primaryPhone)|Primary contact phone number of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[profileImage](#profileImage)|Profile image url location of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[profileSubtype](#profileSubtype)|Profile subtype to define the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[profileType](#profileType)|Profile type to define the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[profileType_display](#profileType_display)||<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[salutation](#salutation)|The salutation of the customer to make sure the customer is addressed correctly in sales calls, email messages, and marketing campaigns.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[satisfactionScore](#satisfactionScore)|Calculated satisfaction score of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[secondaryEmail](#secondaryEmail)|Secondary email address of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[sentimentScore](#sentimentScore)|Calculated sentiment score of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[shippingAddress](#shippingAddress)|Shipping address of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[spouseName](#spouseName)|The name of the customer's spouse or partner for reference during calls, events, or other communications with the contact.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[systemOfOrigin](#systemOfOrigin)|Origin source of the customer data.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[tags](#tags)|Any tags associated with the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[totalLifetimeSpendAmount](#totalLifetimeSpendAmount)|Value of the Total Lifetime Spend Amount in transaction currency.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[totallifetimespendamount_Base](#totallifetimespendamount_Base)|Value of the Total Lifetime Spend Amount in base currency.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[totalTransactionCount](#totalTransactionCount)|Value of the total number of transactions performed by the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[twitterHandle](#twitterHandle)|Twitter account name / handle of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[version](#version)|Denotes latest version of the customer profile for manual tracking.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[websiteUrl](#websiteUrl)|Website url to identify the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[workAddress](#workAddress)|Work address of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[workPhone](#workPhone)|Work phone number of the customer.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[stateCode](#stateCode)|Status of the CustomerProfile|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[stateCode_display](#stateCode_display)||<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[statusCode](#statusCode)|Reason for the status of the CustomerProfile|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[statusCode_display](#statusCode_display)||<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="CustomerProfile.md" target="_blank">customerInsights/CustomerProfile</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>sourceName</td><td>ExchangeRate</td></tr></table>

### <a href=#accountNumber name="accountNumber">accountNumber</a>

Type an ID number or code for the customer to quickly search and identify the customer in system views.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account Number</td></tr><tr><td>description</td><td>Type an ID number or code for the customer to quickly search and identify the customer in system views.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_AccountNumber</td></tr></table>

### <a href=#affiliations name="affiliations">affiliations</a>

Different affiliations associated with the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Affiliations</td></tr><tr><td>description</td><td>Different affiliations associated with the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>sourceName</td><td>msdynci_Affiliations</td></tr></table>

### <a href=#alumniOf name="alumniOf">alumniOf</a>

Alumni customer is a part of.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Alumni Of</td></tr><tr><td>description</td><td>Alumni customer is a part of.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>sourceName</td><td>msdynci_AlumniOf</td></tr></table>

### <a href=#anniversary name="anniversary">anniversary</a>

Date of the customer's wedding or service anniversary for use in customer gift programs or other communications.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Anniversary</td></tr><tr><td>description</td><td>Date of the customer's wedding or service anniversary for use in customer gift programs or other communications.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msdynci_Anniversary</td></tr></table>

### <a href=#assistantName name="assistantName">assistantName</a>

Name of the customer's assistant.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Assistant Name</td></tr><tr><td>description</td><td>Name of the customer's assistant.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_AssistantName</td></tr></table>

### <a href=#awards name="awards">awards</a>

List of award(s) received by the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Awards</td></tr><tr><td>description</td><td>List of award(s) received by the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>sourceName</td><td>msdynci_Awards</td></tr></table>

### <a href=#billingAddress name="billingAddress">billingAddress</a>

Billing address of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Billing Address</td></tr><tr><td>description</td><td>Billing address of the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>sourceName</td><td>msdynci_BillingAddress</td></tr></table>

### <a href=#birthDate name="birthDate">birthDate</a>

First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Birthday</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msdynci_BirthDate</td></tr></table>

### <a href=#childrenNames name="childrenNames">childrenNames</a>

Customer's children name(s).  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Children Names</td></tr><tr><td>description</td><td>Customer's children name(s).</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>sourceName</td><td>msdynci_ChildrenNames</td></tr></table>

### <a href=#churnScore name="churnScore">churnScore</a>

Churn score of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Churn Score</td></tr><tr><td>description</td><td>Churn score of the customer.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>sourceName</td><td>msdynci_ChurnScore</td></tr></table>

### <a href=#companyName name="companyName">companyName</a>

Company name of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Company Name</td></tr><tr><td>description</td><td>Company name of the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_CompanyName</td></tr></table>

### <a href=#countryOrRegion name="countryOrRegion">countryOrRegion</a>

First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country/Region</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_CountryOrRegion</td></tr></table>

### <a href=#culture name="culture">culture</a>

The culture of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Culture</td></tr><tr><td>description</td><td>The culture of the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_Culture</td></tr></table>

### <a href=#currencyName name="currencyName">currencyName</a>

First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency Name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_CurrencyName</td></tr></table>

### <a href=#customerIdType name="customerIdType">customerIdType</a>

The type of customer, either Account or Contact.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Type</td></tr><tr><td>description</td><td>The type of customer, either Account or Contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>customeridtype</td></tr></table>

### <a href=#customerId name="customerId">customerId</a>

The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>description</td><td>The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customerid</td></tr></table>

### <a href=#customerProfileId name="customerProfileId">customerProfileId</a>

Unique identifier for entity instances  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>CustomerProfile</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdynci_CustomerProfileId</td></tr></table>

### <a href=#customerProfileNumber name="customerProfileNumber">customerProfileNumber</a>

First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Profile Number</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_CustomerProfileNumber</td></tr></table>

### <a href=#department name="department">department</a>

The department or business unit where the customer works in the parent company or business.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Department</td></tr><tr><td>description</td><td>The department or business unit where the customer works in the parent company or business.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_Department</td></tr></table>

### <a href=#description name="description">description</a>

Additional information to describe the customer, such as an excerpt from the company's website.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Additional information to describe the customer, such as an excerpt from the company's website.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>sourceName</td><td>msdynci_Description</td></tr></table>

### <a href=#donotBulkEmail name="donotBulkEmail">donotBulkEmail</a>

Select whether the customer accepts bulk email sent through marketing campaigns or quick campaigns. If Do Not Allow is selected, the customer can be added to marketing lists, but will be excluded from the email.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not allow Bulk Emails</td></tr><tr><td>description</td><td>Select whether the customer accepts bulk email sent through marketing campaigns or quick campaigns. If Do Not Allow is selected, the customer can be added to marketing lists, but will be excluded from the email.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>msdynci_DonotBulkEmail</td></tr></table>

### <a href=#doNotBulkPostalMail name="doNotBulkPostalMail">doNotBulkPostalMail</a>

Select whether the customer accepts bulk postal mail sent through marketing campaigns or quick campaigns. If Do Not Allow is selected, the customer can be added to marketing lists, but will be excluded from the letters.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not allow Bulk Postal Mails</td></tr><tr><td>description</td><td>Select whether the customer accepts bulk postal mail sent through marketing campaigns or quick campaigns. If Do Not Allow is selected, the customer can be added to marketing lists, but will be excluded from the letters.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>msdynci_DoNotBulkPostalMail</td></tr></table>

### <a href=#donotContact name="donotContact">donotContact</a>

Select whether the customer allows direct contact from Microsoft Dynamics 365 Customer Insights. If Do Not Contact is selected, Microsoft Dynamics 365 Customer Insights will not contact the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not Contact</td></tr><tr><td>description</td><td>Select whether the customer allows direct contact from Microsoft Dynamics 365 Customer Insights. If Do Not Contact is selected, Microsoft Dynamics 365 Customer Insights will not contact the customer.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>msdynci_DonotContact</td></tr></table>

### <a href=#doNotEmail name="doNotEmail">doNotEmail</a>

Select whether the customer allows direct email sent from Microsoft Dynamics 365 Customer Insights. If Do Not Allow is selected, Microsoft Dynamics 365 Customer Insights will not send the email.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not allow Emails</td></tr><tr><td>description</td><td>Select whether the customer allows direct email sent from Microsoft Dynamics 365 Customer Insights. If Do Not Allow is selected, Microsoft Dynamics 365 Customer Insights will not send the email.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>msdynci_DoNotEmail</td></tr></table>

### <a href=#doNotFax name="doNotFax">doNotFax</a>

Select whether the customer allows faxes. If Do Not Allow is selected, the customer will be excluded from any fax activities distributed in marketing campaigns.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not allow Faxes</td></tr><tr><td>description</td><td>Select whether the customer allows faxes. If Do Not Allow is selected, the customer will be excluded from any fax activities distributed in marketing campaigns.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>msdynci_DoNotFax</td></tr></table>

### <a href=#doNotPhone name="doNotPhone">doNotPhone</a>

Select whether the customer accepts phone calls. If Do Not Allow is selected, the customer will be excluded from any phone call activities distributed in marketing campaigns.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not allow Phone Calls</td></tr><tr><td>description</td><td>Select whether the customer accepts phone calls. If Do Not Allow is selected, the customer will be excluded from any phone call activities distributed in marketing campaigns.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>msdynci_DoNotPhone</td></tr></table>

### <a href=#doNotPostalMail name="doNotPostalMail">doNotPostalMail</a>

Select whether the customer allows direct mail. If Do Not Allow is selected, the customer will be excluded from letter activities distributed in marketing campaigns.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Do not allow Postal Mails</td></tr><tr><td>description</td><td>Select whether the customer allows direct mail. If Do Not Allow is selected, the customer will be excluded from letter activities distributed in marketing campaigns.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>msdynci_DoNotPostalMail</td></tr></table>

### <a href=#educationCode name="educationCode">educationCode</a>

Highest level of education of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Education Code</td></tr><tr><td>description</td><td>Highest level of education of the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_EducationCode</td></tr></table>

### <a href=#employeeIdentifier name="employeeIdentifier">employeeIdentifier</a>

The employee ID or number for the customer for reference in orders, service cases, or other communications with the customer's organization.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Employee Identifier</td></tr><tr><td>description</td><td>The employee ID or number for the customer for reference in orders, service cases, or other communications with the customer's organization.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_EmployeeIdentifier</td></tr></table>

### <a href=#employmentStartDate name="employmentStartDate">employmentStartDate</a>

Employment start date of the customer for reference in with the customer's organization.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Employment Start Date</td></tr><tr><td>description</td><td>Employment start date of the customer for reference in with the customer's organization.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msdynci_EmploymentStartDate</td></tr></table>

### <a href=#engagementScore name="engagementScore">engagementScore</a>

Engagement score of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Engagement Score</td></tr><tr><td>description</td><td>Engagement score of the customer.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>sourceName</td><td>msdynci_EngagementScore</td></tr></table>

### <a href=#facebookProfile name="facebookProfile">facebookProfile</a>

Facebook profile url of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Facebook Profile</td></tr><tr><td>description</td><td>Facebook profile url of the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_FacebookProfile</td></tr></table>

### <a href=#familyStatus name="familyStatus">familyStatus</a>

First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Family Status</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msdynci_FamilyStatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#familyStatus_display name="familyStatus_display">familyStatus_display</a>

First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#fax name="fax">fax</a>

Fax number to send fax to the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fax</td></tr><tr><td>description</td><td>Fax number to send fax to the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_Fax</td></tr></table>

### <a href=#firstName name="firstName">firstName</a>

The customer's first name to make sure the customer is addressed correctly in sales calls, email, and marketing campaigns.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>First Name</td></tr><tr><td>description</td><td>The customer's first name to make sure the customer is addressed correctly in sales calls, email, and marketing campaigns.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_FirstName</td></tr></table>

### <a href=#firstNamePronunciation name="firstNamePronunciation">firstNamePronunciation</a>

The customer's first name pronunciation to make sure the customer is pronounced correctly in sales calls, email, and marketing campaigns.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>First Name Pronunciation</td></tr><tr><td>description</td><td>The customer's first name pronunciation to make sure the customer is pronounced correctly in sales calls, email, and marketing campaigns.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_FirstNamePronunciation</td></tr></table>

### <a href=#fraudScore name="fraudScore">fraudScore</a>

Calculated fraud score of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fraud Score</td></tr><tr><td>description</td><td>Calculated fraud score of the customer.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>sourceName</td><td>msdynci_FraudScore</td></tr></table>

### <a href=#fTPSiteUrl name="fTPSiteUrl">fTPSiteUrl</a>

The URL for the contact's FTP site to enable users to access data and share documents.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>FTP Site Url</td></tr><tr><td>description</td><td>The URL for the contact's FTP site to enable users to access data and share documents.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_FTPSiteUrl</td></tr></table>

### <a href=#gamerTag name="gamerTag">gamerTag</a>

The gamertag from the Xbox world of the  customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>GamerTag</td></tr><tr><td>description</td><td>The gamertag from the Xbox world of the  customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_GamerTag</td></tr></table>

### <a href=#gender name="gender">gender</a>

The customer's gender to make sure the contact is addressed correctly in sales calls, email, and marketing campaigns.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Gender</td></tr><tr><td>description</td><td>The customer's gender to make sure the contact is addressed correctly in sales calls, email, and marketing campaigns.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msdynci_Gender</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#gender_display name="gender_display">gender_display</a>

First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#hasChildren name="hasChildren">hasChildren</a>

Specify whether the customer has any children for reference in follow-up phone calls and other communications.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Has Children</td></tr><tr><td>description</td><td>Specify whether the customer has any children for reference in follow-up phone calls and other communications.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>msdynci_HasChildren</td></tr></table>

### <a href=#hasPets name="hasPets">hasPets</a>

Specify whether the customer has any pets for reference in follow-up phone calls and other communications.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Has Pets</td></tr><tr><td>description</td><td>Specify whether the customer has any pets for reference in follow-up phone calls and other communications.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>msdynci_HasPets</td></tr></table>

### <a href=#hobbies name="hobbies">hobbies</a>

List down the hobbies of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Hobbies</td></tr><tr><td>description</td><td>List down the hobbies of the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>sourceName</td><td>msdynci_Hobbies</td></tr></table>

### <a href=#homeOwnershipType name="homeOwnershipType">homeOwnershipType</a>

Specify the type of home owned by the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Home Ownership Type</td></tr><tr><td>description</td><td>Specify the type of home owned by the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_HomeOwnershipType</td></tr></table>

### <a href=#homePhone name="homePhone">homePhone</a>

Home phone number for this customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Home Phone</td></tr><tr><td>description</td><td>Home phone number for this customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_HomePhone</td></tr></table>

### <a href=#industryCode name="industryCode">industryCode</a>

Select the customer's primary industry for use in marketing segmentation and demographic analysis.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Industry</td></tr><tr><td>description</td><td>Select the customer's primary industry for use in marketing segmentation and demographic analysis.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msdynci_IndustryCode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#industryCode_display name="industryCode_display">industryCode_display</a>

First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#influencerScore name="influencerScore">influencerScore</a>

Calculated influencer score of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Influencer Score</td></tr><tr><td>description</td><td>Calculated influencer score of the customer.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>sourceName</td><td>msdynci_InfluencerScore</td></tr></table>

### <a href=#instagramHandle name="instagramHandle">instagramHandle</a>

Instagram handle of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Instagram Handle</td></tr><tr><td>description</td><td>Instagram handle of the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_InstagramHandle</td></tr></table>

### <a href=#interests name="interests">interests</a>

List down all the interests of this customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Interests</td></tr><tr><td>description</td><td>List down all the interests of this customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>sourceName</td><td>msdynci_Interests</td></tr></table>

### <a href=#isGovernment name="isGovernment">isGovernment</a>

Specify if the customer belongs to or works for government.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Government</td></tr><tr><td>description</td><td>Specify if the customer belongs to or works for government.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>msdynci_IsGovernment</td></tr></table>

### <a href=#isLead name="isLead">isLead</a>

First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Lead</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>msdynci_IsLead</td></tr></table>

### <a href=#isPublicSector name="isPublicSector">isPublicSector</a>

Specify if the customer works in public sector.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Public Sector</td></tr><tr><td>description</td><td>Specify if the customer works in public sector.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>msdynci_IsPublicSector</td></tr></table>

### <a href=#jobTitle name="jobTitle">jobTitle</a>

The job title of the customer to make sure the customer is addressed correctly in sales calls, email, and marketing campaigns.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Job Title</td></tr><tr><td>description</td><td>The job title of the customer to make sure the customer is addressed correctly in sales calls, email, and marketing campaigns.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_JobTitle</td></tr></table>

### <a href=#knownSince name="knownSince">knownSince</a>

Specify the date since when the customer is known.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Known Since</td></tr><tr><td>description</td><td>Specify the date since when the customer is known.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msdynci_KnownSince</td></tr></table>

### <a href=#language name="language">language</a>

Specify the language(s) the customer can interact with.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Language</td></tr><tr><td>description</td><td>Specify the language(s) the customer can interact with.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_Language</td></tr></table>

### <a href=#lastName name="lastName">lastName</a>

The customer's last name to make sure the customer is addressed correctly in sales calls, email, and marketing campaigns.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Name</td></tr><tr><td>description</td><td>The customer's last name to make sure the customer is addressed correctly in sales calls, email, and marketing campaigns.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_LastName</td></tr></table>

### <a href=#lastNamePronunciation name="lastNamePronunciation">lastNamePronunciation</a>

The customer's last name pronunciation to make sure the customer is pronounced correctly in sales calls, email, and marketing campaigns.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Name Pronunciation</td></tr><tr><td>description</td><td>The customer's last name pronunciation to make sure the customer is pronounced correctly in sales calls, email, and marketing campaigns.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_LastNamePronunciation</td></tr></table>

### <a href=#lifeTimeValue name="lifeTimeValue">lifeTimeValue</a>

Calculated life time value of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Life Time Value</td></tr><tr><td>description</td><td>Calculated life time value of the customer.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>sourceName</td><td>msdynci_LifeTimeValue</td></tr></table>

### <a href=#linkedinProfile name="linkedinProfile">linkedinProfile</a>

LinkedIn profile url of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LinkedIn Profile</td></tr><tr><td>description</td><td>LinkedIn profile url of the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_LinkedinProfile</td></tr></table>

### <a href=#mailingAddress name="mailingAddress">mailingAddress</a>

Mailing address of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mailing Address</td></tr><tr><td>description</td><td>Mailing address of the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>sourceName</td><td>msdynci_MailingAddress</td></tr></table>

### <a href=#middleName name="middleName">middleName</a>

The customer's middle name or initial to make sure the customer is addressed correctly.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Middle Name</td></tr><tr><td>description</td><td>The customer's middle name or initial to make sure the customer is addressed correctly.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_MiddleName</td></tr></table>

### <a href=#middleNamePronunciation name="middleNamePronunciation">middleNamePronunciation</a>

The customer's middle name or initial pronunciation to make sure the customer is pronounced correctly.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Middle Name Pronunciation</td></tr><tr><td>description</td><td>The customer's middle name or initial pronunciation to make sure the customer is pronounced correctly.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_MiddleNamePronunciation</td></tr></table>

### <a href=#mobilePhone name="mobilePhone">mobilePhone</a>

The mobile phone number for the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mobile Phone</td></tr><tr><td>description</td><td>The mobile phone number for the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_MobilePhone</td></tr></table>

### <a href=#nameAlias name="nameAlias">nameAlias</a>

Alternate name of the customer that can be used as their alias.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name Alias</td></tr><tr><td>description</td><td>Alternate name of the customer that can be used as their alias.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_NameAlias</td></tr></table>

### <a href=#namePrefix name="namePrefix">namePrefix</a>

Any prefix assigned to the customer's name.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name Prefix</td></tr><tr><td>description</td><td>Any prefix assigned to the customer's name.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_NamePrefix</td></tr></table>

### <a href=#nameSuffix name="nameSuffix">nameSuffix</a>

Any suffix assigned to the customer's name.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name Suffix</td></tr><tr><td>description</td><td>Any suffix assigned to the customer's name.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_NameSuffix</td></tr></table>

### <a href=#nationality name="nationality">nationality</a>

Nationality of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Nationality</td></tr><tr><td>description</td><td>Nationality of the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_Nationality</td></tr></table>

### <a href=#nickName name="nickName">nickName</a>

Nick name of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Nick Name</td></tr><tr><td>description</td><td>Nick name of the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_NickName</td></tr></table>

### <a href=#notes name="notes">notes</a>

Any additional information about the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Notes</td></tr><tr><td>description</td><td>Any additional information about the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>sourceName</td><td>msdynci_Notes</td></tr></table>

### <a href=#numberOfChildren name="numberOfChildren">numberOfChildren</a>

The number of children the customer has for reference in follow-up phone calls and other communications.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number of children</td></tr><tr><td>description</td><td>The number of children the customer has for reference in follow-up phone calls and other communications.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>sourceName</td><td>msdynci_NumberOfChildren</td></tr></table>

### <a href=#pinterestId name="pinterestId">pinterestId</a>

Pinterest identifier of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pinterest Id</td></tr><tr><td>description</td><td>Pinterest identifier of the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_PinterestId</td></tr></table>

### <a href=#poBoxAddress name="poBoxAddress">poBoxAddress</a>

PO Box address of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>PO Box Address</td></tr><tr><td>description</td><td>PO Box address of the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>sourceName</td><td>msdynci_PoBoxAddress</td></tr></table>

### <a href=#postalCode name="postalCode">postalCode</a>

Postal code of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Postal Code</td></tr><tr><td>description</td><td>Postal code of the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_PostalCode</td></tr></table>

### <a href=#preferredCallTime name="preferredCallTime">preferredCallTime</a>

First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Preferred Call Time</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msdynci_PreferredCallTime</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#preferredCallTime_display name="preferredCallTime_display">preferredCallTime_display</a>

First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#preferredContactMethodCode name="preferredContactMethodCode">preferredContactMethodCode</a>

First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Preferred Method of Contact</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msdynci_PreferredContactMethodCode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#preferredContactMethodCode_display name="preferredContactMethodCode_display">preferredContactMethodCode_display</a>

First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#preferredName name="preferredName">preferredName</a>

Preferred name of the customer to be used in communication.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Preferred Name</td></tr><tr><td>description</td><td>Preferred name of the customer to be used in communication.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_PreferredName</td></tr></table>

### <a href=#primaryEmail name="primaryEmail">primaryEmail</a>

Primary email address of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary Email</td></tr><tr><td>description</td><td>Primary email address of the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_PrimaryEmail</td></tr></table>

### <a href=#primaryPhone name="primaryPhone">primaryPhone</a>

Primary contact phone number of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary Phone</td></tr><tr><td>description</td><td>Primary contact phone number of the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_PrimaryPhone</td></tr></table>

### <a href=#profileImage name="profileImage">profileImage</a>

Profile image url location of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Profile Image</td></tr><tr><td>description</td><td>Profile image url location of the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_ProfileImage</td></tr></table>

### <a href=#profileSubtype name="profileSubtype">profileSubtype</a>

Profile subtype to define the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Profile Subtype</td></tr><tr><td>description</td><td>Profile subtype to define the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_ProfileSubtype</td></tr></table>

### <a href=#profileType name="profileType">profileType</a>

Profile type to define the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Profile Type</td></tr><tr><td>description</td><td>Profile type to define the customer.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msdynci_ProfileType</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#profileType_display name="profileType_display">profileType_display</a>

First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#salutation name="salutation">salutation</a>

The salutation of the customer to make sure the customer is addressed correctly in sales calls, email messages, and marketing campaigns.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Salutation</td></tr><tr><td>description</td><td>The salutation of the customer to make sure the customer is addressed correctly in sales calls, email messages, and marketing campaigns.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_Salutation</td></tr></table>

### <a href=#satisfactionScore name="satisfactionScore">satisfactionScore</a>

Calculated satisfaction score of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Satisfaction Score</td></tr><tr><td>description</td><td>Calculated satisfaction score of the customer.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>sourceName</td><td>msdynci_SatisfactionScore</td></tr></table>

### <a href=#secondaryEmail name="secondaryEmail">secondaryEmail</a>

Secondary email address of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Secondary Email</td></tr><tr><td>description</td><td>Secondary email address of the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_SecondaryEmail</td></tr></table>

### <a href=#sentimentScore name="sentimentScore">sentimentScore</a>

Calculated sentiment score of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sentiment Score</td></tr><tr><td>description</td><td>Calculated sentiment score of the customer.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>sourceName</td><td>msdynci_SentimentScore</td></tr></table>

### <a href=#shippingAddress name="shippingAddress">shippingAddress</a>

Shipping address of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping Address</td></tr><tr><td>description</td><td>Shipping address of the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>sourceName</td><td>msdynci_ShippingAddress</td></tr></table>

### <a href=#spouseName name="spouseName">spouseName</a>

The name of the customer's spouse or partner for reference during calls, events, or other communications with the contact.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Spouse/Partner Name</td></tr><tr><td>description</td><td>The name of the customer's spouse or partner for reference during calls, events, or other communications with the contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_SpouseName</td></tr></table>

### <a href=#systemOfOrigin name="systemOfOrigin">systemOfOrigin</a>

Origin source of the customer data.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>System of Origin</td></tr><tr><td>description</td><td>Origin source of the customer data.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_SystemOfOrigin</td></tr></table>

### <a href=#tags name="tags">tags</a>

Any tags associated with the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tags</td></tr><tr><td>description</td><td>Any tags associated with the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_Tags</td></tr></table>

### <a href=#totalLifetimeSpendAmount name="totalLifetimeSpendAmount">totalLifetimeSpendAmount</a>

Value of the Total Lifetime Spend Amount in transaction currency.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Lifetime Spend Amount</td></tr><tr><td>description</td><td>Value of the Total Lifetime Spend Amount in transaction currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msdynci_TotalLifetimeSpendAmount</td></tr></table>

### <a href=#totallifetimespendamount_Base name="totallifetimespendamount_Base">totallifetimespendamount_Base</a>

Value of the Total Lifetime Spend Amount in base currency.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Lifetime Spend Amount (Base)</td></tr><tr><td>description</td><td>Value of the Total Lifetime Spend Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msdynci_totallifetimespendamount_Base</td></tr></table>

### <a href=#totalTransactionCount name="totalTransactionCount">totalTransactionCount</a>

Value of the total number of transactions performed by the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Transaction Count</td></tr><tr><td>description</td><td>Value of the total number of transactions performed by the customer.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>sourceName</td><td>msdynci_TotalTransactionCount</td></tr></table>

### <a href=#twitterHandle name="twitterHandle">twitterHandle</a>

Twitter account name / handle of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Twitter Handle</td></tr><tr><td>description</td><td>Twitter account name / handle of the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_TwitterHandle</td></tr></table>

### <a href=#version name="version">version</a>

Denotes latest version of the customer profile for manual tracking.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version</td></tr><tr><td>description</td><td>Denotes latest version of the customer profile for manual tracking.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>sourceName</td><td>msdynci_Version</td></tr></table>

### <a href=#websiteUrl name="websiteUrl">websiteUrl</a>

Website url to identify the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Website Url</td></tr><tr><td>description</td><td>Website url to identify the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_WebsiteUrl</td></tr></table>

### <a href=#workAddress name="workAddress">workAddress</a>

Work address of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Work Address</td></tr><tr><td>description</td><td>Work address of the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>sourceName</td><td>msdynci_WorkAddress</td></tr></table>

### <a href=#workPhone name="workPhone">workPhone</a>

Work phone number of the customer.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Work Phone</td></tr><tr><td>description</td><td>Work phone number of the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msdynci_WorkPhone</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the CustomerProfile  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the CustomerProfile</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>stateCode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the CustomerProfile  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the CustomerProfile</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statusCode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: customerInsights/CustomerProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>
