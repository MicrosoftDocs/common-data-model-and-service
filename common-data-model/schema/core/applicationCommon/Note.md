---
title: Note - Common Data Model | Microsoft Docs
description: Note that is attached to one or more objects, including other notes.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Note

Note that is attached to one or more objects, including other notes.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/Note.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /Note  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[annotationId](#annotationId)|Unique identifier of the note.|<a href="Note.md" target="_blank">applicationCommon/Note</a>|
|[objectTypeCode](#objectTypeCode)|Type of entity with which the note is associated.|<a href="Note.md" target="_blank">applicationCommon/Note</a>|
|[objectTypeCode_display](#objectTypeCode_display)||<a href="Note.md" target="_blank">applicationCommon/Note</a>|
|[owningUser](#owningUser)|Unique identifier of the user who owns the note.|<a href="Note.md" target="_blank">applicationCommon/Note</a>|
|[objectIdTypeCode](#objectIdTypeCode)|The name of the entity linked by objectId|<a href="Note.md" target="_blank">applicationCommon/Note</a>|
|[objectId](#objectId)|Unique identifier of the object with which the note is associated.|<a href="Note.md" target="_blank">applicationCommon/Note</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier of the business unit that owns the note.|<a href="Note.md" target="_blank">applicationCommon/Note</a>|
|[subject](#subject)|Subject associated with the note.|<a href="Note.md" target="_blank">applicationCommon/Note</a>|
|[isDocument](#isDocument)|Specifies whether the note is an attachment.|<a href="Note.md" target="_blank">applicationCommon/Note</a>|
|[noteText](#noteText)|Text of the note.|<a href="Note.md" target="_blank">applicationCommon/Note</a>|
|[mimeType](#mimeType)|MIME type of the note's attachment.|<a href="Note.md" target="_blank">applicationCommon/Note</a>|
|[langId](#langId)|Language identifier for the note.|<a href="Note.md" target="_blank">applicationCommon/Note</a>|
|[documentBody](#documentBody)|Contents of the note's attachment.|<a href="Note.md" target="_blank">applicationCommon/Note</a>|
|[createdOn](#createdOn)|Date and time when the note was created.|<a href="Note.md" target="_blank">applicationCommon/Note</a>|
|[fileSize](#fileSize)|File size of the note.|<a href="Note.md" target="_blank">applicationCommon/Note</a>|
|[fileName](#fileName)|File name of the note.|<a href="Note.md" target="_blank">applicationCommon/Note</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the note.|<a href="Note.md" target="_blank">applicationCommon/Note</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who last modified the note.|<a href="Note.md" target="_blank">applicationCommon/Note</a>|
|[modifiedOn](#modifiedOn)|Date and time when the note was last modified.|<a href="Note.md" target="_blank">applicationCommon/Note</a>|
|[versionNumber](#versionNumber)|Version number of the note.|<a href="Note.md" target="_blank">applicationCommon/Note</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Note.md" target="_blank">applicationCommon/Note</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Note.md" target="_blank">applicationCommon/Note</a>|
|[stepId](#stepId)|workflow step id associated with the note.|<a href="Note.md" target="_blank">applicationCommon/Note</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Note.md" target="_blank">applicationCommon/Note</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Note.md" target="_blank">applicationCommon/Note</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the annotation.|<a href="Note.md" target="_blank">applicationCommon/Note</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who last modified the annotation.|<a href="Note.md" target="_blank">applicationCommon/Note</a>|
|[owningTeam](#owningTeam)|Unique identifier of the team who owns the note.|<a href="Note.md" target="_blank">applicationCommon/Note</a>|

### <a href=#annotationId name="annotationId">annotationId</a>

Unique identifier of the note.  
First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Note</td></tr><tr><td>description</td><td>Unique identifier of the note.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>annotationid</td></tr></table>

### <a href=#objectTypeCode name="objectTypeCode">objectTypeCode</a>

Type of entity with which the note is associated.  
First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Object Type </td></tr><tr><td>description</td><td>Type of entity with which the note is associated.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>objecttypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Account</td><td>1</td></tr><tr><td>en</td><td>Appointment</td><td>4201</td></tr><tr><td>en</td><td>Bulk Import</td><td>4407</td></tr><tr><td>en</td><td>Calendar</td><td>4003</td></tr><tr><td>en</td><td>Campaign</td><td>4400</td></tr><tr><td>en</td><td>Campaign Activity</td><td>4402</td></tr><tr><td>en</td><td>Campaign Response</td><td>4401</td></tr><tr><td>en</td><td>Case</td><td>112</td></tr><tr><td>en</td><td>Case Resolution</td><td>4206</td></tr><tr><td>en</td><td>Commitment</td><td>4215</td></tr><tr><td>en</td><td>Competitor</td><td>123</td></tr><tr><td>en</td><td>Contact</td><td>2</td></tr><tr><td>en</td><td>Contract</td><td>1010</td></tr><tr><td>en</td><td>Contract Line</td><td>1011</td></tr><tr><td>en</td><td>Email</td><td>4202</td></tr><tr><td>en</td><td>Facility/Equipment</td><td>4000</td></tr><tr><td>en</td><td>Fax</td><td>4204</td></tr><tr><td>en</td><td>Invoice</td><td>1090</td></tr><tr><td>en</td><td>Lead</td><td>4</td></tr><tr><td>en</td><td>Letter</td><td>4207</td></tr><tr><td>en</td><td>Marketing List</td><td>4300</td></tr><tr><td>en</td><td>Opportunity</td><td>3</td></tr><tr><td>en</td><td>Opportunity Close</td><td>4208</td></tr><tr><td>en</td><td>Order</td><td>1088</td></tr><tr><td>en</td><td>Order Close</td><td>4209</td></tr><tr><td>en</td><td>Phone Call</td><td>4210</td></tr><tr><td>en</td><td>Product</td><td>1024</td></tr><tr><td>en</td><td>Quote</td><td>1084</td></tr><tr><td>en</td><td>Quote Close</td><td>4211</td></tr><tr><td>en</td><td>Resource Specification</td><td>4006</td></tr><tr><td>en</td><td>Service</td><td>4001</td></tr><tr><td>en</td><td>Service Activity</td><td>4214</td></tr><tr><td>en</td><td>Task</td><td>4212</td></tr><tr><td>en</td><td>Routing Rule</td><td>8181</td></tr><tr><td>en</td><td>Routing Rule Item</td><td>8199</td></tr></table></td></tr></table>

### <a href=#objectTypeCode_display name="objectTypeCode_display">objectTypeCode_display</a>

First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user who owns the note.  
First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user who owns the note.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#objectIdTypeCode name="objectIdTypeCode">objectIdTypeCode</a>

The name of the entity linked by objectId  
First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>objectId Type</td></tr><tr><td>description</td><td>The name of the entity linked by objectId</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>objectidtypecode</td></tr></table>

### <a href=#objectId name="objectId">objectId</a>

Unique identifier of the object with which the note is associated.  
First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Regarding</td></tr><tr><td>description</td><td>Unique identifier of the object with which the note is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>objectid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier of the business unit that owns the note.  
First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier of the business unit that owns the note.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#subject name="subject">subject</a>

Subject associated with the note.  
First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Title</td></tr><tr><td>description</td><td>Subject associated with the note.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>subject</td></tr></table>

### <a href=#isDocument name="isDocument">isDocument</a>

Specifies whether the note is an attachment.  
First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Document</td></tr><tr><td>description</td><td>Specifies whether the note is an attachment.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isdocument</td></tr></table>

### <a href=#noteText name="noteText">noteText</a>

Text of the note.  
First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Text of the note.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>notetext</td></tr></table>

### <a href=#mimeType name="mimeType">mimeType</a>

MIME type of the note's attachment.  
First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mime Type</td></tr><tr><td>description</td><td>MIME type of the note's attachment.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>256</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mimetype</td></tr></table>

### <a href=#langId name="langId">langId</a>

Language identifier for the note.  
First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Language ID</td></tr><tr><td>description</td><td>Language identifier for the note.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>langid</td></tr></table>

### <a href=#documentBody name="documentBody">documentBody</a>

Contents of the note's attachment.  
First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Document</td></tr><tr><td>description</td><td>Contents of the note's attachment.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>documentbody</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the note was created.  
First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the note was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#fileSize name="fileSize">fileSize</a>

File size of the note.  
First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>File Size (Bytes)</td></tr><tr><td>description</td><td>File size of the note.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>filesize</td></tr></table>

### <a href=#fileName name="fileName">fileName</a>

File name of the note.  
First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>File Name</td></tr><tr><td>description</td><td>File name of the note.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>filename</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the note.  
First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the note.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who last modified the note.  
First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who last modified the note.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the note was last modified.  
First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the note was last modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version number of the note.  
First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version number of the note.</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#stepId name="stepId">stepId</a>

workflow step id associated with the note.  
First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Step Id</td></tr><tr><td>description</td><td>workflow step id associated with the note.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stepid</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the annotation.  
First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the annotation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who last modified the annotation.  
First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who last modified the annotation.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier of the team who owns the note.  
First included in: applicationCommon/Note (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier of the team who owns the note.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>
