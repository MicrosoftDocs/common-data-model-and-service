---
title: JournalizingTransactionPostingDefinitionPayableEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Transaction posting definition payable

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transaction posting definition payable</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AccountsPayableTransactionType](#AccountsPayableTransactionType)||<a href="JournalizingTransactionPostingDefinitionPayableEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity</a>|
|[CategoryRelationRecId](#CategoryRelationRecId)||<a href="JournalizingTransactionPostingDefinitionPayableEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity</a>|
|[ItemCodeTableGroupCategoryAll](#ItemCodeTableGroupCategoryAll)||<a href="JournalizingTransactionPostingDefinitionPayableEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity</a>|
|[ItemRelationGroup](#ItemRelationGroup)||<a href="JournalizingTransactionPostingDefinitionPayableEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity</a>|
|[ItemRelationNumber](#ItemRelationNumber)||<a href="JournalizingTransactionPostingDefinitionPayableEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity</a>|
|[PostingDefinition](#PostingDefinition)||<a href="JournalizingTransactionPostingDefinitionPayableEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity</a>|
|[AccountRelationVendorAccount](#AccountRelationVendorAccount)||<a href="JournalizingTransactionPostingDefinitionPayableEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity</a>|
|[AccountCodeTableGroupAll](#AccountCodeTableGroupAll)||<a href="JournalizingTransactionPostingDefinitionPayableEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity</a>|
|[AccountRelationVendorGroup](#AccountRelationVendorGroup)||<a href="JournalizingTransactionPostingDefinitionPayableEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity</a>|
|[PostingDefinitionId](#PostingDefinitionId)||<a href="JournalizingTransactionPostingDefinitionPayableEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity</a>|
|[CategoryRelation](#CategoryRelation)||<a href="JournalizingTransactionPostingDefinitionPayableEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity</a>|
|[ItemRelation](#ItemRelation)||<a href="JournalizingTransactionPostingDefinitionPayableEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity</a>|
|[AccountRelation](#AccountRelation)||<a href="JournalizingTransactionPostingDefinitionPayableEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity</a>|
|[BackingTable_JournalizingDefinitionPayablesTransRelationshipId](#BackingTable_JournalizingDefinitionPayablesTransRelationshipId)||<a href="JournalizingTransactionPostingDefinitionPayableEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="JournalizingTransactionPostingDefinitionPayableEntity.md" target="_blank">GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity</a>|

### <a href=#AccountsPayableTransactionType name="AccountsPayableTransactionType">AccountsPayableTransactionType</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountsPayableTransactionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryRelationRecId name="CategoryRelationRecId">CategoryRelationRecId</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryRelationRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemCodeTableGroupCategoryAll name="ItemCodeTableGroupCategoryAll">ItemCodeTableGroupCategoryAll</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemCodeTableGroupCategoryAll attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemRelationGroup name="ItemRelationGroup">ItemRelationGroup</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemRelationGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemRelationNumber name="ItemRelationNumber">ItemRelationNumber</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemRelationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingDefinition name="PostingDefinition">PostingDefinition</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Posting definition</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingDefinition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Posting definition</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountRelationVendorAccount name="AccountRelationVendorAccount">AccountRelationVendorAccount</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor account</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountRelationVendorAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountCodeTableGroupAll name="AccountCodeTableGroupAll">AccountCodeTableGroupAll</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account code</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountCodeTableGroupAll attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Account code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountRelationVendorGroup name="AccountRelationVendorGroup">AccountRelationVendorGroup</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor group</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountRelationVendorGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingDefinitionId name="PostingDefinitionId">PostingDefinitionId</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Posting definition</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingDefinitionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Posting definition</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryRelation name="CategoryRelation">CategoryRelation</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Category relation</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Category relation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemRelation name="ItemRelation">ItemRelation</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountRelation name="AccountRelation">AccountRelation</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_JournalizingDefinitionPayablesTransRelationshipId name="BackingTable_JournalizingDefinitionPayablesTransRelationshipId">BackingTable_JournalizingDefinitionPayablesTransRelationshipId</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_JournalizingDefinitionPayablesTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountingFoundation/Group/JournalizingDefinitionPayablesTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/Group/JournalizingDefinitionPayablesTrans.cdm.json/JournalizingDefinitionPayablesTrans</a></td><td><a href="../../../Tables/Finance/AccountingFoundation/Group/JournalizingDefinitionPayablesTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: GeneralLedger/JournalizingTransactionPostingDefinitionPayableEntity (this entity)  

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
