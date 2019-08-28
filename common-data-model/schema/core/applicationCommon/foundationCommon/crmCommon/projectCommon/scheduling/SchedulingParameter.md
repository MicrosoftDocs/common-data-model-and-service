---
title: SchedulingParameter - Common Data Model | Microsoft Docs
description: Scheduling Parameters
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Scheduling Parameter

Scheduling Parameters  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/scheduling/SchedulingParameter.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/scheduling/SchedulingParameter  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[schedulingParameterId](#schedulingParameterId)|A unique identifier for an entity instance.|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[organizationId](#organizationId)|Unique identifier for the organization|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[stateCode](#stateCode)|Status of the Scheduling Parameter|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[stateCode_display](#stateCode_display)||<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[statusCode](#statusCode)|Reason for the status of the Scheduling Parameter|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[statusCode_display](#statusCode_display)||<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[name](#name)|The name of the custom entity.|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[advancedSettings](#advancedSettings)|For internal use|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[backgroundJobsConfiguration](#backgroundJobsConfiguration)|Configuration that defines operations, which will be executed in background periodically (internal use only)|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[enableOptimizer](#enableOptimizer)|Determines if scheduling optimization is enabled.|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[connectToMaps](#connectToMaps)|Determines if the mapping provider will be used for map location and distance calculations.|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[customGeoLatitudeField](#customGeoLatitudeField)|Shows the logical name of the latitude field to be used by geolocations.|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[customGeoLocationEntity](#customGeoLocationEntity)|Shows the logical name of custom entity to be used for geolocations.|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[customGeoLongitudeField](#customGeoLongitudeField)|Shows the logical name of the longitude field to be used for geolocations.|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[customGeoResourceField](#customGeoResourceField)|Shows the logical name of the resource field to be used for geolocations.|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[customGeoTimestampField](#customGeoTimestampField)|Shows the logical name of the timestamp field to be used for geolocations.|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[defaultRadiusUnit](#defaultRadiusUnit)||<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[defaultRadiusUnit_display](#defaultRadiusUnit_display)||<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[defaultRadiusValue](#defaultRadiusValue)||<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[disableSanitizingHTMLTemplates](#disableSanitizingHTMLTemplates)|Disable Sanitizing HTML Templates on the Schedule Board|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[enableCustomGeoLocation](#enableCustomGeoLocation)|Determines if a custom entity will be used as a source of geo locations for resources to be displayed in the map view.|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[geoLocationExpiresAfterXMinutes](#geoLocationExpiresAfterXMinutes)||<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[geoLocationRefreshIntervalSeconds](#geoLocationRefreshIntervalSeconds)||<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[mapApiKey](#mapApiKey)|Api key for map|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[SAAutoFilterServiceTerritory](#SAAutoFilterServiceTerritory)|Determines if the schedule assistant should automatically filter results based on the requirement territory.|<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|
|[scheduleBoardRefreshIntervalSeconds](#scheduleBoardRefreshIntervalSeconds)||<a href="SchedulingParameter.md" target="_blank">scheduling/SchedulingParameter</a>|

### <a href=#schedulingParameterId name="schedulingParameterId">schedulingParameterId</a>

A unique identifier for an entity instance.  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scheduling Parameter</td></tr><tr><td>description</td><td>A unique identifier for an entity instance.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_schedulingparameterid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for the organization  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier for the organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Scheduling Parameter  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Scheduling Parameter</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Scheduling Parameter  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Scheduling Parameter</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_name</td></tr></table>

### <a href=#advancedSettings name="advancedSettings">advancedSettings</a>

For internal use  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Advanced Settings</td></tr><tr><td>description</td><td>For internal use</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1048576</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_advancedsettings</td></tr></table>

### <a href=#backgroundJobsConfiguration name="backgroundJobsConfiguration">backgroundJobsConfiguration</a>

Configuration that defines operations, which will be executed in background periodically (internal use only)  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Background Jobs Configuration</td></tr><tr><td>description</td><td>Configuration that defines operations, which will be executed in background periodically (internal use only)</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>3000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_backgroundjobsconfiguration</td></tr></table>

### <a href=#enableOptimizer name="enableOptimizer">enableOptimizer</a>

Determines if scheduling optimization is enabled.  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Optimizer</td></tr><tr><td>description</td><td>Determines if scheduling optimization is enabled.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_enableoptimizer</td></tr></table>

### <a href=#connectToMaps name="connectToMaps">connectToMaps</a>

Determines if the mapping provider will be used for map location and distance calculations.  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Connect to Maps</td></tr><tr><td>description</td><td>Determines if the mapping provider will be used for map location and distance calculations.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_connecttomaps</td></tr></table>

### <a href=#customGeoLatitudeField name="customGeoLatitudeField">customGeoLatitudeField</a>

Shows the logical name of the latitude field to be used by geolocations.  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Custom Geo Latitude Field</td></tr><tr><td>description</td><td>Shows the logical name of the latitude field to be used by geolocations.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_customgeolatitudefield</td></tr></table>

### <a href=#customGeoLocationEntity name="customGeoLocationEntity">customGeoLocationEntity</a>

Shows the logical name of custom entity to be used for geolocations.  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Custom Geo Location Entity</td></tr><tr><td>description</td><td>Shows the logical name of custom entity to be used for geolocations.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_customgeolocationentity</td></tr></table>

### <a href=#customGeoLongitudeField name="customGeoLongitudeField">customGeoLongitudeField</a>

Shows the logical name of the longitude field to be used for geolocations.  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Custom Geo Longitude Field</td></tr><tr><td>description</td><td>Shows the logical name of the longitude field to be used for geolocations.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_customgeolongitudefield</td></tr></table>

### <a href=#customGeoResourceField name="customGeoResourceField">customGeoResourceField</a>

Shows the logical name of the resource field to be used for geolocations.  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Custom Geo Resource Field</td></tr><tr><td>description</td><td>Shows the logical name of the resource field to be used for geolocations.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_customgeoresourcefield</td></tr></table>

### <a href=#customGeoTimestampField name="customGeoTimestampField">customGeoTimestampField</a>

Shows the logical name of the timestamp field to be used for geolocations.  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Custom Geo Timestamp Field</td></tr><tr><td>description</td><td>Shows the logical name of the timestamp field to be used for geolocations.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_customgeotimestampfield</td></tr></table>

### <a href=#defaultRadiusUnit name="defaultRadiusUnit">defaultRadiusUnit</a>

First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default Radius Unit</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_defaultradiusunit</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Miles</td><td>192350000</td></tr><tr><td>en</td><td>KM</td><td>192350001</td></tr></table></td></tr></table>

### <a href=#defaultRadiusUnit_display name="defaultRadiusUnit_display">defaultRadiusUnit_display</a>

First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#defaultRadiusValue name="defaultRadiusValue">defaultRadiusValue</a>

First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default Radius Value</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_defaultradiusvalue</td></tr></table>

### <a href=#disableSanitizingHTMLTemplates name="disableSanitizingHTMLTemplates">disableSanitizingHTMLTemplates</a>

Disable Sanitizing HTML Templates on the Schedule Board  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Disable Sanitizing HTML Templates</td></tr><tr><td>description</td><td>Disable Sanitizing HTML Templates on the Schedule Board</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_disablesanitizinghtmltemplates</td></tr></table>

### <a href=#enableCustomGeoLocation name="enableCustomGeoLocation">enableCustomGeoLocation</a>

Determines if a custom entity will be used as a source of geo locations for resources to be displayed in the map view.  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Custom Geo Location</td></tr><tr><td>description</td><td>Determines if a custom entity will be used as a source of geo locations for resources to be displayed in the map view.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_enablecustomgeolocation</td></tr></table>

### <a href=#geoLocationExpiresAfterXMinutes name="geoLocationExpiresAfterXMinutes">geoLocationExpiresAfterXMinutes</a>

First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Geo Location Expires After X Minutes</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_geolocationexpiresafterxminutes</td></tr></table>

### <a href=#geoLocationRefreshIntervalSeconds name="geoLocationRefreshIntervalSeconds">geoLocationRefreshIntervalSeconds</a>

First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Geo Location Refresh Interval Seconds</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_geolocationrefreshintervalseconds</td></tr></table>

### <a href=#mapApiKey name="mapApiKey">mapApiKey</a>

Api key for map  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Map Api Key</td></tr><tr><td>description</td><td>Api key for map</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_mapapikey</td></tr></table>

### <a href=#SAAutoFilterServiceTerritory name="SAAutoFilterServiceTerritory">SAAutoFilterServiceTerritory</a>

Determines if the schedule assistant should automatically filter results based on the requirement territory.  
First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Auto Filter Service Territory</td></tr><tr><td>description</td><td>Determines if the schedule assistant should automatically filter results based on the requirement territory.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_saautofilterserviceterritory</td></tr></table>

### <a href=#scheduleBoardRefreshIntervalSeconds name="scheduleBoardRefreshIntervalSeconds">scheduleBoardRefreshIntervalSeconds</a>

First included in: scheduling/SchedulingParameter (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>The refresh rate of the schedule board.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_scheduleboardrefreshintervalseconds</td></tr></table>
