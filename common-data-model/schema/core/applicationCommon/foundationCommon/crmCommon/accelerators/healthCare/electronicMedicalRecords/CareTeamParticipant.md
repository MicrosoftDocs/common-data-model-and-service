---
title: CareTeamParticipant - Common Data Model | Microsoft Docs
description: Identifies all people and organizations who are expected to be involved in the care team.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Care Team Participant

Identifies all people and organizations who are expected to be involved in the care team.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CareTeamParticipant.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CareTeamParticipant  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[ownerId](#ownerId)|Owner Id|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[careTeamParticipantId](#careTeamParticipantId)|Unique identifier for entity instances|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[stateCode](#stateCode)|Status of the Care Team Participant|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[stateCode_display](#stateCode_display)||<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[statusCode](#statusCode)|Reason for the status of the Care Team Participant|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[statusCode_display](#statusCode_display)||<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[description](#description)|The name of the custom entity.|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[entityImageId](#entityImageId)||<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[careTeam](#careTeam)|This records identifiers associated with this care team that are defined by business processes and/or used to refer to it when a direct URL reference to the resource itself is not appropriate.|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[memberCareTeam](#memberCareTeam)|Member is care team|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[memberOrganization](#memberOrganization)|Member is organization|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[memberPatient](#memberPatient)|Member is patient|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[memberPractioner](#memberPractioner)|Member is practitioner|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[memberRelatedPerson](#memberRelatedPerson)|Member is person related to patient|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[memberType](#memberType)|Type of member.|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[memberType_display](#memberType_display)||<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[onBehalfOf](#onBehalfOf)|The organization of the practitioner.|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[periodEnd](#periodEnd)|Indicates when the specific member or organization did (or is intended to) come into effect and end.|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[periodStart](#periodStart)|Indicates when the specific member or organization did (or is intended to) come into effect and end.|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|
|[role](#role)|Indicates specific responsibility of an individual within the care team, such as "Primary care physician", "Trained social worker counselor", "Caregiver", etc.|<a href="CareTeamParticipant.md" target="_blank">electronicMedicalRecords/CareTeamParticipant</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#careTeamParticipantId name="careTeamParticipantId">careTeamParticipantId</a>

Unique identifier for entity instances  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Care Team Participant</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msemr_careteamparticipantid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Care Team Participant  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Care Team Participant</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Care Team Participant  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Care Team Participant</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#description name="description">description</a>

The name of the custom entity.  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_description</td></tr></table>

### <a href=#entityImageId name="entityImageId">entityImageId</a>

First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entityimageid</td></tr></table>

### <a href=#careTeam name="careTeam">careTeam</a>

This records identifiers associated with this care team that are defined by business processes and/or used to refer to it when a direct URL reference to the resource itself is not appropriate.  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Care Team</td></tr><tr><td>description</td><td>This records identifiers associated with this care team that are defined by business processes and/or used to refer to it when a direct URL reference to the resource itself is not appropriate.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_careteam</td></tr></table>

### <a href=#memberCareTeam name="memberCareTeam">memberCareTeam</a>

Member is care team  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Care Team</td></tr><tr><td>description</td><td>Member is care team</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_membercareteam</td></tr></table>

### <a href=#memberOrganization name="memberOrganization">memberOrganization</a>

Member is organization  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization</td></tr><tr><td>description</td><td>Member is organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_memberorganization</td></tr></table>

### <a href=#memberPatient name="memberPatient">memberPatient</a>

Member is patient  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Patient</td></tr><tr><td>description</td><td>Member is patient</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_memberpatient</td></tr></table>

### <a href=#memberPractioner name="memberPractioner">memberPractioner</a>

Member is practitioner  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Practioner</td></tr><tr><td>description</td><td>Member is practitioner</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_memberpractioner</td></tr></table>

### <a href=#memberRelatedPerson name="memberRelatedPerson">memberRelatedPerson</a>

Member is person related to patient  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Related Person</td></tr><tr><td>description</td><td>Member is person related to patient</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_memberrelatedperson</td></tr></table>

### <a href=#memberType name="memberType">memberType</a>

Type of member.  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Member Type</td></tr><tr><td>description</td><td>Type of member.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_membertype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Practitioner</td><td>935000000</td></tr><tr><td>en</td><td>Relation Person</td><td>935000001</td></tr><tr><td>en</td><td>Patient</td><td>935000002</td></tr><tr><td>en</td><td>Organization</td><td>935000003</td></tr><tr><td>en</td><td>Care Team</td><td>935000004</td></tr></table></td></tr></table>

### <a href=#memberType_display name="memberType_display">memberType_display</a>

First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#onBehalfOf name="onBehalfOf">onBehalfOf</a>

The organization of the practitioner.  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>On Behalf Of</td></tr><tr><td>description</td><td>The organization of the practitioner.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_onbehalfof</td></tr></table>

### <a href=#periodEnd name="periodEnd">periodEnd</a>

Indicates when the specific member or organization did (or is intended to) come into effect and end.  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Period End</td></tr><tr><td>description</td><td>Indicates when the specific member or organization did (or is intended to) come into effect and end.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_periodend</td></tr></table>

### <a href=#periodStart name="periodStart">periodStart</a>

Indicates when the specific member or organization did (or is intended to) come into effect and end.  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Period Start</td></tr><tr><td>description</td><td>Indicates when the specific member or organization did (or is intended to) come into effect and end.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_periodstart</td></tr></table>

### <a href=#role name="role">role</a>

Indicates specific responsibility of an individual within the care team, such as "Primary care physician", "Trained social worker counselor", "Caregiver", etc.  
First included in: electronicMedicalRecords/CareTeamParticipant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Role</td></tr><tr><td>description</td><td>Indicates specific responsibility of an individual within the care team, such as "Primary care physician", "Trained social worker counselor", "Caregiver", etc.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_role</td></tr></table>
