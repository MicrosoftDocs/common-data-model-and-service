---
title: PSNLedgerInterestDistributionRuleEntity in GeneralLedger - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Interest distribution rules in GeneralLedger(PSNLedgerInterestDistributionRuleEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/PSNLedgerInterestDistributionRuleEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Interest distribution rules</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CashAccount](#CashAccount)||<a href="PSNLedgerInterestDistributionRuleEntity.md" target="_blank">GeneralLedger/PSNLedgerInterestDistributionRuleEntity</a>|
|[CashAccountDisplayValue](#CashAccountDisplayValue)||<a href="PSNLedgerInterestDistributionRuleEntity.md" target="_blank">GeneralLedger/PSNLedgerInterestDistributionRuleEntity</a>|
|[CashAccountName](#CashAccountName)||<a href="PSNLedgerInterestDistributionRuleEntity.md" target="_blank">GeneralLedger/PSNLedgerInterestDistributionRuleEntity</a>|
|[InterestAccount](#InterestAccount)||<a href="PSNLedgerInterestDistributionRuleEntity.md" target="_blank">GeneralLedger/PSNLedgerInterestDistributionRuleEntity</a>|
|[InterestAccountDisplayValue](#InterestAccountDisplayValue)||<a href="PSNLedgerInterestDistributionRuleEntity.md" target="_blank">GeneralLedger/PSNLedgerInterestDistributionRuleEntity</a>|
|[InterestAccountName](#InterestAccountName)||<a href="PSNLedgerInterestDistributionRuleEntity.md" target="_blank">GeneralLedger/PSNLedgerInterestDistributionRuleEntity</a>|
|[Grant](#Grant)||<a href="PSNLedgerInterestDistributionRuleEntity.md" target="_blank">GeneralLedger/PSNLedgerInterestDistributionRuleEntity</a>|
|[GrantID](#GrantID)||<a href="PSNLedgerInterestDistributionRuleEntity.md" target="_blank">GeneralLedger/PSNLedgerInterestDistributionRuleEntity</a>|
|[ProjectID](#ProjectID)||<a href="PSNLedgerInterestDistributionRuleEntity.md" target="_blank">GeneralLedger/PSNLedgerInterestDistributionRuleEntity</a>|
|[FundingSourceForPosting](#FundingSourceForPosting)||<a href="PSNLedgerInterestDistributionRuleEntity.md" target="_blank">GeneralLedger/PSNLedgerInterestDistributionRuleEntity</a>|
|[ProjectContractID](#ProjectContractID)||<a href="PSNLedgerInterestDistributionRuleEntity.md" target="_blank">GeneralLedger/PSNLedgerInterestDistributionRuleEntity</a>|
|[FundingSourceID](#FundingSourceID)||<a href="PSNLedgerInterestDistributionRuleEntity.md" target="_blank">GeneralLedger/PSNLedgerInterestDistributionRuleEntity</a>|
|[NegativeInterest](#NegativeInterest)||<a href="PSNLedgerInterestDistributionRuleEntity.md" target="_blank">GeneralLedger/PSNLedgerInterestDistributionRuleEntity</a>|
|[Rounding](#Rounding)||<a href="PSNLedgerInterestDistributionRuleEntity.md" target="_blank">GeneralLedger/PSNLedgerInterestDistributionRuleEntity</a>|
|[RuleId](#RuleId)||<a href="PSNLedgerInterestDistributionRuleEntity.md" target="_blank">GeneralLedger/PSNLedgerInterestDistributionRuleEntity</a>|
|[Relationship_InterestAccountCombinationRelationshipId](#Relationship_InterestAccountCombinationRelationshipId)||<a href="PSNLedgerInterestDistributionRuleEntity.md" target="_blank">GeneralLedger/PSNLedgerInterestDistributionRuleEntity</a>|
|[Relationship_CashAccountCombinationRelationshipId](#Relationship_CashAccountCombinationRelationshipId)||<a href="PSNLedgerInterestDistributionRuleEntity.md" target="_blank">GeneralLedger/PSNLedgerInterestDistributionRuleEntity</a>|
|[BackingTable_PSNLedgerInterestDistributionRulesRelationshipId](#BackingTable_PSNLedgerInterestDistributionRulesRelationshipId)||<a href="PSNLedgerInterestDistributionRuleEntity.md" target="_blank">GeneralLedger/PSNLedgerInterestDistributionRuleEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PSNLedgerInterestDistributionRuleEntity.md" target="_blank">GeneralLedger/PSNLedgerInterestDistributionRuleEntity</a>|

### <a href=#CashAccount name="CashAccount">CashAccount</a>

First included in: GeneralLedger/PSNLedgerInterestDistributionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashAccountDisplayValue name="CashAccountDisplayValue">CashAccountDisplayValue</a>

First included in: GeneralLedger/PSNLedgerInterestDistributionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cash account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cash account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashAccountName name="CashAccountName">CashAccountName</a>

First included in: GeneralLedger/PSNLedgerInterestDistributionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashAccountName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InterestAccount name="InterestAccount">InterestAccount</a>

First included in: GeneralLedger/PSNLedgerInterestDistributionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterestAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InterestAccountDisplayValue name="InterestAccountDisplayValue">InterestAccountDisplayValue</a>

First included in: GeneralLedger/PSNLedgerInterestDistributionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Interest account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterestAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Interest account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InterestAccountName name="InterestAccountName">InterestAccountName</a>

First included in: GeneralLedger/PSNLedgerInterestDistributionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterestAccountName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Grant name="Grant">Grant</a>

First included in: GeneralLedger/PSNLedgerInterestDistributionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Grant attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GrantID name="GrantID">GrantID</a>

First included in: GeneralLedger/PSNLedgerInterestDistributionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrantID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectID name="ProjectID">ProjectID</a>

First included in: GeneralLedger/PSNLedgerInterestDistributionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FundingSourceForPosting name="FundingSourceForPosting">FundingSourceForPosting</a>

First included in: GeneralLedger/PSNLedgerInterestDistributionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FundingSourceForPosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectContractID name="ProjectContractID">ProjectContractID</a>

First included in: GeneralLedger/PSNLedgerInterestDistributionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectContractID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FundingSourceID name="FundingSourceID">FundingSourceID</a>

First included in: GeneralLedger/PSNLedgerInterestDistributionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FundingSourceID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NegativeInterest name="NegativeInterest">NegativeInterest</a>

First included in: GeneralLedger/PSNLedgerInterestDistributionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NegativeInterest attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Rounding name="Rounding">Rounding</a>

First included in: GeneralLedger/PSNLedgerInterestDistributionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Rounding attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RuleId name="RuleId">RuleId</a>

First included in: GeneralLedger/PSNLedgerInterestDistributionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RuleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InterestAccountCombinationRelationshipId name="Relationship_InterestAccountCombinationRelationshipId">Relationship_InterestAccountCombinationRelationshipId</a>

First included in: GeneralLedger/PSNLedgerInterestDistributionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InterestAccountCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CashAccountCombinationRelationshipId name="Relationship_CashAccountCombinationRelationshipId">Relationship_CashAccountCombinationRelationshipId</a>

First included in: GeneralLedger/PSNLedgerInterestDistributionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CashAccountCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_PSNLedgerInterestDistributionRulesRelationshipId name="BackingTable_PSNLedgerInterestDistributionRulesRelationshipId">BackingTable_PSNLedgerInterestDistributionRulesRelationshipId</a>

First included in: GeneralLedger/PSNLedgerInterestDistributionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PSNLedgerInterestDistributionRulesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Miscellaneous/PSNLedgerInterestDistributionRules.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Miscellaneous/PSNLedgerInterestDistributionRules.cdm.json/PSNLedgerInterestDistributionRules</a></td><td><a href="../../../Tables/Finance/Ledger/Miscellaneous/PSNLedgerInterestDistributionRules.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: GeneralLedger/PSNLedgerInterestDistributionRuleEntity (this entity)  

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
