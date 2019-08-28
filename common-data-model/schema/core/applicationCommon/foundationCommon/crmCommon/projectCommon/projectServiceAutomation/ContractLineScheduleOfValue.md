---
title: ContractLineScheduleOfValue - Common Data Model | Microsoft Docs
description: List of billing milestones and invoice amounts for this project contract line.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Project Contract Line Milestone

List of billing milestones and invoice amounts for this project contract line.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/ContractLineScheduleOfValue.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/ContractLineScheduleOfValue  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[ownerId](#ownerId)|Owner Id|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[contractLineScheduleOfValueId](#contractLineScheduleOfValueId)|Unique identifier for entity instances|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[stateCode](#stateCode)|Status of the project contract line milestone.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[stateCode_display](#stateCode_display)||<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[statusCode](#statusCode)|Reason for the status of the project contract line milestone.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[statusCode_display](#statusCode_display)||<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[milestoneName](#milestoneName)|Type the name of the milestone.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[milestoneAmount](#milestoneAmount)|Enter the value of the milestone.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Shows the currency associated with the entity.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[amountBase](#amountBase)|Value of the Amount in base currency.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[projectContract](#projectContract)|Select the project contract associated with this milestone.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[contractLine](#contractLine)|(Deprecated) Shows the project contract line that has this milestone|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[contractLineId](#contractLineId)|Unique identifier for Project Contract Line associated with Project Contract Line Invoice Schedule.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[contractLineDescription](#contractLineDescription)|Enter a description of the project contract line that has this milestone.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[milestoneDescription](#milestoneDescription)|Type a description of the milestone.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[externalDescription](#externalDescription)|Description of the project contract line milestone|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[invoiceDate](#invoiceDate)|Enter the date of which this milestone should be achieved|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[invoiceStatus](#invoiceStatus)|Select the status of invoicing of this milestone|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[invoiceStatus_display](#invoiceStatus_display)||<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[price](#price)|Enter the price of the transaction.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[priceBase](#priceBase)|Value of the Price in base currency.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[project](#project)|Select the project that is tracking the work required to achieve this milestone.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[projectTask](#projectTask)|Select the project work breakdown structure (WBS) task that is tracking the work for this milestone.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[startDate](#startDate)|Date of project contract line milestone|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[tax](#tax)||<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[taxBase](#taxBase)|Value of the tax in base currency.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[transactionClassification](#transactionClassification)|Transaction classification of the project contract line milestone|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[transactionClassification_display](#transactionClassification_display)||<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[transactionTypeCode](#transactionTypeCode)|Transaction type of the project contract line milestone|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[transactionTypeCode_display](#transactionTypeCode_display)||<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[amountAfterTax](#amountAfterTax)||<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|
|[amountAfterTaxBase](#amountAfterTaxBase)|Value of the amount_after_tax in base currency.|<a href="ContractLineScheduleOfValue.md" target="_blank">projectServiceAutomation/ContractLineScheduleOfValue</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#contractLineScheduleOfValueId name="contractLineScheduleOfValueId">contractLineScheduleOfValueId</a>

Unique identifier for entity instances  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Contract Line Milestone</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_contractlinescheduleofvalueid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the project contract line milestone.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the project contract line milestone.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the project contract line milestone.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the project contract line milestone.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#milestoneName name="milestoneName">milestoneName</a>

Type the name of the milestone.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Milestone Name</td></tr><tr><td>description</td><td>Type the name of the milestone.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_name</td></tr></table>

### <a href=#milestoneAmount name="milestoneAmount">milestoneAmount</a>

Enter the value of the milestone.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Line Amount</td></tr><tr><td>description</td><td>Enter the value of the milestone.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_amount</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Shows the currency associated with the entity.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Shows the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#amountBase name="amountBase">amountBase</a>

Value of the Amount in base currency.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount (Base)</td></tr><tr><td>description</td><td>Value of the Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_amount_base</td></tr></table>

### <a href=#projectContract name="projectContract">projectContract</a>

Select the project contract associated with this milestone.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Contract</td></tr><tr><td>description</td><td>Select the project contract associated with this milestone.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_contract</td></tr></table>

### <a href=#contractLine name="contractLine">contractLine</a>

(Deprecated) Shows the project contract line that has this milestone  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>(Deprecated) Project Contract Line</td></tr><tr><td>description</td><td>(Deprecated) Shows the project contract line that has this milestone</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_contractline</td></tr></table>

### <a href=#contractLineId name="contractLineId">contractLineId</a>

Unique identifier for Project Contract Line associated with Project Contract Line Invoice Schedule.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Contract Line</td></tr><tr><td>description</td><td>Unique identifier for Project Contract Line associated with Project Contract Line Invoice Schedule.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_contractlineid</td></tr></table>

### <a href=#contractLineDescription name="contractLineDescription">contractLineDescription</a>

Enter a description of the project contract line that has this milestone.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Contract Line Description</td></tr><tr><td>description</td><td>Enter a description of the project contract line that has this milestone.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_contractlinedescription</td></tr></table>

### <a href=#milestoneDescription name="milestoneDescription">milestoneDescription</a>

Type a description of the milestone.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Milestone Description</td></tr><tr><td>description</td><td>Type a description of the milestone.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_description</td></tr></table>

### <a href=#externalDescription name="externalDescription">externalDescription</a>

Description of the project contract line milestone  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>External Description</td></tr><tr><td>description</td><td>Description of the project contract line milestone</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_externaldescription</td></tr></table>

### <a href=#invoiceDate name="invoiceDate">invoiceDate</a>

Enter the date of which this milestone should be achieved  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Milestone Date</td></tr><tr><td>description</td><td>Enter the date of which this milestone should be achieved</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_invoicedate</td></tr></table>

### <a href=#invoiceStatus name="invoiceStatus">invoiceStatus</a>

Select the status of invoicing of this milestone  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice Status</td></tr><tr><td>description</td><td>Select the status of invoicing of this milestone</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_invoicestatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not Ready for invoicing</td><td>192350000</td></tr><tr><td>en</td><td>Ready for invoicing</td><td>192350001</td></tr><tr><td>en</td><td>Customer invoice created</td><td>192350002</td></tr><tr><td>en</td><td>Customer invoice posted</td><td>192350003</td></tr></table></td></tr></table>

### <a href=#invoiceStatus_display name="invoiceStatus_display">invoiceStatus_display</a>

First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#price name="price">price</a>

Enter the price of the transaction.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price</td></tr><tr><td>description</td><td>Enter the price of the transaction.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_price</td></tr></table>

### <a href=#priceBase name="priceBase">priceBase</a>

Value of the Price in base currency.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price (Base)</td></tr><tr><td>description</td><td>Value of the Price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_price_base</td></tr></table>

### <a href=#project name="project">project</a>

Select the project that is tracking the work required to achieve this milestone.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project</td></tr><tr><td>description</td><td>Select the project that is tracking the work required to achieve this milestone.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_project</td></tr></table>

### <a href=#projectTask name="projectTask">projectTask</a>

Select the project work breakdown structure (WBS) task that is tracking the work for this milestone.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Task</td></tr><tr><td>description</td><td>Select the project work breakdown structure (WBS) task that is tracking the work for this milestone.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_projecttask</td></tr></table>

### <a href=#startDate name="startDate">startDate</a>

Date of project contract line milestone  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date</td></tr><tr><td>description</td><td>Date of project contract line milestone</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_startdatetime</td></tr></table>

### <a href=#tax name="tax">tax</a>

First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>tax</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_tax</td></tr></table>

### <a href=#taxBase name="taxBase">taxBase</a>

Value of the tax in base currency.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>tax (Base)</td></tr><tr><td>description</td><td>Value of the tax in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_tax_base</td></tr></table>

### <a href=#transactionClassification name="transactionClassification">transactionClassification</a>

Transaction classification of the project contract line milestone  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Class</td></tr><tr><td>description</td><td>Transaction classification of the project contract line milestone</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactionclassification</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Time</td><td>192350000</td></tr><tr><td>en</td><td>Expense</td><td>192350001</td></tr><tr><td>en</td><td>Material</td><td>192350002</td></tr><tr><td>en</td><td>Milestone</td><td>192350003</td></tr><tr><td>en</td><td>Fee</td><td>192350004</td></tr><tr><td>en</td><td>Tax</td><td>690970002</td></tr></table></td></tr></table>

### <a href=#transactionClassification_display name="transactionClassification_display">transactionClassification_display</a>

First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionTypeCode name="transactionTypeCode">transactionTypeCode</a>

Transaction type of the project contract line milestone  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Type</td></tr><tr><td>description</td><td>Transaction type of the project contract line milestone</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactiontypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Cost</td><td>192350000</td></tr><tr><td>en</td><td>Project Contract</td><td>192350004</td></tr><tr><td>en</td><td>Unbilled Sales</td><td>192350005</td></tr><tr><td>en</td><td>Billed Sales</td><td>192350006</td></tr><tr><td>en</td><td>Resourcing Unit Cost</td><td>192350007</td></tr><tr><td>en</td><td>Inter-Organizational Sales</td><td>192350008</td></tr></table></td></tr></table>

### <a href=#transactionTypeCode_display name="transactionTypeCode_display">transactionTypeCode_display</a>

First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#amountAfterTax name="amountAfterTax">amountAfterTax</a>

First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Milestone Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_amount_after_tax</td></tr></table>

### <a href=#amountAfterTaxBase name="amountAfterTaxBase">amountAfterTaxBase</a>

Value of the amount_after_tax in base currency.  
First included in: projectServiceAutomation/ContractLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>amount_after_tax (Base)</td></tr><tr><td>description</td><td>Value of the amount_after_tax in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_amount_after_tax_base</td></tr></table>
