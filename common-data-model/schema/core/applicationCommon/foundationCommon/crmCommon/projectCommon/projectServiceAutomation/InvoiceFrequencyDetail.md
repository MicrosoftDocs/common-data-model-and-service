---
title: InvoiceFrequencyDetail - Common Data Model | Microsoft Docs
description: List of days expressed as dates or day of week for a specific invoice schedule template.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Invoice Frequency Detail

List of days expressed as dates or day of week for a specific invoice schedule template.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/InvoiceFrequencyDetail.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/InvoiceFrequencyDetail  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[invoiceFrequencyDetailId](#invoiceFrequencyDetailId)|Unique identifier for entity instances|<a href="InvoiceFrequencyDetail.md" target="_blank">projectServiceAutomation/InvoiceFrequencyDetail</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="InvoiceFrequencyDetail.md" target="_blank">projectServiceAutomation/InvoiceFrequencyDetail</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="InvoiceFrequencyDetail.md" target="_blank">projectServiceAutomation/InvoiceFrequencyDetail</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="InvoiceFrequencyDetail.md" target="_blank">projectServiceAutomation/InvoiceFrequencyDetail</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="InvoiceFrequencyDetail.md" target="_blank">projectServiceAutomation/InvoiceFrequencyDetail</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="InvoiceFrequencyDetail.md" target="_blank">projectServiceAutomation/InvoiceFrequencyDetail</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="InvoiceFrequencyDetail.md" target="_blank">projectServiceAutomation/InvoiceFrequencyDetail</a>|
|[organizationId](#organizationId)|Unique identifier for the organization|<a href="InvoiceFrequencyDetail.md" target="_blank">projectServiceAutomation/InvoiceFrequencyDetail</a>|
|[stateCode](#stateCode)|Status of the Invoice Frequency Detail|<a href="InvoiceFrequencyDetail.md" target="_blank">projectServiceAutomation/InvoiceFrequencyDetail</a>|
|[stateCode_display](#stateCode_display)||<a href="InvoiceFrequencyDetail.md" target="_blank">projectServiceAutomation/InvoiceFrequencyDetail</a>|
|[statusCode](#statusCode)|Reason for the status of the Invoice Frequency Detail|<a href="InvoiceFrequencyDetail.md" target="_blank">projectServiceAutomation/InvoiceFrequencyDetail</a>|
|[statusCode_display](#statusCode_display)||<a href="InvoiceFrequencyDetail.md" target="_blank">projectServiceAutomation/InvoiceFrequencyDetail</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="InvoiceFrequencyDetail.md" target="_blank">projectServiceAutomation/InvoiceFrequencyDetail</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="InvoiceFrequencyDetail.md" target="_blank">projectServiceAutomation/InvoiceFrequencyDetail</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="InvoiceFrequencyDetail.md" target="_blank">projectServiceAutomation/InvoiceFrequencyDetail</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="InvoiceFrequencyDetail.md" target="_blank">projectServiceAutomation/InvoiceFrequencyDetail</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="InvoiceFrequencyDetail.md" target="_blank">projectServiceAutomation/InvoiceFrequencyDetail</a>|
|[name](#name)|Type the name of the custom entity.|<a href="InvoiceFrequencyDetail.md" target="_blank">projectServiceAutomation/InvoiceFrequencyDetail</a>|
|[dayOfMonth](#dayOfMonth)|Specify the day(s) of the month on which invoicing should run|<a href="InvoiceFrequencyDetail.md" target="_blank">projectServiceAutomation/InvoiceFrequencyDetail</a>|
|[dayOfMonth_display](#dayOfMonth_display)||<a href="InvoiceFrequencyDetail.md" target="_blank">projectServiceAutomation/InvoiceFrequencyDetail</a>|
|[invoiceFrequency](#invoiceFrequency)|Select the invoice frequency.|<a href="InvoiceFrequencyDetail.md" target="_blank">projectServiceAutomation/InvoiceFrequencyDetail</a>|
|[occurrenceOfWeekday](#occurrenceOfWeekday)|Specifies which occurrence of a weekday the invoicing job should run if there are multiple occurrences of a weekday in the selected period|<a href="InvoiceFrequencyDetail.md" target="_blank">projectServiceAutomation/InvoiceFrequencyDetail</a>|
|[occurrenceOfWeekday_display](#occurrenceOfWeekday_display)||<a href="InvoiceFrequencyDetail.md" target="_blank">projectServiceAutomation/InvoiceFrequencyDetail</a>|
|[weekday](#weekday)|Select the weekday of the invoicing job run.|<a href="InvoiceFrequencyDetail.md" target="_blank">projectServiceAutomation/InvoiceFrequencyDetail</a>|
|[weekday_display](#weekday_display)||<a href="InvoiceFrequencyDetail.md" target="_blank">projectServiceAutomation/InvoiceFrequencyDetail</a>|

### <a href=#invoiceFrequencyDetailId name="invoiceFrequencyDetailId">invoiceFrequencyDetailId</a>

Unique identifier for entity instances  
First included in: projectServiceAutomation/InvoiceFrequencyDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice Frequency Detail</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_invoicefrequencydetailid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/InvoiceFrequencyDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/InvoiceFrequencyDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/InvoiceFrequencyDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/InvoiceFrequencyDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/InvoiceFrequencyDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/InvoiceFrequencyDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for the organization  
First included in: projectServiceAutomation/InvoiceFrequencyDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier for the organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Invoice Frequency Detail  
First included in: projectServiceAutomation/InvoiceFrequencyDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Invoice Frequency Detail</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/InvoiceFrequencyDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Invoice Frequency Detail  
First included in: projectServiceAutomation/InvoiceFrequencyDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Invoice Frequency Detail</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/InvoiceFrequencyDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/InvoiceFrequencyDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: projectServiceAutomation/InvoiceFrequencyDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/InvoiceFrequencyDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/InvoiceFrequencyDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/InvoiceFrequencyDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

Type the name of the custom entity.  
First included in: projectServiceAutomation/InvoiceFrequencyDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type the name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_name</td></tr></table>

### <a href=#dayOfMonth name="dayOfMonth">dayOfMonth</a>

Specify the day(s) of the month on which invoicing should run  
First included in: projectServiceAutomation/InvoiceFrequencyDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Day of month</td></tr><tr><td>description</td><td>Specify the day(s) of the month on which invoicing should run</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_dayofmonth</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>1</td><td>192350001</td></tr><tr><td>en</td><td>2</td><td>192350002</td></tr><tr><td>en</td><td>3</td><td>192350003</td></tr><tr><td>en</td><td>4</td><td>192350004</td></tr><tr><td>en</td><td>5</td><td>192350005</td></tr><tr><td>en</td><td>6</td><td>192350006</td></tr><tr><td>en</td><td>7</td><td>192350007</td></tr><tr><td>en</td><td>8</td><td>192350008</td></tr><tr><td>en</td><td>9</td><td>192350009</td></tr><tr><td>en</td><td>10</td><td>192350010</td></tr><tr><td>en</td><td>11</td><td>192350011</td></tr><tr><td>en</td><td>12</td><td>192350012</td></tr><tr><td>en</td><td>13</td><td>192350013</td></tr><tr><td>en</td><td>14</td><td>192350014</td></tr><tr><td>en</td><td>15</td><td>192350015</td></tr><tr><td>en</td><td>16</td><td>192350016</td></tr><tr><td>en</td><td>17</td><td>192350017</td></tr><tr><td>en</td><td>18</td><td>192350018</td></tr><tr><td>en</td><td>19</td><td>192350019</td></tr><tr><td>en</td><td>20</td><td>192350020</td></tr><tr><td>en</td><td>21</td><td>192350021</td></tr><tr><td>en</td><td>22</td><td>192350022</td></tr><tr><td>en</td><td>23</td><td>192350023</td></tr><tr><td>en</td><td>24</td><td>192350024</td></tr><tr><td>en</td><td>25</td><td>192350025</td></tr><tr><td>en</td><td>26</td><td>192350026</td></tr><tr><td>en</td><td>27</td><td>192350027</td></tr><tr><td>en</td><td>28</td><td>192350028</td></tr><tr><td>en</td><td>29</td><td>192350029</td></tr><tr><td>en</td><td>30</td><td>192350030</td></tr><tr><td>en</td><td>31</td><td>192350031</td></tr></table></td></tr></table>

### <a href=#dayOfMonth_display name="dayOfMonth_display">dayOfMonth_display</a>

First included in: projectServiceAutomation/InvoiceFrequencyDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#invoiceFrequency name="invoiceFrequency">invoiceFrequency</a>

Select the invoice frequency.  
First included in: projectServiceAutomation/InvoiceFrequencyDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice Frequency</td></tr><tr><td>description</td><td>Select the invoice frequency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_invoicefrequency</td></tr></table>

### <a href=#occurrenceOfWeekday name="occurrenceOfWeekday">occurrenceOfWeekday</a>

Specifies which occurrence of a weekday the invoicing job should run if there are multiple occurrences of a weekday in the selected period  
First included in: projectServiceAutomation/InvoiceFrequencyDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Occurrence of weekday</td></tr><tr><td>description</td><td>Specifies which occurrence of a weekday the invoicing job should run if there are multiple occurrences of a weekday in the selected period</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_occurrenceofweekday</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>First</td><td>192350000</td></tr><tr><td>en</td><td>Second</td><td>192350001</td></tr><tr><td>en</td><td>Third</td><td>192350002</td></tr><tr><td>en</td><td>Fourth</td><td>192350003</td></tr><tr><td>en</td><td>Last</td><td>192350004</td></tr></table></td></tr></table>

### <a href=#occurrenceOfWeekday_display name="occurrenceOfWeekday_display">occurrenceOfWeekday_display</a>

First included in: projectServiceAutomation/InvoiceFrequencyDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#weekday name="weekday">weekday</a>

Select the weekday of the invoicing job run.  
First included in: projectServiceAutomation/InvoiceFrequencyDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Weekday</td></tr><tr><td>description</td><td>Select the weekday of the invoicing job run.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_weekday</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Sunday</td><td>192350000</td></tr><tr><td>en</td><td>Monday</td><td>192350001</td></tr><tr><td>en</td><td>Tuesday</td><td>192350002</td></tr><tr><td>en</td><td>Wednesday</td><td>192350003</td></tr><tr><td>en</td><td>Thursday</td><td>192350004</td></tr><tr><td>en</td><td>Friday</td><td>192350005</td></tr><tr><td>en</td><td>Saturday</td><td>192350006</td></tr></table></td></tr></table>

### <a href=#weekday_display name="weekday_display">weekday_display</a>

First included in: projectServiceAutomation/InvoiceFrequencyDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
