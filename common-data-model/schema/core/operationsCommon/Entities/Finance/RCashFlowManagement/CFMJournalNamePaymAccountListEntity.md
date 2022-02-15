---
title: CFMJournalNamePaymAccountListEntity in RCashFlowManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Payments accounts of payment schedule journals in RCashFlowManagement(CFMJournalNamePaymAccountListEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/RCashFlowManagement/CFMJournalNamePaymAccountListEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payments accounts of payment schedule journals</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Name](#Name)||<a href="CFMJournalNamePaymAccountListEntity.md" target="_blank">RCashFlowManagement/CFMJournalNamePaymAccountListEntity</a>|
|[AccountNumber](#AccountNumber)||<a href="CFMJournalNamePaymAccountListEntity.md" target="_blank">RCashFlowManagement/CFMJournalNamePaymAccountListEntity</a>|
|[PaymentAccountType](#PaymentAccountType)||<a href="CFMJournalNamePaymAccountListEntity.md" target="_blank">RCashFlowManagement/CFMJournalNamePaymAccountListEntity</a>|
|[BackingTable_CFMJournalPaymAccountListRelationshipId](#BackingTable_CFMJournalPaymAccountListRelationshipId)||<a href="CFMJournalNamePaymAccountListEntity.md" target="_blank">RCashFlowManagement/CFMJournalNamePaymAccountListEntity</a>|

### <a href=#Name name="Name">Name</a>

First included in: RCashFlowManagement/CFMJournalNamePaymAccountListEntity (this entity)  

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

### <a href=#AccountNumber name="AccountNumber">AccountNumber</a>

First included in: RCashFlowManagement/CFMJournalNamePaymAccountListEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentAccountType name="PaymentAccountType">PaymentAccountType</a>

First included in: RCashFlowManagement/CFMJournalNamePaymAccountListEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentAccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_CFMJournalPaymAccountListRelationshipId name="BackingTable_CFMJournalPaymAccountListRelationshipId">BackingTable_CFMJournalPaymAccountListRelationshipId</a>

First included in: RCashFlowManagement/CFMJournalNamePaymAccountListEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CFMJournalPaymAccountListRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/RCashFlowManagement/Group/CFMJournalPaymAccountList.md" target="_blank">/core/operationsCommon/Tables/Finance/RCashFlowManagement/Group/CFMJournalPaymAccountList.cdm.json/CFMJournalPaymAccountList</a></td><td><a href="../../../Tables/Finance/RCashFlowManagement/Group/CFMJournalPaymAccountList.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
