---
title: ContractLineInvoiceSchedule - Common Data Model | Microsoft Docs
description: This describes the ContractLineInvoiceSchedule entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Project Contract Line Invoice Schedule

List of dates that shows when invoicing for this customer should be run. This list is used by the invoice creation job.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/ContractLineInvoiceSchedule.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/ContractLineInvoiceSchedule  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[contractLineInvoiceScheduleId](#contractLineInvoiceScheduleId)|Unique identifier for entity instances|<a href="ContractLineInvoiceSchedule.md" target="_blank">projectServiceAutomation/ContractLineInvoiceSchedule</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="ContractLineInvoiceSchedule.md" target="_blank">projectServiceAutomation/ContractLineInvoiceSchedule</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="ContractLineInvoiceSchedule.md" target="_blank">projectServiceAutomation/ContractLineInvoiceSchedule</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="ContractLineInvoiceSchedule.md" target="_blank">projectServiceAutomation/ContractLineInvoiceSchedule</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="ContractLineInvoiceSchedule.md" target="_blank">projectServiceAutomation/ContractLineInvoiceSchedule</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="ContractLineInvoiceSchedule.md" target="_blank">projectServiceAutomation/ContractLineInvoiceSchedule</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="ContractLineInvoiceSchedule.md" target="_blank">projectServiceAutomation/ContractLineInvoiceSchedule</a>|
|[organizationId](#organizationId)|Unique identifier for the organization|<a href="ContractLineInvoiceSchedule.md" target="_blank">projectServiceAutomation/ContractLineInvoiceSchedule</a>|
|[stateCode](#stateCode)|Status of the project contract line invoice schedule|<a href="ContractLineInvoiceSchedule.md" target="_blank">projectServiceAutomation/ContractLineInvoiceSchedule</a>|
|[stateCode_display](#stateCode_display)||<a href="ContractLineInvoiceSchedule.md" target="_blank">projectServiceAutomation/ContractLineInvoiceSchedule</a>|
|[statusCode](#statusCode)|Reason for the status of the project contract line invoice schedule|<a href="ContractLineInvoiceSchedule.md" target="_blank">projectServiceAutomation/ContractLineInvoiceSchedule</a>|
|[statusCode_display](#statusCode_display)||<a href="ContractLineInvoiceSchedule.md" target="_blank">projectServiceAutomation/ContractLineInvoiceSchedule</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="ContractLineInvoiceSchedule.md" target="_blank">projectServiceAutomation/ContractLineInvoiceSchedule</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="ContractLineInvoiceSchedule.md" target="_blank">projectServiceAutomation/ContractLineInvoiceSchedule</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="ContractLineInvoiceSchedule.md" target="_blank">projectServiceAutomation/ContractLineInvoiceSchedule</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="ContractLineInvoiceSchedule.md" target="_blank">projectServiceAutomation/ContractLineInvoiceSchedule</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="ContractLineInvoiceSchedule.md" target="_blank">projectServiceAutomation/ContractLineInvoiceSchedule</a>|
|[name](#name)|Type the name of the custom entity.|<a href="ContractLineInvoiceSchedule.md" target="_blank">projectServiceAutomation/ContractLineInvoiceSchedule</a>|
|[contractLine](#contractLine)|(Deprecated) Shows the associated project contract line for this invoice schedule.|<a href="ContractLineInvoiceSchedule.md" target="_blank">projectServiceAutomation/ContractLineInvoiceSchedule</a>|
|[contractLineId](#contractLineId)|Unique identifier for Project Contract Line associated with Project Contract Line Invoice Schedule.|<a href="ContractLineInvoiceSchedule.md" target="_blank">projectServiceAutomation/ContractLineInvoiceSchedule</a>|
|[contractLineScheduleOfValue](#contractLineScheduleOfValue)|Select the billing milestone for a project contract line.|<a href="ContractLineInvoiceSchedule.md" target="_blank">projectServiceAutomation/ContractLineInvoiceSchedule</a>|
|[invoice](#invoice)|Select the Invoice associated with Project contract line invoice schedule.|<a href="ContractLineInvoiceSchedule.md" target="_blank">projectServiceAutomation/ContractLineInvoiceSchedule</a>|
|[invoiceRunDate](#invoiceRunDate)|Enter the date on which invoice should get created|<a href="ContractLineInvoiceSchedule.md" target="_blank">projectServiceAutomation/ContractLineInvoiceSchedule</a>|
|[invoiceRunStatus](#invoiceRunStatus)|Select the invoice status, for example, Not Run, Run Successful, or Run Failed.|<a href="ContractLineInvoiceSchedule.md" target="_blank">projectServiceAutomation/ContractLineInvoiceSchedule</a>|
|[invoiceRunStatus_display](#invoiceRunStatus_display)||<a href="ContractLineInvoiceSchedule.md" target="_blank">projectServiceAutomation/ContractLineInvoiceSchedule</a>|
|[transactionCutOffDate](#transactionCutOffDate)|Enter the date before or on which the transaction will be picked for invoicing by the invoice creation job.|<a href="ContractLineInvoiceSchedule.md" target="_blank">projectServiceAutomation/ContractLineInvoiceSchedule</a>|

### <a href=#contractLineInvoiceScheduleId name="contractLineInvoiceScheduleId">contractLineInvoiceScheduleId</a>

Unique identifier for entity instances  
First included in: projectServiceAutomation/ContractLineInvoiceSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Contract Line Invoice Schedule</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_contractlineinvoicescheduleid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/ContractLineInvoiceSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/ContractLineInvoiceSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/ContractLineInvoiceSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/ContractLineInvoiceSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/ContractLineInvoiceSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/ContractLineInvoiceSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for the organization  
First included in: projectServiceAutomation/ContractLineInvoiceSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier for the organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the project contract line invoice schedule  
First included in: projectServiceAutomation/ContractLineInvoiceSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the project contract line invoice schedule</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/ContractLineInvoiceSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the project contract line invoice schedule  
First included in: projectServiceAutomation/ContractLineInvoiceSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the project contract line invoice schedule</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/ContractLineInvoiceSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/ContractLineInvoiceSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: projectServiceAutomation/ContractLineInvoiceSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/ContractLineInvoiceSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/ContractLineInvoiceSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/ContractLineInvoiceSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

Type the name of the custom entity.  
First included in: projectServiceAutomation/ContractLineInvoiceSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type the name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_name</td></tr></table>

### <a href=#contractLine name="contractLine">contractLine</a>

(Deprecated) Shows the associated project contract line for this invoice schedule.  
First included in: projectServiceAutomation/ContractLineInvoiceSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>(Deprecated) Project Contract Line</td></tr><tr><td>description</td><td>(Deprecated) Shows the associated project contract line for this invoice schedule.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_contractline</td></tr></table>

### <a href=#contractLineId name="contractLineId">contractLineId</a>

Unique identifier for Project Contract Line associated with Project Contract Line Invoice Schedule.  
First included in: projectServiceAutomation/ContractLineInvoiceSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Contract Line</td></tr><tr><td>description</td><td>Unique identifier for Project Contract Line associated with Project Contract Line Invoice Schedule.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_contractlineid</td></tr></table>

### <a href=#contractLineScheduleOfValue name="contractLineScheduleOfValue">contractLineScheduleOfValue</a>

Select the billing milestone for a project contract line.  
First included in: projectServiceAutomation/ContractLineInvoiceSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Contract Line Milestone</td></tr><tr><td>description</td><td>Select the billing milestone for a project contract line.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_contractlinescheduleofvalue</td></tr></table>

### <a href=#invoice name="invoice">invoice</a>

Select the Invoice associated with Project contract line invoice schedule.  
First included in: projectServiceAutomation/ContractLineInvoiceSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice</td></tr><tr><td>description</td><td>Select the Invoice associated with Project contract line invoice schedule.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_invoice</td></tr></table>

### <a href=#invoiceRunDate name="invoiceRunDate">invoiceRunDate</a>

Enter the date on which invoice should get created  
First included in: projectServiceAutomation/ContractLineInvoiceSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice Run Date</td></tr><tr><td>description</td><td>Enter the date on which invoice should get created</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_invoicerundate</td></tr></table>

### <a href=#invoiceRunStatus name="invoiceRunStatus">invoiceRunStatus</a>

Select the invoice status, for example, Not Run, Run Successful, or Run Failed.  
First included in: projectServiceAutomation/ContractLineInvoiceSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice Status</td></tr><tr><td>description</td><td>Select the invoice status, for example, Not Run, Run Successful, or Run Failed.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_invoicerunstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not Run</td><td>192350000</td></tr><tr><td>en</td><td>Run Successful</td><td>192350001</td></tr><tr><td>en</td><td>Run Failed</td><td>192350002</td></tr></table></td></tr></table>

### <a href=#invoiceRunStatus_display name="invoiceRunStatus_display">invoiceRunStatus_display</a>

First included in: projectServiceAutomation/ContractLineInvoiceSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionCutOffDate name="transactionCutOffDate">transactionCutOffDate</a>

Enter the date before or on which the transaction will be picked for invoicing by the invoice creation job.  
First included in: projectServiceAutomation/ContractLineInvoiceSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Cut Off Date</td></tr><tr><td>description</td><td>Enter the date before or on which the transaction will be picked for invoicing by the invoice creation job.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactioncutoffdate</td></tr></table>
