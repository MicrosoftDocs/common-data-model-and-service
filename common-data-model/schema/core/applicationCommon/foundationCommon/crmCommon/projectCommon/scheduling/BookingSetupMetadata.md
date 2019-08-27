---
title: BookingSetupMetadata - Common Data Model | Microsoft Docs
description: This describes the BookingSetupMetadata entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Booking Setup Metadata

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/scheduling/BookingSetupMetadata.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/scheduling/BookingSetupMetadata  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[ownerId](#ownerId)|Owner Id|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[bookingSetupMetadataId](#bookingSetupMetadataId)|A unique identifier for an entity instance.|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[stateCode](#stateCode)|Status of the Booking Setup Metadata|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[stateCode_display](#stateCode_display)||<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[statusCode](#statusCode)|Reason for the status of the Booking Setup Metadata|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[statusCode_display](#statusCode_display)||<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[entityLogicalName](#entityLogicalName)|The name of the custom entity.|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[availableDurationMinimumPercentage](#availableDurationMinimumPercentage)||<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[bookingRelationshipLogicalName](#bookingRelationshipLogicalName)|A unique identifier that links bookings to a scheduling entity.|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[bookingStatusFieldLogicalName](#bookingStatusFieldLogicalName)|An option set that is used to group and filter statuses.|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[cancelBookingsWhenMoving](#cancelBookingsWhenMoving)|Select whether, when moving open slots to the next day, to leave the old slots and change their status to "Cancel."|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[cloneEntityQuery](#cloneEntityQuery)|Query for retrieving resource requirements for cloning.|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[defaultBookingCanceledStatus](#defaultBookingCanceledStatus)|The default booking canceled status to use when a user can't select a status.|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[defaultBookingCommittedStatus](#defaultBookingCommittedStatus)|The default booking committed status to use when a user can't select a status.|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[defaultBookingDuration](#defaultBookingDuration)|The default booking duration to use when a duration is not provided.|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[defaultRequirementActiveStatus](#defaultRequirementActiveStatus)|The default requirement active status to use when a user can't select a status|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[defaultRequirementCanceledStatus](#defaultRequirementCanceledStatus)|The default requirement canceled status to use when a user can't select a status.|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[defaultRequirementCompletedStatus](#defaultRequirementCompletedStatus)|The default requirement completed status to use when a user can't select a status.|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[disableRequirementAutoCreation](#disableRequirementAutoCreation)||<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[requirementRelationshipLogicalName](#requirementRelationshipLogicalName)|A unique identifier that links requirements to an enabled scheduling entity.|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[resourceAvailabilityRetrievalLimit](#resourceAvailabilityRetrievalLimit)|The maximum number of resources to retrieve and show in schedule assistant.|<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[retrieveConstraintsQuery](#retrieveConstraintsQuery)||<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|
|[retrieveResourcesQuery](#retrieveResourcesQuery)||<a href="BookingSetupMetadata.md" target="_blank">scheduling/BookingSetupMetadata</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#bookingSetupMetadataId name="bookingSetupMetadataId">bookingSetupMetadataId</a>

A unique identifier for an entity instance.  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Booking Setup Metadata</td></tr><tr><td>description</td><td>A unique identifier for an entity instance.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_bookingsetupmetadataid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Booking Setup Metadata  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Booking Setup Metadata</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Booking Setup Metadata  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Booking Setup Metadata</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#entityLogicalName name="entityLogicalName">entityLogicalName</a>

The name of the custom entity.  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Entity Logical Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>450</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_entitylogicalname</td></tr></table>

### <a href=#availableDurationMinimumPercentage name="availableDurationMinimumPercentage">availableDurationMinimumPercentage</a>

First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Available Duration Minimum(%)</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>100</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_availabledurationminimumpercentage</td></tr></table>

### <a href=#bookingRelationshipLogicalName name="bookingRelationshipLogicalName">bookingRelationshipLogicalName</a>

A unique identifier that links bookings to a scheduling entity.  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Booking Relationship Logical Name</td></tr><tr><td>description</td><td>A unique identifier that links bookings to a scheduling entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>450</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_bookingrelationshiplogicalname</td></tr></table>

### <a href=#bookingStatusFieldLogicalName name="bookingStatusFieldLogicalName">bookingStatusFieldLogicalName</a>

An option set that is used to group and filter statuses.  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Booking Status Field Logical Name</td></tr><tr><td>description</td><td>An option set that is used to group and filter statuses.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>450</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_bookingstatusfieldlogicalname</td></tr></table>

### <a href=#cancelBookingsWhenMoving name="cancelBookingsWhenMoving">cancelBookingsWhenMoving</a>

Select whether, when moving open slots to the next day, to leave the old slots and change their status to "Cancel."  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cancel Bookings When Moving</td></tr><tr><td>description</td><td>Select whether, when moving open slots to the next day, to leave the old slots and change their status to "Cancel."</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_cancelbookingswhenmoving</td></tr></table>

### <a href=#cloneEntityQuery name="cloneEntityQuery">cloneEntityQuery</a>

Query for retrieving resource requirements for cloning.  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Clone Entity Query</td></tr><tr><td>description</td><td>Query for retrieving resource requirements for cloning.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_cloneentityquery</td></tr></table>

### <a href=#defaultBookingCanceledStatus name="defaultBookingCanceledStatus">defaultBookingCanceledStatus</a>

The default booking canceled status to use when a user can't select a status.  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default Booking Canceled Status</td></tr><tr><td>description</td><td>The default booking canceled status to use when a user can't select a status.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_defaultbookingcanceledstatus</td></tr></table>

### <a href=#defaultBookingCommittedStatus name="defaultBookingCommittedStatus">defaultBookingCommittedStatus</a>

The default booking committed status to use when a user can't select a status.  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default Booking Committed Status</td></tr><tr><td>description</td><td>The default booking committed status to use when a user can't select a status.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_defaultbookingcommittedstatus</td></tr></table>

### <a href=#defaultBookingDuration name="defaultBookingDuration">defaultBookingDuration</a>

The default booking duration to use when a duration is not provided.  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default Booking Duration</td></tr><tr><td>description</td><td>The default booking duration to use when a duration is not provided.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_defaultbookingduration</td></tr></table>

### <a href=#defaultRequirementActiveStatus name="defaultRequirementActiveStatus">defaultRequirementActiveStatus</a>

The default requirement active status to use when a user can't select a status  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default Requirement Active Status</td></tr><tr><td>description</td><td>The default requirement active status to use when a user can't select a status</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_defaultrequirementactivestatus</td></tr></table>

### <a href=#defaultRequirementCanceledStatus name="defaultRequirementCanceledStatus">defaultRequirementCanceledStatus</a>

The default requirement canceled status to use when a user can't select a status.  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default Requirement Canceled Status</td></tr><tr><td>description</td><td>The default requirement canceled status to use when a user can't select a status.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_defaultrequirementcanceledstatus</td></tr></table>

### <a href=#defaultRequirementCompletedStatus name="defaultRequirementCompletedStatus">defaultRequirementCompletedStatus</a>

The default requirement completed status to use when a user can't select a status.  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default Requirement Completed Status</td></tr><tr><td>description</td><td>The default requirement completed status to use when a user can't select a status.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_defaultrequirementcompletedstatus</td></tr></table>

### <a href=#disableRequirementAutoCreation name="disableRequirementAutoCreation">disableRequirementAutoCreation</a>

First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Disable Requirement Auto Creation for Bookings</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_disablerequirementautocreation</td></tr></table>

### <a href=#requirementRelationshipLogicalName name="requirementRelationshipLogicalName">requirementRelationshipLogicalName</a>

A unique identifier that links requirements to an enabled scheduling entity.  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requirement Relationship Logical Name</td></tr><tr><td>description</td><td>A unique identifier that links requirements to an enabled scheduling entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>450</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_requirementrelationshiplogicalname</td></tr></table>

### <a href=#resourceAvailabilityRetrievalLimit name="resourceAvailabilityRetrievalLimit">resourceAvailabilityRetrievalLimit</a>

The maximum number of resources to retrieve and show in schedule assistant.  
First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource Availability Retrieval Limit</td></tr><tr><td>description</td><td>The maximum number of resources to retrieve and show in schedule assistant.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourceavailabilityretrievallimit</td></tr></table>

### <a href=#retrieveConstraintsQuery name="retrieveConstraintsQuery">retrieveConstraintsQuery</a>

First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Retrieve Constraints Query</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_retrieveconstraintsquery</td></tr></table>

### <a href=#retrieveResourcesQuery name="retrieveResourcesQuery">retrieveResourcesQuery</a>

First included in: scheduling/BookingSetupMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Retrieve Resources Query</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_retrieveresourcesquery</td></tr></table>
