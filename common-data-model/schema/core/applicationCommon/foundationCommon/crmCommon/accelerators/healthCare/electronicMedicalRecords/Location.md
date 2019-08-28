---
title: Location - Common Data Model | Microsoft Docs
description: This describes the Location entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Location

Details and position information for a physical place where services are provided and resources and participants may be stored, found, contained, or accommodated.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/Location.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/Location  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[locationId](#locationId)|Unique identifier for entity instances|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[organizationId](#organizationId)|Unique identifier for the organization|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[stateCode](#stateCode)|Status of the Location|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[stateCode_display](#stateCode_display)||<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[statusCode](#statusCode)|Reason for the status of the Location|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[statusCode_display](#statusCode_display)||<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[name](#name)|The name of the custom entity.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[addressCity](#addressCity)|The name of the city, town, village or other community or delivery center.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[addressCountry](#addressCountry)|Country - a nation as commonly understood or generally accepted.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[addressDistinct](#addressDistinct)|The name of the administrative area (county).|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[addressLine1](#addressLine1)|This component contains the house number, apartment number, street name, street direction, P.O. Box number, delivery hints, and similar address information|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[addressLine2](#addressLine2)|This component contains the house number, apartment number, street name, street direction, P.O. Box number, delivery hints, and similar address information|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[addressLine3](#addressLine3)|This component contains the house number, apartment number, street name, street direction, P.O. Box number, delivery hints, and similar address information|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[addressPeriodEnd](#addressPeriodEnd)|Time period when address was/is in use.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[addressPeriodStart](#addressPeriodStart)|Time period when address was/is in use.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[addressPostalCode](#addressPostalCode)|A postal code designating a region defined by the postal service.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[addressState](#addressState)|Sub-unit of a country with limited sovereignty in a federally organized country. A code may be used if codes are in common use (i.e. US 2 letter state codes).|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[addressText](#addressText)|A full text representation of the address.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[addressType](#addressType)|Distinguishes between physical addresses (those you can visit) and mailing addresses (e.g. PO Boxes and care-of addresses). Most addresses are both.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[addressType_display](#addressType_display)||<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[addressUse](#addressUse)|The purpose of this address.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[addressUse_display](#addressUse_display)||<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[description](#description)|Description of the Location, which helps in finding or referencing the place.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[locationAlias1](#locationAlias1)|A list of alternate names that the location is known as, or was known as in the past.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[locationAlias2](#locationAlias2)|A list of alternate names that the location is known as, or was known as in the past.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[locationAlias3](#locationAlias3)|A list of alternate names that the location is known as, or was known as in the past.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[locationNumber](#locationNumber)|Unique code or number identifying the location to its users.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[locationPositionAltitude](#locationPositionAltitude)|Altitude. The value domain and the interpretation are the same as for the text of the altitude element in KML (see notes below)|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[locationPositionLatitude](#locationPositionLatitude)|Latitude. The value domain and the interpretation are the same as for the text of the latitude element in KML|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[locationPositionLongitude](#locationPositionLongitude)|Longitude. The value domain and the interpretation are the same as for the text of the longitude element in KML|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[managingOrganization](#managingOrganization)|The organization responsible for the provisioning and upkeep of the location.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[mode](#mode)|Indicates whether a resource instance represents a specific location or a class of locations.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[mode_display](#mode_display)||<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[operationalStatus](#operationalStatus)|The Operational status covers operation values most relevant to beds (but can also apply to rooms/units/chair/etc such as an isolation unit/dialysis chair).|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[operationalStatus_display](#operationalStatus_display)||<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[partOf](#partOf)|Another Location which this Location is physically part of.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[physicalType](#physicalType)|Physical form of the location, e.g. building, room, vehicle, road.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[status](#status)|The status property covers the general availability of the resource, not the current value which may be covered by the operationStatus, or by a schedule/slots if they are configured for the location.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[status_display](#status_display)||<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|
|[type](#type)|Indicates the type of function performed at the location.|<a href="Location.md" target="_blank">electronicMedicalRecords/Location</a>|

### <a href=#locationId name="locationId">locationId</a>

Unique identifier for entity instances  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Location</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msemr_locationid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for the organization  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier for the organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Location  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Location</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Location  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Location</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_name</td></tr></table>

### <a href=#addressCity name="addressCity">addressCity</a>

The name of the city, town, village or other community or delivery center.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address City</td></tr><tr><td>description</td><td>The name of the city, town, village or other community or delivery center.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_addresscity</td></tr></table>

### <a href=#addressCountry name="addressCountry">addressCountry</a>

Country - a nation as commonly understood or generally accepted.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Country</td></tr><tr><td>description</td><td>Country - a nation as commonly understood or generally accepted.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_addresscountry</td></tr></table>

### <a href=#addressDistinct name="addressDistinct">addressDistinct</a>

The name of the administrative area (county).  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Distinct</td></tr><tr><td>description</td><td>The name of the administrative area (county).</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_addressdistinct</td></tr></table>

### <a href=#addressLine1 name="addressLine1">addressLine1</a>

This component contains the house number, apartment number, street name, street direction, P.O. Box number, delivery hints, and similar address information  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 1</td></tr><tr><td>description</td><td>This component contains the house number, apartment number, street name, street direction, P.O. Box number, delivery hints, and similar address information</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_addressline1</td></tr></table>

### <a href=#addressLine2 name="addressLine2">addressLine2</a>

This component contains the house number, apartment number, street name, street direction, P.O. Box number, delivery hints, and similar address information  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 2</td></tr><tr><td>description</td><td>This component contains the house number, apartment number, street name, street direction, P.O. Box number, delivery hints, and similar address information</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_addressline2</td></tr></table>

### <a href=#addressLine3 name="addressLine3">addressLine3</a>

This component contains the house number, apartment number, street name, street direction, P.O. Box number, delivery hints, and similar address information  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 3</td></tr><tr><td>description</td><td>This component contains the house number, apartment number, street name, street direction, P.O. Box number, delivery hints, and similar address information</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_addressline3</td></tr></table>

### <a href=#addressPeriodEnd name="addressPeriodEnd">addressPeriodEnd</a>

Time period when address was/is in use.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Period End</td></tr><tr><td>description</td><td>Time period when address was/is in use.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_addressperiodend</td></tr></table>

### <a href=#addressPeriodStart name="addressPeriodStart">addressPeriodStart</a>

Time period when address was/is in use.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Period Start</td></tr><tr><td>description</td><td>Time period when address was/is in use.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_addressperiodstart</td></tr></table>

### <a href=#addressPostalCode name="addressPostalCode">addressPostalCode</a>

A postal code designating a region defined by the postal service.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Postal Code</td></tr><tr><td>description</td><td>A postal code designating a region defined by the postal service.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_addresspostalcode</td></tr></table>

### <a href=#addressState name="addressState">addressState</a>

Sub-unit of a country with limited sovereignty in a federally organized country. A code may be used if codes are in common use (i.e. US 2 letter state codes).  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address State</td></tr><tr><td>description</td><td>Sub-unit of a country with limited sovereignty in a federally organized country. A code may be used if codes are in common use (i.e. US 2 letter state codes).</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_addressstate</td></tr></table>

### <a href=#addressText name="addressText">addressText</a>

A full text representation of the address.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Text</td></tr><tr><td>description</td><td>A full text representation of the address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_addresstext</td></tr></table>

### <a href=#addressType name="addressType">addressType</a>

Distinguishes between physical addresses (those you can visit) and mailing addresses (e.g. PO Boxes and care-of addresses). Most addresses are both.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Type</td></tr><tr><td>description</td><td>Distinguishes between physical addresses (those you can visit) and mailing addresses (e.g. PO Boxes and care-of addresses). Most addresses are both.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_addresstype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Postal</td><td>935000000</td></tr><tr><td>en</td><td>Physical</td><td>935000001</td></tr><tr><td>en</td><td>Both</td><td>935000002</td></tr></table></td></tr></table>

### <a href=#addressType_display name="addressType_display">addressType_display</a>

First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#addressUse name="addressUse">addressUse</a>

The purpose of this address.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Use</td></tr><tr><td>description</td><td>The purpose of this address.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_addressuse</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Home</td><td>935000000</td></tr><tr><td>en</td><td>Work</td><td>935000001</td></tr><tr><td>en</td><td>Temp</td><td>935000002</td></tr><tr><td>en</td><td>Old</td><td>935000003</td></tr></table></td></tr></table>

### <a href=#addressUse_display name="addressUse_display">addressUse_display</a>

First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#description name="description">description</a>

Description of the Location, which helps in finding or referencing the place.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the Location, which helps in finding or referencing the place.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_description</td></tr></table>

### <a href=#locationAlias1 name="locationAlias1">locationAlias1</a>

A list of alternate names that the location is known as, or was known as in the past.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Alias 1</td></tr><tr><td>description</td><td>A list of alternate names that the location is known as, or was known as in the past.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_locationalias1</td></tr></table>

### <a href=#locationAlias2 name="locationAlias2">locationAlias2</a>

A list of alternate names that the location is known as, or was known as in the past.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Alias 2</td></tr><tr><td>description</td><td>A list of alternate names that the location is known as, or was known as in the past.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_locationalias2</td></tr></table>

### <a href=#locationAlias3 name="locationAlias3">locationAlias3</a>

A list of alternate names that the location is known as, or was known as in the past.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Alias 3</td></tr><tr><td>description</td><td>A list of alternate names that the location is known as, or was known as in the past.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_locationalias3</td></tr></table>

### <a href=#locationNumber name="locationNumber">locationNumber</a>

Unique code or number identifying the location to its users.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Location Number</td></tr><tr><td>description</td><td>Unique code or number identifying the location to its users.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_locationnumber</td></tr></table>

### <a href=#locationPositionAltitude name="locationPositionAltitude">locationPositionAltitude</a>

Altitude. The value domain and the interpretation are the same as for the text of the altitude element in KML (see notes below)  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Position Altitude</td></tr><tr><td>description</td><td>Altitude. The value domain and the interpretation are the same as for the text of the altitude element in KML (see notes below)</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_locationpositionaltitude</td></tr></table>

### <a href=#locationPositionLatitude name="locationPositionLatitude">locationPositionLatitude</a>

Latitude. The value domain and the interpretation are the same as for the text of the latitude element in KML  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Position Latitude</td></tr><tr><td>description</td><td>Latitude. The value domain and the interpretation are the same as for the text of the latitude element in KML</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_locationpositionlatitude</td></tr></table>

### <a href=#locationPositionLongitude name="locationPositionLongitude">locationPositionLongitude</a>

Longitude. The value domain and the interpretation are the same as for the text of the longitude element in KML  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Position Longitude</td></tr><tr><td>description</td><td>Longitude. The value domain and the interpretation are the same as for the text of the longitude element in KML</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_locationpositionlongitude</td></tr></table>

### <a href=#managingOrganization name="managingOrganization">managingOrganization</a>

The organization responsible for the provisioning and upkeep of the location.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Managing Organization</td></tr><tr><td>description</td><td>The organization responsible for the provisioning and upkeep of the location.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_managingorganization</td></tr></table>

### <a href=#mode name="mode">mode</a>

Indicates whether a resource instance represents a specific location or a class of locations.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mode</td></tr><tr><td>description</td><td>Indicates whether a resource instance represents a specific location or a class of locations.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_mode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>instance</td><td>935000000</td></tr><tr><td>en</td><td>Kind</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#mode_display name="mode_display">mode_display</a>

First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#operationalStatus name="operationalStatus">operationalStatus</a>

The Operational status covers operation values most relevant to beds (but can also apply to rooms/units/chair/etc such as an isolation unit/dialysis chair).  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Operational Status</td></tr><tr><td>description</td><td>The Operational status covers operation values most relevant to beds (but can also apply to rooms/units/chair/etc such as an isolation unit/dialysis chair).</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_operationalstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Closed</td><td>935000000</td></tr><tr><td>en</td><td>Housekeeping</td><td>935000001</td></tr><tr><td>en</td><td>Isolated</td><td>935000002</td></tr><tr><td>en</td><td>Contaminated</td><td>935000003</td></tr><tr><td>en</td><td>Occupied</td><td>935000004</td></tr><tr><td>en</td><td>Unoccupied</td><td>935000005</td></tr></table></td></tr></table>

### <a href=#operationalStatus_display name="operationalStatus_display">operationalStatus_display</a>

First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#partOf name="partOf">partOf</a>

Another Location which this Location is physically part of.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Part Of</td></tr><tr><td>description</td><td>Another Location which this Location is physically part of.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_partof</td></tr></table>

### <a href=#physicalType name="physicalType">physicalType</a>

Physical form of the location, e.g. building, room, vehicle, road.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Physical Type</td></tr><tr><td>description</td><td>Physical form of the location, e.g. building, room, vehicle, road.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_physicaltype</td></tr></table>

### <a href=#status name="status">status</a>

The status property covers the general availability of the resource, not the current value which may be covered by the operationStatus, or by a schedule/slots if they are configured for the location.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>The status property covers the general availability of the resource, not the current value which may be covered by the operationStatus, or by a schedule/slots if they are configured for the location.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_status</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>935000000</td></tr><tr><td>en</td><td>Suspended</td><td>935000001</td></tr><tr><td>en</td><td>Inactive</td><td>935000002</td></tr></table></td></tr></table>

### <a href=#status_display name="status_display">status_display</a>

First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#type name="type">type</a>

Indicates the type of function performed at the location.  
First included in: electronicMedicalRecords/Location (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type</td></tr><tr><td>description</td><td>Indicates the type of function performed at the location.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_type</td></tr></table>
