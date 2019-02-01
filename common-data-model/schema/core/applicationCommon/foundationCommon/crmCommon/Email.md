---
title: Email_
description: some description
ms.service:: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 2/1/2019
ms.author: tpalmer
---
# Email

## Properties

Display Name: Email

Description: Activity that is delivered using email protocols.

Latest Version: 0.8.1

Entity Definition on GitHub: [https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/Email.cdm.json](https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/Email.cdm.json)

## Instances

## Attributes - Summary

<table><tr><th>Name</th><th>Description</th><th>First Included in Instance</th></tr><tr><td>createdOn</td><td>Date and time when the record was created.</td><td> </td></tr><tr><td>createdBy</td><td>Shows who created the record.</td><td> </td></tr><tr><td>modifiedOn</td><td>Date and time when the record was modified.</td><td> </td></tr><tr><td>modifiedBy</td><td>Shows who last updated the record.</td><td> </td></tr><tr><td>createdOnBehalfBy</td><td>Shows who created the record on behalf of another user.</td><td> </td></tr><tr><td>modifiedOnBehalfBy</td><td>Shows who last updated the record on behalf of another user.</td><td> </td></tr><tr><td>overriddenCreatedOn</td><td>Date and time that the record was migrated.</td><td> </td></tr><tr><td>importSequenceNumber</td><td>Unique identifier of the data import or data migration that created this record.</td><td> </td></tr><tr><td>ownerIdType</td><td>The type of owner, either User or Team.</td><td> </td></tr><tr><td>ownerId</td><td>Owner Id</td><td> </td></tr><tr><td>owningBusinessUnit</td><td>Unique identifier for the business unit that owns the record</td><td> </td></tr><tr><td>owningUser</td><td>Unique identifier of the user that owns the activity.</td><td> </td></tr><tr><td>owningTeam</td><td>Unique identifier for the team that owns the record.</td><td> </td></tr><tr><td>timeZoneRuleVersionNumber</td><td>For internal use only.</td><td> </td></tr><tr><td>UTCConversionTimeZoneCode</td><td>Time zone code that was in use when the record was created.</td><td> </td></tr><tr><td>versionNumber</td><td>Version Number</td><td> </td></tr><tr><td>activityTypeCode</td><td>Type of activity.</td><td> </td></tr><tr><td>activityId</td><td>Unique identifier of the activity.</td><td> </td></tr><tr><td>isBilled</td><td>Information regarding whether the fax activity was billed as part of resolving a case.</td><td> </td></tr><tr><td>isRegularActivity</td><td>Information regarding whether the activity is a regular activity type or event type.</td><td> </td></tr><tr><td>isWorkflowCreated</td><td>Information regarding whether the activity was created from a workflow rule.</td><td> </td></tr><tr><td>priorityCode</td><td>Priority of the activity.</td><td> </td></tr><tr><td>priorityCode_display</td><td>undefined</td><td> </td></tr><tr><td>regardingObjectTypeCode</td><td>The name of the entity linked by regardingObjectId</td><td> </td></tr><tr><td>regardingObjectId</td><td>Unique identifier of the object with which the activity is associated.</td><td> </td></tr><tr><td>scheduledEnd</td><td>Scheduled end time of the activity.</td><td> </td></tr><tr><td>scheduledStart</td><td>Scheduled start time of the activity.</td><td> </td></tr><tr><td>sortDate</td><td>Shows the date and time by which the activities are sorted.</td><td> </td></tr><tr><td>subject</td><td>Subject associated with the activity.</td><td> </td></tr><tr><td>scheduledDurationMinutes</td><td>Scheduled duration of the activity, specified in minutes.</td><td> </td></tr><tr><td>actualDurationMinutes</td><td>Actual duration of the activity in minutes.</td><td> </td></tr><tr><td>actualEnd</td><td>Actual end time of the activity.</td><td> </td></tr><tr><td>actualStart</td><td>Actual start time of the activity.</td><td> </td></tr><tr><td>category</td><td>Type a category to identify the activity type, such as lead outreach, customer follow-up, or service alert, to tie the eactivity to a business group or function.</td><td> </td></tr><tr><td>subcategory</td><td>Type a subcategory to identify the activity type and relate the activity to a specific product, sales region, business group, or other function.</td><td> </td></tr><tr><td>activityAdditionalParams</td><td>Additional information provided by the external application as JSON. For internal use only.</td><td> </td></tr><tr><td>to</td><td>Enter the account, contact, lead, or user recipients of the phone call.</td><td> </td></tr><tr><td>from</td><td>Enter the account, contact, lead, or user who made the phone call.</td><td> </td></tr><tr><td>BCC</td><td>Enter the recipients that are included on the activity distribution, but are not displayed to other recipients.</td><td> </td></tr><tr><td>CC</td><td>Enter the recipients that should be copied on the activity.</td><td> </td></tr><tr><td>sentOn</td><td>Date and time when the activity was sent.</td><td> </td></tr><tr><td>senderMailboxId</td><td>Unique identifier of the mailbox associated with the sender of the email message.</td><td> </td></tr><tr><td>deliveryPriorityCode</td><td>Priority of delivery of the activity to the email server.</td><td> </td></tr><tr><td>deliveryPriorityCode_display</td><td>undefined</td><td> </td></tr><tr><td>directionCode</td><td>Select the direction of the activity as incoming or outbound.</td><td> </td></tr><tr><td>statusCode</td><td>Select the email's status.</td><td> </td></tr><tr><td>statusCode_display</td><td>undefined</td><td> </td></tr><tr><td>submittedBy</td><td>Shows the Microsoft Office Outlook account for the user who submitted the email to Microsoft Dynamics 365.</td><td> </td></tr><tr><td>description</td><td>Type the greeting and message text of the email.</td><td> </td></tr><tr><td>mimeType</td><td>MIME type of the email message data.</td><td> </td></tr><tr><td>readReceiptRequested</td><td>Indicates that a read receipt is requested.</td><td> </td></tr><tr><td>trackingToken</td><td>Shows the tracking token assigned to the email to make sure responses are automatically tracked in Microsoft Dynamics 365.</td><td> </td></tr><tr><td>sender</td><td>Sender of the email.</td><td> </td></tr><tr><td>toRecipients</td><td>Shows the email addresses corresponding to the recipients.</td><td> </td></tr><tr><td>deliveryReceiptRequested</td><td>Select whether the sender should receive confirmation that the email was delivered.</td><td> </td></tr><tr><td>stateCode</td><td>Shows whether the email is open, completed, or canceled. Completed and canceled email is read-only and can't be edited.</td><td> </td></tr><tr><td>stateCode_display</td><td>undefined</td><td> </td></tr><tr><td>messageId</td><td>Unique identifier of the email message. Used only for email that is received.</td><td> </td></tr><tr><td>deliveryAttempts</td><td>Shows the count of the number of attempts made to send the email. The count is used as an indicator of email routing issues.</td><td> </td></tr><tr><td>compressed</td><td>Indicates if the body is compressed.</td><td> </td></tr><tr><td>notifications</td><td>Select the notification code to identify issues with the email recipients or attachments, such as blocked attachments.</td><td> </td></tr><tr><td>notifications_display</td><td>undefined</td><td> </td></tr><tr><td>transactionCurrencyId</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td><td> </td></tr><tr><td>exchangeRate</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td><td> </td></tr><tr><td>emailSenderObjectTypeCode</td><td>The name of the entity linked by emailSender</td><td> </td></tr><tr><td>emailSender</td><td>Shows the sender of the email.</td><td> </td></tr><tr><td>sendersAccountObjectTypeCode</td><td>The name of the entity linked by sendersAccount</td><td> </td></tr><tr><td>sendersAccount</td><td>Shows the parent account of the sender of the email.</td><td> </td></tr><tr><td>attachmentCount</td><td>Shows the umber of attachments of the email message.</td><td> </td></tr><tr><td>parentActivityId</td><td>Select the activity that the email is associated with.</td><td> </td></tr><tr><td>inReplyTo</td><td>Type the ID of the email message that this email activity is a response to.</td><td> </td></tr><tr><td>baseConversationIndexHash</td><td>Hash of base of conversation index.</td><td> </td></tr><tr><td>conversationIndex</td><td>Identifier for all the email responses for this conversation.</td><td> </td></tr><tr><td>correlationMethod</td><td>Shows how an email is matched to an existing email in Microsoft Dynamics 365. For system use only.</td><td> </td></tr><tr><td>correlationMethod_display</td><td>undefined</td><td> </td></tr><tr><td>postponeEmailProcessingUntil</td><td>For internal use only.</td><td> </td></tr><tr><td>processId</td><td>Shows the ID of the process.</td><td> </td></tr><tr><td>stageId</td><td>Shows the ID of the stage.</td><td> </td></tr><tr><td>isUnsafe</td><td>For internal use only.</td><td> </td></tr><tr><td>SLAId</td><td>Choose the service level agreement (SLA) that you want to apply to the email record.</td><td> </td></tr><tr><td>SLAInvokedId</td><td>Last SLA that was applied to this email. This field is for internal use only.</td><td> </td></tr><tr><td>onHoldTime</td><td>Shows how long, in minutes, that the record was on hold.</td><td> </td></tr><tr><td>lastOnHoldTime</td><td>Contains the date and time stamp of the last on hold time.</td><td> </td></tr><tr><td>traversedPath</td><td>For internal use only.</td><td> </td></tr><tr><td>attachmentOpenCount</td><td>Shows the number of times an email attachment has been viewed.</td><td> </td></tr><tr><td>conversationTrackingId</td><td>Conversation Tracking Id.</td><td> </td></tr><tr><td>delayedEmailSendTime</td><td>Enter the expected date and time when email will be sent.</td><td> </td></tr><tr><td>lastOpenedTime</td><td>Shows the latest date and time when email was opened.</td><td> </td></tr><tr><td>linksClickedCount</td><td>Shows the number of times a link in an email has been clicked.</td><td> </td></tr><tr><td>openCount</td><td>Shows the number of times an email has been opened.</td><td> </td></tr><tr><td>replyCount</td><td>Shows the number of replies received for an email.</td><td> </td></tr><tr><td>emailTrackingId</td><td>Email Tracking Id.</td><td> </td></tr><tr><td>followEmailUserPreference</td><td>Select whether the email allows following recipient activities sent from Microsoft Dynamics 365.This is user preference state which can be overridden by system evaluated state.</td><td> </td></tr><tr><td>isEmailFollowed</td><td>For internal use only. Shows whether this email is followed. This is evaluated state which overrides user selection of follow email.</td><td> </td></tr><tr><td>emailReminderExpiryTime</td><td>Shows the date and time when an email reminder expires.</td><td> </td></tr><tr><td>emailReminderType</td><td>Shows the type of the email reminder.</td><td> </td></tr><tr><td>emailReminderType_display</td><td>undefined</td><td> </td></tr><tr><td>emailReminderStatus</td><td>Shows the status of the email reminder.</td><td> </td></tr><tr><td>emailReminderStatus_display</td><td>undefined</td><td> </td></tr><tr><td>emailReminderText</td><td>For internal use only.</td><td> </td></tr><tr><td>templateId</td><td>For internal use only. ID for template used in email.</td><td> </td></tr><tr><td>reminderActionCardId</td><td>Reminder Action Card Id.</td><td> </td></tr><tr><td>isEmailReminderSet</td><td>For internal use only. Shows whether this email Reminder is Set.</td><td> </td></tr><tr><td>serviceId</td><td>Unique identifier for the associated service.</td><td> </td></tr></table>

## Attribute - Details

### createdOn

Date and time when the record was created.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.date


##### means.measurement.date


##### is.dataFormat.time


##### means.measurement.time


##### means.measurement.date.creation


##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created On</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was created.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>createdon</td><td>string</td><td>undefined</td></tr></table>


### createdBy

Shows who created the record.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### means.userId

contains a userId


##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created By</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who created the record.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>createdby</td><td>string</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "userId"...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "userId",
  "name": "createdBy",
  "appliedTraits": [
    "is.CDS.standard",
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Created By"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Shows who created the record."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Created By",
  "description": "Shows who created the record.",
  "isNullable": true,
  "sourceName": "createdby"
}
```

### modifiedOn

Date and time when the record was modified.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.date


##### means.measurement.date


##### is.dataFormat.time


##### means.measurement.time


##### means.measurement.date.modify


##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified On</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was modified.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>modifiedon</td><td>string</td><td>undefined</td></tr></table>


### modifiedBy

Shows who last updated the record.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### means.userId

contains a userId


##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified By</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who last updated the record.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>modifiedby</td><td>string</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "userId"...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "userId",
  "name": "modifiedBy",
  "appliedTraits": [
    "is.CDS.standard",
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Modified By"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Shows who last updated the record."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Modified By",
  "description": "Shows who last updated the record.",
  "isNullable": true,
  "sourceName": "modifiedby"
}
```

### createdOnBehalfBy

Shows who created the record on behalf of another user.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### means.userId

contains a userId


##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created By (Delegate)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who created the record on behalf of another user.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>createdonbehalfby</td><td>string</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "userId"...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "userId",
  "name": "createdOnBehalfBy",
  "appliedTraits": [
    "is.CDS.standard",
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Created By (Delegate)"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Shows who created the record on behalf of another user."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Created By (Delegate)",
  "description": "Shows who created the record on behalf of another user.",
  "isNullable": true,
  "sourceName": "createdonbehalfby"
}
```

### modifiedOnBehalfBy

Shows who last updated the record on behalf of another user.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### means.userId

contains a userId


##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified By (Delegate)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who last updated the record on behalf of another user.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>modifiedonbehalfby</td><td>string</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "userId"...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "userId",
  "name": "modifiedOnBehalfBy",
  "appliedTraits": [
    "is.CDS.standard",
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Modified By (Delegate)"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Shows who last updated the record on behalf of another user."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Modified By (Delegate)",
  "description": "Shows who last updated the record on behalf of another user.",
  "isNullable": true,
  "sourceName": "modifiedonbehalfby"
}
```

### overriddenCreatedOn

Date and time that the record was migrated.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.date


##### means.measurement.date


##### is.dataFormat.time


##### means.measurement.time


##### means.measurement.date.creation


##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Record Created On</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time that the record was migrated.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>overriddencreatedon</td><td>string</td><td>undefined</td></tr></table>


### importSequenceNumber

Unique identifier of the data import or data migration that created this record.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Import Sequence Number</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the data import or data migration that created this record.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>importsequencenumber</td><td>string</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-2147483648</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### ownerIdType

The type of owner, either User or Team.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.entityName


##### is.readOnly


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owner Type</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The type of owner, either User or Team.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>owneridtype</td><td>string</td><td>undefined</td></tr></table>


##### is.linkedEntity.name

Marks an attribute that contains the entity name or 'class' for the situation where one entity links to (uses as an attribute) a set of possible entities.


##### is.CDS.owner

contains a User or Team ID


### ownerId

Owner Id

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>ownerid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owner</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owner Id</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>ownerid</td><td>string</td><td>undefined</td></tr></table>


##### is.linkedEntity.identifier

Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.


##### is.CDS.owner

contains a User or Team ID


### owningBusinessUnit

Unique identifier for the business unit that owns the record

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owning Business Unit</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for the business unit that owns the record</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>owningbusinessunit</td><td>string</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "owningBusinessUnit",
  "appliedTraits": [
    "is.CDS.standard",
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Owning Business Unit"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Unique identifier for the business unit that owns the record"
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Owning Business Unit",
  "description": "Unique identifier for the business unit that owns the record",
  "isNullable": true,
  "sourceName": "owningbusinessunit"
}
```

### owningUser

Unique identifier of the user that owns the activity.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### means.userId

contains a userId


##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owning User</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the user that owns the activity.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>owninguser</td><td>string</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "userId"...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "userId",
  "name": "owningUser",
  "appliedTraits": [
    "is.CDS.standard",
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Owning User"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Unique identifier for the user that owns the record."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Owning User",
  "description": "Unique identifier for the user that owns the record.",
  "isNullable": true,
  "sourceName": "owninguser"
}
```

### owningTeam

Unique identifier for the team that owns the record.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owning Team</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for the team that owns the record.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>owningteam</td><td>string</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "owningTeam",
  "appliedTraits": [
    "is.CDS.standard",
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Owning Team"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Unique identifier for the team that owns the record."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Owning Team",
  "description": "Unique identifier for the team that owns the record.",
  "isNullable": true,
  "sourceName": "owningteam"
}
```

### timeZoneRuleVersionNumber

For internal use only.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time Zone Rule Version Number</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>For internal use only.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>timezoneruleversionnumber</td><td>string</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-1</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### UTCConversionTimeZoneCode

Time zone code that was in use when the record was created.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>UTC Conversion Time Zone Code</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time zone code that was in use when the record was created.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>utcconversiontimezonecode</td><td>string</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-1</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### versionNumber

Version Number

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.dataFormat.big


##### means.measurement.version


##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version Number</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version Number</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>versionnumber</td><td>string</td><td>undefined</td></tr></table>


### activityTypeCode

Type of activity.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Type</td></tr><tr><td>description</td><td>Type of activity.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>activitytypecode</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr><tr><td>defaultValue</td><td>[
  {
    "languageTag": "en",
    "displayText": "Fax"
  },
  {
    "languageTag": "en",
    "displayText": "Phone Call"
  },
  {
    "languageTag": "en",
    "displayText": "Email"
  },
  {
    "languageTag": "en",
    "displayText": "Letter"
  },
  {
    "languageTag": "en",
    "displayText": "Appointment"
  },
  {
    "languageTag": "en",
    "displayText": "Task"
  },
  {
    "languageTag": "en",
    "displayText": "Recurring Appointment"
  },
  {
    "languageTag": "en",
    "displayText": "Quick Campaign"
  },
  {
    "languageTag": "en",
    "displayText": "Campaign Activity"
  },
  {
    "languageTag": "en",
    "displayText": "Campaign Response"
  },
  {
    "languageTag": "en",
    "displayText": "Case Resolution"
  },
  {
    "languageTag": "en",
    "displayText": "Service Activity"
  },
  {
    "languageTag": "en",
    "displayText": "Opportunity Close"
  },
  {
    "languageTag": "en",
    "displayText": "Order Close"
  },
  {
    "languageTag": "en",
    "displayText": "Quote Close"
  },
  {
    "languageTag": "en",
    "displayText": "Alert Subscription"
  },
  {
    "languageTag": "en",
    "displayText": "Invite Redemption"
  },
  {
    "languageTag": "en",
    "displayText": "Portal Comment"
  }
]</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.entityName


##### is.readOnly


##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fax</td></tr><tr><td>en</td><td>Phone Call</td></tr><tr><td>en</td><td>Email</td></tr><tr><td>en</td><td>Letter</td></tr><tr><td>en</td><td>Appointment</td></tr><tr><td>en</td><td>Task</td></tr><tr><td>en</td><td>Recurring Appointment</td></tr><tr><td>en</td><td>Quick Campaign</td></tr><tr><td>en</td><td>Campaign Activity</td></tr><tr><td>en</td><td>Campaign Response</td></tr><tr><td>en</td><td>Case Resolution</td></tr><tr><td>en</td><td>Service Activity</td></tr><tr><td>en</td><td>Opportunity Close</td></tr><tr><td>en</td><td>Order Close</td></tr><tr><td>en</td><td>Quote Close</td></tr><tr><td>en</td><td>Alert Subscription</td></tr><tr><td>en</td><td>Invite Redemption</td></tr><tr><td>en</td><td>Portal Comment</td></tr></table>
</td><td>any</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Activity Type</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Type of activity.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>activitytypecode</td><td>string</td><td>undefined</td></tr></table>


##### is.linkedEntity.name

Marks an attribute that contains the entity name or 'class' for the situation where one entity links to (uses as an attribute) a set of possible entities.


### activityId

Unique identifier of the activity.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity</td></tr><tr><td>description</td><td>Unique identifier of the activity.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>activityid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.identifiedBy

names a specifc identity attribute to use with an entity

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>attribute</td><td>"Email_/hasAttributes/activityId"</td><td>attribute</td><td>undefined</td></tr></table>

Definition:

```
"Email_/hasAttributes/activityId"
```

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Activity</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the activity.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>activityid</td><td>string</td><td>undefined</td></tr></table>


##### is.linkedEntity.identifier

Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.


### isBilled

Information regarding whether the fax activity was billed as part of resolving a case.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Billed</td></tr><tr><td>description</td><td>Information regarding whether the fax activity was billed as part of resolving a case.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isbilled</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.boolean


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is Billed</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Information regarding whether the fax activity was billed as part of resolving a case.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>isbilled</td><td>string</td><td>undefined</td></tr></table>


### isRegularActivity

Information regarding whether the activity is a regular activity type or event type.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Regular Activity</td></tr><tr><td>description</td><td>Information regarding whether the activity is a regular activity type or event type.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>isregularactivity</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.boolean


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is Regular Activity</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Information regarding whether the activity is a regular activity type or event type.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>isregularactivity</td><td>string</td><td>undefined</td></tr></table>


### isWorkflowCreated

Information regarding whether the activity was created from a workflow rule.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Workflow Created</td></tr><tr><td>description</td><td>Information regarding whether the activity was created from a workflow rule.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isworkflowcreated</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.boolean


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is Workflow Created</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Information regarding whether the activity was created from a workflow rule.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>isworkflowcreated</td><td>string</td><td>undefined</td></tr></table>


### priorityCode

Priority of the activity.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Priority</td></tr><tr><td>description</td><td>Priority of the activity.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>prioritycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td>[
  {
    "languageTag": "en",
    "displayText": "Low",
    "attributeValue": "0",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Normal",
    "attributeValue": "1",
    "displayOrder": "1"
  },
  {
    "languageTag": "en",
    "displayText": "High",
    "attributeValue": "2",
    "displayOrder": "2"
  }
]</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr><tr><td>en</td><td>Low</td><td>0</td><td>0</td></tr><tr><td>en</td><td>Normal</td><td>1</td><td>1</td></tr><tr><td>en</td><td>High</td><td>2</td><td>2</td></tr></table>
</td><td>any</td><td>undefined</td></tr></table>


##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Priority</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Priority of the activity.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>prioritycode</td><td>string</td><td>undefined</td></tr></table>


### priorityCode_display

undefined

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.reference.displayText


##### is.readOnly


##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>priorityCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>


### regardingObjectTypeCode

The name of the entity linked by regardingObjectId

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regarding Type</td></tr><tr><td>description</td><td>The name of the entity linked by regardingObjectId</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>regardingobjecttypecode</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.entityName


##### is.readOnly


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Regarding Type</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The name of the entity linked by regardingObjectId</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>regardingobjecttypecode</td><td>string</td><td>undefined</td></tr></table>


##### is.linkedEntity.name

Marks an attribute that contains the entity name or 'class' for the situation where one entity links to (uses as an attribute) a set of possible entities.


### regardingObjectId

Unique identifier of the object with which the activity is associated.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regarding</td></tr><tr><td>description</td><td>Unique identifier of the object with which the activity is associated.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>regardingobjectid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Regarding</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the object with which the activity is associated.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>regardingobjectid</td><td>string</td><td>undefined</td></tr></table>


##### is.linkedEntity.identifier

Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "explanation": "Place holder that merges with ...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

Definition:

```
{
  "explanation": "Place holder that merges with the better attribute description from the ActivityCommon entity",
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "regardingObjectId"
}
```

### scheduledEnd

Scheduled end time of the activity.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Due Date</td></tr><tr><td>description</td><td>Scheduled end time of the activity.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduledend</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.date


##### means.measurement.date


##### is.dataFormat.time


##### means.measurement.time


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Due Date</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Scheduled end time of the activity.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>scheduledend</td><td>string</td><td>undefined</td></tr></table>


### scheduledStart

Scheduled start time of the activity.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date</td></tr><tr><td>description</td><td>Scheduled start time of the activity.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduledstart</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.date


##### means.measurement.date


##### is.dataFormat.time


##### means.measurement.time


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Start Date</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Scheduled start time of the activity.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>scheduledstart</td><td>string</td><td>undefined</td></tr></table>


### sortDate

Shows the date and time by which the activities are sorted.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sort Date</td></tr><tr><td>description</td><td>Shows the date and time by which the activities are sorted.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sortdate</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.date


##### means.measurement.date


##### is.dataFormat.time


##### means.measurement.time


##### is.ordered

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>attribute</td><td>"Email_/hasAttributes/sortDate"</td><td>attribute</td><td>undefined</td></tr></table>

Definition:

```
"Email_/hasAttributes/sortDate"
```

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sort Date</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the date and time by which the activities are sorted.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>sortdate</td><td>string</td><td>undefined</td></tr></table>


### subject

Subject associated with the activity.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject</td></tr><tr><td>description</td><td>Subject associated with the activity.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>subject</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>required</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Subject</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Subject associated with the activity.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>subject</td><td>string</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>200</td><td>integer</td><td>undefined</td></tr></table>


### scheduledDurationMinutes

Scheduled duration of the activity, specified in minutes.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scheduled Duration</td></tr><tr><td>description</td><td>Scheduled duration of the activity, specified in minutes.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduleddurationminutes</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### means.measurement.duration.minutes


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Scheduled Duration</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Scheduled duration of the activity, specified in minutes.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>scheduleddurationminutes</td><td>string</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>0</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### actualDurationMinutes

Actual duration of the activity in minutes.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Duration</td></tr><tr><td>description</td><td>Actual duration of the activity in minutes.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualdurationminutes</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### means.measurement.duration.minutes


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Actual Duration</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Actual duration of the activity in minutes.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>actualdurationminutes</td><td>string</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>0</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### actualEnd

Actual end time of the activity.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual End</td></tr><tr><td>description</td><td>Actual end time of the activity.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualend</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.date


##### means.measurement.date


##### is.dataFormat.time


##### means.measurement.time


##### means.measurement.date.end


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Actual End</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Actual end time of the activity.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>actualend</td><td>string</td><td>undefined</td></tr></table>


### actualStart

Actual start time of the activity.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Start</td></tr><tr><td>description</td><td>Actual start time of the activity.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualstart</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.date


##### means.measurement.date


##### is.dataFormat.time


##### means.measurement.time


##### means.measurement.date.start


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Actual Start</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Actual start time of the activity.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>actualstart</td><td>string</td><td>undefined</td></tr></table>


### category

Type a category to identify the activity type, such as lead outreach, customer follow-up, or service alert, to tie the eactivity to a business group or function.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Category</td></tr><tr><td>description</td><td>Type a category to identify the activity type, such as lead outreach, customer follow-up, or service alert, to tie the eactivity to a business group or function.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>category</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.category


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Category</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Type a category to identify the activity type, such as lead outreach, customer follow-up, or service alert, to tie the eactivity to a business group or function.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>category</td><td>string</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>250</td><td>integer</td><td>undefined</td></tr></table>


### subcategory

Type a subcategory to identify the activity type and relate the activity to a specific product, sales region, business group, or other function.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sub-Category</td></tr><tr><td>description</td><td>Type a subcategory to identify the activity type and relate the activity to a specific product, sales region, business group, or other function.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>subcategory</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sub-Category</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Type a subcategory to identify the activity type and relate the activity to a specific product, sales region, business group, or other function.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>subcategory</td><td>string</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>250</td><td>integer</td><td>undefined</td></tr></table>


### activityAdditionalParams

Additional information provided by the external application as JSON. For internal use only.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Additional Parameters</td></tr><tr><td>description</td><td>Additional information provided by the external application as JSON. For internal use only.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>8192</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>activityadditionalparams</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.content.text.JSON


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Activity Additional Parameters</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Additional information provided by the external application as JSON. For internal use only.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>activityadditionalparams</td><td>string</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>8192</td><td>integer</td><td>undefined</td></tr></table>


### to

Enter the account, contact, lead, or user recipients of the phone call.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>To</td></tr><tr><td>description</td><td>Enter the account, contact, lead, or user recipients of the phone call.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>to</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### is.CDS.partyList

contains a link to ActivityParty to identify the set of party members


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>multi</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>To</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Enter the account, contact, lead, or user recipients of the phone call.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>to</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>5</td><td>integer</td><td>undefined</td></tr></table>


### from

Enter the account, contact, lead, or user who made the phone call.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Call From</td></tr><tr><td>description</td><td>Enter the account, contact, lead, or user who made the phone call.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>from</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### is.CDS.partyList

contains a link to ActivityParty to identify the set of party members


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Call From</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Enter the account, contact, lead, or user who made the phone call.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>from</td><td>string</td><td>undefined</td></tr></table>


### BCC

Enter the recipients that are included on the activity distribution, but are not displayed to other recipients.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bcc</td></tr><tr><td>description</td><td>Enter the recipients that are included on the activity distribution, but are not displayed to other recipients.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>bcc</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### is.CDS.partyList

contains a link to ActivityParty to identify the set of party members


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>multi</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bcc</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Enter the recipients that are included on the activity distribution, but are not displayed to other recipients.</td></tr><tr><td>en</td><td>Enter the recipients that are included on the email distribution, but are not displayed to other recipients.</td></tr><tr><td>en</td><td>Enter the recipients that are included in the letter distribution, but are not displayed to other recipients.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>bcc</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>29</td><td>integer</td><td>undefined</td></tr></table>


### CC

Enter the recipients that should be copied on the activity.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cc</td></tr><tr><td>description</td><td>Enter the recipients that should be copied on the activity.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>cc</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### is.CDS.partyList

contains a link to ActivityParty to identify the set of party members


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>multi</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cc</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Enter the recipients that should be copied on the activity.</td></tr><tr><td>en</td><td>Enter the recipients that should be copied on the email.</td></tr><tr><td>en</td><td>Enter the recipients that should be copied on the letter.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>cc</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>30</td><td>integer</td><td>undefined</td></tr></table>


### sentOn

Date and time when the activity was sent.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Sent</td></tr><tr><td>description</td><td>Date and time when the activity was sent.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>senton</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.date


##### means.measurement.date


##### is.dataFormat.time


##### means.measurement.time


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date Sent</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the activity was sent.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>senton</td><td>string</td><td>undefined</td></tr></table>


### senderMailboxId

Unique identifier of the mailbox associated with the sender of the email message.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sender's Mailbox</td></tr><tr><td>description</td><td>Unique identifier of the mailbox associated with the sender of the email message.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sendermailboxid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sender's Mailbox</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the mailbox associated with the sender of the email message.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>sendermailboxid</td><td>string</td><td>undefined</td></tr></table>


### deliveryPriorityCode

Priority of delivery of the activity to the email server.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery Priority</td></tr><tr><td>description</td><td>Priority of delivery of the activity to the email server.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>deliveryprioritycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td>[
  {
    "languageTag": "en",
    "displayText": "Low",
    "attributeValue": "0",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Normal",
    "attributeValue": "1",
    "displayOrder": "1"
  },
  {
    "languageTag": "en",
    "displayText": "High",
    "attributeValue": "2",
    "displayOrder": "2"
  }
]</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr><tr><td>en</td><td>Low</td><td>0</td><td>0</td></tr><tr><td>en</td><td>Normal</td><td>1</td><td>1</td></tr><tr><td>en</td><td>High</td><td>2</td><td>2</td></tr></table>
</td><td>any</td><td>undefined</td></tr></table>


##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delivery Priority</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Priority of delivery of the activity to the email server.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>deliveryprioritycode</td><td>string</td><td>undefined</td></tr></table>


### deliveryPriorityCode_display

undefined

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.reference.displayText


##### is.readOnly


##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>deliveryPriorityCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>


### directionCode

Select the direction of the activity as incoming or outbound.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Direction</td></tr><tr><td>description</td><td>Select the direction of the activity as incoming or outbound.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>directioncode</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.boolean


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Direction</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Select the direction of the activity as incoming or outbound.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>directioncode</td><td>string</td><td>undefined</td></tr></table>


### statusCode

Select the email's status.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the email's status.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td>[
  {
    "languageTag": "en",
    "displayText": "Draft",
    "attributeValue": "1",
    "displayOrder": "0",
    "correlatedValue": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Completed",
    "attributeValue": "2",
    "displayOrder": "1",
    "correlatedValue": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Sent",
    "attributeValue": "3",
    "displayOrder": "2",
    "correlatedValue": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Received",
    "attributeValue": "4",
    "displayOrder": "3",
    "correlatedValue": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Canceled",
    "attributeValue": "5",
    "displayOrder": "4",
    "correlatedValue": "2"
  },
  {
    "languageTag": "en",
    "displayText": "Pending Send",
    "attributeValue": "6",
    "displayOrder": "5",
    "correlatedValue": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Sending",
    "attributeValue": "7",
    "displayOrder": "6",
    "correlatedValue": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Failed",
    "attributeValue": "8",
    "displayOrder": "7",
    "correlatedValue": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Draft",
    "attributeValue": "1",
    "displayOrder": "8",
    "correlatedValue": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Completed",
    "attributeValue": "2",
    "displayOrder": "9",
    "correlatedValue": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Sent",
    "attributeValue": "3",
    "displayOrder": "10",
    "correlatedValue": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Received",
    "attributeValue": "4",
    "displayOrder": "11",
    "correlatedValue": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Canceled",
    "attributeValue": "5",
    "displayOrder": "12",
    "correlatedValue": "2"
  },
  {
    "languageTag": "en",
    "displayText": "Pending Send",
    "attributeValue": "6",
    "displayOrder": "13",
    "correlatedValue": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Sending",
    "attributeValue": "7",
    "displayOrder": "14",
    "correlatedValue": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Failed",
    "attributeValue": "8",
    "displayOrder": "15",
    "correlatedValue": "0"
  }
]</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>correlatedValue</th></tr><tr><td>en</td><td>Draft</td><td>1</td><td>0</td><td>0</td></tr><tr><td>en</td><td>Completed</td><td>2</td><td>1</td><td>1</td></tr><tr><td>en</td><td>Sent</td><td>3</td><td>2</td><td>1</td></tr><tr><td>en</td><td>Received</td><td>4</td><td>3</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>5</td><td>4</td><td>2</td></tr><tr><td>en</td><td>Pending Send</td><td>6</td><td>5</td><td>1</td></tr><tr><td>en</td><td>Sending</td><td>7</td><td>6</td><td>1</td></tr><tr><td>en</td><td>Failed</td><td>8</td><td>7</td><td>0</td></tr><tr><td>en</td><td>Draft</td><td>1</td><td>8</td><td>0</td></tr><tr><td>en</td><td>Completed</td><td>2</td><td>9</td><td>1</td></tr><tr><td>en</td><td>Sent</td><td>3</td><td>10</td><td>1</td></tr><tr><td>en</td><td>Received</td><td>4</td><td>11</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>5</td><td>12</td><td>2</td></tr><tr><td>en</td><td>Pending Send</td><td>6</td><td>13</td><td>1</td></tr><tr><td>en</td><td>Sending</td><td>7</td><td>14</td><td>1</td></tr><tr><td>en</td><td>Failed</td><td>8</td><td>15</td><td>0</td></tr></table>
</td><td>any</td><td>undefined</td></tr></table>


##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities


##### is.correlatedWith

the attribute value is correlated with the sourceAttribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>sourceAttribute</td><td>stateCode</td><td>attributeName</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status Reason</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Select the email's status.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>statuscode</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>2</td><td>integer</td><td>undefined</td></tr></table>


### statusCode_display

undefined

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.reference.displayText


##### is.readOnly


##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>statusCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>


### submittedBy

Shows the Microsoft Office Outlook account for the user who submitted the email to Microsoft Dynamics 365.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Submitted By</td></tr><tr><td>description</td><td>Shows the Microsoft Office Outlook account for the user who submitted the email to Microsoft Dynamics 365.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>submittedby</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Submitted By</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the Microsoft Office Outlook account for the user who submitted the email to Microsoft Dynamics 365.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>submittedby</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>3</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>250</td><td>integer</td><td>undefined</td></tr></table>


### description

Type the greeting and message text of the email.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type the greeting and message text of the email.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Description</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Type the greeting and message text of the email.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>description</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>4</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>1073741823</td><td>integer</td><td>undefined</td></tr></table>


### mimeType

MIME type of the email message data.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mime Type</td></tr><tr><td>description</td><td>MIME type of the email message data.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>256</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mimetype</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Mime Type</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>MIME type of the email message data.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>mimetype</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>9</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>256</td><td>integer</td><td>undefined</td></tr></table>


### readReceiptRequested

Indicates that a read receipt is requested.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Read Receipt Requested</td></tr><tr><td>description</td><td>Indicates that a read receipt is requested.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>readreceiptrequested</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.boolean


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Read Receipt Requested</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indicates that a read receipt is requested.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>readreceiptrequested</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>12</td><td>integer</td><td>undefined</td></tr></table>


### trackingToken

Shows the tracking token assigned to the email to make sure responses are automatically tracked in Microsoft Dynamics 365.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tracking Token</td></tr><tr><td>description</td><td>Shows the tracking token assigned to the email to make sure responses are automatically tracked in Microsoft Dynamics 365.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>trackingtoken</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tracking Token</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the tracking token assigned to the email to make sure responses are automatically tracked in Microsoft Dynamics 365.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>trackingtoken</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>22</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>50</td><td>integer</td><td>undefined</td></tr></table>


### sender

Sender of the email.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>From</td></tr><tr><td>description</td><td>Sender of the email.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sender</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>From</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sender of the email.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>sender</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>31</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>250</td><td>integer</td><td>undefined</td></tr></table>


### toRecipients

Shows the email addresses corresponding to the recipients.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>To Recipients</td></tr><tr><td>description</td><td>Shows the email addresses corresponding to the recipients.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>torecipients</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>To Recipients</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the email addresses corresponding to the recipients.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>torecipients</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>34</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>500</td><td>integer</td><td>undefined</td></tr></table>


### deliveryReceiptRequested

Select whether the sender should receive confirmation that the email was delivered.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery Receipt Requested</td></tr><tr><td>description</td><td>Select whether the sender should receive confirmation that the email was delivered.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>deliveryreceiptrequested</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.boolean


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delivery Receipt Requested</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Select whether the sender should receive confirmation that the email was delivered.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>deliveryreceiptrequested</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>35</td><td>integer</td><td>undefined</td></tr></table>


### stateCode

Shows whether the email is open, completed, or canceled. Completed and canceled email is read-only and can't be edited.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Status</td></tr><tr><td>description</td><td>Shows whether the email is open, completed, or canceled. Completed and canceled email is read-only and can't be edited.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td>[
  {
    "languageTag": "en",
    "displayText": "Open",
    "attributeValue": "0",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Completed",
    "attributeValue": "1",
    "displayOrder": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Canceled",
    "attributeValue": "2",
    "displayOrder": "2"
  }
]</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr><tr><td>en</td><td>Open</td><td>0</td><td>0</td></tr><tr><td>en</td><td>Completed</td><td>1</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>2</td><td>2</td></tr></table>
</td><td>any</td><td>undefined</td></tr></table>


##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities


##### means.entityState

the attribute represents the current state of the entity.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>attribute</td><td>"Email_/hasAttributes/stateCode"</td><td>attribute</td><td>undefined</td></tr></table>

Definition:

```
"Email_/hasAttributes/stateCode"
```

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Activity Status</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows whether the email is open, completed, or canceled. Completed and canceled email is read-only and can't be edited.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>statecode</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>37</td><td>integer</td><td>undefined</td></tr></table>


### stateCode_display

undefined

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.reference.displayText


##### is.readOnly


##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>stateCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>


### messageId

Unique identifier of the email message. Used only for email that is received.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Message ID</td></tr><tr><td>description</td><td>Unique identifier of the email message. Used only for email that is received.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>320</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>messageid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Message ID</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the email message. Used only for email that is received.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>messageid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>39</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>320</td><td>integer</td><td>undefined</td></tr></table>


### deliveryAttempts

Shows the count of the number of attempts made to send the email. The count is used as an indicator of email routing issues.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>No. of Delivery Attempts</td></tr><tr><td>description</td><td>Shows the count of the number of attempts made to send the email. The count is used as an indicator of email routing issues.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>deliveryattempts</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>No. of Delivery Attempts</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the count of the number of attempts made to send the email. The count is used as an indicator of email routing issues.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>deliveryattempts</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>61</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>0</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>1000000000</td><td>decimal</td><td>undefined</td></tr></table>


### compressed

Indicates if the body is compressed.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Compression</td></tr><tr><td>description</td><td>Indicates if the body is compressed.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>compressed</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.boolean


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Compression</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indicates if the body is compressed.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>compressed</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>63</td><td>integer</td><td>undefined</td></tr></table>


### notifications

Select the notification code to identify issues with the email recipients or attachments, such as blocked attachments.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Notifications</td></tr><tr><td>description</td><td>Select the notification code to identify issues with the email recipients or attachments, such as blocked attachments.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>notifications</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td>[
  {
    "languageTag": "en",
    "displayText": "None",
    "attributeValue": "0",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "The message was saved as a Microsoft Dynamics 365 email record, but not all the attachments could be saved with it. An attachment cannot be saved if it is blocked or if its file type is invalid.",
    "attributeValue": "1",
    "displayOrder": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Truncated body.",
    "attributeValue": "2",
    "displayOrder": "2"
  }
]</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr><tr><td>en</td><td>None</td><td>0</td><td>0</td></tr><tr><td>en</td><td>The message was saved as a Microsoft Dynamics 365 email record, but not all the attachments could be saved with it. An attachment cannot be saved if it is blocked or if its file type is invalid.</td><td>1</td><td>1</td></tr><tr><td>en</td><td>Truncated body.</td><td>2</td><td>2</td></tr></table>
</td><td>any</td><td>undefined</td></tr></table>


##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Notifications</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Select the notification code to identify issues with the email recipients or attachments, such as blocked attachments.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>notifications</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>64</td><td>integer</td><td>undefined</td></tr></table>


### notifications_display

undefined

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.reference.displayText


##### is.readOnly


##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>notifications</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>


### transactionCurrencyId

Choose the local currency for the record to make sure budgets are reported in the correct currency.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Currency</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>transactioncurrencyid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>87</td><td>integer</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "transactionCurrencyId",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Currency"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Choose the local currency for the record to make sure budgets are reported in the correct currency."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Currency",
  "description": "Choose the local currency for the record to make sure budgets are reported in the correct currency.",
  "isNullable": true,
  "sourceName": "transactioncurrencyid",
  "sourceOrdering": 87
}
```

### exchangeRate

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Exchange Rate</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>exchangerate</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>89</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>1E-10</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>100000000000</td><td>decimal</td><td>undefined</td></tr></table>


### emailSenderObjectTypeCode

The name of the entity linked by emailSender

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>emailSender Type</td></tr><tr><td>description</td><td>The name of the entity linked by emailSender</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>emailsenderobjecttypecode</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.entityName


##### is.readOnly


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>emailSender Type</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The name of the entity linked by emailSender</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>emailsenderobjecttypecode</td><td>string</td><td>undefined</td></tr></table>


##### is.linkedEntity.name

Marks an attribute that contains the entity name or 'class' for the situation where one entity links to (uses as an attribute) a set of possible entities.


### emailSender

Shows the sender of the email.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sender</td></tr><tr><td>description</td><td>Shows the sender of the email.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailsender</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>multi</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sender</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the sender of the email.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>emailsender</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>90</td><td>integer</td><td>undefined</td></tr></table>


##### is.linkedEntity.identifier

Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "emailSender",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "multi"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Sender"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Shows the sender of the email."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Sender",
  "description": "Shows the sender of the email.",
  "isNullable": true,
  "sourceName": "emailsender",
  "sourceOrdering": 90
}
```

### sendersAccountObjectTypeCode

The name of the entity linked by sendersAccount

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>sendersAccount Type</td></tr><tr><td>description</td><td>The name of the entity linked by sendersAccount</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>sendersaccountobjecttypecode</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.entityName


##### is.readOnly


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>sendersAccount Type</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The name of the entity linked by sendersAccount</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>sendersaccountobjecttypecode</td><td>string</td><td>undefined</td></tr></table>


##### is.linkedEntity.name

Marks an attribute that contains the entity name or 'class' for the situation where one entity links to (uses as an attribute) a set of possible entities.


### sendersAccount

Shows the parent account of the sender of the email.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Senders Account</td></tr><tr><td>description</td><td>Shows the parent account of the sender of the email.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sendersaccount</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Senders Account</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the parent account of the sender of the email.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>sendersaccount</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>94</td><td>integer</td><td>undefined</td></tr></table>


##### is.linkedEntity.identifier

Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.


### attachmentCount

Shows the umber of attachments of the email message.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Attachment Count</td></tr><tr><td>description</td><td>Shows the umber of attachments of the email message.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>attachmentcount</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Attachment Count</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the umber of attachments of the email message.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>attachmentcount</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>96</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>0</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### parentActivityId

Select the activity that the email is associated with.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent Activity Id</td></tr><tr><td>description</td><td>Select the activity that the email is associated with.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>parentactivityid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Parent Activity Id</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Select the activity that the email is associated with.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>parentactivityid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>102</td><td>integer</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "parentActivityId",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Parent Activity Id"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Select the activity that the email is associated with."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Parent Activity Id",
  "description": "Select the activity that the email is associated with.",
  "isNullable": true,
  "sourceName": "parentactivityid",
  "sourceOrdering": 102
}
```

### inReplyTo

Type the ID of the email message that this email activity is a response to.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>In Reply To Message</td></tr><tr><td>description</td><td>Type the ID of the email message that this email activity is a response to.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>320</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>inreplyto</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>In Reply To Message</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Type the ID of the email message that this email activity is a response to.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>inreplyto</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>104</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>320</td><td>integer</td><td>undefined</td></tr></table>


### baseConversationIndexHash

Hash of base of conversation index.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Conversation Index (Hash)</td></tr><tr><td>description</td><td>Hash of base of conversation index.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>baseconversationindexhash</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Conversation Index (Hash)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Hash of base of conversation index.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>baseconversationindexhash</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>105</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-2147483648</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### conversationIndex

Identifier for all the email responses for this conversation.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Conversation Index</td></tr><tr><td>description</td><td>Identifier for all the email responses for this conversation.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2048</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>conversationindex</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Conversation Index</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Identifier for all the email responses for this conversation.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>conversationindex</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>106</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>2048</td><td>integer</td><td>undefined</td></tr></table>


### correlationMethod

Shows how an email is matched to an existing email in Microsoft Dynamics 365. For system use only.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Correlation Method</td></tr><tr><td>description</td><td>Shows how an email is matched to an existing email in Microsoft Dynamics 365. For system use only.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>correlationmethod</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td>[
  {
    "languageTag": "en",
    "displayText": "None",
    "attributeValue": "0",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Skipped",
    "attributeValue": "1",
    "displayOrder": "1"
  },
  {
    "languageTag": "en",
    "displayText": "XHeader",
    "attributeValue": "2",
    "displayOrder": "2"
  },
  {
    "languageTag": "en",
    "displayText": "InReplyTo",
    "attributeValue": "3",
    "displayOrder": "3"
  },
  {
    "languageTag": "en",
    "displayText": "TrackingToken",
    "attributeValue": "4",
    "displayOrder": "4"
  },
  {
    "languageTag": "en",
    "displayText": "ConversationIndex",
    "attributeValue": "5",
    "displayOrder": "5"
  },
  {
    "languageTag": "en",
    "displayText": "SmartMatching",
    "attributeValue": "6",
    "displayOrder": "6"
  },
  {
    "languageTag": "en",
    "displayText": "CustomCorrelation",
    "attributeValue": "7",
    "displayOrder": "7"
  }
]</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr><tr><td>en</td><td>None</td><td>0</td><td>0</td></tr><tr><td>en</td><td>Skipped</td><td>1</td><td>1</td></tr><tr><td>en</td><td>XHeader</td><td>2</td><td>2</td></tr><tr><td>en</td><td>InReplyTo</td><td>3</td><td>3</td></tr><tr><td>en</td><td>TrackingToken</td><td>4</td><td>4</td></tr><tr><td>en</td><td>ConversationIndex</td><td>5</td><td>5</td></tr><tr><td>en</td><td>SmartMatching</td><td>6</td><td>6</td></tr><tr><td>en</td><td>CustomCorrelation</td><td>7</td><td>7</td></tr></table>
</td><td>any</td><td>undefined</td></tr></table>


##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Correlation Method</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows how an email is matched to an existing email in Microsoft Dynamics 365. For system use only.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>correlationmethod</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>107</td><td>integer</td><td>undefined</td></tr></table>


### correlationMethod_display

undefined

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.reference.displayText


##### is.readOnly


##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>correlationMethod</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>


### postponeEmailProcessingUntil

For internal use only.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delay email processing until</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postponeemailprocessinguntil</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.date


##### means.measurement.date


##### is.dataFormat.time


##### means.measurement.time


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delay email processing until</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>For internal use only.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>postponeemailprocessinguntil</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>109</td><td>integer</td><td>undefined</td></tr></table>


### processId

Shows the ID of the process.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process</td></tr><tr><td>description</td><td>Shows the ID of the process.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Process</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the ID of the process.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>processid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>111</td><td>integer</td><td>undefined</td></tr></table>


### stageId

Shows the ID of the stage.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Stage</td></tr><tr><td>description</td><td>Shows the ID of the stage.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Process Stage</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the ID of the stage.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>stageid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>112</td><td>integer</td><td>undefined</td></tr></table>


### isUnsafe

For internal use only.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>IsUnsafe</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isunsafe</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>IsUnsafe</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>For internal use only.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>isunsafe</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>115</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>0</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### SLAId

Choose the service level agreement (SLA) that you want to apply to the email record.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SLA</td></tr><tr><td>description</td><td>Choose the service level agreement (SLA) that you want to apply to the email record.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slaid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>SLA</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Choose the service level agreement (SLA) that you want to apply to the email record.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>slaid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>116</td><td>integer</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "SLAId",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "SLA"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Choose the service level agreement (SLA) that you want to apply to the email record."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "SLA",
  "description": "Choose the service level agreement (SLA) that you want to apply to the email record.",
  "isNullable": true,
  "sourceName": "slaid",
  "sourceOrdering": 116
}
```

### SLAInvokedId

Last SLA that was applied to this email. This field is for internal use only.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last SLA applied</td></tr><tr><td>description</td><td>Last SLA that was applied to this email. This field is for internal use only.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slainvokedid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Last SLA applied</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Last SLA that was applied to this email. This field is for internal use only.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>slainvokedid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>117</td><td>integer</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "SLAInvokedId",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Last SLA applied"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Last SLA that was applied to this email. This field is for internal use only."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Last SLA applied",
  "description": "Last SLA that was applied to this email. This field is for internal use only.",
  "isNullable": true,
  "sourceName": "slainvokedid",
  "sourceOrdering": 117
}
```

### onHoldTime

Shows how long, in minutes, that the record was on hold.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>On Hold Time (Minutes)</td></tr><tr><td>description</td><td>Shows how long, in minutes, that the record was on hold.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>onholdtime</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>On Hold Time (Minutes)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows how long, in minutes, that the record was on hold.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>onholdtime</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>118</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-2147483648</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### lastOnHoldTime

Contains the date and time stamp of the last on hold time.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last On Hold Time</td></tr><tr><td>description</td><td>Contains the date and time stamp of the last on hold time.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastonholdtime</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.date


##### means.measurement.date


##### is.dataFormat.time


##### means.measurement.time


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Last On Hold Time</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Contains the date and time stamp of the last on hold time.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>lastonholdtime</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>119</td><td>integer</td><td>undefined</td></tr></table>


### traversedPath

For internal use only.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Traversed Path</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>For internal use only.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>traversedpath</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>123</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>1250</td><td>integer</td><td>undefined</td></tr></table>


### attachmentOpenCount

Shows the number of times an email attachment has been viewed.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Attachment Open Count</td></tr><tr><td>description</td><td>Shows the number of times an email attachment has been viewed.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>attachmentopencount</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Attachment Open Count</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the number of times an email attachment has been viewed.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>attachmentopencount</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>126</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>0</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### conversationTrackingId

Conversation Tracking Id.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Conversation Tracking Id</td></tr><tr><td>description</td><td>Conversation Tracking Id.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>conversationtrackingid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Conversation Tracking Id</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Conversation Tracking Id.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>conversationtrackingid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>127</td><td>integer</td><td>undefined</td></tr></table>


### delayedEmailSendTime

Enter the expected date and time when email will be sent.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Send Later</td></tr><tr><td>description</td><td>Enter the expected date and time when email will be sent.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>delayedemailsendtime</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.date


##### means.measurement.date


##### is.dataFormat.time


##### means.measurement.time


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Send Later</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Enter the expected date and time when email will be sent.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>delayedemailsendtime</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>128</td><td>integer</td><td>undefined</td></tr></table>


### lastOpenedTime

Shows the latest date and time when email was opened.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Opened Time</td></tr><tr><td>description</td><td>Shows the latest date and time when email was opened.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastopenedtime</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.date


##### means.measurement.date


##### is.dataFormat.time


##### means.measurement.time


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Last Opened Time</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the latest date and time when email was opened.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>lastopenedtime</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>129</td><td>integer</td><td>undefined</td></tr></table>


### linksClickedCount

Shows the number of times a link in an email has been clicked.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Links Clicked Count</td></tr><tr><td>description</td><td>Shows the number of times a link in an email has been clicked.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>linksclickedcount</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Links Clicked Count</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the number of times a link in an email has been clicked.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>linksclickedcount</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>130</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>0</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### openCount

Shows the number of times an email has been opened.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Open Count</td></tr><tr><td>description</td><td>Shows the number of times an email has been opened.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>opencount</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Open Count</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the number of times an email has been opened.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>opencount</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>131</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>0</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### replyCount

Shows the number of replies received for an email.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reply Count</td></tr><tr><td>description</td><td>Shows the number of replies received for an email.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>replycount</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reply Count</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the number of replies received for an email.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>replycount</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>132</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>0</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### emailTrackingId

Email Tracking Id.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Tracking Id</td></tr><tr><td>description</td><td>Email Tracking Id.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailtrackingid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Email Tracking Id</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Email Tracking Id.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>emailtrackingid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>133</td><td>integer</td><td>undefined</td></tr></table>


### followEmailUserPreference

Select whether the email allows following recipient activities sent from Microsoft Dynamics 365.This is user preference state which can be overridden by system evaluated state.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Following</td></tr><tr><td>description</td><td>Select whether the email allows following recipient activities sent from Microsoft Dynamics 365.This is user preference state which can be overridden by system evaluated state.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>followemailuserpreference</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.boolean


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Following</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Select whether the email allows following recipient activities sent from Microsoft Dynamics 365.This is user preference state which can be overridden by system evaluated state.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>followemailuserpreference</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>134</td><td>integer</td><td>undefined</td></tr></table>


### isEmailFollowed

For internal use only. Shows whether this email is followed. This is evaluated state which overrides user selection of follow email.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Followed</td></tr><tr><td>description</td><td>For internal use only. Shows whether this email is followed. This is evaluated state which overrides user selection of follow email.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isemailfollowed</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.boolean


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Followed</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>For internal use only. Shows whether this email is followed. This is evaluated state which overrides user selection of follow email.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>isemailfollowed</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>136</td><td>integer</td><td>undefined</td></tr></table>


### emailReminderExpiryTime

Shows the date and time when an email reminder expires.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Reminder Expiry Time</td></tr><tr><td>description</td><td>Shows the date and time when an email reminder expires.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailreminderexpirytime</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.date


##### means.measurement.date


##### is.dataFormat.time


##### means.measurement.time


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Email Reminder Expiry Time</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the date and time when an email reminder expires.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>emailreminderexpirytime</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>138</td><td>integer</td><td>undefined</td></tr></table>


### emailReminderType

Shows the type of the email reminder.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Reminder Type</td></tr><tr><td>description</td><td>Shows the type of the email reminder.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailremindertype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td>[
  {
    "languageTag": "en",
    "displayText": "If I do not receive a reply by",
    "attributeValue": "0",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "If the email is not opened by",
    "attributeValue": "1",
    "displayOrder": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Remind me anyways at",
    "attributeValue": "2",
    "displayOrder": "2"
  }
]</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr><tr><td>en</td><td>If I do not receive a reply by</td><td>0</td><td>0</td></tr><tr><td>en</td><td>If the email is not opened by</td><td>1</td><td>1</td></tr><tr><td>en</td><td>Remind me anyways at</td><td>2</td><td>2</td></tr></table>
</td><td>any</td><td>undefined</td></tr></table>


##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Email Reminder Type</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the type of the email reminder.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>emailremindertype</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>139</td><td>integer</td><td>undefined</td></tr></table>


### emailReminderType_display

undefined

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.reference.displayText


##### is.readOnly


##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>emailReminderType</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>


### emailReminderStatus

Shows the status of the email reminder.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Reminder Status</td></tr><tr><td>description</td><td>Shows the status of the email reminder.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailreminderstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td>[
  {
    "languageTag": "en",
    "displayText": "NotSet",
    "attributeValue": "0",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "ReminderSet",
    "attributeValue": "1",
    "displayOrder": "1"
  },
  {
    "languageTag": "en",
    "displayText": "ReminderExpired",
    "attributeValue": "2",
    "displayOrder": "2"
  },
  {
    "languageTag": "en",
    "displayText": "ReminderInvalid",
    "attributeValue": "3",
    "displayOrder": "3"
  }
]</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr><tr><td>en</td><td>NotSet</td><td>0</td><td>0</td></tr><tr><td>en</td><td>ReminderSet</td><td>1</td><td>1</td></tr><tr><td>en</td><td>ReminderExpired</td><td>2</td><td>2</td></tr><tr><td>en</td><td>ReminderInvalid</td><td>3</td><td>3</td></tr></table>
</td><td>any</td><td>undefined</td></tr></table>


##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Email Reminder Status</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the status of the email reminder.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>emailreminderstatus</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>141</td><td>integer</td><td>undefined</td></tr></table>


### emailReminderStatus_display

undefined

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.reference.displayText


##### is.readOnly


##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>emailReminderStatus</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>


### emailReminderText

For internal use only.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Reminder Text</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailremindertext</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.identity.service.email


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Email Reminder Text</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>For internal use only.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>emailremindertext</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>143</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>1250</td><td>integer</td><td>undefined</td></tr></table>


### templateId

For internal use only. ID for template used in email.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ID for template used.</td></tr><tr><td>description</td><td>For internal use only. ID for template used in email.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>templateid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>ID for template used.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>For internal use only. ID for template used in email.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>templateid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>146</td><td>integer</td><td>undefined</td></tr></table>


### reminderActionCardId

Reminder Action Card Id.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reminder Action Card Id.</td></tr><tr><td>description</td><td>Reminder Action Card Id.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>reminderactioncardid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reminder Action Card Id.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reminder Action Card Id.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>reminderactioncardid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>147</td><td>integer</td><td>undefined</td></tr></table>


### isEmailReminderSet

For internal use only. Shows whether this email Reminder is Set.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reminder Set</td></tr><tr><td>description</td><td>For internal use only. Shows whether this email Reminder is Set.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isemailreminderset</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.boolean


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reminder Set</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>For internal use only. Shows whether this email Reminder is Set.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>isemailreminderset</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>151</td><td>integer</td><td>undefined</td></tr></table>


### serviceId

Unique identifier for the associated service.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Service</td></tr><tr><td>description</td><td>Unique identifier for the associated service.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>serviceid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Service</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for the associated service.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>serviceid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>10000</td><td>integer</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "serviceId",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Service"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Unique identifier for the associated service."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Service",
  "description": "Unique identifier for the associated service.",
  "isNullable": true,
  "sourceName": "serviceid",
  "sourceOrdering": 10000
}
```

