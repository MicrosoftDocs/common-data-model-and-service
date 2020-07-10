---
title: SourceDocumentLineDomainEventReferenceIdentity in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# SourceDocumentLineDomainEventReferenceIdentity in Miscellaneous

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/AccountingFoundation/Miscellaneous/SourceDocumentLineDomainEventReferenceIdentity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SourceDocumentLineDomainEventReferenceIdentity/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="SourceDocumentLineDomainEventReferenceIdentity.md" target="_blank">Miscellaneous/SourceDocumentLineDomainEventReferenceIdentity</a>|
|[SourceDocumentLine](#SourceDocumentLine)||<a href="SourceDocumentLineDomainEventReferenceIdentity.md" target="_blank">Miscellaneous/SourceDocumentLineDomainEventReferenceIdentity</a>|
|[SourceDocumentDomainEventReferenceIdentity](#SourceDocumentDomainEventReferenceIdentity)||<a href="SourceDocumentLineDomainEventReferenceIdentity.md" target="_blank">Miscellaneous/SourceDocumentLineDomainEventReferenceIdentity</a>|
|[LineDate](#LineDate)||<a href="SourceDocumentLineDomainEventReferenceIdentity.md" target="_blank">Miscellaneous/SourceDocumentLineDomainEventReferenceIdentity</a>|
|[Voucher](#Voucher)||<a href="SourceDocumentLineDomainEventReferenceIdentity.md" target="_blank">Miscellaneous/SourceDocumentLineDomainEventReferenceIdentity</a>|
|[Relationship_SourceDocumentLineRelationshipId](#Relationship_SourceDocumentLineRelationshipId)||<a href="SourceDocumentLineDomainEventReferenceIdentity.md" target="_blank">Miscellaneous/SourceDocumentLineDomainEventReferenceIdentity</a>|
|[Relationship_SourceDocumentDomainEventReferenceIdentityRelationshipId](#Relationship_SourceDocumentDomainEventReferenceIdentityRelationshipId)||<a href="SourceDocumentLineDomainEventReferenceIdentity.md" target="_blank">Miscellaneous/SourceDocumentLineDomainEventReferenceIdentity</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/SourceDocumentLineDomainEventReferenceIdentity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SourceDocumentLineDomainEventReferenceIdentity/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SourceDocumentLine name="SourceDocumentLine">SourceDocumentLine</a>

First included in: Miscellaneous/SourceDocumentLineDomainEventReferenceIdentity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceDocumentLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SourceDocumentDomainEventReferenceIdentity name="SourceDocumentDomainEventReferenceIdentity">SourceDocumentDomainEventReferenceIdentity</a>

First included in: Miscellaneous/SourceDocumentLineDomainEventReferenceIdentity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceDocumentDomainEventReferenceIdentity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LineDate name="LineDate">LineDate</a>

First included in: Miscellaneous/SourceDocumentLineDomainEventReferenceIdentity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: Miscellaneous/SourceDocumentLineDomainEventReferenceIdentity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Voucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SourceDocumentLineRelationshipId name="Relationship_SourceDocumentLineRelationshipId">Relationship_SourceDocumentLineRelationshipId</a>

First included in: Miscellaneous/SourceDocumentLineDomainEventReferenceIdentity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SourceDocumentLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../TransactionLine/SourceDocumentLine.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/TransactionLine/SourceDocumentLine.cdm.json/SourceDocumentLine</a></td><td><a href="../TransactionLine/SourceDocumentLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SourceDocumentDomainEventReferenceIdentityRelationshipId name="Relationship_SourceDocumentDomainEventReferenceIdentityRelationshipId">Relationship_SourceDocumentDomainEventReferenceIdentityRelationshipId</a>

First included in: Miscellaneous/SourceDocumentLineDomainEventReferenceIdentity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SourceDocumentDomainEventReferenceIdentityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="SourceDocumentDomainEventReferenceIdentity.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/Miscellaneous/SourceDocumentDomainEventReferenceIdentity.cdm.json/SourceDocumentDomainEventReferenceIdentity</a></td><td><a href="SourceDocumentDomainEventReferenceIdentity.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
