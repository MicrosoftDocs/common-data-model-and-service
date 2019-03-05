---
title: SLA - Common Data Model | Microsoft Docs
description: Contains information about the tracked service-level KPIs for cases that belong to different customers.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/5/2019
ms.author: nebanfic
---

# SLA

Contains information about the tracked service-level KPIs for cases that belong to different customers.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/SLA.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /SLA  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[SLAId](#SLAId)|Unique identifier of the SLA.|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[name](#name)|Type a descriptive name of the service level agreement (SLA).|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[businessHoursId](#businessHoursId)|Choose the business hours for calculating SLA item timelines.|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[objectTypeCode](#objectTypeCode)|Choose the entity type that the SLA is defined.|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[objectTypeCode_display](#objectTypeCode_display)||<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[owningUser](#owningUser)|Unique identifier for the user that owns the record.|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[description](#description)|Type additional information to describe the SLA|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[changedAttributeList](#changedAttributeList)|Type additional information to describe the SLA|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[applicableFrom](#applicableFrom)|Select the field that specifies the date and time from which the SLA items will be calculated for the case record. For example, if you select the Case Created On field, SLA calculation will begin from the time the case is created. |<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[isDefault](#isDefault)|Tells whether this SLA is the default one.|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[createdOn](#createdOn)|Shows the date and time when the record was created. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[modifiedOn](#modifiedOn)|Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[exchangeRate](#exchangeRate)|Exchange rate between the currency associated with the SLA record and the base currency.|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[versionNumber](#versionNumber)|Version number of the SLA.|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the SLA record.|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[stateCode](#stateCode)|Shows whether the Service Level Agreement (SLA) is active or inactive.|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[stateCode_display](#stateCode_display)||<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[statusCode](#statusCode)|Select the status of the service level agreement (SLA).|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[statusCode_display](#statusCode_display)||<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[solutionId](#solutionId)|Unique identifier of the associated solution.|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[componentState](#componentState)|For internal use only.|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[componentState_display](#componentState_display)||<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[overwriteTime](#overwriteTime)|For internal use only.|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[isManaged](#isManaged)|For internal use only.|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[SLAIdUnique](#SLAIdUnique)|For internal use only.|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[ownerId](#ownerId)|Owner Id|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[applicableFromPickList](#applicableFromPickList)|Select the field that specifies the date and time from which the SLA items will be calculated. For example, if you select the Case Created On field, SLA calculation will begin from the time the case is created.|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[applicableFromPickList_display](#applicableFromPickList_display)||<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[workflowId](#workflowId)|Workflow associated with the SLA.|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[allowPauseResume](#allowPauseResume)|Select whether this SLA will allow pausing and resuming during the time calculation.|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[SLAType](#SLAType)|Select the type of service level agreement (SLA).|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[SLAType_display](#SLAType_display)||<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|
|[primaryEntityOTC](#primaryEntityOTC)|Shows the primary entity that the SLA has been created for.|<a href="SLA.md" target="_blank">applicationCommon/SLA</a>|

### <a href=#SLAId name="SLAId">SLAId</a>

Unique identifier of the SLA.  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SLA</td></tr><tr><td>description</td><td>Unique identifier of the SLA.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>slaid</td></tr></table>

### <a href=#name name="name">name</a>

Type a descriptive name of the service level agreement (SLA).  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type a descriptive name of the service level agreement (SLA).</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#businessHoursId name="businessHoursId">businessHoursId</a>

Choose the business hours for calculating SLA item timelines.  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Business Hours</td></tr><tr><td>description</td><td>Choose the business hours for calculating SLA item timelines.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>businesshoursid</td></tr></table>

### <a href=#objectTypeCode name="objectTypeCode">objectTypeCode</a>

Choose the entity type that the SLA is defined.  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Object Type Code</td></tr><tr><td>description</td><td>Choose the entity type that the SLA is defined.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>objecttypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>0</td></tr></table></td></tr></table>

### <a href=#objectTypeCode_display name="objectTypeCode_display">objectTypeCode_display</a>

First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier for the user that owns the record.  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier for the user that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#description name="description">description</a>

Type additional information to describe the SLA  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type additional information to describe the SLA</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#changedAttributeList name="changedAttributeList">changedAttributeList</a>

Type additional information to describe the SLA  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ChangedAttributeList</td></tr><tr><td>description</td><td>Type additional information to describe the SLA</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>changedattributelist</td></tr></table>

### <a href=#applicableFrom name="applicableFrom">applicableFrom</a>

Select the field that specifies the date and time from which the SLA items will be calculated for the case record. For example, if you select the Case Created On field, SLA calculation will begin from the time the case is created.   
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Applicable From</td></tr><tr><td>description</td><td>Select the field that specifies the date and time from which the SLA items will be calculated for the case record. For example, if you select the Case Created On field, SLA calculation will begin from the time the case is created. </td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>applicablefrom</td></tr></table>

### <a href=#isDefault name="isDefault">isDefault</a>

Tells whether this SLA is the default one.  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Default</td></tr><tr><td>description</td><td>Tells whether this SLA is the default one.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isdefault</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Shows the date and time when the record was created. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Shows the date and time when the record was created. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate between the currency associated with the SLA record and the base currency.  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate between the currency associated with the SLA record and the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version number of the SLA.  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version number of the SLA.</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the SLA record.  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the SLA record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the Service Level Agreement (SLA) is active or inactive.  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows whether the Service Level Agreement (SLA) is active or inactive.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Draft</td><td>0</td></tr><tr><td>en</td><td>Active</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the status of the service level agreement (SLA).  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the status of the service level agreement (SLA).</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Draft</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Active</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#solutionId name="solutionId">solutionId</a>

Unique identifier of the associated solution.  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Solution</td></tr><tr><td>description</td><td>Unique identifier of the associated solution.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>solutionid</td></tr></table>

### <a href=#componentState name="componentState">componentState</a>

For internal use only.  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Component State</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>componentstate</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Published</td><td>0</td></tr><tr><td>en</td><td>Unpublished</td><td>1</td></tr><tr><td>en</td><td>Deleted</td><td>2</td></tr><tr><td>en</td><td>Deleted Unpublished</td><td>3</td></tr></table></td></tr></table>

### <a href=#componentState_display name="componentState_display">componentState_display</a>

First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#overwriteTime name="overwriteTime">overwriteTime</a>

For internal use only.  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Overwrite Time</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>overwritetime</td></tr></table>

### <a href=#isManaged name="isManaged">isManaged</a>

For internal use only.  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Managed</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>ismanaged</td></tr></table>

### <a href=#SLAIdUnique name="SLAIdUnique">SLAIdUnique</a>

For internal use only.  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unique Id</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>slaidunique</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#applicableFromPickList name="applicableFromPickList">applicableFromPickList</a>

Select the field that specifies the date and time from which the SLA items will be calculated. For example, if you select the Case Created On field, SLA calculation will begin from the time the case is created.  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Applicable From</td></tr><tr><td>description</td><td>Select the field that specifies the date and time from which the SLA items will be calculated. For example, if you select the Case Created On field, SLA calculation will begin from the time the case is created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>applicablefrompicklist</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>No</td><td>1</td></tr><tr><td>en</td><td>Yes</td><td>2</td></tr></table></td></tr></table>

### <a href=#applicableFromPickList_display name="applicableFromPickList_display">applicableFromPickList_display</a>

First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#workflowId name="workflowId">workflowId</a>

Workflow associated with the SLA.  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Workflow ID</td></tr><tr><td>description</td><td>Workflow associated with the SLA.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>workflowid</td></tr></table>

### <a href=#allowPauseResume name="allowPauseResume">allowPauseResume</a>

Select whether this SLA will allow pausing and resuming during the time calculation.  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow Pause and Resume</td></tr><tr><td>description</td><td>Select whether this SLA will allow pausing and resuming during the time calculation.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>allowpauseresume</td></tr></table>

### <a href=#SLAType name="SLAType">SLAType</a>

Select the type of service level agreement (SLA).  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SLA Type</td></tr><tr><td>description</td><td>Select the type of service level agreement (SLA).</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>slatype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Standard</td><td>0</td></tr><tr><td>en</td><td>Enhanced</td><td>1</td></tr></table></td></tr></table>

### <a href=#SLAType_display name="SLAType_display">SLAType_display</a>

First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#primaryEntityOTC name="primaryEntityOTC">primaryEntityOTC</a>

Shows the primary entity that the SLA has been created for.  
First included in: applicationCommon/SLA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Primary Entity</td></tr><tr><td>description</td><td>Shows the primary entity that the SLA has been created for.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>sourceName</td><td>primaryentityotc</td></tr></table>
