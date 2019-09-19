---
title: ProjectApproval - Common Data Model | Microsoft Docs
description: This describes the ProjectApproval entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Project Approval

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/ProjectApproval.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/ProjectApproval  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[ownerId](#ownerId)|Owner Id|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[projectApprovalId](#projectApprovalId)|Unique identifier for entity instances|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[stateCode](#stateCode)|Status of the ApprovalsTable|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[stateCode_display](#stateCode_display)||<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[statusCode](#statusCode)|Reason for the status of the ApprovalsTable|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[statusCode_display](#statusCode_display)||<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[name](#name)|The name of the custom entity.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[approvedBy](#approvedBy)|Shows the name of the approver.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[approvedOn](#approvedOn)|Shows the date of the approval.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[billingType](#billingType)|Billing type for the project approval line.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[billingType_display](#billingType_display)||<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[bookableResource](#bookableResource)|Shows the resource that the entry is submitted for.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[costPrice](#costPrice)|Shows the cost price of the transaction.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Shows the currency associated with the entity.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[costPriceBase](#costPriceBase)|Value of the Cost Price in base currency.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[costQuantity](#costQuantity)|Shows the hours submitted for the transaction.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[date](#date)|Shows the date of the transaction.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[entryType](#entryType)|Shows the entry type of the transaction.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[entryType_display](#entryType_display)||<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[expenseCategory](#expenseCategory)|Shows the expense category of the transaction.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[expenseEntry](#expenseEntry)|Expense Entry Id.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[externalComments](#externalComments)|Shows the external comments entered for the transaction.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[hasReceipt](#hasReceipt)|Shows whether the transaction has a receipt.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[internalComments](#internalComments)|Shows the internal comments entered for the transaction.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[journalTransaction](#journalTransaction)|Shows whether the transaction was entered by a journal.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[manager](#manager)|Shows the manager of the person who submitted the transaction.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[project](#project)|Shows the project for the transaction.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[projectTask](#projectTask)|Shows the project task for the transaction.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[recordStage](#recordStage)|Shows the stage of the record.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[recordStage_display](#recordStage_display)||<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[referenceExpenseId](#referenceExpenseId)|Shows the reference ID for the expense entry.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[referenceJournalLine](#referenceJournalLine)|Shows the journal line ID for the journal transaction.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[referenceTimeId](#referenceTimeId)||<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[resourceCategory](#resourceCategory)|Shows the role for the resource for this transaction.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[salesPrice](#salesPrice)|Shows the sales price of the transaction.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[salesPriceBase](#salesPriceBase)|Value of the Sales Price in base currency.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[salesQuantity](#salesQuantity)|Shows the billable hours for the transaction.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[submittedBy](#submittedBy)|Resource that has submitted the entry for approval.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[timeEntry](#timeEntry)|Time Entry Id.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[transactionCategory](#transactionCategory)|Shows the transaction category.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[costAmount](#costAmount)|Shows the cost amount of the transaction.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[costAmountBase](#costAmountBase)|Value of the Cost Amount in base currency.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[salesAmount](#salesAmount)|Shows the sales amount of the transaction.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|
|[salesAmountBase](#salesAmountBase)|Value of the Sales Amount in base currency.|<a href="ProjectApproval.md" target="_blank">projectServiceAutomation/ProjectApproval</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#projectApprovalId name="projectApprovalId">projectApprovalId</a>

Unique identifier for entity instances  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ApprovalsTable</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_projectapprovalid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the ApprovalsTable  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the ApprovalsTable</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the ApprovalsTable  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the ApprovalsTable</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_name</td></tr></table>

### <a href=#approvedBy name="approvedBy">approvedBy</a>

Shows the name of the approver.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Approved By</td></tr><tr><td>description</td><td>Shows the name of the approver.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_approvedby</td></tr></table>

### <a href=#approvedOn name="approvedOn">approvedOn</a>

Shows the date of the approval.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Approved On</td></tr><tr><td>description</td><td>Shows the date of the approval.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_approvedon</td></tr></table>

### <a href=#billingType name="billingType">billingType</a>

Billing type for the project approval line.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Billing Type</td></tr><tr><td>description</td><td>Billing type for the project approval line.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_billingtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Non Chargeable</td><td>192350000</td></tr><tr><td>en</td><td>Chargeable</td><td>192350001</td></tr><tr><td>en</td><td>Complimentary</td><td>192350002</td></tr><tr><td>en</td><td>Not Available</td><td>192350003</td></tr></table></td></tr></table>

### <a href=#billingType_display name="billingType_display">billingType_display</a>

First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#bookableResource name="bookableResource">bookableResource</a>

Shows the resource that the entry is submitted for.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource</td></tr><tr><td>description</td><td>Shows the resource that the entry is submitted for.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_bookableresource</td></tr></table>

### <a href=#costPrice name="costPrice">costPrice</a>

Shows the cost price of the transaction.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost Price</td></tr><tr><td>description</td><td>Shows the cost price of the transaction.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_costprice</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Shows the currency associated with the entity.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Shows the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#costPriceBase name="costPriceBase">costPriceBase</a>

Value of the Cost Price in base currency.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost Price (Base)</td></tr><tr><td>description</td><td>Value of the Cost Price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_costprice_base</td></tr></table>

### <a href=#costQuantity name="costQuantity">costQuantity</a>

Shows the hours submitted for the transaction.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Submitted (hrs)</td></tr><tr><td>description</td><td>Shows the hours submitted for the transaction.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_costquantity</td></tr></table>

### <a href=#date name="date">date</a>

Shows the date of the transaction.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date</td></tr><tr><td>description</td><td>Shows the date of the transaction.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_date</td></tr></table>

### <a href=#entryType name="entryType">entryType</a>

Shows the entry type of the transaction.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Entry Type</td></tr><tr><td>description</td><td>Shows the entry type of the transaction.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_entrytype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Time</td><td>0</td></tr><tr><td>en</td><td>Expense</td><td>1</td></tr></table></td></tr></table>

### <a href=#entryType_display name="entryType_display">entryType_display</a>

First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#expenseCategory name="expenseCategory">expenseCategory</a>

Shows the expense category of the transaction.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expense Category</td></tr><tr><td>description</td><td>Shows the expense category of the transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_expensecategory</td></tr></table>

### <a href=#expenseEntry name="expenseEntry">expenseEntry</a>

Expense Entry Id.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expense Entry</td></tr><tr><td>description</td><td>Expense Entry Id.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_expenseentry</td></tr></table>

### <a href=#externalComments name="externalComments">externalComments</a>

Shows the external comments entered for the transaction.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>External Comments</td></tr><tr><td>description</td><td>Shows the external comments entered for the transaction.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_externalcomments</td></tr></table>

### <a href=#hasReceipt name="hasReceipt">hasReceipt</a>

Shows whether the transaction has a receipt.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Has Receipt</td></tr><tr><td>description</td><td>Shows whether the transaction has a receipt.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_hasreceipt</td></tr></table>

### <a href=#internalComments name="internalComments">internalComments</a>

Shows the internal comments entered for the transaction.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Internal Comments</td></tr><tr><td>description</td><td>Shows the internal comments entered for the transaction.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_internalcomments</td></tr></table>

### <a href=#journalTransaction name="journalTransaction">journalTransaction</a>

Shows whether the transaction was entered by a journal.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>JournalTransaction</td></tr><tr><td>description</td><td>Shows whether the transaction was entered by a journal.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_journaltransaction</td></tr></table>

### <a href=#manager name="manager">manager</a>

Shows the manager of the person who submitted the transaction.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Manager</td></tr><tr><td>description</td><td>Shows the manager of the person who submitted the transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_manager</td></tr></table>

### <a href=#project name="project">project</a>

Shows the project for the transaction.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project</td></tr><tr><td>description</td><td>Shows the project for the transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_project</td></tr></table>

### <a href=#projectTask name="projectTask">projectTask</a>

Shows the project task for the transaction.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Task</td></tr><tr><td>description</td><td>Shows the project task for the transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_projecttask</td></tr></table>

### <a href=#recordStage name="recordStage">recordStage</a>

Shows the stage of the record.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Stage</td></tr><tr><td>description</td><td>Shows the stage of the record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_recordstage</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Pending</td><td>3</td></tr><tr><td>en</td><td>Submitted</td><td>0</td></tr><tr><td>en</td><td>Rejected</td><td>1</td></tr><tr><td>en</td><td>Approved</td><td>2</td></tr><tr><td>en</td><td>Recall Requested</td><td>4</td></tr><tr><td>en</td><td>Recall Request Approved</td><td>5</td></tr><tr><td>en</td><td>Recall Request Rejected</td><td>6</td></tr></table></td></tr></table>

### <a href=#recordStage_display name="recordStage_display">recordStage_display</a>

First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#referenceExpenseId name="referenceExpenseId">referenceExpenseId</a>

Shows the reference ID for the expense entry.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reference expense id</td></tr><tr><td>description</td><td>Shows the reference ID for the expense entry.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_referenceexpenseid</td></tr></table>

### <a href=#referenceJournalLine name="referenceJournalLine">referenceJournalLine</a>

Shows the journal line ID for the journal transaction.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>reference journal line</td></tr><tr><td>description</td><td>Shows the journal line ID for the journal transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_referencejournalline</td></tr></table>

### <a href=#referenceTimeId name="referenceTimeId">referenceTimeId</a>

First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reference time id</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_referencetimeid</td></tr></table>

### <a href=#resourceCategory name="resourceCategory">resourceCategory</a>

Shows the role for the resource for this transaction.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource Role</td></tr><tr><td>description</td><td>Shows the role for the resource for this transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourcecategory</td></tr></table>

### <a href=#salesPrice name="salesPrice">salesPrice</a>

Shows the sales price of the transaction.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales Price</td></tr><tr><td>description</td><td>Shows the sales price of the transaction.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salesprice</td></tr></table>

### <a href=#salesPriceBase name="salesPriceBase">salesPriceBase</a>

Value of the Sales Price in base currency.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales Price (Base)</td></tr><tr><td>description</td><td>Value of the Sales Price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salesprice_base</td></tr></table>

### <a href=#salesQuantity name="salesQuantity">salesQuantity</a>

Shows the billable hours for the transaction.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Billable (hrs)</td></tr><tr><td>description</td><td>Shows the billable hours for the transaction.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salesquantity</td></tr></table>

### <a href=#submittedBy name="submittedBy">submittedBy</a>

Resource that has submitted the entry for approval.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Submitted By</td></tr><tr><td>description</td><td>Resource that has submitted the entry for approval.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_submittedby</td></tr></table>

### <a href=#timeEntry name="timeEntry">timeEntry</a>

Time Entry Id.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Entry</td></tr><tr><td>description</td><td>Time Entry Id.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_timeentry</td></tr></table>

### <a href=#transactionCategory name="transactionCategory">transactionCategory</a>

Shows the transaction category.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Category</td></tr><tr><td>description</td><td>Shows the transaction category.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactioncategory</td></tr></table>

### <a href=#costAmount name="costAmount">costAmount</a>

Shows the cost amount of the transaction.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost Amount</td></tr><tr><td>description</td><td>Shows the cost amount of the transaction.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_costamount</td></tr></table>

### <a href=#costAmountBase name="costAmountBase">costAmountBase</a>

Value of the Cost Amount in base currency.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost Amount (Base)</td></tr><tr><td>description</td><td>Value of the Cost Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_costamount_base</td></tr></table>

### <a href=#salesAmount name="salesAmount">salesAmount</a>

Shows the sales amount of the transaction.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales Amount</td></tr><tr><td>description</td><td>Shows the sales amount of the transaction.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salesamount</td></tr></table>

### <a href=#salesAmountBase name="salesAmountBase">salesAmountBase</a>

Value of the Sales Amount in base currency.  
First included in: projectServiceAutomation/ProjectApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales Amount (Base)</td></tr><tr><td>description</td><td>Value of the Sales Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salesamount_base</td></tr></table>
