---
title: Invitation - Common Data Model | Microsoft Docs
description: Send invitations to existing contacts or email addresses and assign them to web roles upon redemption.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Invitation

Send invitations to existing contacts or email addresses and assign them to web roles upon redemption.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/marketing/eventManagement/Invitation.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/marketing/eventManagement/Invitation  
- [/foundationCommon/crmCommon/solutions/portals/Invitation](../../portals/Invitation.md "/core/applicationCommon/foundationCommon/crmCommon/solutions/portals/Invitation.cdm.json/Invitation")  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[ownerId](#ownerId)|Owner Id|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[invitationId](#invitationId)|Shows the entity instance.|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[stateCode](#stateCode)|Status of the Invitation|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[stateCode_display](#stateCode_display)||<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[statusCode](#statusCode)|Select the invitation's status.|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[statusCode_display](#statusCode_display)||<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[name](#name)|Type the name of the custom entity.|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[assignToAccount](#assignToAccount)|An account record to assign the redeemed contact to.|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[expiryDate](#expiryDate)|The date the invitation is no longer valid for redemption.|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[invitationCode](#invitationCode)|Shows the user who is redeeming the invitation.|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[inviteContact](#inviteContact)|The contact to send an invitation to.|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[inviterContact](#inviterContact)|The contact that invited.|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[maximumRedemptions](#maximumRedemptions)||<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[redeemedContact](#redeemedContact)|The contact associated with the redemption of this invitation.|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[redemptions](#redemptions)|The current number of times this invitation has been redeemed.|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[redemptionWorkflow](#redemptionWorkflow)|A workflow to execute on the redeeming contact.|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[type](#type)|The type of invitation.|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[type_display](#type_display)||<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[website](#website)|Unique identifier for Website associated with Invitation.|<a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>|
|[eventPortalInvitation](#eventPortalInvitation)|Indicates whether the Invitation is used by the Event Portal.|<a href="Invitation.md" target="_blank">eventManagement/Invitation</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#invitationId name="invitationId">invitationId</a>

Shows the entity instance.  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invitation</td></tr><tr><td>description</td><td>Shows the entity instance.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>adx_invitationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Invitation  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Invitation</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the invitation's status.  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the invitation's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>New</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Sent</td><td>756150000</td><td>0</td></tr><tr><td>en</td><td>Redeemed</td><td>756150001</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

Type the name of the custom entity.  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type the name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_name</td></tr></table>

### <a href=#assignToAccount name="assignToAccount">assignToAccount</a>

An account record to assign the redeemed contact to.  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Assign To Account</td></tr><tr><td>description</td><td>An account record to assign the redeemed contact to.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_assigntoaccount</td></tr></table>

### <a href=#expiryDate name="expiryDate">expiryDate</a>

The date the invitation is no longer valid for redemption.  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expiry Date</td></tr><tr><td>description</td><td>The date the invitation is no longer valid for redemption.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_expirydate</td></tr></table>

### <a href=#invitationCode name="invitationCode">invitationCode</a>

Shows the user who is redeeming the invitation.  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invitation Code</td></tr><tr><td>description</td><td>Shows the user who is redeeming the invitation.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_invitationcode</td></tr></table>

### <a href=#inviteContact name="inviteContact">inviteContact</a>

The contact to send an invitation to.  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invite Contact</td></tr><tr><td>description</td><td>The contact to send an invitation to.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_invitecontact</td></tr></table>

### <a href=#inviterContact name="inviterContact">inviterContact</a>

The contact that invited.  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inviter</td></tr><tr><td>description</td><td>The contact that invited.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_invitercontact</td></tr></table>

### <a href=#maximumRedemptions name="maximumRedemptions">maximumRedemptions</a>

First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum Redemptions</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_maximumredemptions</td></tr></table>

### <a href=#redeemedContact name="redeemedContact">redeemedContact</a>

The contact associated with the redemption of this invitation.  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Redeemed Contact</td></tr><tr><td>description</td><td>The contact associated with the redemption of this invitation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_redeemedcontact</td></tr></table>

### <a href=#redemptions name="redemptions">redemptions</a>

The current number of times this invitation has been redeemed.  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Redemptions</td></tr><tr><td>description</td><td>The current number of times this invitation has been redeemed.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_redemptions</td></tr></table>

### <a href=#redemptionWorkflow name="redemptionWorkflow">redemptionWorkflow</a>

A workflow to execute on the redeeming contact.  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Redemption Workflow</td></tr><tr><td>description</td><td>A workflow to execute on the redeeming contact.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_redemptionworkflow</td></tr></table>

### <a href=#type name="type">type</a>

The type of invitation.  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type</td></tr><tr><td>description</td><td>The type of invitation.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_type</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Single</td><td>756150000</td></tr><tr><td>en</td><td>Group</td><td>756150001</td></tr></table></td></tr></table>

### <a href=#type_display name="type_display">type_display</a>

First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#website name="website">website</a>

Unique identifier for Website associated with Invitation.  
First included in: <a href="../../portals/Invitation.md" target="_blank">portals/Invitation</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Website</td></tr><tr><td>description</td><td>Unique identifier for Website associated with Invitation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_website</td></tr></table>

### <a href=#eventPortalInvitation name="eventPortalInvitation">eventPortalInvitation</a>

Indicates whether the Invitation is used by the Event Portal.  
First included in: eventManagement/Invitation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Event Portal Invitation</td></tr><tr><td>description</td><td>Indicates whether the Invitation is used by the Event Portal.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_eventportalinvitation</td></tr></table>
