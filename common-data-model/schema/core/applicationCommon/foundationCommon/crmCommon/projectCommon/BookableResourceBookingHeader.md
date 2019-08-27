---
title: BookableResourceBookingHeader - Common Data Model | Microsoft Docs
description: Reservation entity representing the summary of the associated resource bookings.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Bookable Resource Booking Header

Reservation entity representing the summary of the associated resource bookings.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/BookableResourceBookingHeader.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- [/foundationCommon/BookableResourceBookingHeader](../../BookableResourceBookingHeader.md "/core/applicationCommon/foundationCommon/BookableResourceBookingHeader.cdm.json/BookableResourceBookingHeader")  
- /foundationCommon/crmCommon/projectCommon/BookableResourceBookingHeader  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[ownerId](#ownerId)|Owner Id|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[bookableResourceBookingHeaderId](#bookableResourceBookingHeaderId)|Unique identifier of the resource booking header.|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[name](#name)|The name of the booking summary.|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[processId](#processId)|Contains the id of the process associated with the entity.|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[stageId](#stageId)|Contains the id of the stage where the entity is located.|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[traversedPath](#traversedPath)|A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[duration](#duration)|Shows the aggregate duration of the linked bookings.|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[endTime](#endTime)|Shows the end date and time of the booking summary.|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[startTime](#startTime)|Shows the start date and time of the booking summary.|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[stateCode](#stateCode)|Status of the Bookable Resource Booking Header|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[stateCode_display](#stateCode_display)||<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[statusCode](#statusCode)|Reason for the status of the Bookable Resource Booking Header|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[statusCode_display](#statusCode_display)||<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the bookableresourcebookingheader with respect to the base currency.|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Exchange rate for the currency associated with the BookableResourceBookingHeader with respect to the base currency.|<a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>|
|[bookableResourceId](#bookableResourceId)|Shows the resource.|<a href="BookableResourceBookingHeader.md" target="_blank">projectCommon/BookableResourceBookingHeader</a>|
|[bookingStatusId](#bookingStatusId)|Booking Status|<a href="BookableResourceBookingHeader.md" target="_blank">projectCommon/BookableResourceBookingHeader</a>|
|[bookingType](#bookingType)|Select whether the booking is solid or liquid. Solid bookings are firm and cannot be changed whereas liquid bookings can be changed.|<a href="BookableResourceBookingHeader.md" target="_blank">projectCommon/BookableResourceBookingHeader</a>|
|[bookingType_display](#bookingType_display)||<a href="BookableResourceBookingHeader.md" target="_blank">projectCommon/BookableResourceBookingHeader</a>|
|[resourceRequirement](#resourceRequirement)|Resource Requirement|<a href="BookableResourceBookingHeader.md" target="_blank">projectCommon/BookableResourceBookingHeader</a>|
|[projectId](#projectId)|Project|<a href="BookableResourceBookingHeader.md" target="_blank">projectCommon/BookableResourceBookingHeader</a>|
|[projectTeamId](#projectTeamId)|Project Team|<a href="BookableResourceBookingHeader.md" target="_blank">projectCommon/BookableResourceBookingHeader</a>|
|[resourceCategoryId](#resourceCategoryId)|Resource Category|<a href="BookableResourceBookingHeader.md" target="_blank">projectCommon/BookableResourceBookingHeader</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#bookableResourceBookingHeaderId name="bookableResourceBookingHeaderId">bookableResourceBookingHeaderId</a>

Unique identifier of the resource booking header.  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bookable Resource Booking Header</td></tr><tr><td>description</td><td>Unique identifier of the resource booking header.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>bookableresourcebookingheaderid</td></tr></table>

### <a href=#name name="name">name</a>

The name of the booking summary.  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the booking summary.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#processId name="processId">processId</a>

Contains the id of the process associated with the entity.  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Id</td></tr><tr><td>description</td><td>Contains the id of the process associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Contains the id of the stage where the entity is located.  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stage Id</td></tr><tr><td>description</td><td>Contains the id of the stage where the entity is located.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#duration name="duration">duration</a>

Shows the aggregate duration of the linked bookings.  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Duration</td></tr><tr><td>description</td><td>Shows the aggregate duration of the linked bookings.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>duration</td></tr></table>

### <a href=#endTime name="endTime">endTime</a>

Shows the end date and time of the booking summary.  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End Time</td></tr><tr><td>description</td><td>Shows the end date and time of the booking summary.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>endtime</td></tr></table>

### <a href=#startTime name="startTime">startTime</a>

Shows the start date and time of the booking summary.  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Time</td></tr><tr><td>description</td><td>Shows the start date and time of the booking summary.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>starttime</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Bookable Resource Booking Header  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Bookable Resource Booking Header</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Bookable Resource Booking Header  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Bookable Resource Booking Header</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the bookableresourcebookingheader with respect to the base currency.  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ExchangeRate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the bookableresourcebookingheader with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Exchange rate for the currency associated with the BookableResourceBookingHeader with respect to the base currency.  
First included in: <a href="../../BookableResourceBookingHeader.md" target="_blank">foundationCommon/BookableResourceBookingHeader</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the BookableResourceBookingHeader with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#bookableResourceId name="bookableResourceId">bookableResourceId</a>

Shows the resource.  
First included in: projectCommon/BookableResourceBookingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bookable Resource</td></tr><tr><td>description</td><td>Shows the resource.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_bookableresourceid</td></tr></table>

### <a href=#bookingStatusId name="bookingStatusId">bookingStatusId</a>

Booking Status  
First included in: projectCommon/BookableResourceBookingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Booking Status</td></tr><tr><td>description</td><td>Booking Status</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_bookingstatusid</td></tr></table>

### <a href=#bookingType name="bookingType">bookingType</a>

Select whether the booking is solid or liquid. Solid bookings are firm and cannot be changed whereas liquid bookings can be changed.  
First included in: projectCommon/BookableResourceBookingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Booking Type</td></tr><tr><td>description</td><td>Select whether the booking is solid or liquid. Solid bookings are firm and cannot be changed whereas liquid bookings can be changed.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_bookingtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Solid</td><td>1</td></tr><tr><td>en</td><td>Liquid</td><td>2</td></tr></table></td></tr></table>

### <a href=#bookingType_display name="bookingType_display">bookingType_display</a>

First included in: projectCommon/BookableResourceBookingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#resourceRequirement name="resourceRequirement">resourceRequirement</a>

Resource Requirement  
First included in: projectCommon/BookableResourceBookingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource Requirement</td></tr><tr><td>description</td><td>Resource Requirement</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourcerequirement</td></tr></table>

### <a href=#projectId name="projectId">projectId</a>

Project  
First included in: projectCommon/BookableResourceBookingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project</td></tr><tr><td>description</td><td>Project</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_projectid</td></tr></table>

### <a href=#projectTeamId name="projectTeamId">projectTeamId</a>

Project Team  
First included in: projectCommon/BookableResourceBookingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Team Member</td></tr><tr><td>description</td><td>Project Team</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_projectteamid</td></tr></table>

### <a href=#resourceCategoryId name="resourceCategoryId">resourceCategoryId</a>

Resource Category  
First included in: projectCommon/BookableResourceBookingHeader (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource Category</td></tr><tr><td>description</td><td>Resource Category</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourcecategoryid</td></tr></table>
