---
title: CustCollectionAgencyGracePeriodSetupEntity in AccountsReceivable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Collection agency grace period setup in AccountsReceivable(CustCollectionAgencyGracePeriodSetupEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/CustCollectionAgencyGracePeriodSetupEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Collection agency grace period setup</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AccountOrGroupNumber](#AccountOrGroupNumber)||<a href="CustCollectionAgencyGracePeriodSetupEntity.md" target="_blank">AccountsReceivable/CustCollectionAgencyGracePeriodSetupEntity</a>|
|[AccountCode](#AccountCode)||<a href="CustCollectionAgencyGracePeriodSetupEntity.md" target="_blank">AccountsReceivable/CustCollectionAgencyGracePeriodSetupEntity</a>|
|[ValidFrom](#ValidFrom)||<a href="CustCollectionAgencyGracePeriodSetupEntity.md" target="_blank">AccountsReceivable/CustCollectionAgencyGracePeriodSetupEntity</a>|
|[ValidTo](#ValidTo)||<a href="CustCollectionAgencyGracePeriodSetupEntity.md" target="_blank">AccountsReceivable/CustCollectionAgencyGracePeriodSetupEntity</a>|
|[GracePeriodInDaysAfterTransactionDate](#GracePeriodInDaysAfterTransactionDate)||<a href="CustCollectionAgencyGracePeriodSetupEntity.md" target="_blank">AccountsReceivable/CustCollectionAgencyGracePeriodSetupEntity</a>|
|[BackingTable_CustCollectionAgencyGracePeriodSetup_WRelationshipId](#BackingTable_CustCollectionAgencyGracePeriodSetup_WRelationshipId)||<a href="CustCollectionAgencyGracePeriodSetupEntity.md" target="_blank">AccountsReceivable/CustCollectionAgencyGracePeriodSetupEntity</a>|

### <a href=#AccountOrGroupNumber name="AccountOrGroupNumber">AccountOrGroupNumber</a>

First included in: AccountsReceivable/CustCollectionAgencyGracePeriodSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountOrGroupNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountCode name="AccountCode">AccountCode</a>

First included in: AccountsReceivable/CustCollectionAgencyGracePeriodSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: AccountsReceivable/CustCollectionAgencyGracePeriodSetupEntity (this entity)  

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

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: AccountsReceivable/CustCollectionAgencyGracePeriodSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GracePeriodInDaysAfterTransactionDate name="GracePeriodInDaysAfterTransactionDate">GracePeriodInDaysAfterTransactionDate</a>

First included in: AccountsReceivable/CustCollectionAgencyGracePeriodSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GracePeriodInDaysAfterTransactionDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_CustCollectionAgencyGracePeriodSetup_WRelationshipId name="BackingTable_CustCollectionAgencyGracePeriodSetup_WRelationshipId">BackingTable_CustCollectionAgencyGracePeriodSetup_WRelationshipId</a>

First included in: AccountsReceivable/CustCollectionAgencyGracePeriodSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CustCollectionAgencyGracePeriodSetup_WRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountsReceivable/Main/CustCollectionAgencyGracePeriodSetup_W.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Main/CustCollectionAgencyGracePeriodSetup_W.cdm.json/CustCollectionAgencyGracePeriodSetup_W</a></td><td><a href="../../../Tables/Finance/AccountsReceivable/Main/CustCollectionAgencyGracePeriodSetup_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
