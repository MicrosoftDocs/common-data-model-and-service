---
title: ResourceAssignment - Common Data Model | Microsoft Docs
description: Entity used to keep track of resource assignment header information  on tasks.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Resource Assignment

Entity used to keep track of resource assignment header information  on tasks.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/ResourceAssignment.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/ResourceAssignment  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[ownerId](#ownerId)|Owner Id|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[resourceAssignmentId](#resourceAssignmentId)|Unique identifier for entity instances|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[stateCode](#stateCode)|Status of the Resource Assignment|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[stateCode_display](#stateCode_display)||<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[statusCode](#statusCode)|Reason for the status of the Resource Assignment|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[statusCode_display](#statusCode_display)||<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[name](#name)|Type the name of the custom entity.|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[bookableResourceId](#bookableResourceId)|Shows the resource.|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[bookingStatusId](#bookingStatusId)|Booking Status|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[commitType](#commitType)|Select the commitment type of the assignment (hard or soft).|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[commitType_display](#commitType_display)||<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[fromDate](#fromDate)|Enter the date a resource is assigned from.|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[hours](#hours)|Enter the number of hours for which a resource is assigned.|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[MSProjectClientId](#MSProjectClientId)|id for resource assignment in ms project|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[plannedCost](#plannedCost)|Planned Cost Amount|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[plannedcostBase](#plannedcostBase)|Value of the Planned Cost in base currency.|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[plannedCostContour](#plannedCostContour)|Serialized planned cost contour|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[plannedSales](#plannedSales)|Planned Sales Amount|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[plannedSalesBase](#plannedSalesBase)|Value of the Planned Sales in base currency.|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[plannedSalesContour](#plannedSalesContour)|Serialized planned sales contour|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[plannedWork](#plannedWork)|Serialized planned work schedule for assigned resource|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[projectId](#projectId)|Select the project for which the resource is assigned.|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[projectTeam](#projectTeam)|Unique identifier for Project Team Member associated with Resource Assignment.|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[taskId](#taskId)|Select the task for which the resource is assigned to.|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[toDate](#toDate)|Enter the end date until which a resource is assigned.|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|
|[userResourceId](#userResourceId)|Select the user whose capacity is assigned.|<a href="ResourceAssignment.md" target="_blank">projectServiceAutomation/ResourceAssignment</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#resourceAssignmentId name="resourceAssignmentId">resourceAssignmentId</a>

Unique identifier for entity instances  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource Assignment</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_resourceassignmentid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Resource Assignment  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Resource Assignment</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Resource Assignment  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Resource Assignment</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

Type the name of the custom entity.  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type the name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_name</td></tr></table>

### <a href=#bookableResourceId name="bookableResourceId">bookableResourceId</a>

Shows the resource.  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bookable Resource</td></tr><tr><td>description</td><td>Shows the resource.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_bookableresourceid</td></tr></table>

### <a href=#bookingStatusId name="bookingStatusId">bookingStatusId</a>

Booking Status  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Booking Status (Deprecated in v3.0)</td></tr><tr><td>description</td><td>Booking Status</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_bookingstatusid</td></tr></table>

### <a href=#commitType name="commitType">commitType</a>

Select the commitment type of the assignment (hard or soft).  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Commit Type (Deprecated in v3.0)</td></tr><tr><td>description</td><td>Select the commitment type of the assignment (hard or soft).</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_committype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Canceled</td><td>192350004</td></tr><tr><td>en</td><td>None</td><td>192350000</td></tr><tr><td>en</td><td>Hard Book</td><td>192350001</td></tr><tr><td>en</td><td>Soft Book</td><td>192350002</td></tr><tr><td>en</td><td>Proposed</td><td>192350003</td></tr></table></td></tr></table>

### <a href=#commitType_display name="commitType_display">commitType_display</a>

First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#fromDate name="fromDate">fromDate</a>

Enter the date a resource is assigned from.  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>From Date</td></tr><tr><td>description</td><td>Enter the date a resource is assigned from.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_fromdate</td></tr></table>

### <a href=#hours name="hours">hours</a>

Enter the number of hours for which a resource is assigned.  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Hours</td></tr><tr><td>description</td><td>Enter the number of hours for which a resource is assigned.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_hours</td></tr></table>

### <a href=#MSProjectClientId name="MSProjectClientId">MSProjectClientId</a>

id for resource assignment in ms project  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>MS Project Client Id</td></tr><tr><td>description</td><td>id for resource assignment in ms project</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_msprojectclientid</td></tr></table>

### <a href=#plannedCost name="plannedCost">plannedCost</a>

Planned Cost Amount  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Planned Cost</td></tr><tr><td>description</td><td>Planned Cost Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_plannedcost</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#plannedcostBase name="plannedcostBase">plannedcostBase</a>

Value of the Planned Cost in base currency.  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Planned Cost (Base)</td></tr><tr><td>description</td><td>Value of the Planned Cost in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_plannedcost_base</td></tr></table>

### <a href=#plannedCostContour name="plannedCostContour">plannedCostContour</a>

Serialized planned cost contour  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Planned Cost Contour</td></tr><tr><td>description</td><td>Serialized planned cost contour</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1048576</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_plannedcostcontour</td></tr></table>

### <a href=#plannedSales name="plannedSales">plannedSales</a>

Planned Sales Amount  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Planned Sales</td></tr><tr><td>description</td><td>Planned Sales Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_plannedsales</td></tr></table>

### <a href=#plannedSalesBase name="plannedSalesBase">plannedSalesBase</a>

Value of the Planned Sales in base currency.  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Planned Sales (Base)</td></tr><tr><td>description</td><td>Value of the Planned Sales in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_plannedsales_base</td></tr></table>

### <a href=#plannedSalesContour name="plannedSalesContour">plannedSalesContour</a>

Serialized planned sales contour  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Planned Sales Contour</td></tr><tr><td>description</td><td>Serialized planned sales contour</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1048576</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_plannedsalescontour</td></tr></table>

### <a href=#plannedWork name="plannedWork">plannedWork</a>

Serialized planned work schedule for assigned resource  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Planned Work</td></tr><tr><td>description</td><td>Serialized planned work schedule for assigned resource</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1048576</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_plannedwork</td></tr></table>

### <a href=#projectId name="projectId">projectId</a>

Select the project for which the resource is assigned.  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project</td></tr><tr><td>description</td><td>Select the project for which the resource is assigned.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_projectid</td></tr></table>

### <a href=#projectTeam name="projectTeam">projectTeam</a>

Unique identifier for Project Team Member associated with Resource Assignment.  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Team</td></tr><tr><td>description</td><td>Unique identifier for Project Team Member associated with Resource Assignment.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_projectteamid</td></tr></table>

### <a href=#taskId name="taskId">taskId</a>

Select the task for which the resource is assigned to.  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Task</td></tr><tr><td>description</td><td>Select the task for which the resource is assigned to.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_taskid</td></tr></table>

### <a href=#toDate name="toDate">toDate</a>

Enter the end date until which a resource is assigned.  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>To Date</td></tr><tr><td>description</td><td>Enter the end date until which a resource is assigned.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_todate</td></tr></table>

### <a href=#userResourceId name="userResourceId">userResourceId</a>

Select the user whose capacity is assigned.  
First included in: projectServiceAutomation/ResourceAssignment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource</td></tr><tr><td>description</td><td>Select the user whose capacity is assigned.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_userresourceid</td></tr></table>
