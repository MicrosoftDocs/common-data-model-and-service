---
title: Expense - Common Data Model | Microsoft Docs
description: Main container that holds expense information.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Expense

Main container that holds expense information.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/Expense.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/Expense  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[expenseId](#expenseId)|Shows the entity instances.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[stateCode](#stateCode)|Status of the Expense|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[stateCode_display](#stateCode_display)||<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[statusCode](#statusCode)|Reason for the status of the Expense|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[statusCode_display](#statusCode_display)||<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[expensePurpose](#expensePurpose)|Enter the expense's purpose.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[processId](#processId)|Contains the id of the process associated with the entity.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[stageId](#stageId)|Contains the id of the stage where the entity is located.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[traversedPath](#traversedPath)|A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[amount](#amount)|Enter the total amount for expense.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Shows the currency associated with the entity.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[amountBase](#amountBase)|Value of the Amount in base currency.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[bookableResource](#bookableResource)|Shows the bookable resource..|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[expenseCategory](#expenseCategory)|Enter the expense category.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[expenseStatus](#expenseStatus)|Shows the status of the expense entry.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[expenseStatus_display](#expenseStatus_display)||<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[externalComments](#externalComments)|The external comments of the expense entry.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[manager](#manager)|Select the manager of the expense user. This field is used for approval.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[project](#project)|Enter the project.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[quantity](#quantity)|Enter the Quantity|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[resourceOrganizationalUnitId](#resourceOrganizationalUnitId)|Select the organizational unit at the time the entry was registered of the resource who had the expense.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[salesTaxAmount](#salesTaxAmount)|Enter the sales tax amount.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[salesTaxAmountBase](#salesTaxAmountBase)|Value of the Sales tax amount in base currency.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[targetExpenseStatus](#targetExpenseStatus)|Shows the status that the record will be transitioned to asynchronously. Currently, this is only implemented from submission to approved.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[targetExpenseStatus_display](#targetExpenseStatus_display)||<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[transactionDate](#transactionDate)|Enter the date of the expense transaction.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[unit](#unit)|Enter the Unit|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[unitGroup](#unitGroup)|Enter the Unit Group|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[price](#price)|Enter the Price|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[priceBase](#priceBase)|Value of the Price in base currency.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[totalAmount](#totalAmount)|Shows the total amount of the expense entry.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|
|[totalAmountBase](#totalAmountBase)|Enter the value of the total amount in the base currency.|<a href="Expense.md" target="_blank">projectServiceAutomation/Expense</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#expenseId name="expenseId">expenseId</a>

Shows the entity instances.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expense</td></tr><tr><td>description</td><td>Shows the entity instances.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_expenseid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Expense  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Expense</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Expense  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Expense</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Draft</td><td>867380000</td><td>0</td></tr><tr><td>en</td><td>Rejected</td><td>867380001</td><td>0</td></tr><tr><td>en</td><td>Submitted</td><td>867380002</td><td>1</td></tr><tr><td>en</td><td>Approved</td><td>867380003</td><td>1</td></tr><tr><td>en</td><td>Posted</td><td>867380004</td><td>1</td></tr><tr><td>en</td><td>Paid</td><td>867380005</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#expensePurpose name="expensePurpose">expensePurpose</a>

Enter the expense's purpose.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expense Purpose</td></tr><tr><td>description</td><td>Enter the expense's purpose.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_name</td></tr></table>

### <a href=#processId name="processId">processId</a>

Contains the id of the process associated with the entity.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Id</td></tr><tr><td>description</td><td>Contains the id of the process associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Contains the id of the stage where the entity is located.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stage Id</td></tr><tr><td>description</td><td>Contains the id of the stage where the entity is located.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#amount name="amount">amount</a>

Enter the total amount for expense.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount</td></tr><tr><td>description</td><td>Enter the total amount for expense.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_amount</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Shows the currency associated with the entity.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Shows the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#amountBase name="amountBase">amountBase</a>

Value of the Amount in base currency.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount (Base)</td></tr><tr><td>description</td><td>Value of the Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_amount_base</td></tr></table>

### <a href=#bookableResource name="bookableResource">bookableResource</a>

Shows the bookable resource..  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bookable Resource</td></tr><tr><td>description</td><td>Shows the bookable resource..</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_bookableresource</td></tr></table>

### <a href=#expenseCategory name="expenseCategory">expenseCategory</a>

Enter the expense category.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expense Category</td></tr><tr><td>description</td><td>Enter the expense category.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_expensecategory</td></tr></table>

### <a href=#expenseStatus name="expenseStatus">expenseStatus</a>

Shows the status of the expense entry.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expense Status</td></tr><tr><td>description</td><td>Shows the status of the expense entry.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_expensestatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Draft</td><td>192350000</td></tr><tr><td>en</td><td>Submitted</td><td>192350001</td></tr><tr><td>en</td><td>Approved</td><td>192350002</td></tr><tr><td>en</td><td>Rejected</td><td>192350003</td></tr><tr><td>en</td><td>Posted</td><td>192350004</td></tr><tr><td>en</td><td>Paid</td><td>192350005</td></tr><tr><td>en</td><td>Recall Requested</td><td>192350006</td></tr></table></td></tr></table>

### <a href=#expenseStatus_display name="expenseStatus_display">expenseStatus_display</a>

First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#externalComments name="externalComments">externalComments</a>

The external comments of the expense entry.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>External Comments</td></tr><tr><td>description</td><td>The external comments of the expense entry.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_externaldescription</td></tr></table>

### <a href=#manager name="manager">manager</a>

Select the manager of the expense user. This field is used for approval.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Manager</td></tr><tr><td>description</td><td>Select the manager of the expense user. This field is used for approval.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_manager</td></tr></table>

### <a href=#project name="project">project</a>

Enter the project.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project</td></tr><tr><td>description</td><td>Enter the project.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_project</td></tr></table>

### <a href=#quantity name="quantity">quantity</a>

Enter the Quantity  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity</td></tr><tr><td>description</td><td>Enter the Quantity</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_quantity</td></tr></table>

### <a href=#resourceOrganizationalUnitId name="resourceOrganizationalUnitId">resourceOrganizationalUnitId</a>

Select the organizational unit at the time the entry was registered of the resource who had the expense.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resourcing Unit</td></tr><tr><td>description</td><td>Select the organizational unit at the time the entry was registered of the resource who had the expense.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourceorganizationalunitid</td></tr></table>

### <a href=#salesTaxAmount name="salesTaxAmount">salesTaxAmount</a>

Enter the sales tax amount.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax amount</td></tr><tr><td>description</td><td>Enter the sales tax amount.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salestaxamount</td></tr></table>

### <a href=#salesTaxAmountBase name="salesTaxAmountBase">salesTaxAmountBase</a>

Value of the Sales tax amount in base currency.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax amount (Base)</td></tr><tr><td>description</td><td>Value of the Sales tax amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salestaxamount_base</td></tr></table>

### <a href=#targetExpenseStatus name="targetExpenseStatus">targetExpenseStatus</a>

Shows the status that the record will be transitioned to asynchronously. Currently, this is only implemented from submission to approved.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Target Expense Status</td></tr><tr><td>description</td><td>Shows the status that the record will be transitioned to asynchronously. Currently, this is only implemented from submission to approved.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_targetexpensestatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Draft</td><td>192350000</td></tr><tr><td>en</td><td>Submitted</td><td>192350001</td></tr><tr><td>en</td><td>Approved</td><td>192350002</td></tr><tr><td>en</td><td>Rejected</td><td>192350003</td></tr><tr><td>en</td><td>Posted</td><td>192350004</td></tr><tr><td>en</td><td>Paid</td><td>192350005</td></tr><tr><td>en</td><td>Recall Requested</td><td>192350006</td></tr></table></td></tr></table>

### <a href=#targetExpenseStatus_display name="targetExpenseStatus_display">targetExpenseStatus_display</a>

First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionDate name="transactionDate">transactionDate</a>

Enter the date of the expense transaction.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Date</td></tr><tr><td>description</td><td>Enter the date of the expense transaction.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactiondate</td></tr></table>

### <a href=#unit name="unit">unit</a>

Enter the Unit  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit</td></tr><tr><td>description</td><td>Enter the Unit</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_unit</td></tr></table>

### <a href=#unitGroup name="unitGroup">unitGroup</a>

Enter the Unit Group  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit Group</td></tr><tr><td>description</td><td>Enter the Unit Group</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_unitgroup</td></tr></table>

### <a href=#price name="price">price</a>

Enter the Price  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price</td></tr><tr><td>description</td><td>Enter the Price</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_price</td></tr></table>

### <a href=#priceBase name="priceBase">priceBase</a>

Value of the Price in base currency.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price (Base)</td></tr><tr><td>description</td><td>Value of the Price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_price_base</td></tr></table>

### <a href=#totalAmount name="totalAmount">totalAmount</a>

Shows the total amount of the expense entry.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Amount</td></tr><tr><td>description</td><td>Shows the total amount of the expense entry.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_totalamount</td></tr></table>

### <a href=#totalAmountBase name="totalAmountBase">totalAmountBase</a>

Enter the value of the total amount in the base currency.  
First included in: projectServiceAutomation/Expense (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Amount (Base)</td></tr><tr><td>description</td><td>Enter the value of the total amount in the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_totalamount_base</td></tr></table>
