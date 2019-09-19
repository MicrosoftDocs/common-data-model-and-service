---
title: SalesAttachment - Common Data Model | Microsoft Docs
description: Item in the sales literature collection.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Sales Attachment

Item in the sales literature collection.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/sales/SalesAttachment.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/sales/SalesAttachment  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[salesLiteratureItemId](#salesLiteratureItemId)|Unique identifier for the document.|<a href="SalesAttachment.md" target="_blank">sales/SalesAttachment</a>|
|[createdOn](#createdOn)|Date and time when the document was created.|<a href="SalesAttachment.md" target="_blank">sales/SalesAttachment</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the document.|<a href="SalesAttachment.md" target="_blank">sales/SalesAttachment</a>|
|[modifiedOn](#modifiedOn)|Date and time when the document was last modified.|<a href="SalesAttachment.md" target="_blank">sales/SalesAttachment</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who last modified the document.|<a href="SalesAttachment.md" target="_blank">sales/SalesAttachment</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the salesliteratureitem.|<a href="SalesAttachment.md" target="_blank">sales/SalesAttachment</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who last modified the salesliteratureitem.|<a href="SalesAttachment.md" target="_blank">sales/SalesAttachment</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="SalesAttachment.md" target="_blank">sales/SalesAttachment</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="SalesAttachment.md" target="_blank">sales/SalesAttachment</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="SalesAttachment.md" target="_blank">sales/SalesAttachment</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="SalesAttachment.md" target="_blank">sales/SalesAttachment</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="SalesAttachment.md" target="_blank">sales/SalesAttachment</a>|
|[title](#title)|Type the title or name that describes the document.|<a href="SalesAttachment.md" target="_blank">sales/SalesAttachment</a>|
|[abstract](#abstract)|Abstract of the document.|<a href="SalesAttachment.md" target="_blank">sales/SalesAttachment</a>|
|[attachedDocumentUrl](#attachedDocumentUrl)|URL of the Website on which the document is located.|<a href="SalesAttachment.md" target="_blank">sales/SalesAttachment</a>|
|[authorName](#authorName)|Author name for the document.|<a href="SalesAttachment.md" target="_blank">sales/SalesAttachment</a>|
|[documentBody](#documentBody)|Shows the encoded contents of the sales literature document attachment.|<a href="SalesAttachment.md" target="_blank">sales/SalesAttachment</a>|
|[fileName](#fileName)|File name of the document.|<a href="SalesAttachment.md" target="_blank">sales/SalesAttachment</a>|
|[fileSize](#fileSize)|File size of the document.|<a href="SalesAttachment.md" target="_blank">sales/SalesAttachment</a>|
|[fileTypeCode](#fileTypeCode)|Select the file type of the document.|<a href="SalesAttachment.md" target="_blank">sales/SalesAttachment</a>|
|[fileTypeCode_display](#fileTypeCode_display)||<a href="SalesAttachment.md" target="_blank">sales/SalesAttachment</a>|
|[isCustomerViewable](#isCustomerViewable)|Tells whether the document can be shared with customers or is for internal use only.|<a href="SalesAttachment.md" target="_blank">sales/SalesAttachment</a>|
|[keyWords](#keyWords)|Keywords to use for searches in documents.|<a href="SalesAttachment.md" target="_blank">sales/SalesAttachment</a>|
|[mimeType](#mimeType)|Shows the file type of the sales literature document attachment, such as text or document.|<a href="SalesAttachment.md" target="_blank">sales/SalesAttachment</a>|
|[organizationId](#organizationId)|Unique identifier of the organization associated with the document.|<a href="SalesAttachment.md" target="_blank">sales/SalesAttachment</a>|
|[salesLiteratureId](#salesLiteratureId)|Unique identifier of the sales literature that is associated with the individual item.|<a href="SalesAttachment.md" target="_blank">sales/SalesAttachment</a>|
|[mode](#mode)|Defines the mode of the sales literature document attachment.|<a href="SalesAttachment.md" target="_blank">sales/SalesAttachment</a>|

### <a href=#salesLiteratureItemId name="salesLiteratureItemId">salesLiteratureItemId</a>

Unique identifier for the document.  
First included in: sales/SalesAttachment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales Literature Item</td></tr><tr><td>description</td><td>Unique identifier for the document.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>salesliteratureitemid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the document was created.  
First included in: sales/SalesAttachment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the document was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the document.  
First included in: sales/SalesAttachment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the document.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the document was last modified.  
First included in: sales/SalesAttachment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the document was last modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who last modified the document.  
First included in: sales/SalesAttachment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who last modified the document.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the salesliteratureitem.  
First included in: sales/SalesAttachment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the salesliteratureitem.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who last modified the salesliteratureitem.  
First included in: sales/SalesAttachment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who last modified the salesliteratureitem.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: sales/SalesAttachment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: sales/SalesAttachment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: sales/SalesAttachment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: sales/SalesAttachment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: sales/SalesAttachment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#title name="title">title</a>

Type the title or name that describes the document.  
First included in: sales/SalesAttachment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Title</td></tr><tr><td>description</td><td>Type the title or name that describes the document.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>title</td></tr></table>

### <a href=#abstract name="abstract">abstract</a>

Abstract of the document.  
First included in: sales/SalesAttachment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Abstract</td></tr><tr><td>description</td><td>Abstract of the document.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>abstract</td></tr></table>

### <a href=#attachedDocumentUrl name="attachedDocumentUrl">attachedDocumentUrl</a>

URL of the Website on which the document is located.  
First included in: sales/SalesAttachment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Attached Document URL</td></tr><tr><td>description</td><td>URL of the Website on which the document is located.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>attacheddocumenturl</td></tr></table>

### <a href=#authorName name="authorName">authorName</a>

Author name for the document.  
First included in: sales/SalesAttachment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Author Name</td></tr><tr><td>description</td><td>Author name for the document.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>authorname</td></tr></table>

### <a href=#documentBody name="documentBody">documentBody</a>

Shows the encoded contents of the sales literature document attachment.  
First included in: sales/SalesAttachment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Shows the encoded contents of the sales literature document attachment.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>documentbody</td></tr></table>

### <a href=#fileName name="fileName">fileName</a>

File name of the document.  
First included in: sales/SalesAttachment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>File Name</td></tr><tr><td>description</td><td>File name of the document.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>filename</td></tr></table>

### <a href=#fileSize name="fileSize">fileSize</a>

File size of the document.  
First included in: sales/SalesAttachment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>File Size (Bytes)</td></tr><tr><td>description</td><td>File size of the document.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>filesize</td></tr></table>

### <a href=#fileTypeCode name="fileTypeCode">fileTypeCode</a>

Select the file type of the document.  
First included in: sales/SalesAttachment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>File Type</td></tr><tr><td>description</td><td>Select the file type of the document.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>filetypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#fileTypeCode_display name="fileTypeCode_display">fileTypeCode_display</a>

First included in: sales/SalesAttachment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#isCustomerViewable name="isCustomerViewable">isCustomerViewable</a>

Tells whether the document can be shared with customers or is for internal use only.  
First included in: sales/SalesAttachment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Viewable</td></tr><tr><td>description</td><td>Tells whether the document can be shared with customers or is for internal use only.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>iscustomerviewable</td></tr></table>

### <a href=#keyWords name="keyWords">keyWords</a>

Keywords to use for searches in documents.  
First included in: sales/SalesAttachment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Key Words</td></tr><tr><td>description</td><td>Keywords to use for searches in documents.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>keywords</td></tr></table>

### <a href=#mimeType name="mimeType">mimeType</a>

Shows the file type of the sales literature document attachment, such as text or document.  
First included in: sales/SalesAttachment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mime Type</td></tr><tr><td>description</td><td>Shows the file type of the sales literature document attachment, such as text or document.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>256</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mimetype</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier of the organization associated with the document.  
First included in: sales/SalesAttachment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization </td></tr><tr><td>description</td><td>Unique identifier of the organization associated with the document.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#salesLiteratureId name="salesLiteratureId">salesLiteratureId</a>

Unique identifier of the sales literature that is associated with the individual item.  
First included in: sales/SalesAttachment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales Literature</td></tr><tr><td>description</td><td>Unique identifier of the sales literature that is associated with the individual item.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>salesliteratureid</td></tr></table>

### <a href=#mode name="mode">mode</a>

Defines the mode of the sales literature document attachment.  
First included in: sales/SalesAttachment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mode</td></tr><tr><td>description</td><td>Defines the mode of the sales literature document attachment.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>256</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>mode</td></tr></table>
