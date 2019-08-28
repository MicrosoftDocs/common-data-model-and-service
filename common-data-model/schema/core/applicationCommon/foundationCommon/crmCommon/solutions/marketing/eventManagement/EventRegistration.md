---
title: EventRegistration - Common Data Model | Microsoft Docs
description: This describes the EventRegistration entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Event Registration

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/eventManagement/EventRegistration.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/eventManagement/EventRegistration  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[ownerId](#ownerId)|Owner Id|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[eventRegistrationId](#eventRegistrationId)|Unique identifier for entity instances|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[stateCode](#stateCode)|Status of the Event Registration|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[stateCode_display](#stateCode_display)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[statusCode](#statusCode)|Reason for the status of the Event Registration|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[statusCode_display](#statusCode_display)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[name](#name)|The name of the custom entity.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[area](#area)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[area_display](#area_display)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[companySize](#companySize)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[companySize_display](#companySize_display)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[contactId](#contactId)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[eventId](#eventId)|Unique identifier for Event associated with Event Registration.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[industry](#industry)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[industry_display](#industry_display)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[isCanceled](#isCanceled)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[memo](#memo)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[primaryRole](#primaryRole)|Primary Role of the event attendee.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[primaryRole_display](#primaryRole_display)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[publishingState](#publishingState)|The publishing state of the event registration.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[publishingState_display](#publishingState_display)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[registeredBy](#registeredBy)|A lookup to the contact who created this event registration|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[registrationNotificationSeen](#registrationNotificationSeen)|Whether the registration creation notification has been seen or not|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[registrationStatus](#registrationStatus)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[syncedWithProvider](#syncedWithProvider)|A flag that indicates that the registration was synced with provider|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[syncedWithProvider_display](#syncedWithProvider_display)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[timesCheckedIn](#timesCheckedIn)|Hidden field. Number of Event Check-ins related to this ER.
Used as partial aggregation for Check-in count of Event.
Increasing and decreasing done by corresponding workflows.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[webinarRegistrationID](#webinarRegistrationID)|Webinar ID of the Event Registration.|<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[yearsInIndustry](#yearsInIndustry)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|
|[yearsInIndustry_display](#yearsInIndustry_display)||<a href="EventRegistration.md" target="_blank">eventManagement/EventRegistration</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#eventRegistrationId name="eventRegistrationId">eventRegistrationId</a>

Unique identifier for entity instances  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event Registration</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msevtmgt_eventregistrationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Event Registration  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Event Registration</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Event Registration  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Event Registration</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Registration ID</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_name</td></tr></table>

### <a href=#area name="area">area</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Area</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_area</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Administration</td><td>100000000</td></tr><tr><td>en</td><td>Customer Service</td><td>100000001</td></tr><tr><td>en</td><td>Executive/Management</td><td>100000002</td></tr><tr><td>en</td><td>Logistics</td><td>100000003</td></tr><tr><td>en</td><td>Finance</td><td>100000004</td></tr><tr><td>en</td><td>HR</td><td>100000005</td></tr><tr><td>en</td><td>IT</td><td>100000006</td></tr><tr><td>en</td><td>Legal</td><td>100000007</td></tr><tr><td>en</td><td>Marketing</td><td>100000008</td></tr><tr><td>en</td><td>Sales</td><td>100000009</td></tr></table></td></tr></table>

### <a href=#area_display name="area_display">area_display</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#companySize name="companySize">companySize</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Company Size</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_companysize</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>50 or less</td><td>100000000</td></tr><tr><td>en</td><td>51 to 100</td><td>100000001</td></tr><tr><td>en</td><td>101 to 250</td><td>100000002</td></tr><tr><td>en</td><td>251 to 500</td><td>100000003</td></tr><tr><td>en</td><td>501 to 1000</td><td>100000004</td></tr><tr><td>en</td><td>1001 to 2500</td><td>100000005</td></tr><tr><td>en</td><td>2501 to 5000</td><td>100000006</td></tr><tr><td>en</td><td>5001 to 10000</td><td>100000007</td></tr><tr><td>en</td><td>10001 or more</td><td>100000008</td></tr></table></td></tr></table>

### <a href=#companySize_display name="companySize_display">companySize_display</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#contactId name="contactId">contactId</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_contactid</td></tr></table>

### <a href=#eventId name="eventId">eventId</a>

Unique identifier for Event associated with Event Registration.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event</td></tr><tr><td>description</td><td>Unique identifier for Event associated with Event Registration.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_eventid</td></tr></table>

### <a href=#industry name="industry">industry</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Industry</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_industry</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Architecture and Engineering</td><td>100000000</td></tr><tr><td>en</td><td>Financial Services</td><td>100000001</td></tr><tr><td>en</td><td>Manufacturing</td><td>100000002</td></tr><tr><td>en</td><td>Media, Entertainment</td><td>100000003</td></tr><tr><td>en</td><td>Professional Services</td><td>100000004</td></tr><tr><td>en</td><td>Public Sector</td><td>100000005</td></tr><tr><td>en</td><td>Retail</td><td>100000006</td></tr><tr><td>en</td><td>Wholesale and Distribution</td><td>100000007</td></tr><tr><td>en</td><td>Other</td><td>100000008</td></tr></table></td></tr></table>

### <a href=#industry_display name="industry_display">industry_display</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#isCanceled name="isCanceled">isCanceled</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Canceled</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_iscanceled</td></tr></table>

### <a href=#memo name="memo">memo</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Memo</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_memo</td></tr></table>

### <a href=#primaryRole name="primaryRole">primaryRole</a>

Primary Role of the event attendee.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary Role</td></tr><tr><td>description</td><td>Primary Role of the event attendee.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_primaryrole</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Attendee</td><td>100000000</td></tr><tr><td>en</td><td>Journalist</td><td>100000001</td></tr><tr><td>en</td><td>Other</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#primaryRole_display name="primaryRole_display">primaryRole_display</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#publishingState name="publishingState">publishingState</a>

The publishing state of the event registration.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Publishing State</td></tr><tr><td>description</td><td>The publishing state of the event registration.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_publishingstate</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Pending</td><td>100000000</td></tr><tr><td>en</td><td>Published</td><td>100000001</td></tr><tr><td>en</td><td>ParentWebinarFailed</td><td>100000002</td></tr><tr><td>en</td><td>FailedToPublish</td><td>100000003</td></tr><tr><td>en</td><td>WebinarProviderError</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#publishingState_display name="publishingState_display">publishingState_display</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#registeredBy name="registeredBy">registeredBy</a>

A lookup to the contact who created this event registration  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Registered By</td></tr><tr><td>description</td><td>A lookup to the contact who created this event registration</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_registeredby</td></tr></table>

### <a href=#registrationNotificationSeen name="registrationNotificationSeen">registrationNotificationSeen</a>

Whether the registration creation notification has been seen or not  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Registration Notification Seen</td></tr><tr><td>description</td><td>Whether the registration creation notification has been seen or not</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_registrationnotificationseen</td></tr></table>

### <a href=#registrationStatus name="registrationStatus">registrationStatus</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Registration Status</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_registrationstatus</td></tr></table>

### <a href=#syncedWithProvider name="syncedWithProvider">syncedWithProvider</a>

A flag that indicates that the registration was synced with provider  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Synced with Provider</td></tr><tr><td>description</td><td>A flag that indicates that the registration was synced with provider</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_syncedwithprovider</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>No</td><td>100000001</td></tr><tr><td>en</td><td>Yes</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#syncedWithProvider_display name="syncedWithProvider_display">syncedWithProvider_display</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#timesCheckedIn name="timesCheckedIn">timesCheckedIn</a>

Hidden field. Number of Event Check-ins related to this ER.
Used as partial aggregation for Check-in count of Event.
Increasing and decreasing done by corresponding workflows.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Times Checked-in</td></tr><tr><td>description</td><td>Hidden field. Number of Event Check-ins related to this ER.
Used as partial aggregation for Check-in count of Event.
Increasing and decreasing done by corresponding workflows.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_timescheckedin</td></tr></table>

### <a href=#webinarRegistrationID name="webinarRegistrationID">webinarRegistrationID</a>

Webinar ID of the Event Registration.  
First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Webinar Registration ID</td></tr><tr><td>description</td><td>Webinar ID of the Event Registration.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_webinarregistrationid</td></tr></table>

### <a href=#yearsInIndustry name="yearsInIndustry">yearsInIndustry</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Years in Industry</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_yearsinindustry</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Under 1 year</td><td>100000000</td></tr><tr><td>en</td><td>1 to 5 year</td><td>100000001</td></tr><tr><td>en</td><td>5 to 10 years</td><td>100000002</td></tr><tr><td>en</td><td>Over 10 years</td><td>100000003</td></tr></table></td></tr></table>

### <a href=#yearsInIndustry_display name="yearsInIndustry_display">yearsInIndustry_display</a>

First included in: eventManagement/EventRegistration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
