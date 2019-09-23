---
title: EmailSignature - Common Data Model | Microsoft Docs
description: Signature for email message
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Email Signature

Signature for email message  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/EmailSignature.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /EmailSignature  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[emailSignatureId](#emailSignatureId)|Unique identifier of the email signature.|<a href="EmailSignature.md" target="_blank">applicationCommon/EmailSignature</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier of the business unit that owns the email signature.|<a href="EmailSignature.md" target="_blank">applicationCommon/EmailSignature</a>|
|[isPersonal](#isPersonal)|Information about whether the email signature is personal or is available to all users.|<a href="EmailSignature.md" target="_blank">applicationCommon/EmailSignature</a>|
|[mimeType](#mimeType)|MIME type of the email signature.|<a href="EmailSignature.md" target="_blank">applicationCommon/EmailSignature</a>|
|[body](#body)|Body text of the email signature.|<a href="EmailSignature.md" target="_blank">applicationCommon/EmailSignature</a>|
|[title](#title)|Title of the email signature.|<a href="EmailSignature.md" target="_blank">applicationCommon/EmailSignature</a>|
|[description](#description)|Description of the email signature.|<a href="EmailSignature.md" target="_blank">applicationCommon/EmailSignature</a>|
|[owningUser](#owningUser)|Unique identifier of the user who owns the email signature.|<a href="EmailSignature.md" target="_blank">applicationCommon/EmailSignature</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the email signature.|<a href="EmailSignature.md" target="_blank">applicationCommon/EmailSignature</a>|
|[presentationXml](#presentationXml)|XML data for the body of the email signature.|<a href="EmailSignature.md" target="_blank">applicationCommon/EmailSignature</a>|
|[createdOn](#createdOn)|Date and time when the email signature was created.|<a href="EmailSignature.md" target="_blank">applicationCommon/EmailSignature</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who last modified the email signature.|<a href="EmailSignature.md" target="_blank">applicationCommon/EmailSignature</a>|
|[modifiedOn](#modifiedOn)|Date and time when the email signature was last modified.|<a href="EmailSignature.md" target="_blank">applicationCommon/EmailSignature</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="EmailSignature.md" target="_blank">applicationCommon/EmailSignature</a>|
|[ownerId](#ownerId)|Owner Id|<a href="EmailSignature.md" target="_blank">applicationCommon/EmailSignature</a>|
|[generationTypeCode](#generationTypeCode)|For internal use only.|<a href="EmailSignature.md" target="_blank">applicationCommon/EmailSignature</a>|
|[languageCode](#languageCode)|Language of the email signature.|<a href="EmailSignature.md" target="_blank">applicationCommon/EmailSignature</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="EmailSignature.md" target="_blank">applicationCommon/EmailSignature</a>|
|[overwriteTime](#overwriteTime)|For internal use only.|<a href="EmailSignature.md" target="_blank">applicationCommon/EmailSignature</a>|
|[componentState](#componentState)|For internal use only.|<a href="EmailSignature.md" target="_blank">applicationCommon/EmailSignature</a>|
|[componentState_display](#componentState_display)||<a href="EmailSignature.md" target="_blank">applicationCommon/EmailSignature</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the email signature.|<a href="EmailSignature.md" target="_blank">applicationCommon/EmailSignature</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who last modified the email signature.|<a href="EmailSignature.md" target="_blank">applicationCommon/EmailSignature</a>|
|[owningTeam](#owningTeam)|Unique identifier of the team who owns the email signature.|<a href="EmailSignature.md" target="_blank">applicationCommon/EmailSignature</a>|
|[isCustomizable](#isCustomizable)|Information that specifies whether this component can be customized.|<a href="EmailSignature.md" target="_blank">applicationCommon/EmailSignature</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="EmailSignature.md" target="_blank">applicationCommon/EmailSignature</a>|
|[isDefault](#isDefault)|Information that specifies whether the email signature is default to the user.|<a href="EmailSignature.md" target="_blank">applicationCommon/EmailSignature</a>|

### <a href=#emailSignatureId name="emailSignatureId">emailSignatureId</a>

Unique identifier of the email signature.  
First included in: applicationCommon/EmailSignature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Signature</td></tr><tr><td>description</td><td>Unique identifier of the email signature.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>emailsignatureid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier of the business unit that owns the email signature.  
First included in: applicationCommon/EmailSignature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier of the business unit that owns the email signature.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#isPersonal name="isPersonal">isPersonal</a>

Information about whether the email signature is personal or is available to all users.  
First included in: applicationCommon/EmailSignature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Viewable By</td></tr><tr><td>description</td><td>Information about whether the email signature is personal or is available to all users.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ispersonal</td></tr></table>

### <a href=#mimeType name="mimeType">mimeType</a>

MIME type of the email signature.  
First included in: applicationCommon/EmailSignature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mime Type</td></tr><tr><td>description</td><td>MIME type of the email signature.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>256</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mimetype</td></tr></table>

### <a href=#body name="body">body</a>

Body text of the email signature.  
First included in: applicationCommon/EmailSignature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Body</td></tr><tr><td>description</td><td>Body text of the email signature.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>body</td></tr></table>

### <a href=#title name="title">title</a>

Title of the email signature.  
First included in: applicationCommon/EmailSignature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Title</td></tr><tr><td>description</td><td>Title of the email signature.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>title</td></tr></table>

### <a href=#description name="description">description</a>

Description of the email signature.  
First included in: applicationCommon/EmailSignature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the email signature.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user who owns the email signature.  
First included in: applicationCommon/EmailSignature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user who owns the email signature.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the email signature.  
First included in: applicationCommon/EmailSignature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the email signature.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#presentationXml name="presentationXml">presentationXml</a>

XML data for the body of the email signature.  
First included in: applicationCommon/EmailSignature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Presentation XML</td></tr><tr><td>description</td><td>XML data for the body of the email signature.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>presentationxml</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the email signature was created.  
First included in: applicationCommon/EmailSignature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the email signature was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who last modified the email signature.  
First included in: applicationCommon/EmailSignature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who last modified the email signature.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the email signature was last modified.  
First included in: applicationCommon/EmailSignature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the email signature was last modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: applicationCommon/EmailSignature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: applicationCommon/EmailSignature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#generationTypeCode name="generationTypeCode">generationTypeCode</a>

For internal use only.  
First included in: applicationCommon/EmailSignature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Generation Type Code</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>generationtypecode</td></tr></table>

### <a href=#languageCode name="languageCode">languageCode</a>

Language of the email signature.  
First included in: applicationCommon/EmailSignature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Language</td></tr><tr><td>description</td><td>Language of the email signature.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>languagecode</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: applicationCommon/EmailSignature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overwriteTime name="overwriteTime">overwriteTime</a>

For internal use only.  
First included in: applicationCommon/EmailSignature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Overwrite Time</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>overwritetime</td></tr></table>

### <a href=#componentState name="componentState">componentState</a>

For internal use only.  
First included in: applicationCommon/EmailSignature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Component State</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>componentstate</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Published</td><td>0</td></tr><tr><td>en</td><td>Unpublished</td><td>1</td></tr><tr><td>en</td><td>Deleted</td><td>2</td></tr><tr><td>en</td><td>Deleted Unpublished</td><td>3</td></tr></table></td></tr></table>

### <a href=#componentState_display name="componentState_display">componentState_display</a>

First included in: applicationCommon/EmailSignature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the email signature.  
First included in: applicationCommon/EmailSignature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the email signature.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who last modified the email signature.  
First included in: applicationCommon/EmailSignature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who last modified the email signature.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier of the team who owns the email signature.  
First included in: applicationCommon/EmailSignature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier of the team who owns the email signature.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#isCustomizable name="isCustomizable">isCustomizable</a>

Information that specifies whether this component can be customized.  
First included in: applicationCommon/EmailSignature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customizable</td></tr><tr><td>description</td><td>Information that specifies whether this component can be customized.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>iscustomizable</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: applicationCommon/EmailSignature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#isDefault name="isDefault">isDefault</a>

Information that specifies whether the email signature is default to the user.  
First included in: applicationCommon/EmailSignature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Default</td></tr><tr><td>description</td><td>Information that specifies whether the email signature is default to the user.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isdefault</td></tr></table>
