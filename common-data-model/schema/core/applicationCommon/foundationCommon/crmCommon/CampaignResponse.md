---
title: CampaignResponse - Common Data Model | Microsoft Docs
description: Response from an existing or a potential new customer for a campaign.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Campaign Response

Response from an existing or a potential new customer for a campaign.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/CampaignResponse.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/CampaignResponse  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[ownerId](#ownerId)|Owner Id|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[activityTypeCode](#activityTypeCode)|Type of activity.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[activityId](#activityId)|Unique identifier of the activity.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[isBilled](#isBilled)|Information regarding whether the fax activity was billed as part of resolving a case.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[isRegularActivity](#isRegularActivity)|Information regarding whether the activity is a regular activity type or event type.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[isWorkflowCreated](#isWorkflowCreated)|Information regarding whether the activity was created from a workflow rule.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[priorityCode](#priorityCode)|Priority of the activity.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[priorityCode_display](#priorityCode_display)||<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[regardingObjectTypeCode](#regardingObjectTypeCode)|The name of the entity linked by regardingObjectId|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[regardingObjectId](#regardingObjectId)|Unique identifier of the object with which the activity is associated.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[scheduledEnd](#scheduledEnd)|Scheduled end time of the activity.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[scheduledStart](#scheduledStart)|Scheduled start time of the activity.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[sortDate](#sortDate)|Shows the date and time by which the activities are sorted.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[subject](#subject)|Subject associated with the activity.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[scheduledDurationMinutes](#scheduledDurationMinutes)|Scheduled duration of the activity, specified in minutes.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[actualDurationMinutes](#actualDurationMinutes)|Actual duration of the activity in minutes.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[actualEnd](#actualEnd)|Actual end time of the activity.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[actualStart](#actualStart)|Actual start time of the activity.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[category](#category)|Type a category to identify the activity type, such as lead outreach, customer follow-up, or service alert, to tie the eactivity to a business group or function.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[subcategory](#subcategory)|Type a subcategory to identify the activity type and relate the activity to a specific product, sales region, business group, or other function.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[activityAdditionalParams](#activityAdditionalParams)|Additional information provided by the external application as JSON. For internal use only.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[to](#to)|Enter the account, contact, lead, or user recipients of the phone call.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[from](#from)|Enter the account, contact, lead, or user who made the phone call.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[instanceTypeCode](#instanceTypeCode)|Type of instance of a recurring series.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[instanceTypeCode_display](#instanceTypeCode_display)||<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[isMapiPrivate](#isMapiPrivate)|For internal use only.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[organizer](#organizer)|The user who is in charge of coordinating or leading the activity.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[requiredAttendees](#requiredAttendees)|Enter the account, contact, lead, user, or other equipment resources that are required to attend the appointment.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[optionalAttendees](#optionalAttendees)|Enter the account, contact, lead, user, or other equipment resources that are not needed at the appointment, but can optionally attend.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[seriesId](#seriesId)|Uniqueidentifier specifying the id of recurring series of an instance.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[BCC](#BCC)|Enter the recipients that are included on the activity distribution, but are not displayed to other recipients.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[CC](#CC)|Enter the recipients that should be copied on the activity.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[sentOn](#sentOn)|Date and time when the activity was sent.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[senderMailboxId](#senderMailboxId)|Unique identifier of the mailbox associated with the sender of the email message.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[deliveryPriorityCode](#deliveryPriorityCode)|Priority of delivery of the activity to the email server.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[deliveryPriorityCode_display](#deliveryPriorityCode_display)||<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[resources](#resources)|Users or facility/equipment that are required for the activity.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[community](#community)|Shows how contact about the activity originated, such as from Twitter or Facebook. This field is read-only.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[community_display](#community_display)||<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[leftVoiceMail](#leftVoiceMail)|Left the voice mail|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[deliveryLastAttemptedOn](#deliveryLastAttemptedOn)|Date and time when the delivery of the activity was last attempted.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[exchangeItemId](#exchangeItemId)|The message id of activity which is returned from Exchange Server.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[exchangeWebLink](#exchangeWebLink)|Shows the web link of Activity of type email.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[postponeActivityProcessingUntil](#postponeActivityProcessingUntil)|For internal use only.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[customers](#customers)|Customer with which the activity is associated.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[partners](#partners)|Outsource vendor with which activity is associated.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[description](#description)|Type additional information to describe the campaign response, such as key discussion points or objectives.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[stateCode](#stateCode)|Shows whether the campaign response is open, closed, or canceled. Closed and canceled campaign responses are read-only and can't be edited.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[stateCode_display](#stateCode_display)||<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[statusCode](#statusCode)|Select the campaign response's status.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[statusCode_display](#statusCode_display)||<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[traversedPath](#traversedPath)|For internal use only.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[processId](#processId)|Unique identifier of the Process.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[stageId](#stageId)|Unique identifier of the Stage.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[SLAId](#SLAId)|Choose the service level agreement (SLA) that you want to apply to the case record.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[SLAInvokedId](#SLAInvokedId)|Last SLA that was applied to this case. This field is for internal use only.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[onHoldTime](#onHoldTime)|Shows how long, in minutes, that the record was on hold.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[lastOnHoldTime](#lastOnHoldTime)|Contains the date and time stamp of the last on hold time.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[channelTypeCode](#channelTypeCode)|Select how the response was received, such as phone, letter, fax, or email.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[channelTypeCode_display](#channelTypeCode_display)||<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[companyName](#companyName)|Type the name of the company if the campaign response was received from a new prospect or customer.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[customer](#customer)|Enter the account, contact, or lead that submitted the campaign response, if it was received from an existing prospect or customer.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[emailAddress](#emailAddress)|Type the responder's email address.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[fax](#fax)|Type the responder's fax number.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[firstName](#firstName)|Type the responder's first name if the campaign response was received from a new prospect or customer.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[lastName](#lastName)|Type the responder's last name if the campaign response was received from a new prospect or customer.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[originatingActivityIdTypeCode](#originatingActivityIdTypeCode)|The name of the entity linked by originatingActivityId|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[originatingActivityId](#originatingActivityId)|Choose the phone call, email, fax, letter, or appointment activity that led the prospect or customer to respond to the campaign.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[partner](#partner)|Enter the vendor account or contact to capture any third-party used to obtain the campaign response.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[promotionCodeName](#promotionCodeName)|Type a promotional code to track sales related to the campaign response or to allow the responder to redeem a discount offer.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[receivedOn](#receivedOn)|Enter the date when the campaign response was received.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[responseCode](#responseCode)|Select the type of response from the prospect or customer to indicate their interest in the campaign.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[responseCode_display](#responseCode_display)||<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[telephone](#telephone)|Type the responder's primary phone number.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[yomiCompanyName](#yomiCompanyName)|Type the phonetic spelling of the company name, if specified in Japanese, to make sure the name is pronounced correctly in phone calls and other communications.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[yomiFirstName](#yomiFirstName)|Type the phonetic spelling of the campaign responder's first name, if specified in Japanese, to make sure the name is pronounced correctly in phone calls and other communications.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[yomiLastName](#yomiLastName)|Type the phonetic spelling of the campaign responder's last name, if specified in Japanese, to make sure the name is pronounced correctly in phone calls and other communications.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|
|[serviceId](#serviceId)|Unique identifier for the associated service.|<a href="CampaignResponse.md" target="_blank">crmCommon/CampaignResponse</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#activityTypeCode name="activityTypeCode">activityTypeCode</a>

Type of activity.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Type</td></tr><tr><td>description</td><td>Type of activity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>activitytypecode</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fax</td></tr><tr><td>en</td><td>Phone Call</td></tr><tr><td>en</td><td>Email</td></tr><tr><td>en</td><td>Letter</td></tr><tr><td>en</td><td>Appointment</td></tr><tr><td>en</td><td>Task</td></tr><tr><td>en</td><td>Recurring Appointment</td></tr><tr><td>en</td><td>Quick Campaign</td></tr><tr><td>en</td><td>Campaign Activity</td></tr><tr><td>en</td><td>Campaign Response</td></tr><tr><td>en</td><td>Case Resolution</td></tr><tr><td>en</td><td>Service Activity</td></tr><tr><td>en</td><td>Opportunity Close</td></tr><tr><td>en</td><td>Order Close</td></tr><tr><td>en</td><td>Quote Close</td></tr><tr><td>en</td><td>Alert Subscription</td></tr><tr><td>en</td><td>Invite Redemption</td></tr><tr><td>en</td><td>Portal Comment</td></tr></table></td></tr></table>

### <a href=#activityId name="activityId">activityId</a>

Unique identifier of the activity.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity</td></tr><tr><td>description</td><td>Unique identifier of the activity.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>activityid</td></tr></table>

### <a href=#isBilled name="isBilled">isBilled</a>

Information regarding whether the fax activity was billed as part of resolving a case.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Billed</td></tr><tr><td>description</td><td>Information regarding whether the fax activity was billed as part of resolving a case.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isbilled</td></tr></table>

### <a href=#isRegularActivity name="isRegularActivity">isRegularActivity</a>

Information regarding whether the activity is a regular activity type or event type.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Regular Activity</td></tr><tr><td>description</td><td>Information regarding whether the activity is a regular activity type or event type.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isregularactivity</td></tr></table>

### <a href=#isWorkflowCreated name="isWorkflowCreated">isWorkflowCreated</a>

Information regarding whether the activity was created from a workflow rule.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Workflow Created</td></tr><tr><td>description</td><td>Information regarding whether the activity was created from a workflow rule.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isworkflowcreated</td></tr></table>

### <a href=#priorityCode name="priorityCode">priorityCode</a>

Priority of the activity.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Priority</td></tr><tr><td>description</td><td>Priority of the activity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>prioritycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Low</td><td>0</td></tr><tr><td>en</td><td>Normal</td><td>1</td></tr><tr><td>en</td><td>High</td><td>2</td></tr></table></td></tr></table>

### <a href=#priorityCode_display name="priorityCode_display">priorityCode_display</a>

First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#regardingObjectTypeCode name="regardingObjectTypeCode">regardingObjectTypeCode</a>

The name of the entity linked by regardingObjectId  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regarding Type</td></tr><tr><td>description</td><td>The name of the entity linked by regardingObjectId</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>regardingobjecttypecode</td></tr></table>

### <a href=#regardingObjectId name="regardingObjectId">regardingObjectId</a>

Unique identifier of the object with which the activity is associated.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regarding</td></tr><tr><td>description</td><td>Unique identifier of the object with which the activity is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>regardingobjectid</td></tr></table>

### <a href=#scheduledEnd name="scheduledEnd">scheduledEnd</a>

Scheduled end time of the activity.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Due Date</td></tr><tr><td>description</td><td>Scheduled end time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduledend</td></tr></table>

### <a href=#scheduledStart name="scheduledStart">scheduledStart</a>

Scheduled start time of the activity.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date</td></tr><tr><td>description</td><td>Scheduled start time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduledstart</td></tr></table>

### <a href=#sortDate name="sortDate">sortDate</a>

Shows the date and time by which the activities are sorted.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sort Date</td></tr><tr><td>description</td><td>Shows the date and time by which the activities are sorted.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sortdate</td></tr></table>

### <a href=#subject name="subject">subject</a>

Subject associated with the activity.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject</td></tr><tr><td>description</td><td>Subject associated with the activity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>subject</td></tr></table>

### <a href=#scheduledDurationMinutes name="scheduledDurationMinutes">scheduledDurationMinutes</a>

Scheduled duration of the activity, specified in minutes.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scheduled Duration</td></tr><tr><td>description</td><td>Scheduled duration of the activity, specified in minutes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduleddurationminutes</td></tr></table>

### <a href=#actualDurationMinutes name="actualDurationMinutes">actualDurationMinutes</a>

Actual duration of the activity in minutes.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Duration</td></tr><tr><td>description</td><td>Actual duration of the activity in minutes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualdurationminutes</td></tr></table>

### <a href=#actualEnd name="actualEnd">actualEnd</a>

Actual end time of the activity.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual End</td></tr><tr><td>description</td><td>Actual end time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualend</td></tr></table>

### <a href=#actualStart name="actualStart">actualStart</a>

Actual start time of the activity.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Start</td></tr><tr><td>description</td><td>Actual start time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualstart</td></tr></table>

### <a href=#category name="category">category</a>

Type a category to identify the activity type, such as lead outreach, customer follow-up, or service alert, to tie the eactivity to a business group or function.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Category</td></tr><tr><td>description</td><td>Type a category to identify the activity type, such as lead outreach, customer follow-up, or service alert, to tie the eactivity to a business group or function.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>category</td></tr></table>

### <a href=#subcategory name="subcategory">subcategory</a>

Type a subcategory to identify the activity type and relate the activity to a specific product, sales region, business group, or other function.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sub-Category</td></tr><tr><td>description</td><td>Type a subcategory to identify the activity type and relate the activity to a specific product, sales region, business group, or other function.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>subcategory</td></tr></table>

### <a href=#activityAdditionalParams name="activityAdditionalParams">activityAdditionalParams</a>

Additional information provided by the external application as JSON. For internal use only.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Additional Parameters</td></tr><tr><td>description</td><td>Additional information provided by the external application as JSON. For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>8192</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>activityadditionalparams</td></tr></table>

### <a href=#to name="to">to</a>

Enter the account, contact, lead, or user recipients of the phone call.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Call To</td></tr><tr><td>description</td><td>Enter the account, contact, lead, or user recipients of the phone call.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>to</td></tr></table>

### <a href=#from name="from">from</a>

Enter the account, contact, lead, or user who made the phone call.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Call From</td></tr><tr><td>description</td><td>Enter the account, contact, lead, or user who made the phone call.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>from</td></tr></table>

### <a href=#instanceTypeCode name="instanceTypeCode">instanceTypeCode</a>

Type of instance of a recurring series.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recurring Instance Type</td></tr><tr><td>description</td><td>Type of instance of a recurring series.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>instancetypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not Recurring</td><td>0</td></tr><tr><td>en</td><td>Recurring Master</td><td>1</td></tr><tr><td>en</td><td>Recurring Instance</td><td>2</td></tr><tr><td>en</td><td>Recurring Exception</td><td>3</td></tr><tr><td>en</td><td>Recurring Future Exception</td><td>4</td></tr></table></td></tr></table>

### <a href=#instanceTypeCode_display name="instanceTypeCode_display">instanceTypeCode_display</a>

First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#isMapiPrivate name="isMapiPrivate">isMapiPrivate</a>

For internal use only.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Private</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ismapiprivate</td></tr></table>

### <a href=#organizer name="organizer">organizer</a>

The user who is in charge of coordinating or leading the activity.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organizer</td></tr><tr><td>description</td><td>The user who is in charge of coordinating or leading the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>organizer</td></tr></table>

### <a href=#requiredAttendees name="requiredAttendees">requiredAttendees</a>

Enter the account, contact, lead, user, or other equipment resources that are required to attend the appointment.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Required Attendees</td></tr><tr><td>description</td><td>Enter the account, contact, lead, user, or other equipment resources that are required to attend the appointment.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>requiredattendees</td></tr></table>

### <a href=#optionalAttendees name="optionalAttendees">optionalAttendees</a>

Enter the account, contact, lead, user, or other equipment resources that are not needed at the appointment, but can optionally attend.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Optional Attendees</td></tr><tr><td>description</td><td>Enter the account, contact, lead, user, or other equipment resources that are not needed at the appointment, but can optionally attend.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>optionalattendees</td></tr></table>

### <a href=#seriesId name="seriesId">seriesId</a>

Uniqueidentifier specifying the id of recurring series of an instance.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Series Id</td></tr><tr><td>description</td><td>Uniqueidentifier specifying the id of recurring series of an instance.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>seriesid</td></tr></table>

### <a href=#BCC name="BCC">BCC</a>

Enter the recipients that are included on the activity distribution, but are not displayed to other recipients.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bcc</td></tr><tr><td>description</td><td>Enter the recipients that are included on the activity distribution, but are not displayed to other recipients.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>bcc</td></tr></table>

### <a href=#CC name="CC">CC</a>

Enter the recipients that should be copied on the activity.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cc</td></tr><tr><td>description</td><td>Enter the recipients that should be copied on the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>cc</td></tr></table>

### <a href=#sentOn name="sentOn">sentOn</a>

Date and time when the activity was sent.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Sent</td></tr><tr><td>description</td><td>Date and time when the activity was sent.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>senton</td></tr></table>

### <a href=#senderMailboxId name="senderMailboxId">senderMailboxId</a>

Unique identifier of the mailbox associated with the sender of the email message.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sender's Mailbox</td></tr><tr><td>description</td><td>Unique identifier of the mailbox associated with the sender of the email message.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sendermailboxid</td></tr></table>

### <a href=#deliveryPriorityCode name="deliveryPriorityCode">deliveryPriorityCode</a>

Priority of delivery of the activity to the email server.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery Priority</td></tr><tr><td>description</td><td>Priority of delivery of the activity to the email server.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>deliveryprioritycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Low</td><td>0</td></tr><tr><td>en</td><td>Normal</td><td>1</td></tr><tr><td>en</td><td>High</td><td>2</td></tr></table></td></tr></table>

### <a href=#deliveryPriorityCode_display name="deliveryPriorityCode_display">deliveryPriorityCode_display</a>

First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#resources name="resources">resources</a>

Users or facility/equipment that are required for the activity.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resources</td></tr><tr><td>description</td><td>Users or facility/equipment that are required for the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>resources</td></tr></table>

### <a href=#community name="community">community</a>

Shows how contact about the activity originated, such as from Twitter or Facebook. This field is read-only.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Social Channel</td></tr><tr><td>description</td><td>Shows how contact about the activity originated, such as from Twitter or Facebook. This field is read-only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>community</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Facebook</td><td>1</td></tr><tr><td>en</td><td>Twitter</td><td>2</td></tr><tr><td>en</td><td>Other</td><td>0</td></tr></table></td></tr></table>

### <a href=#community_display name="community_display">community_display</a>

First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#leftVoiceMail name="leftVoiceMail">leftVoiceMail</a>

Left the voice mail  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Left Voice Mail</td></tr><tr><td>description</td><td>Left the voice mail</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>leftvoicemail</td></tr></table>

### <a href=#deliveryLastAttemptedOn name="deliveryLastAttemptedOn">deliveryLastAttemptedOn</a>

Date and time when the delivery of the activity was last attempted.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Delivery Last Attempted</td></tr><tr><td>description</td><td>Date and time when the delivery of the activity was last attempted.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>deliverylastattemptedon</td></tr></table>

### <a href=#exchangeItemId name="exchangeItemId">exchangeItemId</a>

The message id of activity which is returned from Exchange Server.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Item ID</td></tr><tr><td>description</td><td>The message id of activity which is returned from Exchange Server.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangeitemid</td></tr></table>

### <a href=#exchangeWebLink name="exchangeWebLink">exchangeWebLink</a>

Shows the web link of Activity of type email.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange WebLink</td></tr><tr><td>description</td><td>Shows the web link of Activity of type email.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangeweblink</td></tr></table>

### <a href=#postponeActivityProcessingUntil name="postponeActivityProcessingUntil">postponeActivityProcessingUntil</a>

For internal use only.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delay activity processing until</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postponeactivityprocessinguntil</td></tr></table>

### <a href=#customers name="customers">customers</a>

Customer with which the activity is associated.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customers</td></tr><tr><td>description</td><td>Customer with which the activity is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customers</td></tr></table>

### <a href=#partners name="partners">partners</a>

Outsource vendor with which activity is associated.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Outsource Vendors</td></tr><tr><td>description</td><td>Outsource vendor with which activity is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>partners</td></tr></table>

### <a href=#description name="description">description</a>

Type additional information to describe the campaign response, such as key discussion points or objectives.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type additional information to describe the campaign response, such as key discussion points or objectives.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the campaign response is open, closed, or canceled. Closed and canceled campaign responses are read-only and can't be edited.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows whether the campaign response is open, closed, or canceled. Closed and canceled campaign responses are read-only and can't be edited.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Open</td><td>0</td></tr><tr><td>en</td><td>Closed</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>2</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the campaign response's status.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the campaign response's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Open</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Closed</td><td>2</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>3</td><td>2</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

For internal use only.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#processId name="processId">processId</a>

Unique identifier of the Process.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process</td></tr><tr><td>description</td><td>Unique identifier of the Process.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Unique identifier of the Stage.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Stage</td></tr><tr><td>description</td><td>Unique identifier of the Stage.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#SLAId name="SLAId">SLAId</a>

Choose the service level agreement (SLA) that you want to apply to the case record.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SLA</td></tr><tr><td>description</td><td>Choose the service level agreement (SLA) that you want to apply to the case record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slaid</td></tr></table>

### <a href=#SLAInvokedId name="SLAInvokedId">SLAInvokedId</a>

Last SLA that was applied to this case. This field is for internal use only.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last SLA applied</td></tr><tr><td>description</td><td>Last SLA that was applied to this case. This field is for internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slainvokedid</td></tr></table>

### <a href=#onHoldTime name="onHoldTime">onHoldTime</a>

Shows how long, in minutes, that the record was on hold.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>On Hold Time (Minutes)</td></tr><tr><td>description</td><td>Shows how long, in minutes, that the record was on hold.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>onholdtime</td></tr></table>

### <a href=#lastOnHoldTime name="lastOnHoldTime">lastOnHoldTime</a>

Contains the date and time stamp of the last on hold time.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last On Hold Time</td></tr><tr><td>description</td><td>Contains the date and time stamp of the last on hold time.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastonholdtime</td></tr></table>

### <a href=#channelTypeCode name="channelTypeCode">channelTypeCode</a>

Select how the response was received, such as phone, letter, fax, or email.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Channel</td></tr><tr><td>description</td><td>Select how the response was received, such as phone, letter, fax, or email.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>channeltypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Email</td><td>1</td></tr><tr><td>en</td><td>Phone</td><td>2</td></tr><tr><td>en</td><td>Fax</td><td>3</td></tr><tr><td>en</td><td>Letter</td><td>4</td></tr><tr><td>en</td><td>Appointment</td><td>5</td></tr><tr><td>en</td><td>Others</td><td>6</td></tr></table></td></tr></table>

### <a href=#channelTypeCode_display name="channelTypeCode_display">channelTypeCode_display</a>

First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#companyName name="companyName">companyName</a>

Type the name of the company if the campaign response was received from a new prospect or customer.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Company Name</td></tr><tr><td>description</td><td>Type the name of the company if the campaign response was received from a new prospect or customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>companyname</td></tr></table>

### <a href=#customer name="customer">customer</a>

Enter the account, contact, or lead that submitted the campaign response, if it was received from an existing prospect or customer.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>description</td><td>Enter the account, contact, or lead that submitted the campaign response, if it was received from an existing prospect or customer.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customer</td></tr></table>

### <a href=#emailAddress name="emailAddress">emailAddress</a>

Type the responder's email address.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email</td></tr><tr><td>description</td><td>Type the responder's email address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailaddress</td></tr></table>

### <a href=#fax name="fax">fax</a>

Type the responder's fax number.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fax</td></tr><tr><td>description</td><td>Type the responder's fax number.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>fax</td></tr></table>

### <a href=#firstName name="firstName">firstName</a>

Type the responder's first name if the campaign response was received from a new prospect or customer.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>First Name</td></tr><tr><td>description</td><td>Type the responder's first name if the campaign response was received from a new prospect or customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>firstname</td></tr></table>

### <a href=#lastName name="lastName">lastName</a>

Type the responder's last name if the campaign response was received from a new prospect or customer.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Name</td></tr><tr><td>description</td><td>Type the responder's last name if the campaign response was received from a new prospect or customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastname</td></tr></table>

### <a href=#originatingActivityIdTypeCode name="originatingActivityIdTypeCode">originatingActivityIdTypeCode</a>

The name of the entity linked by originatingActivityId  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>originatingActivityId Type</td></tr><tr><td>description</td><td>The name of the entity linked by originatingActivityId</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>originatingactivityidtypecode</td></tr></table>

### <a href=#originatingActivityId name="originatingActivityId">originatingActivityId</a>

Choose the phone call, email, fax, letter, or appointment activity that led the prospect or customer to respond to the campaign.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Originating Activity</td></tr><tr><td>description</td><td>Choose the phone call, email, fax, letter, or appointment activity that led the prospect or customer to respond to the campaign.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>originatingactivityid</td></tr></table>

### <a href=#partner name="partner">partner</a>

Enter the vendor account or contact to capture any third-party used to obtain the campaign response.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Outsource Vendor</td></tr><tr><td>description</td><td>Enter the vendor account or contact to capture any third-party used to obtain the campaign response.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>partner</td></tr></table>

### <a href=#promotionCodeName name="promotionCodeName">promotionCodeName</a>

Type a promotional code to track sales related to the campaign response or to allow the responder to redeem a discount offer.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Promotion Code</td></tr><tr><td>description</td><td>Type a promotional code to track sales related to the campaign response or to allow the responder to redeem a discount offer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>promotioncodename</td></tr></table>

### <a href=#receivedOn name="receivedOn">receivedOn</a>

Enter the date when the campaign response was received.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Received On</td></tr><tr><td>description</td><td>Enter the date when the campaign response was received.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>receivedon</td></tr></table>

### <a href=#responseCode name="responseCode">responseCode</a>

Select the type of response from the prospect or customer to indicate their interest in the campaign.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Response Code</td></tr><tr><td>description</td><td>Select the type of response from the prospect or customer to indicate their interest in the campaign.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>responsecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Interested</td><td>1</td></tr><tr><td>en</td><td>Not Interested</td><td>2</td></tr><tr><td>en</td><td>Do Not Send Marketing Materials</td><td>3</td></tr><tr><td>en</td><td>Error</td><td>4</td></tr></table></td></tr></table>

### <a href=#responseCode_display name="responseCode_display">responseCode_display</a>

First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#telephone name="telephone">telephone</a>

Type the responder's primary phone number.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Phone</td></tr><tr><td>description</td><td>Type the responder's primary phone number.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>telephone</td></tr></table>

### <a href=#yomiCompanyName name="yomiCompanyName">yomiCompanyName</a>

Type the phonetic spelling of the company name, if specified in Japanese, to make sure the name is pronounced correctly in phone calls and other communications.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Yomi Company Name</td></tr><tr><td>description</td><td>Type the phonetic spelling of the company name, if specified in Japanese, to make sure the name is pronounced correctly in phone calls and other communications.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>yomicompanyname</td></tr></table>

### <a href=#yomiFirstName name="yomiFirstName">yomiFirstName</a>

Type the phonetic spelling of the campaign responder's first name, if specified in Japanese, to make sure the name is pronounced correctly in phone calls and other communications.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Yomi First Name</td></tr><tr><td>description</td><td>Type the phonetic spelling of the campaign responder's first name, if specified in Japanese, to make sure the name is pronounced correctly in phone calls and other communications.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>150</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>yomifirstname</td></tr></table>

### <a href=#yomiLastName name="yomiLastName">yomiLastName</a>

Type the phonetic spelling of the campaign responder's last name, if specified in Japanese, to make sure the name is pronounced correctly in phone calls and other communications.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Yomi Last Name</td></tr><tr><td>description</td><td>Type the phonetic spelling of the campaign responder's last name, if specified in Japanese, to make sure the name is pronounced correctly in phone calls and other communications.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>150</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>yomilastname</td></tr></table>

### <a href=#serviceId name="serviceId">serviceId</a>

Unique identifier for the associated service.  
First included in: crmCommon/CampaignResponse (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Service</td></tr><tr><td>description</td><td>Unique identifier for the associated service.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>serviceid</td></tr></table>
