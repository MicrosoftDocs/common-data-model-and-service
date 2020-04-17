---
title: RetailLoyaltyRewardPoint - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailLoyaltyRewardPoint

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailLoyaltyRewardPoint.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailLoyaltyRewardPoint/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailLoyaltyRewardPoint.md" target="_blank">Miscellaneous/RetailLoyaltyRewardPoint</a>|
|[ExpirationTimeUnit](#ExpirationTimeUnit)||<a href="RetailLoyaltyRewardPoint.md" target="_blank">Miscellaneous/RetailLoyaltyRewardPoint</a>|
|[ExpirationTimeValue](#ExpirationTimeValue)||<a href="RetailLoyaltyRewardPoint.md" target="_blank">Miscellaneous/RetailLoyaltyRewardPoint</a>|
|[Redeemable](#Redeemable)||<a href="RetailLoyaltyRewardPoint.md" target="_blank">Miscellaneous/RetailLoyaltyRewardPoint</a>|
|[RedeemRanking](#RedeemRanking)||<a href="RetailLoyaltyRewardPoint.md" target="_blank">Miscellaneous/RetailLoyaltyRewardPoint</a>|
|[RewardPointCurrency](#RewardPointCurrency)||<a href="RetailLoyaltyRewardPoint.md" target="_blank">Miscellaneous/RetailLoyaltyRewardPoint</a>|
|[RewardPointId](#RewardPointId)||<a href="RetailLoyaltyRewardPoint.md" target="_blank">Miscellaneous/RetailLoyaltyRewardPoint</a>|
|[RewardPointType](#RewardPointType)||<a href="RetailLoyaltyRewardPoint.md" target="_blank">Miscellaneous/RetailLoyaltyRewardPoint</a>|
|[VestingTimeUnit](#VestingTimeUnit)||<a href="RetailLoyaltyRewardPoint.md" target="_blank">Miscellaneous/RetailLoyaltyRewardPoint</a>|
|[VestingTimeValue](#VestingTimeValue)||<a href="RetailLoyaltyRewardPoint.md" target="_blank">Miscellaneous/RetailLoyaltyRewardPoint</a>|
|[MaximumLoyaltyRewardPoints](#MaximumLoyaltyRewardPoints)||<a href="RetailLoyaltyRewardPoint.md" target="_blank">Miscellaneous/RetailLoyaltyRewardPoint</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="RetailLoyaltyRewardPoint.md" target="_blank">Miscellaneous/RetailLoyaltyRewardPoint</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailLoyaltyRewardPoint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailLoyaltyRewardPoint/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ExpirationTimeUnit name="ExpirationTimeUnit">ExpirationTimeUnit</a>

First included in: Miscellaneous/RetailLoyaltyRewardPoint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpirationTimeUnit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExpirationTimeValue name="ExpirationTimeValue">ExpirationTimeValue</a>

First included in: Miscellaneous/RetailLoyaltyRewardPoint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpirationTimeValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Redeemable name="Redeemable">Redeemable</a>

First included in: Miscellaneous/RetailLoyaltyRewardPoint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Redeemable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RedeemRanking name="RedeemRanking">RedeemRanking</a>

First included in: Miscellaneous/RetailLoyaltyRewardPoint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RedeemRanking attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RewardPointCurrency name="RewardPointCurrency">RewardPointCurrency</a>

First included in: Miscellaneous/RetailLoyaltyRewardPoint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RewardPointCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RewardPointId name="RewardPointId">RewardPointId</a>

First included in: Miscellaneous/RetailLoyaltyRewardPoint (this entity)  

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

### <a href=#RewardPointType name="RewardPointType">RewardPointType</a>

First included in: Miscellaneous/RetailLoyaltyRewardPoint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RewardPointType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VestingTimeUnit name="VestingTimeUnit">VestingTimeUnit</a>

First included in: Miscellaneous/RetailLoyaltyRewardPoint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VestingTimeUnit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VestingTimeValue name="VestingTimeValue">VestingTimeValue</a>

First included in: Miscellaneous/RetailLoyaltyRewardPoint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VestingTimeValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MaximumLoyaltyRewardPoints name="MaximumLoyaltyRewardPoints">MaximumLoyaltyRewardPoints</a>

First included in: Miscellaneous/RetailLoyaltyRewardPoint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumLoyaltyRewardPoints attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: Miscellaneous/RetailLoyaltyRewardPoint (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/erp/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
