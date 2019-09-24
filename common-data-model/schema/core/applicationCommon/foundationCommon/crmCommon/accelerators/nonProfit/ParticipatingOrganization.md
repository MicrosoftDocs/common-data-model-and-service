---
title: ParticipatingOrganization - Common Data Model | Microsoft Docs
description: Organization involved with the delivery framework
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Participating Organization

Organization involved with the delivery framework  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/ParticipatingOrganization.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/nonProfit/ParticipatingOrganization  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="ParticipatingOrganization.md" target="_blank">nonProfit/ParticipatingOrganization</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="ParticipatingOrganization.md" target="_blank">nonProfit/ParticipatingOrganization</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="ParticipatingOrganization.md" target="_blank">nonProfit/ParticipatingOrganization</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="ParticipatingOrganization.md" target="_blank">nonProfit/ParticipatingOrganization</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="ParticipatingOrganization.md" target="_blank">nonProfit/ParticipatingOrganization</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="ParticipatingOrganization.md" target="_blank">nonProfit/ParticipatingOrganization</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="ParticipatingOrganization.md" target="_blank">nonProfit/ParticipatingOrganization</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="ParticipatingOrganization.md" target="_blank">nonProfit/ParticipatingOrganization</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="ParticipatingOrganization.md" target="_blank">nonProfit/ParticipatingOrganization</a>|
|[ownerId](#ownerId)|Owner Id|<a href="ParticipatingOrganization.md" target="_blank">nonProfit/ParticipatingOrganization</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="ParticipatingOrganization.md" target="_blank">nonProfit/ParticipatingOrganization</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="ParticipatingOrganization.md" target="_blank">nonProfit/ParticipatingOrganization</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="ParticipatingOrganization.md" target="_blank">nonProfit/ParticipatingOrganization</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="ParticipatingOrganization.md" target="_blank">nonProfit/ParticipatingOrganization</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="ParticipatingOrganization.md" target="_blank">nonProfit/ParticipatingOrganization</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="ParticipatingOrganization.md" target="_blank">nonProfit/ParticipatingOrganization</a>|
|[participatingOrganizationId](#participatingOrganizationId)|Unique identifier for entity instances|<a href="ParticipatingOrganization.md" target="_blank">nonProfit/ParticipatingOrganization</a>|
|[stateCode](#stateCode)|Status of the Participating Organization|<a href="ParticipatingOrganization.md" target="_blank">nonProfit/ParticipatingOrganization</a>|
|[stateCode_display](#stateCode_display)||<a href="ParticipatingOrganization.md" target="_blank">nonProfit/ParticipatingOrganization</a>|
|[statusCode](#statusCode)|Reason for the status of the Participating Organization|<a href="ParticipatingOrganization.md" target="_blank">nonProfit/ParticipatingOrganization</a>|
|[statusCode_display](#statusCode_display)||<a href="ParticipatingOrganization.md" target="_blank">nonProfit/ParticipatingOrganization</a>|
|[name](#name)|The name of the custom entity.|<a href="ParticipatingOrganization.md" target="_blank">nonProfit/ParticipatingOrganization</a>|
|[accountid](#accountid)|Unique identifier for Account associated with Participating Organization.|<a href="ParticipatingOrganization.md" target="_blank">nonProfit/ParticipatingOrganization</a>|
|[CRSChannelId](#CRSChannelId)|CRS channel|<a href="ParticipatingOrganization.md" target="_blank">nonProfit/ParticipatingOrganization</a>|
|[organizationRole](#organizationRole)|IATI codes for the role of an organization within a delivery framework|<a href="ParticipatingOrganization.md" target="_blank">nonProfit/ParticipatingOrganization</a>|
|[organizationRole_display](#organizationRole_display)||<a href="ParticipatingOrganization.md" target="_blank">nonProfit/ParticipatingOrganization</a>|
|[participatingOrganizationActivityId](#participatingOrganizationActivityId)|A valid activity identifier published by the participating organization which points to the activity that it has published to IATI that describes its role in this activity|<a href="ParticipatingOrganization.md" target="_blank">nonProfit/ParticipatingOrganization</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: nonProfit/ParticipatingOrganization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: nonProfit/ParticipatingOrganization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: nonProfit/ParticipatingOrganization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: nonProfit/ParticipatingOrganization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: nonProfit/ParticipatingOrganization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: nonProfit/ParticipatingOrganization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: nonProfit/ParticipatingOrganization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: nonProfit/ParticipatingOrganization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: nonProfit/ParticipatingOrganization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: nonProfit/ParticipatingOrganization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: nonProfit/ParticipatingOrganization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: nonProfit/ParticipatingOrganization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: nonProfit/ParticipatingOrganization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: nonProfit/ParticipatingOrganization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: nonProfit/ParticipatingOrganization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: nonProfit/ParticipatingOrganization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#participatingOrganizationId name="participatingOrganizationId">participatingOrganizationId</a>

Unique identifier for entity instances  
First included in: nonProfit/ParticipatingOrganization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Participating Organization</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msiati_participatingorganizationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Participating Organization  
First included in: nonProfit/ParticipatingOrganization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Participating Organization</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: nonProfit/ParticipatingOrganization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Participating Organization  
First included in: nonProfit/ParticipatingOrganization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Participating Organization</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: nonProfit/ParticipatingOrganization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: nonProfit/ParticipatingOrganization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_name</td></tr></table>

### <a href=#accountid name="accountid">accountid</a>

Unique identifier for Account associated with Participating Organization.  
First included in: nonProfit/ParticipatingOrganization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account</td></tr><tr><td>description</td><td>Unique identifier for Account associated with Participating Organization.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_accountid</td></tr></table>

### <a href=#CRSChannelId name="CRSChannelId">CRSChannelId</a>

CRS channel  
First included in: nonProfit/ParticipatingOrganization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>CRS Channel</td></tr><tr><td>description</td><td>CRS channel</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_crschannelid</td></tr></table>

### <a href=#organizationRole name="organizationRole">organizationRole</a>

IATI codes for the role of an organization within a delivery framework  
First included in: nonProfit/ParticipatingOrganization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Role</td></tr><tr><td>description</td><td>IATI codes for the role of an organization within a delivery framework</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_organizationrole</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Funding</td><td>453490001</td></tr><tr><td>en</td><td>Accountable</td><td>453490002</td></tr><tr><td>en</td><td>Extending</td><td>453490003</td></tr><tr><td>en</td><td>Implementing</td><td>453490004</td></tr></table></td></tr></table>

### <a href=#organizationRole_display name="organizationRole_display">organizationRole_display</a>

First included in: nonProfit/ParticipatingOrganization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#participatingOrganizationActivityId name="participatingOrganizationActivityId">participatingOrganizationActivityId</a>

A valid activity identifier published by the participating organization which points to the activity that it has published to IATI that describes its role in this activity  
First included in: nonProfit/ParticipatingOrganization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Participating Organization Activity Id</td></tr><tr><td>description</td><td>A valid activity identifier published by the participating organization which points to the activity that it has published to IATI that describes its role in this activity</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_participatingorganizationactivity</td></tr></table>
