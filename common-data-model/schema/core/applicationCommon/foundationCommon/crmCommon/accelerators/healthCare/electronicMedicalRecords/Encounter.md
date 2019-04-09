---
title: Encounter - Common Data Model | Microsoft Docs
description: This describes the Encounter entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Encounter

An interaction between a patient and healthcare provider(s) for the purpose of providing healthcare service(s) or assessing the health status of a patient.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/Encounter.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/Encounter  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[owningUser](#owningUser)|Unique identifier for the user that owns the record.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[encounterId](#encounterId)|Unique identifier for entity instances|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[stateCode](#stateCode)|Status of the Encounter|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[stateCode_display](#stateCode_display)||<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[statusCode](#statusCode)|Reason for the status of the Encounter|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[statusCode_display](#statusCode_display)||<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[name](#name)|The name of the custom entity.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[emrAppointment](#emrAppointment)|A booking of a healthcare event among patient(s), practitioner(s), related person(s), and/or device(s) for a specific date/time. This may result in one or more encounter(s).|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[class](#class)|Type of: inpatient | outpatient | ambulatory | emergency +.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[class_display](#class_display)||<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[contextEncounter](#contextEncounter)||<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[contextEpisodeofCare](#contextEpisodeofCare)||<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[duration](#duration)|Quantity of time the encounter lasted. This excludes the time during leaves of absence.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[encounterClass](#encounterClass)|Refers to the class of encounter.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[encounterClass_display](#encounterClass_display)||<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[encounterEndDate](#encounterEndDate)|The start and end time of the encounter.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[encounterGroupIdentifier](#encounterGroupIdentifier)|The group present at the encounter|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[encounterIdentifier](#encounterIdentifier)|Identifier(s) by which this encounter is known.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[encounterLength](#encounterLength)|Quantity of time the encounter lasted. This excludes the time during leaves of absence.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[encounterParentEncounterIdentifier](#encounterParentEncounterIdentifier)|Another Encounter of which this encounter is a part of (administratively or in time).|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[encounterPatientIdentifier](#encounterPatientIdentifier)|The patient present at the encounter.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[encounterPriority](#encounterPriority)|Indicates the urgency of the encounter.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[encounterStartDate](#encounterStartDate)|The start and end time of the encounter.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[encounterStatus](#encounterStatus)|Refers to the status of encounter.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[encounterStatus_display](#encounterStatus_display)||<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[hospitalizationAdmitSource](#hospitalizationAdmitSource)|From where patient was admitted (physician referral, transfer).|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[hospitalizationDestination](#hospitalizationDestination)|Location to which the patient is discharged.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[hospitalizationDischargeDisposition](#hospitalizationDischargeDisposition)|Category or kind of location after discharge.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[hospitalizationOrigin](#hospitalizationOrigin)|The location from which the patient came before admission.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[hospitalizationPreAdmissionNumber](#hospitalizationPreAdmissionNumber)|Pre-admission identifier.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[hospitalizationReadmission](#hospitalizationReadmission)|Whether this hospitalization is a readmission and why if known.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[onBehalfOf](#onBehalfOf)||<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[periodEnd](#periodEnd)|The start and end time of the encounter.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[periodStart](#periodStart)|The start and end time of the encounter.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[priority](#priority)|Indicates the urgency of the encounter.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[priority_display](#priority_display)||<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|
|[subjectPatient](#subjectPatient)|The patient or group present at the encounter.|<a href="Encounter.md" target="_blank">electronicMedicalRecords/Encounter</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier for the user that owns the record.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier for the user that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#encounterId name="encounterId">encounterId</a>

Unique identifier for entity instances  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Encounter</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msemr_encounterid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Encounter  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Encounter</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Encounter  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Encounter</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Planned</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Arrived</td><td>935000000</td><td>0</td></tr><tr><td>en</td><td>Triaged</td><td>935000001</td><td>0</td></tr><tr><td>en</td><td>In Progress</td><td>935000002</td><td>0</td></tr><tr><td>en</td><td>On Leave</td><td>935000003</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr><tr><td>en</td><td>Finished</td><td>935000004</td><td>1</td></tr><tr><td>en</td><td>Cancelled</td><td>935000005</td><td>1</td></tr><tr><td>en</td><td>Entered in Error</td><td>935000006</td><td>1</td></tr><tr><td>en</td><td>Unknown</td><td>935000007</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_name</td></tr></table>

### <a href=#emrAppointment name="emrAppointment">emrAppointment</a>

A booking of a healthcare event among patient(s), practitioner(s), related person(s), and/or device(s) for a specific date/time. This may result in one or more encounter(s).  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Appointment (EMR)</td></tr><tr><td>description</td><td>A booking of a healthcare event among patient(s), practitioner(s), related person(s), and/or device(s) for a specific date/time. This may result in one or more encounter(s).</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_appointmentemr</td></tr></table>

### <a href=#class name="class">class</a>

Type of: inpatient | outpatient | ambulatory | emergency +.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Class</td></tr><tr><td>description</td><td>Type of: inpatient | outpatient | ambulatory | emergency +.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_class</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>ambulatory</td><td>935000000</td></tr><tr><td>en</td><td>emergency</td><td>935000001</td></tr><tr><td>en</td><td>field</td><td>935000002</td></tr><tr><td>en</td><td>home health</td><td>935000003</td></tr><tr><td>en</td><td>inpatient encounter</td><td>935000004</td></tr><tr><td>en</td><td>inpatient acute</td><td>935000005</td></tr><tr><td>en</td><td>inpatient non-acute</td><td>935000006</td></tr><tr><td>en</td><td>pre-admission</td><td>935000007</td></tr><tr><td>en</td><td>short stay</td><td>935000008</td></tr><tr><td>en</td><td>virtual</td><td>935000009</td></tr></table></td></tr></table>

### <a href=#class_display name="class_display">class_display</a>

First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#contextEncounter name="contextEncounter">contextEncounter</a>

First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Context (Encounter)</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_contextencounter</td></tr></table>

### <a href=#contextEpisodeofCare name="contextEpisodeofCare">contextEpisodeofCare</a>

First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Context (Episode of Care)</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_contextepisodeofcare</td></tr></table>

### <a href=#duration name="duration">duration</a>

Quantity of time the encounter lasted. This excludes the time during leaves of absence.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Duration</td></tr><tr><td>description</td><td>Quantity of time the encounter lasted. This excludes the time during leaves of absence.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_duration</td></tr></table>

### <a href=#encounterClass name="encounterClass">encounterClass</a>

Refers to the class of encounter.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Class</td></tr><tr><td>description</td><td>Refers to the class of encounter.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_encounterclass</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Inpatient</td><td>935000000</td></tr><tr><td>en</td><td>Outpatient</td><td>935000001</td></tr><tr><td>en</td><td>Ambulatory</td><td>935000002</td></tr><tr><td>en</td><td>Emergency</td><td>935000003</td></tr></table></td></tr></table>

### <a href=#encounterClass_display name="encounterClass_display">encounterClass_display</a>

First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#encounterEndDate name="encounterEndDate">encounterEndDate</a>

The start and end time of the encounter.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End Date/Time</td></tr><tr><td>description</td><td>The start and end time of the encounter.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_encounterenddate</td></tr></table>

### <a href=#encounterGroupIdentifier name="encounterGroupIdentifier">encounterGroupIdentifier</a>

The group present at the encounter  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Group</td></tr><tr><td>description</td><td>The group present at the encounter</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_encountergroupidentifier</td></tr></table>

### <a href=#encounterIdentifier name="encounterIdentifier">encounterIdentifier</a>

Identifier(s) by which this encounter is known.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Encounter Number</td></tr><tr><td>description</td><td>Identifier(s) by which this encounter is known.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_encounteridentifier</td></tr></table>

### <a href=#encounterLength name="encounterLength">encounterLength</a>

Quantity of time the encounter lasted. This excludes the time during leaves of absence.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Duration</td></tr><tr><td>description</td><td>Quantity of time the encounter lasted. This excludes the time during leaves of absence.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_encounterlength</td></tr></table>

### <a href=#encounterParentEncounterIdentifier name="encounterParentEncounterIdentifier">encounterParentEncounterIdentifier</a>

Another Encounter of which this encounter is a part of (administratively or in time).  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent Enounter</td></tr><tr><td>description</td><td>Another Encounter of which this encounter is a part of (administratively or in time).</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_encounterparentencounteridentifier</td></tr></table>

### <a href=#encounterPatientIdentifier name="encounterPatientIdentifier">encounterPatientIdentifier</a>

The patient present at the encounter.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Patient</td></tr><tr><td>description</td><td>The patient present at the encounter.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_encounterpatientidentifier</td></tr></table>

### <a href=#encounterPriority name="encounterPriority">encounterPriority</a>

Indicates the urgency of the encounter.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Priority</td></tr><tr><td>description</td><td>Indicates the urgency of the encounter.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_encounterpriority</td></tr></table>

### <a href=#encounterStartDate name="encounterStartDate">encounterStartDate</a>

The start and end time of the encounter.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date/Time</td></tr><tr><td>description</td><td>The start and end time of the encounter.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_encounterstartdate</td></tr></table>

### <a href=#encounterStatus name="encounterStatus">encounterStatus</a>

Refers to the status of encounter.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Refers to the status of encounter.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_encounterstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Planned</td><td>935000000</td></tr><tr><td>en</td><td>Arrived</td><td>935000001</td></tr><tr><td>en</td><td>Triaged</td><td>935000002</td></tr><tr><td>en</td><td>In Progress</td><td>935000003</td></tr><tr><td>en</td><td>On Leave</td><td>935000004</td></tr><tr><td>en</td><td>Finished</td><td>935000005</td></tr><tr><td>en</td><td>Cancelled</td><td>935000006</td></tr><tr><td>en</td><td>Entered in Error</td><td>935000007</td></tr><tr><td>en</td><td>Unknown</td><td>935000008</td></tr></table></td></tr></table>

### <a href=#encounterStatus_display name="encounterStatus_display">encounterStatus_display</a>

First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#hospitalizationAdmitSource name="hospitalizationAdmitSource">hospitalizationAdmitSource</a>

From where patient was admitted (physician referral, transfer).  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Admit Source</td></tr><tr><td>description</td><td>From where patient was admitted (physician referral, transfer).</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_hospitalizationadmitsource</td></tr></table>

### <a href=#hospitalizationDestination name="hospitalizationDestination">hospitalizationDestination</a>

Location to which the patient is discharged.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Destination</td></tr><tr><td>description</td><td>Location to which the patient is discharged.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_hospitalizationdestination</td></tr></table>

### <a href=#hospitalizationDischargeDisposition name="hospitalizationDischargeDisposition">hospitalizationDischargeDisposition</a>

Category or kind of location after discharge.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Discharge Disposition</td></tr><tr><td>description</td><td>Category or kind of location after discharge.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_hospitalizationdischargedisposition</td></tr></table>

### <a href=#hospitalizationOrigin name="hospitalizationOrigin">hospitalizationOrigin</a>

The location from which the patient came before admission.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Origin</td></tr><tr><td>description</td><td>The location from which the patient came before admission.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_hospitalizationorigin</td></tr></table>

### <a href=#hospitalizationPreAdmissionNumber name="hospitalizationPreAdmissionNumber">hospitalizationPreAdmissionNumber</a>

Pre-admission identifier.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pre Admission Number</td></tr><tr><td>description</td><td>Pre-admission identifier.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_hospitalizationpreadmissionnumber</td></tr></table>

### <a href=#hospitalizationReadmission name="hospitalizationReadmission">hospitalizationReadmission</a>

Whether this hospitalization is a readmission and why if known.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Re admission</td></tr><tr><td>description</td><td>Whether this hospitalization is a readmission and why if known.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_hospitalizationreadmission</td></tr></table>

### <a href=#onBehalfOf name="onBehalfOf">onBehalfOf</a>

First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>On behalf of</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_onbehalfof</td></tr></table>

### <a href=#periodEnd name="periodEnd">periodEnd</a>

The start and end time of the encounter.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Period End</td></tr><tr><td>description</td><td>The start and end time of the encounter.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_periodend</td></tr></table>

### <a href=#periodStart name="periodStart">periodStart</a>

The start and end time of the encounter.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Period Start</td></tr><tr><td>description</td><td>The start and end time of the encounter.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_periodstart</td></tr></table>

### <a href=#priority name="priority">priority</a>

Indicates the urgency of the encounter.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Priority</td></tr><tr><td>description</td><td>Indicates the urgency of the encounter.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_priority</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>ASAP</td><td>935000000</td></tr><tr><td>en</td><td>callback results</td><td>935000001</td></tr><tr><td>en</td><td>callback for scheduling</td><td>935000002</td></tr><tr><td>en</td><td>callback placer for scheduling</td><td>935000003</td></tr><tr><td>en</td><td>contact recipient for scheduling</td><td>935000004</td></tr><tr><td>en</td><td>elective</td><td>935000005</td></tr><tr><td>en</td><td>emergency</td><td>935000006</td></tr><tr><td>en</td><td>preop</td><td>935000007</td></tr><tr><td>en</td><td>as needed</td><td>935000008</td></tr><tr><td>en</td><td>routine</td><td>935000009</td></tr><tr><td>en</td><td>rush reporting</td><td>935000010</td></tr><tr><td>en</td><td>stat</td><td>935000011</td></tr><tr><td>en</td><td>timing critical</td><td>935000012</td></tr><tr><td>en</td><td>use as directed</td><td>935000013</td></tr><tr><td>en</td><td>urgent</td><td>935000014</td></tr></table></td></tr></table>

### <a href=#priority_display name="priority_display">priority_display</a>

First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#subjectPatient name="subjectPatient">subjectPatient</a>

The patient or group present at the encounter.  
First included in: electronicMedicalRecords/Encounter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject (Patient)</td></tr><tr><td>description</td><td>The patient or group present at the encounter.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjectpatient</td></tr></table>
