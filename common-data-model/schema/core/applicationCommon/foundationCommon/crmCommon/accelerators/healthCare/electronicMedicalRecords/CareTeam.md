---
title: CareTeam - Common Data Model | Microsoft Docs
description: This describes the CareTeam entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/5/2019
ms.author: nebanfic
---

# Care Team

The Care Team includes all the people and organizations who plan to participate in the coordination and delivery of care for a patient.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CareTeam.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CareTeam  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[ownerId](#ownerId)|Owner Id|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[careTeamId](#careTeamId)|Unique identifier for entity instances|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[stateCode](#stateCode)|Status of the Care Team|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[stateCode_display](#stateCode_display)||<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[statusCode](#statusCode)|Reason for the status of the Care Team|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[statusCode_display](#statusCode_display)||<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[name](#name)|The name of the custom entity.|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[entityImageId](#entityImageId)||<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[careTeamNumber](#careTeamNumber)|This records identifiers associated with this care team that are defined by business processes and/or used to refer to it when a direct URL reference to the resource itself is not appropriate.|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[careTeamStatus](#careTeamStatus)|Indicates the current state of the care team.|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[careTeamStatus_display](#careTeamStatus_display)||<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[contextType](#contextType)|The encounter or episode of care that establishes the context for this care team.|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[contextType_display](#contextType_display)||<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[encounter](#encounter)|The encounter or episode of care that establishes the context for this care team.|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[episodeOfCare](#episodeOfCare)|The encounter or episode of care that establishes the context for this care team.|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[periodEnd](#periodEnd)|Indicates when the team did (or is intended to) come into effect and end.|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[periodStart](#periodStart)|Indicates when the team did (or is intended to) come into effect and end.|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[subjectGroup](#subjectGroup)|Subject is group|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[subjectPatient](#subjectPatient)|Subject is patient|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[subjectType](#subjectType)|Identifies the patient or group whose intended care is handled by the team.|<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|
|[subjectType_display](#subjectType_display)||<a href="CareTeam.md" target="_blank">electronicMedicalRecords/CareTeam</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#careTeamId name="careTeamId">careTeamId</a>

Unique identifier for entity instances  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Care Team</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msemr_careteamid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Care Team  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Care Team</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Care Team  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Care Team</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_name</td></tr></table>

### <a href=#entityImageId name="entityImageId">entityImageId</a>

First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entityimageid</td></tr></table>

### <a href=#careTeamNumber name="careTeamNumber">careTeamNumber</a>

This records identifiers associated with this care team that are defined by business processes and/or used to refer to it when a direct URL reference to the resource itself is not appropriate.  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Care Team Number</td></tr><tr><td>description</td><td>This records identifiers associated with this care team that are defined by business processes and/or used to refer to it when a direct URL reference to the resource itself is not appropriate.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_careteamnumber</td></tr></table>

### <a href=#careTeamStatus name="careTeamStatus">careTeamStatus</a>

Indicates the current state of the care team.  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Care Team Status</td></tr><tr><td>description</td><td>Indicates the current state of the care team.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_careteamstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Proposed</td><td>935000000</td></tr><tr><td>en</td><td>Active</td><td>935000001</td></tr><tr><td>en</td><td>Suspended</td><td>935000002</td></tr><tr><td>en</td><td>Inactive</td><td>935000003</td></tr><tr><td>en</td><td>Entered-In-Error</td><td>935000004</td></tr></table></td></tr></table>

### <a href=#careTeamStatus_display name="careTeamStatus_display">careTeamStatus_display</a>

First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#contextType name="contextType">contextType</a>

The encounter or episode of care that establishes the context for this care team.  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Context Type</td></tr><tr><td>description</td><td>The encounter or episode of care that establishes the context for this care team.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_contexttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Encounter</td><td>935000000</td></tr><tr><td>en</td><td>Episode Of Care</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#contextType_display name="contextType_display">contextType_display</a>

First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#encounter name="encounter">encounter</a>

The encounter or episode of care that establishes the context for this care team.  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Encounter</td></tr><tr><td>description</td><td>The encounter or episode of care that establishes the context for this care team.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_encounter</td></tr></table>

### <a href=#episodeOfCare name="episodeOfCare">episodeOfCare</a>

The encounter or episode of care that establishes the context for this care team.  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Episode of Care</td></tr><tr><td>description</td><td>The encounter or episode of care that establishes the context for this care team.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_episodeofcare</td></tr></table>

### <a href=#periodEnd name="periodEnd">periodEnd</a>

Indicates when the team did (or is intended to) come into effect and end.  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Period End</td></tr><tr><td>description</td><td>Indicates when the team did (or is intended to) come into effect and end.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_periodend</td></tr></table>

### <a href=#periodStart name="periodStart">periodStart</a>

Indicates when the team did (or is intended to) come into effect and end.  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Period Start</td></tr><tr><td>description</td><td>Indicates when the team did (or is intended to) come into effect and end.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_periodstart</td></tr></table>

### <a href=#subjectGroup name="subjectGroup">subjectGroup</a>

Subject is group  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Group</td></tr><tr><td>description</td><td>Subject is group</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjectgroup</td></tr></table>

### <a href=#subjectPatient name="subjectPatient">subjectPatient</a>

Subject is patient  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Patient</td></tr><tr><td>description</td><td>Subject is patient</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjectpatient</td></tr></table>

### <a href=#subjectType name="subjectType">subjectType</a>

Identifies the patient or group whose intended care is handled by the team.  
First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject Type</td></tr><tr><td>description</td><td>Identifies the patient or group whose intended care is handled by the team.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjecttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Patient</td><td>935000000</td></tr><tr><td>en</td><td>Group</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#subjectType_display name="subjectType_display">subjectType_display</a>

First included in: electronicMedicalRecords/CareTeam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
