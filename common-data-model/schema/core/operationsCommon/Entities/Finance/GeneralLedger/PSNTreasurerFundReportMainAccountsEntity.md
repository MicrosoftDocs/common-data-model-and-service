---
title: PSNTreasurerFundReportMainAccountsEntity in GeneralLedger - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Treasurer's fund accounts in GeneralLedger(PSNTreasurerFundReportMainAccountsEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/PSNTreasurerFundReportMainAccountsEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Treasurer's fund accounts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[MainAccountRecId](#MainAccountRecId)||<a href="PSNTreasurerFundReportMainAccountsEntity.md" target="_blank">GeneralLedger/PSNTreasurerFundReportMainAccountsEntity</a>|
|[LedgerChartOfAccountsRecId](#LedgerChartOfAccountsRecId)||<a href="PSNTreasurerFundReportMainAccountsEntity.md" target="_blank">GeneralLedger/PSNTreasurerFundReportMainAccountsEntity</a>|
|[MainAccountId](#MainAccountId)||<a href="PSNTreasurerFundReportMainAccountsEntity.md" target="_blank">GeneralLedger/PSNTreasurerFundReportMainAccountsEntity</a>|
|[LedgerChartOfAccountsName](#LedgerChartOfAccountsName)||<a href="PSNTreasurerFundReportMainAccountsEntity.md" target="_blank">GeneralLedger/PSNTreasurerFundReportMainAccountsEntity</a>|
|[BackingTable_PSNTreasurerFundReportMainAccountsRelationshipId](#BackingTable_PSNTreasurerFundReportMainAccountsRelationshipId)||<a href="PSNTreasurerFundReportMainAccountsEntity.md" target="_blank">GeneralLedger/PSNTreasurerFundReportMainAccountsEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PSNTreasurerFundReportMainAccountsEntity.md" target="_blank">GeneralLedger/PSNTreasurerFundReportMainAccountsEntity</a>|

### <a href=#MainAccountRecId name="MainAccountRecId">MainAccountRecId</a>

First included in: GeneralLedger/PSNTreasurerFundReportMainAccountsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerChartOfAccountsRecId name="LedgerChartOfAccountsRecId">LedgerChartOfAccountsRecId</a>

First included in: GeneralLedger/PSNTreasurerFundReportMainAccountsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerChartOfAccountsRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountId name="MainAccountId">MainAccountId</a>

First included in: GeneralLedger/PSNTreasurerFundReportMainAccountsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerChartOfAccountsName name="LedgerChartOfAccountsName">LedgerChartOfAccountsName</a>

First included in: GeneralLedger/PSNTreasurerFundReportMainAccountsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerChartOfAccountsName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PSNTreasurerFundReportMainAccountsRelationshipId name="BackingTable_PSNTreasurerFundReportMainAccountsRelationshipId">BackingTable_PSNTreasurerFundReportMainAccountsRelationshipId</a>

First included in: GeneralLedger/PSNTreasurerFundReportMainAccountsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PSNTreasurerFundReportMainAccountsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Miscellaneous/PSNTreasurerFundReportMainAccounts.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Miscellaneous/PSNTreasurerFundReportMainAccounts.cdm.json/PSNTreasurerFundReportMainAccounts</a></td><td><a href="../../../Tables/Finance/Ledger/Miscellaneous/PSNTreasurerFundReportMainAccounts.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: GeneralLedger/PSNTreasurerFundReportMainAccountsEntity (this entity)  

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
