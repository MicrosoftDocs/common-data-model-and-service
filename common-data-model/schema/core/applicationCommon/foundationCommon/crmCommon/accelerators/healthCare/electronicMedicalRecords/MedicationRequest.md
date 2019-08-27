---
title: MedicationRequest - Common Data Model | Microsoft Docs
description: This describes the MedicationRequest entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Medication Request

An order or a request for supplying medication and the instructions for administering the medication to a patient.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/MedicationRequest.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/MedicationRequest  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[ownerId](#ownerId)|Owner Id|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[medicationRequestId](#medicationRequestId)|Unique identifier for entity instances|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[stateCode](#stateCode)|Status of the Medication Request|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[stateCode_display](#stateCode_display)||<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[statusCode](#statusCode)|Reason for the status of the Medication Request|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[statusCode_display](#statusCode_display)||<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[name](#name)|The name of the custom entity.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[authoredOn](#authoredOn)|The date (and perhaps time) when the prescription was initially written or authored on.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[category](#category)|Indicates the type of medication request (for example, where the medication is expected to be consumed or administered or the type of treatment.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[contextType](#contextType)|A link to an encounter, or episode of care, that identifies the particular occurrence or set occurrences of contact between patient and health care provider.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[contextType_display](#contextType_display)||<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[contextTypeEncounter](#contextTypeEncounter)|A link to an encounter that identifies the particular occurrence or set occurrences of contact between patient and health care provider.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[contextTypeEpisodeOfCare](#contextTypeEpisodeOfCare)|A link to an episode of care, that identifies the particular occurrence or set occurrences of contact between patient and health care provider.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[dispenseRequestNumberofRepeatsAllowed](#dispenseRequestNumberofRepeatsAllowed)|An integer indicating the number of times, in addition to the original dispense, (aka refills or repeats) that the patient can receive the prescribed medication.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[dispenseRequestPerformer](#dispenseRequestPerformer)|Indicates the intended dispensing Organization specified by the Prescriber.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[dispenseRequestQuantity](#dispenseRequestQuantity)|The amount that is to be dispensed for one fill.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[dispenseRequestValidityPeriodEndDate](#dispenseRequestValidityPeriodEndDate)|This indicates the validity period of a prescription (stale dating the Prescription).|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[dispenseRequestValidityPeriodStartDate](#dispenseRequestValidityPeriodStartDate)|This indicates the validity period of a prescription (stale dating the Prescription).|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[expectedSupplyDuration](#expectedSupplyDuration)|Identifies the period time over which the supplied product is expected to be used, or the length of time the dispense is expected to last.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[groupIdentifier](#groupIdentifier)|A shared identifier common to all requests that were authorized more or less simultaneously by a single author, representing the identifier of the requisition or prescription.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[identifier](#identifier)|This records identifiers associated with this medication request that are defined by business processes and/or used to refer to it when a direct URL reference to the resource itself is not appropriate|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[intent](#intent)|Whether the request is a proposal, plan, or an original order.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[intent_display](#intent_display)||<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[medicationType](#medicationType)|Identifies the medication being requested.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[medicationType_display](#medicationType_display)||<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[medicationTypeCodeableConcept](#medicationTypeCodeableConcept)|Identifies the medication being requested.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[medicationReference](#medicationReference)|Identifies the medication being requested.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[priority](#priority)|Indicates how quickly the Medication Request should be addressed with respect to other requests.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[priority_display](#priority_display)||<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[priorPrescription](#priorPrescription)|A link to a resource representing an earlier order related order or prescription.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[recorder](#recorder)|The person who entered the order on behalf of another individual for example in the case of a verbal or a telephone order.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[requesterAgentType](#requesterAgentType)|The healthcare professional responsible for authorizing the initial prescription.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[requesterAgentType_display](#requesterAgentType_display)||<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[requesterAgentTypeDevice](#requesterAgentTypeDevice)|The healthcare professional responsible for authorizing the initial prescription.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[requesterAgentTypeOrganization](#requesterAgentTypeOrganization)|The healthcare professional responsible for authorizing the initial prescription.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[requesterAgentTypePatient](#requesterAgentTypePatient)|The healthcare professional responsible for authorizing the initial prescription.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[requesterAgentTypePractitioner](#requesterAgentTypePractitioner)|The healthcare professional responsible for authorizing the initial prescription.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[requesterAgentTypeRelatedPerson](#requesterAgentTypeRelatedPerson)|The healthcare professional responsible for authorizing the initial prescription.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[requesterOnBehalfOf](#requesterOnBehalfOf)|The organization the device or practitioner was acting on behalf of.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[status](#status)|A code specifying the current state of the order. Generally, this will be active or completed state.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[status_display](#status_display)||<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[subjectType](#subjectType)|A link to a resource representing the person or set of individuals to whom the medication will be given.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[subjectType_display](#subjectType_display)||<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[subjectTypeGroup](#subjectTypeGroup)|A link to a resource representing the person or set of individuals to whom the medication will be given.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[subjectTypePatient](#subjectTypePatient)|A link to a resource representing the person or set of individuals to whom the medication will be given.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[substitutionAllowed](#substitutionAllowed)|True if the Prescriber allows a different drug to be dispensed from what was prescribed.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|
|[substitutionReason](#substitutionReason)|Indicates the reason for the substitution, or why substitution must or must not be performed.|<a href="MedicationRequest.md" target="_blank">electronicMedicalRecords/MedicationRequest</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#medicationRequestId name="medicationRequestId">medicationRequestId</a>

Unique identifier for entity instances  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Medication Request</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msemr_medicationrequestid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Medication Request  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Medication Request</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Medication Request  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Medication Request</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_name</td></tr></table>

### <a href=#authoredOn name="authoredOn">authoredOn</a>

The date (and perhaps time) when the prescription was initially written or authored on.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Authored On</td></tr><tr><td>description</td><td>The date (and perhaps time) when the prescription was initially written or authored on.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_authoredon</td></tr></table>

### <a href=#category name="category">category</a>

Indicates the type of medication request (for example, where the medication is expected to be consumed or administered or the type of treatment.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Category</td></tr><tr><td>description</td><td>Indicates the type of medication request (for example, where the medication is expected to be consumed or administered or the type of treatment.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_category</td></tr></table>

### <a href=#contextType name="contextType">contextType</a>

A link to an encounter, or episode of care, that identifies the particular occurrence or set occurrences of contact between patient and health care provider.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Context Type</td></tr><tr><td>description</td><td>A link to an encounter, or episode of care, that identifies the particular occurrence or set occurrences of contact between patient and health care provider.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_contexttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Encounter</td><td>935000000</td></tr><tr><td>en</td><td>Episode of Care</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#contextType_display name="contextType_display">contextType_display</a>

First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#contextTypeEncounter name="contextTypeEncounter">contextTypeEncounter</a>

A link to an encounter that identifies the particular occurrence or set occurrences of contact between patient and health care provider.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Encounter</td></tr><tr><td>description</td><td>A link to an encounter that identifies the particular occurrence or set occurrences of contact between patient and health care provider.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_contexttypeencounter</td></tr></table>

### <a href=#contextTypeEpisodeOfCare name="contextTypeEpisodeOfCare">contextTypeEpisodeOfCare</a>

A link to an episode of care, that identifies the particular occurrence or set occurrences of contact between patient and health care provider.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Episode of Care</td></tr><tr><td>description</td><td>A link to an episode of care, that identifies the particular occurrence or set occurrences of contact between patient and health care provider.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_contexttypeepisodeofcare</td></tr></table>

### <a href=#dispenseRequestNumberofRepeatsAllowed name="dispenseRequestNumberofRepeatsAllowed">dispenseRequestNumberofRepeatsAllowed</a>

An integer indicating the number of times, in addition to the original dispense, (aka refills or repeats) that the patient can receive the prescribed medication.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Dispense Request Number of Repeats Allowed</td></tr><tr><td>description</td><td>An integer indicating the number of times, in addition to the original dispense, (aka refills or repeats) that the patient can receive the prescribed medication.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_dispenserequestnumberofrepeatsallowed</td></tr></table>

### <a href=#dispenseRequestPerformer name="dispenseRequestPerformer">dispenseRequestPerformer</a>

Indicates the intended dispensing Organization specified by the Prescriber.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Performer</td></tr><tr><td>description</td><td>Indicates the intended dispensing Organization specified by the Prescriber.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_dispenserequestperformer</td></tr></table>

### <a href=#dispenseRequestQuantity name="dispenseRequestQuantity">dispenseRequestQuantity</a>

The amount that is to be dispensed for one fill.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Dispense Request Quantity</td></tr><tr><td>description</td><td>The amount that is to be dispensed for one fill.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_dispenserequestquantity</td></tr></table>

### <a href=#dispenseRequestValidityPeriodEndDate name="dispenseRequestValidityPeriodEndDate">dispenseRequestValidityPeriodEndDate</a>

This indicates the validity period of a prescription (stale dating the Prescription).  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Dispense Request Validity Period End Date</td></tr><tr><td>description</td><td>This indicates the validity period of a prescription (stale dating the Prescription).</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_dispenserequestvalidityperiodenddate</td></tr></table>

### <a href=#dispenseRequestValidityPeriodStartDate name="dispenseRequestValidityPeriodStartDate">dispenseRequestValidityPeriodStartDate</a>

This indicates the validity period of a prescription (stale dating the Prescription).  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Dispense Request Validity Period Start Date</td></tr><tr><td>description</td><td>This indicates the validity period of a prescription (stale dating the Prescription).</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_dispenserequestvalidityperiodstartdate</td></tr></table>

### <a href=#expectedSupplyDuration name="expectedSupplyDuration">expectedSupplyDuration</a>

Identifies the period time over which the supplied product is expected to be used, or the length of time the dispense is expected to last.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expected Supply Duration</td></tr><tr><td>description</td><td>Identifies the period time over which the supplied product is expected to be used, or the length of time the dispense is expected to last.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_expectedsupplyduration</td></tr></table>

### <a href=#groupIdentifier name="groupIdentifier">groupIdentifier</a>

A shared identifier common to all requests that were authorized more or less simultaneously by a single author, representing the identifier of the requisition or prescription.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Group Identifier</td></tr><tr><td>description</td><td>A shared identifier common to all requests that were authorized more or less simultaneously by a single author, representing the identifier of the requisition or prescription.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_groupidentifier</td></tr></table>

### <a href=#identifier name="identifier">identifier</a>

This records identifiers associated with this medication request that are defined by business processes and/or used to refer to it when a direct URL reference to the resource itself is not appropriate  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Medication Request Number</td></tr><tr><td>description</td><td>This records identifiers associated with this medication request that are defined by business processes and/or used to refer to it when a direct URL reference to the resource itself is not appropriate</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_identifier</td></tr></table>

### <a href=#intent name="intent">intent</a>

Whether the request is a proposal, plan, or an original order.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Intent</td></tr><tr><td>description</td><td>Whether the request is a proposal, plan, or an original order.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_intent</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Proposal</td><td>935000000</td></tr><tr><td>en</td><td>Plan</td><td>935000001</td></tr><tr><td>en</td><td>Order</td><td>935000002</td></tr><tr><td>en</td><td>Instance Order</td><td>935000003</td></tr></table></td></tr></table>

### <a href=#intent_display name="intent_display">intent_display</a>

First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#medicationType name="medicationType">medicationType</a>

Identifies the medication being requested.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Medication Type</td></tr><tr><td>description</td><td>Identifies the medication being requested.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_medicationtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Medication Code</td><td>935000000</td></tr><tr><td>en</td><td>Medication Reference</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#medicationType_display name="medicationType_display">medicationType_display</a>

First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#medicationTypeCodeableConcept name="medicationTypeCodeableConcept">medicationTypeCodeableConcept</a>

Identifies the medication being requested.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Medication Code</td></tr><tr><td>description</td><td>Identifies the medication being requested.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_medicationtypecodeableconcept</td></tr></table>

### <a href=#medicationReference name="medicationReference">medicationReference</a>

Identifies the medication being requested.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Medication Reference</td></tr><tr><td>description</td><td>Identifies the medication being requested.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_medicationtypereference</td></tr></table>

### <a href=#priority name="priority">priority</a>

Indicates how quickly the Medication Request should be addressed with respect to other requests.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Priority</td></tr><tr><td>description</td><td>Indicates how quickly the Medication Request should be addressed with respect to other requests.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_priority</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Routine</td><td>935000000</td></tr><tr><td>en</td><td>Urgent</td><td>935000001</td></tr><tr><td>en</td><td>Stat</td><td>935000002</td></tr><tr><td>en</td><td>ASAP</td><td>935000003</td></tr></table></td></tr></table>

### <a href=#priority_display name="priority_display">priority_display</a>

First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#priorPrescription name="priorPrescription">priorPrescription</a>

A link to a resource representing an earlier order related order or prescription.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Prior Prescription</td></tr><tr><td>description</td><td>A link to a resource representing an earlier order related order or prescription.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_priorprescription</td></tr></table>

### <a href=#recorder name="recorder">recorder</a>

The person who entered the order on behalf of another individual for example in the case of a verbal or a telephone order.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recorder</td></tr><tr><td>description</td><td>The person who entered the order on behalf of another individual for example in the case of a verbal or a telephone order.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_recorder</td></tr></table>

### <a href=#requesterAgentType name="requesterAgentType">requesterAgentType</a>

The healthcare professional responsible for authorizing the initial prescription.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requester Agent Type</td></tr><tr><td>description</td><td>The healthcare professional responsible for authorizing the initial prescription.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteragenttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Practitioner</td><td>935000000</td></tr><tr><td>en</td><td>Organization</td><td>935000001</td></tr><tr><td>en</td><td>Patient</td><td>935000002</td></tr><tr><td>en</td><td>Related Person</td><td>935000003</td></tr><tr><td>en</td><td>Device</td><td>935000004</td></tr></table></td></tr></table>

### <a href=#requesterAgentType_display name="requesterAgentType_display">requesterAgentType_display</a>

First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#requesterAgentTypeDevice name="requesterAgentTypeDevice">requesterAgentTypeDevice</a>

The healthcare professional responsible for authorizing the initial prescription.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device</td></tr><tr><td>description</td><td>The healthcare professional responsible for authorizing the initial prescription.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteragenttypedevice</td></tr></table>

### <a href=#requesterAgentTypeOrganization name="requesterAgentTypeOrganization">requesterAgentTypeOrganization</a>

The healthcare professional responsible for authorizing the initial prescription.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization</td></tr><tr><td>description</td><td>The healthcare professional responsible for authorizing the initial prescription.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteragenttypeorganization</td></tr></table>

### <a href=#requesterAgentTypePatient name="requesterAgentTypePatient">requesterAgentTypePatient</a>

The healthcare professional responsible for authorizing the initial prescription.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requester Agent (Patient)</td></tr><tr><td>description</td><td>The healthcare professional responsible for authorizing the initial prescription.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteragenttypepatient</td></tr></table>

### <a href=#requesterAgentTypePractitioner name="requesterAgentTypePractitioner">requesterAgentTypePractitioner</a>

The healthcare professional responsible for authorizing the initial prescription.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Practitoner</td></tr><tr><td>description</td><td>The healthcare professional responsible for authorizing the initial prescription.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteragenttypepractitioner</td></tr></table>

### <a href=#requesterAgentTypeRelatedPerson name="requesterAgentTypeRelatedPerson">requesterAgentTypeRelatedPerson</a>

The healthcare professional responsible for authorizing the initial prescription.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Related Person</td></tr><tr><td>description</td><td>The healthcare professional responsible for authorizing the initial prescription.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteragenttyperelatedperson</td></tr></table>

### <a href=#requesterOnBehalfOf name="requesterOnBehalfOf">requesterOnBehalfOf</a>

The organization the device or practitioner was acting on behalf of.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>On Behalf Of</td></tr><tr><td>description</td><td>The organization the device or practitioner was acting on behalf of.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteronbehalfof</td></tr></table>

### <a href=#status name="status">status</a>

A code specifying the current state of the order. Generally, this will be active or completed state.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>A code specifying the current state of the order. Generally, this will be active or completed state.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_status</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>935000000</td></tr><tr><td>en</td><td>On Hold</td><td>935000001</td></tr><tr><td>en</td><td>Cancelled</td><td>935000002</td></tr><tr><td>en</td><td>Completed</td><td>935000003</td></tr><tr><td>en</td><td>Entered In Error</td><td>935000004</td></tr><tr><td>en</td><td>Stopped</td><td>935000005</td></tr><tr><td>en</td><td>Draft</td><td>935000006</td></tr><tr><td>en</td><td>Unknown</td><td>935000007</td></tr></table></td></tr></table>

### <a href=#status_display name="status_display">status_display</a>

First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#subjectType name="subjectType">subjectType</a>

A link to a resource representing the person or set of individuals to whom the medication will be given.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject Type</td></tr><tr><td>description</td><td>A link to a resource representing the person or set of individuals to whom the medication will be given.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjecttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Device</td><td>935000002</td></tr><tr><td>en</td><td>Group</td><td>935000001</td></tr><tr><td>en</td><td>Location</td><td>935000003</td></tr><tr><td>en</td><td>Patient</td><td>935000000</td></tr></table></td></tr></table>

### <a href=#subjectType_display name="subjectType_display">subjectType_display</a>

First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#subjectTypeGroup name="subjectTypeGroup">subjectTypeGroup</a>

A link to a resource representing the person or set of individuals to whom the medication will be given.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Group</td></tr><tr><td>description</td><td>A link to a resource representing the person or set of individuals to whom the medication will be given.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjecttypegroup</td></tr></table>

### <a href=#subjectTypePatient name="subjectTypePatient">subjectTypePatient</a>

A link to a resource representing the person or set of individuals to whom the medication will be given.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject Type (Patient)</td></tr><tr><td>description</td><td>A link to a resource representing the person or set of individuals to whom the medication will be given.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjecttypepatient</td></tr></table>

### <a href=#substitutionAllowed name="substitutionAllowed">substitutionAllowed</a>

True if the Prescriber allows a different drug to be dispensed from what was prescribed.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Substitution Allowed</td></tr><tr><td>description</td><td>True if the Prescriber allows a different drug to be dispensed from what was prescribed.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_substitutionallowed</td></tr></table>

### <a href=#substitutionReason name="substitutionReason">substitutionReason</a>

Indicates the reason for the substitution, or why substitution must or must not be performed.  
First included in: electronicMedicalRecords/MedicationRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Substitution Reason</td></tr><tr><td>description</td><td>Indicates the reason for the substitution, or why substitution must or must not be performed.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_substitutionreason</td></tr></table>
