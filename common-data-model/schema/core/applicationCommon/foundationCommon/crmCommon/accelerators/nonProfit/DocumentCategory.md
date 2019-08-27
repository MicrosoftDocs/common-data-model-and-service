---
title: DocumentCategory - Common Data Model | Microsoft Docs
description: IATI Document Category.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Document Category

IATI Document Category.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/DocumentCategory.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/nonProfit/DocumentCategory  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="DocumentCategory.md" target="_blank">nonProfit/DocumentCategory</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="DocumentCategory.md" target="_blank">nonProfit/DocumentCategory</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="DocumentCategory.md" target="_blank">nonProfit/DocumentCategory</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="DocumentCategory.md" target="_blank">nonProfit/DocumentCategory</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="DocumentCategory.md" target="_blank">nonProfit/DocumentCategory</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="DocumentCategory.md" target="_blank">nonProfit/DocumentCategory</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="DocumentCategory.md" target="_blank">nonProfit/DocumentCategory</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="DocumentCategory.md" target="_blank">nonProfit/DocumentCategory</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="DocumentCategory.md" target="_blank">nonProfit/DocumentCategory</a>|
|[ownerId](#ownerId)|Owner Id|<a href="DocumentCategory.md" target="_blank">nonProfit/DocumentCategory</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="DocumentCategory.md" target="_blank">nonProfit/DocumentCategory</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="DocumentCategory.md" target="_blank">nonProfit/DocumentCategory</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="DocumentCategory.md" target="_blank">nonProfit/DocumentCategory</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="DocumentCategory.md" target="_blank">nonProfit/DocumentCategory</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="DocumentCategory.md" target="_blank">nonProfit/DocumentCategory</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="DocumentCategory.md" target="_blank">nonProfit/DocumentCategory</a>|
|[documentcategoryId](#documentcategoryId)|Unique identifier for entity instances|<a href="DocumentCategory.md" target="_blank">nonProfit/DocumentCategory</a>|
|[stateCode](#stateCode)|Status of the Document Category|<a href="DocumentCategory.md" target="_blank">nonProfit/DocumentCategory</a>|
|[stateCode_display](#stateCode_display)||<a href="DocumentCategory.md" target="_blank">nonProfit/DocumentCategory</a>|
|[statusCode](#statusCode)|Reason for the status of the Document Category|<a href="DocumentCategory.md" target="_blank">nonProfit/DocumentCategory</a>|
|[statusCode_display](#statusCode_display)||<a href="DocumentCategory.md" target="_blank">nonProfit/DocumentCategory</a>|
|[name](#name)|The name of the custom entity.|<a href="DocumentCategory.md" target="_blank">nonProfit/DocumentCategory</a>|
|[category](#category)|IATI Document Category.|<a href="DocumentCategory.md" target="_blank">nonProfit/DocumentCategory</a>|
|[category_display](#category_display)||<a href="DocumentCategory.md" target="_blank">nonProfit/DocumentCategory</a>|
|[documentLinkId](#documentLinkId)|Unique identifier for Document Link associated with Document Category.|<a href="DocumentCategory.md" target="_blank">nonProfit/DocumentCategory</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: nonProfit/DocumentCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: nonProfit/DocumentCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: nonProfit/DocumentCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: nonProfit/DocumentCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: nonProfit/DocumentCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: nonProfit/DocumentCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: nonProfit/DocumentCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: nonProfit/DocumentCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: nonProfit/DocumentCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: nonProfit/DocumentCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: nonProfit/DocumentCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: nonProfit/DocumentCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: nonProfit/DocumentCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: nonProfit/DocumentCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: nonProfit/DocumentCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: nonProfit/DocumentCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#documentcategoryId name="documentcategoryId">documentcategoryId</a>

Unique identifier for entity instances  
First included in: nonProfit/DocumentCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Document Category</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msiati_documentcategoryid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Document Category  
First included in: nonProfit/DocumentCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Document Category</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: nonProfit/DocumentCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Document Category  
First included in: nonProfit/DocumentCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Document Category</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: nonProfit/DocumentCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: nonProfit/DocumentCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_name</td></tr></table>

### <a href=#category name="category">category</a>

IATI Document Category.  
First included in: nonProfit/DocumentCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Category</td></tr><tr><td>description</td><td>IATI Document Category.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_category</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>A01 - Pre- and post-project impact appraisal</td><td>453490000</td></tr><tr><td>en</td><td>A02 - Objectives / Purpose of activity</td><td>453490001</td></tr><tr><td>en</td><td>A03 - Intended ultimate beneficiaries</td><td>453490002</td></tr><tr><td>en</td><td>A04 - Conditions</td><td>453490003</td></tr><tr><td>en</td><td>A05 - Budget</td><td>453490004</td></tr><tr><td>en</td><td>A06 - Summary information about contract</td><td>453490005</td></tr><tr><td>en</td><td>A07 -  Review of project performance and evaluation</td><td>453490006</td></tr><tr><td>en</td><td>A08 - Results, outcomes and outputs</td><td>453490007</td></tr><tr><td>en</td><td>A09 - Memorandum of understanding (If agreed by all parties)</td><td>453490008</td></tr><tr><td>en</td><td>A10 - Tender</td><td>453490009</td></tr><tr><td>en</td><td>A11 - Contract</td><td>453490010</td></tr><tr><td>en</td><td>A12 - Activity web page</td><td>453490011</td></tr><tr><td>en</td><td>B01 - Annual report</td><td>453490012</td></tr><tr><td>en</td><td>B02 - Institutional Strategy paper</td><td>453490013</td></tr><tr><td>en</td><td>B03 - Country strategy paper</td><td>453490014</td></tr><tr><td>en</td><td>B04 - Aid Allocation Policy</td><td>453490015</td></tr><tr><td>en</td><td>B05 - Procurement Policy and Procedure</td><td>453490016</td></tr><tr><td>en</td><td>B06 - Institutional Audit Report</td><td>453490017</td></tr><tr><td>en</td><td>B07 - Country Audit Report</td><td>453490018</td></tr><tr><td>en</td><td>B08 - Exclusions Policy</td><td>453490019</td></tr><tr><td>en</td><td>B09 - Institutional Evaluation Report</td><td>453490020</td></tr><tr><td>en</td><td>B10 - Country Evaluation Report</td><td>453490021</td></tr><tr><td>en</td><td>B11 - Sector strategy</td><td>453490022</td></tr><tr><td>en</td><td>B12 - Thematic strategy</td><td>453490023</td></tr><tr><td>en</td><td>B13 - Country-level Memorandum of Understanding</td><td>453490024</td></tr><tr><td>en</td><td>B14 - Evaluations policy</td><td>453490025</td></tr><tr><td>en</td><td>B15 - General Terms and Conditions</td><td>453490026</td></tr><tr><td>en</td><td>B16 - Organisation web page</td><td>453490027</td></tr><tr><td>en</td><td>B17 - Country/Region web page</td><td>453490028</td></tr><tr><td>en</td><td>B18 - Sector web page</td><td>453490029</td></tr></table></td></tr></table>

### <a href=#category_display name="category_display">category_display</a>

First included in: nonProfit/DocumentCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#documentLinkId name="documentLinkId">documentLinkId</a>

Unique identifier for Document Link associated with Document Category.  
First included in: nonProfit/DocumentCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Document Link</td></tr><tr><td>description</td><td>Unique identifier for Document Link associated with Document Category.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_documentlinkid</td></tr></table>
