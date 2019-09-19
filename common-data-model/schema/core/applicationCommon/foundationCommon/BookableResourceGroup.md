---
title: BookableResourceGroup - Common Data Model | Microsoft Docs
description: Associates resources with resource groups that they are a member of.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Bookable Resource Group

Associates resources with resource groups that they are a member of.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/BookableResourceGroup.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/BookableResourceGroup  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|
|[ownerId](#ownerId)|Owner Id|<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|
|[bookableResourceGroupId](#bookableResourceGroupId)|Unique identifier of the resource group.|<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|
|[name](#name)|Type the name of the resource group.|<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|
|[childResource](#childResource)|The child resource that is a part of the group.|<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|
|[fromDate](#fromDate)|Enter the group membership start date.|<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|
|[parentResource](#parentResource)|The parent resource that is a part of the group.|<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|
|[stateCode](#stateCode)|Status of the Bookable Resource Group|<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|
|[stateCode_display](#stateCode_display)||<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|
|[statusCode](#statusCode)|Reason for the status of the Bookable Resource Group|<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|
|[statusCode_display](#statusCode_display)||<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|
|[toDate](#toDate)|Enter the group membership end date.|<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the bookableresourcegroup with respect to the base currency.|<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Exchange rate for the currency associated with the BookableResourceGroup with respect to the base currency.|<a href="BookableResourceGroup.md" target="_blank">foundationCommon/BookableResourceGroup</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#bookableResourceGroupId name="bookableResourceGroupId">bookableResourceGroupId</a>

Unique identifier of the resource group.  
First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bookable Resource Group</td></tr><tr><td>description</td><td>Unique identifier of the resource group.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>bookableresourcegroupid</td></tr></table>

### <a href=#name name="name">name</a>

Type the name of the resource group.  
First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type the name of the resource group.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#childResource name="childResource">childResource</a>

The child resource that is a part of the group.  
First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Child Resource</td></tr><tr><td>description</td><td>The child resource that is a part of the group.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>childresource</td></tr></table>

### <a href=#fromDate name="fromDate">fromDate</a>

Enter the group membership start date.  
First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>From Date</td></tr><tr><td>description</td><td>Enter the group membership start date.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>fromdate</td></tr></table>

### <a href=#parentResource name="parentResource">parentResource</a>

The parent resource that is a part of the group.  
First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent Resource</td></tr><tr><td>description</td><td>The parent resource that is a part of the group.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>parentresource</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Bookable Resource Group  
First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Bookable Resource Group</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Bookable Resource Group  
First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Bookable Resource Group</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#toDate name="toDate">toDate</a>

Enter the group membership end date.  
First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>To Date</td></tr><tr><td>description</td><td>Enter the group membership end date.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>todate</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the bookableresourcegroup with respect to the base currency.  
First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ExchangeRate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the bookableresourcegroup with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Exchange rate for the currency associated with the BookableResourceGroup with respect to the base currency.  
First included in: foundationCommon/BookableResourceGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the BookableResourceGroup with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>
