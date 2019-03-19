---
title: EmrAppointment - Common Data Model | Microsoft Docs
description: This describes the EmrAppointment entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# Appointment (EMR)

A booking of a healthcare event among patient(s), practitioner(s), related person(s) and/or device(s) for a specific date/time. This may result in one or more Encounter(s).  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/EmrAppointment.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/EmrAppointment  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[ownerId](#ownerId)|Owner Id|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[actualEnd](#actualEnd)|Actual end time of the activity.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[activityId](#activityId)|Unique identifier of the activity.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[isBilled](#isBilled)|Information regarding whether the activity was billed as part of resolving a case.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[description](#description)|Description of the activity.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[activityTypeCode](#activityTypeCode)|Type of activity.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[activityTypeCode_display](#activityTypeCode_display)||<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[stateCode](#stateCode)|Status of the activity.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[stateCode_display](#stateCode_display)||<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[scheduledEnd](#scheduledEnd)|Scheduled end time of the activity.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[scheduledDurationMinutes](#scheduledDurationMinutes)|Scheduled duration of the activity, specified in minutes.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[actualDurationMinutes](#actualDurationMinutes)|Actual duration of the activity in minutes.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[statusCode](#statusCode)|Reason for the status of the activity.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[statusCode_display](#statusCode_display)||<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[actualStart](#actualStart)|Actual start time of the activity.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[priorityCode](#priorityCode)|Priority of the activity.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[priorityCode_display](#priorityCode_display)||<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[regardingObjectId](#regardingObjectId)|Unique identifier of the object with which the activity is associated.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[subject](#subject)|Subject associated with the activity.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[isWorkflowCreated](#isWorkflowCreated)|Information regarding whether the activity was created from a workflow rule.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[scheduledStart](#scheduledStart)|Scheduled start time of the activity.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[instanceTypeCode](#instanceTypeCode)|Type of instance of a recurring series.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[instanceTypeCode_display](#instanceTypeCode_display)||<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[seriesId](#seriesId)|Uniqueidentifier specifying the id of recurring series of an instance.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[isRegularActivity](#isRegularActivity)|Information regarding whether the activity is a regular activity type or event type.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the activitypointer.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the activitypointer with respect to the base currency.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[leftVoiceMail](#leftVoiceMail)|Left the voice mail|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[community](#community)|Shows how contact about the social activity originated, such as from Twitter or Facebook. This field is read-only.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[community_display](#community_display)||<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[traversedPath](#traversedPath)|For internal use only.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[isMapiPrivate](#isMapiPrivate)|For internal use only.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[exchangeWebLink](#exchangeWebLink)|Shows the web link of Activity of type email.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[exchangeItemId](#exchangeItemId)|The message id of activity which is returned from Exchange Server.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[deliveryPriorityCode](#deliveryPriorityCode)|Priority of delivery of the activity to the email server.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[deliveryPriorityCode_display](#deliveryPriorityCode_display)||<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[sentOn](#sentOn)|Date and time when the activity was sent.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[deliveryLastAttemptedOn](#deliveryLastAttemptedOn)|Date and time when the delivery of the activity was last attempted.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[senderMailboxId](#senderMailboxId)|Unique identifier of the mailbox associated with the sender of the email message.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[postponeActivityProcessingUntil](#postponeActivityProcessingUntil)|For internal use only.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[processId](#processId)|Unique identifier of the Process.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[stageId](#stageId)|Unique identifier of the Stage.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[activityAdditionalParams](#activityAdditionalParams)|Additional information provided by the external application as JSON. For internal use only.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[SLAId](#SLAId)|Choose the service level agreement (SLA) that you want to apply to the case record.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[SLAInvokedId](#SLAInvokedId)|Last SLA that was applied to this case. This field is for internal use only.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[onHoldTime](#onHoldTime)|Shows how long, in minutes, that the record was on hold.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[lastOnHoldTime](#lastOnHoldTime)|Contains the date and time stamp of the last on hold time.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[sortDate](#sortDate)|Shows the date and time by which the activities are sorted.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[serviceId](#serviceId)|Unique identifier of an associated service.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[from](#from)|Person who the activity is from.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[to](#to)|Person who is the receiver of the activity.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[CC](#CC)|Carbon-copy (cc) recipients of the activity.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[BCC](#BCC)|Blind Carbon-copy (bcc) recipients of the activity.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[requiredAttendees](#requiredAttendees)|List of required attendees for the activity.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[optionalAttendees](#optionalAttendees)|List of optional attendees for the activity.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[organizer](#organizer)|Person who organized the activity.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[resources](#resources)|Users or facility/equipment that are required for the activity.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[customers](#customers)|Customer with which the activity is associated.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[partners](#partners)|Outsource vendor with which activity is associated.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[actorDevice](#actorDevice)|Name of the Person, Location/HealthcareService or Device.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[actorLocation](#actorLocation)|Name of the Person, Location/HealthcareService or Device.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[actorPatient](#actorPatient)|Name of the Person, Location/HealthcareService or Device.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[actorPractitioner](#actorPractitioner)|Name of the Person, Location/HealthcareService or Device.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[actorRelatedPerson](#actorRelatedPerson)|Name of the Person, Location/HealthcareService or Device.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[appointmentCreationDate](#appointmentCreationDate)|When appointment is to take place|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[appointmentType](#appointmentType)|The style of appointment or patient that has been booked in the slot.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[comment](#comment)|Additional comments about the appointment.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[emrDescription](#emrDescription)|The brief description of the appointment as would be shown on a subject line in a meeting request, or appointment list. Detailed or expanded information should be put in the comment field.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[endTime](#endTime)|End time of an appointment.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[minutesDuration](#minutesDuration)|Number of minutes that the appointment is to take. This can be less than the duration between the start and end times (where actual time of appointment is only an estimate or is a planned appointment.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[participantActorType](#participantActorType)|Type of appointment participant.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[participantActorType_display](#participantActorType_display)||<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[participantStatus](#participantStatus)|The Participation status of an appointment.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[participantStatus_display](#participantStatus_display)||<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[particpantType](#particpantType)|Role of the participant in the appointment.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[patientInstruction](#patientInstruction)|Detailed information and instructions for the patient.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[priority](#priority)|The priority of the appointment. Can be used to make informed decisions if needing to re-prioritize appointments. (The iCal Standard specifies 0 as undefined, 1 as highest, 9 as lowest priority).|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[required](#required)|Is the Participant required to attend the appointment.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[required_display](#required_display)||<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[serviceCategory](#serviceCategory)|A broad categorization of the service that is to be performed during this appointment.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[startTime](#startTime)|Start time of an appointment.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[status](#status)|Codes providing the status of an appointment.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|
|[supportingInformation](#supportingInformation)|Additional information may be attachments to support or provide more insight for an appointment.|<a href="EmrAppointment.md" target="_blank">electronicMedicalRecords/EmrAppointment</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#actualEnd name="actualEnd">actualEnd</a>

Actual end time of the activity.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual End</td></tr><tr><td>description</td><td>Actual end time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualend</td></tr></table>

### <a href=#activityId name="activityId">activityId</a>

Unique identifier of the activity.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity</td></tr><tr><td>description</td><td>Unique identifier of the activity.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>activityid</td></tr></table>

### <a href=#isBilled name="isBilled">isBilled</a>

Information regarding whether the activity was billed as part of resolving a case.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Billed</td></tr><tr><td>description</td><td>Information regarding whether the activity was billed as part of resolving a case.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isbilled</td></tr></table>

### <a href=#description name="description">description</a>

Description of the activity.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the activity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#activityTypeCode name="activityTypeCode">activityTypeCode</a>

Type of activity.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Type</td></tr><tr><td>description</td><td>Type of activity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>activitytypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#activityTypeCode_display name="activityTypeCode_display">activityTypeCode_display</a>

First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the activity.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Status</td></tr><tr><td>description</td><td>Status of the activity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Open</td><td>0</td></tr><tr><td>en</td><td>Completed</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>2</td></tr><tr><td>en</td><td>Scheduled</td><td>3</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#scheduledEnd name="scheduledEnd">scheduledEnd</a>

Scheduled end time of the activity.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Due Date</td></tr><tr><td>description</td><td>Scheduled end time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduledend</td></tr></table>

### <a href=#scheduledDurationMinutes name="scheduledDurationMinutes">scheduledDurationMinutes</a>

Scheduled duration of the activity, specified in minutes.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scheduled Duration</td></tr><tr><td>description</td><td>Scheduled duration of the activity, specified in minutes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduleddurationminutes</td></tr></table>

### <a href=#actualDurationMinutes name="actualDurationMinutes">actualDurationMinutes</a>

Actual duration of the activity in minutes.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Duration</td></tr><tr><td>description</td><td>Actual duration of the activity in minutes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualdurationminutes</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the activity.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the activity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Pending</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Proposed</td><td>935000000</td><td>0</td></tr><tr><td>en</td><td>Booked</td><td>935000001</td><td>0</td></tr><tr><td>en</td><td>Arrived</td><td>935000002</td><td>0</td></tr><tr><td>en</td><td>Fulfilled</td><td>2</td><td>1</td></tr><tr><td>en</td><td>No Show</td><td>935000004</td><td>1</td></tr><tr><td>en</td><td>Entered in error</td><td>935000005</td><td>1</td></tr><tr><td>en</td><td>Cancelled</td><td>3</td><td>2</td></tr><tr><td>en</td><td>Booked</td><td>935000003</td><td>3</td></tr><tr><td>en</td><td>Scheduled</td><td>4</td><td>3</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#actualStart name="actualStart">actualStart</a>

Actual start time of the activity.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Start</td></tr><tr><td>description</td><td>Actual start time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualstart</td></tr></table>

### <a href=#priorityCode name="priorityCode">priorityCode</a>

Priority of the activity.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Priority</td></tr><tr><td>description</td><td>Priority of the activity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>prioritycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Low</td><td>0</td></tr><tr><td>en</td><td>Normal</td><td>1</td></tr><tr><td>en</td><td>High</td><td>2</td></tr></table></td></tr></table>

### <a href=#priorityCode_display name="priorityCode_display">priorityCode_display</a>

First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#regardingObjectId name="regardingObjectId">regardingObjectId</a>

Unique identifier of the object with which the activity is associated.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regarding</td></tr><tr><td>description</td><td>Unique identifier of the object with which the activity is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>regardingobjectid</td></tr></table>

### <a href=#subject name="subject">subject</a>

Subject associated with the activity.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject</td></tr><tr><td>description</td><td>Subject associated with the activity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>subject</td></tr></table>

### <a href=#isWorkflowCreated name="isWorkflowCreated">isWorkflowCreated</a>

Information regarding whether the activity was created from a workflow rule.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Workflow Created</td></tr><tr><td>description</td><td>Information regarding whether the activity was created from a workflow rule.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isworkflowcreated</td></tr></table>

### <a href=#scheduledStart name="scheduledStart">scheduledStart</a>

Scheduled start time of the activity.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Appointment (EMR) Start</td></tr><tr><td>description</td><td>Scheduled start time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduledstart</td></tr></table>

### <a href=#instanceTypeCode name="instanceTypeCode">instanceTypeCode</a>

Type of instance of a recurring series.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recurring Instance Type</td></tr><tr><td>description</td><td>Type of instance of a recurring series.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>instancetypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not Recurring</td><td>0</td></tr><tr><td>en</td><td>Recurring Master</td><td>1</td></tr><tr><td>en</td><td>Recurring Instance</td><td>2</td></tr><tr><td>en</td><td>Recurring Exception</td><td>3</td></tr><tr><td>en</td><td>Recurring Future Exception</td><td>4</td></tr></table></td></tr></table>

### <a href=#instanceTypeCode_display name="instanceTypeCode_display">instanceTypeCode_display</a>

First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#seriesId name="seriesId">seriesId</a>

Uniqueidentifier specifying the id of recurring series of an instance.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Series Id</td></tr><tr><td>description</td><td>Uniqueidentifier specifying the id of recurring series of an instance.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>seriesid</td></tr></table>

### <a href=#isRegularActivity name="isRegularActivity">isRegularActivity</a>

Information regarding whether the activity is a regular activity type or event type.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Regular Activity</td></tr><tr><td>description</td><td>Information regarding whether the activity is a regular activity type or event type.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isregularactivity</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the activitypointer.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the activitypointer.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the activitypointer with respect to the base currency.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the activitypointer with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#leftVoiceMail name="leftVoiceMail">leftVoiceMail</a>

Left the voice mail  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Left Voice Mail</td></tr><tr><td>description</td><td>Left the voice mail</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>leftvoicemail</td></tr></table>

### <a href=#community name="community">community</a>

Shows how contact about the social activity originated, such as from Twitter or Facebook. This field is read-only.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Social Channel</td></tr><tr><td>description</td><td>Shows how contact about the social activity originated, such as from Twitter or Facebook. This field is read-only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>community</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#community_display name="community_display">community_display</a>

First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

For internal use only.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#isMapiPrivate name="isMapiPrivate">isMapiPrivate</a>

For internal use only.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Private</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ismapiprivate</td></tr></table>

### <a href=#exchangeWebLink name="exchangeWebLink">exchangeWebLink</a>

Shows the web link of Activity of type email.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange WebLink</td></tr><tr><td>description</td><td>Shows the web link of Activity of type email.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangeweblink</td></tr></table>

### <a href=#exchangeItemId name="exchangeItemId">exchangeItemId</a>

The message id of activity which is returned from Exchange Server.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Item ID</td></tr><tr><td>description</td><td>The message id of activity which is returned from Exchange Server.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangeitemid</td></tr></table>

### <a href=#deliveryPriorityCode name="deliveryPriorityCode">deliveryPriorityCode</a>

Priority of delivery of the activity to the email server.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery Priority</td></tr><tr><td>description</td><td>Priority of delivery of the activity to the email server.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>deliveryprioritycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#deliveryPriorityCode_display name="deliveryPriorityCode_display">deliveryPriorityCode_display</a>

First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#sentOn name="sentOn">sentOn</a>

Date and time when the activity was sent.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Sent</td></tr><tr><td>description</td><td>Date and time when the activity was sent.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>senton</td></tr></table>

### <a href=#deliveryLastAttemptedOn name="deliveryLastAttemptedOn">deliveryLastAttemptedOn</a>

Date and time when the delivery of the activity was last attempted.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Delivery Last Attempted</td></tr><tr><td>description</td><td>Date and time when the delivery of the activity was last attempted.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>deliverylastattemptedon</td></tr></table>

### <a href=#senderMailboxId name="senderMailboxId">senderMailboxId</a>

Unique identifier of the mailbox associated with the sender of the email message.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sender's Mailbox</td></tr><tr><td>description</td><td>Unique identifier of the mailbox associated with the sender of the email message.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sendermailboxid</td></tr></table>

### <a href=#postponeActivityProcessingUntil name="postponeActivityProcessingUntil">postponeActivityProcessingUntil</a>

For internal use only.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delay activity processing until</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postponeactivityprocessinguntil</td></tr></table>

### <a href=#processId name="processId">processId</a>

Unique identifier of the Process.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process</td></tr><tr><td>description</td><td>Unique identifier of the Process.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Unique identifier of the Stage.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Stage</td></tr><tr><td>description</td><td>Unique identifier of the Stage.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#activityAdditionalParams name="activityAdditionalParams">activityAdditionalParams</a>

Additional information provided by the external application as JSON. For internal use only.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Additional Parameters</td></tr><tr><td>description</td><td>Additional information provided by the external application as JSON. For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>8192</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>activityadditionalparams</td></tr></table>

### <a href=#SLAId name="SLAId">SLAId</a>

Choose the service level agreement (SLA) that you want to apply to the case record.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SLA</td></tr><tr><td>description</td><td>Choose the service level agreement (SLA) that you want to apply to the case record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slaid</td></tr></table>

### <a href=#SLAInvokedId name="SLAInvokedId">SLAInvokedId</a>

Last SLA that was applied to this case. This field is for internal use only.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last SLA applied</td></tr><tr><td>description</td><td>Last SLA that was applied to this case. This field is for internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slainvokedid</td></tr></table>

### <a href=#onHoldTime name="onHoldTime">onHoldTime</a>

Shows how long, in minutes, that the record was on hold.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>On Hold Time (Minutes)</td></tr><tr><td>description</td><td>Shows how long, in minutes, that the record was on hold.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>onholdtime</td></tr></table>

### <a href=#lastOnHoldTime name="lastOnHoldTime">lastOnHoldTime</a>

Contains the date and time stamp of the last on hold time.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last On Hold Time</td></tr><tr><td>description</td><td>Contains the date and time stamp of the last on hold time.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastonholdtime</td></tr></table>

### <a href=#sortDate name="sortDate">sortDate</a>

Shows the date and time by which the activities are sorted.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sort Date</td></tr><tr><td>description</td><td>Shows the date and time by which the activities are sorted.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sortdate</td></tr></table>

### <a href=#serviceId name="serviceId">serviceId</a>

Unique identifier of an associated service.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Service</td></tr><tr><td>description</td><td>Unique identifier of an associated service.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>serviceid</td></tr></table>

### <a href=#from name="from">from</a>

Person who the activity is from.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>From</td></tr><tr><td>description</td><td>Person who the activity is from.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>from</td></tr></table>

### <a href=#to name="to">to</a>

Person who is the receiver of the activity.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>To</td></tr><tr><td>description</td><td>Person who is the receiver of the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>to</td></tr></table>

### <a href=#CC name="CC">CC</a>

Carbon-copy (cc) recipients of the activity.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>CC</td></tr><tr><td>description</td><td>Carbon-copy (cc) recipients of the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>cc</td></tr></table>

### <a href=#BCC name="BCC">BCC</a>

Blind Carbon-copy (bcc) recipients of the activity.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>BCC</td></tr><tr><td>description</td><td>Blind Carbon-copy (bcc) recipients of the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>bcc</td></tr></table>

### <a href=#requiredAttendees name="requiredAttendees">requiredAttendees</a>

List of required attendees for the activity.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Required Attendees</td></tr><tr><td>description</td><td>List of required attendees for the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>requiredattendees</td></tr></table>

### <a href=#optionalAttendees name="optionalAttendees">optionalAttendees</a>

List of optional attendees for the activity.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Optional Attendees</td></tr><tr><td>description</td><td>List of optional attendees for the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>optionalattendees</td></tr></table>

### <a href=#organizer name="organizer">organizer</a>

Person who organized the activity.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organizer</td></tr><tr><td>description</td><td>Person who organized the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>organizer</td></tr></table>

### <a href=#resources name="resources">resources</a>

Users or facility/equipment that are required for the activity.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resources</td></tr><tr><td>description</td><td>Users or facility/equipment that are required for the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>resources</td></tr></table>

### <a href=#customers name="customers">customers</a>

Customer with which the activity is associated.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customers</td></tr><tr><td>description</td><td>Customer with which the activity is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customers</td></tr></table>

### <a href=#partners name="partners">partners</a>

Outsource vendor with which activity is associated.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Outsource Vendors</td></tr><tr><td>description</td><td>Outsource vendor with which activity is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>partners</td></tr></table>

### <a href=#actorDevice name="actorDevice">actorDevice</a>

Name of the Person, Location/HealthcareService or Device.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actor (Device)</td></tr><tr><td>description</td><td>Name of the Person, Location/HealthcareService or Device.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_actordevice</td></tr></table>

### <a href=#actorLocation name="actorLocation">actorLocation</a>

Name of the Person, Location/HealthcareService or Device.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actor (Location)</td></tr><tr><td>description</td><td>Name of the Person, Location/HealthcareService or Device.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_actorlocation</td></tr></table>

### <a href=#actorPatient name="actorPatient">actorPatient</a>

Name of the Person, Location/HealthcareService or Device.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actor (Patient)</td></tr><tr><td>description</td><td>Name of the Person, Location/HealthcareService or Device.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_actorpatient</td></tr></table>

### <a href=#actorPractitioner name="actorPractitioner">actorPractitioner</a>

Name of the Person, Location/HealthcareService or Device.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actor (Practitioner)</td></tr><tr><td>description</td><td>Name of the Person, Location/HealthcareService or Device.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_actorpractitioner</td></tr></table>

### <a href=#actorRelatedPerson name="actorRelatedPerson">actorRelatedPerson</a>

Name of the Person, Location/HealthcareService or Device.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actor (Related Person)</td></tr><tr><td>description</td><td>Name of the Person, Location/HealthcareService or Device.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_actorrelatedperson</td></tr></table>

### <a href=#appointmentCreationDate name="appointmentCreationDate">appointmentCreationDate</a>

When appointment is to take place  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Appointment Creation Date</td></tr><tr><td>description</td><td>When appointment is to take place</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_appointmentcreationdate</td></tr></table>

### <a href=#appointmentType name="appointmentType">appointmentType</a>

The style of appointment or patient that has been booked in the slot.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Appointment Type</td></tr><tr><td>description</td><td>The style of appointment or patient that has been booked in the slot.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_appointmenttype</td></tr></table>

### <a href=#comment name="comment">comment</a>

Additional comments about the appointment.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Comment</td></tr><tr><td>description</td><td>Additional comments about the appointment.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_comment</td></tr></table>

### <a href=#emrDescription name="emrDescription">emrDescription</a>

The brief description of the appointment as would be shown on a subject line in a meeting request, or appointment list. Detailed or expanded information should be put in the comment field.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>The brief description of the appointment as would be shown on a subject line in a meeting request, or appointment list. Detailed or expanded information should be put in the comment field.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_description</td></tr></table>

### <a href=#endTime name="endTime">endTime</a>

End time of an appointment.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End time</td></tr><tr><td>description</td><td>End time of an appointment.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_endtime</td></tr></table>

### <a href=#minutesDuration name="minutesDuration">minutesDuration</a>

Number of minutes that the appointment is to take. This can be less than the duration between the start and end times (where actual time of appointment is only an estimate or is a planned appointment.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Minutes Duration</td></tr><tr><td>description</td><td>Number of minutes that the appointment is to take. This can be less than the duration between the start and end times (where actual time of appointment is only an estimate or is a planned appointment.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_minutesduration</td></tr></table>

### <a href=#participantActorType name="participantActorType">participantActorType</a>

Type of appointment participant.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Participant Actor Type</td></tr><tr><td>description</td><td>Type of appointment participant.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_participantactortype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Patient</td><td>935000000</td></tr><tr><td>en</td><td>Practitioner</td><td>935000001</td></tr><tr><td>en</td><td>RelatedPerson</td><td>935000002</td></tr><tr><td>en</td><td>Device</td><td>935000003</td></tr><tr><td>en</td><td>HealthcareService</td><td>935000004</td></tr><tr><td>en</td><td>Location</td><td>935000005</td></tr></table></td></tr></table>

### <a href=#participantActorType_display name="participantActorType_display">participantActorType_display</a>

First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#participantStatus name="participantStatus">participantStatus</a>

The Participation status of an appointment.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Participant Status</td></tr><tr><td>description</td><td>The Participation status of an appointment.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_participantstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Accepted</td><td>935000000</td></tr><tr><td>en</td><td>Declined</td><td>935000001</td></tr><tr><td>en</td><td>Tentative</td><td>935000002</td></tr><tr><td>en</td><td>Needs Action</td><td>935000003</td></tr></table></td></tr></table>

### <a href=#participantStatus_display name="participantStatus_display">participantStatus_display</a>

First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#particpantType name="particpantType">particpantType</a>

Role of the participant in the appointment.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Participant Type</td></tr><tr><td>description</td><td>Role of the participant in the appointment.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_particpanttype</td></tr></table>

### <a href=#patientInstruction name="patientInstruction">patientInstruction</a>

Detailed information and instructions for the patient.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Patient Instruction</td></tr><tr><td>description</td><td>Detailed information and instructions for the patient.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_patientinstruction</td></tr></table>

### <a href=#priority name="priority">priority</a>

The priority of the appointment. Can be used to make informed decisions if needing to re-prioritize appointments. (The iCal Standard specifies 0 as undefined, 1 as highest, 9 as lowest priority).  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Priority</td></tr><tr><td>description</td><td>The priority of the appointment. Can be used to make informed decisions if needing to re-prioritize appointments. (The iCal Standard specifies 0 as undefined, 1 as highest, 9 as lowest priority).</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>10</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_priority</td></tr></table>

### <a href=#required name="required">required</a>

Is the Participant required to attend the appointment.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Required</td></tr><tr><td>description</td><td>Is the Participant required to attend the appointment.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_required</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Required</td><td>935000000</td></tr><tr><td>en</td><td>Optional</td><td>935000001</td></tr><tr><td>en</td><td>Information Only</td><td>935000002</td></tr></table></td></tr></table>

### <a href=#required_display name="required_display">required_display</a>

First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#serviceCategory name="serviceCategory">serviceCategory</a>

A broad categorization of the service that is to be performed during this appointment.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Service Category</td></tr><tr><td>description</td><td>A broad categorization of the service that is to be performed during this appointment.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_servicecategory</td></tr></table>

### <a href=#startTime name="startTime">startTime</a>

Start time of an appointment.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start time</td></tr><tr><td>description</td><td>Start time of an appointment.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_starttime</td></tr></table>

### <a href=#status name="status">status</a>

Codes providing the status of an appointment.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Codes providing the status of an appointment.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_status</td></tr></table>

### <a href=#supportingInformation name="supportingInformation">supportingInformation</a>

Additional information may be attachments to support or provide more insight for an appointment.  
First included in: electronicMedicalRecords/EmrAppointment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Supporting Information</td></tr><tr><td>description</td><td>Additional information may be attachments to support or provide more insight for an appointment.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_supportinginformation</td></tr></table>
