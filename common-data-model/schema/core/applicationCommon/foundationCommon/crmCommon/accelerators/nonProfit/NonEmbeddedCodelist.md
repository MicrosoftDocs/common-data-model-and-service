---
title: NonEmbeddedCodelist - Common Data Model | Microsoft Docs
description: This describes the NonEmbeddedCodelist entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Non Embedded Codelist

Non-functional codelists that usually provide lookup information on e.g. currencies, languages in use, countries, etc.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/NonEmbeddedCodelist.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/nonProfit/NonEmbeddedCodelist  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|
|[ownerId](#ownerId)|Owner Id|<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|
|[nonEmbeddedCodelistId](#nonEmbeddedCodelistId)|Unique identifier for entity instances|<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|
|[stateCode](#stateCode)|Status of the Non Embedded Codelist|<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|
|[stateCode_display](#stateCode_display)||<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|
|[statusCode](#statusCode)|Reason for the status of the Non Embedded Codelist|<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|
|[statusCode_display](#statusCode_display)||<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|
|[name](#name)|The name of the custom entity.|<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|
|[category](#category)|Category for the non embedded code list|<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|
|[code](#code)|Code (identifier) of the codelist entry.|<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|
|[codelistType](#codelistType)|Type of Codelist being defined.|<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|
|[codelistType_display](#codelistType_display)||<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|
|[description](#description)|Description of the codelist entry.|<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|
|[nonEmbeddedCodelistVocabularyId](#nonEmbeddedCodelistVocabularyId)|Unique identifier for Non Embedded Codelist Vocabulary associated with Non Embedded Codelist.|<a href="NonEmbeddedCodelist.md" target="_blank">nonProfit/NonEmbeddedCodelist</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#nonEmbeddedCodelistId name="nonEmbeddedCodelistId">nonEmbeddedCodelistId</a>

Unique identifier for entity instances  
First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Non Embedded Codelist</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msiati_nonembeddedcodelistid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Non Embedded Codelist  
First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Non Embedded Codelist</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Non Embedded Codelist  
First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Non Embedded Codelist</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_name</td></tr></table>

### <a href=#category name="category">category</a>

Category for the non embedded code list  
First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Category</td></tr><tr><td>description</td><td>Category for the non embedded code list</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_category</td></tr></table>

### <a href=#code name="code">code</a>

Code (identifier) of the codelist entry.  
First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Code</td></tr><tr><td>description</td><td>Code (identifier) of the codelist entry.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_code</td></tr></table>

### <a href=#codelistType name="codelistType">codelistType</a>

Type of Codelist being defined.  
First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Codelist Type</td></tr><tr><td>description</td><td>Type of Codelist being defined.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_codelisttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Activity Scope</td><td>453490000</td></tr><tr><td>en</td><td>Aid Type</td><td>453490001</td></tr><tr><td>en</td><td>Budget Identifier</td><td>453490013</td></tr><tr><td>en</td><td>Budget Not Provided</td><td>453490003</td></tr><tr><td>en</td><td>Collaboration Type</td><td>453490004</td></tr><tr><td>en</td><td>Condition Type</td><td>453490005</td></tr><tr><td>en</td><td>Contact Type</td><td>453490006</td></tr><tr><td>en</td><td>Country</td><td>453490007</td></tr><tr><td>en</td><td>CRS Channel</td><td>453490008</td></tr><tr><td>en</td><td>Description Type</td><td>453490009</td></tr><tr><td>en</td><td>Disbursement Channel</td><td>453490010</td></tr><tr><td>en</td><td>File Format</td><td>453490011</td></tr><tr><td>en</td><td>Finance Type</td><td>453490012</td></tr><tr><td>en</td><td>Flow Type</td><td>453490014</td></tr><tr><td>en</td><td>Geographic Exactness</td><td>453490015</td></tr><tr><td>en</td><td>Geographic Location</td><td>453490016</td></tr><tr><td>en</td><td>Geographic Location Class</td><td>453490017</td></tr><tr><td>en</td><td>Geographic Location Reach</td><td>453490018</td></tr><tr><td>en</td><td>Humanitarian Scope</td><td>453490019</td></tr><tr><td>en</td><td>Humanitarian Scope Type</td><td>453490020</td></tr><tr><td>en</td><td>Indicator</td><td>453490021</td></tr><tr><td>en</td><td>Indicator Measure</td><td>453490034</td></tr><tr><td>en</td><td>Language</td><td>453490022</td></tr><tr><td>en</td><td>Location Type</td><td>453490023</td></tr><tr><td>en</td><td>Organization Type</td><td>453490024</td></tr><tr><td>en</td><td>Other Identifier Type</td><td>453490025</td></tr><tr><td>en</td><td>Policy Marker</td><td>453490026</td></tr><tr><td>en</td><td>Policy Significance</td><td>453490027</td></tr><tr><td>en</td><td>Region</td><td>453490028</td></tr><tr><td>en</td><td>Result</td><td>453490029</td></tr><tr><td>en</td><td>Result Type</td><td>453490033</td></tr><tr><td>en</td><td>Sector</td><td>453490030</td></tr><tr><td>en</td><td>Tag</td><td>453490031</td></tr><tr><td>en</td><td>Tied Status</td><td>453490032</td></tr></table></td></tr></table>

### <a href=#codelistType_display name="codelistType_display">codelistType_display</a>

First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#description name="description">description</a>

Description of the codelist entry.  
First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the codelist entry.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>5000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_description</td></tr></table>

### <a href=#nonEmbeddedCodelistVocabularyId name="nonEmbeddedCodelistVocabularyId">nonEmbeddedCodelistVocabularyId</a>

Unique identifier for Non Embedded Codelist Vocabulary associated with Non Embedded Codelist.  
First included in: nonProfit/NonEmbeddedCodelist (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vocabulary</td></tr><tr><td>description</td><td>Unique identifier for Non Embedded Codelist Vocabulary associated with Non Embedded Codelist.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_nonembeddedcodelistvocabularyid</td></tr></table>
