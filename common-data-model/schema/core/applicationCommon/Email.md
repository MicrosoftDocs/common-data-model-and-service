---
title: Email - Common Data Model | Microsoft Docs
description: Activity that is delivered using email protocols.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Email

Activity that is delivered using email protocols.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/Email.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /Email  
- [/foundationCommon/crmCommon/Email](foundationCommon/crmCommon/Email.md "/core/applicationCommon/foundationCommon/crmCommon/Email.cdm.json/Email")  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[owningUser](#owningUser)|Unique identifier for the user that owns the record.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[activityTypeCode](#activityTypeCode)|Type of activity.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[activityId](#activityId)|Unique identifier of the activity.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[isBilled](#isBilled)|Information regarding whether the fax activity was billed as part of resolving a case.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[isRegularActivity](#isRegularActivity)|Information regarding whether the activity is a regular activity type or event type.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[isWorkflowCreated](#isWorkflowCreated)|Information regarding whether the activity was created from a workflow rule.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[priorityCode](#priorityCode)|Priority of the activity.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[priorityCode_display](#priorityCode_display)||<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[regardingObjectTypeCode](#regardingObjectTypeCode)|The name of the entity linked by regardingObjectId|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[regardingObjectId](#regardingObjectId)|Unique identifier of the object with which the activity is associated.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[scheduledEnd](#scheduledEnd)|Scheduled end time of the activity.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[scheduledStart](#scheduledStart)|Scheduled start time of the activity.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[sortDate](#sortDate)|Shows the date and time by which the activities are sorted.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[subject](#subject)|Subject associated with the activity.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[scheduledDurationMinutes](#scheduledDurationMinutes)|Scheduled duration of the activity, specified in minutes.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[actualDurationMinutes](#actualDurationMinutes)|Actual duration of the activity in minutes.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[actualEnd](#actualEnd)|Actual end time of the activity.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[actualStart](#actualStart)|Actual start time of the activity.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[category](#category)|Type a category to identify the activity type, such as lead outreach, customer follow-up, or service alert, to tie the eactivity to a business group or function.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[subcategory](#subcategory)|Type a subcategory to identify the activity type and relate the activity to a specific product, sales region, business group, or other function.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[activityAdditionalParams](#activityAdditionalParams)|Additional information provided by the external application as JSON. For internal use only.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[to](#to)|Enter the account, contact, lead, or user recipients of the phone call.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[from](#from)|Enter the account, contact, lead, or user who made the phone call.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[BCC](#BCC)|Enter the recipients that are included on the activity distribution, but are not displayed to other recipients.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[CC](#CC)|Enter the recipients that should be copied on the activity.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[sentOn](#sentOn)|Date and time when the activity was sent.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[senderMailboxId](#senderMailboxId)|Unique identifier of the mailbox associated with the sender of the email message.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[deliveryPriorityCode](#deliveryPriorityCode)|Priority of delivery of the activity to the email server.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[deliveryPriorityCode_display](#deliveryPriorityCode_display)||<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[directionCode](#directionCode)|Select the direction of the activity as incoming or outbound.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[statusCode](#statusCode)|Select the email's status.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[statusCode_display](#statusCode_display)||<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[submittedBy](#submittedBy)|Shows the Microsoft Office Outlook account for the user who submitted the email to Microsoft Dynamics 365.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[description](#description)|Type the greeting and message text of the email.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[mimeType](#mimeType)|MIME type of the email message data.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[readReceiptRequested](#readReceiptRequested)|Indicates that a read receipt is requested.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[trackingToken](#trackingToken)|Shows the tracking token assigned to the email to make sure responses are automatically tracked in Microsoft Dynamics 365.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[sender](#sender)|Sender of the email.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[toRecipients](#toRecipients)|Shows the email addresses corresponding to the recipients.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[deliveryReceiptRequested](#deliveryReceiptRequested)|Select whether the sender should receive confirmation that the email was delivered.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[stateCode](#stateCode)|Shows whether the email is open, completed, or canceled. Completed and canceled email is read-only and can't be edited.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[stateCode_display](#stateCode_display)||<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[messageId](#messageId)|Unique identifier of the email message. Used only for email that is received.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[deliveryAttempts](#deliveryAttempts)|Shows the count of the number of attempts made to send the email. The count is used as an indicator of email routing issues.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[compressed](#compressed)|Indicates if the body is compressed.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[notifications](#notifications)|Select the notification code to identify issues with the email recipients or attachments, such as blocked attachments.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[notifications_display](#notifications_display)||<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[emailSenderObjectTypeCode](#emailSenderObjectTypeCode)|The name of the entity linked by emailSender|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[emailSender](#emailSender)|Shows the sender of the email.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[sendersAccountObjectTypeCode](#sendersAccountObjectTypeCode)|The name of the entity linked by sendersAccount|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[sendersAccount](#sendersAccount)|Shows the parent account of the sender of the email.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[attachmentCount](#attachmentCount)|Shows the umber of attachments of the email message.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[parentActivityId](#parentActivityId)|Select the activity that the email is associated with.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[inReplyTo](#inReplyTo)|Type the ID of the email message that this email activity is a response to.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[baseConversationIndexHash](#baseConversationIndexHash)|Hash of base of conversation index.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[conversationIndex](#conversationIndex)|Identifier for all the email responses for this conversation.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[correlationMethod](#correlationMethod)|Shows how an email is matched to an existing email in Microsoft Dynamics 365. For system use only.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[correlationMethod_display](#correlationMethod_display)||<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[postponeEmailProcessingUntil](#postponeEmailProcessingUntil)|For internal use only.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[processId](#processId)|Shows the ID of the process.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[stageId](#stageId)|Shows the ID of the stage.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[isUnsafe](#isUnsafe)|For internal use only.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[SLAId](#SLAId)|Choose the service level agreement (SLA) that you want to apply to the email record.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[SLAInvokedId](#SLAInvokedId)|Last SLA that was applied to this email. This field is for internal use only.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[onHoldTime](#onHoldTime)|Shows how long, in minutes, that the record was on hold.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[lastOnHoldTime](#lastOnHoldTime)|Contains the date and time stamp of the last on hold time.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[traversedPath](#traversedPath)|For internal use only.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[attachmentOpenCount](#attachmentOpenCount)|Shows the number of times an email attachment has been viewed.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[conversationTrackingId](#conversationTrackingId)|Conversation Tracking Id.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[delayedEmailSendTime](#delayedEmailSendTime)|Enter the expected date and time when email will be sent.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[lastOpenedTime](#lastOpenedTime)|Shows the latest date and time when email was opened.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[linksClickedCount](#linksClickedCount)|Shows the number of times a link in an email has been clicked.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[openCount](#openCount)|Shows the number of times an email has been opened.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[replyCount](#replyCount)|Shows the number of replies received for an email.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[emailTrackingId](#emailTrackingId)|Email Tracking Id.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[followEmailUserPreference](#followEmailUserPreference)|Select whether the email allows following recipient activities sent from Microsoft Dynamics 365.This is user preference state which can be overridden by system evaluated state.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[isEmailFollowed](#isEmailFollowed)|For internal use only. Shows whether this email is followed. This is evaluated state which overrides user selection of follow email.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[emailReminderExpiryTime](#emailReminderExpiryTime)|Shows the date and time when an email reminder expires.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[emailReminderType](#emailReminderType)|Shows the type of the email reminder.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[emailReminderType_display](#emailReminderType_display)||<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[emailReminderStatus](#emailReminderStatus)|Shows the status of the email reminder.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[emailReminderStatus_display](#emailReminderStatus_display)||<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[emailReminderText](#emailReminderText)|For internal use only.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[templateId](#templateId)|For internal use only. ID for template used in email.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[reminderActionCardId](#reminderActionCardId)|Reminder Action Card Id.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|
|[isEmailReminderSet](#isEmailReminderSet)|For internal use only. Shows whether this email Reminder is Set.|<a href="Email.md" target="_blank">applicationCommon/Email</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier for the user that owns the record.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier for the user that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#activityTypeCode name="activityTypeCode">activityTypeCode</a>

Type of activity.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Type</td></tr><tr><td>description</td><td>Type of activity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>activitytypecode</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fax</td></tr><tr><td>en</td><td>Phone Call</td></tr><tr><td>en</td><td>Email</td></tr><tr><td>en</td><td>Letter</td></tr><tr><td>en</td><td>Appointment</td></tr><tr><td>en</td><td>Task</td></tr><tr><td>en</td><td>Recurring Appointment</td></tr><tr><td>en</td><td>Quick Campaign</td></tr><tr><td>en</td><td>Campaign Activity</td></tr><tr><td>en</td><td>Campaign Response</td></tr><tr><td>en</td><td>Case Resolution</td></tr><tr><td>en</td><td>Service Activity</td></tr><tr><td>en</td><td>Opportunity Close</td></tr><tr><td>en</td><td>Order Close</td></tr><tr><td>en</td><td>Quote Close</td></tr><tr><td>en</td><td>Alert Subscription</td></tr><tr><td>en</td><td>Invite Redemption</td></tr><tr><td>en</td><td>Portal Comment</td></tr></table></td></tr></table>

### <a href=#activityId name="activityId">activityId</a>

Unique identifier of the activity.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity</td></tr><tr><td>description</td><td>Unique identifier of the activity.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>activityid</td></tr></table>

### <a href=#isBilled name="isBilled">isBilled</a>

Information regarding whether the fax activity was billed as part of resolving a case.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Billed</td></tr><tr><td>description</td><td>Information regarding whether the fax activity was billed as part of resolving a case.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isbilled</td></tr></table>

### <a href=#isRegularActivity name="isRegularActivity">isRegularActivity</a>

Information regarding whether the activity is a regular activity type or event type.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Regular Activity</td></tr><tr><td>description</td><td>Information regarding whether the activity is a regular activity type or event type.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isregularactivity</td></tr></table>

### <a href=#isWorkflowCreated name="isWorkflowCreated">isWorkflowCreated</a>

Information regarding whether the activity was created from a workflow rule.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Workflow Created</td></tr><tr><td>description</td><td>Information regarding whether the activity was created from a workflow rule.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isworkflowcreated</td></tr></table>

### <a href=#priorityCode name="priorityCode">priorityCode</a>

Priority of the activity.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Priority</td></tr><tr><td>description</td><td>Priority of the activity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>prioritycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Low</td><td>0</td></tr><tr><td>en</td><td>Normal</td><td>1</td></tr><tr><td>en</td><td>High</td><td>2</td></tr></table></td></tr></table>

### <a href=#priorityCode_display name="priorityCode_display">priorityCode_display</a>

First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#regardingObjectTypeCode name="regardingObjectTypeCode">regardingObjectTypeCode</a>

The name of the entity linked by regardingObjectId  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regarding Type</td></tr><tr><td>description</td><td>The name of the entity linked by regardingObjectId</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>regardingobjecttypecode</td></tr></table>

### <a href=#regardingObjectId name="regardingObjectId">regardingObjectId</a>

Unique identifier of the object with which the activity is associated.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regarding</td></tr><tr><td>description</td><td>Unique identifier of the object with which the activity is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>regardingobjectid</td></tr></table>

### <a href=#scheduledEnd name="scheduledEnd">scheduledEnd</a>

Scheduled end time of the activity.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Due Date</td></tr><tr><td>description</td><td>Scheduled end time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduledend</td></tr></table>

### <a href=#scheduledStart name="scheduledStart">scheduledStart</a>

Scheduled start time of the activity.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date</td></tr><tr><td>description</td><td>Scheduled start time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduledstart</td></tr></table>

### <a href=#sortDate name="sortDate">sortDate</a>

Shows the date and time by which the activities are sorted.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sort Date</td></tr><tr><td>description</td><td>Shows the date and time by which the activities are sorted.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sortdate</td></tr></table>

### <a href=#subject name="subject">subject</a>

Subject associated with the activity.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject</td></tr><tr><td>description</td><td>Subject associated with the activity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>subject</td></tr></table>

### <a href=#scheduledDurationMinutes name="scheduledDurationMinutes">scheduledDurationMinutes</a>

Scheduled duration of the activity, specified in minutes.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scheduled Duration</td></tr><tr><td>description</td><td>Scheduled duration of the activity, specified in minutes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduleddurationminutes</td></tr></table>

### <a href=#actualDurationMinutes name="actualDurationMinutes">actualDurationMinutes</a>

Actual duration of the activity in minutes.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Duration</td></tr><tr><td>description</td><td>Actual duration of the activity in minutes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualdurationminutes</td></tr></table>

### <a href=#actualEnd name="actualEnd">actualEnd</a>

Actual end time of the activity.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual End</td></tr><tr><td>description</td><td>Actual end time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualend</td></tr></table>

### <a href=#actualStart name="actualStart">actualStart</a>

Actual start time of the activity.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Start</td></tr><tr><td>description</td><td>Actual start time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualstart</td></tr></table>

### <a href=#category name="category">category</a>

Type a category to identify the activity type, such as lead outreach, customer follow-up, or service alert, to tie the eactivity to a business group or function.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Category</td></tr><tr><td>description</td><td>Type a category to identify the activity type, such as lead outreach, customer follow-up, or service alert, to tie the eactivity to a business group or function.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>category</td></tr></table>

### <a href=#subcategory name="subcategory">subcategory</a>

Type a subcategory to identify the activity type and relate the activity to a specific product, sales region, business group, or other function.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sub-Category</td></tr><tr><td>description</td><td>Type a subcategory to identify the activity type and relate the activity to a specific product, sales region, business group, or other function.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>subcategory</td></tr></table>

### <a href=#activityAdditionalParams name="activityAdditionalParams">activityAdditionalParams</a>

Additional information provided by the external application as JSON. For internal use only.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Additional Parameters</td></tr><tr><td>description</td><td>Additional information provided by the external application as JSON. For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>8192</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>activityadditionalparams</td></tr></table>

### <a href=#to name="to">to</a>

Enter the account, contact, lead, or user recipients of the phone call.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Call To</td></tr><tr><td>description</td><td>Enter the account, contact, lead, or user recipients of the phone call.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>to</td></tr></table>

### <a href=#from name="from">from</a>

Enter the account, contact, lead, or user who made the phone call.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Call From</td></tr><tr><td>description</td><td>Enter the account, contact, lead, or user who made the phone call.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>from</td></tr></table>

### <a href=#BCC name="BCC">BCC</a>

Enter the recipients that are included on the activity distribution, but are not displayed to other recipients.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bcc</td></tr><tr><td>description</td><td>Enter the recipients that are included on the activity distribution, but are not displayed to other recipients.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>bcc</td></tr></table>

### <a href=#CC name="CC">CC</a>

Enter the recipients that should be copied on the activity.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cc</td></tr><tr><td>description</td><td>Enter the recipients that should be copied on the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>cc</td></tr></table>

### <a href=#sentOn name="sentOn">sentOn</a>

Date and time when the activity was sent.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Sent</td></tr><tr><td>description</td><td>Date and time when the activity was sent.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>senton</td></tr></table>

### <a href=#senderMailboxId name="senderMailboxId">senderMailboxId</a>

Unique identifier of the mailbox associated with the sender of the email message.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sender's Mailbox</td></tr><tr><td>description</td><td>Unique identifier of the mailbox associated with the sender of the email message.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sendermailboxid</td></tr></table>

### <a href=#deliveryPriorityCode name="deliveryPriorityCode">deliveryPriorityCode</a>

Priority of delivery of the activity to the email server.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery Priority</td></tr><tr><td>description</td><td>Priority of delivery of the activity to the email server.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>deliveryprioritycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Low</td><td>0</td></tr><tr><td>en</td><td>Normal</td><td>1</td></tr><tr><td>en</td><td>High</td><td>2</td></tr></table></td></tr></table>

### <a href=#deliveryPriorityCode_display name="deliveryPriorityCode_display">deliveryPriorityCode_display</a>

First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#directionCode name="directionCode">directionCode</a>

Select the direction of the activity as incoming or outbound.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Direction</td></tr><tr><td>description</td><td>Select the direction of the activity as incoming or outbound.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>directioncode</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the email's status.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the email's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Draft</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Completed</td><td>2</td><td>1</td></tr><tr><td>en</td><td>Sent</td><td>3</td><td>1</td></tr><tr><td>en</td><td>Received</td><td>4</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>5</td><td>2</td></tr><tr><td>en</td><td>Pending Send</td><td>6</td><td>1</td></tr><tr><td>en</td><td>Sending</td><td>7</td><td>1</td></tr><tr><td>en</td><td>Failed</td><td>8</td><td>0</td></tr><tr><td>en</td><td>Draft</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Completed</td><td>2</td><td>1</td></tr><tr><td>en</td><td>Sent</td><td>3</td><td>1</td></tr><tr><td>en</td><td>Received</td><td>4</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>5</td><td>2</td></tr><tr><td>en</td><td>Pending Send</td><td>6</td><td>1</td></tr><tr><td>en</td><td>Sending</td><td>7</td><td>1</td></tr><tr><td>en</td><td>Failed</td><td>8</td><td>0</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#submittedBy name="submittedBy">submittedBy</a>

Shows the Microsoft Office Outlook account for the user who submitted the email to Microsoft Dynamics 365.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Submitted By</td></tr><tr><td>description</td><td>Shows the Microsoft Office Outlook account for the user who submitted the email to Microsoft Dynamics 365.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>submittedby</td></tr></table>

### <a href=#description name="description">description</a>

Type the greeting and message text of the email.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type the greeting and message text of the email.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#mimeType name="mimeType">mimeType</a>

MIME type of the email message data.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mime Type</td></tr><tr><td>description</td><td>MIME type of the email message data.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>256</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mimetype</td></tr></table>

### <a href=#readReceiptRequested name="readReceiptRequested">readReceiptRequested</a>

Indicates that a read receipt is requested.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Read Receipt Requested</td></tr><tr><td>description</td><td>Indicates that a read receipt is requested.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>readreceiptrequested</td></tr></table>

### <a href=#trackingToken name="trackingToken">trackingToken</a>

Shows the tracking token assigned to the email to make sure responses are automatically tracked in Microsoft Dynamics 365.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tracking Token</td></tr><tr><td>description</td><td>Shows the tracking token assigned to the email to make sure responses are automatically tracked in Microsoft Dynamics 365.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>trackingtoken</td></tr></table>

### <a href=#sender name="sender">sender</a>

Sender of the email.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>From</td></tr><tr><td>description</td><td>Sender of the email.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sender</td></tr></table>

### <a href=#toRecipients name="toRecipients">toRecipients</a>

Shows the email addresses corresponding to the recipients.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>To Recipients</td></tr><tr><td>description</td><td>Shows the email addresses corresponding to the recipients.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>torecipients</td></tr></table>

### <a href=#deliveryReceiptRequested name="deliveryReceiptRequested">deliveryReceiptRequested</a>

Select whether the sender should receive confirmation that the email was delivered.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery Receipt Requested</td></tr><tr><td>description</td><td>Select whether the sender should receive confirmation that the email was delivered.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>deliveryreceiptrequested</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the email is open, completed, or canceled. Completed and canceled email is read-only and can't be edited.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Status</td></tr><tr><td>description</td><td>Shows whether the email is open, completed, or canceled. Completed and canceled email is read-only and can't be edited.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Open</td><td>0</td></tr><tr><td>en</td><td>Completed</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>2</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#messageId name="messageId">messageId</a>

Unique identifier of the email message. Used only for email that is received.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Message ID</td></tr><tr><td>description</td><td>Unique identifier of the email message. Used only for email that is received.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>320</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>messageid</td></tr></table>

### <a href=#deliveryAttempts name="deliveryAttempts">deliveryAttempts</a>

Shows the count of the number of attempts made to send the email. The count is used as an indicator of email routing issues.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>No. of Delivery Attempts</td></tr><tr><td>description</td><td>Shows the count of the number of attempts made to send the email. The count is used as an indicator of email routing issues.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>deliveryattempts</td></tr></table>

### <a href=#compressed name="compressed">compressed</a>

Indicates if the body is compressed.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Compression</td></tr><tr><td>description</td><td>Indicates if the body is compressed.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>compressed</td></tr></table>

### <a href=#notifications name="notifications">notifications</a>

Select the notification code to identify issues with the email recipients or attachments, such as blocked attachments.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Notifications</td></tr><tr><td>description</td><td>Select the notification code to identify issues with the email recipients or attachments, such as blocked attachments.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>notifications</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>None</td><td>0</td></tr><tr><td>en</td><td>The message was saved as a Microsoft Dynamics 365 email record, but not all the attachments could be saved with it. An attachment cannot be saved if it is blocked or if its file type is invalid.</td><td>1</td></tr><tr><td>en</td><td>Truncated body.</td><td>2</td></tr></table></td></tr></table>

### <a href=#notifications_display name="notifications_display">notifications_display</a>

First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#emailSenderObjectTypeCode name="emailSenderObjectTypeCode">emailSenderObjectTypeCode</a>

The name of the entity linked by emailSender  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>emailSender Type</td></tr><tr><td>description</td><td>The name of the entity linked by emailSender</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>emailsenderobjecttypecode</td></tr></table>

### <a href=#emailSender name="emailSender">emailSender</a>

Shows the sender of the email.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sender</td></tr><tr><td>description</td><td>Shows the sender of the email.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailsender</td></tr></table>

### <a href=#sendersAccountObjectTypeCode name="sendersAccountObjectTypeCode">sendersAccountObjectTypeCode</a>

The name of the entity linked by sendersAccount  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>sendersAccount Type</td></tr><tr><td>description</td><td>The name of the entity linked by sendersAccount</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>sendersaccountobjecttypecode</td></tr></table>

### <a href=#sendersAccount name="sendersAccount">sendersAccount</a>

Shows the parent account of the sender of the email.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Senders Account</td></tr><tr><td>description</td><td>Shows the parent account of the sender of the email.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sendersaccount</td></tr></table>

### <a href=#attachmentCount name="attachmentCount">attachmentCount</a>

Shows the umber of attachments of the email message.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Attachment Count</td></tr><tr><td>description</td><td>Shows the umber of attachments of the email message.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>attachmentcount</td></tr></table>

### <a href=#parentActivityId name="parentActivityId">parentActivityId</a>

Select the activity that the email is associated with.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent Activity Id</td></tr><tr><td>description</td><td>Select the activity that the email is associated with.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>parentactivityid</td></tr></table>

### <a href=#inReplyTo name="inReplyTo">inReplyTo</a>

Type the ID of the email message that this email activity is a response to.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>In Reply To Message</td></tr><tr><td>description</td><td>Type the ID of the email message that this email activity is a response to.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>320</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>inreplyto</td></tr></table>

### <a href=#baseConversationIndexHash name="baseConversationIndexHash">baseConversationIndexHash</a>

Hash of base of conversation index.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Conversation Index (Hash)</td></tr><tr><td>description</td><td>Hash of base of conversation index.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>baseconversationindexhash</td></tr></table>

### <a href=#conversationIndex name="conversationIndex">conversationIndex</a>

Identifier for all the email responses for this conversation.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Conversation Index</td></tr><tr><td>description</td><td>Identifier for all the email responses for this conversation.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2048</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>conversationindex</td></tr></table>

### <a href=#correlationMethod name="correlationMethod">correlationMethod</a>

Shows how an email is matched to an existing email in Microsoft Dynamics 365. For system use only.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Correlation Method</td></tr><tr><td>description</td><td>Shows how an email is matched to an existing email in Microsoft Dynamics 365. For system use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>correlationmethod</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>None</td><td>0</td></tr><tr><td>en</td><td>Skipped</td><td>1</td></tr><tr><td>en</td><td>XHeader</td><td>2</td></tr><tr><td>en</td><td>InReplyTo</td><td>3</td></tr><tr><td>en</td><td>TrackingToken</td><td>4</td></tr><tr><td>en</td><td>ConversationIndex</td><td>5</td></tr><tr><td>en</td><td>SmartMatching</td><td>6</td></tr><tr><td>en</td><td>CustomCorrelation</td><td>7</td></tr></table></td></tr></table>

### <a href=#correlationMethod_display name="correlationMethod_display">correlationMethod_display</a>

First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#postponeEmailProcessingUntil name="postponeEmailProcessingUntil">postponeEmailProcessingUntil</a>

For internal use only.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delay email processing until</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postponeemailprocessinguntil</td></tr></table>

### <a href=#processId name="processId">processId</a>

Shows the ID of the process.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process</td></tr><tr><td>description</td><td>Shows the ID of the process.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Shows the ID of the stage.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Stage</td></tr><tr><td>description</td><td>Shows the ID of the stage.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#isUnsafe name="isUnsafe">isUnsafe</a>

For internal use only.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>IsUnsafe</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isunsafe</td></tr></table>

### <a href=#SLAId name="SLAId">SLAId</a>

Choose the service level agreement (SLA) that you want to apply to the email record.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SLA</td></tr><tr><td>description</td><td>Choose the service level agreement (SLA) that you want to apply to the email record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slaid</td></tr></table>

### <a href=#SLAInvokedId name="SLAInvokedId">SLAInvokedId</a>

Last SLA that was applied to this email. This field is for internal use only.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last SLA applied</td></tr><tr><td>description</td><td>Last SLA that was applied to this email. This field is for internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slainvokedid</td></tr></table>

### <a href=#onHoldTime name="onHoldTime">onHoldTime</a>

Shows how long, in minutes, that the record was on hold.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>On Hold Time (Minutes)</td></tr><tr><td>description</td><td>Shows how long, in minutes, that the record was on hold.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>onholdtime</td></tr></table>

### <a href=#lastOnHoldTime name="lastOnHoldTime">lastOnHoldTime</a>

Contains the date and time stamp of the last on hold time.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last On Hold Time</td></tr><tr><td>description</td><td>Contains the date and time stamp of the last on hold time.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastonholdtime</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

For internal use only.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#attachmentOpenCount name="attachmentOpenCount">attachmentOpenCount</a>

Shows the number of times an email attachment has been viewed.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Attachment Open Count</td></tr><tr><td>description</td><td>Shows the number of times an email attachment has been viewed.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>attachmentopencount</td></tr></table>

### <a href=#conversationTrackingId name="conversationTrackingId">conversationTrackingId</a>

Conversation Tracking Id.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Conversation Tracking Id</td></tr><tr><td>description</td><td>Conversation Tracking Id.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>conversationtrackingid</td></tr></table>

### <a href=#delayedEmailSendTime name="delayedEmailSendTime">delayedEmailSendTime</a>

Enter the expected date and time when email will be sent.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Send Later</td></tr><tr><td>description</td><td>Enter the expected date and time when email will be sent.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>delayedemailsendtime</td></tr></table>

### <a href=#lastOpenedTime name="lastOpenedTime">lastOpenedTime</a>

Shows the latest date and time when email was opened.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Opened Time</td></tr><tr><td>description</td><td>Shows the latest date and time when email was opened.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastopenedtime</td></tr></table>

### <a href=#linksClickedCount name="linksClickedCount">linksClickedCount</a>

Shows the number of times a link in an email has been clicked.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Links Clicked Count</td></tr><tr><td>description</td><td>Shows the number of times a link in an email has been clicked.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>linksclickedcount</td></tr></table>

### <a href=#openCount name="openCount">openCount</a>

Shows the number of times an email has been opened.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Open Count</td></tr><tr><td>description</td><td>Shows the number of times an email has been opened.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>opencount</td></tr></table>

### <a href=#replyCount name="replyCount">replyCount</a>

Shows the number of replies received for an email.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reply Count</td></tr><tr><td>description</td><td>Shows the number of replies received for an email.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>replycount</td></tr></table>

### <a href=#emailTrackingId name="emailTrackingId">emailTrackingId</a>

Email Tracking Id.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Tracking Id</td></tr><tr><td>description</td><td>Email Tracking Id.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailtrackingid</td></tr></table>

### <a href=#followEmailUserPreference name="followEmailUserPreference">followEmailUserPreference</a>

Select whether the email allows following recipient activities sent from Microsoft Dynamics 365.This is user preference state which can be overridden by system evaluated state.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Following</td></tr><tr><td>description</td><td>Select whether the email allows following recipient activities sent from Microsoft Dynamics 365.This is user preference state which can be overridden by system evaluated state.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>followemailuserpreference</td></tr></table>

### <a href=#isEmailFollowed name="isEmailFollowed">isEmailFollowed</a>

For internal use only. Shows whether this email is followed. This is evaluated state which overrides user selection of follow email.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Followed</td></tr><tr><td>description</td><td>For internal use only. Shows whether this email is followed. This is evaluated state which overrides user selection of follow email.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isemailfollowed</td></tr></table>

### <a href=#emailReminderExpiryTime name="emailReminderExpiryTime">emailReminderExpiryTime</a>

Shows the date and time when an email reminder expires.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Reminder Expiry Time</td></tr><tr><td>description</td><td>Shows the date and time when an email reminder expires.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailreminderexpirytime</td></tr></table>

### <a href=#emailReminderType name="emailReminderType">emailReminderType</a>

Shows the type of the email reminder.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Reminder Type</td></tr><tr><td>description</td><td>Shows the type of the email reminder.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailremindertype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>If I do not receive a reply by</td><td>0</td></tr><tr><td>en</td><td>If the email is not opened by</td><td>1</td></tr><tr><td>en</td><td>Remind me anyways at</td><td>2</td></tr></table></td></tr></table>

### <a href=#emailReminderType_display name="emailReminderType_display">emailReminderType_display</a>

First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#emailReminderStatus name="emailReminderStatus">emailReminderStatus</a>

Shows the status of the email reminder.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Reminder Status</td></tr><tr><td>description</td><td>Shows the status of the email reminder.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailreminderstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>NotSet</td><td>0</td></tr><tr><td>en</td><td>ReminderSet</td><td>1</td></tr><tr><td>en</td><td>ReminderExpired</td><td>2</td></tr><tr><td>en</td><td>ReminderInvalid</td><td>3</td></tr></table></td></tr></table>

### <a href=#emailReminderStatus_display name="emailReminderStatus_display">emailReminderStatus_display</a>

First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#emailReminderText name="emailReminderText">emailReminderText</a>

For internal use only.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Reminder Text</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailremindertext</td></tr></table>

### <a href=#templateId name="templateId">templateId</a>

For internal use only. ID for template used in email.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ID for template used.</td></tr><tr><td>description</td><td>For internal use only. ID for template used in email.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>templateid</td></tr></table>

### <a href=#reminderActionCardId name="reminderActionCardId">reminderActionCardId</a>

Reminder Action Card Id.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reminder Action Card Id.</td></tr><tr><td>description</td><td>Reminder Action Card Id.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>reminderactioncardid</td></tr></table>

### <a href=#isEmailReminderSet name="isEmailReminderSet">isEmailReminderSet</a>

For internal use only. Shows whether this email Reminder is Set.  
First included in: applicationCommon/Email (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reminder Set</td></tr><tr><td>description</td><td>For internal use only. Shows whether this email Reminder is Set.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isemailreminderset</td></tr></table>
