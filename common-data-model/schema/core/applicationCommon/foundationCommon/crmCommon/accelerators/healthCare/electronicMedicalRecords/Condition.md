---
title: Condition - Common Data Model | Microsoft Docs
description: This describes the Condition entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Condition

A clinical condition, a problem, a diagnosis, or some other event, situation, issue, or clinical concept that has risen to a level of concern.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/Condition.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/Condition  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[conditionId](#conditionId)|Unique identifier for entity instances|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[stateCode](#stateCode)|Status of the Condition|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[stateCode_display](#stateCode_display)||<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[statusCode](#statusCode)|Reason for the status of the Condition|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[statusCode_display](#statusCode_display)||<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[name](#name)|The name of the custom entity.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[abatementAge](#abatementAge)|The date or estimated date that the condition resolved or went into remission. This is called "abatement" because of the many overloaded connotations associated with "remission" or "resolution" -|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[abatementDate](#abatementDate)|The date or estimated date that the condition resolved or went into remission. This is called "abatement" because of the many overloaded connotations associated with "remission" or "resolution"|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[abatementPeriodEndDate](#abatementPeriodEndDate)|The date or estimated date that the condition resolved or went into remission. This is called "abatement" because of the many overloaded connotations associated with "remission" or "resolution"|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[abatementPeriodStartDate](#abatementPeriodStartDate)|The date or estimated date that the condition resolved or went into remission. This is called "abatement" because of the many overloaded connotations associated with "remission" or "resolution"|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[abatementRangeHigh](#abatementRangeHigh)|The date or estimated date that the condition resolved or went into remission. This is called "abatement" because of the many overloaded connotations associated with "remission" or "resolution"|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[abatementRangeLow](#abatementRangeLow)|The date or estimated date that the condition resolved or went into remission. This is called "abatement" because of the many overloaded connotations associated with "remission" or "resolution"|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[abatementString](#abatementString)|The date or estimated date that the condition resolved or went into remission. This is called "abatement" because of the many overloaded connotations associated with "remission" or "resolution"|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[abatementType](#abatementType)|Type of: The date or estimated date that the condition resolved or went into remission. This is called "abatement" because of the many overloaded connotations associated with "remission"/resolution.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[abatementType_display](#abatementType_display)||<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[appointment](#appointment)|A booking of a healthcare event among patient(s), practitioner(s), related person(s), and/or device(s) for a specific date/time. This may result in one or more encounter(s).|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[assertedDate](#assertedDate)|The date on which the existence of the Condition was first asserted or acknowledged.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[asserter](#asserter)|Person who asserts this condition|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[carePlan](#carePlan)|Intention of how one or more practitioners intend to deliver care for a particular patient, group, or community for a period of time, possibly limited to care for a specific condition.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[category](#category)|Categorization of the condition recorded by health care practitioner.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[clinicalStatus](#clinicalStatus)|The clinical status of the condition.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[clinicalStatus_display](#clinicalStatus_display)||<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[conditionCode](#conditionCode)|List of diagnosis/condition codes|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[contextEncounter](#contextEncounter)|Categorization of the condition recorded by health care practitioner.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[contextEpisodeofCare](#contextEpisodeofCare)|Encounter or episode when condition first asserted|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[contextType](#contextType)|Type of: Encounter during which the condition was first asserted.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[contextType_display](#contextType_display)||<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[encounter](#encounter)|An interaction between a patient and healthcare provider(s) for the purpose of providing healthcare service(s) or assessing the health status of a patient.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[isAbatement](#isAbatement)|The date or estimated date that the condition resolved or went into remission. This is called "abatement" because of the many overloaded connotations associated with "remission" or "resolution"|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[onsetAge](#onsetAge)|Estimated or actual date or date-time the condition began, in the opinion of the clinician.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[onsetDate](#onsetDate)|Estimated or actual date or date-time the condition began, in the opinion of the clinician.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[onsetPeriodEndDate](#onsetPeriodEndDate)|Estimated or actual date or date-time the condition began, in the opinion of the clinician.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[onsetPeriodStartDate](#onsetPeriodStartDate)|Estimated or actual date or date-time the condition began, in the opinion of the clinician.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[onsetRangeHigh](#onsetRangeHigh)|Estimated or actual date or date-time the condition began, in the opinion of the clinician.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[onsetRangeLow](#onsetRangeLow)|Estimated or actual date or date-time the condition began, in the opinion of the clinician.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[onsetString](#onsetString)|Estimated or actual date or date-time the condition began, in the opinion of the clinician.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[onsetType](#onsetType)|Type of: Estimated or actual date or date-time the condition began, in the opinion of the clinician.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[onsetType_display](#onsetType_display)||<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[practitioner](#practitioner)|Individual who is making the condition statement.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[reasonReferenceReferralRequest](#reasonReferenceReferralRequest)||<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[severity](#severity)|Grading  of the severity of the condition recorded|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[stage](#stage)|Specific stage of condition|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[subjectType](#subjectType)|Type of: Indicates the patient or group who the condition record is associated with.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[subjectType_display](#subjectType_display)||<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[subjectTypeGroup](#subjectTypeGroup)|Indicates the patient or group who the condition record is associated with.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[subjectTypePatient](#subjectTypePatient)|Indicates the patient or group who the condition record is associated with.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[verificationStatus](#verificationStatus)|Type of: The verification status to support the clinical status of the condition.|<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|
|[verificationStatus_display](#verificationStatus_display)||<a href="Condition.md" target="_blank">electronicMedicalRecords/Condition</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#conditionId name="conditionId">conditionId</a>

Unique identifier for entity instances  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Condition</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msemr_conditionid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Condition  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Condition</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Condition  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Condition</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_name</td></tr></table>

### <a href=#abatementAge name="abatementAge">abatementAge</a>

The date or estimated date that the condition resolved or went into remission. This is called "abatement" because of the many overloaded connotations associated with "remission" or "resolution" -  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Abatement Age</td></tr><tr><td>description</td><td>The date or estimated date that the condition resolved or went into remission. This is called "abatement" because of the many overloaded connotations associated with "remission" or "resolution" -</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_abatementage</td></tr></table>

### <a href=#abatementDate name="abatementDate">abatementDate</a>

The date or estimated date that the condition resolved or went into remission. This is called "abatement" because of the many overloaded connotations associated with "remission" or "resolution"  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Abatement Date</td></tr><tr><td>description</td><td>The date or estimated date that the condition resolved or went into remission. This is called "abatement" because of the many overloaded connotations associated with "remission" or "resolution"</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_abatementdate</td></tr></table>

### <a href=#abatementPeriodEndDate name="abatementPeriodEndDate">abatementPeriodEndDate</a>

The date or estimated date that the condition resolved or went into remission. This is called "abatement" because of the many overloaded connotations associated with "remission" or "resolution"  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Abatement Period End Date</td></tr><tr><td>description</td><td>The date or estimated date that the condition resolved or went into remission. This is called "abatement" because of the many overloaded connotations associated with "remission" or "resolution"</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_abatementperiodenddate</td></tr></table>

### <a href=#abatementPeriodStartDate name="abatementPeriodStartDate">abatementPeriodStartDate</a>

The date or estimated date that the condition resolved or went into remission. This is called "abatement" because of the many overloaded connotations associated with "remission" or "resolution"  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Abatement Period Start Date</td></tr><tr><td>description</td><td>The date or estimated date that the condition resolved or went into remission. This is called "abatement" because of the many overloaded connotations associated with "remission" or "resolution"</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_abatementperiodstartdate</td></tr></table>

### <a href=#abatementRangeHigh name="abatementRangeHigh">abatementRangeHigh</a>

The date or estimated date that the condition resolved or went into remission. This is called "abatement" because of the many overloaded connotations associated with "remission" or "resolution"  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Abatement Range High</td></tr><tr><td>description</td><td>The date or estimated date that the condition resolved or went into remission. This is called "abatement" because of the many overloaded connotations associated with "remission" or "resolution"</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_abatementrangehigh</td></tr></table>

### <a href=#abatementRangeLow name="abatementRangeLow">abatementRangeLow</a>

The date or estimated date that the condition resolved or went into remission. This is called "abatement" because of the many overloaded connotations associated with "remission" or "resolution"  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Abatement Range Low</td></tr><tr><td>description</td><td>The date or estimated date that the condition resolved or went into remission. This is called "abatement" because of the many overloaded connotations associated with "remission" or "resolution"</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_abatementrangelow</td></tr></table>

### <a href=#abatementString name="abatementString">abatementString</a>

The date or estimated date that the condition resolved or went into remission. This is called "abatement" because of the many overloaded connotations associated with "remission" or "resolution"  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Abatement String</td></tr><tr><td>description</td><td>The date or estimated date that the condition resolved or went into remission. This is called "abatement" because of the many overloaded connotations associated with "remission" or "resolution"</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_abatementstring</td></tr></table>

### <a href=#abatementType name="abatementType">abatementType</a>

Type of: The date or estimated date that the condition resolved or went into remission. This is called "abatement" because of the many overloaded connotations associated with "remission"/resolution.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Abatement Type</td></tr><tr><td>description</td><td>Type of: The date or estimated date that the condition resolved or went into remission. This is called "abatement" because of the many overloaded connotations associated with "remission"/resolution.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_abatementtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Age</td><td>935000000</td></tr><tr><td>en</td><td>Period</td><td>935000001</td></tr><tr><td>en</td><td>Range</td><td>935000002</td></tr><tr><td>en</td><td>String</td><td>935000003</td></tr><tr><td>en</td><td>Boolean</td><td>935000004</td></tr><tr><td>en</td><td>Date time</td><td>935000005</td></tr></table></td></tr></table>

### <a href=#abatementType_display name="abatementType_display">abatementType_display</a>

First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#appointment name="appointment">appointment</a>

A booking of a healthcare event among patient(s), practitioner(s), related person(s), and/or device(s) for a specific date/time. This may result in one or more encounter(s).  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Appointment</td></tr><tr><td>description</td><td>A booking of a healthcare event among patient(s), practitioner(s), related person(s), and/or device(s) for a specific date/time. This may result in one or more encounter(s).</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_appointment</td></tr></table>

### <a href=#assertedDate name="assertedDate">assertedDate</a>

The date on which the existence of the Condition was first asserted or acknowledged.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Asserted Date</td></tr><tr><td>description</td><td>The date on which the existence of the Condition was first asserted or acknowledged.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_asserteddate</td></tr></table>

### <a href=#asserter name="asserter">asserter</a>

Person who asserts this condition  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Asserter</td></tr><tr><td>description</td><td>Person who asserts this condition</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_asserter</td></tr></table>

### <a href=#carePlan name="carePlan">carePlan</a>

Intention of how one or more practitioners intend to deliver care for a particular patient, group, or community for a period of time, possibly limited to care for a specific condition.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Care Plan</td></tr><tr><td>description</td><td>Intention of how one or more practitioners intend to deliver care for a particular patient, group, or community for a period of time, possibly limited to care for a specific condition.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_careplan</td></tr></table>

### <a href=#category name="category">category</a>

Categorization of the condition recorded by health care practitioner.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Category</td></tr><tr><td>description</td><td>Categorization of the condition recorded by health care practitioner.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_category</td></tr></table>

### <a href=#clinicalStatus name="clinicalStatus">clinicalStatus</a>

The clinical status of the condition.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Clinical Status</td></tr><tr><td>description</td><td>The clinical status of the condition.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_clinicalstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>935000000</td></tr><tr><td>en</td><td>Recurrence</td><td>935000001</td></tr><tr><td>en</td><td>Inactive</td><td>935000002</td></tr><tr><td>en</td><td>Remission</td><td>935000003</td></tr><tr><td>en</td><td>Resolved</td><td>935000004</td></tr></table></td></tr></table>

### <a href=#clinicalStatus_display name="clinicalStatus_display">clinicalStatus_display</a>

First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#conditionCode name="conditionCode">conditionCode</a>

List of diagnosis/condition codes  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Condition Code</td></tr><tr><td>description</td><td>List of diagnosis/condition codes</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_conditioncode</td></tr></table>

### <a href=#contextEncounter name="contextEncounter">contextEncounter</a>

Categorization of the condition recorded by health care practitioner.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Context</td></tr><tr><td>description</td><td>Categorization of the condition recorded by health care practitioner.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_contextencounter</td></tr></table>

### <a href=#contextEpisodeofCare name="contextEpisodeofCare">contextEpisodeofCare</a>

Encounter or episode when condition first asserted  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Context</td></tr><tr><td>description</td><td>Encounter or episode when condition first asserted</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_contextepisodeofcare</td></tr></table>

### <a href=#contextType name="contextType">contextType</a>

Type of: Encounter during which the condition was first asserted.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Context Type</td></tr><tr><td>description</td><td>Type of: Encounter during which the condition was first asserted.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_contexttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Encounter</td><td>935000000</td></tr><tr><td>en</td><td>Episode Of Care</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#contextType_display name="contextType_display">contextType_display</a>

First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#encounter name="encounter">encounter</a>

An interaction between a patient and healthcare provider(s) for the purpose of providing healthcare service(s) or assessing the health status of a patient.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Encounter</td></tr><tr><td>description</td><td>An interaction between a patient and healthcare provider(s) for the purpose of providing healthcare service(s) or assessing the health status of a patient.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_encounter</td></tr></table>

### <a href=#isAbatement name="isAbatement">isAbatement</a>

The date or estimated date that the condition resolved or went into remission. This is called "abatement" because of the many overloaded connotations associated with "remission" or "resolution"  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Abatement</td></tr><tr><td>description</td><td>The date or estimated date that the condition resolved or went into remission. This is called "abatement" because of the many overloaded connotations associated with "remission" or "resolution"</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_isabatement</td></tr></table>

### <a href=#onsetAge name="onsetAge">onsetAge</a>

Estimated or actual date or date-time the condition began, in the opinion of the clinician.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Onset Age</td></tr><tr><td>description</td><td>Estimated or actual date or date-time the condition began, in the opinion of the clinician.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_onsetage</td></tr></table>

### <a href=#onsetDate name="onsetDate">onsetDate</a>

Estimated or actual date or date-time the condition began, in the opinion of the clinician.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Onset Date</td></tr><tr><td>description</td><td>Estimated or actual date or date-time the condition began, in the opinion of the clinician.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_onsetdate</td></tr></table>

### <a href=#onsetPeriodEndDate name="onsetPeriodEndDate">onsetPeriodEndDate</a>

Estimated or actual date or date-time the condition began, in the opinion of the clinician.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Onset Period End Date</td></tr><tr><td>description</td><td>Estimated or actual date or date-time the condition began, in the opinion of the clinician.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_onsetperiodenddate</td></tr></table>

### <a href=#onsetPeriodStartDate name="onsetPeriodStartDate">onsetPeriodStartDate</a>

Estimated or actual date or date-time the condition began, in the opinion of the clinician.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Onset Period Start Date</td></tr><tr><td>description</td><td>Estimated or actual date or date-time the condition began, in the opinion of the clinician.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_onsetperiodstartdate</td></tr></table>

### <a href=#onsetRangeHigh name="onsetRangeHigh">onsetRangeHigh</a>

Estimated or actual date or date-time the condition began, in the opinion of the clinician.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Onset Range High</td></tr><tr><td>description</td><td>Estimated or actual date or date-time the condition began, in the opinion of the clinician.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_onsetrangehigh</td></tr></table>

### <a href=#onsetRangeLow name="onsetRangeLow">onsetRangeLow</a>

Estimated or actual date or date-time the condition began, in the opinion of the clinician.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Onset Range Low</td></tr><tr><td>description</td><td>Estimated or actual date or date-time the condition began, in the opinion of the clinician.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_onsetrangelow</td></tr></table>

### <a href=#onsetString name="onsetString">onsetString</a>

Estimated or actual date or date-time the condition began, in the opinion of the clinician.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Onset String</td></tr><tr><td>description</td><td>Estimated or actual date or date-time the condition began, in the opinion of the clinician.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_onsetstring</td></tr></table>

### <a href=#onsetType name="onsetType">onsetType</a>

Type of: Estimated or actual date or date-time the condition began, in the opinion of the clinician.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Onset Type</td></tr><tr><td>description</td><td>Type of: Estimated or actual date or date-time the condition began, in the opinion of the clinician.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_onsettype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Age</td><td>935000000</td></tr><tr><td>en</td><td>Period</td><td>935000001</td></tr><tr><td>en</td><td>Range</td><td>935000002</td></tr><tr><td>en</td><td>String</td><td>935000003</td></tr></table></td></tr></table>

### <a href=#onsetType_display name="onsetType_display">onsetType_display</a>

First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#practitioner name="practitioner">practitioner</a>

Individual who is making the condition statement.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Practitioner</td></tr><tr><td>description</td><td>Individual who is making the condition statement.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_practitioner</td></tr></table>

### <a href=#reasonReferenceReferralRequest name="reasonReferenceReferralRequest">reasonReferenceReferralRequest</a>

First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reason Reference (Referral Request)</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_reasonreferencereferralrequest</td></tr></table>

### <a href=#severity name="severity">severity</a>

Grading  of the severity of the condition recorded  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Severity</td></tr><tr><td>description</td><td>Grading  of the severity of the condition recorded</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_severity</td></tr></table>

### <a href=#stage name="stage">stage</a>

Specific stage of condition  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stage</td></tr><tr><td>description</td><td>Specific stage of condition</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_stage</td></tr></table>

### <a href=#subjectType name="subjectType">subjectType</a>

Type of: Indicates the patient or group who the condition record is associated with.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject Type</td></tr><tr><td>description</td><td>Type of: Indicates the patient or group who the condition record is associated with.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjecttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Patient</td><td>935000000</td></tr><tr><td>en</td><td>Group</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#subjectType_display name="subjectType_display">subjectType_display</a>

First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#subjectTypeGroup name="subjectTypeGroup">subjectTypeGroup</a>

Indicates the patient or group who the condition record is associated with.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Group</td></tr><tr><td>description</td><td>Indicates the patient or group who the condition record is associated with.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjecttypegroup</td></tr></table>

### <a href=#subjectTypePatient name="subjectTypePatient">subjectTypePatient</a>

Indicates the patient or group who the condition record is associated with.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Patient</td></tr><tr><td>description</td><td>Indicates the patient or group who the condition record is associated with.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjecttypepatient</td></tr></table>

### <a href=#verificationStatus name="verificationStatus">verificationStatus</a>

Type of: The verification status to support the clinical status of the condition.  
First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Verification Status</td></tr><tr><td>description</td><td>Type of: The verification status to support the clinical status of the condition.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_verificationstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Provisional</td><td>935000000</td></tr><tr><td>en</td><td>Differential</td><td>935000001</td></tr><tr><td>en</td><td>Confirmed</td><td>935000002</td></tr><tr><td>en</td><td>Refuted</td><td>935000003</td></tr><tr><td>en</td><td>Entered-In-Error</td><td>935000004</td></tr><tr><td>en</td><td>Unknown</td><td>935000005</td></tr></table></td></tr></table>

### <a href=#verificationStatus_display name="verificationStatus_display">verificationStatus_display</a>

First included in: electronicMedicalRecords/Condition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
