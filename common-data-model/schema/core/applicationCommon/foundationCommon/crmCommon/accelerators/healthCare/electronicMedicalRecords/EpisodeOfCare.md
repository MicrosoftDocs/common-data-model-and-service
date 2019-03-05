---
title: EpisodeOfCare - Common Data Model | Microsoft Docs
description: This describes the EpisodeOfCare entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/5/2019
ms.author: nebanfic
---

# Episode of Care

An association between a patient and an organization / healthcare provider(s) during which time encounters may occur.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/EpisodeOfCare.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/EpisodeOfCare  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[ownerId](#ownerId)|Owner Id|<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[episodeOfCareId](#episodeOfCareId)|Unique identifier for entity instances|<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[stateCode](#stateCode)|Status of the Episode of Care|<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[stateCode_display](#stateCode_display)||<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[statusCode](#statusCode)|Reason for the status of the Episode of Care|<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[statusCode_display](#statusCode_display)||<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[description](#description)|The name of the custom entity.|<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[careManager](#careManager)|The practitioner that is the care manager/care coordinator for this patient.|<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[endDateTime](#endDateTime)|The interval during which the managing organization assumes the defined responsibility.|<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[identifier](#identifier)|The EpisodeOfCare may be known by different identifiers for different contexts of use, such as when an external agency is tracking the Episode for funding purposes.|<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[organization](#organization)|The organization that has assumed the specific responsibilities for the specified duration.|<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[patient](#patient)|The patient who is the focus of this episode of care.|<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[startDateTime](#startDateTime)|The interval during which the managing organization assumes the defined responsibility.|<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[status](#status)|Current status of episode.|<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|
|[status_display](#status_display)||<a href="EpisodeOfCare.md" target="_blank">electronicMedicalRecords/EpisodeOfCare</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#episodeOfCareId name="episodeOfCareId">episodeOfCareId</a>

Unique identifier for entity instances  
First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Episode of Care</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msemr_episodeofcareid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Episode of Care  
First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Episode of Care</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Episode of Care  
First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Episode of Care</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#description name="description">description</a>

The name of the custom entity.  
First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_description</td></tr></table>

### <a href=#careManager name="careManager">careManager</a>

The practitioner that is the care manager/care coordinator for this patient.  
First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Care Manager</td></tr><tr><td>description</td><td>The practitioner that is the care manager/care coordinator for this patient.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_caremanager</td></tr></table>

### <a href=#endDateTime name="endDateTime">endDateTime</a>

The interval during which the managing organization assumes the defined responsibility.  
First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End Date/Time</td></tr><tr><td>description</td><td>The interval during which the managing organization assumes the defined responsibility.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_enddatetime</td></tr></table>

### <a href=#identifier name="identifier">identifier</a>

The EpisodeOfCare may be known by different identifiers for different contexts of use, such as when an external agency is tracking the Episode for funding purposes.  
First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Episode Of Care Number</td></tr><tr><td>description</td><td>The EpisodeOfCare may be known by different identifiers for different contexts of use, such as when an external agency is tracking the Episode for funding purposes.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_identifier</td></tr></table>

### <a href=#organization name="organization">organization</a>

The organization that has assumed the specific responsibilities for the specified duration.  
First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization</td></tr><tr><td>description</td><td>The organization that has assumed the specific responsibilities for the specified duration.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_organization</td></tr></table>

### <a href=#patient name="patient">patient</a>

The patient who is the focus of this episode of care.  
First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Patient</td></tr><tr><td>description</td><td>The patient who is the focus of this episode of care.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_patient</td></tr></table>

### <a href=#startDateTime name="startDateTime">startDateTime</a>

The interval during which the managing organization assumes the defined responsibility.  
First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date/Time</td></tr><tr><td>description</td><td>The interval during which the managing organization assumes the defined responsibility.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_startdatetime</td></tr></table>

### <a href=#status name="status">status</a>

Current status of episode.  
First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Current status of episode.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_status</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Planned</td><td>935000000</td></tr><tr><td>en</td><td>Waitlist</td><td>935000001</td></tr><tr><td>en</td><td>Active</td><td>935000002</td></tr><tr><td>en</td><td>On Hold</td><td>935000003</td></tr><tr><td>en</td><td>Finished</td><td>935000004</td></tr><tr><td>en</td><td>Cancelled</td><td>935000005</td></tr><tr><td>en</td><td>Entered in Error</td><td>935000006</td></tr></table></td></tr></table>

### <a href=#status_display name="status_display">status_display</a>

First included in: electronicMedicalRecords/EpisodeOfCare (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
