---
title: Goal - Common Data Model | Microsoft Docs
description: Target objective for a user or a team for a specified time period.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# Goal

Target objective for a user or a team for a specified time period.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/Goal.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /Goal  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[goalId](#goalId)|Unique identifier of the goal.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[stateCode](#stateCode)|Shows whether the goal is open, completed, or canceled. Completed and canceled goals are read-only and can't be edited.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[stateCode_display](#stateCode_display)||<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[statusCode](#statusCode)|Select the goal's status.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[statusCode_display](#statusCode_display)||<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[title](#title)|Type a title or name that describes the goal.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[fiscalPeriod](#fiscalPeriod)|Select the fiscal period for the goal.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[fiscalPeriod_display](#fiscalPeriod_display)||<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[fiscalYear](#fiscalYear)|Select the fiscal year for the goal that's being tracked.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[fiscalYear_display](#fiscalYear_display)||<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[goalStartDate](#goalStartDate)|Enter the date and time when the period for tracking the goal begins.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[goalEndDate](#goalEndDate)|Enter the date when the goal ends.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[goalOwnerIdType](#goalOwnerIdType)|The name of the entity linked by goalOwnerId|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[goalOwnerId](#goalOwnerId)|Choose the user or team responsible for meeting the goal.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[parentGoalId](#parentGoalId)|Choose a parent goal if the current goal is a child goal. This sets up a parent-child relationship for reporting and analytics.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[metricId](#metricId)|Choose the metric for the goal. This metric determines how the goal is tracked.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[treeId](#treeId)|Unique identifier of the goal tree.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[depth](#depth)|Depth of the goal in the tree.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[stretchTargetMoney](#stretchTargetMoney)|Select stretch target (money) of the goal to define a higher or difficult level of goal than the usual ones.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[stretchTargetMoneyBase](#stretchTargetMoneyBase)|Shows the stretch target (money) in base currency to indicate a higher or difficult level of goal than the usual ones.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[stretchTargetDecimal](#stretchTargetDecimal)|Select a stretch target (decimal) of the goal to define a higher or difficult level of goal than the usual ones.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[stretchTargetInteger](#stretchTargetInteger)|Select the stretch target (integer) of the goal to define a higher or difficult level of goal than the usual ones.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[targetMoney](#targetMoney)|Select a goal target (money) to track a monetary amount such as revenue from a product.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[targetMoneyBase](#targetMoneyBase)|Shows the goal target of the money type in base currency.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[targetDecimal](#targetDecimal)|Select a goal target of the decimal type to use for tracking data that include partial numbers, such as pounds sold of a product sold by weight.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[targetInteger](#targetInteger)|Select a goal target of the integer type to use for tracking anything countable in whole numbers, such as units sold.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[actualMoney](#actualMoney)|Shows the actual value (Money type) achieved towards the target as of the last rolled-up date. This field appears when the metric type of the goal is Amount and the amount data type is Money.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[actualMoneyBase](#actualMoneyBase)|Shows the actual value (money type) in base currency to track goal results against the target.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[customRollupFieldMoney](#customRollupFieldMoney)|Indicates a placeholder rollup field for a money value to track a third category of results other than actuals and in-progress results.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[customRollupFieldMoneyBase](#customRollupFieldMoneyBase)|Indicates a placeholder rollup field for a money value in base currency to track a third category of results other than actuals and in-progress results.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[inProgressMoney](#inProgressMoney)|Shows the in-progress value (money) against the target. This value could contribute to a goal, but is not counted yet as actual.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[inProgressMoneyBase](#inProgressMoneyBase)|Shows the in-progress value (money) in base currency to track goal results against the target.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[actualDecimal](#actualDecimal)|Shows the actual value (Decimal type) achieved towards the target as of the last rolled-up date. This field appears when the metric type of the goal is Amount and the amount data type is Decimal.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[customRollupFieldDecimal](#customRollupFieldDecimal)|Indicates a placeholder rollup field for a decimal value to track a third category of results other than actuals and in-progress results.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[inProgressDecimal](#inProgressDecimal)|Shows the in-progress value (decimal) against the target. This value could contribute to a goal, but is not counted yet as actual.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[actualInteger](#actualInteger)|Shows the actual value (integer) achieved towards the target as of the last rolled-up date. This field appears when the metric type of the goal is Amount or Count and the amount data type is Integer.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[customRollupFieldInteger](#customRollupFieldInteger)|Indicates a placeholder rollup field for an integer value to track a third category of results other than actuals and in-progress results.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[inProgressInteger](#inProgressInteger)|Shows the in-progress value (integer) against the target. This value could contribute to a goal, but is not counted yet as actual.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[percentage](#percentage)|Shows the percentage achieved against the target goal.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[isFiscalPeriodGoal](#isFiscalPeriodGoal)|Select whether the goal period is a fiscal period or custom period.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[considerOnlyGoalOwnersRecords](#considerOnlyGoalOwnersRecords)|Select whether only the goal owner's records, or all records, should be rolled up for goal results.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[lastRolledupDate](#lastRolledupDate)|Shows the date and time when the goal was last rolled up. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[targetString](#targetString)|Target value of the goal.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[stretchTargetString](#stretchTargetString)|Stretch target value for all data types.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[actualString](#actualString)|Actual Value of the goal.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[customRollupFieldString](#customRollupFieldString)|Placeholder rollup field for the goal.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[inProgressString](#inProgressString)|In-progress value of the goal.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[amountDataType](#amountDataType)|Data type of the amount.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[amountDataType_display](#amountDataType_display)||<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[isAmount](#isAmount)|Indicates whether the metric type is Count or Amount.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[rollupQueryActualIntegerId](#rollupQueryActualIntegerId)|Choose the query that will be used to calculate the actual data for the goal (integer).|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[rollUpQueryActualMoneyId](#rollUpQueryActualMoneyId)|Choose the query that will be used to calculate the actual data for the goal (money).|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[rollUpQueryActualDecimalId](#rollUpQueryActualDecimalId)|Choose the query that will be used to calculate the actual data for the goal (decimal).|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[rollUpQueryCustomIntegerId](#rollUpQueryCustomIntegerId)|Choose the query that will be used to calculate data for the custom rollup field (integer).|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[rollUpQueryCustomMoneyId](#rollUpQueryCustomMoneyId)|Choose the query that will be used to calculate data for the custom rollup field (money).|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[rollUpQueryCustomDecimalId](#rollUpQueryCustomDecimalId)|Choose the query that will be used to calculate data for the custom rollup field (decimal).|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[rollUpQueryInprogressIntegerId](#rollUpQueryInprogressIntegerId)|Choose the query that will be used to calculate data for the in-progress rollup field (integer).|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[rollUpQueryInprogressMoneyId](#rollUpQueryInprogressMoneyId)|Choose the query that will be used to calculate data for the in-progress rollup field (money).|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[rollUpQueryInprogressDecimalId](#rollUpQueryInprogressDecimalId)|Choose the query that will be used to calculate data for the in-progress rollup field (decimal).|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[rollupOnlyFromChildGoals](#rollupOnlyFromChildGoals)|Select whether the data should be rolled up only from the child goals.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[goalWithErrorId](#goalWithErrorId)|Unique identifier of the goal that caused an error in the rollup of the goal hierarchy.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[rollupErrorCode](#rollupErrorCode)|Error code associated with rollup.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[computedTargetAsOfTodayPercentageAchieved](#computedTargetAsOfTodayPercentageAchieved)|Shows the expected value for percentage achieved against the target goal as of the current date.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[computedTargetAsOfTodayMoney](#computedTargetAsOfTodayMoney)|Shows the expected amount for actual value (money type) against the target goal as of the current date.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[computedTargetAsOfTodayMoneyBase](#computedTargetAsOfTodayMoneyBase)|Shows the expected amount in base currency for actual value (money type) against the target goal as of the current date.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[computedTargetAsOfTodayDecimal](#computedTargetAsOfTodayDecimal)|Shows the expected amount for actual value (decimal type) against the target goal.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[computedTargetAsOfTodayInteger](#computedTargetAsOfTodayInteger)|Shows the expected amount for actual value (integer type) against the target goal as of the current date.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[isOverride](#isOverride)|Indicates whether the values of system rollup fields can be updated.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[isOverridden](#isOverridden)|Select whether the system rollup fields are updated. If set to Yes, the next system rollup will not update the values of the rollup fields with the system calculated values.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|
|[entityImageId](#entityImageId)|For internal use only.|<a href="Goal.md" target="_blank">applicationCommon/Goal</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#goalId name="goalId">goalId</a>

Unique identifier of the goal.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Goal</td></tr><tr><td>description</td><td>Unique identifier of the goal.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>goalid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the goal is open, completed, or canceled. Completed and canceled goals are read-only and can't be edited.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows whether the goal is open, completed, or canceled. Completed and canceled goals are read-only and can't be edited.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the goal's status.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the goal's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Open</td><td>0</td><td>0</td></tr><tr><td>en</td><td>Closed</td><td>1</td><td>1</td></tr><tr><td>en</td><td>Discarded</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#title name="title">title</a>

Type a title or name that describes the goal.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type a title or name that describes the goal.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>title</td></tr></table>

### <a href=#fiscalPeriod name="fiscalPeriod">fiscalPeriod</a>

Select the fiscal period for the goal.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fiscal Period</td></tr><tr><td>description</td><td>Select the fiscal period for the goal.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>fiscalperiod</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Quarter 1</td><td>1</td></tr><tr><td>en</td><td>Quarter 2</td><td>2</td></tr><tr><td>en</td><td>Quarter 3</td><td>3</td></tr><tr><td>en</td><td>Quarter 4</td><td>4</td></tr><tr><td>en</td><td>January</td><td>101</td></tr><tr><td>en</td><td>February</td><td>102</td></tr><tr><td>en</td><td>March</td><td>103</td></tr><tr><td>en</td><td>April</td><td>104</td></tr><tr><td>en</td><td>May</td><td>105</td></tr><tr><td>en</td><td>June</td><td>106</td></tr><tr><td>en</td><td>July</td><td>107</td></tr><tr><td>en</td><td>August</td><td>108</td></tr><tr><td>en</td><td>September</td><td>109</td></tr><tr><td>en</td><td>October</td><td>110</td></tr><tr><td>en</td><td>November</td><td>111</td></tr><tr><td>en</td><td>December</td><td>112</td></tr><tr><td>en</td><td>Semester 1</td><td>201</td></tr><tr><td>en</td><td>Semester 2</td><td>202</td></tr><tr><td>en</td><td>Annual</td><td>301</td></tr><tr><td>en</td><td>P1</td><td>401</td></tr><tr><td>en</td><td>P2</td><td>402</td></tr><tr><td>en</td><td>P3</td><td>403</td></tr><tr><td>en</td><td>P4</td><td>404</td></tr><tr><td>en</td><td>P5</td><td>405</td></tr><tr><td>en</td><td>P6</td><td>406</td></tr><tr><td>en</td><td>P7</td><td>407</td></tr><tr><td>en</td><td>P8</td><td>408</td></tr><tr><td>en</td><td>P9</td><td>409</td></tr><tr><td>en</td><td>P10</td><td>410</td></tr><tr><td>en</td><td>P11</td><td>411</td></tr><tr><td>en</td><td>P12</td><td>412</td></tr><tr><td>en</td><td>P13</td><td>413</td></tr></table></td></tr></table>

### <a href=#fiscalPeriod_display name="fiscalPeriod_display">fiscalPeriod_display</a>

First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#fiscalYear name="fiscalYear">fiscalYear</a>

Select the fiscal year for the goal that's being tracked.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fiscal Year</td></tr><tr><td>description</td><td>Select the fiscal year for the goal that's being tracked.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>fiscalyear</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>FY2038</td><td>2038</td></tr><tr><td>en</td><td>FY2037</td><td>2037</td></tr><tr><td>en</td><td>FY2036</td><td>2036</td></tr><tr><td>en</td><td>FY2035</td><td>2035</td></tr><tr><td>en</td><td>FY2034</td><td>2034</td></tr><tr><td>en</td><td>FY2033</td><td>2033</td></tr><tr><td>en</td><td>FY2032</td><td>2032</td></tr><tr><td>en</td><td>FY2031</td><td>2031</td></tr><tr><td>en</td><td>FY2030</td><td>2030</td></tr><tr><td>en</td><td>FY2029</td><td>2029</td></tr><tr><td>en</td><td>FY2028</td><td>2028</td></tr><tr><td>en</td><td>FY2027</td><td>2027</td></tr><tr><td>en</td><td>FY2026</td><td>2026</td></tr><tr><td>en</td><td>FY2025</td><td>2025</td></tr><tr><td>en</td><td>FY2024</td><td>2024</td></tr><tr><td>en</td><td>FY2023</td><td>2023</td></tr><tr><td>en</td><td>FY2022</td><td>2022</td></tr><tr><td>en</td><td>FY2021</td><td>2021</td></tr><tr><td>en</td><td>FY2020</td><td>2020</td></tr><tr><td>en</td><td>FY2019</td><td>2019</td></tr><tr><td>en</td><td>FY2018</td><td>2018</td></tr><tr><td>en</td><td>FY2017</td><td>2017</td></tr><tr><td>en</td><td>FY2016</td><td>2016</td></tr><tr><td>en</td><td>FY2015</td><td>2015</td></tr><tr><td>en</td><td>FY2014</td><td>2014</td></tr><tr><td>en</td><td>FY2013</td><td>2013</td></tr><tr><td>en</td><td>FY2012</td><td>2012</td></tr><tr><td>en</td><td>FY2011</td><td>2011</td></tr><tr><td>en</td><td>FY2010</td><td>2010</td></tr><tr><td>en</td><td>FY2009</td><td>2009</td></tr><tr><td>en</td><td>FY2008</td><td>2008</td></tr><tr><td>en</td><td>FY2007</td><td>2007</td></tr><tr><td>en</td><td>FY2006</td><td>2006</td></tr><tr><td>en</td><td>FY2005</td><td>2005</td></tr><tr><td>en</td><td>FY2004</td><td>2004</td></tr><tr><td>en</td><td>FY2003</td><td>2003</td></tr><tr><td>en</td><td>FY2002</td><td>2002</td></tr><tr><td>en</td><td>FY2001</td><td>2001</td></tr><tr><td>en</td><td>FY2000</td><td>2000</td></tr><tr><td>en</td><td>FY1999</td><td>1999</td></tr><tr><td>en</td><td>FY1998</td><td>1998</td></tr><tr><td>en</td><td>FY1997</td><td>1997</td></tr><tr><td>en</td><td>FY1996</td><td>1996</td></tr><tr><td>en</td><td>FY1995</td><td>1995</td></tr><tr><td>en</td><td>FY1994</td><td>1994</td></tr><tr><td>en</td><td>FY1993</td><td>1993</td></tr><tr><td>en</td><td>FY1992</td><td>1992</td></tr><tr><td>en</td><td>FY1991</td><td>1991</td></tr><tr><td>en</td><td>FY1990</td><td>1990</td></tr><tr><td>en</td><td>FY1989</td><td>1989</td></tr><tr><td>en</td><td>FY1988</td><td>1988</td></tr><tr><td>en</td><td>FY1987</td><td>1987</td></tr><tr><td>en</td><td>FY1986</td><td>1986</td></tr><tr><td>en</td><td>FY1985</td><td>1985</td></tr><tr><td>en</td><td>FY1984</td><td>1984</td></tr><tr><td>en</td><td>FY1983</td><td>1983</td></tr><tr><td>en</td><td>FY1982</td><td>1982</td></tr><tr><td>en</td><td>FY1981</td><td>1981</td></tr><tr><td>en</td><td>FY1980</td><td>1980</td></tr><tr><td>en</td><td>FY1979</td><td>1979</td></tr><tr><td>en</td><td>FY1978</td><td>1978</td></tr><tr><td>en</td><td>FY1977</td><td>1977</td></tr><tr><td>en</td><td>FY1976</td><td>1976</td></tr><tr><td>en</td><td>FY1975</td><td>1975</td></tr><tr><td>en</td><td>FY1974</td><td>1974</td></tr><tr><td>en</td><td>FY1973</td><td>1973</td></tr><tr><td>en</td><td>FY1972</td><td>1972</td></tr><tr><td>en</td><td>FY1971</td><td>1971</td></tr><tr><td>en</td><td>FY1970</td><td>1970</td></tr></table></td></tr></table>

### <a href=#fiscalYear_display name="fiscalYear_display">fiscalYear_display</a>

First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#goalStartDate name="goalStartDate">goalStartDate</a>

Enter the date and time when the period for tracking the goal begins.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>From</td></tr><tr><td>description</td><td>Enter the date and time when the period for tracking the goal begins.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>goalstartdate</td></tr></table>

### <a href=#goalEndDate name="goalEndDate">goalEndDate</a>

Enter the date when the goal ends.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>To</td></tr><tr><td>description</td><td>Enter the date when the goal ends.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>goalenddate</td></tr></table>

### <a href=#goalOwnerIdType name="goalOwnerIdType">goalOwnerIdType</a>

The name of the entity linked by goalOwnerId  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>goalOwnerId Type</td></tr><tr><td>description</td><td>The name of the entity linked by goalOwnerId</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>goalowneridtype</td></tr></table>

### <a href=#goalOwnerId name="goalOwnerId">goalOwnerId</a>

Choose the user or team responsible for meeting the goal.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Goal Owner</td></tr><tr><td>description</td><td>Choose the user or team responsible for meeting the goal.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>goalownerid</td></tr></table>

### <a href=#parentGoalId name="parentGoalId">parentGoalId</a>

Choose a parent goal if the current goal is a child goal. This sets up a parent-child relationship for reporting and analytics.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent Goal</td></tr><tr><td>description</td><td>Choose a parent goal if the current goal is a child goal. This sets up a parent-child relationship for reporting and analytics.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>parentgoalid</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#metricId name="metricId">metricId</a>

Choose the metric for the goal. This metric determines how the goal is tracked.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Goal Metric</td></tr><tr><td>description</td><td>Choose the metric for the goal. This metric determines how the goal is tracked.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>metricid</td></tr></table>

### <a href=#treeId name="treeId">treeId</a>

Unique identifier of the goal tree.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tree ID</td></tr><tr><td>description</td><td>Unique identifier of the goal tree.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>treeid</td></tr></table>

### <a href=#depth name="depth">depth</a>

Depth of the goal in the tree.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Depth</td></tr><tr><td>description</td><td>Depth of the goal in the tree.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>depth</td></tr></table>

### <a href=#stretchTargetMoney name="stretchTargetMoney">stretchTargetMoney</a>

Select stretch target (money) of the goal to define a higher or difficult level of goal than the usual ones.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stretch Target (Money)</td></tr><tr><td>description</td><td>Select stretch target (money) of the goal to define a higher or difficult level of goal than the usual ones.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stretchtargetmoney</td></tr></table>

### <a href=#stretchTargetMoneyBase name="stretchTargetMoneyBase">stretchTargetMoneyBase</a>

Shows the stretch target (money) in base currency to indicate a higher or difficult level of goal than the usual ones.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stretch Target (Money) (Base)</td></tr><tr><td>description</td><td>Shows the stretch target (money) in base currency to indicate a higher or difficult level of goal than the usual ones.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stretchtargetmoney_base</td></tr></table>

### <a href=#stretchTargetDecimal name="stretchTargetDecimal">stretchTargetDecimal</a>

Select a stretch target (decimal) of the goal to define a higher or difficult level of goal than the usual ones.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stretch Target (Decimal)</td></tr><tr><td>description</td><td>Select a stretch target (decimal) of the goal to define a higher or difficult level of goal than the usual ones.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stretchtargetdecimal</td></tr></table>

### <a href=#stretchTargetInteger name="stretchTargetInteger">stretchTargetInteger</a>

Select the stretch target (integer) of the goal to define a higher or difficult level of goal than the usual ones.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stretch Target (Integer)</td></tr><tr><td>description</td><td>Select the stretch target (integer) of the goal to define a higher or difficult level of goal than the usual ones.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stretchtargetinteger</td></tr></table>

### <a href=#targetMoney name="targetMoney">targetMoney</a>

Select a goal target (money) to track a monetary amount such as revenue from a product.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Target (Money)</td></tr><tr><td>description</td><td>Select a goal target (money) to track a monetary amount such as revenue from a product.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>targetmoney</td></tr></table>

### <a href=#targetMoneyBase name="targetMoneyBase">targetMoneyBase</a>

Shows the goal target of the money type in base currency.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Target (Money) (Base)</td></tr><tr><td>description</td><td>Shows the goal target of the money type in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>targetmoney_base</td></tr></table>

### <a href=#targetDecimal name="targetDecimal">targetDecimal</a>

Select a goal target of the decimal type to use for tracking data that include partial numbers, such as pounds sold of a product sold by weight.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Target (Decimal)</td></tr><tr><td>description</td><td>Select a goal target of the decimal type to use for tracking data that include partial numbers, such as pounds sold of a product sold by weight.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>targetdecimal</td></tr></table>

### <a href=#targetInteger name="targetInteger">targetInteger</a>

Select a goal target of the integer type to use for tracking anything countable in whole numbers, such as units sold.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Target (Integer)</td></tr><tr><td>description</td><td>Select a goal target of the integer type to use for tracking anything countable in whole numbers, such as units sold.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>targetinteger</td></tr></table>

### <a href=#actualMoney name="actualMoney">actualMoney</a>

Shows the actual value (Money type) achieved towards the target as of the last rolled-up date. This field appears when the metric type of the goal is Amount and the amount data type is Money.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual (Money)</td></tr><tr><td>description</td><td>Shows the actual value (Money type) achieved towards the target as of the last rolled-up date. This field appears when the metric type of the goal is Amount and the amount data type is Money.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualmoney</td></tr></table>

### <a href=#actualMoneyBase name="actualMoneyBase">actualMoneyBase</a>

Shows the actual value (money type) in base currency to track goal results against the target.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual (Money) (Base)</td></tr><tr><td>description</td><td>Shows the actual value (money type) in base currency to track goal results against the target.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualmoney_base</td></tr></table>

### <a href=#customRollupFieldMoney name="customRollupFieldMoney">customRollupFieldMoney</a>

Indicates a placeholder rollup field for a money value to track a third category of results other than actuals and in-progress results.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Custom Rollup Field (Money)</td></tr><tr><td>description</td><td>Indicates a placeholder rollup field for a money value to track a third category of results other than actuals and in-progress results.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customrollupfieldmoney</td></tr></table>

### <a href=#customRollupFieldMoneyBase name="customRollupFieldMoneyBase">customRollupFieldMoneyBase</a>

Indicates a placeholder rollup field for a money value in base currency to track a third category of results other than actuals and in-progress results.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Custom Rollup Field (Money) (Base)</td></tr><tr><td>description</td><td>Indicates a placeholder rollup field for a money value in base currency to track a third category of results other than actuals and in-progress results.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customrollupfieldmoney_base</td></tr></table>

### <a href=#inProgressMoney name="inProgressMoney">inProgressMoney</a>

Shows the in-progress value (money) against the target. This value could contribute to a goal, but is not counted yet as actual.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>In-progress (Money)</td></tr><tr><td>description</td><td>Shows the in-progress value (money) against the target. This value could contribute to a goal, but is not counted yet as actual.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>inprogressmoney</td></tr></table>

### <a href=#inProgressMoneyBase name="inProgressMoneyBase">inProgressMoneyBase</a>

Shows the in-progress value (money) in base currency to track goal results against the target.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>In-progress (Money) (Base)</td></tr><tr><td>description</td><td>Shows the in-progress value (money) in base currency to track goal results against the target.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>inprogressmoney_base</td></tr></table>

### <a href=#actualDecimal name="actualDecimal">actualDecimal</a>

Shows the actual value (Decimal type) achieved towards the target as of the last rolled-up date. This field appears when the metric type of the goal is Amount and the amount data type is Decimal.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual (Decimal)</td></tr><tr><td>description</td><td>Shows the actual value (Decimal type) achieved towards the target as of the last rolled-up date. This field appears when the metric type of the goal is Amount and the amount data type is Decimal.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualdecimal</td></tr></table>

### <a href=#customRollupFieldDecimal name="customRollupFieldDecimal">customRollupFieldDecimal</a>

Indicates a placeholder rollup field for a decimal value to track a third category of results other than actuals and in-progress results.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Custom Rollup Field (Decimal)</td></tr><tr><td>description</td><td>Indicates a placeholder rollup field for a decimal value to track a third category of results other than actuals and in-progress results.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customrollupfielddecimal</td></tr></table>

### <a href=#inProgressDecimal name="inProgressDecimal">inProgressDecimal</a>

Shows the in-progress value (decimal) against the target. This value could contribute to a goal, but is not counted yet as actual.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>In-progress (Decimal)</td></tr><tr><td>description</td><td>Shows the in-progress value (decimal) against the target. This value could contribute to a goal, but is not counted yet as actual.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>inprogressdecimal</td></tr></table>

### <a href=#actualInteger name="actualInteger">actualInteger</a>

Shows the actual value (integer) achieved towards the target as of the last rolled-up date. This field appears when the metric type of the goal is Amount or Count and the amount data type is Integer.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual (Integer)</td></tr><tr><td>description</td><td>Shows the actual value (integer) achieved towards the target as of the last rolled-up date. This field appears when the metric type of the goal is Amount or Count and the amount data type is Integer.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualinteger</td></tr></table>

### <a href=#customRollupFieldInteger name="customRollupFieldInteger">customRollupFieldInteger</a>

Indicates a placeholder rollup field for an integer value to track a third category of results other than actuals and in-progress results.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Custom Rollup Field (Integer)</td></tr><tr><td>description</td><td>Indicates a placeholder rollup field for an integer value to track a third category of results other than actuals and in-progress results.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customrollupfieldinteger</td></tr></table>

### <a href=#inProgressInteger name="inProgressInteger">inProgressInteger</a>

Shows the in-progress value (integer) against the target. This value could contribute to a goal, but is not counted yet as actual.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>In-progress (Integer)</td></tr><tr><td>description</td><td>Shows the in-progress value (integer) against the target. This value could contribute to a goal, but is not counted yet as actual.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>inprogressinteger</td></tr></table>

### <a href=#percentage name="percentage">percentage</a>

Shows the percentage achieved against the target goal.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Percentage Achieved</td></tr><tr><td>description</td><td>Shows the percentage achieved against the target goal.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>percentage</td></tr></table>

### <a href=#isFiscalPeriodGoal name="isFiscalPeriodGoal">isFiscalPeriodGoal</a>

Select whether the goal period is a fiscal period or custom period.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Goal Period Type</td></tr><tr><td>description</td><td>Select whether the goal period is a fiscal period or custom period.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isfiscalperiodgoal</td></tr></table>

### <a href=#considerOnlyGoalOwnersRecords name="considerOnlyGoalOwnersRecords">considerOnlyGoalOwnersRecords</a>

Select whether only the goal owner's records, or all records, should be rolled up for goal results.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Set for Rollup</td></tr><tr><td>description</td><td>Select whether only the goal owner's records, or all records, should be rolled up for goal results.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>consideronlygoalownersrecords</td></tr></table>

### <a href=#lastRolledupDate name="lastRolledupDate">lastRolledupDate</a>

Shows the date and time when the goal was last rolled up. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Rolled Up Date</td></tr><tr><td>description</td><td>Shows the date and time when the goal was last rolled up. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastrolledupdate</td></tr></table>

### <a href=#targetString name="targetString">targetString</a>

Target value of the goal.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Target</td></tr><tr><td>description</td><td>Target value of the goal.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>targetstring</td></tr></table>

### <a href=#stretchTargetString name="stretchTargetString">stretchTargetString</a>

Stretch target value for all data types.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stretched Target</td></tr><tr><td>description</td><td>Stretch target value for all data types.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stretchtargetstring</td></tr></table>

### <a href=#actualString name="actualString">actualString</a>

Actual Value of the goal.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual</td></tr><tr><td>description</td><td>Actual Value of the goal.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualstring</td></tr></table>

### <a href=#customRollupFieldString name="customRollupFieldString">customRollupFieldString</a>

Placeholder rollup field for the goal.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Custom Rollup Field</td></tr><tr><td>description</td><td>Placeholder rollup field for the goal.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customrollupfieldstring</td></tr></table>

### <a href=#inProgressString name="inProgressString">inProgressString</a>

In-progress value of the goal.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>In-Progress</td></tr><tr><td>description</td><td>In-progress value of the goal.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>inprogressstring</td></tr></table>

### <a href=#amountDataType name="amountDataType">amountDataType</a>

Data type of the amount.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount Data Type</td></tr><tr><td>description</td><td>Data type of the amount.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>amountdatatype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Money</td><td>0</td></tr><tr><td>en</td><td>Decimal</td><td>1</td></tr><tr><td>en</td><td>Integer</td><td>2</td></tr></table></td></tr></table>

### <a href=#amountDataType_display name="amountDataType_display">amountDataType_display</a>

First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#isAmount name="isAmount">isAmount</a>

Indicates whether the metric type is Count or Amount.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Metric Type</td></tr><tr><td>description</td><td>Indicates whether the metric type is Count or Amount.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isamount</td></tr></table>

### <a href=#rollupQueryActualIntegerId name="rollupQueryActualIntegerId">rollupQueryActualIntegerId</a>

Choose the query that will be used to calculate the actual data for the goal (integer).  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rollup Query - Actual(Integer)</td></tr><tr><td>description</td><td>Choose the query that will be used to calculate the actual data for the goal (integer).</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rollupqueryactualintegerid</td></tr></table>

### <a href=#rollUpQueryActualMoneyId name="rollUpQueryActualMoneyId">rollUpQueryActualMoneyId</a>

Choose the query that will be used to calculate the actual data for the goal (money).  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rollup Query - Actual(Money)</td></tr><tr><td>description</td><td>Choose the query that will be used to calculate the actual data for the goal (money).</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rollupqueryactualmoneyid</td></tr></table>

### <a href=#rollUpQueryActualDecimalId name="rollUpQueryActualDecimalId">rollUpQueryActualDecimalId</a>

Choose the query that will be used to calculate the actual data for the goal (decimal).  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rollup Query - Actual(Decimal)</td></tr><tr><td>description</td><td>Choose the query that will be used to calculate the actual data for the goal (decimal).</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rollupqueryactualdecimalid</td></tr></table>

### <a href=#rollUpQueryCustomIntegerId name="rollUpQueryCustomIntegerId">rollUpQueryCustomIntegerId</a>

Choose the query that will be used to calculate data for the custom rollup field (integer).  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rollup Query - Custom Rollup Field (Integer)</td></tr><tr><td>description</td><td>Choose the query that will be used to calculate data for the custom rollup field (integer).</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rollupquerycustomintegerid</td></tr></table>

### <a href=#rollUpQueryCustomMoneyId name="rollUpQueryCustomMoneyId">rollUpQueryCustomMoneyId</a>

Choose the query that will be used to calculate data for the custom rollup field (money).  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rollup Query - Custom Rollup Field (Money)</td></tr><tr><td>description</td><td>Choose the query that will be used to calculate data for the custom rollup field (money).</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rollupquerycustommoneyid</td></tr></table>

### <a href=#rollUpQueryCustomDecimalId name="rollUpQueryCustomDecimalId">rollUpQueryCustomDecimalId</a>

Choose the query that will be used to calculate data for the custom rollup field (decimal).  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rollup Query - Custom Rollup Field (Decimal)</td></tr><tr><td>description</td><td>Choose the query that will be used to calculate data for the custom rollup field (decimal).</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rollupquerycustomdecimalid</td></tr></table>

### <a href=#rollUpQueryInprogressIntegerId name="rollUpQueryInprogressIntegerId">rollUpQueryInprogressIntegerId</a>

Choose the query that will be used to calculate data for the in-progress rollup field (integer).  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rollup Query - In-progress(Integer)</td></tr><tr><td>description</td><td>Choose the query that will be used to calculate data for the in-progress rollup field (integer).</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rollupqueryinprogressintegerid</td></tr></table>

### <a href=#rollUpQueryInprogressMoneyId name="rollUpQueryInprogressMoneyId">rollUpQueryInprogressMoneyId</a>

Choose the query that will be used to calculate data for the in-progress rollup field (money).  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rollup Query - In-progress(Money)</td></tr><tr><td>description</td><td>Choose the query that will be used to calculate data for the in-progress rollup field (money).</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rollupqueryinprogressmoneyid</td></tr></table>

### <a href=#rollUpQueryInprogressDecimalId name="rollUpQueryInprogressDecimalId">rollUpQueryInprogressDecimalId</a>

Choose the query that will be used to calculate data for the in-progress rollup field (decimal).  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rollup Query - In-progress(Decimal)</td></tr><tr><td>description</td><td>Choose the query that will be used to calculate data for the in-progress rollup field (decimal).</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rollupqueryinprogressdecimalid</td></tr></table>

### <a href=#rollupOnlyFromChildGoals name="rollupOnlyFromChildGoals">rollupOnlyFromChildGoals</a>

Select whether the data should be rolled up only from the child goals.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Roll Up Only from Child Goals</td></tr><tr><td>description</td><td>Select whether the data should be rolled up only from the child goals.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>rolluponlyfromchildgoals</td></tr></table>

### <a href=#goalWithErrorId name="goalWithErrorId">goalWithErrorId</a>

Unique identifier of the goal that caused an error in the rollup of the goal hierarchy.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Goal With Error</td></tr><tr><td>description</td><td>Unique identifier of the goal that caused an error in the rollup of the goal hierarchy.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>goalwitherrorid</td></tr></table>

### <a href=#rollupErrorCode name="rollupErrorCode">rollupErrorCode</a>

Error code associated with rollup.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rollup Error Code</td></tr><tr><td>description</td><td>Error code associated with rollup.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rolluperrorcode</td></tr></table>

### <a href=#computedTargetAsOfTodayPercentageAchieved name="computedTargetAsOfTodayPercentageAchieved">computedTargetAsOfTodayPercentageAchieved</a>

Shows the expected value for percentage achieved against the target goal as of the current date.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Today's Target (Percentage Achieved)</td></tr><tr><td>description</td><td>Shows the expected value for percentage achieved against the target goal as of the current date.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>computedtargetasoftodaypercentageachieved</td></tr></table>

### <a href=#computedTargetAsOfTodayMoney name="computedTargetAsOfTodayMoney">computedTargetAsOfTodayMoney</a>

Shows the expected amount for actual value (money type) against the target goal as of the current date.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Today's Target (Money)</td></tr><tr><td>description</td><td>Shows the expected amount for actual value (money type) against the target goal as of the current date.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>computedtargetasoftodaymoney</td></tr></table>

### <a href=#computedTargetAsOfTodayMoneyBase name="computedTargetAsOfTodayMoneyBase">computedTargetAsOfTodayMoneyBase</a>

Shows the expected amount in base currency for actual value (money type) against the target goal as of the current date.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Today's Target (Money) (Base)</td></tr><tr><td>description</td><td>Shows the expected amount in base currency for actual value (money type) against the target goal as of the current date.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>computedtargetasoftodaymoney_base</td></tr></table>

### <a href=#computedTargetAsOfTodayDecimal name="computedTargetAsOfTodayDecimal">computedTargetAsOfTodayDecimal</a>

Shows the expected amount for actual value (decimal type) against the target goal.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Today's Target (Decimal)</td></tr><tr><td>description</td><td>Shows the expected amount for actual value (decimal type) against the target goal.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>computedtargetasoftodaydecimal</td></tr></table>

### <a href=#computedTargetAsOfTodayInteger name="computedTargetAsOfTodayInteger">computedTargetAsOfTodayInteger</a>

Shows the expected amount for actual value (integer type) against the target goal as of the current date.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Today's Target (Integer)</td></tr><tr><td>description</td><td>Shows the expected amount for actual value (integer type) against the target goal as of the current date.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>computedtargetasoftodayinteger</td></tr></table>

### <a href=#isOverride name="isOverride">isOverride</a>

Indicates whether the values of system rollup fields can be updated.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Override</td></tr><tr><td>description</td><td>Indicates whether the values of system rollup fields can be updated.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isoverride</td></tr></table>

### <a href=#isOverridden name="isOverridden">isOverridden</a>

Select whether the system rollup fields are updated. If set to Yes, the next system rollup will not update the values of the rollup fields with the system calculated values.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Overridden</td></tr><tr><td>description</td><td>Select whether the system rollup fields are updated. If set to Yes, the next system rollup will not update the values of the rollup fields with the system calculated values.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isoverridden</td></tr></table>

### <a href=#entityImageId name="entityImageId">entityImageId</a>

For internal use only.  
First included in: applicationCommon/Goal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Entity Image Id</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entityimageid</td></tr></table>
