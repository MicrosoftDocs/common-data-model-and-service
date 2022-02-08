---
title: RetailLoyaltyCardRewardPointAdjustment in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Loyalty adjustment in Miscellaneous(RetailLoyaltyCardRewardPointAdjustment)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/CommerceCustomers/Miscellaneous/RetailLoyaltyCardRewardPointAdjustment.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailLoyaltyCardRewardPointAdjustment/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Loyalty adjustment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailLoyaltyCardRewardPointAdjustment.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointAdjustment</a>|
|[AdjustmentId](#AdjustmentId)||<a href="RetailLoyaltyCardRewardPointAdjustment.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointAdjustment</a>|
|[AdjustmentStatus](#AdjustmentStatus)||<a href="RetailLoyaltyCardRewardPointAdjustment.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointAdjustment</a>|
|[Affiliation](#Affiliation)||<a href="RetailLoyaltyCardRewardPointAdjustment.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointAdjustment</a>|
|[Comment](#Comment)||<a href="RetailLoyaltyCardRewardPointAdjustment.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointAdjustment</a>|
|[LoyaltyCard](#LoyaltyCard)||<a href="RetailLoyaltyCardRewardPointAdjustment.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointAdjustment</a>|
|[RewardPoint](#RewardPoint)||<a href="RetailLoyaltyCardRewardPointAdjustment.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointAdjustment</a>|
|[RewardPointAmountQty](#RewardPointAmountQty)||<a href="RetailLoyaltyCardRewardPointAdjustment.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointAdjustment</a>|
|[TransactionDate](#TransactionDate)||<a href="RetailLoyaltyCardRewardPointAdjustment.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointAdjustment</a>|
|[Relationship_RetailAffiliationRelationshipId](#Relationship_RetailAffiliationRelationshipId)||<a href="RetailLoyaltyCardRewardPointAdjustment.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointAdjustment</a>|
|[Relationship_RetailLoyaltyCardRelationshipId](#Relationship_RetailLoyaltyCardRelationshipId)||<a href="RetailLoyaltyCardRewardPointAdjustment.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointAdjustment</a>|
|[Relationship_RetailLoyaltyRewardPointRelationshipId](#Relationship_RetailLoyaltyRewardPointRelationshipId)||<a href="RetailLoyaltyCardRewardPointAdjustment.md" target="_blank">Miscellaneous/RetailLoyaltyCardRewardPointAdjustment</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointAdjustment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailLoyaltyCardRewardPointAdjustment/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AdjustmentId name="AdjustmentId">AdjustmentId</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointAdjustment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdjustmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdjustmentStatus name="AdjustmentStatus">AdjustmentStatus</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointAdjustment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdjustmentStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Affiliation name="Affiliation">Affiliation</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointAdjustment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Affiliation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Comment name="Comment">Comment</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointAdjustment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Comment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyCard name="LoyaltyCard">LoyaltyCard</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointAdjustment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyCard attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RewardPoint name="RewardPoint">RewardPoint</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointAdjustment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RewardPoint attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RewardPointAmountQty name="RewardPointAmountQty">RewardPointAmountQty</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointAdjustment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount or quantity</td></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RewardPointAmountQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Amount or quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransactionDate name="TransactionDate">TransactionDate</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointAdjustment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Relationship_RetailAffiliationRelationshipId name="Relationship_RetailAffiliationRelationshipId">Relationship_RetailAffiliationRelationshipId</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointAdjustment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailAffiliationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailAffiliation.md" target="_blank">/core/operationsCommon/Tables/Commerce/CommerceCustomers/Miscellaneous/RetailAffiliation.cdm.json/RetailAffiliation</a></td><td><a href="RetailAffiliation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailLoyaltyCardRelationshipId name="Relationship_RetailLoyaltyCardRelationshipId">Relationship_RetailLoyaltyCardRelationshipId</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointAdjustment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailLoyaltyCardRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailLoyaltyCard.md" target="_blank">/core/operationsCommon/Tables/Commerce/CommerceCustomers/Miscellaneous/RetailLoyaltyCard.cdm.json/RetailLoyaltyCard</a></td><td><a href="RetailLoyaltyCard.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailLoyaltyRewardPointRelationshipId name="Relationship_RetailLoyaltyRewardPointRelationshipId">Relationship_RetailLoyaltyRewardPointRelationshipId</a>

First included in: Miscellaneous/RetailLoyaltyCardRewardPointAdjustment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailLoyaltyRewardPointRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailLoyaltyRewardPoint.md" target="_blank">/core/operationsCommon/Tables/Commerce/CommerceCustomers/Miscellaneous/RetailLoyaltyRewardPoint.cdm.json/RetailLoyaltyRewardPoint</a></td><td><a href="RetailLoyaltyRewardPoint.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
