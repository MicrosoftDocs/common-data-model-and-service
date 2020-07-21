---
title: LedgerConsolidateAccountGroupV2Entity in GeneralLedger - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Consolidation main accounts in GeneralLedger(LedgerConsolidateAccountGroupV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/LedgerConsolidateAccountGroupV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Consolidation main accounts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[MainAccount](#MainAccount)||<a href="LedgerConsolidateAccountGroupV2Entity.md" target="_blank">GeneralLedger/LedgerConsolidateAccountGroupV2Entity</a>|
|[MainAccountName](#MainAccountName)||<a href="LedgerConsolidateAccountGroupV2Entity.md" target="_blank">GeneralLedger/LedgerConsolidateAccountGroupV2Entity</a>|
|[ConsolidationAccountGroup](#ConsolidationAccountGroup)||<a href="LedgerConsolidateAccountGroupV2Entity.md" target="_blank">GeneralLedger/LedgerConsolidateAccountGroupV2Entity</a>|
|[ConsolidationAccountGroupName](#ConsolidationAccountGroupName)||<a href="LedgerConsolidateAccountGroupV2Entity.md" target="_blank">GeneralLedger/LedgerConsolidateAccountGroupV2Entity</a>|
|[ConsolidationAccount](#ConsolidationAccount)||<a href="LedgerConsolidateAccountGroupV2Entity.md" target="_blank">GeneralLedger/LedgerConsolidateAccountGroupV2Entity</a>|
|[ConsolidationAccountName](#ConsolidationAccountName)||<a href="LedgerConsolidateAccountGroupV2Entity.md" target="_blank">GeneralLedger/LedgerConsolidateAccountGroupV2Entity</a>|
|[MainAccountType](#MainAccountType)||<a href="LedgerConsolidateAccountGroupV2Entity.md" target="_blank">GeneralLedger/LedgerConsolidateAccountGroupV2Entity</a>|
|[MainAccountCategory](#MainAccountCategory)||<a href="LedgerConsolidateAccountGroupV2Entity.md" target="_blank">GeneralLedger/LedgerConsolidateAccountGroupV2Entity</a>|
|[ChartOfAccounts](#ChartOfAccounts)||<a href="LedgerConsolidateAccountGroupV2Entity.md" target="_blank">GeneralLedger/LedgerConsolidateAccountGroupV2Entity</a>|
|[CostCenterName](#CostCenterName)||<a href="LedgerConsolidateAccountGroupV2Entity.md" target="_blank">GeneralLedger/LedgerConsolidateAccountGroupV2Entity</a>|
|[Relationship_MainAccountRelationshipId](#Relationship_MainAccountRelationshipId)||<a href="LedgerConsolidateAccountGroupV2Entity.md" target="_blank">GeneralLedger/LedgerConsolidateAccountGroupV2Entity</a>|
|[Relationship_LedgerChartOfAccountsRelationshipId](#Relationship_LedgerChartOfAccountsRelationshipId)||<a href="LedgerConsolidateAccountGroupV2Entity.md" target="_blank">GeneralLedger/LedgerConsolidateAccountGroupV2Entity</a>|
|[Relationship_ConsolidationMainAccountRelationshipId](#Relationship_ConsolidationMainAccountRelationshipId)||<a href="LedgerConsolidateAccountGroupV2Entity.md" target="_blank">GeneralLedger/LedgerConsolidateAccountGroupV2Entity</a>|
|[BackingTable_LedgerConsolidateAccountGroupRelationshipId](#BackingTable_LedgerConsolidateAccountGroupRelationshipId)||<a href="LedgerConsolidateAccountGroupV2Entity.md" target="_blank">GeneralLedger/LedgerConsolidateAccountGroupV2Entity</a>|

### <a href=#MainAccount name="MainAccount">MainAccount</a>

First included in: GeneralLedger/LedgerConsolidateAccountGroupV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountName name="MainAccountName">MainAccountName</a>

First included in: GeneralLedger/LedgerConsolidateAccountGroupV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Main account name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Main account name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsolidationAccountGroup name="ConsolidationAccountGroup">ConsolidationAccountGroup</a>

First included in: GeneralLedger/LedgerConsolidateAccountGroupV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsolidationAccountGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsolidationAccountGroupName name="ConsolidationAccountGroupName">ConsolidationAccountGroupName</a>

First included in: GeneralLedger/LedgerConsolidateAccountGroupV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsolidationAccountGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsolidationAccount name="ConsolidationAccount">ConsolidationAccount</a>

First included in: GeneralLedger/LedgerConsolidateAccountGroupV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsolidationAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsolidationAccountName name="ConsolidationAccountName">ConsolidationAccountName</a>

First included in: GeneralLedger/LedgerConsolidateAccountGroupV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsolidationAccountName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountType name="MainAccountType">MainAccountType</a>

First included in: GeneralLedger/LedgerConsolidateAccountGroupV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountCategory name="MainAccountCategory">MainAccountCategory</a>

First included in: GeneralLedger/LedgerConsolidateAccountGroupV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChartOfAccounts name="ChartOfAccounts">ChartOfAccounts</a>

First included in: GeneralLedger/LedgerConsolidateAccountGroupV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChartOfAccounts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostCenterName name="CostCenterName">CostCenterName</a>

First included in: GeneralLedger/LedgerConsolidateAccountGroupV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostCenterName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MainAccountRelationshipId name="Relationship_MainAccountRelationshipId">Relationship_MainAccountRelationshipId</a>

First included in: GeneralLedger/LedgerConsolidateAccountGroupV2Entity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerChartOfAccountsRelationshipId name="Relationship_LedgerChartOfAccountsRelationshipId">Relationship_LedgerChartOfAccountsRelationshipId</a>

First included in: GeneralLedger/LedgerConsolidateAccountGroupV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerChartOfAccountsRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ConsolidationMainAccountRelationshipId name="Relationship_ConsolidationMainAccountRelationshipId">Relationship_ConsolidationMainAccountRelationshipId</a>

First included in: GeneralLedger/LedgerConsolidateAccountGroupV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ConsolidationMainAccountRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_LedgerConsolidateAccountGroupRelationshipId name="BackingTable_LedgerConsolidateAccountGroupRelationshipId">BackingTable_LedgerConsolidateAccountGroupRelationshipId</a>

First included in: GeneralLedger/LedgerConsolidateAccountGroupV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_LedgerConsolidateAccountGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Group/LedgerConsolidateAccountGroup.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Group/LedgerConsolidateAccountGroup.cdm.json/LedgerConsolidateAccountGroup</a></td><td><a href="../../../Tables/Finance/Ledger/Group/LedgerConsolidateAccountGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
