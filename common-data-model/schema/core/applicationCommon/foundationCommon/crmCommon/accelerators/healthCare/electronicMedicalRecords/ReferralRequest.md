---
title: ReferralRequest - Common Data Model | Microsoft Docs
description: This describes the ReferralRequest entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# Referral Request

Used to record and send details about a request for referral service or transfer of a patient to the care of another provider or provider organization.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/ReferralRequest.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/ReferralRequest  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[ownerId](#ownerId)|Owner Id|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[referralRequestId](#referralRequestId)|Unique identifier for entity instances|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[stateCode](#stateCode)|Status of the Referral Request|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[stateCode_display](#stateCode_display)||<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[statusCode](#statusCode)|Reason for the status of the Referral Request|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[statusCode_display](#statusCode_display)||<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[name](#name)|The name of the custom entity.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[emrAppointment](#emrAppointment)||<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[authoredOn](#authoredOn)|Date/DateTime of creation for draft requests and date of activation for active requests.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[basedOnReferral](#basedOnReferral)||<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[contextType](#contextType)|The encounter at which the request for referral or transfer of care is initiated.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[contextType_display](#contextType_display)||<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[description](#description)|The reason element gives a short description of why the referral is being made, the description expands on this to support a more complete clinical summary.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[groupIdentifier](#groupIdentifier)|The business identifier of the logical ""grouping"" request/order that this referral is a part of.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[initiatingEncounter](#initiatingEncounter)||<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[initiatingEpisodeofCare](#initiatingEpisodeofCare)||<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[intent](#intent)|Distinguishes the "level" of authorization/demand implicit in this request.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[intent_display](#intent_display)||<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[occurencePeriodEndDate](#occurencePeriodEndDate)|End time with inclusive boundary, if not ongoing.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[occurencePeriodStartDate](#occurencePeriodStartDate)|Starting time with inclusive boundary.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[occurrenceDate](#occurrenceDate)|The period of time within which the services identified in the referral/transfer of care is specified or required to occur.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[occurrenceType](#occurrenceType)|The type of the period of time within which the services identified in the referral/transfer of care is specified or required to occur.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[occurrenceType_display](#occurrenceType_display)||<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[practitionerSpecialty](#practitionerSpecialty)|Indication of the clinical domain or discipline to which the referral or transfer of care request is sent. For example: Cardiology Gastroenterology Diabetology.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[priority](#priority)|An indication of the urgency of referral (or where applicable the type of transfer of care) request.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[priority_display](#priority_display)||<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[referralRequestNumber](#referralRequestNumber)|Business identifier that uniquely identifies the referral/care transfer request instance.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[requesterAgent](#requesterAgent)|The device, practitioner, etc. who initiated the request.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[requesterAgent_display](#requesterAgent_display)||<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[requesterAgentDevice](#requesterAgentDevice)|This resource identifies an instance or a type of a manufactured item that is used in the provision of healthcare without being substantially changed through that activity.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[requesterAgentOrganization](#requesterAgentOrganization)|A formally or informally recognized grouping of people or organizations formed for the purpose of achieving some form of collective action. Includes companies, institutions, corporations, departments.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[requesterAgentPatient](#requesterAgentPatient)|Demographics and other administrative information about an individual or animal receiving care or other health-related services.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[requesterAgentPractitioner](#requesterAgentPractitioner)|A person who is directly or indirectly involved in the provisioning of healthcare.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[requesterAgentRelatedPerson](#requesterAgentRelatedPerson)|Information about a person that is involved in the care for a patient, but who is not the target of healthcare, nor has a formal responsibility in the care process.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[requesterOnBehalfOf](#requesterOnBehalfOf)|This resource identifies an instance or a type of a manufactured item that is used in the provision of healthcare without being substantially changed through that activity.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[requestorIdType](#requestorIdType)|The type of requestor, either Account or Contact.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[requestor](#requestor)||<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[status](#status)|The status of the authorization/intention reflected by the referral request record.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[status_display](#status_display)||<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[subject](#subject)|The patient who is the subject of a referral or transfer of care request.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[subject_display](#subject_display)||<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[subjectContextEncounter](#subjectContextEncounter)|An interaction between a patient and healthcare provider(s) for the purpose of providing healthcare service(s) or assessing the health status of a patient.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[subjectContextEpisodeOfCare](#subjectContextEpisodeOfCare)|An association between a patient and an organization / healthcare provider(s) during which time encounters may occur.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[subjectGroup](#subjectGroup)|Represents a defined collection of entities that may be discussed or acted upon collectively but which are not expected to act collectively and are not formally or legally recognized.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[subjectPatient](#subjectPatient)|The patient who is the subject of a referral or transfer of care request.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|
|[type](#type)|An indication of the type of referral (or where applicable the type of transfer of care) request.|<a href="ReferralRequest.md" target="_blank">electronicMedicalRecords/ReferralRequest</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#referralRequestId name="referralRequestId">referralRequestId</a>

Unique identifier for entity instances  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Referral Request</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msemr_referralrequestid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Referral Request  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Referral Request</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Referral Request  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Referral Request Status</td></tr><tr><td>description</td><td>Reason for the status of the Referral Request</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Proposal</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Plan</td><td>935000000</td><td>0</td></tr><tr><td>en</td><td>Original Order</td><td>935000001</td><td>0</td></tr><tr><td>en</td><td>Reflex Order</td><td>935000002</td><td>0</td></tr><tr><td>en</td><td>Instance Order</td><td>935000003</td><td>0</td></tr><tr><td>en</td><td>Option</td><td>935000004</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_name</td></tr></table>

### <a href=#emrAppointment name="emrAppointment">emrAppointment</a>

First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Appointment (EMR)</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_appointmentemr</td></tr></table>

### <a href=#authoredOn name="authoredOn">authoredOn</a>

Date/DateTime of creation for draft requests and date of activation for active requests.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Authored On</td></tr><tr><td>description</td><td>Date/DateTime of creation for draft requests and date of activation for active requests.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_authoredon</td></tr></table>

### <a href=#basedOnReferral name="basedOnReferral">basedOnReferral</a>

First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Based On (Referral)</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_basedonreferral</td></tr></table>

### <a href=#contextType name="contextType">contextType</a>

The encounter at which the request for referral or transfer of care is initiated.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Referral Request Context</td></tr><tr><td>description</td><td>The encounter at which the request for referral or transfer of care is initiated.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_contexttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Encounter</td><td>935000000</td></tr><tr><td>en</td><td>Episode of Care</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#contextType_display name="contextType_display">contextType_display</a>

First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#description name="description">description</a>

The reason element gives a short description of why the referral is being made, the description expands on this to support a more complete clinical summary.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>The reason element gives a short description of why the referral is being made, the description expands on this to support a more complete clinical summary.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_description</td></tr></table>

### <a href=#groupIdentifier name="groupIdentifier">groupIdentifier</a>

The business identifier of the logical ""grouping"" request/order that this referral is a part of.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Group Identifier</td></tr><tr><td>description</td><td>The business identifier of the logical ""grouping"" request/order that this referral is a part of.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_groupidentifier</td></tr></table>

### <a href=#initiatingEncounter name="initiatingEncounter">initiatingEncounter</a>

First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Initiating Encounter</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_initiatingencounter</td></tr></table>

### <a href=#initiatingEpisodeofCare name="initiatingEpisodeofCare">initiatingEpisodeofCare</a>

First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Initiating Episode of Care</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_initiatingepisodeofcare</td></tr></table>

### <a href=#intent name="intent">intent</a>

Distinguishes the "level" of authorization/demand implicit in this request.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Referral Request Intent</td></tr><tr><td>description</td><td>Distinguishes the "level" of authorization/demand implicit in this request.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_intent</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Proposal</td><td>935000000</td></tr><tr><td>en</td><td>Plan</td><td>935000001</td></tr><tr><td>en</td><td>Order</td><td>935000002</td></tr></table></td></tr></table>

### <a href=#intent_display name="intent_display">intent_display</a>

First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#occurencePeriodEndDate name="occurencePeriodEndDate">occurencePeriodEndDate</a>

End time with inclusive boundary, if not ongoing.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Occurrence End Date</td></tr><tr><td>description</td><td>End time with inclusive boundary, if not ongoing.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_occurenceperiodenddate</td></tr></table>

### <a href=#occurencePeriodStartDate name="occurencePeriodStartDate">occurencePeriodStartDate</a>

Starting time with inclusive boundary.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Occurrence Start Date</td></tr><tr><td>description</td><td>Starting time with inclusive boundary.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_occurenceperiodstartdate</td></tr></table>

### <a href=#occurrenceDate name="occurrenceDate">occurrenceDate</a>

The period of time within which the services identified in the referral/transfer of care is specified or required to occur.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Occurrence Date</td></tr><tr><td>description</td><td>The period of time within which the services identified in the referral/transfer of care is specified or required to occur.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_occurrencedate</td></tr></table>

### <a href=#occurrenceType name="occurrenceType">occurrenceType</a>

The type of the period of time within which the services identified in the referral/transfer of care is specified or required to occur.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Occurrence Type</td></tr><tr><td>description</td><td>The type of the period of time within which the services identified in the referral/transfer of care is specified or required to occur.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_occurrencetype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Date</td><td>935000000</td></tr><tr><td>en</td><td>Period</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#occurrenceType_display name="occurrenceType_display">occurrenceType_display</a>

First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#practitionerSpecialty name="practitionerSpecialty">practitionerSpecialty</a>

Indication of the clinical domain or discipline to which the referral or transfer of care request is sent. For example: Cardiology Gastroenterology Diabetology.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Practitioner Specialty</td></tr><tr><td>description</td><td>Indication of the clinical domain or discipline to which the referral or transfer of care request is sent. For example: Cardiology Gastroenterology Diabetology.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_practitionerspecialty</td></tr></table>

### <a href=#priority name="priority">priority</a>

An indication of the urgency of referral (or where applicable the type of transfer of care) request.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Referral Request Priority</td></tr><tr><td>description</td><td>An indication of the urgency of referral (or where applicable the type of transfer of care) request.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_priority</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Routine</td><td>935000000</td></tr><tr><td>en</td><td>Urgent</td><td>935000001</td></tr><tr><td>en</td><td>Stat</td><td>935000003</td></tr><tr><td>en</td><td>Asap</td><td>935000002</td></tr></table></td></tr></table>

### <a href=#priority_display name="priority_display">priority_display</a>

First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#referralRequestNumber name="referralRequestNumber">referralRequestNumber</a>

Business identifier that uniquely identifies the referral/care transfer request instance.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Referral Request Number</td></tr><tr><td>description</td><td>Business identifier that uniquely identifies the referral/care transfer request instance.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_referralrequestnumber</td></tr></table>

### <a href=#requesterAgent name="requesterAgent">requesterAgent</a>

The device, practitioner, etc. who initiated the request.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requester Agent</td></tr><tr><td>description</td><td>The device, practitioner, etc. who initiated the request.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteragent</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Practitioner</td><td>935000000</td></tr><tr><td>en</td><td>Organization</td><td>935000001</td></tr><tr><td>en</td><td>Patient</td><td>935000002</td></tr><tr><td>en</td><td>Related Person</td><td>935000003</td></tr><tr><td>en</td><td>Device</td><td>935000004</td></tr></table></td></tr></table>

### <a href=#requesterAgent_display name="requesterAgent_display">requesterAgent_display</a>

First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#requesterAgentDevice name="requesterAgentDevice">requesterAgentDevice</a>

This resource identifies an instance or a type of a manufactured item that is used in the provision of healthcare without being substantially changed through that activity.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Device</td></tr><tr><td>description</td><td>This resource identifies an instance or a type of a manufactured item that is used in the provision of healthcare without being substantially changed through that activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteragentdevice</td></tr></table>

### <a href=#requesterAgentOrganization name="requesterAgentOrganization">requesterAgentOrganization</a>

A formally or informally recognized grouping of people or organizations formed for the purpose of achieving some form of collective action. Includes companies, institutions, corporations, departments.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization</td></tr><tr><td>description</td><td>A formally or informally recognized grouping of people or organizations formed for the purpose of achieving some form of collective action. Includes companies, institutions, corporations, departments.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteragentorganization</td></tr></table>

### <a href=#requesterAgentPatient name="requesterAgentPatient">requesterAgentPatient</a>

Demographics and other administrative information about an individual or animal receiving care or other health-related services.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Patient</td></tr><tr><td>description</td><td>Demographics and other administrative information about an individual or animal receiving care or other health-related services.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteragentpatient</td></tr></table>

### <a href=#requesterAgentPractitioner name="requesterAgentPractitioner">requesterAgentPractitioner</a>

A person who is directly or indirectly involved in the provisioning of healthcare.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Practitioner</td></tr><tr><td>description</td><td>A person who is directly or indirectly involved in the provisioning of healthcare.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteragentpractitioner</td></tr></table>

### <a href=#requesterAgentRelatedPerson name="requesterAgentRelatedPerson">requesterAgentRelatedPerson</a>

Information about a person that is involved in the care for a patient, but who is not the target of healthcare, nor has a formal responsibility in the care process.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Related Person</td></tr><tr><td>description</td><td>Information about a person that is involved in the care for a patient, but who is not the target of healthcare, nor has a formal responsibility in the care process.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteragentrelatedperson</td></tr></table>

### <a href=#requesterOnBehalfOf name="requesterOnBehalfOf">requesterOnBehalfOf</a>

This resource identifies an instance or a type of a manufactured item that is used in the provision of healthcare without being substantially changed through that activity.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requester on behalf of</td></tr><tr><td>description</td><td>This resource identifies an instance or a type of a manufactured item that is used in the provision of healthcare without being substantially changed through that activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteronbehalfof</td></tr></table>

### <a href=#requestorIdType name="requestorIdType">requestorIdType</a>

The type of requestor, either Account or Contact.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requestor Type</td></tr><tr><td>description</td><td>The type of requestor, either Account or Contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>requestoridtype</td></tr></table>

### <a href=#requestor name="requestor">requestor</a>

First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requestor</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requestor</td></tr></table>

### <a href=#status name="status">status</a>

The status of the authorization/intention reflected by the referral request record.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Referral Request Status</td></tr><tr><td>description</td><td>The status of the authorization/intention reflected by the referral request record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_status</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Draft</td><td>935000000</td></tr><tr><td>en</td><td>Active</td><td>935000001</td></tr><tr><td>en</td><td>Suspended</td><td>935000002</td></tr><tr><td>en</td><td>Cancelled</td><td>935000003</td></tr><tr><td>en</td><td>Completed</td><td>935000004</td></tr><tr><td>en</td><td>Entered-In-Error</td><td>935000005</td></tr><tr><td>en</td><td>Unknown</td><td>935000006</td></tr></table></td></tr></table>

### <a href=#status_display name="status_display">status_display</a>

First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#subject name="subject">subject</a>

The patient who is the subject of a referral or transfer of care request.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Referral Request Subject</td></tr><tr><td>description</td><td>The patient who is the subject of a referral or transfer of care request.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subject</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Patinet</td><td>935000000</td></tr><tr><td>en</td><td>Group</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#subject_display name="subject_display">subject_display</a>

First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#subjectContextEncounter name="subjectContextEncounter">subjectContextEncounter</a>

An interaction between a patient and healthcare provider(s) for the purpose of providing healthcare service(s) or assessing the health status of a patient.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Encounter</td></tr><tr><td>description</td><td>An interaction between a patient and healthcare provider(s) for the purpose of providing healthcare service(s) or assessing the health status of a patient.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjectcontextencounter</td></tr></table>

### <a href=#subjectContextEpisodeOfCare name="subjectContextEpisodeOfCare">subjectContextEpisodeOfCare</a>

An association between a patient and an organization / healthcare provider(s) during which time encounters may occur.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Episode of Care</td></tr><tr><td>description</td><td>An association between a patient and an organization / healthcare provider(s) during which time encounters may occur.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjectcontextepisodeofcare</td></tr></table>

### <a href=#subjectGroup name="subjectGroup">subjectGroup</a>

Represents a defined collection of entities that may be discussed or acted upon collectively but which are not expected to act collectively and are not formally or legally recognized.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject (Group)</td></tr><tr><td>description</td><td>Represents a defined collection of entities that may be discussed or acted upon collectively but which are not expected to act collectively and are not formally or legally recognized.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjectgroup</td></tr></table>

### <a href=#subjectPatient name="subjectPatient">subjectPatient</a>

The patient who is the subject of a referral or transfer of care request.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject (Patient)</td></tr><tr><td>description</td><td>The patient who is the subject of a referral or transfer of care request.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_subjectpatient</td></tr></table>

### <a href=#type name="type">type</a>

An indication of the type of referral (or where applicable the type of transfer of care) request.  
First included in: electronicMedicalRecords/ReferralRequest (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Referral Request Type</td></tr><tr><td>description</td><td>An indication of the type of referral (or where applicable the type of transfer of care) request.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_type</td></tr></table>
