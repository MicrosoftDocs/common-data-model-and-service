---
title: RetailLoyaltyTierRuleEntity in CommerceCustomers - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Retail loyalty tier rules in CommerceCustomers(RetailLoyaltyTierRuleEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/CommerceCustomers/RetailLoyaltyTierRuleEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Retail loyalty tier rules</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[LoyaltyTier](#LoyaltyTier)||<a href="RetailLoyaltyTierRuleEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyTierRuleEntity</a>|
|[MinValue](#MinValue)||<a href="RetailLoyaltyTierRuleEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyTierRuleEntity</a>|
|[PoolRelatedCards](#PoolRelatedCards)||<a href="RetailLoyaltyTierRuleEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyTierRuleEntity</a>|
|[RewardPoint](#RewardPoint)||<a href="RetailLoyaltyTierRuleEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyTierRuleEntity</a>|
|[EvaluationDateInterval](#EvaluationDateInterval)||<a href="RetailLoyaltyTierRuleEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyTierRuleEntity</a>|
|[RewardPointId](#RewardPointId)||<a href="RetailLoyaltyTierRuleEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyTierRuleEntity</a>|
|[Affiliation](#Affiliation)||<a href="RetailLoyaltyTierRuleEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyTierRuleEntity</a>|
|[LoyaltyTierId](#LoyaltyTierId)||<a href="RetailLoyaltyTierRuleEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyTierRuleEntity</a>|
|[LoyaltyName](#LoyaltyName)||<a href="RetailLoyaltyTierRuleEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyTierRuleEntity</a>|
|[BackingTable_RetailLoyaltyTierRuleRelationshipId](#BackingTable_RetailLoyaltyTierRuleRelationshipId)||<a href="RetailLoyaltyTierRuleEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyTierRuleEntity</a>|

### <a href=#LoyaltyTier name="LoyaltyTier">LoyaltyTier</a>

First included in: CommerceCustomers/RetailLoyaltyTierRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyTier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinValue name="MinValue">MinValue</a>

First included in: CommerceCustomers/RetailLoyaltyTierRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Minimum issued points</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Minimum issued points</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PoolRelatedCards name="PoolRelatedCards">PoolRelatedCards</a>

First included in: CommerceCustomers/RetailLoyaltyTierRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PoolRelatedCards attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RewardPoint name="RewardPoint">RewardPoint</a>

First included in: CommerceCustomers/RetailLoyaltyTierRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reward point</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RewardPoint attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reward point</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EvaluationDateInterval name="EvaluationDateInterval">EvaluationDateInterval</a>

First included in: CommerceCustomers/RetailLoyaltyTierRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Evaluation date interval</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EvaluationDateInterval attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Evaluation date interval</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RewardPointId name="RewardPointId">RewardPointId</a>

First included in: CommerceCustomers/RetailLoyaltyTierRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RewardPointId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Affiliation name="Affiliation">Affiliation</a>

First included in: CommerceCustomers/RetailLoyaltyTierRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Affiliation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyTierId name="LoyaltyTierId">LoyaltyTierId</a>

First included in: CommerceCustomers/RetailLoyaltyTierRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyTierId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyName name="LoyaltyName">LoyaltyName</a>

First included in: CommerceCustomers/RetailLoyaltyTierRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailLoyaltyTierRuleRelationshipId name="BackingTable_RetailLoyaltyTierRuleRelationshipId">BackingTable_RetailLoyaltyTierRuleRelationshipId</a>

First included in: CommerceCustomers/RetailLoyaltyTierRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailLoyaltyTierRuleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/CommerceCustomers/Miscellaneous/RetailLoyaltyTierRule.md" target="_blank">/core/operationsCommon/Tables/Commerce/CommerceCustomers/Miscellaneous/RetailLoyaltyTierRule.cdm.json/RetailLoyaltyTierRule</a></td><td><a href="../../../Tables/Commerce/CommerceCustomers/Miscellaneous/RetailLoyaltyTierRule.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
