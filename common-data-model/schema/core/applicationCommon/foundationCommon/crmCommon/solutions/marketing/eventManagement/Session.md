---
title: Session - Common Data Model | Microsoft Docs
description: This describes the Session entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Session

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/eventManagement/Session.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/eventManagement/Session  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[owningUser](#owningUser)|Unique identifier for the user that owns the record.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[sessionId](#sessionId)|Unique identifier for entity instances|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[stateCode](#stateCode)|Status of the Session|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[stateCode_display](#stateCode_display)||<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[statusCode](#statusCode)|Reason for the status of the Session|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[statusCode_display](#statusCode_display)||<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[name](#name)|The name of the custom entity.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[audienceType](#audienceType)|Audience Type of the Session.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[audienceType_display](#audienceType_display)||<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[AVSupport](#AVSupport)|Audio/Video Support.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[AVSupport_display](#AVSupport_display)||<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[byInvitationOnly](#byInvitationOnly)|Is access by invitation only.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[byInvitationOnly_display](#byInvitationOnly_display)||<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[camerasPermitted](#camerasPermitted)|Are cameras permitted.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[camerasPermitted_display](#camerasPermitted_display)||<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[checkInCount](#checkInCount)|Check-in count|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[detailedDescription](#detailedDescription)|Detailed description of the Session.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[endTime](#endTime)|End time of the Session.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[event](#event)|Unique identifier for Event associated with Event Session.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[eventSpeakerId](#eventSpeakerId)|Unique identifier for Speaker associated with Session.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[externalUrl](#externalUrl)|External url for the Session.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[flipChart](#flipChart)|Is available flip-chart for the Session.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[flipChart_display](#flipChart_display)||<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[industry](#industry)|Industry of the Session.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[industry_display](#industry_display)||<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[internetConnection](#internetConnection)|Are internet connections available.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[internetConnection_display](#internetConnection_display)||<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[keywords](#keywords)|Comma-delimited keyword list for this session|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[language](#language)|The language of the webinar|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[language_display](#language_display)||<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[NDA](#NDA)|Non Disclosure Agreement|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[NDA_display](#NDA_display)||<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[passSessions](#passSessions)|Unique identifier for Product associated with Session.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[presentationManagerUrl](#presentationManagerUrl)||<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[producer](#producer)|Producer of the session|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[publishStatus](#publishStatus)|Publish status of the Session|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[publishStatus_display](#publishStatus_display)||<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[recordingsPermitted](#recordingsPermitted)|Are recordings permitted.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[recordingsPermitted_display](#recordingsPermitted_display)||<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[recurrencePattern](#recurrencePattern)||<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[registrationCount](#registrationCount)|Registration count of the Session.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[sessionCode](#sessionCode)|Code of the Session.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[sessionFormat](#sessionFormat)||<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[sessionFormat_display](#sessionFormat_display)||<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[sessionMaxCapacity](#sessionMaxCapacity)|Maximum capacity of the Session.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[sessionObjectives](#sessionObjectives)|Objectives of the Session.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[sessionPreRequisites](#sessionPreRequisites)|Pre-Requisites of the Session.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[sessionSummary](#sessionSummary)|Summary of the Session.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[sessionType](#sessionType)|Type of the Session.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[sessionType_display](#sessionType_display)||<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[startTime](#startTime)|Start time of the Session.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[venue](#venue)|Active Venue records for this Session.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[videoConferencing](#videoConferencing)|Is available video conferencing for the Session.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[videoConferencing_display](#videoConferencing_display)||<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[webinarConfigurationId](#webinarConfigurationId)|Webinar Configuration|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[webinarID](#webinarID)|Webinar ID of the Session.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[webinarNotificationSeen](#webinarNotificationSeen)|Whether the webinar notification has been seen or not.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[webinarOperation](#webinarOperation)||<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[webinarStatus](#webinarStatus)||<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[webinarStatusReason](#webinarStatusReason)||<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[webinarType](#webinarType)||<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[webinarURL](#webinarURL)||<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[whiteBoard](#whiteBoard)|Is available white board for the Session.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[whiteBoard_display](#whiteBoard_display)||<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[durationMins](#durationMins)|Duration of the Session in minutes.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[totalNumberOfQuestionsAsked](#totalNumberOfQuestionsAsked)|Total numbers of questions asked on the Session.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[totalNumberOfQuestionsAskedDate](#totalNumberOfQuestionsAskedDate)|Last Updated time of rollup field Total number of questions asked.|<a href="Session.md" target="_blank">eventManagement/Session</a>|
|[totalNumberOfQuestionsAskedState](#totalNumberOfQuestionsAskedState)|State of rollup field Total number of questions asked.|<a href="Session.md" target="_blank">eventManagement/Session</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier for the user that owns the record.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier for the user that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#sessionId name="sessionId">sessionId</a>

Unique identifier for entity instances  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msevtmgt_sessionid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Session  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Session</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Session  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Reason for the status of the Session</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session Title</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_name</td></tr></table>

### <a href=#audienceType name="audienceType">audienceType</a>

Audience Type of the Session.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Audience Type</td></tr><tr><td>description</td><td>Audience Type of the Session.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_audiencetype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>General</td><td>100000000</td></tr><tr><td>en</td><td>Introductory</td><td>100000001</td></tr><tr><td>en</td><td>Intermediate</td><td>100000002</td></tr><tr><td>en</td><td>Advanced</td><td>100000003</td></tr></table></td></tr></table>

### <a href=#audienceType_display name="audienceType_display">audienceType_display</a>

First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#AVSupport name="AVSupport">AVSupport</a>

Audio/Video Support.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>A/V Support</td></tr><tr><td>description</td><td>Audio/Video Support.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_avsupport</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Yes</td><td>100000001</td></tr><tr><td>en</td><td>No</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#AVSupport_display name="AVSupport_display">AVSupport_display</a>

First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#byInvitationOnly name="byInvitationOnly">byInvitationOnly</a>

Is access by invitation only.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>By invitation only</td></tr><tr><td>description</td><td>Is access by invitation only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_byinvitationonly</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Yes</td><td>100000001</td></tr><tr><td>en</td><td>No</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#byInvitationOnly_display name="byInvitationOnly_display">byInvitationOnly_display</a>

First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#camerasPermitted name="camerasPermitted">camerasPermitted</a>

Are cameras permitted.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cameras permitted</td></tr><tr><td>description</td><td>Are cameras permitted.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_cameraspermitted</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Yes</td><td>100000001</td></tr><tr><td>en</td><td>No</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#camerasPermitted_display name="camerasPermitted_display">camerasPermitted_display</a>

First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#checkInCount name="checkInCount">checkInCount</a>

Check-in count  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Check-in count</td></tr><tr><td>description</td><td>Check-in count</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_checkincount</td></tr></table>

### <a href=#detailedDescription name="detailedDescription">detailedDescription</a>

Detailed description of the Session.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Detailed Description</td></tr><tr><td>description</td><td>Detailed description of the Session.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_detaileddescription</td></tr></table>

### <a href=#endTime name="endTime">endTime</a>

End time of the Session.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End Time</td></tr><tr><td>description</td><td>End time of the Session.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_endtime</td></tr></table>

### <a href=#event name="event">event</a>

Unique identifier for Event associated with Event Session.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event</td></tr><tr><td>description</td><td>Unique identifier for Event associated with Event Session.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_event</td></tr></table>

### <a href=#eventSpeakerId name="eventSpeakerId">eventSpeakerId</a>

Unique identifier for Speaker associated with Session.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event Speaker</td></tr><tr><td>description</td><td>Unique identifier for Speaker associated with Session.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_eventspeakerid</td></tr></table>

### <a href=#externalUrl name="externalUrl">externalUrl</a>

External url for the Session.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session Url</td></tr><tr><td>description</td><td>External url for the Session.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_externalurl</td></tr></table>

### <a href=#flipChart name="flipChart">flipChart</a>

Is available flip-chart for the Session.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Flip-Chart</td></tr><tr><td>description</td><td>Is available flip-chart for the Session.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_flipchart</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Yes</td><td>100000001</td></tr><tr><td>en</td><td>No</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#flipChart_display name="flipChart_display">flipChart_display</a>

First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#industry name="industry">industry</a>

Industry of the Session.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Industry</td></tr><tr><td>description</td><td>Industry of the Session.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_industry</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Architecture and Engineering</td><td>100000000</td></tr><tr><td>en</td><td>Financial Services</td><td>100000001</td></tr><tr><td>en</td><td>Manufacturing</td><td>100000002</td></tr><tr><td>en</td><td>Media, Entertainment</td><td>100000003</td></tr><tr><td>en</td><td>Professional Services</td><td>100000004</td></tr><tr><td>en</td><td>Public Sector</td><td>100000005</td></tr><tr><td>en</td><td>Retail</td><td>100000006</td></tr><tr><td>en</td><td>Wholesale and Distribution</td><td>100000007</td></tr><tr><td>en</td><td>Other</td><td>100000008</td></tr></table></td></tr></table>

### <a href=#industry_display name="industry_display">industry_display</a>

First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#internetConnection name="internetConnection">internetConnection</a>

Are internet connections available.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Internet Connection</td></tr><tr><td>description</td><td>Are internet connections available.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_internetconnection</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Yes</td><td>100000001</td></tr><tr><td>en</td><td>No</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#internetConnection_display name="internetConnection_display">internetConnection_display</a>

First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#keywords name="keywords">keywords</a>

Comma-delimited keyword list for this session  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Keywords</td></tr><tr><td>description</td><td>Comma-delimited keyword list for this session</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_keywords</td></tr></table>

### <a href=#language name="language">language</a>

The language of the webinar  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Language</td></tr><tr><td>description</td><td>The language of the webinar</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_language</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>English</td><td>100000000</td></tr><tr><td>en</td><td>French</td><td>100000001</td></tr><tr><td>en</td><td>German</td><td>100000002</td></tr><tr><td>en</td><td>Spanish</td><td>100000003</td></tr><tr><td>en</td><td>Italian</td><td>100000004</td></tr><tr><td>en</td><td>Russian</td><td>100000005</td></tr><tr><td>en</td><td>Dutch</td><td>100000006</td></tr><tr><td>en</td><td>Turkish</td><td>100000007</td></tr><tr><td>en</td><td>Portuguese</td><td>100000008</td></tr><tr><td>en</td><td>Chinese (Simplified)</td><td>100000009</td></tr><tr><td>en</td><td>Chinese (Traditional)</td><td>100000013</td></tr><tr><td>en</td><td>Japanese</td><td>100000010</td></tr><tr><td>en</td><td>Korean</td><td>100000011</td></tr><tr><td>en</td><td>Hebrew</td><td>100000012</td></tr></table></td></tr></table>

### <a href=#language_display name="language_display">language_display</a>

First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#NDA name="NDA">NDA</a>

Non Disclosure Agreement  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>NDA</td></tr><tr><td>description</td><td>Non Disclosure Agreement</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_nda</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Yes</td><td>100000001</td></tr><tr><td>en</td><td>No</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#NDA_display name="NDA_display">NDA_display</a>

First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#passSessions name="passSessions">passSessions</a>

Unique identifier for Product associated with Session.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ProductPass Sessions</td></tr><tr><td>description</td><td>Unique identifier for Product associated with Session.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_passsessions</td></tr></table>

### <a href=#presentationManagerUrl name="presentationManagerUrl">presentationManagerUrl</a>

First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Presentation Manager URL</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_presentationmanagerurl</td></tr></table>

### <a href=#producer name="producer">producer</a>

Producer of the session  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Producer</td></tr><tr><td>description</td><td>Producer of the session</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_producer</td></tr></table>

### <a href=#publishStatus name="publishStatus">publishStatus</a>

Publish status of the Session  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Publish Status</td></tr><tr><td>description</td><td>Publish status of the Session</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_publishstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Draft</td><td>100000000</td></tr><tr><td>en</td><td>Ready to publish</td><td>100000001</td></tr><tr><td>en</td><td>In progress</td><td>100000002</td></tr><tr><td>en</td><td>Published</td><td>100000003</td></tr></table></td></tr></table>

### <a href=#publishStatus_display name="publishStatus_display">publishStatus_display</a>

First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#recordingsPermitted name="recordingsPermitted">recordingsPermitted</a>

Are recordings permitted.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recordings permitted</td></tr><tr><td>description</td><td>Are recordings permitted.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_recordingspermitted</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Yes</td><td>100000001</td></tr><tr><td>en</td><td>No</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#recordingsPermitted_display name="recordingsPermitted_display">recordingsPermitted_display</a>

First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#recurrencePattern name="recurrencePattern">recurrencePattern</a>

First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>recurrencepattern</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_recurrencepattern</td></tr></table>

### <a href=#registrationCount name="registrationCount">registrationCount</a>

Registration count of the Session.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Registration count</td></tr><tr><td>description</td><td>Registration count of the Session.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_registrationcount</td></tr></table>

### <a href=#sessionCode name="sessionCode">sessionCode</a>

Code of the Session.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session Code</td></tr><tr><td>description</td><td>Code of the Session.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_sessioncode</td></tr></table>

### <a href=#sessionFormat name="sessionFormat">sessionFormat</a>

First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session Format</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_sessionformat</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>On Site</td><td>100000001</td></tr><tr><td>en</td><td>Webinar</td><td>100000002</td></tr><tr><td>en</td><td>Hybrid</td><td>100000003</td></tr></table></td></tr></table>

### <a href=#sessionFormat_display name="sessionFormat_display">sessionFormat_display</a>

First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#sessionMaxCapacity name="sessionMaxCapacity">sessionMaxCapacity</a>

Maximum capacity of the Session.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session max. capacity</td></tr><tr><td>description</td><td>Maximum capacity of the Session.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_sessionmaxcapacity</td></tr></table>

### <a href=#sessionObjectives name="sessionObjectives">sessionObjectives</a>

Objectives of the Session.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session Objectives</td></tr><tr><td>description</td><td>Objectives of the Session.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_sessionobjectives</td></tr></table>

### <a href=#sessionPreRequisites name="sessionPreRequisites">sessionPreRequisites</a>

Pre-Requisites of the Session.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session Pre-Requisites</td></tr><tr><td>description</td><td>Pre-Requisites of the Session.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_sessionprerequisites</td></tr></table>

### <a href=#sessionSummary name="sessionSummary">sessionSummary</a>

Summary of the Session.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session Summary</td></tr><tr><td>description</td><td>Summary of the Session.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>700</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_sessionsummary</td></tr></table>

### <a href=#sessionType name="sessionType">sessionType</a>

Type of the Session.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session Type</td></tr><tr><td>description</td><td>Type of the Session.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_sessiontype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Keynote</td><td>100000001</td></tr><tr><td>en</td><td>Breakout</td><td>100000004</td></tr><tr><td>en</td><td>General</td><td>100000002</td></tr><tr><td>en</td><td>Hands-on/Lab</td><td>100000000</td></tr><tr><td>en</td><td>Training</td><td>100000005</td></tr><tr><td>en</td><td>Brainstorming</td><td>100000003</td></tr></table></td></tr></table>

### <a href=#sessionType_display name="sessionType_display">sessionType_display</a>

First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#startTime name="startTime">startTime</a>

Start time of the Session.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Time</td></tr><tr><td>description</td><td>Start time of the Session.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_starttime</td></tr></table>

### <a href=#venue name="venue">venue</a>

Active Venue records for this Session.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Venue</td></tr><tr><td>description</td><td>Active Venue records for this Session.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_venue</td></tr></table>

### <a href=#videoConferencing name="videoConferencing">videoConferencing</a>

Is available video conferencing for the Session.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Video Conferencing</td></tr><tr><td>description</td><td>Is available video conferencing for the Session.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_videoconferencing</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Yes</td><td>100000001</td></tr><tr><td>en</td><td>No</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#videoConferencing_display name="videoConferencing_display">videoConferencing_display</a>

First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#webinarConfigurationId name="webinarConfigurationId">webinarConfigurationId</a>

Webinar Configuration  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Webinar Configuration</td></tr><tr><td>description</td><td>Webinar Configuration</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_webinarconfigurationid</td></tr></table>

### <a href=#webinarID name="webinarID">webinarID</a>

Webinar ID of the Session.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Webinar ID</td></tr><tr><td>description</td><td>Webinar ID of the Session.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_webinarid</td></tr></table>

### <a href=#webinarNotificationSeen name="webinarNotificationSeen">webinarNotificationSeen</a>

Whether the webinar notification has been seen or not.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Webinar Notification Seen</td></tr><tr><td>description</td><td>Whether the webinar notification has been seen or not.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_webinarnotificationseen</td></tr></table>

### <a href=#webinarOperation name="webinarOperation">webinarOperation</a>

First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Webinar Operation</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_webinaroperation</td></tr></table>

### <a href=#webinarStatus name="webinarStatus">webinarStatus</a>

First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Webinar Status</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_webinarstatus</td></tr></table>

### <a href=#webinarStatusReason name="webinarStatusReason">webinarStatusReason</a>

First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Webinar Status Reason</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>5000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_webinarstatusreason</td></tr></table>

### <a href=#webinarType name="webinarType">webinarType</a>

First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Webinar Type</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_webinartype</td></tr></table>

### <a href=#webinarURL name="webinarURL">webinarURL</a>

First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Webinar URL</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_webinarurl</td></tr></table>

### <a href=#whiteBoard name="whiteBoard">whiteBoard</a>

Is available white board for the Session.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Whiteboard</td></tr><tr><td>description</td><td>Is available white board for the Session.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_whiteboard</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Yes</td><td>100000001</td></tr><tr><td>en</td><td>No</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#whiteBoard_display name="whiteBoard_display">whiteBoard_display</a>

First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#durationMins name="durationMins">durationMins</a>

Duration of the Session in minutes.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Duration (mins)</td></tr><tr><td>description</td><td>Duration of the Session in minutes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_durationmins</td></tr></table>

### <a href=#totalNumberOfQuestionsAsked name="totalNumberOfQuestionsAsked">totalNumberOfQuestionsAsked</a>

Total numbers of questions asked on the Session.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total number of questions asked</td></tr><tr><td>description</td><td>Total numbers of questions asked on the Session.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_totalnumberofquestionsasked</td></tr></table>

### <a href=#totalNumberOfQuestionsAskedDate name="totalNumberOfQuestionsAskedDate">totalNumberOfQuestionsAskedDate</a>

Last Updated time of rollup field Total number of questions asked.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total number of questions asked (Last Updated On)</td></tr><tr><td>description</td><td>Last Updated time of rollup field Total number of questions asked.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_totalnumberofquestionsasked_date</td></tr></table>

### <a href=#totalNumberOfQuestionsAskedState name="totalNumberOfQuestionsAskedState">totalNumberOfQuestionsAskedState</a>

State of rollup field Total number of questions asked.  
First included in: eventManagement/Session (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total number of questions asked (State)</td></tr><tr><td>description</td><td>State of rollup field Total number of questions asked.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_totalnumberofquestionsasked_state</td></tr></table>
