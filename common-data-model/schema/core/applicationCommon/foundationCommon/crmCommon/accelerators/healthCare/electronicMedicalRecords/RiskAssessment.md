---
title: RiskAssessment - Common Data Model | Microsoft Docs
description: This describes the RiskAssessment entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/5/2019
ms.author: nebanfic
---

# Risk Assessment

An assessment of the likely outcome(s) for a patient or other subject as well as the likelihood of each outcome.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/RiskAssessment.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/RiskAssessment  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[ownerId](#ownerId)|Owner Id|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[riskAssessmentId](#riskAssessmentId)|Unique identifier for entity instances|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[stateCode](#stateCode)|Status of the Risk Assessment|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[stateCode_display](#stateCode_display)||<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[statusCode](#statusCode)|Reason for the status of the Risk Assessment|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[statusCode_display](#statusCode_display)||<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[name](#name)|The name of the custom entity.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[basedOn](#basedOn)|A reference to the request that is fulfilled by this risk assessment.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[basis](#basis)|Indicates the source data considered as part of the assessment (Family History, Observations, Procedures, Conditions, etc.).|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[code](#code)|The type of the risk assessment performed.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[comment](#comment)|Additional comments about the risk assessment.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[condition](#condition)|For assessments or prognosis specific to a particular condition, indicates the condition being assessed.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[contextEncounter](#contextEncounter)|The encounter where the assessment was performed.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[episodeOfCare](#episodeOfCare)|The Episode of care type of the encounter where the assessment was performed.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[contextType](#contextType)|Type of context under which assessment is performed|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[contextType_display](#contextType_display)||<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[method](#method)|The algorithm, process or mechanism used to evaluate the risk.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[mitigation](#mitigation)|A description of the steps that might be taken to reduce the identified risk(s).|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[occurrencedatetime](#occurrencedatetime)|The date (and possibly time) the risk assessment was performed.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[occurrenceEndDateTime](#occurrenceEndDateTime)|The date (and possibly time) the risk assessment was performed.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[occurrenceStartDateTime](#occurrenceStartDateTime)|The start date of the risk assessment was performed.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[occurrenceType](#occurrenceType)|Type of time when assessment occurred|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[occurrenceType_display](#occurrenceType_display)||<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[parent](#parent)|A reference to a resource that this risk assessment is part of, such as a Procedure.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[performerDevice](#performerDevice)|The software application that performed the assessment.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[performerPractitioner](#performerPractitioner)|The provider that performed the assessment.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[performerType](#performerType)|Type of performer|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[performerType_display](#performerType_display)||<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[reasonConcept](#reasonConcept)|The reason the risk assessment was performed.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[reasonReference](#reasonReference)|The reason the risk assessment was performed.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[reasonType](#reasonType)|Type of reason why assessment is performed|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[reasonType_display](#reasonType_display)||<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[riskAssessmentNumber](#riskAssessmentNumber)|Business identifier assigned to the risk assessment.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[status](#status)|The status of the Risk Assessment, using the same statuses as an Observation.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[status_display](#status_display)||<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[subjectGroup](#subjectGroup)|The group the risk assessment applies to.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[subjectPatient](#subjectPatient)|The patient the risk assessment applies to.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[subjectType](#subjectType)|The patient or group the risk assessment applies to.|<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|
|[subjectType_display](#subjectType_display)||<a href="RiskAssessment.md" target="_blank">electronicMedicalRecords/RiskAssessment</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#riskAssessmentId name="riskAssessmentId">riskAssessmentId</a>

Unique identifier for entity instances  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Risk Assessment</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msemr_riskassessmentid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Risk Assessment  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Risk Assessment</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Risk Assessment  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Risk Assessment</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_name</td></tr></table>

### <a href=#basedOn name="basedOn">basedOn</a>

A reference to the request that is fulfilled by this risk assessment.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Based On</td></tr><tr><td>description</td><td>A reference to the request that is fulfilled by this risk assessment.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_basedon</td></tr></table>

### <a href=#basis name="basis">basis</a>

Indicates the source data considered as part of the assessment (Family History, Observations, Procedures, Conditions, etc.).  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Basis</td></tr><tr><td>description</td><td>Indicates the source data considered as part of the assessment (Family History, Observations, Procedures, Conditions, etc.).</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_basis</td></tr></table>

### <a href=#code name="code">code</a>

The type of the risk assessment performed.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Code</td></tr><tr><td>description</td><td>The type of the risk assessment performed.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_code</td></tr></table>

### <a href=#comment name="comment">comment</a>

Additional comments about the risk assessment.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Comment</td></tr><tr><td>description</td><td>Additional comments about the risk assessment.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_comment</td></tr></table>

### <a href=#condition name="condition">condition</a>

For assessments or prognosis specific to a particular condition, indicates the condition being assessed.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Condition</td></tr><tr><td>description</td><td>For assessments or prognosis specific to a particular condition, indicates the condition being assessed.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_condition</td></tr></table>

### <a href=#contextEncounter name="contextEncounter">contextEncounter</a>

The encounter where the assessment was performed.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Encounter</td></tr><tr><td>description</td><td>The encounter where the assessment was performed.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_contextencounter</td></tr></table>

### <a href=#episodeOfCare name="episodeOfCare">episodeOfCare</a>

The Episode of care type of the encounter where the assessment was performed.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Episode of Care</td></tr><tr><td>description</td><td>The Episode of care type of the encounter where the assessment was performed.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_contextspisodeofcare</td></tr></table>

### <a href=#contextType name="contextType">contextType</a>

Type of context under which assessment is performed  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Context Type</td></tr><tr><td>description</td><td>Type of context under which assessment is performed</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_contexttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Encounter</td><td>935000000</td></tr><tr><td>en</td><td>Episode Of Care</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#contextType_display name="contextType_display">contextType_display</a>

First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#method name="method">method</a>

The algorithm, process or mechanism used to evaluate the risk.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Method</td></tr><tr><td>description</td><td>The algorithm, process or mechanism used to evaluate the risk.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_method</td></tr></table>

### <a href=#mitigation name="mitigation">mitigation</a>

A description of the steps that might be taken to reduce the identified risk(s).  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mitigation</td></tr><tr><td>description</td><td>A description of the steps that might be taken to reduce the identified risk(s).</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_mitigation</td></tr></table>

### <a href=#occurrencedatetime name="occurrencedatetime">occurrencedatetime</a>

The date (and possibly time) the risk assessment was performed.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date/Time</td></tr><tr><td>description</td><td>The date (and possibly time) the risk assessment was performed.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_occurrencedatetime</td></tr></table>

### <a href=#occurrenceEndDateTime name="occurrenceEndDateTime">occurrenceEndDateTime</a>

The date (and possibly time) the risk assessment was performed.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End Date/Time</td></tr><tr><td>description</td><td>The date (and possibly time) the risk assessment was performed.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_occurrenceenddate</td></tr></table>

### <a href=#occurrenceStartDateTime name="occurrenceStartDateTime">occurrenceStartDateTime</a>

The start date of the risk assessment was performed.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date/Time</td></tr><tr><td>description</td><td>The start date of the risk assessment was performed.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_occurrencestartdate</td></tr></table>

### <a href=#occurrenceType name="occurrenceType">occurrenceType</a>

Type of time when assessment occurred  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Occurrence Type</td></tr><tr><td>description</td><td>Type of time when assessment occurred</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_occurrencetype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Time</td><td>935000000</td></tr><tr><td>en</td><td>Period</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#occurrenceType_display name="occurrenceType_display">occurrenceType_display</a>

First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#parent name="parent">parent</a>

A reference to a resource that this risk assessment is part of, such as a Procedure.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent</td></tr><tr><td>description</td><td>A reference to a resource that this risk assessment is part of, such as a Procedure.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_parent</td></tr></table>

### <a href=#performerDevice name="performerDevice">performerDevice</a>

The software application that performed the assessment.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device</td></tr><tr><td>description</td><td>The software application that performed the assessment.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_performerdevice</td></tr></table>

### <a href=#performerPractitioner name="performerPractitioner">performerPractitioner</a>

The provider that performed the assessment.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Practitioner</td></tr><tr><td>description</td><td>The provider that performed the assessment.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_performerpractitioner</td></tr></table>

### <a href=#performerType name="performerType">performerType</a>

Type of performer  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Performer Type</td></tr><tr><td>description</td><td>Type of performer</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_performertype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Pratitioner</td><td>935000000</td></tr><tr><td>en</td><td>Device</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#performerType_display name="performerType_display">performerType_display</a>

First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#reasonConcept name="reasonConcept">reasonConcept</a>

The reason the risk assessment was performed.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reason Concept</td></tr><tr><td>description</td><td>The reason the risk assessment was performed.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_reasonconcept</td></tr></table>

### <a href=#reasonReference name="reasonReference">reasonReference</a>

The reason the risk assessment was performed.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reason Reference</td></tr><tr><td>description</td><td>The reason the risk assessment was performed.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_reasonentity</td></tr></table>

### <a href=#reasonType name="reasonType">reasonType</a>

Type of reason why assessment is performed  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reason Type</td></tr><tr><td>description</td><td>Type of reason why assessment is performed</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_reasontype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Codeable Concept</td><td>935000000</td></tr><tr><td>en</td><td>Reference</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#reasonType_display name="reasonType_display">reasonType_display</a>

First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#riskAssessmentNumber name="riskAssessmentNumber">riskAssessmentNumber</a>

Business identifier assigned to the risk assessment.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Risk Assessment Number</td></tr><tr><td>description</td><td>Business identifier assigned to the risk assessment.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_riskassessmentnumber</td></tr></table>

### <a href=#status name="status">status</a>

The status of the Risk Assessment, using the same statuses as an Observation.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>The status of the Risk Assessment, using the same statuses as an Observation.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_status</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Registered</td><td>935000000</td></tr><tr><td>en</td><td>Preliminary</td><td>935000001</td></tr><tr><td>en</td><td>Final</td><td>935000002</td></tr><tr><td>en</td><td>Amended</td><td>935000003</td></tr><tr><td>en</td><td>Corrected</td><td>935000004</td></tr><tr><td>en</td><td>Cancelled</td><td>935000005</td></tr><tr><td>en</td><td>Entered in Error</td><td>935000006</td></tr><tr><td>en</td><td>Unknown</td><td>935000007</td></tr></table></td></tr></table>

### <a href=#status_display name="status_display">status_display</a>

First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#subjectGroup name="subjectGroup">subjectGroup</a>

The group the risk assessment applies to.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Group</td></tr><tr><td>description</td><td>The group the risk assessment applies to.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjectgroup</td></tr></table>

### <a href=#subjectPatient name="subjectPatient">subjectPatient</a>

The patient the risk assessment applies to.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Patient</td></tr><tr><td>description</td><td>The patient the risk assessment applies to.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjectpatient</td></tr></table>

### <a href=#subjectType name="subjectType">subjectType</a>

The patient or group the risk assessment applies to.  
First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject Type</td></tr><tr><td>description</td><td>The patient or group the risk assessment applies to.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjecttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Patient</td><td>935000000</td></tr><tr><td>en</td><td>Group</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#subjectType_display name="subjectType_display">subjectType_display</a>

First included in: electronicMedicalRecords/RiskAssessment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
