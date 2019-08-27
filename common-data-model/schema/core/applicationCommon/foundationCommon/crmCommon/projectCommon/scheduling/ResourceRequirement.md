---
title: ResourceRequirement - Common Data Model | Microsoft Docs
description: This describes the ResourceRequirement entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Resource Requirement

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/scheduling/ResourceRequirement.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/scheduling/ResourceRequirement  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[ownerId](#ownerId)|Owner Id|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[resourceRequirementId](#resourceRequirementId)|Unique identifier for entity instances|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[stateCode](#stateCode)|Status of the Resource Requirement|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[stateCode_display](#stateCode_display)||<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[statusCode](#statusCode)|Reason for the status of the Resource Requirement|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[statusCode_display](#statusCode_display)||<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[name](#name)|The name of the custom entity.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[allocationMethod](#allocationMethod)|Select the allocation method to be used for creating requirement distribution over a time period.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[allocationMethod_display](#allocationMethod_display)||<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[appointmentRequirementId](#appointmentRequirementId)|Unique identifier for Appointment associated with Resource Requirement.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[bookingSetupMetadataId](#bookingSetupMetadataId)|A unique identifier for the booking setup metadata that is associated with a resource requirement.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[calendarId](#calendarId)|The calendar that will be used for a resource requirement|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[duration](#duration)|Duration of total minutes required|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[effort](#effort)|Effort that's required from resource capacity|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[fromDate](#fromDate)||<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[fulfilledDuration](#fulfilledDuration)|The fulfilled duration, in minutes.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[internalFlags](#internalFlags)|For internal use only.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[isPrimary](#isPrimary)||<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[isTemplate](#isTemplate)|Is template requirement|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[latitude](#latitude)|The latitude to use for the location of a requirement.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[longitude](#longitude)|The longitude to use for the location of a requirement.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[percentage](#percentage)|Enter the percentage of the calendar capacity required.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[poolType](#poolType)||<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[poolType_display](#poolType_display)||<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[priority](#priority)|Priority of the requirement. To be taken into consideration while scheduling resources|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[proposedDuration](#proposedDuration)||<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[remainingDuration](#remainingDuration)||<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[requirementGroupControlViewId](#requirementGroupControlViewId)|The requirement group control view id of the resource requirement entity. This field will has value only when the entity is inside the requirement group control.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[requirementGroup](#requirementGroup)|Requirement Group|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[requirementRelationship](#requirementRelationship)|Requirement Relationship|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[resourceType](#resourceType)||<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[resourceType_display](#resourceType_display)||<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[status](#status)|Requirement Status|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[sortOptions](#sortOptions)|Sort option string field of resource requirement|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[templateRequirementId](#templateRequirementId)|template requirement id if requirement is created from template|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[territory](#territory)||<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[timeFromPromised](#timeFromPromised)|Enter the starting range of the time promised to the account that incidents will be resolved.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[timeGroup](#timeGroup)||<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[timeToPromised](#timeToPromised)|Enter the ending range of the time promised to the account that incidents will be resolved.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[timeWindowEnd](#timeWindowEnd)||<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[timeWindowStart](#timeWindowStart)||<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[toDate](#toDate)|End date of requirement period|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[workHourTemplate](#workHourTemplate)|The working hours for a requirement.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[workLocation](#workLocation)||<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[workLocation_display](#workLocation_display)||<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[city](#city)|Type the city where the resource is required.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[costPrice](#costPrice)|Enter the cost price of the resource required.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[costPriceBase](#costPriceBase)|Value of the Cost Price in base currency.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[country](#country)|Type the country/region where the resource is required.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[deprecatedFulfilledHours](#deprecatedFulfilledHours)|Enter the hours fulfilled against requirement when the requirement status is fulfilled.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[deprecatedHours](#deprecatedHours)|Enter the number of hours for which a requirement is required.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[projectId](#projectId)|Select the project for which the resource is required.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[quantity](#quantity)|Enter the number of resources required.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[requestStatus](#requestStatus)|The status of the resource request associated with this requirement.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[deprecatedRole](#deprecatedRole)|Select the required role.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[stateOrProvince](#stateOrProvince)|Type the state/province where the resource is required.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[type](#type)|Select the type of resource requirement.|<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|
|[type_display](#type_display)||<a href="ResourceRequirement.md" target="_blank">scheduling/ResourceRequirement</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#resourceRequirementId name="resourceRequirementId">resourceRequirementId</a>

Unique identifier for entity instances  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource Requirement</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_resourcerequirementid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Resource Requirement  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Resource Requirement</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Resource Requirement  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Resource Requirement</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_name</td></tr></table>

### <a href=#allocationMethod name="allocationMethod">allocationMethod</a>

Select the allocation method to be used for creating requirement distribution over a time period.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allocation Method</td></tr><tr><td>description</td><td>Select the allocation method to be used for creating requirement distribution over a time period.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_allocationmethod</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>None</td><td>192350000</td></tr><tr><td>en</td><td>Full capacity</td><td>192350001</td></tr><tr><td>en</td><td>Percentage capacity</td><td>192350004</td></tr><tr><td>en</td><td>Distribute evenly</td><td>192350003</td></tr><tr><td>en</td><td>Front load</td><td>192350005</td></tr></table></td></tr></table>

### <a href=#allocationMethod_display name="allocationMethod_display">allocationMethod_display</a>

First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#appointmentRequirementId name="appointmentRequirementId">appointmentRequirementId</a>

Unique identifier for Appointment associated with Resource Requirement.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Appointment Requirement</td></tr><tr><td>description</td><td>Unique identifier for Appointment associated with Resource Requirement.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_appointmentrequirementid</td></tr></table>

### <a href=#bookingSetupMetadataId name="bookingSetupMetadataId">bookingSetupMetadataId</a>

A unique identifier for the booking setup metadata that is associated with a resource requirement.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Booking Setup Metadata</td></tr><tr><td>description</td><td>A unique identifier for the booking setup metadata that is associated with a resource requirement.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_bookingsetupmetadataid</td></tr></table>

### <a href=#calendarId name="calendarId">calendarId</a>

The calendar that will be used for a resource requirement  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Calendar Id</td></tr><tr><td>description</td><td>The calendar that will be used for a resource requirement</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_calendarid</td></tr></table>

### <a href=#duration name="duration">duration</a>

Duration of total minutes required  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Duration</td></tr><tr><td>description</td><td>Duration of total minutes required</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_duration</td></tr></table>

### <a href=#effort name="effort">effort</a>

Effort that's required from resource capacity  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Effort</td></tr><tr><td>description</td><td>Effort that's required from resource capacity</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0.0001</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_effort</td></tr></table>

### <a href=#fromDate name="fromDate">fromDate</a>

First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>From Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_fromdate</td></tr></table>

### <a href=#fulfilledDuration name="fulfilledDuration">fulfilledDuration</a>

The fulfilled duration, in minutes.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fulfilled Duration</td></tr><tr><td>description</td><td>The fulfilled duration, in minutes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_fulfilledduration</td></tr></table>

### <a href=#internalFlags name="internalFlags">internalFlags</a>

For internal use only.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Internal Flags</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1048576</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_internalflags</td></tr></table>

### <a href=#isPrimary name="isPrimary">isPrimary</a>

First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Primary</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_isprimary</td></tr></table>

### <a href=#isTemplate name="isTemplate">isTemplate</a>

Is template requirement  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Template</td></tr><tr><td>description</td><td>Is template requirement</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_istemplate</td></tr></table>

### <a href=#latitude name="latitude">latitude</a>

The latitude to use for the location of a requirement.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Latitude</td></tr><tr><td>description</td><td>The latitude to use for the location of a requirement.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>90</td></tr><tr><td>minimumValue</td><td>-90</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_latitude</td></tr></table>

### <a href=#longitude name="longitude">longitude</a>

The longitude to use for the location of a requirement.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Longitude</td></tr><tr><td>description</td><td>The longitude to use for the location of a requirement.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>180</td></tr><tr><td>minimumValue</td><td>-180</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_longitude</td></tr></table>

### <a href=#percentage name="percentage">percentage</a>

Enter the percentage of the calendar capacity required.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Percentage</td></tr><tr><td>description</td><td>Enter the percentage of the calendar capacity required.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_percentage</td></tr></table>

### <a href=#poolType name="poolType">poolType</a>

First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pool Type</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_pooltype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Account</td><td>192350000</td></tr><tr><td>en</td><td>Contact</td><td>192350001</td></tr><tr><td>en</td><td>User</td><td>192350002</td></tr><tr><td>en</td><td>Equipment</td><td>192350003</td></tr><tr><td>en</td><td>Facility</td><td>192350004</td></tr></table></td></tr></table>

### <a href=#poolType_display name="poolType_display">poolType_display</a>

First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#priority name="priority">priority</a>

Priority of the requirement. To be taken into consideration while scheduling resources  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Priority</td></tr><tr><td>description</td><td>Priority of the requirement. To be taken into consideration while scheduling resources</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_priority</td></tr></table>

### <a href=#proposedDuration name="proposedDuration">proposedDuration</a>

First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Proposed Duration</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_proposedduration</td></tr></table>

### <a href=#remainingDuration name="remainingDuration">remainingDuration</a>

First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Remaining Duration</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_remainingduration</td></tr></table>

### <a href=#requirementGroupControlViewId name="requirementGroupControlViewId">requirementGroupControlViewId</a>

The requirement group control view id of the resource requirement entity. This field will has value only when the entity is inside the requirement group control.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requirement Group Control View Id</td></tr><tr><td>description</td><td>The requirement group control view id of the resource requirement entity. This field will has value only when the entity is inside the requirement group control.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_requirementgroupcontrolviewid</td></tr></table>

### <a href=#requirementGroup name="requirementGroup">requirementGroup</a>

Requirement Group  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requirement Group</td></tr><tr><td>description</td><td>Requirement Group</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_requirementgroupid</td></tr></table>

### <a href=#requirementRelationship name="requirementRelationship">requirementRelationship</a>

Requirement Relationship  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requirement Relationship</td></tr><tr><td>description</td><td>Requirement Relationship</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_requirementrelationshipid</td></tr></table>

### <a href=#resourceType name="resourceType">resourceType</a>

First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource Type</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourcetype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#resourceType_display name="resourceType_display">resourceType_display</a>

First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#status name="status">status</a>

Requirement Status  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Requirement Status</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_status</td></tr></table>

### <a href=#sortOptions name="sortOptions">sortOptions</a>

Sort option string field of resource requirement  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sort Options</td></tr><tr><td>description</td><td>Sort option string field of resource requirement</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_sortoptions</td></tr></table>

### <a href=#templateRequirementId name="templateRequirementId">templateRequirementId</a>

template requirement id if requirement is created from template  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Template Requirement Id</td></tr><tr><td>description</td><td>template requirement id if requirement is created from template</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_templaterequirementid</td></tr></table>

### <a href=#territory name="territory">territory</a>

First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Territory</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_territory</td></tr></table>

### <a href=#timeFromPromised name="timeFromPromised">timeFromPromised</a>

Enter the starting range of the time promised to the account that incidents will be resolved.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time From Promised</td></tr><tr><td>description</td><td>Enter the starting range of the time promised to the account that incidents will be resolved.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_timefrompromised</td></tr></table>

### <a href=#timeGroup name="timeGroup">timeGroup</a>

First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fulfillment Preference</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_timegroup</td></tr></table>

### <a href=#timeToPromised name="timeToPromised">timeToPromised</a>

Enter the ending range of the time promised to the account that incidents will be resolved.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time To Promised</td></tr><tr><td>description</td><td>Enter the ending range of the time promised to the account that incidents will be resolved.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_timetopromised</td></tr></table>

### <a href=#timeWindowEnd name="timeWindowEnd">timeWindowEnd</a>

First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Window End</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_timewindowend</td></tr></table>

### <a href=#timeWindowStart name="timeWindowStart">timeWindowStart</a>

First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Window Start</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_timewindowstart</td></tr></table>

### <a href=#toDate name="toDate">toDate</a>

End date of requirement period  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>To Date</td></tr><tr><td>description</td><td>End date of requirement period</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_todate</td></tr></table>

### <a href=#workHourTemplate name="workHourTemplate">workHourTemplate</a>

The working hours for a requirement.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Work Hour Template</td></tr><tr><td>description</td><td>The working hours for a requirement.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_workhourtemplate</td></tr></table>

### <a href=#workLocation name="workLocation">workLocation</a>

First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Work Location</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_worklocation</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Onsite</td><td>690970000</td></tr><tr><td>en</td><td>Facility</td><td>690970001</td></tr><tr><td>en</td><td>Location Agnostic</td><td>690970002</td></tr></table></td></tr></table>

### <a href=#workLocation_display name="workLocation_display">workLocation_display</a>

First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#city name="city">city</a>

Type the city where the resource is required.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>City</td></tr><tr><td>description</td><td>Type the city where the resource is required.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_city</td></tr></table>

### <a href=#costPrice name="costPrice">costPrice</a>

Enter the cost price of the resource required.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost Price</td></tr><tr><td>description</td><td>Enter the cost price of the resource required.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_costprice</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#costPriceBase name="costPriceBase">costPriceBase</a>

Value of the Cost Price in base currency.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost Price (Base)</td></tr><tr><td>description</td><td>Value of the Cost Price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_costprice_base</td></tr></table>

### <a href=#country name="country">country</a>

Type the country/region where the resource is required.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country/Region</td></tr><tr><td>description</td><td>Type the country/region where the resource is required.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_country</td></tr></table>

### <a href=#deprecatedFulfilledHours name="deprecatedFulfilledHours">deprecatedFulfilledHours</a>

Enter the hours fulfilled against requirement when the requirement status is fulfilled.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fulfilled Hours (Deprecated)</td></tr><tr><td>description</td><td>Enter the hours fulfilled against requirement when the requirement status is fulfilled.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_fulfilledhours</td></tr></table>

### <a href=#deprecatedHours name="deprecatedHours">deprecatedHours</a>

Enter the number of hours for which a requirement is required.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Hours (Deprecated)</td></tr><tr><td>description</td><td>Enter the number of hours for which a requirement is required.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_hours</td></tr></table>

### <a href=#projectId name="projectId">projectId</a>

Select the project for which the resource is required.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project</td></tr><tr><td>description</td><td>Select the project for which the resource is required.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_projectid</td></tr></table>

### <a href=#quantity name="quantity">quantity</a>

Enter the number of resources required.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity (Deprecated in v3.0)</td></tr><tr><td>description</td><td>Enter the number of resources required.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_quantity</td></tr></table>

### <a href=#requestStatus name="requestStatus">requestStatus</a>

The status of the resource request associated with this requirement.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Request Status</td></tr><tr><td>description</td><td>The status of the resource request associated with this requirement.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_requeststatus</td></tr></table>

### <a href=#deprecatedRole name="deprecatedRole">deprecatedRole</a>

Select the required role.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Role (Deprecated)</td></tr><tr><td>description</td><td>Select the required role.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_roleid</td></tr></table>

### <a href=#stateOrProvince name="stateOrProvince">stateOrProvince</a>

Type the state/province where the resource is required.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State/Province</td></tr><tr><td>description</td><td>Type the state/province where the resource is required.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_stateorprovince</td></tr></table>

### <a href=#type name="type">type</a>

Select the type of resource requirement.  
First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type</td></tr><tr><td>description</td><td>Select the type of resource requirement.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_type</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>New</td><td>192350000</td></tr><tr><td>en</td><td>Extend</td><td>192350001</td></tr></table></td></tr></table>

### <a href=#type_display name="type_display">type_display</a>

First included in: scheduling/ResourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
