---
title: RelatedPerson - Common Data Model | Microsoft Docs
description: This describes the RelatedPerson entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Related Person

Information about a person who is involved in the care for a patient but who isn't the target of healthcare and has no formal responsibility in the care process.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/RelatedPerson.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/RelatedPerson  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|
|[ownerId](#ownerId)|Owner Id|<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|
|[relatedPersonId](#relatedPersonId)|Unique identifier for entity instances|<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|
|[stateCode](#stateCode)|Status of the Related Person|<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|
|[stateCode_display](#stateCode_display)||<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|
|[statusCode](#statusCode)|Reason for the status of the Related Person|<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|
|[statusCode_display](#statusCode_display)||<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|
|[name](#name)|The name of the custom entity.|<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|
|[active](#active)|Whether this related person record is in active use.|<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|
|[patient](#patient)|The patient this person is related to.|<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|
|[relatedPerson](#relatedPerson)|Information about a person who is involved in the care for a patient but who isn't the target of healthcare and has no formal responsibility in the care process.|<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|
|[relatedPersonPeriodEndDate](#relatedPersonPeriodEndDate)|The period of time that this relationship is considered to be valid. If there are no dates defined, then the interval is unknown.|<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|
|[relatedPersonPeriodStartDate](#relatedPersonPeriodStartDate)|The period of time that this relationship is considered to be valid. If there are no dates defined, then the interval is unknown.|<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|
|[relationship](#relationship)|The nature of the relationship between a patient and the related person.|<a href="RelatedPerson.md" target="_blank">electronicMedicalRecords/RelatedPerson</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#relatedPersonId name="relatedPersonId">relatedPersonId</a>

Unique identifier for entity instances  
First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Related Person</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msemr_relatedpersonid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Related Person  
First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Related Person</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Related Person  
First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Related Person</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_name</td></tr></table>

### <a href=#active name="active">active</a>

Whether this related person record is in active use.  
First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Active</td></tr><tr><td>description</td><td>Whether this related person record is in active use.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_active</td></tr></table>

### <a href=#patient name="patient">patient</a>

The patient this person is related to.  
First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Patient</td></tr><tr><td>description</td><td>The patient this person is related to.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_patient</td></tr></table>

### <a href=#relatedPerson name="relatedPerson">relatedPerson</a>

Information about a person who is involved in the care for a patient but who isn't the target of healthcare and has no formal responsibility in the care process.  
First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Related Person</td></tr><tr><td>description</td><td>Information about a person who is involved in the care for a patient but who isn't the target of healthcare and has no formal responsibility in the care process.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_relatedperson</td></tr></table>

### <a href=#relatedPersonPeriodEndDate name="relatedPersonPeriodEndDate">relatedPersonPeriodEndDate</a>

The period of time that this relationship is considered to be valid. If there are no dates defined, then the interval is unknown.  
First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Related Person Period End Date</td></tr><tr><td>description</td><td>The period of time that this relationship is considered to be valid. If there are no dates defined, then the interval is unknown.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_relatedpersonperiodenddate</td></tr></table>

### <a href=#relatedPersonPeriodStartDate name="relatedPersonPeriodStartDate">relatedPersonPeriodStartDate</a>

The period of time that this relationship is considered to be valid. If there are no dates defined, then the interval is unknown.  
First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Related Person Period Start Date</td></tr><tr><td>description</td><td>The period of time that this relationship is considered to be valid. If there are no dates defined, then the interval is unknown.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_relatedpersonperiodstartdate</td></tr></table>

### <a href=#relationship name="relationship">relationship</a>

The nature of the relationship between a patient and the related person.  
First included in: electronicMedicalRecords/RelatedPerson (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Relationship</td></tr><tr><td>description</td><td>The nature of the relationship between a patient and the related person.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_relationship</td></tr></table>
