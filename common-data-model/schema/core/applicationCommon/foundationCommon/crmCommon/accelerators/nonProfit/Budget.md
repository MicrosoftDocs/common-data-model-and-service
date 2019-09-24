---
title: Budget - Common Data Model | Microsoft Docs
description: This describes the Budget entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Budget

A Budget represents the amount of funds that can be awarded for a particular delivery framework (i.e Program, Project, Initiative, Activity) for a defined period of time (i.e. fiscal year).  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/Budget.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/nonProfit/Budget  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[budgetId](#budgetId)|Unique identifier for entity instances|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[stateCode](#stateCode)|Status of the Budget|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[stateCode_display](#stateCode_display)||<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[statusCode](#statusCode)|Reason for the status of the Budget|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[statusCode_display](#statusCode_display)||<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[name](#name)||<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[budgetName](#budgetName)|Name of the Budget.|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[deliveryFrameworkId](#deliveryFrameworkId)||<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[description](#description)|Description of the Budget.|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[endDate](#endDate)|End date of the objective|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[objectiveId](#objectiveId)|Objective|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[startDate](#startDate)|Start date off the objective|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[totalBudget](#totalBudget)|Indicates the total budget amount.|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[totalbudgetBase](#totalbudgetBase)|Value of the Total Budget in base currency.|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[accountId](#accountId)|Unique identifier for Account associated with Budget.|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[budgetIdentifier](#budgetIdentifier)|An identifier for the budget-item.|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[budgetStatus](#budgetStatus)|Denotes if the described budget is binding|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[budgetStatus_display](#budgetStatus_display)||<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[budgetType](#budgetType)||<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[msiatiBudgetType_display](#msiatiBudgetType_display)||<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[currencyValueDate](#currencyValueDate)|Date of the currency value|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[parentBudgetId](#parentBudgetId)|Unique identifier for Budget associated with Budget.|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[percentage](#percentage)|Percentage of each budget.|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[recipientCountryId](#recipientCountryId)|Unique identifier for Non Embedded Codelist associated with Budget.|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[recipientOrganization](#recipientOrganization)|Unique identifier for Account associated with Budget.|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[recipientRegionId](#recipientRegionId)|Unique identifier for Non Embedded Codelist associated with Budget.|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[relatedTo](#relatedTo)|Defines the entity to which the budget is related (e.g. Delivery Framework or Account).|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[relatedTo_display](#relatedTo_display)||<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[type](#type)|OECD DAC classification used to determine the character of resource flows (bilateral or multilateral)|<a href="Budget.md" target="_blank">nonProfit/Budget</a>|
|[msiatiType_display](#msiatiType_display)||<a href="Budget.md" target="_blank">nonProfit/Budget</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#budgetId name="budgetId">budgetId</a>

Unique identifier for entity instances  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msnfp_budgetid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Budget  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Budget</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Budget  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Budget</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_name</td></tr></table>

### <a href=#budgetName name="budgetName">budgetName</a>

Name of the Budget.  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget Name</td></tr><tr><td>description</td><td>Name of the Budget.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_budgetname</td></tr></table>

### <a href=#deliveryFrameworkId name="deliveryFrameworkId">deliveryFrameworkId</a>

First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery Framework</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_deliveryframeworkid</td></tr></table>

### <a href=#description name="description">description</a>

Description of the Budget.  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the Budget.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_description</td></tr></table>

### <a href=#endDate name="endDate">endDate</a>

End date of the objective  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End Date</td></tr><tr><td>description</td><td>End date of the objective</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_enddate</td></tr></table>

### <a href=#objectiveId name="objectiveId">objectiveId</a>

Objective  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Objective</td></tr><tr><td>description</td><td>Objective</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_objectiveid</td></tr></table>

### <a href=#startDate name="startDate">startDate</a>

Start date off the objective  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date</td></tr><tr><td>description</td><td>Start date off the objective</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_startdate</td></tr></table>

### <a href=#totalBudget name="totalBudget">totalBudget</a>

Indicates the total budget amount.  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Budget</td></tr><tr><td>description</td><td>Indicates the total budget amount.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_totalbudget</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#totalbudgetBase name="totalbudgetBase">totalbudgetBase</a>

Value of the Total Budget in base currency.  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Budget (Base)</td></tr><tr><td>description</td><td>Value of the Total Budget in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_totalbudget_base</td></tr></table>

### <a href=#accountId name="accountId">accountId</a>

Unique identifier for Account associated with Budget.  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account</td></tr><tr><td>description</td><td>Unique identifier for Account associated with Budget.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_accountid</td></tr></table>

### <a href=#budgetIdentifier name="budgetIdentifier">budgetIdentifier</a>

An identifier for the budget-item.  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget Identifier</td></tr><tr><td>description</td><td>An identifier for the budget-item.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_budgetidentifierid</td></tr></table>

### <a href=#budgetStatus name="budgetStatus">budgetStatus</a>

Denotes if the described budget is binding  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget Status</td></tr><tr><td>description</td><td>Denotes if the described budget is binding</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_budgetstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Indicative</td><td>453490001</td></tr><tr><td>en</td><td>Committed</td><td>453490002</td></tr></table></td></tr></table>

### <a href=#budgetStatus_display name="budgetStatus_display">budgetStatus_display</a>

First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#budgetType name="budgetType">budgetType</a>

First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Budget Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_budgettype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Total Budget</td><td>453490000</td></tr><tr><td>en</td><td>Recipient Org Budget</td><td>453490001</td></tr><tr><td>en</td><td>Recipient Country Budget</td><td>453490002</td></tr><tr><td>en</td><td>Recipient Region Budget</td><td>453490003</td></tr></table></td></tr></table>

### <a href=#msiatiBudgetType_display name="msiatiBudgetType_display">msiatiBudgetType_display</a>

First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#currencyValueDate name="currencyValueDate">currencyValueDate</a>

Date of the currency value  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency Value Date</td></tr><tr><td>description</td><td>Date of the currency value</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_currencyvaluedate</td></tr></table>

### <a href=#parentBudgetId name="parentBudgetId">parentBudgetId</a>

Unique identifier for Budget associated with Budget.  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent Budget</td></tr><tr><td>description</td><td>Unique identifier for Budget associated with Budget.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_parentbudgetid</td></tr></table>

### <a href=#percentage name="percentage">percentage</a>

Percentage of each budget.  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Percentage</td></tr><tr><td>description</td><td>Percentage of each budget.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_percentage</td></tr></table>

### <a href=#recipientCountryId name="recipientCountryId">recipientCountryId</a>

Unique identifier for Non Embedded Codelist associated with Budget.  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Country</td></tr><tr><td>description</td><td>Unique identifier for Non Embedded Codelist associated with Budget.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientcountryid</td></tr></table>

### <a href=#recipientOrganization name="recipientOrganization">recipientOrganization</a>

Unique identifier for Account associated with Budget.  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Organization</td></tr><tr><td>description</td><td>Unique identifier for Account associated with Budget.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientorganizationid</td></tr></table>

### <a href=#recipientRegionId name="recipientRegionId">recipientRegionId</a>

Unique identifier for Non Embedded Codelist associated with Budget.  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Region</td></tr><tr><td>description</td><td>Unique identifier for Non Embedded Codelist associated with Budget.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientregionid</td></tr></table>

### <a href=#relatedTo name="relatedTo">relatedTo</a>

Defines the entity to which the budget is related (e.g. Delivery Framework or Account).  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Related To</td></tr><tr><td>description</td><td>Defines the entity to which the budget is related (e.g. Delivery Framework or Account).</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_relatedto</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Account</td><td>453490000</td></tr><tr><td>en</td><td>Delivery Framework</td><td>453490001</td></tr></table></td></tr></table>

### <a href=#relatedTo_display name="relatedTo_display">relatedTo_display</a>

First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#type name="type">type</a>

OECD DAC classification used to determine the character of resource flows (bilateral or multilateral)  
First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type</td></tr><tr><td>description</td><td>OECD DAC classification used to determine the character of resource flows (bilateral or multilateral)</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_type</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Original</td><td>453490001</td></tr><tr><td>en</td><td>Revised</td><td>453490002</td></tr></table></td></tr></table>

### <a href=#msiatiType_display name="msiatiType_display">msiatiType_display</a>

First included in: nonProfit/Budget (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
