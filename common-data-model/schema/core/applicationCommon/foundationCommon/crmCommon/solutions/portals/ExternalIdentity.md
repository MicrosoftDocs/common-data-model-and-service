---
title: ExternalIdentity - Common Data Model | Microsoft Docs
description: This describes the ExternalIdentity entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/5/2019
ms.author: nebanfic
---

# External Identity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/portals/ExternalIdentity.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/portals/ExternalIdentity  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[externalIdentityId](#externalIdentityId)|Shows the entity instances.|<a href="ExternalIdentity.md" target="_blank">portals/ExternalIdentity</a>|
|[createdOn](#createdOn)|Shows the date and time when the record was created.|<a href="ExternalIdentity.md" target="_blank">portals/ExternalIdentity</a>|
|[createdBy](#createdBy)|Shows the user who created the record.|<a href="ExternalIdentity.md" target="_blank">portals/ExternalIdentity</a>|
|[modifiedOn](#modifiedOn)|Shows the date and time when the record was modified.|<a href="ExternalIdentity.md" target="_blank">portals/ExternalIdentity</a>|
|[modifiedBy](#modifiedBy)|Shows the user who modified the record.|<a href="ExternalIdentity.md" target="_blank">portals/ExternalIdentity</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows the delegate user who created the record.|<a href="ExternalIdentity.md" target="_blank">portals/ExternalIdentity</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows the delegate user who modified the record.|<a href="ExternalIdentity.md" target="_blank">portals/ExternalIdentity</a>|
|[organizationId](#organizationId)|Shows the organization.|<a href="ExternalIdentity.md" target="_blank">portals/ExternalIdentity</a>|
|[stateCode](#stateCode)|Shows whether the external identity is active or inactive. Inactive records are read-only and can't be edited unless they are reactivated.|<a href="ExternalIdentity.md" target="_blank">portals/ExternalIdentity</a>|
|[stateCode_display](#stateCode_display)||<a href="ExternalIdentity.md" target="_blank">portals/ExternalIdentity</a>|
|[statusCode](#statusCode)|Select the external identity's status.|<a href="ExternalIdentity.md" target="_blank">portals/ExternalIdentity</a>|
|[statusCode_display](#statusCode_display)||<a href="ExternalIdentity.md" target="_blank">portals/ExternalIdentity</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="ExternalIdentity.md" target="_blank">portals/ExternalIdentity</a>|
|[importSequenceNumber](#importSequenceNumber)|Shows the sequence number of the import that created this record.|<a href="ExternalIdentity.md" target="_blank">portals/ExternalIdentity</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Shows the date and time that the record was migrated.|<a href="ExternalIdentity.md" target="_blank">portals/ExternalIdentity</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="ExternalIdentity.md" target="_blank">portals/ExternalIdentity</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Shows the time zone code that was in use when the record was created.|<a href="ExternalIdentity.md" target="_blank">portals/ExternalIdentity</a>|
|[userName](#userName)|Shows the name of the custom entity.|<a href="ExternalIdentity.md" target="_blank">portals/ExternalIdentity</a>|
|[contactId](#contactId)|Unique identifier for Contact associated with External Identity.|<a href="ExternalIdentity.md" target="_blank">portals/ExternalIdentity</a>|
|[identityProviderName](#identityProviderName)||<a href="ExternalIdentity.md" target="_blank">portals/ExternalIdentity</a>|

### <a href=#externalIdentityId name="externalIdentityId">externalIdentityId</a>

Shows the entity instances.  
First included in: portals/ExternalIdentity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>External Identity</td></tr><tr><td>description</td><td>Shows the entity instances.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>adx_externalidentityid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Shows the date and time when the record was created.  
First included in: portals/ExternalIdentity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Shows the date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows the user who created the record.  
First included in: portals/ExternalIdentity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Shows the date and time when the record was modified.  
First included in: portals/ExternalIdentity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Shows the date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows the user who modified the record.  
First included in: portals/ExternalIdentity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows the delegate user who created the record.  
First included in: portals/ExternalIdentity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows the delegate user who modified the record.  
First included in: portals/ExternalIdentity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Shows the organization.  
First included in: portals/ExternalIdentity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization ID</td></tr><tr><td>description</td><td>Shows the organization.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the external identity is active or inactive. Inactive records are read-only and can't be edited unless they are reactivated.  
First included in: portals/ExternalIdentity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows whether the external identity is active or inactive. Inactive records are read-only and can't be edited unless they are reactivated.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: portals/ExternalIdentity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the external identity's status.  
First included in: portals/ExternalIdentity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the external identity's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: portals/ExternalIdentity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: portals/ExternalIdentity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Shows the sequence number of the import that created this record.  
First included in: portals/ExternalIdentity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Shows the sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Shows the date and time that the record was migrated.  
First included in: portals/ExternalIdentity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Shows the date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: portals/ExternalIdentity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Shows the time zone code that was in use when the record was created.  
First included in: portals/ExternalIdentity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Shows the time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#userName name="userName">userName</a>

Shows the name of the custom entity.  
First included in: portals/ExternalIdentity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>User Name</td></tr><tr><td>description</td><td>Shows the name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_username</td></tr></table>

### <a href=#contactId name="contactId">contactId</a>

Unique identifier for Contact associated with External Identity.  
First included in: portals/ExternalIdentity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>description</td><td>Unique identifier for Contact associated with External Identity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_contactid</td></tr></table>

### <a href=#identityProviderName name="identityProviderName">identityProviderName</a>

First included in: portals/ExternalIdentity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Identity Provider</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>400</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_identityprovidername</td></tr></table>
