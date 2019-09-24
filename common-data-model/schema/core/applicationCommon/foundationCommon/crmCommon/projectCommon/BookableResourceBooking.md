---
title: BookableResourceBooking - Common Data Model | Microsoft Docs
description: Represents the line details of a resource booking.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Bookable Resource Booking

Represents the line details of a resource booking.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/BookableResourceBooking.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- [/foundationCommon/BookableResourceBooking](../../BookableResourceBooking.md "/core/applicationCommon/foundationCommon/BookableResourceBooking.cdm.json/BookableResourceBooking")  
- /foundationCommon/crmCommon/projectCommon/BookableResourceBooking  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[ownerId](#ownerId)|Owner Id|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[bookableResourceBookingId](#bookableResourceBookingId)|Unique identifier of the resource booking.|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[name](#name)|Type a name for the booking.|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[processId](#processId)|Contains the id of the process associated with the entity.|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[stageId](#stageId)|Contains the id of the stage where the entity is located.|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[traversedPath](#traversedPath)|A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[bookingStatus](#bookingStatus)|Select the status of the booking.|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[bookingType](#bookingType)|Select whether the booking is solid or liquid. Solid bookings are firm and cannot be changed whereas liquid bookings can be changed.|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[bookingType_display](#bookingType_display)||<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[duration](#duration)|Enter the duration of the booking.|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[endTime](#endTime)|Enter the end date and time of the booking.|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[header](#header)|Shows the reference to the booking header record that represents the summary of bookings.|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[resource](#resource)|Shows the resource that is booked.|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[startTime](#startTime)|Enter the start date and time of the booking.|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[stateCode](#stateCode)|Status of the Bookable Resource Booking|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[stateCode_display](#stateCode_display)||<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[statusCode](#statusCode)|Reason for the status of the Bookable Resource Booking|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[statusCode_display](#statusCode_display)||<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the bookableresourcebooking with respect to the base currency.|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Exchange rate for the currency associated with the BookableResourceBooking with respect to the base currency.|<a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>|
|[actualArrivalTime](#actualArrivalTime)|Shows the time that work started.|<a href="BookableResourceBooking.md" target="_blank">projectCommon/BookableResourceBooking</a>|
|[actualTravelDuration](#actualTravelDuration)|Shows the total travel duration. If you leave this field blank the system automatically determines the travel duration by calculating the resource journal details.|<a href="BookableResourceBooking.md" target="_blank">projectCommon/BookableResourceBooking</a>|
|[allowOverlapping](#allowOverlapping)|Allow the time of this booking to be displayed on the schedule assistant as available.|<a href="BookableResourceBooking.md" target="_blank">projectCommon/BookableResourceBooking</a>|
|[appointmentBookingId](#appointmentBookingId)|Unique identifier for Appointment associated with Bookable Resource Booking.|<a href="BookableResourceBooking.md" target="_blank">projectCommon/BookableResourceBooking</a>|
|[bookingMethod](#bookingMethod)|Shows the method used to create this booking.|<a href="BookableResourceBooking.md" target="_blank">projectCommon/BookableResourceBooking</a>|
|[bookingMethod_display](#bookingMethod_display)||<a href="BookableResourceBooking.md" target="_blank">projectCommon/BookableResourceBooking</a>|
|[bookingSetupMetadataId](#bookingSetupMetadataId)|A unique identifier for the booking setup metadata that is associated with a bookable resource booking.|<a href="BookableResourceBooking.md" target="_blank">projectCommon/BookableResourceBooking</a>|
|[cascadeCrewChanges](#cascadeCrewChanges)|Defines whether changing any of the following fields (Start Time, End Time, Status) should cascade the changes to other bookings on this requirement that have the same start and end time.|<a href="BookableResourceBooking.md" target="_blank">projectCommon/BookableResourceBooking</a>|
|[acceptCascadeCrewChanges](#acceptCascadeCrewChanges)|Defines whether this booking accepts changes propagated as cascading changes|<a href="BookableResourceBooking.md" target="_blank">projectCommon/BookableResourceBooking</a>|
|[effort](#effort)|Capacity that needs to take from resource capacity|<a href="BookableResourceBooking.md" target="_blank">projectCommon/BookableResourceBooking</a>|
|[estimatedArrivalTime](#estimatedArrivalTime)|Estimated Arrival Time|<a href="BookableResourceBooking.md" target="_blank">projectCommon/BookableResourceBooking</a>|
|[estimatedTravelDuration](#estimatedTravelDuration)|Estimated Travel Duration|<a href="BookableResourceBooking.md" target="_blank">projectCommon/BookableResourceBooking</a>|
|[latitude](#latitude)||<a href="BookableResourceBooking.md" target="_blank">projectCommon/BookableResourceBooking</a>|
|[longitude](#longitude)||<a href="BookableResourceBooking.md" target="_blank">projectCommon/BookableResourceBooking</a>|
|[milesTraveled](#milesTraveled)|In this field you can enter the total miles the resource drove to the job site|<a href="BookableResourceBooking.md" target="_blank">projectCommon/BookableResourceBooking</a>|
|[requirementGroup](#requirementGroup)|Requirement Group|<a href="BookableResourceBooking.md" target="_blank">projectCommon/BookableResourceBooking</a>|
|[resourceGroup](#resourceGroup)|Unique identifier for Resource associated with Resource Booking|<a href="BookableResourceBooking.md" target="_blank">projectCommon/BookableResourceBooking</a>|
|[resourceRequirement](#resourceRequirement)|Resource Requirement|<a href="BookableResourceBooking.md" target="_blank">projectCommon/BookableResourceBooking</a>|
|[timeGroupDetailSelected](#timeGroupDetailSelected)||<a href="BookableResourceBooking.md" target="_blank">projectCommon/BookableResourceBooking</a>|
|[workLocation](#workLocation)||<a href="BookableResourceBooking.md" target="_blank">projectCommon/BookableResourceBooking</a>|
|[workLocation_display](#workLocation_display)||<a href="BookableResourceBooking.md" target="_blank">projectCommon/BookableResourceBooking</a>|
|[projectId](#projectId)|Project of booking detail record|<a href="BookableResourceBooking.md" target="_blank">projectCommon/BookableResourceBooking</a>|
|[projectTeamId](#projectTeamId)|Project team member of booking detail record|<a href="BookableResourceBooking.md" target="_blank">projectCommon/BookableResourceBooking</a>|
|[resourceCategoryId](#resourceCategoryId)|Resource Category|<a href="BookableResourceBooking.md" target="_blank">projectCommon/BookableResourceBooking</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#bookableResourceBookingId name="bookableResourceBookingId">bookableResourceBookingId</a>

Unique identifier of the resource booking.  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bookable Resource Booking</td></tr><tr><td>description</td><td>Unique identifier of the resource booking.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>bookableresourcebookingid</td></tr></table>

### <a href=#name name="name">name</a>

Type a name for the booking.  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type a name for the booking.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#processId name="processId">processId</a>

Contains the id of the process associated with the entity.  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Id</td></tr><tr><td>description</td><td>Contains the id of the process associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Contains the id of the stage where the entity is located.  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stage Id</td></tr><tr><td>description</td><td>Contains the id of the stage where the entity is located.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#bookingStatus name="bookingStatus">bookingStatus</a>

Select the status of the booking.  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Booking Status</td></tr><tr><td>description</td><td>Select the status of the booking.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>bookingstatus</td></tr></table>

### <a href=#bookingType name="bookingType">bookingType</a>

Select whether the booking is solid or liquid. Solid bookings are firm and cannot be changed whereas liquid bookings can be changed.  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Booking Type</td></tr><tr><td>description</td><td>Select whether the booking is solid or liquid. Solid bookings are firm and cannot be changed whereas liquid bookings can be changed.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>bookingtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Liquid</td><td>2</td></tr><tr><td>en</td><td>Solid</td><td>1</td></tr></table></td></tr></table>

### <a href=#bookingType_display name="bookingType_display">bookingType_display</a>

First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#duration name="duration">duration</a>

Enter the duration of the booking.  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Duration</td></tr><tr><td>description</td><td>Enter the duration of the booking.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>duration</td></tr></table>

### <a href=#endTime name="endTime">endTime</a>

Enter the end date and time of the booking.  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End Time</td></tr><tr><td>description</td><td>Enter the end date and time of the booking.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>endtime</td></tr></table>

### <a href=#header name="header">header</a>

Shows the reference to the booking header record that represents the summary of bookings.  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Header</td></tr><tr><td>description</td><td>Shows the reference to the booking header record that represents the summary of bookings.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>header</td></tr></table>

### <a href=#resource name="resource">resource</a>

Shows the resource that is booked.  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource</td></tr><tr><td>description</td><td>Shows the resource that is booked.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>resource</td></tr></table>

### <a href=#startTime name="startTime">startTime</a>

Enter the start date and time of the booking.  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Time</td></tr><tr><td>description</td><td>Enter the start date and time of the booking.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>starttime</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Bookable Resource Booking  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Bookable Resource Booking</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Bookable Resource Booking  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Bookable Resource Booking</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the bookableresourcebooking with respect to the base currency.  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ExchangeRate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the bookableresourcebooking with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Exchange rate for the currency associated with the BookableResourceBooking with respect to the base currency.  
First included in: <a href="../../BookableResourceBooking.md" target="_blank">foundationCommon/BookableResourceBooking</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the BookableResourceBooking with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#actualArrivalTime name="actualArrivalTime">actualArrivalTime</a>

Shows the time that work started.  
First included in: projectCommon/BookableResourceBooking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Arrival Time</td></tr><tr><td>description</td><td>Shows the time that work started.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actualarrivaltime</td></tr></table>

### <a href=#actualTravelDuration name="actualTravelDuration">actualTravelDuration</a>

Shows the total travel duration. If you leave this field blank the system automatically determines the travel duration by calculating the resource journal details.  
First included in: projectCommon/BookableResourceBooking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Travel Duration</td></tr><tr><td>description</td><td>Shows the total travel duration. If you leave this field blank the system automatically determines the travel duration by calculating the resource journal details.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actualtravelduration</td></tr></table>

### <a href=#allowOverlapping name="allowOverlapping">allowOverlapping</a>

Allow the time of this booking to be displayed on the schedule assistant as available.  
First included in: projectCommon/BookableResourceBooking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow Overlapping</td></tr><tr><td>description</td><td>Allow the time of this booking to be displayed on the schedule assistant as available.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_allowoverlapping</td></tr></table>

### <a href=#appointmentBookingId name="appointmentBookingId">appointmentBookingId</a>

Unique identifier for Appointment associated with Bookable Resource Booking.  
First included in: projectCommon/BookableResourceBooking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Appointment Booking</td></tr><tr><td>description</td><td>Unique identifier for Appointment associated with Bookable Resource Booking.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_appointmentbookingid</td></tr></table>

### <a href=#bookingMethod name="bookingMethod">bookingMethod</a>

Shows the method used to create this booking.  
First included in: projectCommon/BookableResourceBooking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Booking Method</td></tr><tr><td>description</td><td>Shows the method used to create this booking.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_bookingmethod</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Schedule Board</td><td>690970001</td></tr><tr><td>en</td><td>Mobile</td><td>690970002</td></tr><tr><td>en</td><td>Manual</td><td>690970003</td></tr><tr><td>en</td><td>Schedule Assistant</td><td>690970004</td></tr></table></td></tr></table>

### <a href=#bookingMethod_display name="bookingMethod_display">bookingMethod_display</a>

First included in: projectCommon/BookableResourceBooking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#bookingSetupMetadataId name="bookingSetupMetadataId">bookingSetupMetadataId</a>

A unique identifier for the booking setup metadata that is associated with a bookable resource booking.  
First included in: projectCommon/BookableResourceBooking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Booking Setup Metadata</td></tr><tr><td>description</td><td>A unique identifier for the booking setup metadata that is associated with a bookable resource booking.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_bookingsetupmetadataid</td></tr></table>

### <a href=#cascadeCrewChanges name="cascadeCrewChanges">cascadeCrewChanges</a>

Defines whether changing any of the following fields (Start Time, End Time, Status) should cascade the changes to other bookings on this requirement that have the same start and end time.  
First included in: projectCommon/BookableResourceBooking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cascade Crew Changes</td></tr><tr><td>description</td><td>Defines whether changing any of the following fields (Start Time, End Time, Status) should cascade the changes to other bookings on this requirement that have the same start and end time.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_cascadecrewchanges</td></tr></table>

### <a href=#acceptCascadeCrewChanges name="acceptCascadeCrewChanges">acceptCascadeCrewChanges</a>

Defines whether this booking accepts changes propagated as cascading changes  
First included in: projectCommon/BookableResourceBooking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accept Cascade Crew Changes</td></tr><tr><td>description</td><td>Defines whether this booking accepts changes propagated as cascading changes</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_acceptcascadecrewchanges</td></tr></table>

### <a href=#effort name="effort">effort</a>

Capacity that needs to take from resource capacity  
First included in: projectCommon/BookableResourceBooking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Capacity</td></tr><tr><td>description</td><td>Capacity that needs to take from resource capacity</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0.0001</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_effort</td></tr></table>

### <a href=#estimatedArrivalTime name="estimatedArrivalTime">estimatedArrivalTime</a>

Estimated Arrival Time  
First included in: projectCommon/BookableResourceBooking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Arrival Time</td></tr><tr><td>description</td><td>Estimated Arrival Time</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estimatedarrivaltime</td></tr></table>

### <a href=#estimatedTravelDuration name="estimatedTravelDuration">estimatedTravelDuration</a>

Estimated Travel Duration  
First included in: projectCommon/BookableResourceBooking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Travel Duration</td></tr><tr><td>description</td><td>Estimated Travel Duration</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estimatedtravelduration</td></tr></table>

### <a href=#latitude name="latitude">latitude</a>

First included in: projectCommon/BookableResourceBooking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Latitude</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>90</td></tr><tr><td>minimumValue</td><td>-90</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_latitude</td></tr></table>

### <a href=#longitude name="longitude">longitude</a>

First included in: projectCommon/BookableResourceBooking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Longitude</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>180</td></tr><tr><td>minimumValue</td><td>-180</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_longitude</td></tr></table>

### <a href=#milesTraveled name="milesTraveled">milesTraveled</a>

In this field you can enter the total miles the resource drove to the job site  
First included in: projectCommon/BookableResourceBooking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Miles Traveled</td></tr><tr><td>description</td><td>In this field you can enter the total miles the resource drove to the job site</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_milestraveled</td></tr></table>

### <a href=#requirementGroup name="requirementGroup">requirementGroup</a>

Requirement Group  
First included in: projectCommon/BookableResourceBooking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requirement Group</td></tr><tr><td>description</td><td>Requirement Group</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_requirementgroupid</td></tr></table>

### <a href=#resourceGroup name="resourceGroup">resourceGroup</a>

Unique identifier for Resource associated with Resource Booking  
First included in: projectCommon/BookableResourceBooking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource Group</td></tr><tr><td>description</td><td>Unique identifier for Resource associated with Resource Booking</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourcegroup</td></tr></table>

### <a href=#resourceRequirement name="resourceRequirement">resourceRequirement</a>

Resource Requirement  
First included in: projectCommon/BookableResourceBooking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource Requirement</td></tr><tr><td>description</td><td>Resource Requirement</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourcerequirement</td></tr></table>

### <a href=#timeGroupDetailSelected name="timeGroupDetailSelected">timeGroupDetailSelected</a>

First included in: projectCommon/BookableResourceBooking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Group Detail Selected</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_timegroupdetailselected</td></tr></table>

### <a href=#workLocation name="workLocation">workLocation</a>

First included in: projectCommon/BookableResourceBooking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Work Location</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_worklocation</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Onsite</td><td>690970000</td></tr><tr><td>en</td><td>Facility</td><td>690970001</td></tr><tr><td>en</td><td>Location Agnostic</td><td>690970002</td></tr></table></td></tr></table>

### <a href=#workLocation_display name="workLocation_display">workLocation_display</a>

First included in: projectCommon/BookableResourceBooking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#projectId name="projectId">projectId</a>

Project of booking detail record  
First included in: projectCommon/BookableResourceBooking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project</td></tr><tr><td>description</td><td>Project of booking detail record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_projectid</td></tr></table>

### <a href=#projectTeamId name="projectTeamId">projectTeamId</a>

Project team member of booking detail record  
First included in: projectCommon/BookableResourceBooking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Team Member</td></tr><tr><td>description</td><td>Project team member of booking detail record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_projectteamid</td></tr></table>

### <a href=#resourceCategoryId name="resourceCategoryId">resourceCategoryId</a>

Resource Category  
First included in: projectCommon/BookableResourceBooking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource Category</td></tr><tr><td>description</td><td>Resource Category</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourcecategoryid</td></tr></table>
