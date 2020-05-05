---
title: CredManCreditLimitAdvancedEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Temporary credit limits

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/CredManCreditLimitAdvancedEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Temporary credit limits</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CreditLimitId](#CreditLimitId)||<a href="CredManCreditLimitAdvancedEntity.md" target="_blank">AccountsReceivable/CredManCreditLimitAdvancedEntity</a>|
|[CreditMax](#CreditMax)||<a href="CredManCreditLimitAdvancedEntity.md" target="_blank">AccountsReceivable/CredManCreditLimitAdvancedEntity</a>|
|[CustAccount](#CustAccount)||<a href="CredManCreditLimitAdvancedEntity.md" target="_blank">AccountsReceivable/CredManCreditLimitAdvancedEntity</a>|
|[CustAccountDataArea](#CustAccountDataArea)||<a href="CredManCreditLimitAdvancedEntity.md" target="_blank">AccountsReceivable/CredManCreditLimitAdvancedEntity</a>|
|[FromDate](#FromDate)||<a href="CredManCreditLimitAdvancedEntity.md" target="_blank">AccountsReceivable/CredManCreditLimitAdvancedEntity</a>|
|[ToDate](#ToDate)||<a href="CredManCreditLimitAdvancedEntity.md" target="_blank">AccountsReceivable/CredManCreditLimitAdvancedEntity</a>|
|[BackingTable_CredManCreditLimitAdvancedRelationshipId](#BackingTable_CredManCreditLimitAdvancedRelationshipId)||<a href="CredManCreditLimitAdvancedEntity.md" target="_blank">AccountsReceivable/CredManCreditLimitAdvancedEntity</a>|

### <a href=#CreditLimitId name="CreditLimitId">CreditLimitId</a>

First included in: AccountsReceivable/CredManCreditLimitAdvancedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditLimitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditMax name="CreditMax">CreditMax</a>

First included in: AccountsReceivable/CredManCreditLimitAdvancedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditMax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustAccount name="CustAccount">CustAccount</a>

First included in: AccountsReceivable/CredManCreditLimitAdvancedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustAccountDataArea name="CustAccountDataArea">CustAccountDataArea</a>

First included in: AccountsReceivable/CredManCreditLimitAdvancedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustAccountDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromDate name="FromDate">FromDate</a>

First included in: AccountsReceivable/CredManCreditLimitAdvancedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToDate name="ToDate">ToDate</a>

First included in: AccountsReceivable/CredManCreditLimitAdvancedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_CredManCreditLimitAdvancedRelationshipId name="BackingTable_CredManCreditLimitAdvancedRelationshipId">BackingTable_CredManCreditLimitAdvancedRelationshipId</a>

First included in: AccountsReceivable/CredManCreditLimitAdvancedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CredManCreditLimitAdvancedRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountsReceivable/Main/CredManCreditLimitAdvanced.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Main/CredManCreditLimitAdvanced.cdm.json/CredManCreditLimitAdvanced</a></td><td><a href="../../../Tables/Finance/AccountsReceivable/Main/CredManCreditLimitAdvanced.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
