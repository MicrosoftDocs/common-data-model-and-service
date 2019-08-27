---
title: SLAKPIInstance - Common Data Model | Microsoft Docs
description: Service level agreement (SLA) key performance indicator (KPI) instance that is tracked for an individual case
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# SLA KPI Instance

Service level agreement (SLA) key performance indicator (KPI) instance that is tracked for an individual case  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/service/SLAKPIInstance.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- [/SLAKPIInstance](../../../SLAKPIInstance.md "/core/applicationCommon/SLAKPIInstance.cdm.json/SLAKPIInstance")  
- /foundationCommon/crmCommon/service/SLAKPIInstance  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[SLAKPIInstanceId](#SLAKPIInstanceId)|Unique identifier of the SLA KPI Instance.|<a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>|
|[name](#name)|Type a descriptive name for the service level agreement (SLA) key performance indicator (KPI) instance.|<a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>|
|[computedFailureTime](#computedFailureTime)|Computed Failure Date and time|<a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>|
|[computedWarningTime](#computedWarningTime)|Computed Warning Date and time|<a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>|
|[failureTime](#failureTime)|Enter the date and time when the service level agreement (SLA) key performance indicator (KPI) will expire.|<a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>|
|[ownerId](#ownerId)|Owner Id|<a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>|
|[owningUser](#owningUser)|Owning User.|<a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>|
|[owningTeam](#owningTeam)|OwningTeam.|<a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Owning Business Unit.|<a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>|
|[status](#status)|Reason for the status of the service level agreement (SLA) key performance indicator (KPI) instance. For example, the SLA KPI could be Noncompliant or Succeeded.|<a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>|
|[status_display](#status_display)||<a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>|
|[succeededOn](#succeededOn)|Shows the date and time when the service level agreement (SLA) key performance indicator (KPI) success criteria was met.|<a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>|
|[warningTime](#warningTime)|Enter the date and time when the service level agreement (SLA) key performance indicator (KPI)will go to a warning state.|<a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>|
|[exchangeRate](#exchangeRate)|For internal use only.|<a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>|
|[createdBy](#createdBy)|For internal use only.|<a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>|
|[createdOn](#createdOn)|For internal use only.|<a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|For internal use only.|<a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>|
|[description](#description)|For internal use only.|<a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>|
|[modifiedBy](#modifiedBy)|For internal use only.|<a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>|
|[modifiedOn](#modifiedOn)|For internal use only.|<a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|For internal use only.|<a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>|
|[versionNumber](#versionNumber)|For internal use only.|<a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>|
|[warningTimeReached](#warningTimeReached)|Shows information about whether the case has reached its warning time.|<a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>|
|[warningTimeReached_display](#warningTimeReached_display)||<a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>|
|[regardingObjectTypeCode](#regardingObjectTypeCode)|The name of the entity linked by Regarding|<a href="SLAKPIInstance.md" target="_blank">service/SLAKPIInstance</a>|

### <a href=#SLAKPIInstanceId name="SLAKPIInstanceId">SLAKPIInstanceId</a>

Unique identifier of the SLA KPI Instance.  
First included in: <a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SLA KPI InstanceId</td></tr><tr><td>description</td><td>Unique identifier of the SLA KPI Instance.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>slakpiinstanceid</td></tr></table>

### <a href=#name name="name">name</a>

Type a descriptive name for the service level agreement (SLA) key performance indicator (KPI) instance.  
First included in: <a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type a descriptive name for the service level agreement (SLA) key performance indicator (KPI) instance.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#computedFailureTime name="computedFailureTime">computedFailureTime</a>

Computed Failure Date and time  
First included in: <a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Computed Failure Time</td></tr><tr><td>description</td><td>Computed Failure Date and time</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>computedfailuretime</td></tr></table>

### <a href=#computedWarningTime name="computedWarningTime">computedWarningTime</a>

Computed Warning Date and time  
First included in: <a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Computed Warning Time</td></tr><tr><td>description</td><td>Computed Warning Date and time</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>computedwarningtime</td></tr></table>

### <a href=#failureTime name="failureTime">failureTime</a>

Enter the date and time when the service level agreement (SLA) key performance indicator (KPI) will expire.  
First included in: <a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Failure Time</td></tr><tr><td>description</td><td>Enter the date and time when the service level agreement (SLA) key performance indicator (KPI) will expire.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>failuretime</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: <a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: <a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Owning User.  
First included in: <a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Owning User.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

OwningTeam.  
First included in: <a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>OwningTeam.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Owning Business Unit.  
First included in: <a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Owning Business Unit.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#status name="status">status</a>

Reason for the status of the service level agreement (SLA) key performance indicator (KPI) instance. For example, the SLA KPI could be Noncompliant or Succeeded.  
First included in: <a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Reason for the status of the service level agreement (SLA) key performance indicator (KPI) instance. For example, the SLA KPI could be Noncompliant or Succeeded.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>status</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>In Progress</td><td>0</td></tr><tr><td>en</td><td>Noncompliant</td><td>1</td></tr><tr><td>en</td><td>Nearing Noncompliance</td><td>2</td></tr><tr><td>en</td><td>Paused</td><td>3</td></tr><tr><td>en</td><td>Succeeded</td><td>4</td></tr><tr><td>en</td><td>Canceled</td><td>5</td></tr></table></td></tr></table>

### <a href=#status_display name="status_display">status_display</a>

First included in: <a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#succeededOn name="succeededOn">succeededOn</a>

Shows the date and time when the service level agreement (SLA) key performance indicator (KPI) success criteria was met.  
First included in: <a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Succeeded On</td></tr><tr><td>description</td><td>Shows the date and time when the service level agreement (SLA) key performance indicator (KPI) success criteria was met.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>succeededon</td></tr></table>

### <a href=#warningTime name="warningTime">warningTime</a>

Enter the date and time when the service level agreement (SLA) key performance indicator (KPI)will go to a warning state.  
First included in: <a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Warning Time</td></tr><tr><td>description</td><td>Enter the date and time when the service level agreement (SLA) key performance indicator (KPI)will go to a warning state.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>warningtime</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: <a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

For internal use only.  
First included in: <a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

For internal use only.  
First included in: <a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

For internal use only.  
First included in: <a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

For internal use only.  
First included in: <a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#description name="description">description</a>

For internal use only.  
First included in: <a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

For internal use only.  
First included in: <a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

For internal use only.  
First included in: <a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

For internal use only.  
First included in: <a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

For internal use only.  
First included in: <a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#warningTimeReached name="warningTimeReached">warningTimeReached</a>

Shows information about whether the case has reached its warning time.  
First included in: <a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Warning Time Reached</td></tr><tr><td>description</td><td>Shows information about whether the case has reached its warning time.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>warningtimereached</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>No</td><td>0</td></tr><tr><td>en</td><td>Yes</td><td>1</td></tr></table></td></tr></table>

### <a href=#warningTimeReached_display name="warningTimeReached_display">warningTimeReached_display</a>

First included in: <a href="../../../SLAKPIInstance.md" target="_blank">applicationCommon/SLAKPIInstance</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#regardingObjectTypeCode name="regardingObjectTypeCode">regardingObjectTypeCode</a>

The name of the entity linked by Regarding  
First included in: service/SLAKPIInstance (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regarding Type</td></tr><tr><td>description</td><td>The name of the entity linked by Regarding</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>regardingobjecttypecode</td></tr></table>
