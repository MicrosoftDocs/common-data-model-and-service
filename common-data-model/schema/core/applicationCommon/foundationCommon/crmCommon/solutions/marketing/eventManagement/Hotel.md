---
title: Hotel - Common Data Model | Microsoft Docs
description: This describes the Hotel entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Hotel

This represents a single hotel property (for e.g, Marriott in Bellevue). Each individual property belongs to a Hotel Group (e.g., Marriott) which is represented by an Account  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/eventManagement/Hotel.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/eventManagement/Hotel  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[owningUser](#owningUser)|Unique identifier for the user that owns the record.|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[hotelId](#hotelId)|Unique identifier for entity instances|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[stateCode](#stateCode)|Status of the Hotel|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[stateCode_display](#stateCode_display)||<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[statusCode](#statusCode)|Reason for the status of the Hotel|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[statusCode_display](#statusCode_display)||<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[name](#name)|The name of the hotel.|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[addressLine1](#addressLine1)||<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[addressLine2](#addressLine2)||<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[addressLine3](#addressLine3)||<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[city](#city)|City where the hotel is located|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[country](#country)|Country/Region where the hotel is located|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[description](#description)|Hotel description|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[facilities](#facilities)|Hotel facilities|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[hotelGroup](#hotelGroup)||<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[primaryContact](#primaryContact)|Hotel primary contact|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[stateProvince](#stateProvince)|State or Province where the hotel is located|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[website](#website)|Hotel website|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|
|[ZIPPostalCode](#ZIPPostalCode)|Hotel ZIP postal code|<a href="Hotel.md" target="_blank">eventManagement/Hotel</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier for the user that owns the record.  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier for the user that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#hotelId name="hotelId">hotelId</a>

Unique identifier for entity instances  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Hotel</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msevtmgt_hotelid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Hotel  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Hotel</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Hotel  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Hotel</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the hotel.  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the hotel.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_name</td></tr></table>

### <a href=#addressLine1 name="addressLine1">addressLine1</a>

First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Line 1</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_addressline1</td></tr></table>

### <a href=#addressLine2 name="addressLine2">addressLine2</a>

First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Line 2</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_addressline2</td></tr></table>

### <a href=#addressLine3 name="addressLine3">addressLine3</a>

First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address Line 3</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_addressline3</td></tr></table>

### <a href=#city name="city">city</a>

City where the hotel is located  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>City</td></tr><tr><td>description</td><td>City where the hotel is located</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_city</td></tr></table>

### <a href=#country name="country">country</a>

Country/Region where the hotel is located  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country/Region</td></tr><tr><td>description</td><td>Country/Region where the hotel is located</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_country</td></tr></table>

### <a href=#description name="description">description</a>

Hotel description  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Hotel description</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_description</td></tr></table>

### <a href=#facilities name="facilities">facilities</a>

Hotel facilities  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Facilities</td></tr><tr><td>description</td><td>Hotel facilities</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_facilities</td></tr></table>

### <a href=#hotelGroup name="hotelGroup">hotelGroup</a>

First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Hotel Group</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_hotelgroup</td></tr></table>

### <a href=#primaryContact name="primaryContact">primaryContact</a>

Hotel primary contact  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary Contact</td></tr><tr><td>description</td><td>Hotel primary contact</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_primarycontact</td></tr></table>

### <a href=#stateProvince name="stateProvince">stateProvince</a>

State or Province where the hotel is located  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State/Province</td></tr><tr><td>description</td><td>State or Province where the hotel is located</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_stateprovince</td></tr></table>

### <a href=#website name="website">website</a>

Hotel website  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Website</td></tr><tr><td>description</td><td>Hotel website</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_website</td></tr></table>

### <a href=#ZIPPostalCode name="ZIPPostalCode">ZIPPostalCode</a>

Hotel ZIP postal code  
First included in: eventManagement/Hotel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ZIP/Postal Code</td></tr><tr><td>description</td><td>Hotel ZIP postal code</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msevtmgt_zippostalcode</td></tr></table>
