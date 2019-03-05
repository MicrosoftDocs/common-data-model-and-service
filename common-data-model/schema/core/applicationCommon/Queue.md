---
title: Queue - Common Data Model | Microsoft Docs
description: A list of records that require action, such as accounts, activities, and cases.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/5/2019
ms.author: nebanfic
---

# Queue

A list of records that require action, such as accounts, activities, and cases.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/Queue.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /Queue  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[queueId](#queueId)|Unique identifier of the queue.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[businessUnitId](#businessUnitId)|Unique identifier of the business unit with which the queue is associated.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[organizationId](#organizationId)|Unique identifier of the organization associated with the queue.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[emailAddress](#emailAddress)|Email address that is associated with the queue.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[primaryUserId](#primaryUserId)|Unique identifier of the owner of the queue.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[queueTypeCode](#queueTypeCode)|Type of queue that is automatically assigned when a user or queue is created. The type can be public, private, or work in process.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[queueTypeCode_display](#queueTypeCode_display)||<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[name](#name)|Name of the queue.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[description](#description)|Description of the queue.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[queueSemantics](#queueSemantics)|For internal use only.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[createdOn](#createdOn)|Date and time when the queue was created.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the queue record.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who last modified the queue.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[modifiedOn](#modifiedOn)|Date and time when the queue was last modified.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[versionNumber](#versionNumber)|Version number of the queue.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[ignoreUnsolicitedEmail](#ignoreUnsolicitedEmail)|Information that specifies whether a queue is to ignore unsolicited email (deprecated).|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[isFaxQueue](#isFaxQueue)|Indication of whether a queue is the fax delivery queue.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[emailPassword](#emailPassword)|This attribute is no longer used. The data is now in the Mailbox.Password attribute.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[incomingEmailDeliveryMethod](#incomingEmailDeliveryMethod)|Incoming email delivery method for the queue.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[incomingEmailDeliveryMethod_display](#incomingEmailDeliveryMethod_display)||<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[emailUsername](#emailUsername)|This attribute is no longer used. The data is now in the Mailbox.UserName attribute.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[outgoingEmailDeliveryMethod](#outgoingEmailDeliveryMethod)|Outgoing email delivery method for the queue.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[outgoingEmailDeliveryMethod_display](#outgoingEmailDeliveryMethod_display)||<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[allowEmailCredentials](#allowEmailCredentials)|This attribute is no longer used. The data is now in the Mailbox.AllowEmailConnectorToUseCredentials attribute.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[incomingEmailFilteringMethod](#incomingEmailFilteringMethod)|Convert Incoming Email To Activities|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[incomingEmailFilteringMethod_display](#incomingEmailFilteringMethod_display)||<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[statusCode](#statusCode)|Reason for the status of the queue.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[statusCode_display](#statusCode_display)||<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier of the business unit that owns the queue.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[owningUser](#owningUser)|Unique identifier of the user who owns the queue.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[stateCode](#stateCode)|Status of the queue.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[stateCode_display](#stateCode_display)||<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the queue.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who last modified the queue.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[numberOfItems](#numberOfItems)|Number of Queue items associated with the queue.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[numberOfMembers](#numberOfMembers)|Number of Members associated with the queue.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[owningTeam](#owningTeam)|Unique identifier of the team who owns the queue.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the queue.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the queue with respect to the base currency.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[emailRouterAccessApproval](#emailRouterAccessApproval)|Shows the status of the primary email address.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[emailRouterAccessApproval_display](#emailRouterAccessApproval_display)||<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[defaultMailbox](#defaultMailbox)|Select the mailbox associated with this queue.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[entityImageId](#entityImageId)|For internal use only.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[isEmailAddressApprovedByO365Admin](#isEmailAddressApprovedByO365Admin)|Shows the status of approval of the email address by O365 Admin.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[queueViewType](#queueViewType)|Select whether the queue is public or private. A public queue can be viewed by all. A private queue can be viewed only by the members added to the queue.|<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|
|[queueViewType_display](#queueViewType_display)||<a href="Queue.md" target="_blank">applicationCommon/Queue</a>|

### <a href=#queueId name="queueId">queueId</a>

Unique identifier of the queue.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Queue</td></tr><tr><td>description</td><td>Unique identifier of the queue.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>queueid</td></tr></table>

### <a href=#businessUnitId name="businessUnitId">businessUnitId</a>

Unique identifier of the business unit with which the queue is associated.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Business Unit</td></tr><tr><td>description</td><td>Unique identifier of the business unit with which the queue is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>businessunitid</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier of the organization associated with the queue.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization</td></tr><tr><td>description</td><td>Unique identifier of the organization associated with the queue.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#emailAddress name="emailAddress">emailAddress</a>

Email address that is associated with the queue.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Incoming Email</td></tr><tr><td>description</td><td>Email address that is associated with the queue.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailaddress</td></tr></table>

### <a href=#primaryUserId name="primaryUserId">primaryUserId</a>

Unique identifier of the owner of the queue.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner (deprecated)</td></tr><tr><td>description</td><td>Unique identifier of the owner of the queue.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>primaryuserid</td></tr></table>

### <a href=#queueTypeCode name="queueTypeCode">queueTypeCode</a>

Type of queue that is automatically assigned when a user or queue is created. The type can be public, private, or work in process.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Queue Type</td></tr><tr><td>description</td><td>Type of queue that is automatically assigned when a user or queue is created. The type can be public, private, or work in process.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>queuetypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#queueTypeCode_display name="queueTypeCode_display">queueTypeCode_display</a>

First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

Name of the queue.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Name of the queue.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#description name="description">description</a>

Description of the queue.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the queue.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#queueSemantics name="queueSemantics">queueSemantics</a>

For internal use only.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Queue Semantics</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>queuesemantics</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the queue was created.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the queue was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the queue record.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the queue record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who last modified the queue.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who last modified the queue.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the queue was last modified.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the queue was last modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version number of the queue.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version number of the queue.</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#ignoreUnsolicitedEmail name="ignoreUnsolicitedEmail">ignoreUnsolicitedEmail</a>

Information that specifies whether a queue is to ignore unsolicited email (deprecated).  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Convert To Email Activities</td></tr><tr><td>description</td><td>Information that specifies whether a queue is to ignore unsolicited email (deprecated).</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ignoreunsolicitedemail</td></tr></table>

### <a href=#isFaxQueue name="isFaxQueue">isFaxQueue</a>

Indication of whether a queue is the fax delivery queue.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fax Queue</td></tr><tr><td>description</td><td>Indication of whether a queue is the fax delivery queue.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isfaxqueue</td></tr></table>

### <a href=#emailPassword name="emailPassword">emailPassword</a>

This attribute is no longer used. The data is now in the Mailbox.Password attribute.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Password (Obsolete)</td></tr><tr><td>description</td><td>This attribute is no longer used. The data is now in the Mailbox.Password attribute.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailpassword</td></tr></table>

### <a href=#incomingEmailDeliveryMethod name="incomingEmailDeliveryMethod">incomingEmailDeliveryMethod</a>

Incoming email delivery method for the queue.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Incoming Email Delivery Method</td></tr><tr><td>description</td><td>Incoming email delivery method for the queue.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>incomingemaildeliverymethod</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>None</td><td>0</td></tr><tr><td>en</td><td>Server-Side Synchronization or Email Router</td><td>2</td></tr><tr><td>en</td><td>Forward Mailbox</td><td>3</td></tr></table></td></tr></table>

### <a href=#incomingEmailDeliveryMethod_display name="incomingEmailDeliveryMethod_display">incomingEmailDeliveryMethod_display</a>

First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#emailUsername name="emailUsername">emailUsername</a>

This attribute is no longer used. The data is now in the Mailbox.UserName attribute.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>User Name (Obsolete)</td></tr><tr><td>description</td><td>This attribute is no longer used. The data is now in the Mailbox.UserName attribute.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailusername</td></tr></table>

### <a href=#outgoingEmailDeliveryMethod name="outgoingEmailDeliveryMethod">outgoingEmailDeliveryMethod</a>

Outgoing email delivery method for the queue.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Outgoing Email Delivery Method</td></tr><tr><td>description</td><td>Outgoing email delivery method for the queue.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>outgoingemaildeliverymethod</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>None</td><td>0</td></tr><tr><td>en</td><td>Server-Side Synchronization or Email Router</td><td>2</td></tr></table></td></tr></table>

### <a href=#outgoingEmailDeliveryMethod_display name="outgoingEmailDeliveryMethod_display">outgoingEmailDeliveryMethod_display</a>

First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#allowEmailCredentials name="allowEmailCredentials">allowEmailCredentials</a>

This attribute is no longer used. The data is now in the Mailbox.AllowEmailConnectorToUseCredentials attribute.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow to Use Credentials for Email Processing (Obsolete)</td></tr><tr><td>description</td><td>This attribute is no longer used. The data is now in the Mailbox.AllowEmailConnectorToUseCredentials attribute.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>allowemailcredentials</td></tr></table>

### <a href=#incomingEmailFilteringMethod name="incomingEmailFilteringMethod">incomingEmailFilteringMethod</a>

Convert Incoming Email To Activities  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Convert Incoming Email To Activities</td></tr><tr><td>description</td><td>Convert Incoming Email To Activities</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>incomingemailfilteringmethod</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>All email messages</td><td>0</td></tr><tr><td>en</td><td>Email messages in response to Dynamics 365 email</td><td>1</td></tr><tr><td>en</td><td>Email messages from Dynamics 365 Leads, Contacts and Accounts</td><td>2</td></tr><tr><td>en</td><td>Email messages from Dynamics 365 records that are email enabled</td><td>3</td></tr></table></td></tr></table>

### <a href=#incomingEmailFilteringMethod_display name="incomingEmailFilteringMethod_display">incomingEmailFilteringMethod_display</a>

First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the queue.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the queue.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier of the business unit that owns the queue.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier of the business unit that owns the queue.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user who owns the queue.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user who owns the queue.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the queue.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the queue.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the queue.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the queue.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who last modified the queue.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who last modified the queue.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#numberOfItems name="numberOfItems">numberOfItems</a>

Number of Queue items associated with the queue.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Queue Items</td></tr><tr><td>description</td><td>Number of Queue items associated with the queue.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>numberofitems</td></tr></table>

### <a href=#numberOfMembers name="numberOfMembers">numberOfMembers</a>

Number of Members associated with the queue.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>No. of Members</td></tr><tr><td>description</td><td>Number of Members associated with the queue.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>numberofmembers</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier of the team who owns the queue.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier of the team who owns the queue.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the queue.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the queue.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the queue with respect to the base currency.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the queue with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#emailRouterAccessApproval name="emailRouterAccessApproval">emailRouterAccessApproval</a>

Shows the status of the primary email address.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary Email Status</td></tr><tr><td>description</td><td>Shows the status of the primary email address.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>emailrouteraccessapproval</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Empty</td><td>0</td></tr><tr><td>en</td><td>Approved</td><td>1</td></tr><tr><td>en</td><td>Pending Approval</td><td>2</td></tr><tr><td>en</td><td>Rejected</td><td>3</td></tr></table></td></tr></table>

### <a href=#emailRouterAccessApproval_display name="emailRouterAccessApproval_display">emailRouterAccessApproval_display</a>

First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#defaultMailbox name="defaultMailbox">defaultMailbox</a>

Select the mailbox associated with this queue.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mailbox</td></tr><tr><td>description</td><td>Select the mailbox associated with this queue.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>defaultmailbox</td></tr></table>

### <a href=#entityImageId name="entityImageId">entityImageId</a>

For internal use only.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Entity Image Id</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entityimageid</td></tr></table>

### <a href=#isEmailAddressApprovedByO365Admin name="isEmailAddressApprovedByO365Admin">isEmailAddressApprovedByO365Admin</a>

Shows the status of approval of the email address by O365 Admin.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Address O365 Admin Approval Status</td></tr><tr><td>description</td><td>Shows the status of approval of the email address by O365 Admin.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isemailaddressapprovedbyo365admin</td></tr></table>

### <a href=#queueViewType name="queueViewType">queueViewType</a>

Select whether the queue is public or private. A public queue can be viewed by all. A private queue can be viewed only by the members added to the queue.  
First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type</td></tr><tr><td>description</td><td>Select whether the queue is public or private. A public queue can be viewed by all. A private queue can be viewed only by the members added to the queue.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>queueviewtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Public</td><td>0</td></tr><tr><td>en</td><td>Private</td><td>1</td></tr></table></td></tr></table>

### <a href=#queueViewType_display name="queueViewType_display">queueViewType_display</a>

First included in: applicationCommon/Queue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
