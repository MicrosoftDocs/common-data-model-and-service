---
title: JournalizingPostingDefinitionEntryEntity in GeneralLedger - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Posting definition entry in GeneralLedger(JournalizingPostingDefinitionEntryEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/JournalizingPostingDefinitionEntryEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Posting definition entry</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[GeneratedEntryAccountStructure](#GeneratedEntryAccountStructure)||<a href="JournalizingPostingDefinitionEntryEntity.md" target="_blank">GeneralLedger/JournalizingPostingDefinitionEntryEntity</a>|
|[JournalizingDefinitionMatch](#JournalizingDefinitionMatch)||<a href="JournalizingPostingDefinitionEntryEntity.md" target="_blank">GeneralLedger/JournalizingPostingDefinitionEntryEntity</a>|
|[GeneratedEntriesDebitCredit](#GeneratedEntriesDebitCredit)||<a href="JournalizingPostingDefinitionEntryEntity.md" target="_blank">GeneralLedger/JournalizingPostingDefinitionEntryEntity</a>|
|[GeneratedEntryLedgerAccount](#GeneratedEntryLedgerAccount)||<a href="JournalizingPostingDefinitionEntryEntity.md" target="_blank">GeneralLedger/JournalizingPostingDefinitionEntryEntity</a>|
|[MatchCriteriaAccountStructure](#MatchCriteriaAccountStructure)||<a href="JournalizingPostingDefinitionEntryEntity.md" target="_blank">GeneralLedger/JournalizingPostingDefinitionEntryEntity</a>|
|[Priority](#Priority)||<a href="JournalizingPostingDefinitionEntryEntity.md" target="_blank">GeneralLedger/JournalizingPostingDefinitionEntryEntity</a>|
|[JournalizingDefinitionVersion](#JournalizingDefinitionVersion)||<a href="JournalizingPostingDefinitionEntryEntity.md" target="_blank">GeneralLedger/JournalizingPostingDefinitionEntryEntity</a>|
|[MatchCriteriaLedgerAccount](#MatchCriteriaLedgerAccount)||<a href="JournalizingPostingDefinitionEntryEntity.md" target="_blank">GeneralLedger/JournalizingPostingDefinitionEntryEntity</a>|
|[MatchCriteriaLedgerAccountDisplayValue](#MatchCriteriaLedgerAccountDisplayValue)||<a href="JournalizingPostingDefinitionEntryEntity.md" target="_blank">GeneralLedger/JournalizingPostingDefinitionEntryEntity</a>|
|[MatchCriteriaLedgerAccountAccountStructure](#MatchCriteriaLedgerAccountAccountStructure)||<a href="JournalizingPostingDefinitionEntryEntity.md" target="_blank">GeneralLedger/JournalizingPostingDefinitionEntryEntity</a>|
|[GeneratedEntryLedgerAccountDisplayValue](#GeneratedEntryLedgerAccountDisplayValue)||<a href="JournalizingPostingDefinitionEntryEntity.md" target="_blank">GeneralLedger/JournalizingPostingDefinitionEntryEntity</a>|
|[GeneratedEntryLedgerAccountAccountStructure](#GeneratedEntryLedgerAccountAccountStructure)||<a href="JournalizingPostingDefinitionEntryEntity.md" target="_blank">GeneralLedger/JournalizingPostingDefinitionEntryEntity</a>|
|[PostingDefinitionId](#PostingDefinitionId)||<a href="JournalizingPostingDefinitionEntryEntity.md" target="_blank">GeneralLedger/JournalizingPostingDefinitionEntryEntity</a>|
|[ValidFrom](#ValidFrom)||<a href="JournalizingPostingDefinitionEntryEntity.md" target="_blank">GeneralLedger/JournalizingPostingDefinitionEntryEntity</a>|
|[Relationship_MatchAccountNumberDAVCRelationshipId](#Relationship_MatchAccountNumberDAVCRelationshipId)||<a href="JournalizingPostingDefinitionEntryEntity.md" target="_blank">GeneralLedger/JournalizingPostingDefinitionEntryEntity</a>|
|[Relationship_GeneratedAccountNumberDAVCRelationshipId](#Relationship_GeneratedAccountNumberDAVCRelationshipId)||<a href="JournalizingPostingDefinitionEntryEntity.md" target="_blank">GeneralLedger/JournalizingPostingDefinitionEntryEntity</a>|
|[BackingTable_JournalizingDefinitionMatchDetailRelationshipId](#BackingTable_JournalizingDefinitionMatchDetailRelationshipId)||<a href="JournalizingPostingDefinitionEntryEntity.md" target="_blank">GeneralLedger/JournalizingPostingDefinitionEntryEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="JournalizingPostingDefinitionEntryEntity.md" target="_blank">GeneralLedger/JournalizingPostingDefinitionEntryEntity</a>|

### <a href=#GeneratedEntryAccountStructure name="GeneratedEntryAccountStructure">GeneratedEntryAccountStructure</a>

First included in: GeneralLedger/JournalizingPostingDefinitionEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Generated entry account structure</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneratedEntryAccountStructure attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Generated entry account structure</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalizingDefinitionMatch name="JournalizingDefinitionMatch">JournalizingDefinitionMatch</a>

First included in: GeneralLedger/JournalizingPostingDefinitionEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalizingDefinitionMatch attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneratedEntriesDebitCredit name="GeneratedEntriesDebitCredit">GeneratedEntriesDebitCredit</a>

First included in: GeneralLedger/JournalizingPostingDefinitionEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Generated entries debit credit</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneratedEntriesDebitCredit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Generated entries debit credit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneratedEntryLedgerAccount name="GeneratedEntryLedgerAccount">GeneratedEntryLedgerAccount</a>

First included in: GeneralLedger/JournalizingPostingDefinitionEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Generated entry ledger account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneratedEntryLedgerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Generated entry ledger account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MatchCriteriaAccountStructure name="MatchCriteriaAccountStructure">MatchCriteriaAccountStructure</a>

First included in: GeneralLedger/JournalizingPostingDefinitionEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Match criteria account structure</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MatchCriteriaAccountStructure attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Match criteria account structure</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Priority name="Priority">Priority</a>

First included in: GeneralLedger/JournalizingPostingDefinitionEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Priority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalizingDefinitionVersion name="JournalizingDefinitionVersion">JournalizingDefinitionVersion</a>

First included in: GeneralLedger/JournalizingPostingDefinitionEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalizingDefinitionVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MatchCriteriaLedgerAccount name="MatchCriteriaLedgerAccount">MatchCriteriaLedgerAccount</a>

First included in: GeneralLedger/JournalizingPostingDefinitionEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Match criteria ledger account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MatchCriteriaLedgerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Match criteria ledger account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MatchCriteriaLedgerAccountDisplayValue name="MatchCriteriaLedgerAccountDisplayValue">MatchCriteriaLedgerAccountDisplayValue</a>

First included in: GeneralLedger/JournalizingPostingDefinitionEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Match criteria ledger account display value</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MatchCriteriaLedgerAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Match criteria ledger account display value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MatchCriteriaLedgerAccountAccountStructure name="MatchCriteriaLedgerAccountAccountStructure">MatchCriteriaLedgerAccountAccountStructure</a>

First included in: GeneralLedger/JournalizingPostingDefinitionEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MatchCriteriaLedgerAccountAccountStructure attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneratedEntryLedgerAccountDisplayValue name="GeneratedEntryLedgerAccountDisplayValue">GeneratedEntryLedgerAccountDisplayValue</a>

First included in: GeneralLedger/JournalizingPostingDefinitionEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Generated entry ledger account display value</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneratedEntryLedgerAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Generated entry ledger account display value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneratedEntryLedgerAccountAccountStructure name="GeneratedEntryLedgerAccountAccountStructure">GeneratedEntryLedgerAccountAccountStructure</a>

First included in: GeneralLedger/JournalizingPostingDefinitionEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Generated entry account structure display value</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneratedEntryLedgerAccountAccountStructure attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Generated entry account structure display value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingDefinitionId name="PostingDefinitionId">PostingDefinitionId</a>

First included in: GeneralLedger/JournalizingPostingDefinitionEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingDefinitionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: GeneralLedger/JournalizingPostingDefinitionEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MatchAccountNumberDAVCRelationshipId name="Relationship_MatchAccountNumberDAVCRelationshipId">Relationship_MatchAccountNumberDAVCRelationshipId</a>

First included in: GeneralLedger/JournalizingPostingDefinitionEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MatchAccountNumberDAVCRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_GeneratedAccountNumberDAVCRelationshipId name="Relationship_GeneratedAccountNumberDAVCRelationshipId">Relationship_GeneratedAccountNumberDAVCRelationshipId</a>

First included in: GeneralLedger/JournalizingPostingDefinitionEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_GeneratedAccountNumberDAVCRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_JournalizingDefinitionMatchDetailRelationshipId name="BackingTable_JournalizingDefinitionMatchDetailRelationshipId">BackingTable_JournalizingDefinitionMatchDetailRelationshipId</a>

First included in: GeneralLedger/JournalizingPostingDefinitionEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_JournalizingDefinitionMatchDetailRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountingFoundation/Main/JournalizingDefinitionMatchDetail.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/Main/JournalizingDefinitionMatchDetail.cdm.json/JournalizingDefinitionMatchDetail</a></td><td><a href="../../../Tables/Finance/AccountingFoundation/Main/JournalizingDefinitionMatchDetail.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: GeneralLedger/JournalizingPostingDefinitionEntryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
