---
title: ProjectTask - Common Data Model | Microsoft Docs
description: Tasks related to project.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Project Task

Tasks related to project.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/ProjectTask.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/ProjectTask  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[ownerId](#ownerId)|Owner Id|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[projectTaskId](#projectTaskId)|Shows the entity instances.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[stateCode](#stateCode)|Status of the Project Task|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[stateCode_display](#stateCode_display)||<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[statusCode](#statusCode)|Reason for the status of the Project Task|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[statusCode_display](#statusCode_display)||<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[projectTaskName](#projectTaskName)|Type the name of the custom entity.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[actualCost](#actualCost)|Enter the value of the actual cost consumed based on work reported to be completed on the task. |<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Shows the currency associated with the entity.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[exchangeRate](#exchangeRate)|Shows the exchange rate for the currency associated with the entity with respect to the base currency.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[actualCostBase](#actualCostBase)|Value of the Actual Cost in base currency.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[actualDuration](#actualDuration)|Shows the actual duration of the project task in days|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[actualEffort](#actualEffort)|Shows the hours submitted against the task.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[actualEndDateTime](#actualEndDateTime)|Enter the actual end time of the project task.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[actualSales](#actualSales)|Actual Sales Amount|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[actualsalesBase](#actualsalesBase)|Shows the value of the actual sales in the base currency.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[actualStart](#actualStart)|Enter the actual start time of the project task.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[aggregationDirection](#aggregationDirection)|Shows whether the aggregation is happening upstream or downstream.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[aggregationDirection_display](#aggregationDirection_display)||<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[assignedResources](#assignedResources)|Type the project team members that are assigned to task.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[assignedTeamMembers](#assignedTeamMembers)|Select the project team member that has been assigned to a task.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[autoScheduling](#autoScheduling)|Shows whether auto scheduling was used for this task.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[costEstimateContour](#costEstimateContour)|The cost estimate contour for the task|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[description](#description)|Enter a description of the project task.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[duration](#duration)|Shows the duration in days for the task.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[effort](#effort)|Shows the effort hours required for the task.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[effortContour](#effortContour)|The effort distribution|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[effortEstimateAtComplete](#effortEstimateAtComplete)|Shows the forecast of total effort to complete the task.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[isLineTask](#isLineTask)|Shows whether the task is a line task|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[isMilestone](#isMilestone)|Show whether this task is a milestone.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[MSProjectClientId](#MSProjectClientId)|The id of the project task in MS Project Client.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[numberOfResources](#numberOfResources)|Shows the number of resources that are estimated for the task. This is not the number of resources assigned to the task.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[parentTask](#parentTask)|Select the summary or parent task in the hierarchy that contains a child task.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[plannedCost](#plannedCost)|Enter the value of the cost the service provider will incur based on the estimated work and cost rates in the pricelist.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[plannedCostBase](#plannedCostBase)|Enter the value of cost estimated in base currency.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[plannedSales](#plannedSales)|Planned Sales Amount|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[plannedSalesBase](#plannedSalesBase)|Shows the value of the planned sales in the base currency.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[pluginProcessingData](#pluginProcessingData)|Processing data for the plugin pipeline|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[progress](#progress)|Enter the percentage indicating work completed.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[project](#project)|Select the project name.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[remainingCost](#remainingCost)|Enter the cost left over that can be consumed for future work.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[remainingCostBase](#remainingCostBase)|Shows the value of the remaining cost in the  base currency.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[remainingHours](#remainingHours)|Shows the hours remaining to complete the task.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[remainingSales](#remainingSales)|Remaining Sales Amount|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[remainingSalesBase](#remainingSalesBase)|Shows the value of the remaining sales in the base currency.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[requestedHours](#requestedHours)|Shows the hours assigned by generic resource.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[resourceCategory](#resourceCategory)|Select the resource role for the task.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[resourceOrganizationalUnitId](#resourceOrganizationalUnitId)|Select the organizational unit of the resource who should perform the work.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[resourceUtilization](#resourceUtilization)|Shows the utilization units for a resource that is assigned to a project task|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[salesEstimateContour](#salesEstimateContour)|The sales estimate contour|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[scheduledDurationMinutes](#scheduledDurationMinutes)|Shows the scheduled duration of the project task, specified in minutes.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[dueDate](#dueDate)|Enter the scheduled end time of the project.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[scheduledHours](#scheduledHours)|Shows the scheduled hours for the task.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[scheduleStartDate](#scheduleStartDate)|Enter the scheduled start time of the project task.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[scheduleVariance](#scheduleVariance)|Shows the variance between the estimated work and the forecasted work based on the estimate at completion (EAC).|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[skipUpdateEstimateLine](#skipUpdateEstimateLine)|Internal flag to avoid the update process on the estimate lines of the project task|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[transactionCategory](#transactionCategory)|Select the transaction category for the task.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[WBSID](#WBSID)|Shows the ID of the task in the work breakdown structure (WBS).|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[processId](#processId)|Contains the id of the process associated with the entity.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[stageId](#stageId)|Unique identifier of the Stage.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[traversedPath](#traversedPath)|A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[costAtCompleteEstimate](#costAtCompleteEstimate)|Enter the forecast of the total cost to complete the task.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[costAtCompleteEstimateBase](#costAtCompleteEstimateBase)|Value of the Cost estimate at complete (EAC) in base currency.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[costConsumptionPercentage](#costConsumptionPercentage)|Enter the consumption of the total cost in percentage.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[salesConsumptionPercentage](#salesConsumptionPercentage)|Shows the sales consumption percentage for this task.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[salesEstimateAtComplete](#salesEstimateAtComplete)|Shows the sales estimate at the completion of this task.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[salesEstimateAtCompleteBase](#salesEstimateAtCompleteBase)|Value of the Sales Estimate At Complete (EAC) in base currency.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[salesVariance](#salesVariance)|Shows the sales variance for this task.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[salesVarianceBase](#salesVarianceBase)|Shows the value of the sales variance in the base currency.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[varianceOfCost](#varianceOfCost)|Enter the variance between the estimated cost and the forecasted cost based on the estimate at completion (EAC).|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|
|[varianceOfCostBase](#varianceOfCostBase)|Shows the value of the cost variance in the base currency.|<a href="ProjectTask.md" target="_blank">projectServiceAutomation/ProjectTask</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#projectTaskId name="projectTaskId">projectTaskId</a>

Shows the entity instances.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project task</td></tr><tr><td>description</td><td>Shows the entity instances.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_projecttaskid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Project Task  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Task Status</td></tr><tr><td>description</td><td>Status of the Project Task</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Project Task  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Project Task</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#projectTaskName name="projectTaskName">projectTaskName</a>

Type the name of the custom entity.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Task Name</td></tr><tr><td>description</td><td>Type the name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>450</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_subject</td></tr></table>

### <a href=#actualCost name="actualCost">actualCost</a>

Enter the value of the actual cost consumed based on work reported to be completed on the task.   
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Cost</td></tr><tr><td>description</td><td>Enter the value of the actual cost consumed based on work reported to be completed on the task. </td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actualcost</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Shows the currency associated with the entity.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Shows the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#actualCostBase name="actualCostBase">actualCostBase</a>

Value of the Actual Cost in base currency.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Cost (Base)</td></tr><tr><td>description</td><td>Value of the Actual Cost in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actualcost_base</td></tr></table>

### <a href=#actualDuration name="actualDuration">actualDuration</a>

Shows the actual duration of the project task in days  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Duration</td></tr><tr><td>description</td><td>Shows the actual duration of the project task in days</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actualdurationminutes</td></tr></table>

### <a href=#actualEffort name="actualEffort">actualEffort</a>

Shows the hours submitted against the task.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Hours</td></tr><tr><td>description</td><td>Shows the hours submitted against the task.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actualeffort</td></tr></table>

### <a href=#actualEndDateTime name="actualEndDateTime">actualEndDateTime</a>

Enter the actual end time of the project task.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual End Date/Time</td></tr><tr><td>description</td><td>Enter the actual end time of the project task.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actualend</td></tr></table>

### <a href=#actualSales name="actualSales">actualSales</a>

Actual Sales Amount  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Sales</td></tr><tr><td>description</td><td>Actual Sales Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actualsales</td></tr></table>

### <a href=#actualsalesBase name="actualsalesBase">actualsalesBase</a>

Shows the value of the actual sales in the base currency.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Sales (Base)</td></tr><tr><td>description</td><td>Shows the value of the actual sales in the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actualsales_base</td></tr></table>

### <a href=#actualStart name="actualStart">actualStart</a>

Enter the actual start time of the project task.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Start</td></tr><tr><td>description</td><td>Enter the actual start time of the project task.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actualstart</td></tr></table>

### <a href=#aggregationDirection name="aggregationDirection">aggregationDirection</a>

Shows whether the aggregation is happening upstream or downstream.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aggregation Direction</td></tr><tr><td>description</td><td>Shows whether the aggregation is happening upstream or downstream.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_aggregationdirection</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Upstream</td><td>0</td></tr><tr><td>en</td><td>Downstream</td><td>1</td></tr><tr><td>en</td><td>Both</td><td>2</td></tr></table></td></tr></table>

### <a href=#aggregationDirection_display name="aggregationDirection_display">aggregationDirection_display</a>

First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#assignedResources name="assignedResources">assignedResources</a>

Type the project team members that are assigned to task.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Assigned Resources (Deprecated in v3.0)</td></tr><tr><td>description</td><td>Type the project team members that are assigned to task.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>300</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_assignedresources</td></tr></table>

### <a href=#assignedTeamMembers name="assignedTeamMembers">assignedTeamMembers</a>

Select the project team member that has been assigned to a task.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Assigned Team Members (Deprecated in v3.0)</td></tr><tr><td>description</td><td>Select the project team member that has been assigned to a task.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_assignedteammembers</td></tr></table>

### <a href=#autoScheduling name="autoScheduling">autoScheduling</a>

Shows whether auto scheduling was used for this task.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Auto Scheduling</td></tr><tr><td>description</td><td>Shows whether auto scheduling was used for this task.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_autoscheduling</td></tr></table>

### <a href=#costEstimateContour name="costEstimateContour">costEstimateContour</a>

The cost estimate contour for the task  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>CostEstimateContour (Deprecated in v3.0)</td></tr><tr><td>description</td><td>The cost estimate contour for the task</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1048576</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_costestimatecontour</td></tr></table>

### <a href=#description name="description">description</a>

Enter a description of the project task.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Enter a description of the project task.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_description</td></tr></table>

### <a href=#duration name="duration">duration</a>

Shows the duration in days for the task.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Duration</td></tr><tr><td>description</td><td>Shows the duration in days for the task.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_duration</td></tr></table>

### <a href=#effort name="effort">effort</a>

Shows the effort hours required for the task.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Effort</td></tr><tr><td>description</td><td>Shows the effort hours required for the task.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_effort</td></tr></table>

### <a href=#effortContour name="effortContour">effortContour</a>

The effort distribution  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Effort Contour (Deprecated in v3.0)</td></tr><tr><td>description</td><td>The effort distribution</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1048576</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_effortcontour</td></tr></table>

### <a href=#effortEstimateAtComplete name="effortEstimateAtComplete">effortEstimateAtComplete</a>

Shows the forecast of total effort to complete the task.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Effort estimate at complete (EAC)</td></tr><tr><td>description</td><td>Shows the forecast of total effort to complete the task.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_effortestimateatcomplete</td></tr></table>

### <a href=#isLineTask name="isLineTask">isLineTask</a>

Shows whether the task is a line task  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>IsLineTask</td></tr><tr><td>description</td><td>Shows whether the task is a line task</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_islinetask</td></tr></table>

### <a href=#isMilestone name="isMilestone">isMilestone</a>

Show whether this task is a milestone.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Milestone</td></tr><tr><td>description</td><td>Show whether this task is a milestone.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_ismilestone</td></tr></table>

### <a href=#MSProjectClientId name="MSProjectClientId">MSProjectClientId</a>

The id of the project task in MS Project Client.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>MS Project Client Id</td></tr><tr><td>description</td><td>The id of the project task in MS Project Client.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_msprojectclientid</td></tr></table>

### <a href=#numberOfResources name="numberOfResources">numberOfResources</a>

Shows the number of resources that are estimated for the task. This is not the number of resources assigned to the task.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number of resources (Deprecated in v3.0)</td></tr><tr><td>description</td><td>Shows the number of resources that are estimated for the task. This is not the number of resources assigned to the task.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_numberofresources</td></tr></table>

### <a href=#parentTask name="parentTask">parentTask</a>

Select the summary or parent task in the hierarchy that contains a child task.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent Task</td></tr><tr><td>description</td><td>Select the summary or parent task in the hierarchy that contains a child task.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_parenttask</td></tr></table>

### <a href=#plannedCost name="plannedCost">plannedCost</a>

Enter the value of the cost the service provider will incur based on the estimated work and cost rates in the pricelist.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Planned cost</td></tr><tr><td>description</td><td>Enter the value of the cost the service provider will incur based on the estimated work and cost rates in the pricelist.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_plannedcost</td></tr></table>

### <a href=#plannedCostBase name="plannedCostBase">plannedCostBase</a>

Enter the value of cost estimated in base currency.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated cost</td></tr><tr><td>description</td><td>Enter the value of cost estimated in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_plannedcost_base</td></tr></table>

### <a href=#plannedSales name="plannedSales">plannedSales</a>

Planned Sales Amount  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Planned Sales</td></tr><tr><td>description</td><td>Planned Sales Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_plannedsales</td></tr></table>

### <a href=#plannedSalesBase name="plannedSalesBase">plannedSalesBase</a>

Shows the value of the planned sales in the base currency.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Planned Sales (Base)</td></tr><tr><td>description</td><td>Shows the value of the planned sales in the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_plannedsales_base</td></tr></table>

### <a href=#pluginProcessingData name="pluginProcessingData">pluginProcessingData</a>

Processing data for the plugin pipeline  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Plugin Processing Data</td></tr><tr><td>description</td><td>Processing data for the plugin pipeline</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_pluginprocessingdata</td></tr></table>

### <a href=#progress name="progress">progress</a>

Enter the percentage indicating work completed.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Progress %</td></tr><tr><td>description</td><td>Enter the percentage indicating work completed.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_progress</td></tr></table>

### <a href=#project name="project">project</a>

Select the project name.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project</td></tr><tr><td>description</td><td>Select the project name.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_project</td></tr></table>

### <a href=#remainingCost name="remainingCost">remainingCost</a>

Enter the cost left over that can be consumed for future work.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Remaining Cost</td></tr><tr><td>description</td><td>Enter the cost left over that can be consumed for future work.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_remainingcost</td></tr></table>

### <a href=#remainingCostBase name="remainingCostBase">remainingCostBase</a>

Shows the value of the remaining cost in the  base currency.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Remaining Cost (Base)</td></tr><tr><td>description</td><td>Shows the value of the remaining cost in the  base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_remainingcost_base</td></tr></table>

### <a href=#remainingHours name="remainingHours">remainingHours</a>

Shows the hours remaining to complete the task.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Remaining Hours</td></tr><tr><td>description</td><td>Shows the hours remaining to complete the task.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_remaininghours</td></tr></table>

### <a href=#remainingSales name="remainingSales">remainingSales</a>

Remaining Sales Amount  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Remaining Sales</td></tr><tr><td>description</td><td>Remaining Sales Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_remainingsales</td></tr></table>

### <a href=#remainingSalesBase name="remainingSalesBase">remainingSalesBase</a>

Shows the value of the remaining sales in the base currency.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Remaining Sales (Base)</td></tr><tr><td>description</td><td>Shows the value of the remaining sales in the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_remainingsales_base</td></tr></table>

### <a href=#requestedHours name="requestedHours">requestedHours</a>

Shows the hours assigned by generic resource.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requested Hours</td></tr><tr><td>description</td><td>Shows the hours assigned by generic resource.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_requestedhours</td></tr></table>

### <a href=#resourceCategory name="resourceCategory">resourceCategory</a>

Select the resource role for the task.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Role (Deprecated in v3.0)</td></tr><tr><td>description</td><td>Select the resource role for the task.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourcecategory</td></tr></table>

### <a href=#resourceOrganizationalUnitId name="resourceOrganizationalUnitId">resourceOrganizationalUnitId</a>

Select the organizational unit of the resource who should perform the work.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resourcing unit (Deprecated in v3.0)</td></tr><tr><td>description</td><td>Select the organizational unit of the resource who should perform the work.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourceorganizationalunitid</td></tr></table>

### <a href=#resourceUtilization name="resourceUtilization">resourceUtilization</a>

Shows the utilization units for a resource that is assigned to a project task  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ResourceUtilization</td></tr><tr><td>description</td><td>Shows the utilization units for a resource that is assigned to a project task</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourceutilization</td></tr></table>

### <a href=#salesEstimateContour name="salesEstimateContour">salesEstimateContour</a>

The sales estimate contour  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SalesEstimateContour (Deprecated in v3.0)</td></tr><tr><td>description</td><td>The sales estimate contour</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1048576</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salesestimatecontour</td></tr></table>

### <a href=#scheduledDurationMinutes name="scheduledDurationMinutes">scheduledDurationMinutes</a>

Shows the scheduled duration of the project task, specified in minutes.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scheduled Duration</td></tr><tr><td>description</td><td>Shows the scheduled duration of the project task, specified in minutes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_scheduleddurationminutes</td></tr></table>

### <a href=#dueDate name="dueDate">dueDate</a>

Enter the scheduled end time of the project.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Due Date</td></tr><tr><td>description</td><td>Enter the scheduled end time of the project.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_scheduledend</td></tr></table>

### <a href=#scheduledHours name="scheduledHours">scheduledHours</a>

Shows the scheduled hours for the task.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scheduled Hours (Deprecated in v3.0)</td></tr><tr><td>description</td><td>Shows the scheduled hours for the task.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_scheduledhours</td></tr></table>

### <a href=#scheduleStartDate name="scheduleStartDate">scheduleStartDate</a>

Enter the scheduled start time of the project task.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date</td></tr><tr><td>description</td><td>Enter the scheduled start time of the project task.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_scheduledstart</td></tr></table>

### <a href=#scheduleVariance name="scheduleVariance">scheduleVariance</a>

Shows the variance between the estimated work and the forecasted work based on the estimate at completion (EAC).  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Schedule Variance</td></tr><tr><td>description</td><td>Shows the variance between the estimated work and the forecasted work based on the estimate at completion (EAC).</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_schedulevariance</td></tr></table>

### <a href=#skipUpdateEstimateLine name="skipUpdateEstimateLine">skipUpdateEstimateLine</a>

Internal flag to avoid the update process on the estimate lines of the project task  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Skip Update Estimate Line</td></tr><tr><td>description</td><td>Internal flag to avoid the update process on the estimate lines of the project task</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_skipupdateestimateline</td></tr></table>

### <a href=#transactionCategory name="transactionCategory">transactionCategory</a>

Select the transaction category for the task.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Category</td></tr><tr><td>description</td><td>Select the transaction category for the task.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactioncategory</td></tr></table>

### <a href=#WBSID name="WBSID">WBSID</a>

Shows the ID of the task in the work breakdown structure (WBS).  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>WBS ID</td></tr><tr><td>description</td><td>Shows the ID of the task in the work breakdown structure (WBS).</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_wbsid</td></tr></table>

### <a href=#processId name="processId">processId</a>

Contains the id of the process associated with the entity.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Id</td></tr><tr><td>description</td><td>Contains the id of the process associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Unique identifier of the Stage.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Stage</td></tr><tr><td>description</td><td>Unique identifier of the Stage.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#costAtCompleteEstimate name="costAtCompleteEstimate">costAtCompleteEstimate</a>

Enter the forecast of the total cost to complete the task.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost estimate at complete (EAC)</td></tr><tr><td>description</td><td>Enter the forecast of the total cost to complete the task.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_costatcompleteestimate</td></tr></table>

### <a href=#costAtCompleteEstimateBase name="costAtCompleteEstimateBase">costAtCompleteEstimateBase</a>

Value of the Cost estimate at complete (EAC) in base currency.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost estimate at completion (EAC) (Base)</td></tr><tr><td>description</td><td>Value of the Cost estimate at complete (EAC) in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_costatcompleteestimate_base</td></tr></table>

### <a href=#costConsumptionPercentage name="costConsumptionPercentage">costConsumptionPercentage</a>

Enter the consumption of the total cost in percentage.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost Consumption %</td></tr><tr><td>description</td><td>Enter the consumption of the total cost in percentage.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_costconsumptionpercentage</td></tr></table>

### <a href=#salesConsumptionPercentage name="salesConsumptionPercentage">salesConsumptionPercentage</a>

Shows the sales consumption percentage for this task.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales Consumption %</td></tr><tr><td>description</td><td>Shows the sales consumption percentage for this task.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salesconsumptionpercentage</td></tr></table>

### <a href=#salesEstimateAtComplete name="salesEstimateAtComplete">salesEstimateAtComplete</a>

Shows the sales estimate at the completion of this task.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales Estimate At Complete (EAC)</td></tr><tr><td>description</td><td>Shows the sales estimate at the completion of this task.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salesestimateatcomplete</td></tr></table>

### <a href=#salesEstimateAtCompleteBase name="salesEstimateAtCompleteBase">salesEstimateAtCompleteBase</a>

Value of the Sales Estimate At Complete (EAC) in base currency.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales Estimate At Complete (EAC) (Base)</td></tr><tr><td>description</td><td>Value of the Sales Estimate At Complete (EAC) in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salesestimateatcomplete_base</td></tr></table>

### <a href=#salesVariance name="salesVariance">salesVariance</a>

Shows the sales variance for this task.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales Variance</td></tr><tr><td>description</td><td>Shows the sales variance for this task.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salesvariance</td></tr></table>

### <a href=#salesVarianceBase name="salesVarianceBase">salesVarianceBase</a>

Shows the value of the sales variance in the base currency.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales Variance (Base)</td></tr><tr><td>description</td><td>Shows the value of the sales variance in the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salesvariance_base</td></tr></table>

### <a href=#varianceOfCost name="varianceOfCost">varianceOfCost</a>

Enter the variance between the estimated cost and the forecasted cost based on the estimate at completion (EAC).  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost Variance</td></tr><tr><td>description</td><td>Enter the variance between the estimated cost and the forecasted cost based on the estimate at completion (EAC).</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_varianceofcost</td></tr></table>

### <a href=#varianceOfCostBase name="varianceOfCostBase">varianceOfCostBase</a>

Shows the value of the cost variance in the base currency.  
First included in: projectServiceAutomation/ProjectTask (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost Variance (Base)</td></tr><tr><td>description</td><td>Shows the value of the cost variance in the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_varianceofcost_base</td></tr></table>
