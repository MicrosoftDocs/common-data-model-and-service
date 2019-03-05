---
title: CheckIn - Common Data Model | Microsoft Docs
description: This describes the CheckIn entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/5/2019
ms.author: nebanfic
---

# Check-in

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/eventManagement/CheckIn.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/eventManagement/CheckIn  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[ownerId](#ownerId)|Owner Id|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[checkInId](#checkInId)|Unique identifier for entity instances|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[stateCode](#stateCode)|Status of the Check-in|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[stateCode_display](#stateCode_display)||<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[statusCode](#statusCode)|Reason for the status of the Check-in|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[statusCode_display](#statusCode_display)||<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[name](#name)|Check-in records are used to log the attendance of an attendee at particular event or session.|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[audienceType](#audienceType)|Audience type|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[audienceType_display](#audienceType_display)||<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[checkintime](#checkintime)|Check-in time.|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[checkInType](#checkInType)||<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[checkInType_display](#checkInType_display)||<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[checkOutTime](#checkOutTime)|Check-out time.|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[contact](#contact)|Contact records of the Check-in.|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[event](#event)|Unique identifier for Event associated with Check-in.|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[numberOfQuestionsAsked](#numberOfQuestionsAsked)||<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[purchasedPassesId](#purchasedPassesId)|Unique identifier for Attendee Pass associated with Check-in.|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[registrationId](#registrationId)||<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[sessionAttended](#sessionAttended)|Session records of the Check-in.|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[sessionCode](#sessionCode)||<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[sessionRegistration](#sessionRegistration)|All Active Session Registration Records for this Check-in.|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[sessionType](#sessionType)||<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[sessionType_display](#sessionType_display)||<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|
|[viewingDurationInMins](#viewingDurationInMins)||<a href="CheckIn.md" target="_blank">eventManagement/CheckIn</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#checkInId name="checkInId">checkInId</a>

Unique identifier for entity instances  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Check-in</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msevtmgt_checkinid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Check-in  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Check-in</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Check-in  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Check-in</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

Check-in records are used to log the attendance of an attendee at particular event or session.  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Check-in records are used to log the attendance of an attendee at particular event or session.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_name</td></tr></table>

### <a href=#audienceType name="audienceType">audienceType</a>

Audience type  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Audience Type</td></tr><tr><td>description</td><td>Audience type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_audiencetype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>General</td><td>100000000</td></tr><tr><td>en</td><td>Introductory</td><td>100000001</td></tr><tr><td>en</td><td>Intermediate</td><td>100000002</td></tr><tr><td>en</td><td>Advanced</td><td>100000003</td></tr></table></td></tr></table>

### <a href=#audienceType_display name="audienceType_display">audienceType_display</a>

First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#checkintime name="checkintime">checkintime</a>

Check-in time.  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Check-in time</td></tr><tr><td>description</td><td>Check-in time.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_checkintime</td></tr></table>

### <a href=#checkInType name="checkInType">checkInType</a>

First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Check-in Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_checkintype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Session Check-in</td><td>100000000</td></tr><tr><td>en</td><td>Event Check-in</td><td>100000001</td></tr></table></td></tr></table>

### <a href=#checkInType_display name="checkInType_display">checkInType_display</a>

First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#checkOutTime name="checkOutTime">checkOutTime</a>

Check-out time.  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Check-out time</td></tr><tr><td>description</td><td>Check-out time.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_checkouttime</td></tr></table>

### <a href=#contact name="contact">contact</a>

Contact records of the Check-in.  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Attendee</td></tr><tr><td>description</td><td>Contact records of the Check-in.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_contact</td></tr></table>

### <a href=#event name="event">event</a>

Unique identifier for Event associated with Check-in.  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event</td></tr><tr><td>description</td><td>Unique identifier for Event associated with Check-in.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_event</td></tr></table>

### <a href=#numberOfQuestionsAsked name="numberOfQuestionsAsked">numberOfQuestionsAsked</a>

First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number of interactions</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_numberofquestionsasked</td></tr></table>

### <a href=#purchasedPassesId name="purchasedPassesId">purchasedPassesId</a>

Unique identifier for Attendee Pass associated with Check-in.  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchased Passes</td></tr><tr><td>description</td><td>Unique identifier for Attendee Pass associated with Check-in.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_purchasedpassesid</td></tr></table>

### <a href=#registrationId name="registrationId">registrationId</a>

First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Registrant Attending</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_registrationid</td></tr></table>

### <a href=#sessionAttended name="sessionAttended">sessionAttended</a>

Session records of the Check-in.  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session Attended</td></tr><tr><td>description</td><td>Session records of the Check-in.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_sessionattended</td></tr></table>

### <a href=#sessionCode name="sessionCode">sessionCode</a>

First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session Code</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_sessioncode</td></tr></table>

### <a href=#sessionRegistration name="sessionRegistration">sessionRegistration</a>

All Active Session Registration Records for this Check-in.  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session Registration</td></tr><tr><td>description</td><td>All Active Session Registration Records for this Check-in.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_sessionregistration</td></tr></table>

### <a href=#sessionType name="sessionType">sessionType</a>

First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_sessiontype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Keynote</td><td>100000001</td></tr><tr><td>en</td><td>Breakout</td><td>100000004</td></tr><tr><td>en</td><td>General</td><td>100000002</td></tr><tr><td>en</td><td>Hands-on/Lab</td><td>100000000</td></tr><tr><td>en</td><td>Training</td><td>100000005</td></tr><tr><td>en</td><td>Brainstorming</td><td>100000003</td></tr></table></td></tr></table>

### <a href=#sessionType_display name="sessionType_display">sessionType_display</a>

First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_transactioncurrencyid</td></tr></table>

### <a href=#viewingDurationInMins name="viewingDurationInMins">viewingDurationInMins</a>

First included in: eventManagement/CheckIn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Viewing Duration in mins</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_viewingdurationinmins</td></tr></table>
