---
title: TestDrive - Common Data Model | Microsoft Docs
description: This describes the TestDrive entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Test Drive

The physical experience a customer or prospect has of a vehicle or device prior to a possible purchase of same or similar one.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/automotive/TestDrive.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/automotive/TestDrive  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[ownerId](#ownerId)|Owner Id|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[actualDuration](#actualDuration)|Actual time the test drive took.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[actualEnd](#actualEnd)|Actual end time of the test drive.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[actualStart](#actualStart)|Actual start time of the test drive.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[appointmentId](#appointmentId)|Appointment scheduled for the test drive.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[businessFacilityId](#businessFacilityId)|Dealership where test drive takes place.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[businessId](#businessId)|Owning company of the dealership.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[businessOperationId](#businessOperationId)|Department/team at dealership responsible for test drive.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[contactId](#contactId)|Person who is test driving the automobile.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[customerIdType](#customerIdType)|The type of customer, either Account or Contact.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[customerId](#customerId)|The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[deviceBrandId](#deviceBrandId)|Vehicle brand.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[deviceClassId](#deviceClassId)|Vehicle class.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[deviceGenerationId](#deviceGenerationId)|Vehicle model generation.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[deviceId](#deviceId)|Test drive vehicle.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[deviceModelCodeId](#deviceModelCodeId)|Vehicle model configuration.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[deviceModelId](#deviceModelId)|Vehicle Model|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[deviceStyleId](#deviceStyleId)|Vehicle body style.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[deviceVariantId](#deviceVariantId)|Vehicle variant.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[identificationExpiresOn](#identificationExpiresOn)|Expiration date of the identification provided.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[identificationNumber](#identificationNumber)|Unique number of the identification provided.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[identificationType](#identificationType)|Type of identification provided.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[identificationType_display](#identificationType_display)||<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[leadId](#leadId)|The initial identification of the customer as a potential buyer.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[name](#name)|Name of the test drive.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[opportunityId](#opportunityId)|Opportunity associated to this test drive.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[scheduledDuration](#scheduledDuration)|The original scheduled duration of the test drive.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[scheduledEnd](#scheduledEnd)|The original scheduled end time of the test drive.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[scheduledStart](#scheduledStart)|The original scheduled start time of the test drive.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[testDriveId](#testDriveId)|Unique identifier for entity instances|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[year](#year)|Vehicle year of manufacture.|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[stateCode](#stateCode)|Status of the Test Drive|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[stateCode_display](#stateCode_display)||<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[statusCode](#statusCode)|Reason for the status of the Test Drive|<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|
|[statusCode_display](#statusCode_display)||<a href="TestDrive.md" target="_blank">automotive/TestDrive</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#actualDuration name="actualDuration">actualDuration</a>

Actual time the test drive took.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Duration</td></tr><tr><td>description</td><td>Actual time the test drive took.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msauto_actualduration</td></tr></table>

### <a href=#actualEnd name="actualEnd">actualEnd</a>

Actual end time of the test drive.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual End</td></tr><tr><td>description</td><td>Actual end time of the test drive.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msauto_actualend</td></tr></table>

### <a href=#actualStart name="actualStart">actualStart</a>

Actual start time of the test drive.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Start</td></tr><tr><td>description</td><td>Actual start time of the test drive.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msauto_actualstart</td></tr></table>

### <a href=#appointmentId name="appointmentId">appointmentId</a>

Appointment scheduled for the test drive.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Appointment</td></tr><tr><td>description</td><td>Appointment scheduled for the test drive.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_appointmentid</td></tr></table>

### <a href=#businessFacilityId name="businessFacilityId">businessFacilityId</a>

Dealership where test drive takes place.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Business Facility</td></tr><tr><td>description</td><td>Dealership where test drive takes place.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_businessfacilityid</td></tr></table>

### <a href=#businessId name="businessId">businessId</a>

Owning company of the dealership.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Business</td></tr><tr><td>description</td><td>Owning company of the dealership.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_businessid</td></tr></table>

### <a href=#businessOperationId name="businessOperationId">businessOperationId</a>

Department/team at dealership responsible for test drive.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Business Operation</td></tr><tr><td>description</td><td>Department/team at dealership responsible for test drive.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_businessoperationid</td></tr></table>

### <a href=#contactId name="contactId">contactId</a>

Person who is test driving the automobile.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>description</td><td>Person who is test driving the automobile.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_contactid</td></tr></table>

### <a href=#customerIdType name="customerIdType">customerIdType</a>

The type of customer, either Account or Contact.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Type</td></tr><tr><td>description</td><td>The type of customer, either Account or Contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>customeridtype</td></tr></table>

### <a href=#customerId name="customerId">customerId</a>

The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>description</td><td>The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customerid</td></tr></table>

### <a href=#deviceBrandId name="deviceBrandId">deviceBrandId</a>

Vehicle brand.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Brand</td></tr><tr><td>description</td><td>Vehicle brand.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicebrandid</td></tr></table>

### <a href=#deviceClassId name="deviceClassId">deviceClassId</a>

Vehicle class.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Class</td></tr><tr><td>description</td><td>Vehicle class.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_deviceclassid</td></tr></table>

### <a href=#deviceGenerationId name="deviceGenerationId">deviceGenerationId</a>

Vehicle model generation.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Generation</td></tr><tr><td>description</td><td>Vehicle model generation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicegenerationid</td></tr></table>

### <a href=#deviceId name="deviceId">deviceId</a>

Test drive vehicle.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device</td></tr><tr><td>description</td><td>Test drive vehicle.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_deviceid</td></tr></table>

### <a href=#deviceModelCodeId name="deviceModelCodeId">deviceModelCodeId</a>

Vehicle model configuration.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Model Code</td></tr><tr><td>description</td><td>Vehicle model configuration.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicemodelcodeid</td></tr></table>

### <a href=#deviceModelId name="deviceModelId">deviceModelId</a>

Vehicle Model  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Model</td></tr><tr><td>description</td><td>Vehicle Model</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicemodelid</td></tr></table>

### <a href=#deviceStyleId name="deviceStyleId">deviceStyleId</a>

Vehicle body style.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Style</td></tr><tr><td>description</td><td>Vehicle body style.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicestyleid</td></tr></table>

### <a href=#deviceVariantId name="deviceVariantId">deviceVariantId</a>

Vehicle variant.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device Variant</td></tr><tr><td>description</td><td>Vehicle variant.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_devicevariantid</td></tr></table>

### <a href=#identificationExpiresOn name="identificationExpiresOn">identificationExpiresOn</a>

Expiration date of the identification provided.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Identification Expires On</td></tr><tr><td>description</td><td>Expiration date of the identification provided.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msauto_identificationexpireson</td></tr></table>

### <a href=#identificationNumber name="identificationNumber">identificationNumber</a>

Unique number of the identification provided.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Identification Number</td></tr><tr><td>description</td><td>Unique number of the identification provided.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_identificationnumber</td></tr></table>

### <a href=#identificationType name="identificationType">identificationType</a>

Type of identification provided.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Identification Type</td></tr><tr><td>description</td><td>Type of identification provided.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msauto_identificationtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#identificationType_display name="identificationType_display">identificationType_display</a>

First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#leadId name="leadId">leadId</a>

The initial identification of the customer as a potential buyer.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lead</td></tr><tr><td>description</td><td>The initial identification of the customer as a potential buyer.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_leadid</td></tr></table>

### <a href=#name name="name">name</a>

Name of the test drive.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Name of the test drive.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_name</td></tr></table>

### <a href=#opportunityId name="opportunityId">opportunityId</a>

Opportunity associated to this test drive.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Opportunity</td></tr><tr><td>description</td><td>Opportunity associated to this test drive.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_opportunityid</td></tr></table>

### <a href=#scheduledDuration name="scheduledDuration">scheduledDuration</a>

The original scheduled duration of the test drive.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scheduled Duration</td></tr><tr><td>description</td><td>The original scheduled duration of the test drive.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msauto_scheduledduration</td></tr></table>

### <a href=#scheduledEnd name="scheduledEnd">scheduledEnd</a>

The original scheduled end time of the test drive.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scheduled End</td></tr><tr><td>description</td><td>The original scheduled end time of the test drive.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msauto_scheduledend</td></tr></table>

### <a href=#scheduledStart name="scheduledStart">scheduledStart</a>

The original scheduled start time of the test drive.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scheduled Start</td></tr><tr><td>description</td><td>The original scheduled start time of the test drive.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msauto_scheduledstart</td></tr></table>

### <a href=#testDriveId name="testDriveId">testDriveId</a>

Unique identifier for entity instances  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Test Drive</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_testdriveid</td></tr></table>

### <a href=#year name="year">year</a>

Vehicle year of manufacture.  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Year</td></tr><tr><td>description</td><td>Vehicle year of manufacture.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4</td></tr><tr><td>sourceName</td><td>msauto_year</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Test Drive  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Test Drive</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Test Drive  
First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Test Drive</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Requested</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Confirmed</td><td>972230000</td><td>0</td></tr><tr><td>en</td><td>In Progress</td><td>972230001</td><td>0</td></tr><tr><td>en</td><td>Completed</td><td>972230002</td><td>0</td></tr><tr><td>en</td><td>Closed</td><td>2</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>972230003</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: automotive/TestDrive (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
