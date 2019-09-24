---
title: InvoiceFrequency - Common Data Model | Microsoft Docs
description: Setup entity for invoice schedules.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Invoice Frequency

Setup entity for invoice schedules.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/InvoiceFrequency.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/InvoiceFrequency  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[invoiceFrequencyId](#invoiceFrequencyId)|Shows the entity instances.|<a href="InvoiceFrequency.md" target="_blank">projectServiceAutomation/InvoiceFrequency</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="InvoiceFrequency.md" target="_blank">projectServiceAutomation/InvoiceFrequency</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="InvoiceFrequency.md" target="_blank">projectServiceAutomation/InvoiceFrequency</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="InvoiceFrequency.md" target="_blank">projectServiceAutomation/InvoiceFrequency</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="InvoiceFrequency.md" target="_blank">projectServiceAutomation/InvoiceFrequency</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="InvoiceFrequency.md" target="_blank">projectServiceAutomation/InvoiceFrequency</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="InvoiceFrequency.md" target="_blank">projectServiceAutomation/InvoiceFrequency</a>|
|[organizationId](#organizationId)|Unique identifier for the organization|<a href="InvoiceFrequency.md" target="_blank">projectServiceAutomation/InvoiceFrequency</a>|
|[stateCode](#stateCode)|Status of the Invoice Frequency|<a href="InvoiceFrequency.md" target="_blank">projectServiceAutomation/InvoiceFrequency</a>|
|[stateCode_display](#stateCode_display)||<a href="InvoiceFrequency.md" target="_blank">projectServiceAutomation/InvoiceFrequency</a>|
|[statusCode](#statusCode)|Reason for the status of the Invoice Frequency|<a href="InvoiceFrequency.md" target="_blank">projectServiceAutomation/InvoiceFrequency</a>|
|[statusCode_display](#statusCode_display)||<a href="InvoiceFrequency.md" target="_blank">projectServiceAutomation/InvoiceFrequency</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="InvoiceFrequency.md" target="_blank">projectServiceAutomation/InvoiceFrequency</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="InvoiceFrequency.md" target="_blank">projectServiceAutomation/InvoiceFrequency</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="InvoiceFrequency.md" target="_blank">projectServiceAutomation/InvoiceFrequency</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="InvoiceFrequency.md" target="_blank">projectServiceAutomation/InvoiceFrequency</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="InvoiceFrequency.md" target="_blank">projectServiceAutomation/InvoiceFrequency</a>|
|[name](#name)|Type the name of the custom entity.|<a href="InvoiceFrequency.md" target="_blank">projectServiceAutomation/InvoiceFrequency</a>|
|[daysOfRun](#daysOfRun)|Describes how the run days per period interval are setup. As weekdays (Monday, Tuesday...) or day of period (1st, 2nd…) |<a href="InvoiceFrequency.md" target="_blank">projectServiceAutomation/InvoiceFrequency</a>|
|[daysOfRun_display](#daysOfRun_display)||<a href="InvoiceFrequency.md" target="_blank">projectServiceAutomation/InvoiceFrequency</a>|
|[period](#period)|Select the period used for the setup of invoice frequency: supported values are Monthly, Weekly or Bi Weekly.|<a href="InvoiceFrequency.md" target="_blank">projectServiceAutomation/InvoiceFrequency</a>|
|[period_display](#period_display)||<a href="InvoiceFrequency.md" target="_blank">projectServiceAutomation/InvoiceFrequency</a>|
|[runsPerMonth](#runsPerMonth)|Select the number of times invoicing should run in a period.|<a href="InvoiceFrequency.md" target="_blank">projectServiceAutomation/InvoiceFrequency</a>|
|[runsPerMonth_display](#runsPerMonth_display)||<a href="InvoiceFrequency.md" target="_blank">projectServiceAutomation/InvoiceFrequency</a>|

### <a href=#invoiceFrequencyId name="invoiceFrequencyId">invoiceFrequencyId</a>

Shows the entity instances.  
First included in: projectServiceAutomation/InvoiceFrequency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice Frequency</td></tr><tr><td>description</td><td>Shows the entity instances.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_invoicefrequencyid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/InvoiceFrequency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/InvoiceFrequency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/InvoiceFrequency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/InvoiceFrequency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/InvoiceFrequency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/InvoiceFrequency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for the organization  
First included in: projectServiceAutomation/InvoiceFrequency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier for the organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Invoice Frequency  
First included in: projectServiceAutomation/InvoiceFrequency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Invoice Frequency</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/InvoiceFrequency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Invoice Frequency  
First included in: projectServiceAutomation/InvoiceFrequency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Invoice Frequency</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/InvoiceFrequency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/InvoiceFrequency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: projectServiceAutomation/InvoiceFrequency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/InvoiceFrequency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/InvoiceFrequency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/InvoiceFrequency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

Type the name of the custom entity.  
First included in: projectServiceAutomation/InvoiceFrequency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type the name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_name</td></tr></table>

### <a href=#daysOfRun name="daysOfRun">daysOfRun</a>

Describes how the run days per period interval are setup. As weekdays (Monday, Tuesday...) or day of period (1st, 2nd…)   
First included in: projectServiceAutomation/InvoiceFrequency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Setup of runs</td></tr><tr><td>description</td><td>Describes how the run days per period interval are setup. As weekdays (Monday, Tuesday...) or day of period (1st, 2nd…) </td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_daysofrun</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Day of period</td><td>192350000</td></tr><tr><td>en</td><td>Weekday of period</td><td>192350001</td></tr></table></td></tr></table>

### <a href=#daysOfRun_display name="daysOfRun_display">daysOfRun_display</a>

First included in: projectServiceAutomation/InvoiceFrequency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#period name="period">period</a>

Select the period used for the setup of invoice frequency: supported values are Monthly, Weekly or Bi Weekly.  
First included in: projectServiceAutomation/InvoiceFrequency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Period</td></tr><tr><td>description</td><td>Select the period used for the setup of invoice frequency: supported values are Monthly, Weekly or Bi Weekly.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_period</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Weekly</td><td>192350000</td></tr><tr><td>en</td><td>Monthly</td><td>192350001</td></tr><tr><td>en</td><td>Biweekly</td><td>192350002</td></tr></table></td></tr></table>

### <a href=#period_display name="period_display">period_display</a>

First included in: projectServiceAutomation/InvoiceFrequency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#runsPerMonth name="runsPerMonth">runsPerMonth</a>

Select the number of times invoicing should run in a period.  
First included in: projectServiceAutomation/InvoiceFrequency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Runs per period</td></tr><tr><td>description</td><td>Select the number of times invoicing should run in a period.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_runspermonth</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>1</td><td>1</td></tr><tr><td>en</td><td>2</td><td>2</td></tr><tr><td>en</td><td>3</td><td>3</td></tr><tr><td>en</td><td>4</td><td>4</td></tr></table></td></tr></table>

### <a href=#runsPerMonth_display name="runsPerMonth_display">runsPerMonth_display</a>

First included in: projectServiceAutomation/InvoiceFrequency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
