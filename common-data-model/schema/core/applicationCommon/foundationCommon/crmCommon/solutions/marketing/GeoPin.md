---
title: GeoPin - Common Data Model | Microsoft Docs
description: This describes the GeoPin entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Geo Pin

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/GeoPin.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/GeoPin  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[ownerId](#ownerId)|Owner Id|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[geopinId](#geopinId)|Unique ID for entity instances.|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[stateCode](#stateCode)|Status of the geo pin.|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[stateCode_display](#stateCode_display)||<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[statusCode](#statusCode)|Geo-pin status reason|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[statusCode_display](#statusCode_display)||<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[name](#name)|The name of the custom entity.|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[campaignGeoPinsId](#campaignGeoPinsId)|Unique ID for the campaign associated with the geo pin.|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[centerLatitude](#centerLatitude)||<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[centerLongitude](#centerLongitude)||<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[city](#city)|City|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[contactGeoPinsId](#contactGeoPinsId)|Unique ID for the contact associated with the geo pin.|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[country](#country)|Country/Region|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[customerJourney](#customerJourney)||<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[marketingformGeoPinsId](#marketingformGeoPinsId)|Unique ID for the marketing form associated with the geo pin.|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[KPIEmailClickedCount](#KPIEmailClickedCount)||<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[KPIEmailOpenedCount](#KPIEmailOpenedCount)||<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[KPIRedirectLinkClickedCount](#KPIRedirectLinkClickedCount)||<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[KPIWebsiteClickedCount](#KPIWebsiteClickedCount)||<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[KPIWebsiteVisitedCount](#KPIWebsiteVisitedCount)||<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[kpiFormSubmittedCount](#kpiFormSubmittedCount)||<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[leadGeoPinsId](#leadGeoPinsId)|Unique ID for the lead associated with the geo pin.|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[marketingEmailGeoPinsId](#marketingEmailGeoPinsId)|Unique ID for the marketing email associated with the geo pin.|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[marketingPageGeoPinsId](#marketingPageGeoPinsId)|Unique ID for the marketing page associated with the geo pin.|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[northwestLatitude](#northwestLatitude)||<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[northwestLongitude](#northwestLongitude)||<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[postalCode](#postalCode)|Postal Code|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[redirectURLGeoPinsId](#redirectURLGeoPinsId)|Unique ID for the redirect URL associated with the geo pin.|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[requestBuilderService_mktgeopins](#requestBuilderService_mktgeopins)||<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[resultParserService_mktgeopins](#resultParserService_mktgeopins)||<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[serverIdMarketing](#serverIdMarketing)||<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[southeastLatitude](#southeastLatitude)||<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[southeastLongitude](#southeastLongitude)||<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[state](#state)|State|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|
|[websiteGeoPinsId](#websiteGeoPinsId)|Unique ID for the website associated with the geo pin.|<a href="GeoPin.md" target="_blank">marketing/GeoPin</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#geopinId name="geopinId">geopinId</a>

Unique ID for entity instances.  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Geo pin</td></tr><tr><td>description</td><td>Unique ID for entity instances.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyncrm_geopinid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the geo pin.  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the geo pin.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Geo-pin status reason  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status reason</td></tr><tr><td>description</td><td>Geo-pin status reason</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_name</td></tr></table>

### <a href=#campaignGeoPinsId name="campaignGeoPinsId">campaignGeoPinsId</a>

Unique ID for the campaign associated with the geo pin.  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Campaign geo pins</td></tr><tr><td>description</td><td>Unique ID for the campaign associated with the geo pin.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_campaigngeopinsid</td></tr></table>

### <a href=#centerLatitude name="centerLatitude">centerLatitude</a>

First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Center latitude</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_centerlatitude</td></tr></table>

### <a href=#centerLongitude name="centerLongitude">centerLongitude</a>

First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Center longitude</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_centerlongitude</td></tr></table>

### <a href=#city name="city">city</a>

City  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>City</td></tr><tr><td>description</td><td>City</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_city</td></tr></table>

### <a href=#contactGeoPinsId name="contactGeoPinsId">contactGeoPinsId</a>

Unique ID for the contact associated with the geo pin.  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact geo pins</td></tr><tr><td>description</td><td>Unique ID for the contact associated with the geo pin.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_contactgeopinsid</td></tr></table>

### <a href=#country name="country">country</a>

Country/Region  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country/Region</td></tr><tr><td>description</td><td>Country/Region</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_country</td></tr></table>

### <a href=#customerJourney name="customerJourney">customerJourney</a>

First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Journey</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_customerjourney</td></tr></table>

### <a href=#marketingformGeoPinsId name="marketingformGeoPinsId">marketingformGeoPinsId</a>

Unique ID for the marketing form associated with the geo pin.  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Marketing form geo pins</td></tr><tr><td>description</td><td>Unique ID for the marketing form associated with the geo pin.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_marketingformgeopinsid</td></tr></table>

### <a href=#KPIEmailClickedCount name="KPIEmailClickedCount">KPIEmailClickedCount</a>

First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>KPI email clicked count</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_kpi_email_clicked_count</td></tr></table>

### <a href=#KPIEmailOpenedCount name="KPIEmailOpenedCount">KPIEmailOpenedCount</a>

First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>KPI email opened count</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_kpi_email_opened_count</td></tr></table>

### <a href=#KPIRedirectLinkClickedCount name="KPIRedirectLinkClickedCount">KPIRedirectLinkClickedCount</a>

First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>KPI redirect link clicked count</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_kpi_redirect_link_clicked_count</td></tr></table>

### <a href=#KPIWebsiteClickedCount name="KPIWebsiteClickedCount">KPIWebsiteClickedCount</a>

First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>KPI website clicked count</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_kpi_website_clicked_count</td></tr></table>

### <a href=#KPIWebsiteVisitedCount name="KPIWebsiteVisitedCount">KPIWebsiteVisitedCount</a>

First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>KPI website visited count</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_kpi_website_visited_count</td></tr></table>

### <a href=#kpiFormSubmittedCount name="kpiFormSubmittedCount">kpiFormSubmittedCount</a>

First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_kpi_form_submitted_count</td></tr></table>

### <a href=#leadGeoPinsId name="leadGeoPinsId">leadGeoPinsId</a>

Unique ID for the lead associated with the geo pin.  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lead geo pins</td></tr><tr><td>description</td><td>Unique ID for the lead associated with the geo pin.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_leadgeopinsid</td></tr></table>

### <a href=#marketingEmailGeoPinsId name="marketingEmailGeoPinsId">marketingEmailGeoPinsId</a>

Unique ID for the marketing email associated with the geo pin.  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Marketing email geo pins</td></tr><tr><td>description</td><td>Unique ID for the marketing email associated with the geo pin.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_marketingemailgeopinsid</td></tr></table>

### <a href=#marketingPageGeoPinsId name="marketingPageGeoPinsId">marketingPageGeoPinsId</a>

Unique ID for the marketing page associated with the geo pin.  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Marketing page geo pins</td></tr><tr><td>description</td><td>Unique ID for the marketing page associated with the geo pin.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_marketingpagegeopinsid</td></tr></table>

### <a href=#northwestLatitude name="northwestLatitude">northwestLatitude</a>

First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Northwest latitude</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_northwestlatitude</td></tr></table>

### <a href=#northwestLongitude name="northwestLongitude">northwestLongitude</a>

First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Northwest longitude</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_northwestlongitude</td></tr></table>

### <a href=#postalCode name="postalCode">postalCode</a>

Postal Code  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Postal code</td></tr><tr><td>description</td><td>Postal Code</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_postalcode</td></tr></table>

### <a href=#redirectURLGeoPinsId name="redirectURLGeoPinsId">redirectURLGeoPinsId</a>

Unique ID for the redirect URL associated with the geo pin.  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Redirect URL geo pins</td></tr><tr><td>description</td><td>Unique ID for the redirect URL associated with the geo pin.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_redirecturlgeopinsid</td></tr></table>

### <a href=#requestBuilderService_mktgeopins name="requestBuilderService_mktgeopins">requestBuilderService_mktgeopins</a>

First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Marketing interactions</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_requestbuilderservice_mktgeopins</td></tr></table>

### <a href=#resultParserService_mktgeopins name="resultParserService_mktgeopins">resultParserService_mktgeopins</a>

First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Marketing interactions</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_resultparserservice_mktgeopins</td></tr></table>

### <a href=#serverIdMarketing name="serverIdMarketing">serverIdMarketing</a>

First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>serverId_marketing</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_serverid_marketing</td></tr></table>

### <a href=#southeastLatitude name="southeastLatitude">southeastLatitude</a>

First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Southeast latitude</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_southeastlatitude</td></tr></table>

### <a href=#southeastLongitude name="southeastLongitude">southeastLongitude</a>

First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Southeast longitude</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_southeastlongitude</td></tr></table>

### <a href=#state name="state">state</a>

State  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State</td></tr><tr><td>description</td><td>State</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_state</td></tr></table>

### <a href=#websiteGeoPinsId name="websiteGeoPinsId">websiteGeoPinsId</a>

Unique ID for the website associated with the geo pin.  
First included in: marketing/GeoPin (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Website geo pins</td></tr><tr><td>description</td><td>Unique ID for the website associated with the geo pin.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyncrm_websitegeopinsid</td></tr></table>
