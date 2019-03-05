---
title: Building - Common Data Model | Microsoft Docs
description: This describes the Building entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/5/2019
ms.author: nebanfic
---

# Building

A single venue can be comprised of zero or more buildings where event activities are held. Each building in turn is comprised of zero or more rooms where event activities are held.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/eventManagement/Building.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/eventManagement/Building  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[buildingId](#buildingId)|Unique identifier for entity instances|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[stateCode](#stateCode)|Status of the Building|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[stateCode_display](#stateCode_display)||<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[statusCode](#statusCode)|Reason for the status of the Building|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[statusCode_display](#statusCode_display)||<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[name](#name)|The name of the custom entity.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[accessibleToilets](#accessibleToilets)|There are accessible toilets or not.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[accessibleToilets_display](#accessibleToilets_display)||<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[additionalFacilities](#additionalFacilities)|Some additional facilities which is not covered by available options.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[addressLine1](#addressLine1)|Address (except of city, country/region, state or province and postal code).|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[addressLine2](#addressLine2)|Additional address details.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[addressLine3](#addressLine3)|Additional address details.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[city](#city)|City. Part of address info.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[cost](#cost)|Cost (of using the building)|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[costBase](#costBase)|Value of the Cost in base currency.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[country](#country)|Country/Region. Part of address info.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[description](#description)|Description of the building.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[disabledAccess](#disabledAccess)|There is disabled access or not.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[disabledAccess_display](#disabledAccess_display)||<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[disabledParking](#disabledParking)|There is disabled parking or not.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[disabledParking_display](#disabledParking_display)||<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[email](#email)|Email to contact the building|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[estimatedCapacity](#estimatedCapacity)|Estimated capacity of building|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[postalCode](#postalCode)|Postal code. Part of address info.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[primaryContact](#primaryContact)|A person who is responsible for the building.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[publicTelephoneAvailable](#publicTelephoneAvailable)|There is available public telephone or not.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[publicTelephoneAvailable_display](#publicTelephoneAvailable_display)||<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[stateProvince](#stateProvince)|State or province. Part of address info.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[telephone1](#telephone1)|Telephone to contact the building|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[telephone2](#telephone2)|Telephone to contact the building|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[telephone3](#telephone3)|Telephone to contact the building|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[website](#website)|Website to contact the building|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[wifiAvailable](#wifiAvailable)|There is available wifi or not.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[wifiAvailable_display](#wifiAvailable_display)||<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[wifiPassword](#wifiPassword)|Wifi password.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[wifiSSID](#wifiSSID)|SSID of the wifi|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[addressComposite](#addressComposite)||<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[numberOfRooms](#numberOfRooms)|Number of available rooms.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[numberOfRoomsDate](#numberOfRoomsDate)|Last Updated time of rollup field Number of Rooms.|<a href="Building.md" target="_blank">eventManagement/Building</a>|
|[numberOfRoomsState](#numberOfRoomsState)|State of rollup field Number of Rooms.|<a href="Building.md" target="_blank">eventManagement/Building</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#buildingId name="buildingId">buildingId</a>

Unique identifier for entity instances  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Building</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msevtmgt_buildingid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Building  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Building</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Building  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Building</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_name</td></tr></table>

### <a href=#accessibleToilets name="accessibleToilets">accessibleToilets</a>

There are accessible toilets or not.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accessible Toilets</td></tr><tr><td>description</td><td>There are accessible toilets or not.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_accessibletoilets</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Yes</td><td>100000001</td></tr><tr><td>en</td><td>No</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#accessibleToilets_display name="accessibleToilets_display">accessibleToilets_display</a>

First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#additionalFacilities name="additionalFacilities">additionalFacilities</a>

Some additional facilities which is not covered by available options.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Additional Facilities</td></tr><tr><td>description</td><td>Some additional facilities which is not covered by available options.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_additionalfacilities</td></tr></table>

### <a href=#addressLine1 name="addressLine1">addressLine1</a>

Address (except of city, country/region, state or province and postal code).  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Line 1</td></tr><tr><td>description</td><td>Address (except of city, country/region, state or province and postal code).</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_addressline1</td></tr></table>

### <a href=#addressLine2 name="addressLine2">addressLine2</a>

Additional address details.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Line 2</td></tr><tr><td>description</td><td>Additional address details.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_addressline2</td></tr></table>

### <a href=#addressLine3 name="addressLine3">addressLine3</a>

Additional address details.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Line 3</td></tr><tr><td>description</td><td>Additional address details.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_addressline3</td></tr></table>

### <a href=#city name="city">city</a>

City. Part of address info.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>City</td></tr><tr><td>description</td><td>City. Part of address info.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_city</td></tr></table>

### <a href=#cost name="cost">cost</a>

Cost (of using the building)  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost</td></tr><tr><td>description</td><td>Cost (of using the building)</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_cost</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#costBase name="costBase">costBase</a>

Value of the Cost in base currency.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost (Base)</td></tr><tr><td>description</td><td>Value of the Cost in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_cost_base</td></tr></table>

### <a href=#country name="country">country</a>

Country/Region. Part of address info.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country/Region</td></tr><tr><td>description</td><td>Country/Region. Part of address info.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_country</td></tr></table>

### <a href=#description name="description">description</a>

Description of the building.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the building.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_description</td></tr></table>

### <a href=#disabledAccess name="disabledAccess">disabledAccess</a>

There is disabled access or not.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Disabled Access</td></tr><tr><td>description</td><td>There is disabled access or not.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_disabledaccess</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Yes</td><td>100000001</td></tr><tr><td>en</td><td>No</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#disabledAccess_display name="disabledAccess_display">disabledAccess_display</a>

First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#disabledParking name="disabledParking">disabledParking</a>

There is disabled parking or not.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Disabled Parkting</td></tr><tr><td>description</td><td>There is disabled parking or not.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_disabledparking</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Yes</td><td>100000001</td></tr><tr><td>en</td><td>No</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#disabledParking_display name="disabledParking_display">disabledParking_display</a>

First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#email name="email">email</a>

Email to contact the building  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email</td></tr><tr><td>description</td><td>Email to contact the building</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_email</td></tr></table>

### <a href=#estimatedCapacity name="estimatedCapacity">estimatedCapacity</a>

Estimated capacity of building  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Capacity</td></tr><tr><td>description</td><td>Estimated capacity of building</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_estimatedcapacity</td></tr></table>

### <a href=#postalCode name="postalCode">postalCode</a>

Postal code. Part of address info.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Postal Code</td></tr><tr><td>description</td><td>Postal code. Part of address info.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_postalcode</td></tr></table>

### <a href=#primaryContact name="primaryContact">primaryContact</a>

A person who is responsible for the building.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary Contact</td></tr><tr><td>description</td><td>A person who is responsible for the building.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_primarycontact</td></tr></table>

### <a href=#publicTelephoneAvailable name="publicTelephoneAvailable">publicTelephoneAvailable</a>

There is available public telephone or not.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Public Telephone Available</td></tr><tr><td>description</td><td>There is available public telephone or not.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_publictelephoneavailable</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Yes</td><td>100000001</td></tr><tr><td>en</td><td>No</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#publicTelephoneAvailable_display name="publicTelephoneAvailable_display">publicTelephoneAvailable_display</a>

First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#stateProvince name="stateProvince">stateProvince</a>

State or province. Part of address info.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State/Province</td></tr><tr><td>description</td><td>State or province. Part of address info.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_stateprovince</td></tr></table>

### <a href=#telephone1 name="telephone1">telephone1</a>

Telephone to contact the building  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Telephone 1</td></tr><tr><td>description</td><td>Telephone to contact the building</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_telephone1</td></tr></table>

### <a href=#telephone2 name="telephone2">telephone2</a>

Telephone to contact the building  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Telephone 2</td></tr><tr><td>description</td><td>Telephone to contact the building</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_telephone2</td></tr></table>

### <a href=#telephone3 name="telephone3">telephone3</a>

Telephone to contact the building  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Telephone 3</td></tr><tr><td>description</td><td>Telephone to contact the building</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_telephone3</td></tr></table>

### <a href=#website name="website">website</a>

Website to contact the building  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Website</td></tr><tr><td>description</td><td>Website to contact the building</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_website</td></tr></table>

### <a href=#wifiAvailable name="wifiAvailable">wifiAvailable</a>

There is available wifi or not.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Wifi Available</td></tr><tr><td>description</td><td>There is available wifi or not.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_wifiavailable</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Yes</td><td>100000001</td></tr><tr><td>en</td><td>No</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#wifiAvailable_display name="wifiAvailable_display">wifiAvailable_display</a>

First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#wifiPassword name="wifiPassword">wifiPassword</a>

Wifi password.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Wifi Password</td></tr><tr><td>description</td><td>Wifi password.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_wifipassword</td></tr></table>

### <a href=#wifiSSID name="wifiSSID">wifiSSID</a>

SSID of the wifi  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Wifi SSID</td></tr><tr><td>description</td><td>SSID of the wifi</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_wifissid</td></tr></table>

### <a href=#addressComposite name="addressComposite">addressComposite</a>

First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Composite</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_addresscomposite</td></tr></table>

### <a href=#numberOfRooms name="numberOfRooms">numberOfRooms</a>

Number of available rooms.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number of Rooms</td></tr><tr><td>description</td><td>Number of available rooms.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_numberofrooms</td></tr></table>

### <a href=#numberOfRoomsDate name="numberOfRoomsDate">numberOfRoomsDate</a>

Last Updated time of rollup field Number of Rooms.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number of Rooms (Last Updated On)</td></tr><tr><td>description</td><td>Last Updated time of rollup field Number of Rooms.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_numberofrooms_date</td></tr></table>

### <a href=#numberOfRoomsState name="numberOfRoomsState">numberOfRoomsState</a>

State of rollup field Number of Rooms.  
First included in: eventManagement/Building (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number of Rooms (State)</td></tr><tr><td>description</td><td>State of rollup field Number of Rooms.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_numberofrooms_state</td></tr></table>
