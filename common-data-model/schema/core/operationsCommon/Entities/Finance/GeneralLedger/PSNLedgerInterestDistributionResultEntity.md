---
title: PSNLedgerInterestDistributionResultEntity in GeneralLedger - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# Interest distribution results in GeneralLedger(PSNLedgerInterestDistributionResultEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/PSNLedgerInterestDistributionResultEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Interest distribution results</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RuleId](#RuleId)||<a href="PSNLedgerInterestDistributionResultEntity.md" target="_blank">GeneralLedger/PSNLedgerInterestDistributionResultEntity</a>|
|[AverageDailyBalance](#AverageDailyBalance)||<a href="PSNLedgerInterestDistributionResultEntity.md" target="_blank">GeneralLedger/PSNLedgerInterestDistributionResultEntity</a>|
|[PercentOfTotal](#PercentOfTotal)||<a href="PSNLedgerInterestDistributionResultEntity.md" target="_blank">GeneralLedger/PSNLedgerInterestDistributionResultEntity</a>|
|[AllocatedInterest](#AllocatedInterest)||<a href="PSNLedgerInterestDistributionResultEntity.md" target="_blank">GeneralLedger/PSNLedgerInterestDistributionResultEntity</a>|
|[InterestDistributionRules](#InterestDistributionRules)||<a href="PSNLedgerInterestDistributionResultEntity.md" target="_blank">GeneralLedger/PSNLedgerInterestDistributionResultEntity</a>|
|[Relationship_LedgerInterestDistributionRuleRelationshipId](#Relationship_LedgerInterestDistributionRuleRelationshipId)||<a href="PSNLedgerInterestDistributionResultEntity.md" target="_blank">GeneralLedger/PSNLedgerInterestDistributionResultEntity</a>|
|[BackingTable_PSNLedgerInterestDistributionResultsRelationshipId](#BackingTable_PSNLedgerInterestDistributionResultsRelationshipId)||<a href="PSNLedgerInterestDistributionResultEntity.md" target="_blank">GeneralLedger/PSNLedgerInterestDistributionResultEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PSNLedgerInterestDistributionResultEntity.md" target="_blank">GeneralLedger/PSNLedgerInterestDistributionResultEntity</a>|

### <a href=#RuleId name="RuleId">RuleId</a>

First included in: GeneralLedger/PSNLedgerInterestDistributionResultEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RuleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AverageDailyBalance name="AverageDailyBalance">AverageDailyBalance</a>

First included in: GeneralLedger/PSNLedgerInterestDistributionResultEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AverageDailyBalance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PercentOfTotal name="PercentOfTotal">PercentOfTotal</a>

First included in: GeneralLedger/PSNLedgerInterestDistributionResultEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PercentOfTotal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllocatedInterest name="AllocatedInterest">AllocatedInterest</a>

First included in: GeneralLedger/PSNLedgerInterestDistributionResultEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllocatedInterest attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InterestDistributionRules name="InterestDistributionRules">InterestDistributionRules</a>

First included in: GeneralLedger/PSNLedgerInterestDistributionResultEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterestDistributionRules attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerInterestDistributionRuleRelationshipId name="Relationship_LedgerInterestDistributionRuleRelationshipId">Relationship_LedgerInterestDistributionRuleRelationshipId</a>

First included in: GeneralLedger/PSNLedgerInterestDistributionResultEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerInterestDistributionRuleRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_PSNLedgerInterestDistributionResultsRelationshipId name="BackingTable_PSNLedgerInterestDistributionResultsRelationshipId">BackingTable_PSNLedgerInterestDistributionResultsRelationshipId</a>

First included in: GeneralLedger/PSNLedgerInterestDistributionResultEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PSNLedgerInterestDistributionResultsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Miscellaneous/PSNLedgerInterestDistributionResults.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Miscellaneous/PSNLedgerInterestDistributionResults.cdm.json/PSNLedgerInterestDistributionResults</a></td><td><a href="../../../Tables/Finance/Ledger/Miscellaneous/PSNLedgerInterestDistributionResults.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: GeneralLedger/PSNLedgerInterestDistributionResultEntity (this entity)  

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
