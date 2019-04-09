---
title: PractitionerRole - Common Data Model | Microsoft Docs
description: This describes the PractitionerRole entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Practitioner Role

A specific set of roles, locations, specialties, or services that a practitioner may perform at an organization for a period of time.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/PractitionerRole.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/PractitionerRole  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[ownerId](#ownerId)|Owner Id|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[owningUser](#owningUser)|Unique identifier for the user that owns the record.|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[practitionerRoleId](#practitionerRoleId)|Unique identifier for entity instances|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[stateCode](#stateCode)|Status of the Practitioner Role|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[stateCode_display](#stateCode_display)||<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[statusCode](#statusCode)|Reason for the status of the Practitioner Role|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[statusCode_display](#statusCode_display)||<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[name](#name)|The name of the custom entity.|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[availabilityExceptions](#availabilityExceptions)|A description of site availability exceptions, e.g. public holiday availability.|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[notAvailableDescription](#notAvailableDescription)|The HealthcareService is not available during this period of time due to the provided reason.|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[notavailableEnddatetime](#notavailableEnddatetime)|The end of the period. If the end of the period is missing, it means that the period is ongoing.|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[notavailableStartdatetime](#notavailableStartdatetime)|The start of the period. The boundary is inclusive.|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[organization](#organization)|The organization where the Practitioner performs the roles associated.|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[periodEndDatetime](#periodEndDatetime)|End time with inclusive boundary, if not ongoing|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[periodStartDatetime](#periodStartDatetime)|Starting time with inclusive boundary|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[practitioner](#practitioner)|Practitioner that is able to provide the defined services for the organization.|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|
|[practitionerRoleNumber](#practitionerRoleNumber)|A specific set of roles, locations, specialties, or services that a practitioner may perform at an organization for a period of time.|<a href="PractitionerRole.md" target="_blank">electronicMedicalRecords/PractitionerRole</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier for the user that owns the record.  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier for the user that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#practitionerRoleId name="practitionerRoleId">practitionerRoleId</a>

Unique identifier for entity instances  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Practitioner Role</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msemr_practitionerroleid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Practitioner Role  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Practitioner Role</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Practitioner Role  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Practitioner Role</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_name</td></tr></table>

### <a href=#availabilityExceptions name="availabilityExceptions">availabilityExceptions</a>

A description of site availability exceptions, e.g. public holiday availability.  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Availability Exceptions</td></tr><tr><td>description</td><td>A description of site availability exceptions, e.g. public holiday availability.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_availabilityexceptions</td></tr></table>

### <a href=#notAvailableDescription name="notAvailableDescription">notAvailableDescription</a>

The HealthcareService is not available during this period of time due to the provided reason.  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>The HealthcareService is not available during this period of time due to the provided reason.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_notavailabledescription</td></tr></table>

### <a href=#notavailableEnddatetime name="notavailableEnddatetime">notavailableEnddatetime</a>

The end of the period. If the end of the period is missing, it means that the period is ongoing.  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Not available (End datetime)</td></tr><tr><td>description</td><td>The end of the period. If the end of the period is missing, it means that the period is ongoing.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_notavailableenddatetime</td></tr></table>

### <a href=#notavailableStartdatetime name="notavailableStartdatetime">notavailableStartdatetime</a>

The start of the period. The boundary is inclusive.  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Not available (Start datetime)</td></tr><tr><td>description</td><td>The start of the period. The boundary is inclusive.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_notavailablestartdatetime</td></tr></table>

### <a href=#organization name="organization">organization</a>

The organization where the Practitioner performs the roles associated.  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization</td></tr><tr><td>description</td><td>The organization where the Practitioner performs the roles associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_organization</td></tr></table>

### <a href=#periodEndDatetime name="periodEndDatetime">periodEndDatetime</a>

End time with inclusive boundary, if not ongoing  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Period (End datetime)</td></tr><tr><td>description</td><td>End time with inclusive boundary, if not ongoing</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_periodenddatetime</td></tr></table>

### <a href=#periodStartDatetime name="periodStartDatetime">periodStartDatetime</a>

Starting time with inclusive boundary  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Period (Start datetime)</td></tr><tr><td>description</td><td>Starting time with inclusive boundary</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_periodstartdatetime</td></tr></table>

### <a href=#practitioner name="practitioner">practitioner</a>

Practitioner that is able to provide the defined services for the organization.  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Practitioner</td></tr><tr><td>description</td><td>Practitioner that is able to provide the defined services for the organization.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_practitioner</td></tr></table>

### <a href=#practitionerRoleNumber name="practitionerRoleNumber">practitionerRoleNumber</a>

A specific set of roles, locations, specialties, or services that a practitioner may perform at an organization for a period of time.  
First included in: electronicMedicalRecords/PractitionerRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Practitioner Role Number</td></tr><tr><td>description</td><td>A specific set of roles, locations, specialties, or services that a practitioner may perform at an organization for a period of time.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_practitionerrolenumber</td></tr></table>
