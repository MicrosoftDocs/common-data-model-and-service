---
title: SLAItem - Common Data Model | Microsoft Docs
description: Contains information about a tracked support KPI for a specific customer.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# SLA Item

Contains information about a tracked support KPI for a specific customer.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/SLAItem.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /SLAItem  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[SLAItemId](#SLAItemId)|Unique identifier of the SLA Item.|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[name](#name)|Type a descriptive name of the service level agreement (SLA) item.|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[description](#description)|Type additional information to describe the SLA Item|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[relatedField](#relatedField)|Select the service level agreement (SLA) key performance indicator (KPI) that this SLA Item is created for.|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[SLAId](#SLAId)|Unique identifier for SLA associated with SLA Item.|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[createdOn](#createdOn)|Shows the date and time when the record was created. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[modifiedOn](#modifiedOn)|Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[exchangeRate](#exchangeRate)|Exchange rate between the currency associated with the SLA Item record and the base currency.|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[versionNumber](#versionNumber)|Version number of the SLA Item.|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the SLA Item record.|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[applicableWhenXml](#applicableWhenXml)|Condition for SLA item|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[successConditionsXml](#successConditionsXml)|Condition for SLA item|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[solutionId](#solutionId)|Unique identifier of the associated solution.|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[componentState](#componentState)|For internal use only.|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[componentState_display](#componentState_display)||<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[overwriteTime](#overwriteTime)|For internal use only.|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[isManaged](#isManaged)|For internal use only.|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[SLAItemIdUnique](#SLAItemIdUnique)|For internal use only.|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[sequenceNumber](#sequenceNumber)|Select the time zone, or UTC offset, for this address so that other people can reference it when they contact someone at this address.|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[failureAfter](#failureAfter)|Select how soon the success criteria must be met until the SLA item is considered failed and failure actions are initiated. The actual duration is based on the business hours as specified in the associated SLA record.|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[warnAfter](#warnAfter)|Select how soon the success criteria must be met before warning actions are initiated. The actual duration is based on the business hours as specified in the associated SLA record.|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[owningUser](#owningUser)|Unique identifier of the user who owns the SLA Item record.|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[ownerId](#ownerId)|Owner Id|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[workflowId](#workflowId)|Workflow associated with the SLA Item.|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="SLAItem.md" target="_blank">applicationCommon/SLAItem</a>|

### <a href=#SLAItemId name="SLAItemId">SLAItemId</a>

Unique identifier of the SLA Item.  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SLA Item</td></tr><tr><td>description</td><td>Unique identifier of the SLA Item.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>slaitemid</td></tr></table>

### <a href=#name name="name">name</a>

Type a descriptive name of the service level agreement (SLA) item.  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type a descriptive name of the service level agreement (SLA) item.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#description name="description">description</a>

Type additional information to describe the SLA Item  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type additional information to describe the SLA Item</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#relatedField name="relatedField">relatedField</a>

Select the service level agreement (SLA) key performance indicator (KPI) that this SLA Item is created for.  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Related Case Field</td></tr><tr><td>description</td><td>Select the service level agreement (SLA) key performance indicator (KPI) that this SLA Item is created for.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>relatedfield</td></tr></table>

### <a href=#SLAId name="SLAId">SLAId</a>

Unique identifier for SLA associated with SLA Item.  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SLA</td></tr><tr><td>description</td><td>Unique identifier for SLA associated with SLA Item.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slaid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Shows the date and time when the record was created. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Shows the date and time when the record was created. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate between the currency associated with the SLA Item record and the base currency.  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate between the currency associated with the SLA Item record and the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version number of the SLA Item.  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version number of the SLA Item.</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the SLA Item record.  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the SLA Item record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#applicableWhenXml name="applicableWhenXml">applicableWhenXml</a>

Condition for SLA item  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ApplicableWhenXml</td></tr><tr><td>description</td><td>Condition for SLA item</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>applicablewhenxml</td></tr></table>

### <a href=#successConditionsXml name="successConditionsXml">successConditionsXml</a>

Condition for SLA item  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SuccessConditionsXml</td></tr><tr><td>description</td><td>Condition for SLA item</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>successconditionsxml</td></tr></table>

### <a href=#solutionId name="solutionId">solutionId</a>

Unique identifier of the associated solution.  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Solution</td></tr><tr><td>description</td><td>Unique identifier of the associated solution.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>solutionid</td></tr></table>

### <a href=#componentState name="componentState">componentState</a>

For internal use only.  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Component State</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>componentstate</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Published</td><td>0</td></tr><tr><td>en</td><td>Unpublished</td><td>1</td></tr><tr><td>en</td><td>Deleted</td><td>2</td></tr><tr><td>en</td><td>Deleted Unpublished</td><td>3</td></tr></table></td></tr></table>

### <a href=#componentState_display name="componentState_display">componentState_display</a>

First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#overwriteTime name="overwriteTime">overwriteTime</a>

For internal use only.  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Overwrite Time</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>overwritetime</td></tr></table>

### <a href=#isManaged name="isManaged">isManaged</a>

For internal use only.  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Managed</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>ismanaged</td></tr></table>

### <a href=#SLAItemIdUnique name="SLAItemIdUnique">SLAItemIdUnique</a>

For internal use only.  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unique Id</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>slaitemidunique</td></tr></table>

### <a href=#sequenceNumber name="sequenceNumber">sequenceNumber</a>

Select the time zone, or UTC offset, for this address so that other people can reference it when they contact someone at this address.  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sequence</td></tr><tr><td>description</td><td>Select the time zone, or UTC offset, for this address so that other people can reference it when they contact someone at this address.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1500</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sequencenumber</td></tr></table>

### <a href=#failureAfter name="failureAfter">failureAfter</a>

Select how soon the success criteria must be met until the SLA item is considered failed and failure actions are initiated. The actual duration is based on the business hours as specified in the associated SLA record.  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Failure After</td></tr><tr><td>description</td><td>Select how soon the success criteria must be met until the SLA item is considered failed and failure actions are initiated. The actual duration is based on the business hours as specified in the associated SLA record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>failureafter</td></tr></table>

### <a href=#warnAfter name="warnAfter">warnAfter</a>

Select how soon the success criteria must be met before warning actions are initiated. The actual duration is based on the business hours as specified in the associated SLA record.  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Warn After</td></tr><tr><td>description</td><td>Select how soon the success criteria must be met before warning actions are initiated. The actual duration is based on the business hours as specified in the associated SLA record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>warnafter</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user who owns the SLA Item record.  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user who owns the SLA Item record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#workflowId name="workflowId">workflowId</a>

Workflow associated with the SLA Item.  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Workflow ID</td></tr><tr><td>description</td><td>Workflow associated with the SLA Item.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>workflowid</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: applicationCommon/SLAItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>
