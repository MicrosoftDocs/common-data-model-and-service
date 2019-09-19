---
title: ExpenseCategory - Common Data Model | Microsoft Docs
description: Main container that holds expense category information.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Expense Category

Main container that holds expense category information.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/ExpenseCategory.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/ExpenseCategory  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[expenseCategoryId](#expenseCategoryId)|Shows the entity instances.|<a href="ExpenseCategory.md" target="_blank">projectServiceAutomation/ExpenseCategory</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="ExpenseCategory.md" target="_blank">projectServiceAutomation/ExpenseCategory</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="ExpenseCategory.md" target="_blank">projectServiceAutomation/ExpenseCategory</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="ExpenseCategory.md" target="_blank">projectServiceAutomation/ExpenseCategory</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="ExpenseCategory.md" target="_blank">projectServiceAutomation/ExpenseCategory</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="ExpenseCategory.md" target="_blank">projectServiceAutomation/ExpenseCategory</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="ExpenseCategory.md" target="_blank">projectServiceAutomation/ExpenseCategory</a>|
|[organizationId](#organizationId)|Unique identifier for the organization|<a href="ExpenseCategory.md" target="_blank">projectServiceAutomation/ExpenseCategory</a>|
|[stateCode](#stateCode)|Status of the Expense Category|<a href="ExpenseCategory.md" target="_blank">projectServiceAutomation/ExpenseCategory</a>|
|[stateCode_display](#stateCode_display)||<a href="ExpenseCategory.md" target="_blank">projectServiceAutomation/ExpenseCategory</a>|
|[statusCode](#statusCode)|Reason for the status of the Expense Category|<a href="ExpenseCategory.md" target="_blank">projectServiceAutomation/ExpenseCategory</a>|
|[statusCode_display](#statusCode_display)||<a href="ExpenseCategory.md" target="_blank">projectServiceAutomation/ExpenseCategory</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="ExpenseCategory.md" target="_blank">projectServiceAutomation/ExpenseCategory</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="ExpenseCategory.md" target="_blank">projectServiceAutomation/ExpenseCategory</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="ExpenseCategory.md" target="_blank">projectServiceAutomation/ExpenseCategory</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="ExpenseCategory.md" target="_blank">projectServiceAutomation/ExpenseCategory</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="ExpenseCategory.md" target="_blank">projectServiceAutomation/ExpenseCategory</a>|
|[name](#name)|Type the name of the custom entity.|<a href="ExpenseCategory.md" target="_blank">projectServiceAutomation/ExpenseCategory</a>|
|[expenseCategoryuId](#expenseCategoryuId)|Select the Transaction Category associated with Expense Category.|<a href="ExpenseCategory.md" target="_blank">projectServiceAutomation/ExpenseCategory</a>|
|[expenseType](#expenseType)|Enter the type of expense|<a href="ExpenseCategory.md" target="_blank">projectServiceAutomation/ExpenseCategory</a>|
|[expenseType_display](#expenseType_display)||<a href="ExpenseCategory.md" target="_blank">projectServiceAutomation/ExpenseCategory</a>|
|[receiptRequired](#receiptRequired)|Shows whether the expense entry requires a receipt.|<a href="ExpenseCategory.md" target="_blank">projectServiceAutomation/ExpenseCategory</a>|
|[receiptRequired_display](#receiptRequired_display)||<a href="ExpenseCategory.md" target="_blank">projectServiceAutomation/ExpenseCategory</a>|

### <a href=#expenseCategoryId name="expenseCategoryId">expenseCategoryId</a>

Shows the entity instances.  
First included in: projectServiceAutomation/ExpenseCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expense Category</td></tr><tr><td>description</td><td>Shows the entity instances.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_expensecategoryid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/ExpenseCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/ExpenseCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/ExpenseCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/ExpenseCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/ExpenseCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/ExpenseCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for the organization  
First included in: projectServiceAutomation/ExpenseCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier for the organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Expense Category  
First included in: projectServiceAutomation/ExpenseCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Expense Category</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/ExpenseCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Expense Category  
First included in: projectServiceAutomation/ExpenseCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Expense Category</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/ExpenseCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/ExpenseCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: projectServiceAutomation/ExpenseCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/ExpenseCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/ExpenseCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/ExpenseCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

Type the name of the custom entity.  
First included in: projectServiceAutomation/ExpenseCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type the name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_name</td></tr></table>

### <a href=#expenseCategoryuId name="expenseCategoryuId">expenseCategoryuId</a>

Select the Transaction Category associated with Expense Category.  
First included in: projectServiceAutomation/ExpenseCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Category</td></tr><tr><td>description</td><td>Select the Transaction Category associated with Expense Category.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_expensecategoryuid</td></tr></table>

### <a href=#expenseType name="expenseType">expenseType</a>

Enter the type of expense  
First included in: projectServiceAutomation/ExpenseCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expense Type</td></tr><tr><td>description</td><td>Enter the type of expense</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_expensetype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Car Rental</td><td>192350001</td></tr><tr><td>en</td><td>Meal</td><td>192350002</td></tr><tr><td>en</td><td>Airline</td><td>192350003</td></tr><tr><td>en</td><td>Entertainment</td><td>192350004</td></tr><tr><td>en</td><td>Gift</td><td>192350005</td></tr><tr><td>en</td><td>Conference</td><td>192350006</td></tr><tr><td>en</td><td>Miscellaneous</td><td>192350007</td></tr><tr><td>en</td><td>Mileage</td><td>192350008</td></tr><tr><td>en</td><td>Per diem</td><td>192350009</td></tr><tr><td>en</td><td>Hotel</td><td>192350000</td></tr></table></td></tr></table>

### <a href=#expenseType_display name="expenseType_display">expenseType_display</a>

First included in: projectServiceAutomation/ExpenseCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#receiptRequired name="receiptRequired">receiptRequired</a>

Shows whether the expense entry requires a receipt.  
First included in: projectServiceAutomation/ExpenseCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Receipt Required</td></tr><tr><td>description</td><td>Shows whether the expense entry requires a receipt.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_receiptrequired</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Optional</td><td>192350000</td></tr><tr><td>en</td><td>Mandatory</td><td>192350001</td></tr></table></td></tr></table>

### <a href=#receiptRequired_display name="receiptRequired_display">receiptRequired_display</a>

First included in: projectServiceAutomation/ExpenseCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
