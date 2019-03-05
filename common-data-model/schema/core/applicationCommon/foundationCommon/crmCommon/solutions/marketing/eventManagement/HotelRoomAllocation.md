---
title: HotelRoomAllocation - Common Data Model | Microsoft Docs
description: This entity records the number of rooms that are allocated from a single hotel for guests of a single event.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/5/2019
ms.author: nebanfic
---

# Hotel Room Allocation

This entity records the number of rooms that are allocated from a single hotel for guests of a single event.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/eventManagement/HotelRoomAllocation.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/eventManagement/HotelRoomAllocation  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[ownerId](#ownerId)|Owner Id|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[hotelRoomAllocationId](#hotelRoomAllocationId)|Unique identifier for entity instances|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[stateCode](#stateCode)|Status of the Hotel Room Allocation|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[stateCode_display](#stateCode_display)||<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[statusCode](#statusCode)|Reason for the status of the Hotel Room Allocation|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[statusCode_display](#statusCode_display)||<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[name](#name)|The name of the custom entity.|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[additionalDetails](#additionalDetails)|Room allocation additional details|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[event](#event)|Related event|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[hotelProperty](#hotelProperty)|Related hotel property|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[numberOfRoomsAllocated](#numberOfRoomsAllocated)|Number of allocated rooms|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[pricePerRoom](#pricePerRoom)|Price per room|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[pricePerRoomBase](#pricePerRoomBase)|Value of the Price per Room in base currency.|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[primaryContact](#primaryContact)|Primary contact|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[roomType](#roomType)|Room type|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[roomType_display](#roomType_display)||<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[numberOfRoomsLeft](#numberOfRoomsLeft)|Number of rooms left|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[numberofRoomsReserved](#numberofRoomsReserved)|Number of reserved rooms|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[numberofRoomsReservedDate](#numberofRoomsReservedDate)|Last Updated time of rollup field Number of rooms reserved.|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|
|[numberofRoomsReservedState](#numberofRoomsReservedState)|State of rollup field Number of rooms reserved.|<a href="HotelRoomAllocation.md" target="_blank">eventManagement/HotelRoomAllocation</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#hotelRoomAllocationId name="hotelRoomAllocationId">hotelRoomAllocationId</a>

Unique identifier for entity instances  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Hotel Room Allocation</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msevtmgt_hotelroomallocationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Hotel Room Allocation  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Hotel Room Allocation</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Hotel Room Allocation  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Hotel Room Allocation</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_name</td></tr></table>

### <a href=#additionalDetails name="additionalDetails">additionalDetails</a>

Room allocation additional details  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Additional Details</td></tr><tr><td>description</td><td>Room allocation additional details</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_additionaldetails</td></tr></table>

### <a href=#event name="event">event</a>

Related event  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event</td></tr><tr><td>description</td><td>Related event</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_event</td></tr></table>

### <a href=#hotelProperty name="hotelProperty">hotelProperty</a>

Related hotel property  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Hotel/Property</td></tr><tr><td>description</td><td>Related hotel property</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_hotelproperty</td></tr></table>

### <a href=#numberOfRoomsAllocated name="numberOfRoomsAllocated">numberOfRoomsAllocated</a>

Number of allocated rooms  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number of rooms allocated</td></tr><tr><td>description</td><td>Number of allocated rooms</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_numberofroomsallocated</td></tr></table>

### <a href=#pricePerRoom name="pricePerRoom">pricePerRoom</a>

Price per room  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price per room</td></tr><tr><td>description</td><td>Price per room</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_priceperroom</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#pricePerRoomBase name="pricePerRoomBase">pricePerRoomBase</a>

Value of the Price per Room in base currency.  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price per Room (Base)</td></tr><tr><td>description</td><td>Value of the Price per Room in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_priceperroom_base</td></tr></table>

### <a href=#primaryContact name="primaryContact">primaryContact</a>

Primary contact  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary Contact</td></tr><tr><td>description</td><td>Primary contact</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_primarycontact</td></tr></table>

### <a href=#roomType name="roomType">roomType</a>

Room type  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Room Type</td></tr><tr><td>description</td><td>Room type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_roomtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Single Room</td><td>100000000</td></tr><tr><td>en</td><td>Double Room</td><td>100000001</td></tr><tr><td>en</td><td>Junior Suite</td><td>100000002</td></tr><tr><td>en</td><td>Executive Suite</td><td>100000003</td></tr><tr><td>en</td><td>Luxury Suite</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#roomType_display name="roomType_display">roomType_display</a>

First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#numberOfRoomsLeft name="numberOfRoomsLeft">numberOfRoomsLeft</a>

Number of rooms left  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number of rooms left</td></tr><tr><td>description</td><td>Number of rooms left</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_numberofroomsleft</td></tr></table>

### <a href=#numberofRoomsReserved name="numberofRoomsReserved">numberofRoomsReserved</a>

Number of reserved rooms  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number of rooms reserved</td></tr><tr><td>description</td><td>Number of reserved rooms</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_numberofroomsreserved</td></tr></table>

### <a href=#numberofRoomsReservedDate name="numberofRoomsReservedDate">numberofRoomsReservedDate</a>

Last Updated time of rollup field Number of rooms reserved.  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number of rooms reserved (Last Updated On)</td></tr><tr><td>description</td><td>Last Updated time of rollup field Number of rooms reserved.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_numberofroomsreserved_date</td></tr></table>

### <a href=#numberofRoomsReservedState name="numberofRoomsReservedState">numberofRoomsReservedState</a>

State of rollup field Number of rooms reserved.  
First included in: eventManagement/HotelRoomAllocation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number of rooms reserved (State)</td></tr><tr><td>description</td><td>State of rollup field Number of rooms reserved.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_numberofroomsreserved_state</td></tr></table>
