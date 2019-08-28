---
title: ScheduleBoardSetting - Common Data Model | Microsoft Docs
description: To store settings of SB by user & tabs
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Schedule Board Setting

To store settings of SB by user & tabs  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/scheduling/ScheduleBoardSetting.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/scheduling/ScheduleBoardSetting  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[ownerId](#ownerId)|Owner Id|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[scheduleBoardSettingId](#scheduleBoardSettingId)|Shows the entity instances.|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[stateCode](#stateCode)|Status of the Schedule Board Setting|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[stateCode_display](#stateCode_display)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[statusCode](#statusCode)|Reason for the status of the Schedule Board Setting|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[statusCode_display](#statusCode_display)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[tabName](#tabName)|Enter the tab name.|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[bookBasedOn](#bookBasedOn)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[customTabName](#customTabName)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[customTabWebResource](#customTabWebResource)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[filterLayout](#filterLayout)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[filterValues](#filterValues)|Storing filter values as Json string.|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[fullyBookedColor](#fullyBookedColor)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[hideCancelled](#hideCancelled)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[isPublic](#isPublic)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[isSynchronizeResources](#isSynchronizeResources)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[mapViewTabPlacement](#mapViewTabPlacement)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[notBookedColor](#notBookedColor)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[orderNumber](#orderNumber)|Tab index.|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[organizationalUnitTooltipsViewId](#organizationalUnitTooltipsViewId)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[organizationalUnitViewId](#organizationalUnitViewId)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[overbookedColor](#overbookedColor)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[partiallyBookedColor](#partiallyBookedColor)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[resourceCellTemplate](#resourceCellTemplate)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[retrieveResourcesQuery](#retrieveResourcesQuery)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[SAAvailableColor](#SAAvailableColor)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[SAAvailableIcon](#SAAvailableIcon)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[SAAvailableIconDefault](#SAAvailableIconDefault)|Is available icon inheriting from default setting.|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[SAPartiallyAvailableColor](#SAPartiallyAvailableColor)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[SAPartiallyAvailableIcon](#SAPartiallyAvailableIcon)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[SAPartiallyAvailableIconDefault](#SAPartiallyAvailableIconDefault)|Is partially available icon inheriting from default setting.|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[SAUnavailableColor](#SAUnavailableColor)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[SAUnavailableIcon](#SAUnavailableIcon)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[SAUnavailableIconDefault](#SAUnavailableIconDefault)|Is unavailable icon inheriting from default setting.|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[schedulerAlertsView](#schedulerAlertsView)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[schedulerResourceDetailsView](#schedulerResourceDetailsView)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[schedulerResourceTooltipView](#schedulerResourceTooltipView)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[settings](#settings)|Shows the settings as a JSON string.|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[shareType](#shareType)|Field is used to determine if Schedule Board Tab are Private, Public or Shareable|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[shareType_display](#shareType_display)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[unscheduledRequirementsViewId](#unscheduledRequirementsViewId)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[unscheduledWOPageRecCount](#unscheduledWOPageRecCount)|Shows the number of records to be displayed per page in 'Resource Requirement' section.|<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|
|[workingHoursColor](#workingHoursColor)||<a href="ScheduleBoardSetting.md" target="_blank">scheduling/ScheduleBoardSetting</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#scheduleBoardSettingId name="scheduleBoardSettingId">scheduleBoardSettingId</a>

Shows the entity instances.  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Schedule Board Setting</td></tr><tr><td>description</td><td>Shows the entity instances.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_scheduleboardsettingid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Schedule Board Setting  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Schedule Board Setting</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Schedule Board Setting  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Schedule Board Setting</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#tabName name="tabName">tabName</a>

Enter the tab name.  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tab name.</td></tr><tr><td>description</td><td>Enter the tab name.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_tabname</td></tr></table>

### <a href=#bookBasedOn name="bookBasedOn">bookBasedOn</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Book Based On</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_bookbasedon</td></tr></table>

### <a href=#customTabName name="customTabName">customTabName</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Custom Tab Name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_customtabname</td></tr></table>

### <a href=#customTabWebResource name="customTabWebResource">customTabWebResource</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Custom Tab Web Resource</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_customtabwebresource</td></tr></table>

### <a href=#filterLayout name="filterLayout">filterLayout</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Filter Layout</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_filterlayout</td></tr></table>

### <a href=#filterValues name="filterValues">filterValues</a>

Storing filter values as Json string.  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Filter Values</td></tr><tr><td>description</td><td>Storing filter values as Json string.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1048576</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_filtervalues</td></tr></table>

### <a href=#fullyBookedColor name="fullyBookedColor">fullyBookedColor</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fully Booked Color</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_fullybookedcolor</td></tr></table>

### <a href=#hideCancelled name="hideCancelled">hideCancelled</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Hide Canceled</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_hidecancelled</td></tr></table>

### <a href=#isPublic name="isPublic">isPublic</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Public (Deprecated)</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_ispublic</td></tr></table>

### <a href=#isSynchronizeResources name="isSynchronizeResources">isSynchronizeResources</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Synchronize Resources</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_issynchronizeresources</td></tr></table>

### <a href=#mapViewTabPlacement name="mapViewTabPlacement">mapViewTabPlacement</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Map View Tab Placement</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_mapviewtabplacement</td></tr></table>

### <a href=#notBookedColor name="notBookedColor">notBookedColor</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Not Booked Color</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_notbookedcolor</td></tr></table>

### <a href=#orderNumber name="orderNumber">orderNumber</a>

Tab index.  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Order Number</td></tr><tr><td>description</td><td>Tab index.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>100</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_ordernumber</td></tr></table>

### <a href=#organizationalUnitTooltipsViewId name="organizationalUnitTooltipsViewId">organizationalUnitTooltipsViewId</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organizational Unit Tooltips View Id</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_organizationalunittooltipsviewid</td></tr></table>

### <a href=#organizationalUnitViewId name="organizationalUnitViewId">organizationalUnitViewId</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organizational Unit View Id</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_organizationalunitviewid</td></tr></table>

### <a href=#overbookedColor name="overbookedColor">overbookedColor</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Overbooked Color</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_overbookedcolor</td></tr></table>

### <a href=#partiallyBookedColor name="partiallyBookedColor">partiallyBookedColor</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Partially Booked Color</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_partiallybookedcolor</td></tr></table>

### <a href=#resourceCellTemplate name="resourceCellTemplate">resourceCellTemplate</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource Cell Template</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourcecelltemplate</td></tr></table>

### <a href=#retrieveResourcesQuery name="retrieveResourcesQuery">retrieveResourcesQuery</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Retrieve Resources Query</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_retrieveresourcesquery</td></tr></table>

### <a href=#SAAvailableColor name="SAAvailableColor">SAAvailableColor</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SA Available Color</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_saavailablecolor</td></tr></table>

### <a href=#SAAvailableIcon name="SAAvailableIcon">SAAvailableIcon</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SA Available Icon</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>256</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_saavailableicon</td></tr></table>

### <a href=#SAAvailableIconDefault name="SAAvailableIconDefault">SAAvailableIconDefault</a>

Is available icon inheriting from default setting.  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SA Available Icon Default</td></tr><tr><td>description</td><td>Is available icon inheriting from default setting.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_saavailableicondefault</td></tr></table>

### <a href=#SAPartiallyAvailableColor name="SAPartiallyAvailableColor">SAPartiallyAvailableColor</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SA Partially Available Color</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_sapartiallyavailablecolor</td></tr></table>

### <a href=#SAPartiallyAvailableIcon name="SAPartiallyAvailableIcon">SAPartiallyAvailableIcon</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SA Partially Available Icon</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>256</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_sapartiallyavailableicon</td></tr></table>

### <a href=#SAPartiallyAvailableIconDefault name="SAPartiallyAvailableIconDefault">SAPartiallyAvailableIconDefault</a>

Is partially available icon inheriting from default setting.  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SA Partially Available Icon Default</td></tr><tr><td>description</td><td>Is partially available icon inheriting from default setting.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_sapartiallyavailableicondefault</td></tr></table>

### <a href=#SAUnavailableColor name="SAUnavailableColor">SAUnavailableColor</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SA Unavailable Color</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_saunavailablecolor</td></tr></table>

### <a href=#SAUnavailableIcon name="SAUnavailableIcon">SAUnavailableIcon</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SA Unavailable Icon</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>256</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_saunavailableicon</td></tr></table>

### <a href=#SAUnavailableIconDefault name="SAUnavailableIconDefault">SAUnavailableIconDefault</a>

Is unavailable icon inheriting from default setting.  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SA Unavailable Icon Default</td></tr><tr><td>description</td><td>Is unavailable icon inheriting from default setting.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_saunavailableicondefault</td></tr></table>

### <a href=#schedulerAlertsView name="schedulerAlertsView">schedulerAlertsView</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scheduler Alerts View</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_scheduleralertsview</td></tr></table>

### <a href=#schedulerResourceDetailsView name="schedulerResourceDetailsView">schedulerResourceDetailsView</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource Details View</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>40</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_schedulerresourcedetailsview</td></tr></table>

### <a href=#schedulerResourceTooltipView name="schedulerResourceTooltipView">schedulerResourceTooltipView</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource Tooltips View</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>40</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_schedulerresourcetooltipview</td></tr></table>

### <a href=#settings name="settings">settings</a>

Shows the settings as a JSON string.  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Settings</td></tr><tr><td>description</td><td>Shows the settings as a JSON string.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1048576</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_settings</td></tr></table>

### <a href=#shareType name="shareType">shareType</a>

Field is used to determine if Schedule Board Tab are Private, Public or Shareable  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Share Type</td></tr><tr><td>description</td><td>Field is used to determine if Schedule Board Tab are Private, Public or Shareable</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_sharetype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Everyone</td><td>192350000</td></tr><tr><td>en</td><td>Just me</td><td>192350001</td></tr><tr><td>en</td><td>Specific people</td><td>192350002</td></tr><tr><td>en</td><td>System</td><td>192350003</td></tr></table></td></tr></table>

### <a href=#shareType_display name="shareType_display">shareType_display</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#unscheduledRequirementsViewId name="unscheduledRequirementsViewId">unscheduledRequirementsViewId</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requirements View Id</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_unscheduledrequirementsviewid</td></tr></table>

### <a href=#unscheduledWOPageRecCount name="unscheduledWOPageRecCount">unscheduledWOPageRecCount</a>

Shows the number of records to be displayed per page in 'Resource Requirement' section.  
First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource Requirement View Page Record Count</td></tr><tr><td>description</td><td>Shows the number of records to be displayed per page in 'Resource Requirement' section.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_unscheduledwopagereccount</td></tr></table>

### <a href=#workingHoursColor name="workingHoursColor">workingHoursColor</a>

First included in: scheduling/ScheduleBoardSetting (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Working Hours Color</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_workinghourscolor</td></tr></table>
