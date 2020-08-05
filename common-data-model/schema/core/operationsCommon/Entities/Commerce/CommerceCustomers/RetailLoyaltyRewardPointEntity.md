---
title: RetailLoyaltyRewardPointEntity in CommerceCustomers - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Loyalty reward points in CommerceCustomers(RetailLoyaltyRewardPointEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/CommerceCustomers/RetailLoyaltyRewardPointEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Loyalty reward points</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ExpirationTimeUnit](#ExpirationTimeUnit)||<a href="RetailLoyaltyRewardPointEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRewardPointEntity</a>|
|[ExpirationTimeValue](#ExpirationTimeValue)||<a href="RetailLoyaltyRewardPointEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRewardPointEntity</a>|
|[Redeemable](#Redeemable)||<a href="RetailLoyaltyRewardPointEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRewardPointEntity</a>|
|[RedeemRanking](#RedeemRanking)||<a href="RetailLoyaltyRewardPointEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRewardPointEntity</a>|
|[RewardPointCurrency](#RewardPointCurrency)||<a href="RetailLoyaltyRewardPointEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRewardPointEntity</a>|
|[RewardPointId](#RewardPointId)||<a href="RetailLoyaltyRewardPointEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRewardPointEntity</a>|
|[RewardPointType](#RewardPointType)||<a href="RetailLoyaltyRewardPointEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRewardPointEntity</a>|
|[VestingTimeUnit](#VestingTimeUnit)||<a href="RetailLoyaltyRewardPointEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRewardPointEntity</a>|
|[VestingTimeValue](#VestingTimeValue)||<a href="RetailLoyaltyRewardPointEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRewardPointEntity</a>|
|[MaximumLoyaltyRewardPoints](#MaximumLoyaltyRewardPoints)||<a href="RetailLoyaltyRewardPointEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRewardPointEntity</a>|
|[BackingTable_RetailLoyaltyRewardPointRelationshipId](#BackingTable_RetailLoyaltyRewardPointRelationshipId)||<a href="RetailLoyaltyRewardPointEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRewardPointEntity</a>|

### <a href=#ExpirationTimeUnit name="ExpirationTimeUnit">ExpirationTimeUnit</a>

First included in: CommerceCustomers/RetailLoyaltyRewardPointEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpirationTimeUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpirationTimeValue name="ExpirationTimeValue">ExpirationTimeValue</a>

First included in: CommerceCustomers/RetailLoyaltyRewardPointEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpirationTimeValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Redeemable name="Redeemable">Redeemable</a>

First included in: CommerceCustomers/RetailLoyaltyRewardPointEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Redeemable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RedeemRanking name="RedeemRanking">RedeemRanking</a>

First included in: CommerceCustomers/RetailLoyaltyRewardPointEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RedeemRanking attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RewardPointCurrency name="RewardPointCurrency">RewardPointCurrency</a>

First included in: CommerceCustomers/RetailLoyaltyRewardPointEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RewardPointCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RewardPointId name="RewardPointId">RewardPointId</a>

First included in: CommerceCustomers/RetailLoyaltyRewardPointEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RewardPointId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RewardPointType name="RewardPointType">RewardPointType</a>

First included in: CommerceCustomers/RetailLoyaltyRewardPointEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RewardPointType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VestingTimeUnit name="VestingTimeUnit">VestingTimeUnit</a>

First included in: CommerceCustomers/RetailLoyaltyRewardPointEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VestingTimeUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VestingTimeValue name="VestingTimeValue">VestingTimeValue</a>

First included in: CommerceCustomers/RetailLoyaltyRewardPointEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VestingTimeValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumLoyaltyRewardPoints name="MaximumLoyaltyRewardPoints">MaximumLoyaltyRewardPoints</a>

First included in: CommerceCustomers/RetailLoyaltyRewardPointEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumLoyaltyRewardPoints attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailLoyaltyRewardPointRelationshipId name="BackingTable_RetailLoyaltyRewardPointRelationshipId">BackingTable_RetailLoyaltyRewardPointRelationshipId</a>

First included in: CommerceCustomers/RetailLoyaltyRewardPointEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailLoyaltyRewardPointRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/CommerceCustomers/Miscellaneous/RetailLoyaltyRewardPoint.md" target="_blank">/core/operationsCommon/Tables/Commerce/CommerceCustomers/Miscellaneous/RetailLoyaltyRewardPoint.cdm.json/RetailLoyaltyRewardPoint</a></td><td><a href="../../../Tables/Commerce/CommerceCustomers/Miscellaneous/RetailLoyaltyRewardPoint.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
