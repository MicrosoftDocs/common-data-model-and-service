---
title: HealthcareService - Common Data Model | Microsoft Docs
description: The details of a healthcare service available at a location.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Healthcare Service

The details of a healthcare service available at a location.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/HealthcareService.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/HealthcareService  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[healthCareServiceId](#healthCareServiceId)|Unique identifier for entity instances|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[organizationId](#organizationId)|Unique identifier for the organization|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[stateCode](#stateCode)|Status of the Healthcare Service|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[stateCode_display](#stateCode_display)||<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[statusCode](#statusCode)|Reason for the status of the Healthcare Service|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[statusCode_display](#statusCode_display)||<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[name](#name)|Further description of the service as it would be presented to a consumer while searching.|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[appointmentRequired](#appointmentRequired)|Indicates whether or not a prospective consumer will require an appointment for a particular service at a site to be provided by the Organization. Indicates if an appointment is required for access|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[availabilityExceptions](#availabilityExceptions)|A description of site availability exceptions, e.g. public holiday availability. Succinctly describing all possible exceptions to normal site availability as details in available/ not available times.|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[category](#category)|Identifies the broad category of service being performed or delivered.|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[comment](#comment)|Any additional description of the service and/or any specific issues not covered by the other attributes, which can be displayed as further detail under the serviceName.|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[eligibility](#eligibility)|Does this service have specific eligibility requirements that need to be met in order to use the service?|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[eligibilitynote](#eligibilitynote)|Describes the eligibility conditions for the service.|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[extraDetails](#extraDetails)|Extra details about the service that can't be placed in the other fields.|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[healthcareService](#healthcareService)|The details of a healthcare service available at a location.|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[notAvailableDescription](#notAvailableDescription)|The closing time of day. Note: If the AllDay flag is set, then this time is ignored.|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[notAvailableDuringEndDateTime](#notAvailableDuringEndDateTime)|End time with inclusive boundary, if not ongoing|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[notAvailableDuringStartDateTime](#notAvailableDuringStartDateTime)|Starting time with inclusive boundary|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|
|[providedby](#providedby)|The organization that provides this healthcare service.|<a href="HealthcareService.md" target="_blank">electronicMedicalRecords/HealthcareService</a>|

### <a href=#healthCareServiceId name="healthCareServiceId">healthCareServiceId</a>

Unique identifier for entity instances  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Healthcare Service</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msemr_healthcareserviceid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for the organization  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier for the organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Healthcare Service  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Healthcare Service</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Healthcare Service  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Healthcare Service</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

Further description of the service as it would be presented to a consumer while searching.  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Further description of the service as it would be presented to a consumer while searching.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_name</td></tr></table>

### <a href=#appointmentRequired name="appointmentRequired">appointmentRequired</a>

Indicates whether or not a prospective consumer will require an appointment for a particular service at a site to be provided by the Organization. Indicates if an appointment is required for access  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Appointment Required</td></tr><tr><td>description</td><td>Indicates whether or not a prospective consumer will require an appointment for a particular service at a site to be provided by the Organization. Indicates if an appointment is required for access</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_appointmentrequired</td></tr></table>

### <a href=#availabilityExceptions name="availabilityExceptions">availabilityExceptions</a>

A description of site availability exceptions, e.g. public holiday availability. Succinctly describing all possible exceptions to normal site availability as details in available/ not available times.  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Availability Exceptions</td></tr><tr><td>description</td><td>A description of site availability exceptions, e.g. public holiday availability. Succinctly describing all possible exceptions to normal site availability as details in available/ not available times.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_availabilityexceptions</td></tr></table>

### <a href=#category name="category">category</a>

Identifies the broad category of service being performed or delivered.  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Category</td></tr><tr><td>description</td><td>Identifies the broad category of service being performed or delivered.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_category</td></tr></table>

### <a href=#comment name="comment">comment</a>

Any additional description of the service and/or any specific issues not covered by the other attributes, which can be displayed as further detail under the serviceName.  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Comment</td></tr><tr><td>description</td><td>Any additional description of the service and/or any specific issues not covered by the other attributes, which can be displayed as further detail under the serviceName.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_comment</td></tr></table>

### <a href=#eligibility name="eligibility">eligibility</a>

Does this service have specific eligibility requirements that need to be met in order to use the service?  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Eligibility</td></tr><tr><td>description</td><td>Does this service have specific eligibility requirements that need to be met in order to use the service?</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_eligibility</td></tr></table>

### <a href=#eligibilitynote name="eligibilitynote">eligibilitynote</a>

Describes the eligibility conditions for the service.  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Eligibility note</td></tr><tr><td>description</td><td>Describes the eligibility conditions for the service.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_eligibilitynote</td></tr></table>

### <a href=#extraDetails name="extraDetails">extraDetails</a>

Extra details about the service that can't be placed in the other fields.  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Extra Details</td></tr><tr><td>description</td><td>Extra details about the service that can't be placed in the other fields.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_extradetails</td></tr></table>

### <a href=#healthcareService name="healthcareService">healthcareService</a>

The details of a healthcare service available at a location.  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Healthcare Service</td></tr><tr><td>description</td><td>The details of a healthcare service available at a location.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_healthcareservice</td></tr></table>

### <a href=#notAvailableDescription name="notAvailableDescription">notAvailableDescription</a>

The closing time of day. Note: If the AllDay flag is set, then this time is ignored.  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>The closing time of day. Note: If the AllDay flag is set, then this time is ignored.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_notavailabledescription</td></tr></table>

### <a href=#notAvailableDuringEndDateTime name="notAvailableDuringEndDateTime">notAvailableDuringEndDateTime</a>

End time with inclusive boundary, if not ongoing  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End Datetime</td></tr><tr><td>description</td><td>End time with inclusive boundary, if not ongoing</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_notavailableduringenddatetime</td></tr></table>

### <a href=#notAvailableDuringStartDateTime name="notAvailableDuringStartDateTime">notAvailableDuringStartDateTime</a>

Starting time with inclusive boundary  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Datetime</td></tr><tr><td>description</td><td>Starting time with inclusive boundary</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_notavailableduringstartdatetime</td></tr></table>

### <a href=#providedby name="providedby">providedby</a>

The organization that provides this healthcare service.  
First included in: electronicMedicalRecords/HealthcareService (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Provided by</td></tr><tr><td>description</td><td>The organization that provides this healthcare service.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_providedby</td></tr></table>
