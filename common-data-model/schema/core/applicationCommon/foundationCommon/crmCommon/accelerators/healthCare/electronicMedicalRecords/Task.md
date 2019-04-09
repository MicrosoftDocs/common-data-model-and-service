---
title: Task - Common Data Model | Microsoft Docs
description: Generic activity that represents work to be done.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Task

Generic activity that represents work to be done.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/Task.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- [/Task](../../../../../Task.md "/core/applicationCommon/Task.cdm.json/Task")  
- /foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/Task  
- [/foundationCommon/crmCommon/service/Task](../../../service/Task.md "/core/applicationCommon/foundationCommon/crmCommon/service/Task.cdm.json/Task")  
- [/foundationCommon/crmCommon/solutions/marketing/Task](../../../solutions/marketing/Task.md "/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Task.cdm.json/Task")  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[ownerId](#ownerId)|Owner Id|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[owningUser](#owningUser)|Unique identifier for the user that owns the record.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[activityTypeCode](#activityTypeCode)|Type of activity.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[activityId](#activityId)|Unique identifier of the activity.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[isBilled](#isBilled)|Information regarding whether the fax activity was billed as part of resolving a case.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[isRegularActivity](#isRegularActivity)|Information regarding whether the activity is a regular activity type or event type.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[isWorkflowCreated](#isWorkflowCreated)|Information regarding whether the activity was created from a workflow rule.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[priorityCode](#priorityCode)|Priority of the activity.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[priorityCode_display](#priorityCode_display)||<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[regardingObjectTypeCode](#regardingObjectTypeCode)|The name of the entity linked by regardingObjectId|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[regardingObjectId](#regardingObjectId)|Unique identifier of the object with which the activity is associated.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[scheduledEnd](#scheduledEnd)|Scheduled end time of the activity.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[scheduledStart](#scheduledStart)|Scheduled start time of the activity.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[sortDate](#sortDate)|Shows the date and time by which the activities are sorted.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[subject](#subject)|Subject associated with the activity.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[scheduledDurationMinutes](#scheduledDurationMinutes)|Scheduled duration of the activity, specified in minutes.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[actualDurationMinutes](#actualDurationMinutes)|Actual duration of the activity in minutes.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[actualEnd](#actualEnd)|Actual end time of the activity.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[actualStart](#actualStart)|Actual start time of the activity.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[category](#category)|Type a category to identify the activity type, such as lead outreach, customer follow-up, or service alert, to tie the eactivity to a business group or function.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[subcategory](#subcategory)|Type a subcategory to identify the activity type and relate the activity to a specific product, sales region, business group, or other function.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[activityAdditionalParams](#activityAdditionalParams)|Additional information provided by the external application as JSON. For internal use only.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[stateCode](#stateCode)|Shows whether the task is open, completed, or canceled. Completed and canceled tasks are read-only and can't be edited.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[stateCode_display](#stateCode_display)||<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[description](#description)|Type additional information to describe the task.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[percentComplete](#percentComplete)|Type the percentage complete value for the task to track tasks to completion.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[statusCode](#statusCode)|Select the task's status.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[statusCode_display](#statusCode_display)||<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[processId](#processId)|Shows the ID of the process.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[stageId](#stageId)|Shows the ID of the stage.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[traversedPath](#traversedPath)|For internal use only.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[crmTaskAssignedUniqueId](#crmTaskAssignedUniqueId)|Assigned Task Unique Id|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[SLAId](#SLAId)|Choose the service level agreement (SLA) that you want to apply to the Task record.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[SLAInvokedId](#SLAInvokedId)|Last SLA that was applied to this Task. This field is for internal use only.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[onHoldTime](#onHoldTime)|Shows how long, in minutes, that the record was on hold.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[lastOnHoldTime](#lastOnHoldTime)|Contains the date and time stamp of the last on hold time.|<a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>|
|[businessStatus](#businessStatus)|There's often a need to track substrates of a task - this is often variable by specific workflow implementation.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[code](#code)|A name or code (or both) briefly describing what the task involves.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[contextEncounter](#contextEncounter)|An interaction between a patient and healthcare provider(s) for the purpose of providing healthcare service(s) or assessing the health status of a patient|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[contextEpisodeofCare](#contextEpisodeofCare)|An association between a patient and an organization, healthcare provider(s), or both during which time encounters may occur.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[contextType](#contextType)|The healthcare event (e.g. a patient and healthcare provider interaction) during which this task was created.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[contextType_display](#contextType_display)||<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[definitionUri](#definitionUri)|A reference to a formal or informal definition of the task. For example, a protocol, a step within a defined workflow definition, etc.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[descriptionFocus](#descriptionFocus)|The request being actioned or the resource being manipulated by this task.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[descriptionFor](#descriptionFor)|The entity who benefits from the performance of the service specified in the task (e.g., the patient).|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[groupIdentifier](#groupIdentifier)|An identifier that links together multiple tasks and other requests that were created in the same context.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[intent](#intent)|Indicates the ""level"" of actionability associated with the Task. I.e. Is this a proposed task, a planned task, an actionable task, etc.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[intent_display](#intent_display)||<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[performerOwnerAgentDevice](#performerOwnerAgentDevice)|This resource identifies an instance or a type of a manufactured item that is used in the provision of healthcare without being substantially changed through that activity.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[performerOwnerOrganization](#performerOwnerOrganization)|A formally or informally recognized grouping of people or organizations formed for the purpose of achieving some form of collective action.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[performerOwnerPatient](#performerOwnerPatient)|Demographics and other administrative information about an individual or animal receiving care or other health-related services.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[performerOwnerPractitioner](#performerOwnerPractitioner)|A person who is directly or indirectly involved in the provisioning of healthcare.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[performerOwnerRelatedPerson](#performerOwnerRelatedPerson)|Information about a person who is involved in the care for a patient but who isn't the target of healthcare and has no formal responsibility in the care process.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[performerOwnerType](#performerOwnerType)|The type for Individual organization or Device currently responsible for task execution.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[performerOwnerType_display](#performerOwnerType_display)||<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[reason](#reason)|A description or code indicating why this task needs to be performed.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[reference](#reference)|A reference to a formal or informal definition of the task. For example, a protocol, a step within a defined workflow definition, etc.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[requesterAgent](#requesterAgent)|The device, practitioner, etc. who initiated the task.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[requesterAgent_display](#requesterAgent_display)||<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[requesterAgentDevice](#requesterAgentDevice)|" 
This resource identifies an instance or a type of a manufactured item that is used in the provision of healthcare without being substantially changed through that activity.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[requesterAgentOrganization](#requesterAgentOrganization)|A formally or informally recognized grouping of people or organizations formed for the purpose of achieving some form of collective action.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[requesterAgentPatient](#requesterAgentPatient)|Demographics and other administrative information about an individual or animal receiving care or other health-related services.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[requesterAgentPractitioner](#requesterAgentPractitioner)|A person who is directly or indirectly involved in the provisioning of healthcare.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[requesterAgentRelatedPerson](#requesterAgentRelatedPerson)|Information about a person who is involved in the care for a patient but who isn't the target of healthcare and has no formal responsibility in the care process.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[requesterOnBehalfOf](#requesterOnBehalfOf)|This resource identifies an instance or a type of a manufactured item that is used in the provision of healthcare without being substantially changed through that activity.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[restrictionPeriodEndDate](#restrictionPeriodEndDate)|The end of the period. If the end of the period is missing, it means that the period is ongoing.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[restrictionPeriodStartDate](#restrictionPeriodStartDate)|The start of the period. The boundary is inclusive.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[restrictionRepetitions](#restrictionRepetitions)|Indicates the number of times the requested action should occur.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[status](#status)|These states enable coordination of task status with off-the-shelf workflow solutions that support automation of tasks.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[status_display](#status_display)||<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[statusReason](#statusReason)|These states enable coordination of task status with off-the-shelf workflow solutions that support automation of tasks.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[taskNumber](#taskNumber)|A task to be performed.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[taskPriority](#taskPriority)|Indicates how quickly the Task should be addressed with respect to other requests.|<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|
|[taskPriority_display](#taskPriority_display)||<a href="Task.md" target="_blank">electronicMedicalRecords/Task</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier for the user that owns the record.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier for the user that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#activityTypeCode name="activityTypeCode">activityTypeCode</a>

Type of activity.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Type</td></tr><tr><td>description</td><td>Type of activity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>activitytypecode</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fax</td></tr><tr><td>en</td><td>Phone Call</td></tr><tr><td>en</td><td>Email</td></tr><tr><td>en</td><td>Letter</td></tr><tr><td>en</td><td>Appointment</td></tr><tr><td>en</td><td>Task</td></tr><tr><td>en</td><td>Recurring Appointment</td></tr><tr><td>en</td><td>Quick Campaign</td></tr><tr><td>en</td><td>Campaign Activity</td></tr><tr><td>en</td><td>Campaign Response</td></tr><tr><td>en</td><td>Case Resolution</td></tr><tr><td>en</td><td>Service Activity</td></tr><tr><td>en</td><td>Opportunity Close</td></tr><tr><td>en</td><td>Order Close</td></tr><tr><td>en</td><td>Quote Close</td></tr><tr><td>en</td><td>Alert Subscription</td></tr><tr><td>en</td><td>Invite Redemption</td></tr><tr><td>en</td><td>Portal Comment</td></tr></table></td></tr></table>

### <a href=#activityId name="activityId">activityId</a>

Unique identifier of the activity.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity</td></tr><tr><td>description</td><td>Unique identifier of the activity.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>activityid</td></tr></table>

### <a href=#isBilled name="isBilled">isBilled</a>

Information regarding whether the fax activity was billed as part of resolving a case.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Billed</td></tr><tr><td>description</td><td>Information regarding whether the fax activity was billed as part of resolving a case.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isbilled</td></tr></table>

### <a href=#isRegularActivity name="isRegularActivity">isRegularActivity</a>

Information regarding whether the activity is a regular activity type or event type.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Regular Activity</td></tr><tr><td>description</td><td>Information regarding whether the activity is a regular activity type or event type.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isregularactivity</td></tr></table>

### <a href=#isWorkflowCreated name="isWorkflowCreated">isWorkflowCreated</a>

Information regarding whether the activity was created from a workflow rule.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Workflow Created</td></tr><tr><td>description</td><td>Information regarding whether the activity was created from a workflow rule.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isworkflowcreated</td></tr></table>

### <a href=#priorityCode name="priorityCode">priorityCode</a>

Priority of the activity.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Priority</td></tr><tr><td>description</td><td>Priority of the activity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>prioritycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Low</td><td>0</td></tr><tr><td>en</td><td>Normal</td><td>1</td></tr><tr><td>en</td><td>High</td><td>2</td></tr></table></td></tr></table>

### <a href=#priorityCode_display name="priorityCode_display">priorityCode_display</a>

First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#regardingObjectTypeCode name="regardingObjectTypeCode">regardingObjectTypeCode</a>

The name of the entity linked by regardingObjectId  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regarding Type</td></tr><tr><td>description</td><td>The name of the entity linked by regardingObjectId</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>regardingobjecttypecode</td></tr></table>

### <a href=#regardingObjectId name="regardingObjectId">regardingObjectId</a>

Unique identifier of the object with which the activity is associated.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regarding</td></tr><tr><td>description</td><td>Unique identifier of the object with which the activity is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>regardingobjectid</td></tr></table>

### <a href=#scheduledEnd name="scheduledEnd">scheduledEnd</a>

Scheduled end time of the activity.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Due Date</td></tr><tr><td>description</td><td>Scheduled end time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduledend</td></tr></table>

### <a href=#scheduledStart name="scheduledStart">scheduledStart</a>

Scheduled start time of the activity.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date</td></tr><tr><td>description</td><td>Scheduled start time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduledstart</td></tr></table>

### <a href=#sortDate name="sortDate">sortDate</a>

Shows the date and time by which the activities are sorted.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sort Date</td></tr><tr><td>description</td><td>Shows the date and time by which the activities are sorted.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sortdate</td></tr></table>

### <a href=#subject name="subject">subject</a>

Subject associated with the activity.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject</td></tr><tr><td>description</td><td>Subject associated with the activity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>subject</td></tr></table>

### <a href=#scheduledDurationMinutes name="scheduledDurationMinutes">scheduledDurationMinutes</a>

Scheduled duration of the activity, specified in minutes.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scheduled Duration</td></tr><tr><td>description</td><td>Scheduled duration of the activity, specified in minutes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduleddurationminutes</td></tr></table>

### <a href=#actualDurationMinutes name="actualDurationMinutes">actualDurationMinutes</a>

Actual duration of the activity in minutes.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Duration</td></tr><tr><td>description</td><td>Actual duration of the activity in minutes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualdurationminutes</td></tr></table>

### <a href=#actualEnd name="actualEnd">actualEnd</a>

Actual end time of the activity.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual End</td></tr><tr><td>description</td><td>Actual end time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualend</td></tr></table>

### <a href=#actualStart name="actualStart">actualStart</a>

Actual start time of the activity.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Start</td></tr><tr><td>description</td><td>Actual start time of the activity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualstart</td></tr></table>

### <a href=#category name="category">category</a>

Type a category to identify the activity type, such as lead outreach, customer follow-up, or service alert, to tie the eactivity to a business group or function.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Category</td></tr><tr><td>description</td><td>Type a category to identify the activity type, such as lead outreach, customer follow-up, or service alert, to tie the eactivity to a business group or function.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>category</td></tr></table>

### <a href=#subcategory name="subcategory">subcategory</a>

Type a subcategory to identify the activity type and relate the activity to a specific product, sales region, business group, or other function.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sub-Category</td></tr><tr><td>description</td><td>Type a subcategory to identify the activity type and relate the activity to a specific product, sales region, business group, or other function.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>subcategory</td></tr></table>

### <a href=#activityAdditionalParams name="activityAdditionalParams">activityAdditionalParams</a>

Additional information provided by the external application as JSON. For internal use only.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Additional Parameters</td></tr><tr><td>description</td><td>Additional information provided by the external application as JSON. For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>8192</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>activityadditionalparams</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the task is open, completed, or canceled. Completed and canceled tasks are read-only and can't be edited.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Activity Status</td></tr><tr><td>description</td><td>Shows whether the task is open, completed, or canceled. Completed and canceled tasks are read-only and can't be edited.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Open</td><td>0</td></tr><tr><td>en</td><td>Completed</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>2</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#description name="description">description</a>

Type additional information to describe the task.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type additional information to describe the task.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#percentComplete name="percentComplete">percentComplete</a>

Type the percentage complete value for the task to track tasks to completion.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Percent Complete</td></tr><tr><td>description</td><td>Type the percentage complete value for the task to track tasks to completion.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>100</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>percentcomplete</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the task's status.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the task's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Not Started</td><td>2</td><td>0</td></tr><tr><td>en</td><td>In Progress</td><td>3</td><td>0</td></tr><tr><td>en</td><td>Waiting on someone else</td><td>4</td><td>0</td></tr><tr><td>en</td><td>Completed</td><td>5</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>6</td><td>2</td></tr><tr><td>en</td><td>Deferred</td><td>7</td><td>0</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#processId name="processId">processId</a>

Shows the ID of the process.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process</td></tr><tr><td>description</td><td>Shows the ID of the process.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Shows the ID of the stage.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Stage</td></tr><tr><td>description</td><td>Shows the ID of the stage.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

For internal use only.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#crmTaskAssignedUniqueId name="crmTaskAssignedUniqueId">crmTaskAssignedUniqueId</a>

Assigned Task Unique Id  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Assigned Task Unique Id</td></tr><tr><td>description</td><td>Assigned Task Unique Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>crmtaskassigneduniqueid</td></tr></table>

### <a href=#SLAId name="SLAId">SLAId</a>

Choose the service level agreement (SLA) that you want to apply to the Task record.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SLA</td></tr><tr><td>description</td><td>Choose the service level agreement (SLA) that you want to apply to the Task record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slaid</td></tr></table>

### <a href=#SLAInvokedId name="SLAInvokedId">SLAInvokedId</a>

Last SLA that was applied to this Task. This field is for internal use only.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last SLA applied</td></tr><tr><td>description</td><td>Last SLA that was applied to this Task. This field is for internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slainvokedid</td></tr></table>

### <a href=#onHoldTime name="onHoldTime">onHoldTime</a>

Shows how long, in minutes, that the record was on hold.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>On Hold Time (Minutes)</td></tr><tr><td>description</td><td>Shows how long, in minutes, that the record was on hold.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>onholdtime</td></tr></table>

### <a href=#lastOnHoldTime name="lastOnHoldTime">lastOnHoldTime</a>

Contains the date and time stamp of the last on hold time.  
First included in: <a href="../../../../../Task.md" target="_blank">applicationCommon/Task</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last On Hold Time</td></tr><tr><td>description</td><td>Contains the date and time stamp of the last on hold time.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastonholdtime</td></tr></table>

### <a href=#businessStatus name="businessStatus">businessStatus</a>

There's often a need to track substrates of a task - this is often variable by specific workflow implementation.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Business Status</td></tr><tr><td>description</td><td>There's often a need to track substrates of a task - this is often variable by specific workflow implementation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_businessstatus</td></tr></table>

### <a href=#code name="code">code</a>

A name or code (or both) briefly describing what the task involves.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Code</td></tr><tr><td>description</td><td>A name or code (or both) briefly describing what the task involves.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_code</td></tr></table>

### <a href=#contextEncounter name="contextEncounter">contextEncounter</a>

An interaction between a patient and healthcare provider(s) for the purpose of providing healthcare service(s) or assessing the health status of a patient  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Encounter</td></tr><tr><td>description</td><td>An interaction between a patient and healthcare provider(s) for the purpose of providing healthcare service(s) or assessing the health status of a patient</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_contextencounter</td></tr></table>

### <a href=#contextEpisodeofCare name="contextEpisodeofCare">contextEpisodeofCare</a>

An association between a patient and an organization, healthcare provider(s), or both during which time encounters may occur.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Episode of Care</td></tr><tr><td>description</td><td>An association between a patient and an organization, healthcare provider(s), or both during which time encounters may occur.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_contextepisodeofcare</td></tr></table>

### <a href=#contextType name="contextType">contextType</a>

The healthcare event (e.g. a patient and healthcare provider interaction) during which this task was created.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Context Type</td></tr><tr><td>description</td><td>The healthcare event (e.g. a patient and healthcare provider interaction) during which this task was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_contexttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Encounter</td><td>935000000</td></tr><tr><td>en</td><td>Episode Of Care</td><td>935000001</td></tr></table></td></tr></table>

### <a href=#contextType_display name="contextType_display">contextType_display</a>

First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#definitionUri name="definitionUri">definitionUri</a>

A reference to a formal or informal definition of the task. For example, a protocol, a step within a defined workflow definition, etc.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Definition Uri</td></tr><tr><td>description</td><td>A reference to a formal or informal definition of the task. For example, a protocol, a step within a defined workflow definition, etc.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_definitionuri</td></tr></table>

### <a href=#descriptionFocus name="descriptionFocus">descriptionFocus</a>

The request being actioned or the resource being manipulated by this task.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description Focus</td></tr><tr><td>description</td><td>The request being actioned or the resource being manipulated by this task.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_descriptionfocus</td></tr></table>

### <a href=#descriptionFor name="descriptionFor">descriptionFor</a>

The entity who benefits from the performance of the service specified in the task (e.g., the patient).  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description For</td></tr><tr><td>description</td><td>The entity who benefits from the performance of the service specified in the task (e.g., the patient).</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_descriptionfor</td></tr></table>

### <a href=#groupIdentifier name="groupIdentifier">groupIdentifier</a>

An identifier that links together multiple tasks and other requests that were created in the same context.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Group Identifier</td></tr><tr><td>description</td><td>An identifier that links together multiple tasks and other requests that were created in the same context.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_groupidentifier</td></tr></table>

### <a href=#intent name="intent">intent</a>

Indicates the ""level"" of actionability associated with the Task. I.e. Is this a proposed task, a planned task, an actionable task, etc.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Intent</td></tr><tr><td>description</td><td>Indicates the ""level"" of actionability associated with the Task. I.e. Is this a proposed task, a planned task, an actionable task, etc.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_intent</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Proposal</td><td>935000000</td></tr><tr><td>en</td><td>Plan</td><td>935000001</td></tr><tr><td>en</td><td>Order</td><td>935000002</td></tr><tr><td>en</td><td>Reflex order</td><td>935000003</td></tr><tr><td>en</td><td>Filler order</td><td>935000004</td></tr><tr><td>en</td><td>Original-order</td><td>935000006</td></tr><tr><td>en</td><td>Instance order</td><td>935000005</td></tr><tr><td>en</td><td>Option</td><td>935000007</td></tr></table></td></tr></table>

### <a href=#intent_display name="intent_display">intent_display</a>

First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#performerOwnerAgentDevice name="performerOwnerAgentDevice">performerOwnerAgentDevice</a>

This resource identifies an instance or a type of a manufactured item that is used in the provision of healthcare without being substantially changed through that activity.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Performer (Device)</td></tr><tr><td>description</td><td>This resource identifies an instance or a type of a manufactured item that is used in the provision of healthcare without being substantially changed through that activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_performerowneragentdevice</td></tr></table>

### <a href=#performerOwnerOrganization name="performerOwnerOrganization">performerOwnerOrganization</a>

A formally or informally recognized grouping of people or organizations formed for the purpose of achieving some form of collective action.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Performer (Organization)</td></tr><tr><td>description</td><td>A formally or informally recognized grouping of people or organizations formed for the purpose of achieving some form of collective action.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_performerownerorganization</td></tr></table>

### <a href=#performerOwnerPatient name="performerOwnerPatient">performerOwnerPatient</a>

Demographics and other administrative information about an individual or animal receiving care or other health-related services.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Performer (Patient)</td></tr><tr><td>description</td><td>Demographics and other administrative information about an individual or animal receiving care or other health-related services.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_performerownerpatient</td></tr></table>

### <a href=#performerOwnerPractitioner name="performerOwnerPractitioner">performerOwnerPractitioner</a>

A person who is directly or indirectly involved in the provisioning of healthcare.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Performer (Practitioner)</td></tr><tr><td>description</td><td>A person who is directly or indirectly involved in the provisioning of healthcare.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_performerownerpractitioner</td></tr></table>

### <a href=#performerOwnerRelatedPerson name="performerOwnerRelatedPerson">performerOwnerRelatedPerson</a>

Information about a person who is involved in the care for a patient but who isn't the target of healthcare and has no formal responsibility in the care process.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Performer (Related Person)</td></tr><tr><td>description</td><td>Information about a person who is involved in the care for a patient but who isn't the target of healthcare and has no formal responsibility in the care process.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_performerownerrelatedperson</td></tr></table>

### <a href=#performerOwnerType name="performerOwnerType">performerOwnerType</a>

The type for Individual organization or Device currently responsible for task execution.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Performer type</td></tr><tr><td>description</td><td>The type for Individual organization or Device currently responsible for task execution.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_performerownertype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Practitioner</td><td>935000000</td></tr><tr><td>en</td><td>Organization</td><td>935000001</td></tr><tr><td>en</td><td>Patient</td><td>935000002</td></tr><tr><td>en</td><td>Device</td><td>935000003</td></tr><tr><td>en</td><td>Related Person</td><td>935000004</td></tr><tr><td>en</td><td>Healthcare Service</td><td>935000005</td></tr></table></td></tr></table>

### <a href=#performerOwnerType_display name="performerOwnerType_display">performerOwnerType_display</a>

First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#reason name="reason">reason</a>

A description or code indicating why this task needs to be performed.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reason</td></tr><tr><td>description</td><td>A description or code indicating why this task needs to be performed.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_reason</td></tr></table>

### <a href=#reference name="reference">reference</a>

A reference to a formal or informal definition of the task. For example, a protocol, a step within a defined workflow definition, etc.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Definition Reference</td></tr><tr><td>description</td><td>A reference to a formal or informal definition of the task. For example, a protocol, a step within a defined workflow definition, etc.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_reference</td></tr></table>

### <a href=#requesterAgent name="requesterAgent">requesterAgent</a>

The device, practitioner, etc. who initiated the task.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requester Agent</td></tr><tr><td>description</td><td>The device, practitioner, etc. who initiated the task.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteragent</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Practitioner</td><td>935000000</td></tr><tr><td>en</td><td>Organization</td><td>935000001</td></tr><tr><td>en</td><td>Patient</td><td>935000002</td></tr><tr><td>en</td><td>Related Person</td><td>935000003</td></tr><tr><td>en</td><td>Device</td><td>935000004</td></tr></table></td></tr></table>

### <a href=#requesterAgent_display name="requesterAgent_display">requesterAgent_display</a>

First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#requesterAgentDevice name="requesterAgentDevice">requesterAgentDevice</a>

" 
This resource identifies an instance or a type of a manufactured item that is used in the provision of healthcare without being substantially changed through that activity.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requester (Device)</td></tr><tr><td>description</td><td>" 
This resource identifies an instance or a type of a manufactured item that is used in the provision of healthcare without being substantially changed through that activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteragentdevice</td></tr></table>

### <a href=#requesterAgentOrganization name="requesterAgentOrganization">requesterAgentOrganization</a>

A formally or informally recognized grouping of people or organizations formed for the purpose of achieving some form of collective action.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requester (Organization)</td></tr><tr><td>description</td><td>A formally or informally recognized grouping of people or organizations formed for the purpose of achieving some form of collective action.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteragentorganization</td></tr></table>

### <a href=#requesterAgentPatient name="requesterAgentPatient">requesterAgentPatient</a>

Demographics and other administrative information about an individual or animal receiving care or other health-related services.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requester (Patient)</td></tr><tr><td>description</td><td>Demographics and other administrative information about an individual or animal receiving care or other health-related services.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteragentpatient</td></tr></table>

### <a href=#requesterAgentPractitioner name="requesterAgentPractitioner">requesterAgentPractitioner</a>

A person who is directly or indirectly involved in the provisioning of healthcare.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requester (Practitioner)</td></tr><tr><td>description</td><td>A person who is directly or indirectly involved in the provisioning of healthcare.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteragentpractitioner</td></tr></table>

### <a href=#requesterAgentRelatedPerson name="requesterAgentRelatedPerson">requesterAgentRelatedPerson</a>

Information about a person who is involved in the care for a patient but who isn't the target of healthcare and has no formal responsibility in the care process.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requester (Related Person)</td></tr><tr><td>description</td><td>Information about a person who is involved in the care for a patient but who isn't the target of healthcare and has no formal responsibility in the care process.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteragentrelatedperson</td></tr></table>

### <a href=#requesterOnBehalfOf name="requesterOnBehalfOf">requesterOnBehalfOf</a>

This resource identifies an instance or a type of a manufactured item that is used in the provision of healthcare without being substantially changed through that activity.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requester on behalf of</td></tr><tr><td>description</td><td>This resource identifies an instance or a type of a manufactured item that is used in the provision of healthcare without being substantially changed through that activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_requesteronbehalfof</td></tr></table>

### <a href=#restrictionPeriodEndDate name="restrictionPeriodEndDate">restrictionPeriodEndDate</a>

The end of the period. If the end of the period is missing, it means that the period is ongoing.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Restriction Period End Date</td></tr><tr><td>description</td><td>The end of the period. If the end of the period is missing, it means that the period is ongoing.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_restrictionperiodenddate</td></tr></table>

### <a href=#restrictionPeriodStartDate name="restrictionPeriodStartDate">restrictionPeriodStartDate</a>

The start of the period. The boundary is inclusive.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Restriction Period Start Date</td></tr><tr><td>description</td><td>The start of the period. The boundary is inclusive.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_restrictionperiodstartdate</td></tr></table>

### <a href=#restrictionRepetitions name="restrictionRepetitions">restrictionRepetitions</a>

Indicates the number of times the requested action should occur.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Restriction Repetitions</td></tr><tr><td>description</td><td>Indicates the number of times the requested action should occur.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_restrictionrepetitions</td></tr></table>

### <a href=#status name="status">status</a>

These states enable coordination of task status with off-the-shelf workflow solutions that support automation of tasks.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>These states enable coordination of task status with off-the-shelf workflow solutions that support automation of tasks.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_status</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Draft</td><td>935000000</td></tr><tr><td>en</td><td>Requested</td><td>935000001</td></tr><tr><td>en</td><td>Received</td><td>935000002</td></tr><tr><td>en</td><td>Accepted</td><td>935000003</td></tr><tr><td>en</td><td>Rejected</td><td>935000004</td></tr><tr><td>en</td><td>Ready</td><td>935000005</td></tr><tr><td>en</td><td>Cancelled</td><td>935000006</td></tr><tr><td>en</td><td>In progress</td><td>935000007</td></tr><tr><td>en</td><td>On-hold</td><td>935000008</td></tr><tr><td>en</td><td>Failed</td><td>935000009</td></tr><tr><td>en</td><td>Completed</td><td>935000010</td></tr><tr><td>en</td><td>Entered-in-error</td><td>935000011</td></tr></table></td></tr></table>

### <a href=#status_display name="status_display">status_display</a>

First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusReason name="statusReason">statusReason</a>

These states enable coordination of task status with off-the-shelf workflow solutions that support automation of tasks.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>These states enable coordination of task status with off-the-shelf workflow solutions that support automation of tasks.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_statusreason</td></tr></table>

### <a href=#taskNumber name="taskNumber">taskNumber</a>

A task to be performed.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Task Number</td></tr><tr><td>description</td><td>A task to be performed.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_tasknumber</td></tr></table>

### <a href=#taskPriority name="taskPriority">taskPriority</a>

Indicates how quickly the Task should be addressed with respect to other requests.  
First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Task Priority</td></tr><tr><td>description</td><td>Indicates how quickly the Task should be addressed with respect to other requests.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_taskpriority</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Routine</td><td>935000000</td></tr><tr><td>en</td><td>Urgent</td><td>935000001</td></tr><tr><td>en</td><td>Asap</td><td>935000002</td></tr><tr><td>en</td><td>Stat</td><td>935000003</td></tr></table></td></tr></table>

### <a href=#taskPriority_display name="taskPriority_display">taskPriority_display</a>

First included in: electronicMedicalRecords/Task (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
