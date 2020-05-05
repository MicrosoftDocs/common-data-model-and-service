---
title: ProjCDSTransactionRelationshipImportEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Integration entity for project transaction relationships

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/ProfessionalServices/ProjectManagementAndAccounting/ProjCDSTransactionRelationshipImportEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Integration entity for project transaction relationships</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ConnectionId](#ConnectionId)||<a href="ProjCDSTransactionRelationshipImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSTransactionRelationshipImportEntity</a>|
|[Transaction1Id](#Transaction1Id)||<a href="ProjCDSTransactionRelationshipImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSTransactionRelationshipImportEntity</a>|
|[Transaction1Role](#Transaction1Role)||<a href="ProjCDSTransactionRelationshipImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSTransactionRelationshipImportEntity</a>|
|[Transaction1Type](#Transaction1Type)||<a href="ProjCDSTransactionRelationshipImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSTransactionRelationshipImportEntity</a>|
|[Transaction2Id](#Transaction2Id)||<a href="ProjCDSTransactionRelationshipImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSTransactionRelationshipImportEntity</a>|
|[Transaction2Role](#Transaction2Role)||<a href="ProjCDSTransactionRelationshipImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSTransactionRelationshipImportEntity</a>|
|[Transaction2Type](#Transaction2Type)||<a href="ProjCDSTransactionRelationshipImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSTransactionRelationshipImportEntity</a>|
|[BackingTable_ProjCDSTransactionRelationshipImportRelationshipId](#BackingTable_ProjCDSTransactionRelationshipImportRelationshipId)||<a href="ProjCDSTransactionRelationshipImportEntity.md" target="_blank">ProjectManagementAndAccounting/ProjCDSTransactionRelationshipImportEntity</a>|

### <a href=#ConnectionId name="ConnectionId">ConnectionId</a>

First included in: ProjectManagementAndAccounting/ProjCDSTransactionRelationshipImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConnectionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Transaction1Id name="Transaction1Id">Transaction1Id</a>

First included in: ProjectManagementAndAccounting/ProjCDSTransactionRelationshipImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Transaction1Id attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Transaction1Role name="Transaction1Role">Transaction1Role</a>

First included in: ProjectManagementAndAccounting/ProjCDSTransactionRelationshipImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Transaction1Role attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Transaction1Type name="Transaction1Type">Transaction1Type</a>

First included in: ProjectManagementAndAccounting/ProjCDSTransactionRelationshipImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Transaction1Type attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Transaction2Id name="Transaction2Id">Transaction2Id</a>

First included in: ProjectManagementAndAccounting/ProjCDSTransactionRelationshipImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Transaction2Id attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Transaction2Role name="Transaction2Role">Transaction2Role</a>

First included in: ProjectManagementAndAccounting/ProjCDSTransactionRelationshipImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Transaction2Role attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Transaction2Type name="Transaction2Type">Transaction2Type</a>

First included in: ProjectManagementAndAccounting/ProjCDSTransactionRelationshipImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Transaction2Type attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_ProjCDSTransactionRelationshipImportRelationshipId name="BackingTable_ProjCDSTransactionRelationshipImportRelationshipId">BackingTable_ProjCDSTransactionRelationshipImportRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjCDSTransactionRelationshipImportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ProjCDSTransactionRelationshipImportRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Miscellaneous/ProjCDSTransactionRelationshipImport.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Miscellaneous/ProjCDSTransactionRelationshipImport.cdm.json/ProjCDSTransactionRelationshipImport</a></td><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Miscellaneous/ProjCDSTransactionRelationshipImport.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
