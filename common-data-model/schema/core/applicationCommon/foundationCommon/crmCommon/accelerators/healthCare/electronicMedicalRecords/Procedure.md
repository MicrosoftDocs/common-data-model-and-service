---
title: Procedure - Common Data Model | Microsoft Docs
description: This describes the Procedure entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# Procedure

An action that is or was performed on a patient. This can be a physical intervention like an operation, or less invasive like counseling or hypnotherapy.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/Procedure.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/Procedure  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[procedureId](#procedureId)|Unique identifier for entity instances|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[stateCode](#stateCode)|Status of the Procedure|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[stateCode_display](#stateCode_display)||<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[statusCode](#statusCode)|Reason for the status of the Procedure|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[statusCode_display](#statusCode_display)||<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[description](#description)|The name of the custom entity.|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[category](#category)|A code that classifies the procedure for searching, sorting and display purposes (e.g. "Surgical Procedure").|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[code](#code)|The specific procedure that is performed. Use text if the exact nature of the procedure cannot be coded (e.g. "Laparoscopic Appendectomy").|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[dateTime](#dateTime)|The date(time)/period over which the procedure was performed.|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[encounter](#encounter)|The encounter during which the procedure was performed.|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[episodeOfCare](#episodeOfCare)|The encounter during which the procedure was performed.|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[group](#group)|The person, animal or group on which the procedure was performed.|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[location](#location)|The location where the procedure actually happened. E.g. a newborn at home, a tracheotomy at a restaurant.|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[notDone](#notDone)|Set this to true if the record is saying that the procedure was NOT performed.|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[notDoneReason](#notDoneReason)|A code indicating why the procedure was not performed.|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[outcome](#outcome)|The outcome of the procedure - did it resolve reasons for the procedure being performed?|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[patient](#patient)|The person, animal or group on which the procedure was performed.|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[performedEndDate](#performedEndDate)|The period End date over which the procedure was performed. Allows a period to support complex procedures that span more than one date, and also allows for the length of the procedure to be captured|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[performedStartDate](#performedStartDate)|The period start date over which the procedure was performed. Allows a period to support complex procedures that span more than one date, and also allows for the length of the procedure to be captured|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[procedureIdentifier](#procedureIdentifier)|This records identifiers associated with this procedure that are defined by business processes and/or used to refer to it when a direct URL reference to the resource itself is not appropriate|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[status](#status)|A code specifying the state of the procedure. Generally this will be in-progress or completed state.|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[status_display](#status_display)||<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[subjectType](#subjectType)|Type of Subject on whom procedure is performed|<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|
|[subjectType_display](#subjectType_display)||<a href="Procedure.md" target="_blank">electronicMedicalRecords/Procedure</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#procedureId name="procedureId">procedureId</a>

Unique identifier for entity instances  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Procedure</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msemr_procedureid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Procedure  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Procedure</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Procedure  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Procedure</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#description name="description">description</a>

The name of the custom entity.  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_description</td></tr></table>

### <a href=#category name="category">category</a>

A code that classifies the procedure for searching, sorting and display purposes (e.g. "Surgical Procedure").  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Category</td></tr><tr><td>description</td><td>A code that classifies the procedure for searching, sorting and display purposes (e.g. "Surgical Procedure").</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_category</td></tr></table>

### <a href=#code name="code">code</a>

The specific procedure that is performed. Use text if the exact nature of the procedure cannot be coded (e.g. "Laparoscopic Appendectomy").  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Code</td></tr><tr><td>description</td><td>The specific procedure that is performed. Use text if the exact nature of the procedure cannot be coded (e.g. "Laparoscopic Appendectomy").</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_code</td></tr></table>

### <a href=#dateTime name="dateTime">dateTime</a>

The date(time)/period over which the procedure was performed.  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date/Time</td></tr><tr><td>description</td><td>The date(time)/period over which the procedure was performed.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_datetime</td></tr></table>

### <a href=#encounter name="encounter">encounter</a>

The encounter during which the procedure was performed.  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Encounter</td></tr><tr><td>description</td><td>The encounter during which the procedure was performed.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_encounter</td></tr></table>

### <a href=#episodeOfCare name="episodeOfCare">episodeOfCare</a>

The encounter during which the procedure was performed.  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Episode of Care</td></tr><tr><td>description</td><td>The encounter during which the procedure was performed.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_episodeofcare</td></tr></table>

### <a href=#group name="group">group</a>

The person, animal or group on which the procedure was performed.  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Group</td></tr><tr><td>description</td><td>The person, animal or group on which the procedure was performed.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_group</td></tr></table>

### <a href=#location name="location">location</a>

The location where the procedure actually happened. E.g. a newborn at home, a tracheotomy at a restaurant.  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Location</td></tr><tr><td>description</td><td>The location where the procedure actually happened. E.g. a newborn at home, a tracheotomy at a restaurant.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_location</td></tr></table>

### <a href=#notDone name="notDone">notDone</a>

Set this to true if the record is saying that the procedure was NOT performed.  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Not Done</td></tr><tr><td>description</td><td>Set this to true if the record is saying that the procedure was NOT performed.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_notdone</td></tr></table>

### <a href=#notDoneReason name="notDoneReason">notDoneReason</a>

A code indicating why the procedure was not performed.  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reason</td></tr><tr><td>description</td><td>A code indicating why the procedure was not performed.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_notdonereason</td></tr></table>

### <a href=#outcome name="outcome">outcome</a>

The outcome of the procedure - did it resolve reasons for the procedure being performed?  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Outcome</td></tr><tr><td>description</td><td>The outcome of the procedure - did it resolve reasons for the procedure being performed?</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_outcome</td></tr></table>

### <a href=#patient name="patient">patient</a>

The person, animal or group on which the procedure was performed.  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Patient</td></tr><tr><td>description</td><td>The person, animal or group on which the procedure was performed.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_patient</td></tr></table>

### <a href=#performedEndDate name="performedEndDate">performedEndDate</a>

The period End date over which the procedure was performed. Allows a period to support complex procedures that span more than one date, and also allows for the length of the procedure to be captured  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Performed End Date</td></tr><tr><td>description</td><td>The period End date over which the procedure was performed. Allows a period to support complex procedures that span more than one date, and also allows for the length of the procedure to be captured</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_performedenddate</td></tr></table>

### <a href=#performedStartDate name="performedStartDate">performedStartDate</a>

The period start date over which the procedure was performed. Allows a period to support complex procedures that span more than one date, and also allows for the length of the procedure to be captured  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Performed Start Date</td></tr><tr><td>description</td><td>The period start date over which the procedure was performed. Allows a period to support complex procedures that span more than one date, and also allows for the length of the procedure to be captured</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_performedstartdate</td></tr></table>

### <a href=#procedureIdentifier name="procedureIdentifier">procedureIdentifier</a>

This records identifiers associated with this procedure that are defined by business processes and/or used to refer to it when a direct URL reference to the resource itself is not appropriate  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Procedure ID</td></tr><tr><td>description</td><td>This records identifiers associated with this procedure that are defined by business processes and/or used to refer to it when a direct URL reference to the resource itself is not appropriate</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_procedureidentifier</td></tr></table>

### <a href=#status name="status">status</a>

A code specifying the state of the procedure. Generally this will be in-progress or completed state.  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>A code specifying the state of the procedure. Generally this will be in-progress or completed state.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_status</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Preparation</td><td>935000000</td></tr><tr><td>en</td><td>In Progress</td><td>935000001</td></tr><tr><td>en</td><td>Suspended</td><td>935000002</td></tr><tr><td>en</td><td>Aborted</td><td>935000003</td></tr><tr><td>en</td><td>Completed</td><td>935000004</td></tr><tr><td>en</td><td>Entered in Error</td><td>935000005</td></tr><tr><td>en</td><td>Unknown</td><td>935000006</td></tr></table></td></tr></table>

### <a href=#status_display name="status_display">status_display</a>

First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#subjectType name="subjectType">subjectType</a>

Type of Subject on whom procedure is performed  
First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject Type</td></tr><tr><td>description</td><td>Type of Subject on whom procedure is performed</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjecttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Patient</td><td>935000000</td></tr><tr><td>en</td><td>Patient Group</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#subjectType_display name="subjectType_display">subjectType_display</a>

First included in: electronicMedicalRecords/Procedure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
