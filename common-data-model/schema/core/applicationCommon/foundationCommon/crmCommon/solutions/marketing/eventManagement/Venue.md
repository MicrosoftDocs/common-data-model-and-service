---
title: Venue - Common Data Model | Microsoft Docs
description: This describes the Venue entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/5/2019
ms.author: nebanfic
---

# Venue

The Venue describes the location at which all event sessions and activities take place. A single event venue can be comprised of zero or more buildings, each of which can have zero or more rooms where sessions take place.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/eventManagement/Venue.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/eventManagement/Venue  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[venueId](#venueId)|Unique identifier for entity instances|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[stateCode](#stateCode)|Status of the Venue|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[stateCode_display](#stateCode_display)||<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[statusCode](#statusCode)|Reason for the status of the Venue|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[statusCode_display](#statusCode_display)||<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[name](#name)|The name of the custom entity.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[accessibleToilets](#accessibleToilets)|There are accessible toilets or not.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[accessibleToilets_display](#accessibleToilets_display)||<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[additionalFacilities](#additionalFacilities)|Some additional facilities which is not covered by available options.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[addressLine1](#addressLine1)|Address (except of city, country/region, state or province and postal code).|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[addressLine2](#addressLine2)|Additional address details.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[addressLine3](#addressLine3)|Additional address details.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[buildingId](#buildingId)|Unique identifier for Building associated with Venue.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[city](#city)|City part of address info.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[cost](#cost)|Cost of the venue.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[costBase](#costBase)|Value of the Cost in base currency.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[country](#country)|Country/Region part of address info.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[description](#description)|Description of the venue.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[disabledAccess](#disabledAccess)|There is disabled access or not.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[disabledAccess_display](#disabledAccess_display)||<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[disabledParking](#disabledParking)|There is disabled parking or not.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[disabledParking_display](#disabledParking_display)||<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[email](#email)|Email. Part of the venue contact information.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[estCapacity](#estCapacity)|Estimated capacity of the venue.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[parentVenueId](#parentVenueId)|Unique identifier for Venue associated with Venue.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[postalCode](#postalCode)|Postal code part of address info.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[primaryContact](#primaryContact)|A person who is responsible for the venue.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[publicTelephoneAvailable](#publicTelephoneAvailable)|There is available public telephone or not.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[publicTelephoneAvailable_display](#publicTelephoneAvailable_display)||<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[roomId](#roomId)|Unique identifier for Room associated with Venue.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[stateProvince](#stateProvince)|State or province part of address info.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[telephone1](#telephone1)|Telephone 1. Part of the venue contact information.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[telephone2](#telephone2)|Telephone 2. Part of the venue contact information.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[telephone3](#telephone3)|Telephone 3. Part of the venue contact information.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[website](#website)|Website. Part of the venue contact information.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[wifiAvailable](#wifiAvailable)|There is available wifi or not.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[wifiAvailable_display](#wifiAvailable_display)||<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[wifiPassword](#wifiPassword)|Wifi password.|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[wifiSSID](#wifiSSID)|SSID of Wifi|<a href="Venue.md" target="_blank">eventManagement/Venue</a>|
|[addressComposite](#addressComposite)||<a href="Venue.md" target="_blank">eventManagement/Venue</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#venueId name="venueId">venueId</a>

Unique identifier for entity instances  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Venue</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msevtmgt_venueid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Venue  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Venue</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Venue  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Venue</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_name</td></tr></table>

### <a href=#accessibleToilets name="accessibleToilets">accessibleToilets</a>

There are accessible toilets or not.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accessible Toilets</td></tr><tr><td>description</td><td>There are accessible toilets or not.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_accessibletoilets</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Yes</td><td>100000001</td></tr><tr><td>en</td><td>No</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#accessibleToilets_display name="accessibleToilets_display">accessibleToilets_display</a>

First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#additionalFacilities name="additionalFacilities">additionalFacilities</a>

Some additional facilities which is not covered by available options.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Additional Facilities</td></tr><tr><td>description</td><td>Some additional facilities which is not covered by available options.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_additionalfacilities</td></tr></table>

### <a href=#addressLine1 name="addressLine1">addressLine1</a>

Address (except of city, country/region, state or province and postal code).  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Line 1</td></tr><tr><td>description</td><td>Address (except of city, country/region, state or province and postal code).</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_addressline1</td></tr></table>

### <a href=#addressLine2 name="addressLine2">addressLine2</a>

Additional address details.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Line 2</td></tr><tr><td>description</td><td>Additional address details.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_addressline2</td></tr></table>

### <a href=#addressLine3 name="addressLine3">addressLine3</a>

Additional address details.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Line 3</td></tr><tr><td>description</td><td>Additional address details.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_addressline3</td></tr></table>

### <a href=#buildingId name="buildingId">buildingId</a>

Unique identifier for Building associated with Venue.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Building</td></tr><tr><td>description</td><td>Unique identifier for Building associated with Venue.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_buildingid</td></tr></table>

### <a href=#city name="city">city</a>

City part of address info.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>City</td></tr><tr><td>description</td><td>City part of address info.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_city</td></tr></table>

### <a href=#cost name="cost">cost</a>

Cost of the venue.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost</td></tr><tr><td>description</td><td>Cost of the venue.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_cost</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#costBase name="costBase">costBase</a>

Value of the Cost in base currency.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost (Base)</td></tr><tr><td>description</td><td>Value of the Cost in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_cost_base</td></tr></table>

### <a href=#country name="country">country</a>

Country/Region part of address info.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country/Region</td></tr><tr><td>description</td><td>Country/Region part of address info.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_country</td></tr></table>

### <a href=#description name="description">description</a>

Description of the venue.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the venue.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_description</td></tr></table>

### <a href=#disabledAccess name="disabledAccess">disabledAccess</a>

There is disabled access or not.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Disabled Access</td></tr><tr><td>description</td><td>There is disabled access or not.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_disabledaccess</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Yes</td><td>100000001</td></tr><tr><td>en</td><td>No</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#disabledAccess_display name="disabledAccess_display">disabledAccess_display</a>

First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#disabledParking name="disabledParking">disabledParking</a>

There is disabled parking or not.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Disable parking</td></tr><tr><td>description</td><td>There is disabled parking or not.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_disabledparking</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Yes</td><td>100000001</td></tr><tr><td>en</td><td>No</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#disabledParking_display name="disabledParking_display">disabledParking_display</a>

First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#email name="email">email</a>

Email. Part of the venue contact information.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email</td></tr><tr><td>description</td><td>Email. Part of the venue contact information.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_email</td></tr></table>

### <a href=#estCapacity name="estCapacity">estCapacity</a>

Estimated capacity of the venue.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Est. Capacity</td></tr><tr><td>description</td><td>Estimated capacity of the venue.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_estcapacity</td></tr></table>

### <a href=#parentVenueId name="parentVenueId">parentVenueId</a>

Unique identifier for Venue associated with Venue.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent Venue</td></tr><tr><td>description</td><td>Unique identifier for Venue associated with Venue.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_parentvenueid</td></tr></table>

### <a href=#postalCode name="postalCode">postalCode</a>

Postal code part of address info.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Postal Code</td></tr><tr><td>description</td><td>Postal code part of address info.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_postalcode</td></tr></table>

### <a href=#primaryContact name="primaryContact">primaryContact</a>

A person who is responsible for the venue.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary Contact</td></tr><tr><td>description</td><td>A person who is responsible for the venue.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_primarycontact</td></tr></table>

### <a href=#publicTelephoneAvailable name="publicTelephoneAvailable">publicTelephoneAvailable</a>

There is available public telephone or not.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Public Telephone Available</td></tr><tr><td>description</td><td>There is available public telephone or not.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_publictelephoneavailable</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Yes</td><td>100000001</td></tr><tr><td>en</td><td>No</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#publicTelephoneAvailable_display name="publicTelephoneAvailable_display">publicTelephoneAvailable_display</a>

First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#roomId name="roomId">roomId</a>

Unique identifier for Room associated with Venue.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Room</td></tr><tr><td>description</td><td>Unique identifier for Room associated with Venue.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_roomid</td></tr></table>

### <a href=#stateProvince name="stateProvince">stateProvince</a>

State or province part of address info.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State/Province</td></tr><tr><td>description</td><td>State or province part of address info.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_stateprovince</td></tr></table>

### <a href=#telephone1 name="telephone1">telephone1</a>

Telephone 1. Part of the venue contact information.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Telephone1</td></tr><tr><td>description</td><td>Telephone 1. Part of the venue contact information.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_telephone1</td></tr></table>

### <a href=#telephone2 name="telephone2">telephone2</a>

Telephone 2. Part of the venue contact information.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Telephone2</td></tr><tr><td>description</td><td>Telephone 2. Part of the venue contact information.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_telephone2</td></tr></table>

### <a href=#telephone3 name="telephone3">telephone3</a>

Telephone 3. Part of the venue contact information.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Telephone3</td></tr><tr><td>description</td><td>Telephone 3. Part of the venue contact information.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_telephone3</td></tr></table>

### <a href=#website name="website">website</a>

Website. Part of the venue contact information.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Website</td></tr><tr><td>description</td><td>Website. Part of the venue contact information.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_website</td></tr></table>

### <a href=#wifiAvailable name="wifiAvailable">wifiAvailable</a>

There is available wifi or not.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Wifi Available</td></tr><tr><td>description</td><td>There is available wifi or not.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_wifiavailable</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Yes</td><td>100000001</td></tr><tr><td>en</td><td>No</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#wifiAvailable_display name="wifiAvailable_display">wifiAvailable_display</a>

First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#wifiPassword name="wifiPassword">wifiPassword</a>

Wifi password.  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Wifi Password</td></tr><tr><td>description</td><td>Wifi password.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_wifipassword</td></tr></table>

### <a href=#wifiSSID name="wifiSSID">wifiSSID</a>

SSID of Wifi  
First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Wifi SSID</td></tr><tr><td>description</td><td>SSID of Wifi</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_wifissid</td></tr></table>

### <a href=#addressComposite name="addressComposite">addressComposite</a>

First included in: eventManagement/Venue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Composite</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_addresscomposite</td></tr></table>
