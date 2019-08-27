---
title: Idea - Common Data Model | Microsoft Docs
description: An idea belonging to a portal Idea Forum.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Idea

An idea belonging to a portal Idea Forum.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/portals/Idea.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/solutions/portals/Idea  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[ideaId](#ideaId)|Shows the entity instances.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[stateCode](#stateCode)|Shows whether the idea is active or inactive. Inactive records are read-only and can't be edited unless they are reactivated.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[stateCode_display](#stateCode_display)||<a href="Idea.md" target="_blank">portals/Idea</a>|
|[statusCode](#statusCode)|Select the idea's status.
|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[statusCode_display](#statusCode_display)||<a href="Idea.md" target="_blank">portals/Idea</a>|
|[name](#name)|Shows the name or title of the idea.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[approved](#approved)|Indicates whether or not this idea is approved for display.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[authorEmail](#authorEmail)|Shows the email address for the author of this idea.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[authorId](#authorId)|The author of the idea.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[authorName](#authorName)|Shows the name for the author of this idea.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[commentPolicy](#commentPolicy)|Indicates the comment policy to be used for this idea.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[commentPolicy_display](#commentPolicy_display)||<a href="Idea.md" target="_blank">portals/Idea</a>|
|[copy](#copy)|Type a description of the idea.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[adxCreatedByIPAddress](#adxCreatedByIPAddress)|Shows the IP address of the user when they submitted this idea.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[adxCreatedByUsername](#adxCreatedByUsername)|Shows the system username of the user when they submitted this idea.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[submittedOn](#submittedOn)|Shows the date and time this idea was submitted.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[ideaForumId](#ideaForumId)|The parent idea forum that this idea belongs to.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[partialURL](#partialURL)|Shows the URL path fragment used to generate a URL for this idea.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[statusAuthorId](#statusAuthorId)|The author of the idea's status.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[statusComment](#statusComment)|Type a comment for the status of the idea.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[summary](#summary)|Type an abstract of this idea.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[votersTotalNumberOf](#votersTotalNumberOf)|Shows the total number of voters for this idea.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[votesDown](#votesDown)|Shows the number of down votes this idea has received.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[votesTotalNumberOf](#votesTotalNumberOf)|Shows the total number of votes for this idea.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[voteSum](#voteSum)|Shows the calculated number of up votes minus down votes.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[votesUp](#votesUp)|Shows the number of up votes this idea has received.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[totalVotes](#totalVotes)|Shows the total votes casted on the idea.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[totalVotesDate](#totalVotesDate)|Last Updated time of rollup field Total Votes.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[totalVotesState](#totalVotesState)|State of rollup field Total Votes.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[votesSum](#votesSum)|Shows the sum of all votes casted on the idea.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[votesSumDate](#votesSumDate)|Last Updated time of rollup field Vote Sum.|<a href="Idea.md" target="_blank">portals/Idea</a>|
|[votesSumState](#votesSumState)|State of rollup field Vote Sum.|<a href="Idea.md" target="_blank">portals/Idea</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#ideaId name="ideaId">ideaId</a>

Shows the entity instances.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Idea</td></tr><tr><td>description</td><td>Shows the entity instances.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>adx_ideaid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the idea is active or inactive. Inactive records are read-only and can't be edited unless they are reactivated.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows whether the idea is active or inactive. Inactive records are read-only and can't be edited unless they are reactivated.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the idea's status.
  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the idea's status.
</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>New</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Accepted</td><td>100000000</td><td>0</td></tr><tr><td>en</td><td>Completed</td><td>100000001</td><td>0</td></tr><tr><td>en</td><td>Rejected</td><td>100000002</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

Shows the name or title of the idea.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Title</td></tr><tr><td>description</td><td>Shows the name or title of the idea.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_name</td></tr></table>

### <a href=#approved name="approved">approved</a>

Indicates whether or not this idea is approved for display.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Published to Web</td></tr><tr><td>description</td><td>Indicates whether or not this idea is approved for display.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_approved</td></tr></table>

### <a href=#authorEmail name="authorEmail">authorEmail</a>

Shows the email address for the author of this idea.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Author Email</td></tr><tr><td>description</td><td>Shows the email address for the author of this idea.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_authoremail</td></tr></table>

### <a href=#authorId name="authorId">authorId</a>

The author of the idea.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Author</td></tr><tr><td>description</td><td>The author of the idea.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_authorid</td></tr></table>

### <a href=#authorName name="authorName">authorName</a>

Shows the name for the author of this idea.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Author Name</td></tr><tr><td>description</td><td>Shows the name for the author of this idea.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_authorname</td></tr></table>

### <a href=#commentPolicy name="commentPolicy">commentPolicy</a>

Indicates the comment policy to be used for this idea.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Comment Policy</td></tr><tr><td>description</td><td>Indicates the comment policy to be used for this idea.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_commentpolicy</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Inherit</td><td>100000005</td></tr><tr><td>en</td><td>Open</td><td>100000000</td></tr><tr><td>en</td><td>Open to Authenticated Users</td><td>100000001</td></tr><tr><td>en</td><td>Moderated</td><td>100000002</td></tr><tr><td>en</td><td>Closed</td><td>100000003</td></tr><tr><td>en</td><td>None</td><td>100000004</td></tr></table></td></tr></table>

### <a href=#commentPolicy_display name="commentPolicy_display">commentPolicy_display</a>

First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#copy name="copy">copy</a>

Type a description of the idea.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Copy</td></tr><tr><td>description</td><td>Type a description of the idea.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_copy</td></tr></table>

### <a href=#adxCreatedByIPAddress name="adxCreatedByIPAddress">adxCreatedByIPAddress</a>

Shows the IP address of the user when they submitted this idea.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (IP Address)</td></tr><tr><td>description</td><td>Shows the IP address of the user when they submitted this idea.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_createdbyipaddress</td></tr></table>

### <a href=#adxCreatedByUsername name="adxCreatedByUsername">adxCreatedByUsername</a>

Shows the system username of the user when they submitted this idea.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Username)</td></tr><tr><td>description</td><td>Shows the system username of the user when they submitted this idea.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_createdbyusername</td></tr></table>

### <a href=#submittedOn name="submittedOn">submittedOn</a>

Shows the date and time this idea was submitted.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Submitted On</td></tr><tr><td>description</td><td>Shows the date and time this idea was submitted.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_date</td></tr></table>

### <a href=#ideaForumId name="ideaForumId">ideaForumId</a>

The parent idea forum that this idea belongs to.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Idea Forum</td></tr><tr><td>description</td><td>The parent idea forum that this idea belongs to.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_ideaforumid</td></tr></table>

### <a href=#partialURL name="partialURL">partialURL</a>

Shows the URL path fragment used to generate a URL for this idea.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Partial URL</td></tr><tr><td>description</td><td>Shows the URL path fragment used to generate a URL for this idea.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_partialurl</td></tr></table>

### <a href=#statusAuthorId name="statusAuthorId">statusAuthorId</a>

The author of the idea's status.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Author</td></tr><tr><td>description</td><td>The author of the idea's status.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_statusauthorid</td></tr></table>

### <a href=#statusComment name="statusComment">statusComment</a>

Type a comment for the status of the idea.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Comment</td></tr><tr><td>description</td><td>Type a comment for the status of the idea.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_statuscomment</td></tr></table>

### <a href=#summary name="summary">summary</a>

Type an abstract of this idea.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Summary</td></tr><tr><td>description</td><td>Type an abstract of this idea.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_summary</td></tr></table>

### <a href=#votersTotalNumberOf name="votersTotalNumberOf">votersTotalNumberOf</a>

Shows the total number of voters for this idea.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Number Of Voters</td></tr><tr><td>description</td><td>Shows the total number of voters for this idea.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_voterstotalnumberof</td></tr></table>

### <a href=#votesDown name="votesDown">votesDown</a>

Shows the number of down votes this idea has received.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Votes Down</td></tr><tr><td>description</td><td>Shows the number of down votes this idea has received.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_votesdown</td></tr></table>

### <a href=#votesTotalNumberOf name="votesTotalNumberOf">votesTotalNumberOf</a>

Shows the total number of votes for this idea.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Number of Votes</td></tr><tr><td>description</td><td>Shows the total number of votes for this idea.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_votestotalnumberof</td></tr></table>

### <a href=#voteSum name="voteSum">voteSum</a>

Shows the calculated number of up votes minus down votes.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vote Sum</td></tr><tr><td>description</td><td>Shows the calculated number of up votes minus down votes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_votesum</td></tr></table>

### <a href=#votesUp name="votesUp">votesUp</a>

Shows the number of up votes this idea has received.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Votes Up</td></tr><tr><td>description</td><td>Shows the number of up votes this idea has received.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_votesup</td></tr></table>

### <a href=#totalVotes name="totalVotes">totalVotes</a>

Shows the total votes casted on the idea.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Votes</td></tr><tr><td>description</td><td>Shows the total votes casted on the idea.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_totalvotes</td></tr></table>

### <a href=#totalVotesDate name="totalVotesDate">totalVotesDate</a>

Last Updated time of rollup field Total Votes.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Votes (Last Updated On)</td></tr><tr><td>description</td><td>Last Updated time of rollup field Total Votes.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_totalvotes_date</td></tr></table>

### <a href=#totalVotesState name="totalVotesState">totalVotesState</a>

State of rollup field Total Votes.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Votes (State)</td></tr><tr><td>description</td><td>State of rollup field Total Votes.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_totalvotes_state</td></tr></table>

### <a href=#votesSum name="votesSum">votesSum</a>

Shows the sum of all votes casted on the idea.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vote Sum</td></tr><tr><td>description</td><td>Shows the sum of all votes casted on the idea.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_votessum</td></tr></table>

### <a href=#votesSumDate name="votesSumDate">votesSumDate</a>

Last Updated time of rollup field Vote Sum.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vote Sum (Last Updated On)</td></tr><tr><td>description</td><td>Last Updated time of rollup field Vote Sum.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_votessum_date</td></tr></table>

### <a href=#votesSumState name="votesSumState">votesSumState</a>

State of rollup field Vote Sum.  
First included in: portals/Idea (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vote Sum (State)</td></tr><tr><td>description</td><td>State of rollup field Vote Sum.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_votessum_state</td></tr></table>
