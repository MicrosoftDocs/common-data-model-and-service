---
title: GeneralJournalAccountEntryDimension in Main - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# General journal account entry dimension in Main(GeneralJournalAccountEntryDimension)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Ledger/Main/GeneralJournalAccountEntryDimension.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[GeneralJournalAccountEntryDimension/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>General journal account entry dimension</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="GeneralJournalAccountEntryDimension.md" target="_blank">Main/GeneralJournalAccountEntryDimension</a>|
|[CurrentSessionId](#CurrentSessionId)||<a href="GeneralJournalAccountEntryDimension.md" target="_blank">Main/GeneralJournalAccountEntryDimension</a>|
|[GeneralJournalAccountEntry](#GeneralJournalAccountEntry)||<a href="GeneralJournalAccountEntryDimension.md" target="_blank">Main/GeneralJournalAccountEntryDimension</a>|
|[GeneralJournalAccountEntryHash](#GeneralJournalAccountEntryHash)||<a href="GeneralJournalAccountEntryDimension.md" target="_blank">Main/GeneralJournalAccountEntryDimension</a>|
|[MainAccount](#MainAccount)||<a href="GeneralJournalAccountEntryDimension.md" target="_blank">Main/GeneralJournalAccountEntryDimension</a>|
|[PostingLayer](#PostingLayer)||<a href="GeneralJournalAccountEntryDimension.md" target="_blank">Main/GeneralJournalAccountEntryDimension</a>|
|[SessionId](#SessionId)||<a href="GeneralJournalAccountEntryDimension.md" target="_blank">Main/GeneralJournalAccountEntryDimension</a>|
|[Type](#Type)||<a href="GeneralJournalAccountEntryDimension.md" target="_blank">Main/GeneralJournalAccountEntryDimension</a>|
|[UTCTimestamp](#UTCTimestamp)||<a href="GeneralJournalAccountEntryDimension.md" target="_blank">Main/GeneralJournalAccountEntryDimension</a>|
|[DataAreaId](#DataAreaId)||<a href="GeneralJournalAccountEntryDimension.md" target="_blank">Main/GeneralJournalAccountEntryDimension</a>|
|[Relationship_GeneralJournalAccountEntryRelationshipId](#Relationship_GeneralJournalAccountEntryRelationshipId)||<a href="GeneralJournalAccountEntryDimension.md" target="_blank">Main/GeneralJournalAccountEntryDimension</a>|
|[Relationship_GeneralJournalAccountEntryHashRelationshipId](#Relationship_GeneralJournalAccountEntryHashRelationshipId)||<a href="GeneralJournalAccountEntryDimension.md" target="_blank">Main/GeneralJournalAccountEntryDimension</a>|
|[Relationship_MainAccountRelationshipId](#Relationship_MainAccountRelationshipId)||<a href="GeneralJournalAccountEntryDimension.md" target="_blank">Main/GeneralJournalAccountEntryDimension</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="GeneralJournalAccountEntryDimension.md" target="_blank">Main/GeneralJournalAccountEntryDimension</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/GeneralJournalAccountEntryDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[GeneralJournalAccountEntryDimension/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CurrentSessionId name="CurrentSessionId">CurrentSessionId</a>

First included in: Main/GeneralJournalAccountEntryDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentSessionId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#GeneralJournalAccountEntry name="GeneralJournalAccountEntry">GeneralJournalAccountEntry</a>

First included in: Main/GeneralJournalAccountEntryDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralJournalAccountEntry attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#GeneralJournalAccountEntryHash name="GeneralJournalAccountEntryHash">GeneralJournalAccountEntryHash</a>

First included in: Main/GeneralJournalAccountEntryDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralJournalAccountEntryHash attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MainAccount name="MainAccount">MainAccount</a>

First included in: Main/GeneralJournalAccountEntryDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PostingLayer name="PostingLayer">PostingLayer</a>

First included in: Main/GeneralJournalAccountEntryDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingLayer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SessionId name="SessionId">SessionId</a>

First included in: Main/GeneralJournalAccountEntryDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SessionId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Type name="Type">Type</a>

First included in: Main/GeneralJournalAccountEntryDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Type attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#UTCTimestamp name="UTCTimestamp">UTCTimestamp</a>

First included in: Main/GeneralJournalAccountEntryDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UTCTimestamp attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/GeneralJournalAccountEntryDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_GeneralJournalAccountEntryRelationshipId name="Relationship_GeneralJournalAccountEntryRelationshipId">Relationship_GeneralJournalAccountEntryRelationshipId</a>

First included in: Main/GeneralJournalAccountEntryDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_GeneralJournalAccountEntryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../TransactionLine/GeneralJournalAccountEntry.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/TransactionLine/GeneralJournalAccountEntry.cdm.json/GeneralJournalAccountEntry</a></td><td><a href="../TransactionLine/GeneralJournalAccountEntry.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_GeneralJournalAccountEntryHashRelationshipId name="Relationship_GeneralJournalAccountEntryHashRelationshipId">Relationship_GeneralJournalAccountEntryHashRelationshipId</a>

First included in: Main/GeneralJournalAccountEntryDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_GeneralJournalAccountEntryHashRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="GeneralJournalAccountEntryHash.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/GeneralJournalAccountEntryHash.cdm.json/GeneralJournalAccountEntryHash</a></td><td><a href="GeneralJournalAccountEntryHash.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MainAccountRelationshipId name="Relationship_MainAccountRelationshipId">Relationship_MainAccountRelationshipId</a>

First included in: Main/GeneralJournalAccountEntryDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MainAccountRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/MainAccount.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/MainAccount.cdm.json/MainAccount</a></td><td><a href="../../FinancialDimensions/Main/MainAccount.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/GeneralJournalAccountEntryDimension (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
