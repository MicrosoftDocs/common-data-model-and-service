---
title: CarePlan - Common Data Model | Microsoft Docs
description: This describes the CarePlan entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/5/2019
ms.author: nebanfic
---

# Care Plan

Describes the intention of how one or more practitioners intend to deliver care for a particular patient, group or community for a period of time, possibly limited to care for a specific condition  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CarePlan.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/CarePlan  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[ownerId](#ownerId)|Owner Id|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[carePlanId](#carePlanId)|Unique identifier for entity instances|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[stateCode](#stateCode)|Status of the Care Plan|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[stateCode_display](#stateCode_display)||<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[statusCode](#statusCode)|Reason for the status of the Care Plan|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[statusCode_display](#statusCode_display)||<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[title](#title)|The name of the custom entity.|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[carePlanIdentifier](#carePlanIdentifier)|This records identifiers associated with this care plan that are defined by business processes and/or used to refer to it when a direct URL reference to the resource itself is not appropriate.|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[contextType](#contextType)|Type of the context care plan is created for|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[contextType_display](#contextType_display)||<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[encounterIdentifier](#encounterIdentifier)|Identifies the original context in which this particular CarePlan was created.|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[episodeOfCare](#episodeOfCare)|Identifies the original context in which this particular CarePlan was created.|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[groupIdentifier](#groupIdentifier)|Identifies the patient or group whose intended care is described by the plan.|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[patientIdentifier](#patientIdentifier)|Identifies the patient or group whose intended care is described by the plan.|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[planDescription](#planDescription)|A description of the scope and nature of the plan.|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[planEndDate](#planEndDate)|Indicates when the plan did (or is intended to) come into effect and end.|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[planIntent](#planIntent)|Indicates the level of authority/intentionality associated with the care plan and where the care plan fits into the workflow chain.|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[planIntent_display](#planIntent_display)||<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[planStartDate](#planStartDate)|Indicates when the plan did (or is intended to) come into effect and end.|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[planStatus](#planStatus)|Indicates whether the plan is currently being acted upon, represents future intentions or is now a historical record.|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[planStatus_display](#planStatus_display)||<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[subjectType](#subjectType)|Type of subject of the care plan|<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|
|[subjectType_display](#subjectType_display)||<a href="CarePlan.md" target="_blank">electronicMedicalRecords/CarePlan</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#carePlanId name="carePlanId">carePlanId</a>

Unique identifier for entity instances  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Care Plan</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msemr_careplanid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Care Plan  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Care Plan</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Care Plan  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Care Plan</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#title name="title">title</a>

The name of the custom entity.  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Title</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_title</td></tr></table>

### <a href=#carePlanIdentifier name="carePlanIdentifier">carePlanIdentifier</a>

This records identifiers associated with this care plan that are defined by business processes and/or used to refer to it when a direct URL reference to the resource itself is not appropriate.  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Identifier</td></tr><tr><td>description</td><td>This records identifiers associated with this care plan that are defined by business processes and/or used to refer to it when a direct URL reference to the resource itself is not appropriate.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_careplanidentifier</td></tr></table>

### <a href=#contextType name="contextType">contextType</a>

Type of the context care plan is created for  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Context Type</td></tr><tr><td>description</td><td>Type of the context care plan is created for</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_contexttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Encounter</td><td>935000000</td></tr><tr><td>en</td><td>Episode Of Care</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#contextType_display name="contextType_display">contextType_display</a>

First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#encounterIdentifier name="encounterIdentifier">encounterIdentifier</a>

Identifies the original context in which this particular CarePlan was created.  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Encounter</td></tr><tr><td>description</td><td>Identifies the original context in which this particular CarePlan was created.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_encounteridentifier</td></tr></table>

### <a href=#episodeOfCare name="episodeOfCare">episodeOfCare</a>

Identifies the original context in which this particular CarePlan was created.  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Episode of Care</td></tr><tr><td>description</td><td>Identifies the original context in which this particular CarePlan was created.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_episodeofcare</td></tr></table>

### <a href=#groupIdentifier name="groupIdentifier">groupIdentifier</a>

Identifies the patient or group whose intended care is described by the plan.  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Group</td></tr><tr><td>description</td><td>Identifies the patient or group whose intended care is described by the plan.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_groupidentifier</td></tr></table>

### <a href=#patientIdentifier name="patientIdentifier">patientIdentifier</a>

Identifies the patient or group whose intended care is described by the plan.  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Patient</td></tr><tr><td>description</td><td>Identifies the patient or group whose intended care is described by the plan.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_patientidentifier</td></tr></table>

### <a href=#planDescription name="planDescription">planDescription</a>

A description of the scope and nature of the plan.  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>A description of the scope and nature of the plan.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_plandescription</td></tr></table>

### <a href=#planEndDate name="planEndDate">planEndDate</a>

Indicates when the plan did (or is intended to) come into effect and end.  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End Date</td></tr><tr><td>description</td><td>Indicates when the plan did (or is intended to) come into effect and end.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_planenddate</td></tr></table>

### <a href=#planIntent name="planIntent">planIntent</a>

Indicates the level of authority/intentionality associated with the care plan and where the care plan fits into the workflow chain.  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Intent</td></tr><tr><td>description</td><td>Indicates the level of authority/intentionality associated with the care plan and where the care plan fits into the workflow chain.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_planintent</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Proposal</td><td>935000000</td></tr><tr><td>en</td><td>Plan</td><td>935000001</td></tr><tr><td>en</td><td>Order</td><td>935000002</td></tr><tr><td>en</td><td>Option</td><td>935000003</td></tr></table></td></tr></table>

### <a href=#planIntent_display name="planIntent_display">planIntent_display</a>

First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#planStartDate name="planStartDate">planStartDate</a>

Indicates when the plan did (or is intended to) come into effect and end.  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date</td></tr><tr><td>description</td><td>Indicates when the plan did (or is intended to) come into effect and end.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_planstartdate</td></tr></table>

### <a href=#planStatus name="planStatus">planStatus</a>

Indicates whether the plan is currently being acted upon, represents future intentions or is now a historical record.  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Indicates whether the plan is currently being acted upon, represents future intentions or is now a historical record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_planstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Pending</td><td>935000000</td></tr><tr><td>en</td><td>Active</td><td>935000001</td></tr><tr><td>en</td><td>Suspended</td><td>935000002</td></tr><tr><td>en</td><td>Completed</td><td>935000003</td></tr><tr><td>en</td><td>Entered In Error</td><td>935000004</td></tr><tr><td>en</td><td>Cancelled</td><td>935000005</td></tr><tr><td>en</td><td>Unknown</td><td>935000006</td></tr></table></td></tr></table>

### <a href=#planStatus_display name="planStatus_display">planStatus_display</a>

First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#subjectType name="subjectType">subjectType</a>

Type of subject of the care plan  
First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject Type</td></tr><tr><td>description</td><td>Type of subject of the care plan</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjecttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Patient</td><td>935000000</td></tr><tr><td>en</td><td>Group</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#subjectType_display name="subjectType_display">subjectType_display</a>

First included in: electronicMedicalRecords/CarePlan (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
