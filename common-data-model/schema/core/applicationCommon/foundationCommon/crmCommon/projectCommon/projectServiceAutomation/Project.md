---
title: Project - Common Data Model | Microsoft Docs
description: Delivery entity in an engagement.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Project

Delivery entity in an engagement.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/Project.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/Project  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[projectId](#projectId)|Shows the entity instances.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[stateCode](#stateCode)|Status of the Project|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[stateCode_display](#stateCode_display)||<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[statusCode](#statusCode)|Reason for the status of the Project|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[statusCode_display](#statusCode_display)||<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[subject](#subject)|Type the name of the custom entity.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[processId](#processId)|Contains the id of the process associated with the entity.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[stageId](#stageId)|Contains the id of the stage where the entity is located.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[traversedPath](#traversedPath)|A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[actualDuration](#actualDuration)|Shows the actual duration of the project in minutes.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[actualEnd](#actualEnd)|Enter the actual end time of the project.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[actualExpenseCost](#actualExpenseCost)|Shows the aggregate of actual expense cost on the project.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Shows the currency associated with the entity.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[exchangeRate](#exchangeRate)|Shows the exchange rate for the currency associated with the entity with respect to the base currency.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[actualexpensecostBase](#actualexpensecostBase)|Value of the Actual Expense Cost in base currency.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[actualHours](#actualHours)|Shows the total actual hours of the project|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[actualLaborCost](#actualLaborCost)|Shows the aggregate of actual labor cost on the project.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[actuallaborcostBase](#actuallaborcostBase)|Value of the Actual Labor Cost in base currency.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[actualSales](#actualSales)|Shows the actual sales value.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[actualsalesBase](#actualsalesBase)|Shows the value of the actual sales in the base currency.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[actualStart](#actualStart)|Enter the actual start time of the project.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[bulkGenerationStatus](#bulkGenerationStatus)|The status of the bulk generation operations running on the project entity. If no operation is running, the value is null.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[bulkGenerationStatus_display](#bulkGenerationStatus_display)||<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[calendarId](#calendarId)|Id of the calendar for the project.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[comments](#comments)|Enter the comments that are used to describe the current project status.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[contractOrganizationalUnitId](#contractOrganizationalUnitId)|Select the organizational unit sponsoring the project.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[customer](#customer)|Enter the customer who the project is associated with.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[description](#description)|Enter a description of the project.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[disableCreateOfTeamMemberForProjectManager](#disableCreateOfTeamMemberForProjectManager)|This is an internal field, mainly used during import so that we don't create a team member record for the project manager.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[effortestimateatcompleteEAC](#effortestimateatcompleteEAC)|Shows the total of actual hours and the remaining hours.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[projectExchangeRate](#projectExchangeRate)|Exchange rate for the currency associated with the project with respect to the base currency.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[isLinkedToMSProjectClient](#isLinkedToMSProjectClient)|Specifies if the project is linked to a project in MS Project|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[isTemplate](#isTemplate)|Shows if the project is a project template.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[linkedDocumentURL](#linkedDocumentURL)|The URL for the linked document.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[overallProjectStatus](#overallProjectStatus)|Describes the project status.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[overallProjectStatus_display](#overallProjectStatus_display)||<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[estimatedExpenseCost](#estimatedExpenseCost)|Shows the aggregate of the planned expense cost of all the associated tasks.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[plannedexpensecostBase](#plannedexpensecostBase)|Value of the Estimated Expense Cost in base currency.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[estimatedHours](#estimatedHours)|Shows the total estimate hours of the project.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[estimatedLaborCost](#estimatedLaborCost)|Shows the aggregate of the planned labor cost of all the associated tasks.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[plannedlaborcostBase](#plannedlaborcostBase)|Value of the Estimated Labor Cost in base currency.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[plannedSales](#plannedSales)|Shows the total planned sales.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[plannedSalesBase](#plannedSalesBase)|Shows the value of the planned sales in the base currency.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[progress](#progress)|Shows the actual hours divided by effort at estimate.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[projectManager](#projectManager)|Shows the project manager assigned to the project.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[projectResourceRequirementsVisibleToResources](#projectResourceRequirementsVisibleToResources)|Indicates if the project resource requirements are visible to the resources assigned to the project.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[projectTeamId](#projectTeamId)|Select the Team associated with Project.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[projectTemplate](#projectTemplate)|Select the project template behind the project.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[remainingCost](#remainingCost)|Shows the difference between the estimated cost and the actual cost.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[remainingCostBase](#remainingCostBase)|Shows the value of the remaining cost in the  base currency.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[remainingHours](#remainingHours)|Shows the difference between the estimate at completion (EAC) and the actual hours.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[remainingSales](#remainingSales)|Shows the difference between estimated sales and the actual sales.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[remainingSalesBase](#remainingSalesBase)|Shows the value of the remaining sales in the base currency.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[salesOrderId](#salesOrderId)|Shows the contract for this project.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[scheduledDurationMinutes](#scheduledDurationMinutes)|Shows the scheduled duration of the project, specified in minutes.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[estimatedFinishDate](#estimatedFinishDate)|Enter the scheduled end time of the project.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[scheduleStartDate](#scheduleStartDate)|Enter the scheduled start time of the project.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[schedulePerformance](#schedulePerformance)|Describes the schedule performance of the project.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[schedulePerformance_display](#schedulePerformance_display)||<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[scheduleVariance](#scheduleVariance)|Shows the difference between the planned effort and the estimate at completion (EAC).|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[stageName](#stageName)|Shows the stage of the project (Deprecated in v3.0).|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[statusUpdatedOn](#statusUpdatedOn)|Shows the most recent update on a status field(comments or overall project status).|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[totalActualCost](#totalActualCost)|Shows the aggregated cost from actuals on the project.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[totalActualCostBase](#totalActualCostBase)|Shows the value of the total actual cost in the base currency.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[totalPlannedCost](#totalPlannedCost)|Shows the aggregate of the total planned cost of all the associated tasks.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[totalPlannedCostBase](#totalPlannedCostBase)|Shows the value of the total planned cost in the base currency.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[wbsDuration](#wbsDuration)|Shows the work breakdown structure (WBS) duration in days.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[workHourTemplate](#workHourTemplate)|Select the work hour template used to create the project calendar.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[costConsumption](#costConsumption)|Shows the actual cost divided by the estimated cost at completion.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[costEstimateAtComplete](#costEstimateAtComplete)|Sum of Actual Cost and Remaining cost|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[costEstimateAtCompleteBase](#costEstimateAtCompleteBase)|Value of the Cost estimate at completion (EAC) in base currency.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[costPerformence](#costPerformence)||<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[costPerformence_display](#costPerformence_display)||<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[costVariance](#costVariance)|Variance between the estimated cost and the forecasted cost based on the estimate at completion (EAC).|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[costVarianceBase](#costVarianceBase)|Shows the value of the cost variance in the base currency.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[salesConsumption](#salesConsumption)|Shows the actual sales divided by the estimated sales.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[salesEstimateAtCompleteEAC](#salesEstimateAtCompleteEAC)|Shows the total of actual and remaining sales.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[salesEstimateAtCompleteEACBase](#salesEstimateAtCompleteEACBase)|Value of the Sales Estimate At Complete (EAC) in base currency.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[salesVariance](#salesVariance)|Shows the difference between the planned sales and the sales estimate at completion (EAC).|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[salesVarianceBase](#salesVarianceBase)|Shows the value of the sales variance in the base currency.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[teamSize](#teamSize)|Shows the total number of team members assigned to this project|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[teamsizeDate](#teamsizeDate)|Last Updated time of rollup field Team Size.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|
|[teamsizeState](#teamsizeState)|State of rollup field Team Size.|<a href="Project.md" target="_blank">projectServiceAutomation/Project</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#projectId name="projectId">projectId</a>

Shows the entity instances.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project</td></tr><tr><td>description</td><td>Shows the entity instances.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_projectid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Project  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Status</td></tr><tr><td>description</td><td>Status of the Project</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Project  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Project</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive - Sets project to read only</td><td>2</td><td>1</td></tr><tr><td>en</td><td>Closed - Sets project to read only and cancels future bookings</td><td>192350000</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#subject name="subject">subject</a>

Type the name of the custom entity.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type the name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_subject</td></tr></table>

### <a href=#processId name="processId">processId</a>

Contains the id of the process associated with the entity.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Id</td></tr><tr><td>description</td><td>Contains the id of the process associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Contains the id of the stage where the entity is located.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stage Id</td></tr><tr><td>description</td><td>Contains the id of the stage where the entity is located.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#actualDuration name="actualDuration">actualDuration</a>

Shows the actual duration of the project in minutes.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Duration</td></tr><tr><td>description</td><td>Shows the actual duration of the project in minutes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actualdurationminutes</td></tr></table>

### <a href=#actualEnd name="actualEnd">actualEnd</a>

Enter the actual end time of the project.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual End</td></tr><tr><td>description</td><td>Enter the actual end time of the project.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actualend</td></tr></table>

### <a href=#actualExpenseCost name="actualExpenseCost">actualExpenseCost</a>

Shows the aggregate of actual expense cost on the project.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Expense Cost</td></tr><tr><td>description</td><td>Shows the aggregate of actual expense cost on the project.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actualexpensecost</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Shows the currency associated with the entity.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Shows the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#actualexpensecostBase name="actualexpensecostBase">actualexpensecostBase</a>

Value of the Actual Expense Cost in base currency.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Expense Cost (Base)</td></tr><tr><td>description</td><td>Value of the Actual Expense Cost in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actualexpensecost_base</td></tr></table>

### <a href=#actualHours name="actualHours">actualHours</a>

Shows the total actual hours of the project  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Hours</td></tr><tr><td>description</td><td>Shows the total actual hours of the project</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actualhours</td></tr></table>

### <a href=#actualLaborCost name="actualLaborCost">actualLaborCost</a>

Shows the aggregate of actual labor cost on the project.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Labor Cost</td></tr><tr><td>description</td><td>Shows the aggregate of actual labor cost on the project.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actuallaborcost</td></tr></table>

### <a href=#actuallaborcostBase name="actuallaborcostBase">actuallaborcostBase</a>

Value of the Actual Labor Cost in base currency.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Labor Cost (Base)</td></tr><tr><td>description</td><td>Value of the Actual Labor Cost in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actuallaborcost_base</td></tr></table>

### <a href=#actualSales name="actualSales">actualSales</a>

Shows the actual sales value.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Sales</td></tr><tr><td>description</td><td>Shows the actual sales value.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actualsales</td></tr></table>

### <a href=#actualsalesBase name="actualsalesBase">actualsalesBase</a>

Shows the value of the actual sales in the base currency.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Sales (Base)</td></tr><tr><td>description</td><td>Shows the value of the actual sales in the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actualsales_base</td></tr></table>

### <a href=#actualStart name="actualStart">actualStart</a>

Enter the actual start time of the project.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Start</td></tr><tr><td>description</td><td>Enter the actual start time of the project.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_actualstart</td></tr></table>

### <a href=#bulkGenerationStatus name="bulkGenerationStatus">bulkGenerationStatus</a>

The status of the bulk generation operations running on the project entity. If no operation is running, the value is null.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bulk Generation Status</td></tr><tr><td>description</td><td>The status of the bulk generation operations running on the project entity. If no operation is running, the value is null.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_bulkgenerationstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Processing</td><td>192350000</td></tr><tr><td>en</td><td>Failed</td><td>192350001</td></tr></table></td></tr></table>

### <a href=#bulkGenerationStatus_display name="bulkGenerationStatus_display">bulkGenerationStatus_display</a>

First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#calendarId name="calendarId">calendarId</a>

Id of the calendar for the project.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Calendar Id</td></tr><tr><td>description</td><td>Id of the calendar for the project.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_calendarid</td></tr></table>

### <a href=#comments name="comments">comments</a>

Enter the comments that are used to describe the current project status.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Comments</td></tr><tr><td>description</td><td>Enter the comments that are used to describe the current project status.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_comments</td></tr></table>

### <a href=#contractOrganizationalUnitId name="contractOrganizationalUnitId">contractOrganizationalUnitId</a>

Select the organizational unit sponsoring the project.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contracting Unit</td></tr><tr><td>description</td><td>Select the organizational unit sponsoring the project.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_contractorganizationalunitid</td></tr></table>

### <a href=#customer name="customer">customer</a>

Enter the customer who the project is associated with.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>description</td><td>Enter the customer who the project is associated with.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_customer</td></tr></table>

### <a href=#description name="description">description</a>

Enter a description of the project.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Enter a description of the project.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_description</td></tr></table>

### <a href=#disableCreateOfTeamMemberForProjectManager name="disableCreateOfTeamMemberForProjectManager">disableCreateOfTeamMemberForProjectManager</a>

This is an internal field, mainly used during import so that we don't create a team member record for the project manager.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Disable create of team member for project manager</td></tr><tr><td>description</td><td>This is an internal field, mainly used during import so that we don't create a team member record for the project manager.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_disablecreateofteammemberformanager</td></tr></table>

### <a href=#effortestimateatcompleteEAC name="effortestimateatcompleteEAC">effortestimateatcompleteEAC</a>

Shows the total of actual hours and the remaining hours.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Effort estimate at complete (EAC)</td></tr><tr><td>description</td><td>Shows the total of actual hours and the remaining hours.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_effortestimateatcompleteeac</td></tr></table>

### <a href=#projectExchangeRate name="projectExchangeRate">projectExchangeRate</a>

Exchange rate for the currency associated with the project with respect to the base currency.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the project with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_exchangerate</td></tr></table>

### <a href=#isLinkedToMSProjectClient name="isLinkedToMSProjectClient">isLinkedToMSProjectClient</a>

Specifies if the project is linked to a project in MS Project  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Linked To MS Project Client</td></tr><tr><td>description</td><td>Specifies if the project is linked to a project in MS Project</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_islinkedtomsprojectclient</td></tr></table>

### <a href=#isTemplate name="isTemplate">isTemplate</a>

Shows if the project is a project template.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Template</td></tr><tr><td>description</td><td>Shows if the project is a project template.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_istemplate</td></tr></table>

### <a href=#linkedDocumentURL name="linkedDocumentURL">linkedDocumentURL</a>

The URL for the linked document.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Linked Document URL</td></tr><tr><td>description</td><td>The URL for the linked document.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_linkeddocumenturl</td></tr></table>

### <a href=#overallProjectStatus name="overallProjectStatus">overallProjectStatus</a>

Describes the project status.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Overall Project Status</td></tr><tr><td>description</td><td>Describes the project status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_overallprojectstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Green</td><td>1</td></tr><tr><td>en</td><td>Yellow</td><td>2</td></tr><tr><td>en</td><td>Red</td><td>3</td></tr></table></td></tr></table>

### <a href=#overallProjectStatus_display name="overallProjectStatus_display">overallProjectStatus_display</a>

First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#estimatedExpenseCost name="estimatedExpenseCost">estimatedExpenseCost</a>

Shows the aggregate of the planned expense cost of all the associated tasks.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Expense Cost</td></tr><tr><td>description</td><td>Shows the aggregate of the planned expense cost of all the associated tasks.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_plannedexpensecost</td></tr></table>

### <a href=#plannedexpensecostBase name="plannedexpensecostBase">plannedexpensecostBase</a>

Value of the Estimated Expense Cost in base currency.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Expense Cost (Base)</td></tr><tr><td>description</td><td>Value of the Estimated Expense Cost in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_plannedexpensecost_base</td></tr></table>

### <a href=#estimatedHours name="estimatedHours">estimatedHours</a>

Shows the total estimate hours of the project.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Hours</td></tr><tr><td>description</td><td>Shows the total estimate hours of the project.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_plannedhours</td></tr></table>

### <a href=#estimatedLaborCost name="estimatedLaborCost">estimatedLaborCost</a>

Shows the aggregate of the planned labor cost of all the associated tasks.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Labor Cost</td></tr><tr><td>description</td><td>Shows the aggregate of the planned labor cost of all the associated tasks.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_plannedlaborcost</td></tr></table>

### <a href=#plannedlaborcostBase name="plannedlaborcostBase">plannedlaborcostBase</a>

Value of the Estimated Labor Cost in base currency.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Labor Cost (Base)</td></tr><tr><td>description</td><td>Value of the Estimated Labor Cost in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_plannedlaborcost_base</td></tr></table>

### <a href=#plannedSales name="plannedSales">plannedSales</a>

Shows the total planned sales.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Planned Sales</td></tr><tr><td>description</td><td>Shows the total planned sales.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_plannedsales</td></tr></table>

### <a href=#plannedSalesBase name="plannedSalesBase">plannedSalesBase</a>

Shows the value of the planned sales in the base currency.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Planned Sales (Base)</td></tr><tr><td>description</td><td>Shows the value of the planned sales in the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_plannedsales_base</td></tr></table>

### <a href=#progress name="progress">progress</a>

Shows the actual hours divided by effort at estimate.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Progress %</td></tr><tr><td>description</td><td>Shows the actual hours divided by effort at estimate.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_progress</td></tr></table>

### <a href=#projectManager name="projectManager">projectManager</a>

Shows the project manager assigned to the project.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Manager</td></tr><tr><td>description</td><td>Shows the project manager assigned to the project.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_projectmanager</td></tr></table>

### <a href=#projectResourceRequirementsVisibleToResources name="projectResourceRequirementsVisibleToResources">projectResourceRequirementsVisibleToResources</a>

Indicates if the project resource requirements are visible to the resources assigned to the project.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project resource requirements visible to resources</td></tr><tr><td>description</td><td>Indicates if the project resource requirements are visible to the resources assigned to the project.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_projectresourcerequirementsvisibletore</td></tr></table>

### <a href=#projectTeamId name="projectTeamId">projectTeamId</a>

Select the Team associated with Project.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Team</td></tr><tr><td>description</td><td>Select the Team associated with Project.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_projectteamid</td></tr></table>

### <a href=#projectTemplate name="projectTemplate">projectTemplate</a>

Select the project template behind the project.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Template</td></tr><tr><td>description</td><td>Select the project template behind the project.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_projecttemplate</td></tr></table>

### <a href=#remainingCost name="remainingCost">remainingCost</a>

Shows the difference between the estimated cost and the actual cost.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Remaining Cost</td></tr><tr><td>description</td><td>Shows the difference between the estimated cost and the actual cost.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_remainingcost</td></tr></table>

### <a href=#remainingCostBase name="remainingCostBase">remainingCostBase</a>

Shows the value of the remaining cost in the  base currency.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Remaining Cost (Base)</td></tr><tr><td>description</td><td>Shows the value of the remaining cost in the  base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_remainingcost_base</td></tr></table>

### <a href=#remainingHours name="remainingHours">remainingHours</a>

Shows the difference between the estimate at completion (EAC) and the actual hours.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Remaining Hours</td></tr><tr><td>description</td><td>Shows the difference between the estimate at completion (EAC) and the actual hours.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_remaininghours</td></tr></table>

### <a href=#remainingSales name="remainingSales">remainingSales</a>

Shows the difference between estimated sales and the actual sales.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Remaining Sales</td></tr><tr><td>description</td><td>Shows the difference between estimated sales and the actual sales.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_remainingsales</td></tr></table>

### <a href=#remainingSalesBase name="remainingSalesBase">remainingSalesBase</a>

Shows the value of the remaining sales in the base currency.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Remaining Sales (Base)</td></tr><tr><td>description</td><td>Shows the value of the remaining sales in the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_remainingsales_base</td></tr></table>

### <a href=#salesOrderId name="salesOrderId">salesOrderId</a>

Shows the contract for this project.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contract</td></tr><tr><td>description</td><td>Shows the contract for this project.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salesorderid</td></tr></table>

### <a href=#scheduledDurationMinutes name="scheduledDurationMinutes">scheduledDurationMinutes</a>

Shows the scheduled duration of the project, specified in minutes.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scheduled Duration</td></tr><tr><td>description</td><td>Shows the scheduled duration of the project, specified in minutes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_scheduleddurationminutes</td></tr></table>

### <a href=#estimatedFinishDate name="estimatedFinishDate">estimatedFinishDate</a>

Enter the scheduled end time of the project.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Finish Date</td></tr><tr><td>description</td><td>Enter the scheduled end time of the project.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_scheduledend</td></tr></table>

### <a href=#scheduleStartDate name="scheduleStartDate">scheduleStartDate</a>

Enter the scheduled start time of the project.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date</td></tr><tr><td>description</td><td>Enter the scheduled start time of the project.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_scheduledstart</td></tr></table>

### <a href=#schedulePerformance name="schedulePerformance">schedulePerformance</a>

Describes the schedule performance of the project.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Schedule Performance</td></tr><tr><td>description</td><td>Describes the schedule performance of the project.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_scheduleperformance</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>On Time</td><td>192350000</td></tr><tr><td>en</td><td>Ahead</td><td>192350001</td></tr><tr><td>en</td><td>Behind</td><td>192350002</td></tr></table></td></tr></table>

### <a href=#schedulePerformance_display name="schedulePerformance_display">schedulePerformance_display</a>

First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#scheduleVariance name="scheduleVariance">scheduleVariance</a>

Shows the difference between the planned effort and the estimate at completion (EAC).  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Schedule Variance</td></tr><tr><td>description</td><td>Shows the difference between the planned effort and the estimate at completion (EAC).</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_schedulevariance</td></tr></table>

### <a href=#stageName name="stageName">stageName</a>

Shows the stage of the project (Deprecated in v3.0).  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stage Name (Deprecated in v3.0)</td></tr><tr><td>description</td><td>Shows the stage of the project (Deprecated in v3.0).</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_stagename</td></tr></table>

### <a href=#statusUpdatedOn name="statusUpdatedOn">statusUpdatedOn</a>

Shows the most recent update on a status field(comments or overall project status).  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Updated On</td></tr><tr><td>description</td><td>Shows the most recent update on a status field(comments or overall project status).</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_statusupdatedon</td></tr></table>

### <a href=#totalActualCost name="totalActualCost">totalActualCost</a>

Shows the aggregated cost from actuals on the project.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Total Cost</td></tr><tr><td>description</td><td>Shows the aggregated cost from actuals on the project.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_totalactualcost</td></tr></table>

### <a href=#totalActualCostBase name="totalActualCostBase">totalActualCostBase</a>

Shows the value of the total actual cost in the base currency.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Total Cost (Base)</td></tr><tr><td>description</td><td>Shows the value of the total actual cost in the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_totalactualcost_base</td></tr></table>

### <a href=#totalPlannedCost name="totalPlannedCost">totalPlannedCost</a>

Shows the aggregate of the total planned cost of all the associated tasks.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Total Cost</td></tr><tr><td>description</td><td>Shows the aggregate of the total planned cost of all the associated tasks.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_totalplannedcost</td></tr></table>

### <a href=#totalPlannedCostBase name="totalPlannedCostBase">totalPlannedCostBase</a>

Shows the value of the total planned cost in the base currency.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Total Cost (Base)</td></tr><tr><td>description</td><td>Shows the value of the total planned cost in the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_totalplannedcost_base</td></tr></table>

### <a href=#wbsDuration name="wbsDuration">wbsDuration</a>

Shows the work breakdown structure (WBS) duration in days.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Duration</td></tr><tr><td>description</td><td>Shows the work breakdown structure (WBS) duration in days.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_wbsduration</td></tr></table>

### <a href=#workHourTemplate name="workHourTemplate">workHourTemplate</a>

Select the work hour template used to create the project calendar.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Work hour template</td></tr><tr><td>description</td><td>Select the work hour template used to create the project calendar.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_workhourtemplate</td></tr></table>

### <a href=#costConsumption name="costConsumption">costConsumption</a>

Shows the actual cost divided by the estimated cost at completion.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost Consumption %</td></tr><tr><td>description</td><td>Shows the actual cost divided by the estimated cost at completion.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_costconsumption</td></tr></table>

### <a href=#costEstimateAtComplete name="costEstimateAtComplete">costEstimateAtComplete</a>

Sum of Actual Cost and Remaining cost  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost estimate at completion (EAC)</td></tr><tr><td>description</td><td>Sum of Actual Cost and Remaining cost</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_costestimateatcomplete</td></tr></table>

### <a href=#costEstimateAtCompleteBase name="costEstimateAtCompleteBase">costEstimateAtCompleteBase</a>

Value of the Cost estimate at completion (EAC) in base currency.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost estimate at completion (EAC)(Base)</td></tr><tr><td>description</td><td>Value of the Cost estimate at completion (EAC) in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_costestimateatcomplete_base</td></tr></table>

### <a href=#costPerformence name="costPerformence">costPerformence</a>

First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost Performance</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_costperformence</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>On Budget</td><td>192350000</td></tr><tr><td>en</td><td>Over Budget</td><td>192350001</td></tr><tr><td>en</td><td>Under Budget</td><td>192350002</td></tr></table></td></tr></table>

### <a href=#costPerformence_display name="costPerformence_display">costPerformence_display</a>

First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#costVariance name="costVariance">costVariance</a>

Variance between the estimated cost and the forecasted cost based on the estimate at completion (EAC).  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost Variance</td></tr><tr><td>description</td><td>Variance between the estimated cost and the forecasted cost based on the estimate at completion (EAC).</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_costvariance</td></tr></table>

### <a href=#costVarianceBase name="costVarianceBase">costVarianceBase</a>

Shows the value of the cost variance in the base currency.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost Variance (Base)</td></tr><tr><td>description</td><td>Shows the value of the cost variance in the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_costvariance_base</td></tr></table>

### <a href=#salesConsumption name="salesConsumption">salesConsumption</a>

Shows the actual sales divided by the estimated sales.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales Consumption %</td></tr><tr><td>description</td><td>Shows the actual sales divided by the estimated sales.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salesconsumption</td></tr></table>

### <a href=#salesEstimateAtCompleteEAC name="salesEstimateAtCompleteEAC">salesEstimateAtCompleteEAC</a>

Shows the total of actual and remaining sales.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales Estimate At Complete (EAC)</td></tr><tr><td>description</td><td>Shows the total of actual and remaining sales.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salesestimateatcompleteeac</td></tr></table>

### <a href=#salesEstimateAtCompleteEACBase name="salesEstimateAtCompleteEACBase">salesEstimateAtCompleteEACBase</a>

Value of the Sales Estimate At Complete (EAC) in base currency.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales Estimate At Complete (EAC) (Base)</td></tr><tr><td>description</td><td>Value of the Sales Estimate At Complete (EAC) in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salesestimateatcompleteeac_base</td></tr></table>

### <a href=#salesVariance name="salesVariance">salesVariance</a>

Shows the difference between the planned sales and the sales estimate at completion (EAC).  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales Variance</td></tr><tr><td>description</td><td>Shows the difference between the planned sales and the sales estimate at completion (EAC).</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salesvariance</td></tr></table>

### <a href=#salesVarianceBase name="salesVarianceBase">salesVarianceBase</a>

Shows the value of the sales variance in the base currency.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales Variance (Base)</td></tr><tr><td>description</td><td>Shows the value of the sales variance in the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salesvariance_base</td></tr></table>

### <a href=#teamSize name="teamSize">teamSize</a>

Shows the total number of team members assigned to this project  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Team Size</td></tr><tr><td>description</td><td>Shows the total number of team members assigned to this project</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_teamsize</td></tr></table>

### <a href=#teamsizeDate name="teamsizeDate">teamsizeDate</a>

Last Updated time of rollup field Team Size.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Team Size (Last Updated On)</td></tr><tr><td>description</td><td>Last Updated time of rollup field Team Size.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_teamsize_date</td></tr></table>

### <a href=#teamsizeState name="teamsizeState">teamsizeState</a>

State of rollup field Team Size.  
First included in: projectServiceAutomation/Project (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Team Size (State)</td></tr><tr><td>description</td><td>State of rollup field Team Size.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_teamsize_state</td></tr></table>
