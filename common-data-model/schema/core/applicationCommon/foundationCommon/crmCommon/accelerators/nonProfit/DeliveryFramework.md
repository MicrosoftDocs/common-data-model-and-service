---
title: DeliveryFramework - Common Data Model | Microsoft Docs
description: A Delivery Framework is a Management Unit of work defined by the organization or entity doing the work.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# Delivery Framework

A Delivery Framework is a Management Unit of work defined by the organization or entity doing the work.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/DeliveryFramework.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/nonProfit/DeliveryFramework  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[ownerId](#ownerId)|Owner Id|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[deliveryFrameworkId](#deliveryFrameworkId)|Unique identifier for entity instances|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[stateCode](#stateCode)|Status of the Delivery Framework|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[stateCode_display](#stateCode_display)||<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[statusCode](#statusCode)|Reason for the status of the Delivery Framework|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[statusCode_display](#statusCode_display)||<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[name](#name)|The name of the custom entity.|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[account](#account)|Account|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[deliveryFrameworkType](#deliveryFrameworkType)|The type of Framwork, i.e. Program, Project, Initiative, Activity|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[deliveryFrameworkType_display](#deliveryFrameworkType_display)||<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[description](#description)|Description of the Framework.|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[endDate](#endDate)|End date of the Framework.|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[goal](#goal)|Indicates the goal of the Framework.|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[objectiveid](#objectiveid)|Objective|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[parentDeliveryFrameworkId](#parentDeliveryFrameworkId)|Parent DeliveryFramework|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[scope](#scope)|Scope of the Framework.|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[scope_display](#scope_display)||<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[startDate](#startDate)|Start date off the Framework.|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[status](#status)|Status|<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|
|[status_display](#status_display)||<a href="DeliveryFramework.md" target="_blank">nonProfit/DeliveryFramework</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#deliveryFrameworkId name="deliveryFrameworkId">deliveryFrameworkId</a>

Unique identifier for entity instances  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery Framework</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msnfp_deliveryframeworkid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Delivery Framework  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Delivery Framework</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Delivery Framework  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Delivery Framework</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_name</td></tr></table>

### <a href=#account name="account">account</a>

Account  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account</td></tr><tr><td>description</td><td>Account</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_account</td></tr></table>

### <a href=#deliveryFrameworkType name="deliveryFrameworkType">deliveryFrameworkType</a>

The type of Framwork, i.e. Program, Project, Initiative, Activity  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery Framework Type</td></tr><tr><td>description</td><td>The type of Framwork, i.e. Program, Project, Initiative, Activity</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_deliveryframeworktype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Program</td><td>844060000</td></tr><tr><td>en</td><td>Project</td><td>844060001</td></tr><tr><td>en</td><td>Action</td><td>844060002</td></tr></table></td></tr></table>

### <a href=#deliveryFrameworkType_display name="deliveryFrameworkType_display">deliveryFrameworkType_display</a>

First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#description name="description">description</a>

Description of the Framework.  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the Framework.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_description</td></tr></table>

### <a href=#endDate name="endDate">endDate</a>

End date of the Framework.  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End Date</td></tr><tr><td>description</td><td>End date of the Framework.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_enddate</td></tr></table>

### <a href=#goal name="goal">goal</a>

Indicates the goal of the Framework.  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Goal</td></tr><tr><td>description</td><td>Indicates the goal of the Framework.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_goal</td></tr></table>

### <a href=#objectiveid name="objectiveid">objectiveid</a>

Objective  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Objective</td></tr><tr><td>description</td><td>Objective</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_objectiveid</td></tr></table>

### <a href=#parentDeliveryFrameworkId name="parentDeliveryFrameworkId">parentDeliveryFrameworkId</a>

Parent DeliveryFramework  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent Delivery Framework</td></tr><tr><td>description</td><td>Parent DeliveryFramework</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_parentdeliveryframeworkid</td></tr></table>

### <a href=#scope name="scope">scope</a>

Scope of the Framework.  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scope</td></tr><tr><td>description</td><td>Scope of the Framework.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_scope</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Global</td><td>844060000</td></tr><tr><td>en</td><td>Regional</td><td>844060001</td></tr><tr><td>en</td><td>Multi-National</td><td>844060002</td></tr><tr><td>en</td><td>National</td><td>844060003</td></tr><tr><td>en</td><td>Sub-national: Multi-first-level administrative areas</td><td>844060004</td></tr><tr><td>en</td><td>Sub-national: Multi second-level administrative area</td><td>844060005</td></tr><tr><td>en</td><td>Sub-national: Single second-level administrative area</td><td>844060006</td></tr><tr><td>en</td><td>Single Location</td><td>844060007</td></tr></table></td></tr></table>

### <a href=#scope_display name="scope_display">scope_display</a>

First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#startDate name="startDate">startDate</a>

Start date off the Framework.  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date</td></tr><tr><td>description</td><td>Start date off the Framework.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_startdate</td></tr></table>

### <a href=#status name="status">status</a>

Status  
First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_status</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Pipeline/Identification</td><td>844060000</td></tr><tr><td>en</td><td>Implementation</td><td>844060001</td></tr><tr><td>en</td><td>Completion</td><td>844060002</td></tr><tr><td>en</td><td>POst-Completion</td><td>844060004</td></tr><tr><td>en</td><td>Cancelled</td><td>844060005</td></tr><tr><td>en</td><td>Suspended</td><td>844060006</td></tr></table></td></tr></table>

### <a href=#status_display name="status_display">status_display</a>

First included in: nonProfit/DeliveryFramework (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
