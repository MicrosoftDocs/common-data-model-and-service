---
title: AllergyIntolerance - Common Data Model | Microsoft Docs
description: This describes the AllergyIntolerance entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# Allergy Intolerance

Risk of harmful or undesirable, physiological response which is unique to an individual and associated with exposure to a substance.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/AllergyIntolerance.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/AllergyIntolerance  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[ownerId](#ownerId)|Owner Id|<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[allergyIntoleranceId](#allergyIntoleranceId)|Unique identifier for entity instances|<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[stateCode](#stateCode)|Status of the Allergy Intolerance|<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[stateCode_display](#stateCode_display)||<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[statusCode](#statusCode)|Reason for the status of the Allergy Intolerance|<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[statusCode_display](#statusCode_display)||<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[name](#name)|The name of the custom entity.|<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[code](#code)||<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[criticality](#criticality)||<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[criticality_display](#criticality_display)||<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[type](#type)||<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[type_display](#type_display)||<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[verificationStatus](#verificationStatus)||<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|
|[verificationStatus_display](#verificationStatus_display)||<a href="AllergyIntolerance.md" target="_blank">electronicMedicalRecords/AllergyIntolerance</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#allergyIntoleranceId name="allergyIntoleranceId">allergyIntoleranceId</a>

Unique identifier for entity instances  
First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allergy Intolerance</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msemr_allergyintoleranceid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Allergy Intolerance  
First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Allergy Intolerance</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Allergy Intolerance  
First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Allergy Intolerance</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr><tr><td>en</td><td>Resolve</td><td>935000000</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_name</td></tr></table>

### <a href=#code name="code">code</a>

First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Code</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_code</td></tr></table>

### <a href=#criticality name="criticality">criticality</a>

First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Criticality</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_criticality</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Low Risk</td><td>935000000</td></tr><tr><td>en</td><td>High Risk</td><td>935000001</td></tr><tr><td>en</td><td>Unable to Assess Risk</td><td>935000002</td></tr></table></td></tr></table>

### <a href=#criticality_display name="criticality_display">criticality_display</a>

First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#type name="type">type</a>

First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_type</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Allergy</td><td>935000000</td></tr><tr><td>en</td><td>Intolerance</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#type_display name="type_display">type_display</a>

First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#verificationStatus name="verificationStatus">verificationStatus</a>

First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Verification Status</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_verificationstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Unconfirmed</td><td>935000000</td></tr><tr><td>en</td><td>Confirmed</td><td>935000001</td></tr><tr><td>en</td><td>Refuted</td><td>935000002</td></tr><tr><td>en</td><td>Entered In Error</td><td>935000003</td></tr></table></td></tr></table>

### <a href=#verificationStatus_display name="verificationStatus_display">verificationStatus_display</a>

First included in: electronicMedicalRecords/AllergyIntolerance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
