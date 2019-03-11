---
title: SocialProfile - Common Data Model | Microsoft Docs
description: This describes the SocialProfile entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# Social Profile

This entity is used to store social profile information of its associated account and contacts on different social channels.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/SocialProfile.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /SocialProfile  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[ownerId](#ownerId)|Owner Id|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[socialProfileId](#socialProfileId)|Unique Identifier of the social profile name.|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[profileName](#profileName)|Shows the name of the social profile on the corresponding social channel.|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[profileFullName](#profileFullName)|Shows the display name of the customer on this social profile.|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[stateCode](#stateCode)|Status of the Social Profile|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[stateCode_display](#stateCode_display)||<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[statusCode](#statusCode)|Reason for the status of the Social Profile|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[statusCode_display](#statusCode_display)||<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[customerIdType](#customerIdType)|The type of customer, either Account or Contact.|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[customerId](#customerId)|The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[blocked](#blocked)|Identifies if the social profile has been blocked.|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[community](#community)|Identifies where the social profile originated from, such as Twitter, or Facebook.|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[community_display](#community_display)||<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[influenceScore](#influenceScore)|Shows the score that determines the online social influence of the social profile.|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[profileLink](#profileLink)|Shows the customer that this social profile belongs to.|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[uniqueProfileID](#uniqueProfileID)|Unique ID of the Profile ID|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="SocialProfile.md" target="_blank">applicationCommon/SocialProfile</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#socialProfileId name="socialProfileId">socialProfileId</a>

Unique Identifier of the social profile name.  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Social Profile ID</td></tr><tr><td>description</td><td>Unique Identifier of the social profile name.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>socialprofileid</td></tr></table>

### <a href=#profileName name="profileName">profileName</a>

Shows the name of the social profile on the corresponding social channel.  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Profile Name</td></tr><tr><td>description</td><td>Shows the name of the social profile on the corresponding social channel.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>profilename</td></tr></table>

### <a href=#profileFullName name="profileFullName">profileFullName</a>

Shows the display name of the customer on this social profile.  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Full Name</td></tr><tr><td>description</td><td>Shows the display name of the customer on this social profile.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>profilefullname</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Social Profile  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Social Profile</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Social Profile  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Social Profile</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#customerIdType name="customerIdType">customerIdType</a>

The type of customer, either Account or Contact.  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Type</td></tr><tr><td>description</td><td>The type of customer, either Account or Contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>customeridtype</td></tr></table>

### <a href=#customerId name="customerId">customerId</a>

The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>description</td><td>The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customerid</td></tr></table>

### <a href=#blocked name="blocked">blocked</a>

Identifies if the social profile has been blocked.  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Blocked</td></tr><tr><td>description</td><td>Identifies if the social profile has been blocked.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>blocked</td></tr></table>

### <a href=#community name="community">community</a>

Identifies where the social profile originated from, such as Twitter, or Facebook.  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Social Channel</td></tr><tr><td>description</td><td>Identifies where the social profile originated from, such as Twitter, or Facebook.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>community</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Facebook</td><td>1</td></tr><tr><td>en</td><td>Twitter</td><td>2</td></tr><tr><td>en</td><td>Other</td><td>0</td></tr></table></td></tr></table>

### <a href=#community_display name="community_display">community_display</a>

First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#influenceScore name="influenceScore">influenceScore</a>

Shows the score that determines the online social influence of the social profile.  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Influence Score</td></tr><tr><td>description</td><td>Shows the score that determines the online social influence of the social profile.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>influencescore</td></tr></table>

### <a href=#profileLink name="profileLink">profileLink</a>

Shows the customer that this social profile belongs to.  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Profile Link</td></tr><tr><td>description</td><td>Shows the customer that this social profile belongs to.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>profilelink</td></tr></table>

### <a href=#uniqueProfileID name="uniqueProfileID">uniqueProfileID</a>

Unique ID of the Profile ID  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unique Profile ID</td></tr><tr><td>description</td><td>Unique ID of the Profile ID</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>uniqueprofileid</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: applicationCommon/SocialProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>
