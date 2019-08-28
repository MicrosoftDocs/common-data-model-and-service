---
title: RequirementRelationship - Common Data Model | Microsoft Docs
description: Relationship of requirements in the group
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Requirement Relationship

Relationship of requirements in the group  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/scheduling/RequirementRelationship.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/scheduling/RequirementRelationship  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[ownerId](#ownerId)|Owner Id|<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[requirementrelationshipId](#requirementrelationshipId)|Unique identifier for entity instances|<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[stateCode](#stateCode)|Status of the Requirement Relationship|<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[stateCode_display](#stateCode_display)||<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[statusCode](#statusCode)|Reason for the status of the Requirement Relationship|<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[statusCode_display](#statusCode_display)||<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[name](#name)|The name of the custom entity.|<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[minConditionCount](#minConditionCount)|Minimal Condition Count that needs get satisfied in Or relationship|<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[operator](#operator)||<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[operator_display](#operator_display)||<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[parentRequirementRelationship](#parentRequirementRelationship)|Parent Requirement Relationship|<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[resourceGroupings](#resourceGroupings)||<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[resourceGroupings_display](#resourceGroupings_display)||<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[requirementGroupControlViewId](#requirementGroupControlViewId)|The requirement group control view id of the requirement relationship entity. This field will has value only when the entity is inside the requirement group control.|<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|
|[requirementGroup](#requirementGroup)|Requirement Group|<a href="RequirementRelationship.md" target="_blank">scheduling/RequirementRelationship</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#requirementrelationshipId name="requirementrelationshipId">requirementrelationshipId</a>

Unique identifier for entity instances  
First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requirement Relationship</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_requirementrelationshipid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Requirement Relationship  
First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Requirement Relationship</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Requirement Relationship  
First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Requirement Relationship</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_name</td></tr></table>

### <a href=#minConditionCount name="minConditionCount">minConditionCount</a>

Minimal Condition Count that needs get satisfied in Or relationship  
First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Min Condition Count</td></tr><tr><td>description</td><td>Minimal Condition Count that needs get satisfied in Or relationship</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1024</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_minconditioncount</td></tr></table>

### <a href=#operator name="operator">operator</a>

First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Operator</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_operator</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>&&</td><td>192350000</td></tr><tr><td>en</td><td>||</td><td>192350001</td></tr></table></td></tr></table>

### <a href=#operator_display name="operator_display">operator_display</a>

First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#parentRequirementRelationship name="parentRequirementRelationship">parentRequirementRelationship</a>

Parent Requirement Relationship  
First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent Requirement Relationship</td></tr><tr><td>description</td><td>Parent Requirement Relationship</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_parentrequirementrelationshipid</td></tr></table>

### <a href=#resourceGroupings name="resourceGroupings">resourceGroupings</a>

First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Part of Same</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourcegroupings</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Organizational Unit</td><td>192350000</td></tr><tr><td>en</td><td>Related Resource Pools</td><td>192350001</td></tr><tr><td>en</td><td>Location</td><td>192350002</td></tr></table></td></tr></table>

### <a href=#resourceGroupings_display name="resourceGroupings_display">resourceGroupings_display</a>

First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#requirementGroupControlViewId name="requirementGroupControlViewId">requirementGroupControlViewId</a>

The requirement group control view id of the requirement relationship entity. This field will has value only when the entity is inside the requirement group control.  
First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requirement Group Control View Id</td></tr><tr><td>description</td><td>The requirement group control view id of the requirement relationship entity. This field will has value only when the entity is inside the requirement group control.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_requirementgroupcontrolviewid</td></tr></table>

### <a href=#requirementGroup name="requirementGroup">requirementGroup</a>

Requirement Group  
First included in: scheduling/RequirementRelationship (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requirement Group</td></tr><tr><td>description</td><td>Requirement Group</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_requirementgroupid</td></tr></table>
