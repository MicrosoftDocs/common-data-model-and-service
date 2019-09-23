---
title: BusinessOperation - Common Data Model | Microsoft Docs
description: Operation run at a business facility, such as new car sales showroom, used car sales or service center.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Business Operation

Operation run at a business facility, such as new car sales showroom, used car sales or service center.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/automotive/BusinessOperation.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/automotive/BusinessOperation  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[ownerId](#ownerId)|Owner Id|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[accountId](#accountId)|Parent company of the business operation.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[addressCity](#addressCity)|City where the business operation is located.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[addressCountry](#addressCountry)|Country where the business operation is located.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[addressCounty](#addressCounty)|County where the business operation is located.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[addressLatitude](#addressLatitude)|Latitude coordinate of the business operation's location.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[addressLongitude](#addressLongitude)|Longitude coordinate of the business operation's location.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[addressName](#addressName)|Name of the business operation.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[addressPostalCode](#addressPostalCode)|Zip code where the business operation is located.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[addressStateProvince](#addressStateProvince)|State where the business operation is located.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[addressStreet1](#addressStreet1)|Line 1 of the street address where the business operation is located.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[addressStreet2](#addressStreet2)|Line 2 of the street address where the business operation is located.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[addressStreet3](#addressStreet3)|Line 3 of the street address where the business operation is located.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[businessOperationId](#businessOperationId)|Unique identifier for entity instances|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[description](#description)|Description of the business operation.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[facilityId](#facilityId)|Building where the business operation is located.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[name](#name)|Name of the business operation.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[operationTypeId](#operationTypeId)|Type of operation run at this facility.|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[stateCode](#stateCode)|Status of the Business Operation|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[stateCode_display](#stateCode_display)||<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[statusCode](#statusCode)|Reason for the status of the Business Operation|<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|
|[statusCode_display](#statusCode_display)||<a href="BusinessOperation.md" target="_blank">automotive/BusinessOperation</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#accountId name="accountId">accountId</a>

Parent company of the business operation.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account</td></tr><tr><td>description</td><td>Parent company of the business operation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_account</td></tr></table>

### <a href=#addressCity name="addressCity">addressCity</a>

City where the business operation is located.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address: City</td></tr><tr><td>description</td><td>City where the business operation is located.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_addresscity</td></tr></table>

### <a href=#addressCountry name="addressCountry">addressCountry</a>

Country where the business operation is located.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address: Country</td></tr><tr><td>description</td><td>Country where the business operation is located.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_addresscountry</td></tr></table>

### <a href=#addressCounty name="addressCounty">addressCounty</a>

County where the business operation is located.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address: County</td></tr><tr><td>description</td><td>County where the business operation is located.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_addresscounty</td></tr></table>

### <a href=#addressLatitude name="addressLatitude">addressLatitude</a>

Latitude coordinate of the business operation's location.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address: Latitude</td></tr><tr><td>description</td><td>Latitude coordinate of the business operation's location.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_addresslatitude</td></tr></table>

### <a href=#addressLongitude name="addressLongitude">addressLongitude</a>

Longitude coordinate of the business operation's location.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address: Longitude</td></tr><tr><td>description</td><td>Longitude coordinate of the business operation's location.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_addresslongitude</td></tr></table>

### <a href=#addressName name="addressName">addressName</a>

Name of the business operation.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address: Name</td></tr><tr><td>description</td><td>Name of the business operation.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_addressname</td></tr></table>

### <a href=#addressPostalCode name="addressPostalCode">addressPostalCode</a>

Zip code where the business operation is located.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address: ZIP/Postal Code</td></tr><tr><td>description</td><td>Zip code where the business operation is located.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_addresspostalcode</td></tr></table>

### <a href=#addressStateProvince name="addressStateProvince">addressStateProvince</a>

State where the business operation is located.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address: State/Province</td></tr><tr><td>description</td><td>State where the business operation is located.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_addressstateprovince</td></tr></table>

### <a href=#addressStreet1 name="addressStreet1">addressStreet1</a>

Line 1 of the street address where the business operation is located.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address: Street 1</td></tr><tr><td>description</td><td>Line 1 of the street address where the business operation is located.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_addressstreet1</td></tr></table>

### <a href=#addressStreet2 name="addressStreet2">addressStreet2</a>

Line 2 of the street address where the business operation is located.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address: Street 2</td></tr><tr><td>description</td><td>Line 2 of the street address where the business operation is located.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_addressstreet2</td></tr></table>

### <a href=#addressStreet3 name="addressStreet3">addressStreet3</a>

Line 3 of the street address where the business operation is located.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address: Street 3</td></tr><tr><td>description</td><td>Line 3 of the street address where the business operation is located.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_addressstreet3</td></tr></table>

### <a href=#businessOperationId name="businessOperationId">businessOperationId</a>

Unique identifier for entity instances  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Business Operation</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_businessoperationid</td></tr></table>

### <a href=#description name="description">description</a>

Description of the business operation.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the business operation.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>sourceName</td><td>msauto_description</td></tr></table>

### <a href=#facilityId name="facilityId">facilityId</a>

Building where the business operation is located.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Facility</td></tr><tr><td>description</td><td>Building where the business operation is located.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_facilityid</td></tr></table>

### <a href=#name name="name">name</a>

Name of the business operation.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Name of the business operation.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_name</td></tr></table>

### <a href=#operationTypeId name="operationTypeId">operationTypeId</a>

Type of operation run at this facility.  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Operation Type</td></tr><tr><td>description</td><td>Type of operation run at this facility.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_operationtypeid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Business Operation  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Business Operation</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Business Operation  
First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Business Operation</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: automotive/BusinessOperation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
