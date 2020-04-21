---
title: DocuDeletedRef - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# DocuDeletedRef

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/WorksheetLine/DocuDeletedRef.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DocuDeletedRef/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="DocuDeletedRef.md" target="_blank">WorksheetLine/DocuDeletedRef</a>|
|[RefCompanyId](#RefCompanyId)||<a href="DocuDeletedRef.md" target="_blank">WorksheetLine/DocuDeletedRef</a>|
|[ActualCompanyId](#ActualCompanyId)||<a href="DocuDeletedRef.md" target="_blank">WorksheetLine/DocuDeletedRef</a>|
|[Author](#Author)||<a href="DocuDeletedRef.md" target="_blank">WorksheetLine/DocuDeletedRef</a>|
|[InterCompanySkipUpdate](#InterCompanySkipUpdate)||<a href="DocuDeletedRef.md" target="_blank">WorksheetLine/DocuDeletedRef</a>|
|[Name](#Name)||<a href="DocuDeletedRef.md" target="_blank">WorksheetLine/DocuDeletedRef</a>|
|[Notes](#Notes)||<a href="DocuDeletedRef.md" target="_blank">WorksheetLine/DocuDeletedRef</a>|
|[Party](#Party)||<a href="DocuDeletedRef.md" target="_blank">WorksheetLine/DocuDeletedRef</a>|
|[RefRecId](#RefRecId)||<a href="DocuDeletedRef.md" target="_blank">WorksheetLine/DocuDeletedRef</a>|
|[RefTableId](#RefTableId)||<a href="DocuDeletedRef.md" target="_blank">WorksheetLine/DocuDeletedRef</a>|
|[Restriction](#Restriction)||<a href="DocuDeletedRef.md" target="_blank">WorksheetLine/DocuDeletedRef</a>|
|[TypeId](#TypeId)||<a href="DocuDeletedRef.md" target="_blank">WorksheetLine/DocuDeletedRef</a>|
|[ValueRecId](#ValueRecId)||<a href="DocuDeletedRef.md" target="_blank">WorksheetLine/DocuDeletedRef</a>|
|[DocumentId](#DocumentId)||<a href="DocuDeletedRef.md" target="_blank">WorksheetLine/DocuDeletedRef</a>|
|[DefaultAttachment](#DefaultAttachment)||<a href="DocuDeletedRef.md" target="_blank">WorksheetLine/DocuDeletedRef</a>|
|[RemoveOption](#RemoveOption)||<a href="DocuDeletedRef.md" target="_blank">WorksheetLine/DocuDeletedRef</a>|
|[Caption](#Caption)||<a href="DocuDeletedRef.md" target="_blank">WorksheetLine/DocuDeletedRef</a>|
|[ExtensionFields](#ExtensionFields)||<a href="DocuDeletedRef.md" target="_blank">WorksheetLine/DocuDeletedRef</a>|
|[FileRemovalConfirmationResponse](#FileRemovalConfirmationResponse)||<a href="DocuDeletedRef.md" target="_blank">WorksheetLine/DocuDeletedRef</a>|
|[PhysicalFileForceDeletion](#PhysicalFileForceDeletion)||<a href="DocuDeletedRef.md" target="_blank">WorksheetLine/DocuDeletedRef</a>|
|[DocuType](#DocuType)||<a href="DocuDeletedRef.md" target="_blank">WorksheetLine/DocuDeletedRef</a>|
|[Relationship_DocuDeletedValueRelationshipId](#Relationship_DocuDeletedValueRelationshipId)||<a href="DocuDeletedRef.md" target="_blank">WorksheetLine/DocuDeletedRef</a>|
|[Relationship_DocuValueRelationshipId](#Relationship_DocuValueRelationshipId)||<a href="DocuDeletedRef.md" target="_blank">WorksheetLine/DocuDeletedRef</a>|
|[Relationship_DocuTypeRelationshipId](#Relationship_DocuTypeRelationshipId)||<a href="DocuDeletedRef.md" target="_blank">WorksheetLine/DocuDeletedRef</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/DocuDeletedRef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DocuDeletedRef/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RefCompanyId name="RefCompanyId">RefCompanyId</a>

First included in: WorksheetLine/DocuDeletedRef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefCompanyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActualCompanyId name="ActualCompanyId">ActualCompanyId</a>

First included in: WorksheetLine/DocuDeletedRef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualCompanyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Author name="Author">Author</a>

First included in: WorksheetLine/DocuDeletedRef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Author attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InterCompanySkipUpdate name="InterCompanySkipUpdate">InterCompanySkipUpdate</a>

First included in: WorksheetLine/DocuDeletedRef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterCompanySkipUpdate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: WorksheetLine/DocuDeletedRef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Notes name="Notes">Notes</a>

First included in: WorksheetLine/DocuDeletedRef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Notes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Party name="Party">Party</a>

First included in: WorksheetLine/DocuDeletedRef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Party attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RefRecId name="RefRecId">RefRecId</a>

First included in: WorksheetLine/DocuDeletedRef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RefTableId name="RefTableId">RefTableId</a>

First included in: WorksheetLine/DocuDeletedRef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#Restriction name="Restriction">Restriction</a>

First included in: WorksheetLine/DocuDeletedRef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Restriction attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TypeId name="TypeId">TypeId</a>

First included in: WorksheetLine/DocuDeletedRef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValueRecId name="ValueRecId">ValueRecId</a>

First included in: WorksheetLine/DocuDeletedRef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValueRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DocumentId name="DocumentId">DocumentId</a>

First included in: WorksheetLine/DocuDeletedRef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultAttachment name="DefaultAttachment">DefaultAttachment</a>

First included in: WorksheetLine/DocuDeletedRef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultAttachment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RemoveOption name="RemoveOption">RemoveOption</a>

First included in: WorksheetLine/DocuDeletedRef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemoveOption attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Caption name="Caption">Caption</a>

First included in: WorksheetLine/DocuDeletedRef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Caption attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExtensionFields name="ExtensionFields">ExtensionFields</a>

First included in: WorksheetLine/DocuDeletedRef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExtensionFields attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#FileRemovalConfirmationResponse name="FileRemovalConfirmationResponse">FileRemovalConfirmationResponse</a>

First included in: WorksheetLine/DocuDeletedRef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FileRemovalConfirmationResponse attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PhysicalFileForceDeletion name="PhysicalFileForceDeletion">PhysicalFileForceDeletion</a>

First included in: WorksheetLine/DocuDeletedRef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalFileForceDeletion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DocuType name="DocuType">DocuType</a>

First included in: WorksheetLine/DocuDeletedRef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_DocuDeletedValueRelationshipId name="Relationship_DocuDeletedValueRelationshipId">Relationship_DocuDeletedValueRelationshipId</a>

First included in: WorksheetLine/DocuDeletedRef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DocuDeletedValueRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/DocuDeletedValue.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Transaction/DocuDeletedValue.cdm.json/DocuDeletedValue</a></td><td><a href="../Transaction/DocuDeletedValue.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DocuValueRelationshipId name="Relationship_DocuValueRelationshipId">Relationship_DocuValueRelationshipId</a>

First included in: WorksheetLine/DocuDeletedRef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DocuValueRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/DocuValue.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Transaction/DocuValue.cdm.json/DocuValue</a></td><td><a href="../Transaction/DocuValue.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DocuTypeRelationshipId name="Relationship_DocuTypeRelationshipId">Relationship_DocuTypeRelationshipId</a>

First included in: WorksheetLine/DocuDeletedRef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DocuTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/DocuType.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Group/DocuType.cdm.json/DocuType</a></td><td><a href="../Group/DocuType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
