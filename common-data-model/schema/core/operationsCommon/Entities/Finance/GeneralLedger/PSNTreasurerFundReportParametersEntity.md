---
title: PSNTreasurerFundReportParametersEntity in GeneralLedger - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Treasurer's fund report parameters in GeneralLedger(PSNTreasurerFundReportParametersEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/PSNTreasurerFundReportParametersEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Treasurer's fund report parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[TreasurerDimensionFocus](#TreasurerDimensionFocus)||<a href="PSNTreasurerFundReportParametersEntity.md" target="_blank">GeneralLedger/PSNTreasurerFundReportParametersEntity</a>|
|[GroupByFundType](#GroupByFundType)||<a href="PSNTreasurerFundReportParametersEntity.md" target="_blank">GeneralLedger/PSNTreasurerFundReportParametersEntity</a>|
|[IncludeFundName](#IncludeFundName)||<a href="PSNTreasurerFundReportParametersEntity.md" target="_blank">GeneralLedger/PSNTreasurerFundReportParametersEntity</a>|
|[IncludeClosingTransactions](#IncludeClosingTransactions)||<a href="PSNTreasurerFundReportParametersEntity.md" target="_blank">GeneralLedger/PSNTreasurerFundReportParametersEntity</a>|
|[SuppressZeroAmountAccounts](#SuppressZeroAmountAccounts)||<a href="PSNTreasurerFundReportParametersEntity.md" target="_blank">GeneralLedger/PSNTreasurerFundReportParametersEntity</a>|
|[SuppressMainAccount](#SuppressMainAccount)||<a href="PSNTreasurerFundReportParametersEntity.md" target="_blank">GeneralLedger/PSNTreasurerFundReportParametersEntity</a>|
|[ID](#ID)||<a href="PSNTreasurerFundReportParametersEntity.md" target="_blank">GeneralLedger/PSNTreasurerFundReportParametersEntity</a>|
|[BackingTable_PSNTreasurerFundReportParametersRelationshipId](#BackingTable_PSNTreasurerFundReportParametersRelationshipId)||<a href="PSNTreasurerFundReportParametersEntity.md" target="_blank">GeneralLedger/PSNTreasurerFundReportParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PSNTreasurerFundReportParametersEntity.md" target="_blank">GeneralLedger/PSNTreasurerFundReportParametersEntity</a>|

### <a href=#TreasurerDimensionFocus name="TreasurerDimensionFocus">TreasurerDimensionFocus</a>

First included in: GeneralLedger/PSNTreasurerFundReportParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TreasurerDimensionFocus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupByFundType name="GroupByFundType">GroupByFundType</a>

First included in: GeneralLedger/PSNTreasurerFundReportParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupByFundType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IncludeFundName name="IncludeFundName">IncludeFundName</a>

First included in: GeneralLedger/PSNTreasurerFundReportParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeFundName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IncludeClosingTransactions name="IncludeClosingTransactions">IncludeClosingTransactions</a>

First included in: GeneralLedger/PSNTreasurerFundReportParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeClosingTransactions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SuppressZeroAmountAccounts name="SuppressZeroAmountAccounts">SuppressZeroAmountAccounts</a>

First included in: GeneralLedger/PSNTreasurerFundReportParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SuppressZeroAmountAccounts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SuppressMainAccount name="SuppressMainAccount">SuppressMainAccount</a>

First included in: GeneralLedger/PSNTreasurerFundReportParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SuppressMainAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ID name="ID">ID</a>

First included in: GeneralLedger/PSNTreasurerFundReportParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PSNTreasurerFundReportParametersRelationshipId name="BackingTable_PSNTreasurerFundReportParametersRelationshipId">BackingTable_PSNTreasurerFundReportParametersRelationshipId</a>

First included in: GeneralLedger/PSNTreasurerFundReportParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PSNTreasurerFundReportParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Parameter/PSNTreasurerFundReportParameters.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Parameter/PSNTreasurerFundReportParameters.cdm.json/PSNTreasurerFundReportParameters</a></td><td><a href="../../../Tables/Finance/Ledger/Parameter/PSNTreasurerFundReportParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: GeneralLedger/PSNTreasurerFundReportParametersEntity (this entity)  

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
