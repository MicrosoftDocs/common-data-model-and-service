---
title: RetailLoyaltyCardRewardPointDeduction - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailLoyaltyCardRewardPointDeduction

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailLoyaltyCardRewardPointDeduction.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailLoyaltyCardRewardPointDeduction/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailLoyaltyCardRewardPointDeduction.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointDeduction</a>|
|[RewardPointAmountQty](#RewardPointAmountQty)||<a href="RetailLoyaltyCardRewardPointDeduction.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointDeduction</a>|
|[RewardPointDeductTrans](#RewardPointDeductTrans)||<a href="RetailLoyaltyCardRewardPointDeduction.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointDeduction</a>|
|[RewardPointSourceTrans](#RewardPointSourceTrans)||<a href="RetailLoyaltyCardRewardPointDeduction.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointDeduction</a>|
|[Relationship_RewardPointDeductTransRelationshipId](#Relationship_RewardPointDeductTransRelationshipId)||<a href="RetailLoyaltyCardRewardPointDeduction.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointDeduction</a>|
|[Relationship_RewardPointSourceTransRelationshipId](#Relationship_RewardPointSourceTransRelationshipId)||<a href="RetailLoyaltyCardRewardPointDeduction.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointDeduction</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointDeduction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailLoyaltyCardRewardPointDeduction/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RewardPointAmountQty name="RewardPointAmountQty">RewardPointAmountQty</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointDeduction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RewardPointAmountQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RewardPointDeductTrans name="RewardPointDeductTrans">RewardPointDeductTrans</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointDeduction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RewardPointDeductTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RewardPointSourceTrans name="RewardPointSourceTrans">RewardPointSourceTrans</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointDeduction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RewardPointSourceTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_RewardPointDeductTransRelationshipId name="Relationship_RewardPointDeductTransRelationshipId">Relationship_RewardPointDeductTransRelationshipId</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointDeduction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RewardPointDeductTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/RetailLoyaltyCardRewardPointTrans.md" target="_blank">/core/erp/Tables/Commerce/Retail/Transaction/RetailLoyaltyCardRewardPointTrans.cdm.json/RetailLoyaltyCardRewardPointTrans</a></td><td><a href="../Transaction/RetailLoyaltyCardRewardPointTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RewardPointSourceTransRelationshipId name="Relationship_RewardPointSourceTransRelationshipId">Relationship_RewardPointSourceTransRelationshipId</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointDeduction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RewardPointSourceTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/RetailLoyaltyCardRewardPointTrans.md" target="_blank">/core/erp/Tables/Commerce/Retail/Transaction/RetailLoyaltyCardRewardPointTrans.cdm.json/RetailLoyaltyCardRewardPointTrans</a></td><td><a href="../Transaction/RetailLoyaltyCardRewardPointTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
