---
title: Connection - Common Data Model | Microsoft Docs
description: Relationship between two entities.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Connection

Relationship between two entities.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/Connection.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- [/Connection](../../../../Connection.md "/core/applicationCommon/Connection.cdm.json/Connection")  
- /foundationCommon/crmCommon/solutions/marketing/Connection  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[owningUser](#owningUser)|Unique identifier of the user who owns the connection.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[statusCode](#statusCode)|Reason for the status of the connection.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[statusCode_display](#statusCode_display)||<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[connectionId](#connectionId)|Unique identifier of the connection.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[versionNumber](#versionNumber)|Version number of the connection.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[effectiveStart](#effectiveStart)|Enter the start date of the connection.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[isMaster](#isMaster)|Indicates that this is the master record.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[ownerId](#ownerId)|Owner Id|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[relatedConnectionId](#relatedConnectionId)|Unique identifier for the reciprocal connection record.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[description](#description)|Type additional information to describe the connection, such as the length or quality of the relationship.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Shows the business unit that the record owner belongs to.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[record2IdObjectTypeCode](#record2IdObjectTypeCode)|The name of the entity linked by record2Id|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[record2Id](#record2Id)|Unique identifier of the target record.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[record2RoleId](#record2RoleId)|Choose the secondary party's role or relationship with the primary party.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[effectiveEnd](#effectiveEnd)|Enter the end date of the connection.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[record1RoleId](#record1RoleId)|Choose the primary party's role or relationship with the second party.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[createdOn](#createdOn)|Shows the date and time when the record was created. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[modifiedOn](#modifiedOn)|Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[record1IdObjectTypeCode](#record1IdObjectTypeCode)|The name of the entity linked by record1Id|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[record1Id](#record1Id)|Unique identifier of the source record.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[stateCode](#stateCode)|Shows whether the connection is active or inactive. Inactive connections are read-only and can't be edited unless they are reactivated.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[stateCode_display](#stateCode_display)||<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[owningTeam](#owningTeam)|Unique identifier of the team who owns the connection.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[record2ObjectTypeCode](#record2ObjectTypeCode)|Shows the record type of the target record.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[record2ObjectTypeCode_display](#record2ObjectTypeCode_display)||<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[record1ObjectTypeCode](#record1ObjectTypeCode)|Shows the record type of the source record.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[record1ObjectTypeCode_display](#record1ObjectTypeCode_display)||<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[name](#name)|Name of the connection.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|
|[entityImageId](#entityImageId)|For internal use only.|<a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>|

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user who owns the connection.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user who owns the connection.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the connection.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the connection.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#connectionId name="connectionId">connectionId</a>

Unique identifier of the connection.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Connection</td></tr><tr><td>description</td><td>Unique identifier of the connection.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>connectionid</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version number of the connection.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version number of the connection.</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#effectiveStart name="effectiveStart">effectiveStart</a>

Enter the start date of the connection.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Starting</td></tr><tr><td>description</td><td>Enter the start date of the connection.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>effectivestart</td></tr></table>

### <a href=#isMaster name="isMaster">isMaster</a>

Indicates that this is the master record.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Master</td></tr><tr><td>description</td><td>Indicates that this is the master record.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>ismaster</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#relatedConnectionId name="relatedConnectionId">relatedConnectionId</a>

Unique identifier for the reciprocal connection record.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reciprocal Connection</td></tr><tr><td>description</td><td>Unique identifier for the reciprocal connection record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>relatedconnectionid</td></tr></table>

### <a href=#description name="description">description</a>

Type additional information to describe the connection, such as the length or quality of the relationship.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type additional information to describe the connection, such as the length or quality of the relationship.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Shows the business unit that the record owner belongs to.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Shows the business unit that the record owner belongs to.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#record2IdObjectTypeCode name="record2IdObjectTypeCode">record2IdObjectTypeCode</a>

The name of the entity linked by record2Id  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>record2Id Type</td></tr><tr><td>description</td><td>The name of the entity linked by record2Id</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>record2idobjecttypecode</td></tr></table>

### <a href=#record2Id name="record2Id">record2Id</a>

Unique identifier of the target record.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Connected To</td></tr><tr><td>description</td><td>Unique identifier of the target record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>record2id</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#record2RoleId name="record2RoleId">record2RoleId</a>

Choose the secondary party's role or relationship with the primary party.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Role (To)</td></tr><tr><td>description</td><td>Choose the secondary party's role or relationship with the primary party.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>record2roleid</td></tr></table>

### <a href=#effectiveEnd name="effectiveEnd">effectiveEnd</a>

Enter the end date of the connection.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ending</td></tr><tr><td>description</td><td>Enter the end date of the connection.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>effectiveend</td></tr></table>

### <a href=#record1RoleId name="record1RoleId">record1RoleId</a>

Choose the primary party's role or relationship with the second party.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Role (From)</td></tr><tr><td>description</td><td>Choose the primary party's role or relationship with the second party.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>record1roleid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Shows the date and time when the record was created. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Shows the date and time when the record was created. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#record1IdObjectTypeCode name="record1IdObjectTypeCode">record1IdObjectTypeCode</a>

The name of the entity linked by record1Id  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>record1Id Type</td></tr><tr><td>description</td><td>The name of the entity linked by record1Id</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>record1idobjecttypecode</td></tr></table>

### <a href=#record1Id name="record1Id">record1Id</a>

Unique identifier of the source record.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Connected From</td></tr><tr><td>description</td><td>Unique identifier of the source record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>record1id</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the connection is active or inactive. Inactive connections are read-only and can't be edited unless they are reactivated.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows whether the connection is active or inactive. Inactive connections are read-only and can't be edited unless they are reactivated.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier of the team who owns the connection.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier of the team who owns the connection.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#record2ObjectTypeCode name="record2ObjectTypeCode">record2ObjectTypeCode</a>

Shows the record type of the target record.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type (To)</td></tr><tr><td>description</td><td>Shows the record type of the target record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>record2objecttypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>0</td></tr></table></td></tr></table>

### <a href=#record2ObjectTypeCode_display name="record2ObjectTypeCode_display">record2ObjectTypeCode_display</a>

First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#record1ObjectTypeCode name="record1ObjectTypeCode">record1ObjectTypeCode</a>

Shows the record type of the source record.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type (From)</td></tr><tr><td>description</td><td>Shows the record type of the source record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>record1objecttypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>0</td></tr></table></td></tr></table>

### <a href=#record1ObjectTypeCode_display name="record1ObjectTypeCode_display">record1ObjectTypeCode_display</a>

First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

Name of the connection.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Connection Name</td></tr><tr><td>description</td><td>Name of the connection.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#entityImageId name="entityImageId">entityImageId</a>

For internal use only.  
First included in: <a href="../../../../Connection.md" target="_blank">applicationCommon/Connection</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Entity Image Id</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entityimageid</td></tr></table>
