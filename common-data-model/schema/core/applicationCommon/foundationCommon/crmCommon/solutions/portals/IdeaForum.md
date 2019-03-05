---
title: IdeaForum - Common Data Model | Microsoft Docs
description: The root entity for portal Ideas.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/5/2019
ms.author: nebanfic
---

# Idea Forum

The root entity for portal Ideas.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/portals/IdeaForum.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/portals/IdeaForum  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[ownerId](#ownerId)|Owner Id|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[ideaForumId](#ideaForumId)|Shows the entity instances.|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[stateCode](#stateCode)|Shows whether the idea forum is active or inactive. Inactive records are read-only and can't be edited unless they are reactivated.|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[stateCode_display](#stateCode_display)||<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[statusCode](#statusCode)|Select the idea forum's status.|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[statusCode_display](#statusCode_display)||<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[name](#name)|Shows the name or title of the idea forum.|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[commentPolicy](#commentPolicy)|Shows the default comment policy to be used on ideas in this idea forum.|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[commentPolicy_display](#commentPolicy_display)||<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[ideaSubmissionPolicy](#ideaSubmissionPolicy)|Indicates the policy to be enforced for user submitted ideas in this idea forum.|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[ideaSubmissionPolicy_display](#ideaSubmissionPolicy_display)||<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[partialURL](#partialURL)|Shows the URL path fragment used to generate a URL for this idea forum.|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[summary](#summary)|Type a description of this idea forum's purpose.|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[votesPerIdea](#votesPerIdea)|Shows the number of votes a user is allowed for a single idea belonging to this idea forum.|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[votesPerUser](#votesPerUser)|Shows the number of votes a user is allowed to use in this idea forum.|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[votingPolicy](#votingPolicy)|Indicates the voting policy to be used for this idea forum.|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[votingPolicy_display](#votingPolicy_display)||<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[votingType](#votingType)|Shows the type of voting that this idea forum allows.|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[votingType_display](#votingType_display)||<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[websiteId](#websiteId)|Shows the website associated with the idea forum.|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|
|[websiteLanguageId](#websiteLanguageId)|Option to make idea forums language specific|<a href="IdeaForum.md" target="_blank">portals/IdeaForum</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#ideaForumId name="ideaForumId">ideaForumId</a>

Shows the entity instances.  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Idea Forum</td></tr><tr><td>description</td><td>Shows the entity instances.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>adx_ideaforumid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the idea forum is active or inactive. Inactive records are read-only and can't be edited unless they are reactivated.  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows whether the idea forum is active or inactive. Inactive records are read-only and can't be edited unless they are reactivated.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the idea forum's status.  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the idea forum's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

Shows the name or title of the idea forum.  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Title</td></tr><tr><td>description</td><td>Shows the name or title of the idea forum.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_name</td></tr></table>

### <a href=#commentPolicy name="commentPolicy">commentPolicy</a>

Shows the default comment policy to be used on ideas in this idea forum.  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Comment Policy</td></tr><tr><td>description</td><td>Shows the default comment policy to be used on ideas in this idea forum.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_commentpolicy</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Open</td><td>100000000</td></tr><tr><td>en</td><td>Open to Authenticated Users</td><td>100000001</td></tr><tr><td>en</td><td>Moderated</td><td>100000002</td></tr><tr><td>en</td><td>Closed</td><td>100000003</td></tr><tr><td>en</td><td>None</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#commentPolicy_display name="commentPolicy_display">commentPolicy_display</a>

First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#ideaSubmissionPolicy name="ideaSubmissionPolicy">ideaSubmissionPolicy</a>

Indicates the policy to be enforced for user submitted ideas in this idea forum.  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Idea Submission Policy</td></tr><tr><td>description</td><td>Indicates the policy to be enforced for user submitted ideas in this idea forum.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_ideasubmissionpolicy</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Open</td><td>100000000</td></tr><tr><td>en</td><td>Open to Authenticated Users</td><td>100000001</td></tr><tr><td>en</td><td>Moderated</td><td>100000002</td></tr><tr><td>en</td><td>Closed</td><td>100000003</td></tr></table></td></tr></table>

### <a href=#ideaSubmissionPolicy_display name="ideaSubmissionPolicy_display">ideaSubmissionPolicy_display</a>

First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#partialURL name="partialURL">partialURL</a>

Shows the URL path fragment used to generate a URL for this idea forum.  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Partial URL</td></tr><tr><td>description</td><td>Shows the URL path fragment used to generate a URL for this idea forum.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_partialurl</td></tr></table>

### <a href=#summary name="summary">summary</a>

Type a description of this idea forum's purpose.  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Summary</td></tr><tr><td>description</td><td>Type a description of this idea forum's purpose.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_summary</td></tr></table>

### <a href=#votesPerIdea name="votesPerIdea">votesPerIdea</a>

Shows the number of votes a user is allowed for a single idea belonging to this idea forum.  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Votes Per Idea</td></tr><tr><td>description</td><td>Shows the number of votes a user is allowed for a single idea belonging to this idea forum.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>100</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_votesperidea</td></tr></table>

### <a href=#votesPerUser name="votesPerUser">votesPerUser</a>

Shows the number of votes a user is allowed to use in this idea forum.  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Votes Per User</td></tr><tr><td>description</td><td>Shows the number of votes a user is allowed to use in this idea forum.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>100000</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_votesperuser</td></tr></table>

### <a href=#votingPolicy name="votingPolicy">votingPolicy</a>

Indicates the voting policy to be used for this idea forum.  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Voting Policy</td></tr><tr><td>description</td><td>Indicates the voting policy to be used for this idea forum.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_votingpolicy</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Open</td><td>100000000</td></tr><tr><td>en</td><td>Open to Authenticated Users</td><td>100000001</td></tr><tr><td>en</td><td>Closed</td><td>100000002</td></tr><tr><td>en</td><td>None</td><td>100000003</td></tr></table></td></tr></table>

### <a href=#votingPolicy_display name="votingPolicy_display">votingPolicy_display</a>

First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#votingType name="votingType">votingType</a>

Shows the type of voting that this idea forum allows.  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Voting Type</td></tr><tr><td>description</td><td>Shows the type of voting that this idea forum allows.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_votingtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Up Only</td><td>100000000</td></tr><tr><td>en</td><td>Up or Down</td><td>100000001</td></tr><tr><td>en</td><td>Rating</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#votingType_display name="votingType_display">votingType_display</a>

First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#websiteId name="websiteId">websiteId</a>

Shows the website associated with the idea forum.  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Website</td></tr><tr><td>description</td><td>Shows the website associated with the idea forum.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_websiteid</td></tr></table>

### <a href=#websiteLanguageId name="websiteLanguageId">websiteLanguageId</a>

Option to make idea forums language specific  
First included in: portals/IdeaForum (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Idea Forum Language</td></tr><tr><td>description</td><td>Option to make idea forums language specific</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_websitelanguageid</td></tr></table>
