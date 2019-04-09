---
title: ConnectionRole - Common Data Model | Microsoft Docs
description: Role describing a relationship between a two records.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Connection Role

Role describing a relationship between a two records.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/ConnectionRole.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /ConnectionRole  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[connectionRoleId](#connectionRoleId)|Unique identifier of the connection role.|<a href="ConnectionRole.md" target="_blank">applicationCommon/ConnectionRole</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who last modified the connection role.|<a href="ConnectionRole.md" target="_blank">applicationCommon/ConnectionRole</a>|
|[modifiedOn](#modifiedOn)|Date and time when the connection role was last modified.|<a href="ConnectionRole.md" target="_blank">applicationCommon/ConnectionRole</a>|
|[name](#name)|Name of the connection role.|<a href="ConnectionRole.md" target="_blank">applicationCommon/ConnectionRole</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="ConnectionRole.md" target="_blank">applicationCommon/ConnectionRole</a>|
|[stateCode](#stateCode)|Status of the connection role.|<a href="ConnectionRole.md" target="_blank">applicationCommon/ConnectionRole</a>|
|[stateCode_display](#stateCode_display)||<a href="ConnectionRole.md" target="_blank">applicationCommon/ConnectionRole</a>|
|[statusCode](#statusCode)|Reason for the status of the connection role.|<a href="ConnectionRole.md" target="_blank">applicationCommon/ConnectionRole</a>|
|[statusCode_display](#statusCode_display)||<a href="ConnectionRole.md" target="_blank">applicationCommon/ConnectionRole</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the relationship role.|<a href="ConnectionRole.md" target="_blank">applicationCommon/ConnectionRole</a>|
|[category](#category)|Categories for connection roles.|<a href="ConnectionRole.md" target="_blank">applicationCommon/ConnectionRole</a>|
|[category_display](#category_display)||<a href="ConnectionRole.md" target="_blank">applicationCommon/ConnectionRole</a>|
|[organizationId](#organizationId)|Unique identifier of the organization that this connection role belongs to.|<a href="ConnectionRole.md" target="_blank">applicationCommon/ConnectionRole</a>|
|[description](#description)|Description of the connection role.|<a href="ConnectionRole.md" target="_blank">applicationCommon/ConnectionRole</a>|
|[createdOn](#createdOn)|Date and time when the connection role was created.|<a href="ConnectionRole.md" target="_blank">applicationCommon/ConnectionRole</a>|
|[versionNumber](#versionNumber)|Version number of the connection role.|<a href="ConnectionRole.md" target="_blank">applicationCommon/ConnectionRole</a>|
|[solutionId](#solutionId)|Unique identifier of the associated solution.|<a href="ConnectionRole.md" target="_blank">applicationCommon/ConnectionRole</a>|
|[componentState](#componentState)|State of the component.|<a href="ConnectionRole.md" target="_blank">applicationCommon/ConnectionRole</a>|
|[componentState_display](#componentState_display)||<a href="ConnectionRole.md" target="_blank">applicationCommon/ConnectionRole</a>|
|[overwriteTime](#overwriteTime)|Date and time when the record was last overwritten.|<a href="ConnectionRole.md" target="_blank">applicationCommon/ConnectionRole</a>|
|[connectionRoleIdUnique](#connectionRoleIdUnique)|Unique identifier of the published or unpublished connection role record.|<a href="ConnectionRole.md" target="_blank">applicationCommon/ConnectionRole</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the relationship role.|<a href="ConnectionRole.md" target="_blank">applicationCommon/ConnectionRole</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the relationship role.|<a href="ConnectionRole.md" target="_blank">applicationCommon/ConnectionRole</a>|
|[isManaged](#isManaged)|Indicates whether the solution component is part of a managed solution.|<a href="ConnectionRole.md" target="_blank">applicationCommon/ConnectionRole</a>|
|[isCustomizable](#isCustomizable)|Information that specifies whether this component can be customized.|<a href="ConnectionRole.md" target="_blank">applicationCommon/ConnectionRole</a>|
|[introducedVersion](#introducedVersion)|Version in which the form is introduced.|<a href="ConnectionRole.md" target="_blank">applicationCommon/ConnectionRole</a>|

### <a href=#connectionRoleId name="connectionRoleId">connectionRoleId</a>

Unique identifier of the connection role.  
First included in: applicationCommon/ConnectionRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Connection Role</td></tr><tr><td>description</td><td>Unique identifier of the connection role.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>connectionroleid</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who last modified the connection role.  
First included in: applicationCommon/ConnectionRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who last modified the connection role.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the connection role was last modified.  
First included in: applicationCommon/ConnectionRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the connection role was last modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#name name="name">name</a>

Name of the connection role.  
First included in: applicationCommon/ConnectionRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Name of the connection role.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: applicationCommon/ConnectionRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the connection role.  
First included in: applicationCommon/ConnectionRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the connection role.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: applicationCommon/ConnectionRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the connection role.  
First included in: applicationCommon/ConnectionRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the connection role.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: applicationCommon/ConnectionRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the relationship role.  
First included in: applicationCommon/ConnectionRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the relationship role.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#category name="category">category</a>

Categories for connection roles.  
First included in: applicationCommon/ConnectionRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Connection Role Category</td></tr><tr><td>description</td><td>Categories for connection roles.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>category</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Business</td><td>1</td></tr><tr><td>en</td><td>Family</td><td>2</td></tr><tr><td>en</td><td>Social</td><td>3</td></tr><tr><td>en</td><td>Sales</td><td>4</td></tr><tr><td>en</td><td>Other</td><td>5</td></tr><tr><td>en</td><td>Stakeholder</td><td>1000</td></tr><tr><td>en</td><td>Sales Team</td><td>1001</td></tr><tr><td>en</td><td>Service</td><td>1002</td></tr></table></td></tr></table>

### <a href=#category_display name="category_display">category_display</a>

First included in: applicationCommon/ConnectionRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier of the organization that this connection role belongs to.  
First included in: applicationCommon/ConnectionRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization</td></tr><tr><td>description</td><td>Unique identifier of the organization that this connection role belongs to.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#description name="description">description</a>

Description of the connection role.  
First included in: applicationCommon/ConnectionRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the connection role.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the connection role was created.  
First included in: applicationCommon/ConnectionRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the connection role was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version number of the connection role.  
First included in: applicationCommon/ConnectionRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version number of the connection role.</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#solutionId name="solutionId">solutionId</a>

Unique identifier of the associated solution.  
First included in: applicationCommon/ConnectionRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Solution</td></tr><tr><td>description</td><td>Unique identifier of the associated solution.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>solutionid</td></tr></table>

### <a href=#componentState name="componentState">componentState</a>

State of the component.  
First included in: applicationCommon/ConnectionRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Component State</td></tr><tr><td>description</td><td>State of the component.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>componentstate</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Published</td><td>0</td></tr><tr><td>en</td><td>Unpublished</td><td>1</td></tr><tr><td>en</td><td>Deleted</td><td>2</td></tr><tr><td>en</td><td>Deleted Unpublished</td><td>3</td></tr></table></td></tr></table>

### <a href=#componentState_display name="componentState_display">componentState_display</a>

First included in: applicationCommon/ConnectionRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#overwriteTime name="overwriteTime">overwriteTime</a>

Date and time when the record was last overwritten.  
First included in: applicationCommon/ConnectionRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Overwritten On</td></tr><tr><td>description</td><td>Date and time when the record was last overwritten.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>overwritetime</td></tr></table>

### <a href=#connectionRoleIdUnique name="connectionRoleIdUnique">connectionRoleIdUnique</a>

Unique identifier of the published or unpublished connection role record.  
First included in: applicationCommon/ConnectionRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unique ID</td></tr><tr><td>description</td><td>Unique identifier of the published or unpublished connection role record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>connectionroleidunique</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the relationship role.  
First included in: applicationCommon/ConnectionRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the relationship role.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the relationship role.  
First included in: applicationCommon/ConnectionRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the relationship role.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#isManaged name="isManaged">isManaged</a>

Indicates whether the solution component is part of a managed solution.  
First included in: applicationCommon/ConnectionRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State</td></tr><tr><td>description</td><td>Indicates whether the solution component is part of a managed solution.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>ismanaged</td></tr></table>

### <a href=#isCustomizable name="isCustomizable">isCustomizable</a>

Information that specifies whether this component can be customized.  
First included in: applicationCommon/ConnectionRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customizable</td></tr><tr><td>description</td><td>Information that specifies whether this component can be customized.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>iscustomizable</td></tr></table>

### <a href=#introducedVersion name="introducedVersion">introducedVersion</a>

Version in which the form is introduced.  
First included in: applicationCommon/ConnectionRole (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Introduced Version</td></tr><tr><td>description</td><td>Version in which the form is introduced.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>48</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>introducedversion</td></tr></table>
