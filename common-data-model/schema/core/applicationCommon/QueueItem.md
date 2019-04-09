---
title: QueueItem - Common Data Model | Microsoft Docs
description: A specific item in a queue, such as a case record or an activity record.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Queue Item

A specific item in a queue, such as a case record or an activity record.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/QueueItem.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /QueueItem  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[queueItemId](#queueItemId)|Unique identifier of the queue item.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[queueId](#queueId)|Choose the queue that the item is assigned to.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[objectIdTypeCode](#objectIdTypeCode)|The name of the entity linked by objectId|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[objectId](#objectId)|Choose the activity, case, or article assigned to the queue.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[objectTypeCode](#objectTypeCode)|Select the type of the queue item, such as activity, case, or appointment.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[objectTypeCode_display](#objectTypeCode_display)||<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[title](#title)|Shows the title or name that describes the queue record. This value is copied from the record that was assigned to the queue.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[enteredOn](#enteredOn)|Shows the date the record was assigned to the queue.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[priority](#priority)|Priority of the queue item.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[state](#state)|Status of the queue item.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[status](#status)|Reason for the status of the queue item.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[createdOn](#createdOn)|Shows the date and time when the record was created. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[modifiedOn](#modifiedOn)|Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[toRecipients](#toRecipients)|Recipients listed on the To line of the message for email queue items.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[sender](#sender)|Sender who created the queue item.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[organizationId](#organizationId)|Unique identifier of the organization with which the queue item is associated.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[versionNumber](#versionNumber)|Version number of the queue item.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[workerIdModifiedOn](#workerIdModifiedOn)|Shows the date and time when the queue item was last assigned to a user.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[ownerId](#ownerId)|Owner Id|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[owningUser](#owningUser)|Unique identifier of the user who owns the queue item.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[workerIdType](#workerIdType)|The name of the entity linked by workerId|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[workerId](#workerId)|Shows who is working on the queue item.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier of the business unit that owns the queue item.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[statusCode](#statusCode)|Select the item's status.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[statusCode_display](#statusCode_display)||<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[stateCode](#stateCode)|Shows whether the queue record is active or inactive. Inactive queue records are read-only and can't be edited unless they are reactivated.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[stateCode_display](#stateCode_display)||<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who last modified the queueitem.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="QueueItem.md" target="_blank">applicationCommon/QueueItem</a>|

### <a href=#queueItemId name="queueItemId">queueItemId</a>

Unique identifier of the queue item.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Queue Item</td></tr><tr><td>description</td><td>Unique identifier of the queue item.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>queueitemid</td></tr></table>

### <a href=#queueId name="queueId">queueId</a>

Choose the queue that the item is assigned to.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Queue</td></tr><tr><td>description</td><td>Choose the queue that the item is assigned to.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>queueid</td></tr></table>

### <a href=#objectIdTypeCode name="objectIdTypeCode">objectIdTypeCode</a>

The name of the entity linked by objectId  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ObjectId Type</td></tr><tr><td>description</td><td>The name of the entity linked by objectId</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>objectidtypecode</td></tr></table>

### <a href=#objectId name="objectId">objectId</a>

Choose the activity, case, or article assigned to the queue.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Object</td></tr><tr><td>description</td><td>Choose the activity, case, or article assigned to the queue.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>objectid</td></tr></table>

### <a href=#objectTypeCode name="objectTypeCode">objectTypeCode</a>

Select the type of the queue item, such as activity, case, or appointment.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type</td></tr><tr><td>description</td><td>Select the type of the queue item, such as activity, case, or appointment.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>objecttypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>0</td></tr></table></td></tr></table>

### <a href=#objectTypeCode_display name="objectTypeCode_display">objectTypeCode_display</a>

First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#title name="title">title</a>

Shows the title or name that describes the queue record. This value is copied from the record that was assigned to the queue.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Title</td></tr><tr><td>description</td><td>Shows the title or name that describes the queue record. This value is copied from the record that was assigned to the queue.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>300</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>title</td></tr></table>

### <a href=#enteredOn name="enteredOn">enteredOn</a>

Shows the date the record was assigned to the queue.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Entered Queue</td></tr><tr><td>description</td><td>Shows the date the record was assigned to the queue.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>enteredon</td></tr></table>

### <a href=#priority name="priority">priority</a>

Priority of the queue item.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Priority</td></tr><tr><td>description</td><td>Priority of the queue item.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>priority</td></tr></table>

### <a href=#state name="state">state</a>

Status of the queue item.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status (deprecated)</td></tr><tr><td>description</td><td>Status of the queue item.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>state</td></tr></table>

### <a href=#status name="status">status</a>

Reason for the status of the queue item.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason (deprecated)</td></tr><tr><td>description</td><td>Reason for the status of the queue item.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>status</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Shows the date and time when the record was created. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Shows the date and time when the record was created. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#toRecipients name="toRecipients">toRecipients</a>

Recipients listed on the To line of the message for email queue items.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>To</td></tr><tr><td>description</td><td>Recipients listed on the To line of the message for email queue items.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>torecipients</td></tr></table>

### <a href=#sender name="sender">sender</a>

Sender who created the queue item.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>From</td></tr><tr><td>description</td><td>Sender who created the queue item.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sender</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier of the organization with which the queue item is associated.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization</td></tr><tr><td>description</td><td>Unique identifier of the organization with which the queue item is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version number of the queue item.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version number of the queue item.</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#workerIdModifiedOn name="workerIdModifiedOn">workerIdModifiedOn</a>

Shows the date and time when the queue item was last assigned to a user.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Worked On</td></tr><tr><td>description</td><td>Shows the date and time when the queue item was last assigned to a user.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>workeridmodifiedon</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user who owns the queue item.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user who owns the queue item.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#workerIdType name="workerIdType">workerIdType</a>

The name of the entity linked by workerId  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>WorkerId Type</td></tr><tr><td>description</td><td>The name of the entity linked by workerId</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>workeridtype</td></tr></table>

### <a href=#workerId name="workerId">workerId</a>

Shows who is working on the queue item.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Worked By</td></tr><tr><td>description</td><td>Shows who is working on the queue item.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>workerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier of the business unit that owns the queue item.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier of the business unit that owns the queue item.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the item's status.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the item's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the queue record is active or inactive. Inactive queue records are read-only and can't be edited unless they are reactivated.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows whether the queue record is active or inactive. Inactive queue records are read-only and can't be edited unless they are reactivated.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who last modified the queueitem.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who last modified the queueitem.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: applicationCommon/QueueItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>
