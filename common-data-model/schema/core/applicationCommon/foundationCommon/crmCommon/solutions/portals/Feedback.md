---
title: Feedback - Common Data Model | Microsoft Docs
description: Container for feedback and ratings for knowledge articles.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Feedback

Container for feedback and ratings for knowledge articles.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/portals/Feedback.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- [/Feedback](../../../../Feedback.md "/core/applicationCommon/Feedback.cdm.json/Feedback")  
- /foundationCommon/crmCommon/solutions/portals/Feedback  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[feedbackId](#feedbackId)|FeedbackId|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[rating](#rating)|Specifies how helpful the related record was.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[minRating](#minRating)|Enter the minimum rating value.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[maxRating](#maxRating)|Enter the maximum rating value.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[normalizedRating](#normalizedRating)|Shows the rating scaled to a value between 0 and 1 based on minimum and maximum ratings.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[comments](#comments)|Type the feedback comments.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[source](#source)|Shows where the feedback was submitted from.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[source_display](#source_display)||<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[stateCode](#stateCode)|Shows whether the feedback is open, rejected or closed.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[stateCode_display](#stateCode_display)||<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[statusCode](#statusCode)|Select the feedback's status.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[statusCode_display](#statusCode_display)||<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[versionNumber](#versionNumber)|Version number of the feedback.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[regardingObjectId](#regardingObjectId)|Shows the record that the feedback is associated with.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[createdOn](#createdOn)|Shows the date and time when the record was created. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[modifiedOn](#modifiedOn)|Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[ownerId](#ownerId)|Owner Id|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier of the business unit that owns the knowledge article views.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[owningUser](#owningUser)|Unique identifier of the user who owns this feedback.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[owningTeam](#owningTeam)|Unique identifier of the team that owns the feedback.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[closedBy](#closedBy)|Shows who closed the record.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[closedOn](#closedOn)|Shows the date and time when the record was closed. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[title](#title)|Type a title for the feedback.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[createdByContact](#createdByContact)|Shows the contact who created the record.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[createdOnBehalfByContact](#createdOnBehalfByContact)|Shows the contact who created the record on behalf of another user.|<a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>|
|[publishedToWeb](#publishedToWeb)|Shows whether the feedback is approved for display.|<a href="Feedback.md" target="_blank">portals/Feedback</a>|
|[authorURL](#authorURL)|The URL of the author’s home page/blog.|<a href="Feedback.md" target="_blank">portals/Feedback</a>|
|[adxContactEmail](#adxContactEmail)|Email of the contact who created the record.|<a href="Feedback.md" target="_blank">portals/Feedback</a>|
|[adxContactUsername](#adxContactUsername)|Username of the contact who created the record.|<a href="Feedback.md" target="_blank">portals/Feedback</a>|
|[adxCreatedByContact](#adxCreatedByContact)|Name of the contact who created the record.|<a href="Feedback.md" target="_blank">portals/Feedback</a>|

### <a href=#feedbackId name="feedbackId">feedbackId</a>

FeedbackId  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Feedback</td></tr><tr><td>description</td><td>FeedbackId</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>feedbackid</td></tr></table>

### <a href=#rating name="rating">rating</a>

Specifies how helpful the related record was.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rating</td></tr><tr><td>description</td><td>Specifies how helpful the related record was.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rating</td></tr></table>

### <a href=#minRating name="minRating">minRating</a>

Enter the minimum rating value.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Minimum Rating</td></tr><tr><td>description</td><td>Enter the minimum rating value.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>minrating</td></tr></table>

### <a href=#maxRating name="maxRating">maxRating</a>

Enter the maximum rating value.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum Rating</td></tr><tr><td>description</td><td>Enter the maximum rating value.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>maxrating</td></tr></table>

### <a href=#normalizedRating name="normalizedRating">normalizedRating</a>

Shows the rating scaled to a value between 0 and 1 based on minimum and maximum ratings.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Normalized Rating</td></tr><tr><td>description</td><td>Shows the rating scaled to a value between 0 and 1 based on minimum and maximum ratings.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>normalizedrating</td></tr></table>

### <a href=#comments name="comments">comments</a>

Type the feedback comments.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Comments</td></tr><tr><td>description</td><td>Type the feedback comments.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>comments</td></tr></table>

### <a href=#source name="source">source</a>

Shows where the feedback was submitted from.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Source</td></tr><tr><td>description</td><td>Shows where the feedback was submitted from.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>source</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Internal</td><td>0</td></tr><tr><td>en</td><td>Portal</td><td>1</td></tr></table></td></tr></table>

### <a href=#source_display name="source_display">source_display</a>

First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the feedback is open, rejected or closed.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows whether the feedback is open, rejected or closed.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Open</td><td>0</td></tr><tr><td>en</td><td>Closed</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the feedback's status.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the feedback's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Proposed</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Accepted</td><td>2</td><td>0</td></tr><tr><td>en</td><td>Closed</td><td>3</td><td>1</td></tr><tr><td>en</td><td>Rejected</td><td>4</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version number of the feedback.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version number of the feedback.</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#regardingObjectId name="regardingObjectId">regardingObjectId</a>

Shows the record that the feedback is associated with.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regarding</td></tr><tr><td>description</td><td>Shows the record that the feedback is associated with.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>regardingobjectid</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Shows the date and time when the record was created. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Shows the date and time when the record was created. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier of the business unit that owns the knowledge article views.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier of the business unit that owns the knowledge article views.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user who owns this feedback.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user who owns this feedback.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier of the team that owns the feedback.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier of the team that owns the feedback.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#closedBy name="closedBy">closedBy</a>

Shows who closed the record.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Closed By</td></tr><tr><td>description</td><td>Shows who closed the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>closedby</td></tr></table>

### <a href=#closedOn name="closedOn">closedOn</a>

Shows the date and time when the record was closed. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Closed On</td></tr><tr><td>description</td><td>Shows the date and time when the record was closed. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>closedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#title name="title">title</a>

Type a title for the feedback.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Title</td></tr><tr><td>description</td><td>Type a title for the feedback.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>155</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>title</td></tr></table>

### <a href=#createdByContact name="createdByContact">createdByContact</a>

Shows the contact who created the record.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Contact)</td></tr><tr><td>description</td><td>Shows the contact who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdbycontact</td></tr></table>

### <a href=#createdOnBehalfByContact name="createdOnBehalfByContact">createdOnBehalfByContact</a>

Shows the contact who created the record on behalf of another user.  
First included in: <a href="../../../../Feedback.md" target="_blank">applicationCommon/Feedback</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created OnBelhalfBy (Contact)</td></tr><tr><td>description</td><td>Shows the contact who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfbycontact</td></tr></table>

### <a href=#publishedToWeb name="publishedToWeb">publishedToWeb</a>

Shows whether the feedback is approved for display.  
First included in: portals/Feedback (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Published To Web</td></tr><tr><td>description</td><td>Shows whether the feedback is approved for display.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_approved</td></tr></table>

### <a href=#authorURL name="authorURL">authorURL</a>

The URL of the author’s home page/blog.  
First included in: portals/Feedback (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Author URL</td></tr><tr><td>description</td><td>The URL of the author’s home page/blog.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_authorurl</td></tr></table>

### <a href=#adxContactEmail name="adxContactEmail">adxContactEmail</a>

Email of the contact who created the record.  
First included in: portals/Feedback (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email</td></tr><tr><td>description</td><td>Email of the contact who created the record.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_contactemail</td></tr></table>

### <a href=#adxContactUsername name="adxContactUsername">adxContactUsername</a>

Username of the contact who created the record.  
First included in: portals/Feedback (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Username</td></tr><tr><td>description</td><td>Username of the contact who created the record.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_contactusername</td></tr></table>

### <a href=#adxCreatedByContact name="adxCreatedByContact">adxCreatedByContact</a>

Name of the contact who created the record.  
First included in: portals/Feedback (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By Name (Contact)</td></tr><tr><td>description</td><td>Name of the contact who created the record.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>adx_createdbycontact</td></tr></table>
