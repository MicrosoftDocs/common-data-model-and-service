---
title: RetailLoyaltyTierPriceGroupEntity in CommerceCustomers - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Loyalty tier price groups in CommerceCustomers(RetailLoyaltyTierPriceGroupEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/CommerceCustomers/RetailLoyaltyTierPriceGroupEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Loyalty tier price groups</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[PriceDiscGroup](#PriceDiscGroup)||<a href="RetailLoyaltyTierPriceGroupEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyTierPriceGroupEntity</a>|
|[RetailAffiliation](#RetailAffiliation)||<a href="RetailLoyaltyTierPriceGroupEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyTierPriceGroupEntity</a>|
|[RetailLoyaltyTier](#RetailLoyaltyTier)||<a href="RetailLoyaltyTierPriceGroupEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyTierPriceGroupEntity</a>|
|[PriceGroupId](#PriceGroupId)||<a href="RetailLoyaltyTierPriceGroupEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyTierPriceGroupEntity</a>|
|[RetailLoyaltyTier_Affiliation](#RetailLoyaltyTier_Affiliation)||<a href="RetailLoyaltyTierPriceGroupEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyTierPriceGroupEntity</a>|
|[LoyaltyTierId](#LoyaltyTierId)||<a href="RetailLoyaltyTierPriceGroupEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyTierPriceGroupEntity</a>|
|[PriceGroupCompany](#PriceGroupCompany)||<a href="RetailLoyaltyTierPriceGroupEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyTierPriceGroupEntity</a>|
|[LoyaltyName](#LoyaltyName)||<a href="RetailLoyaltyTierPriceGroupEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyTierPriceGroupEntity</a>|
|[BackingTable_RetailAffiliationPriceGroupRelationshipId](#BackingTable_RetailAffiliationPriceGroupRelationshipId)||<a href="RetailLoyaltyTierPriceGroupEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyTierPriceGroupEntity</a>|

### <a href=#PriceDiscGroup name="PriceDiscGroup">PriceDiscGroup</a>

First included in: CommerceCustomers/RetailLoyaltyTierPriceGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceDiscGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailAffiliation name="RetailAffiliation">RetailAffiliation</a>

First included in: CommerceCustomers/RetailLoyaltyTierPriceGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailAffiliation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailLoyaltyTier name="RetailLoyaltyTier">RetailLoyaltyTier</a>

First included in: CommerceCustomers/RetailLoyaltyTierPriceGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailLoyaltyTier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceGroupId name="PriceGroupId">PriceGroupId</a>

First included in: CommerceCustomers/RetailLoyaltyTierPriceGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailLoyaltyTier_Affiliation name="RetailLoyaltyTier_Affiliation">RetailLoyaltyTier_Affiliation</a>

First included in: CommerceCustomers/RetailLoyaltyTierPriceGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailLoyaltyTier_Affiliation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyTierId name="LoyaltyTierId">LoyaltyTierId</a>

First included in: CommerceCustomers/RetailLoyaltyTierPriceGroupEntity (this entity)  

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

### <a href=#PriceGroupCompany name="PriceGroupCompany">PriceGroupCompany</a>

First included in: CommerceCustomers/RetailLoyaltyTierPriceGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceGroupCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyName name="LoyaltyName">LoyaltyName</a>

First included in: CommerceCustomers/RetailLoyaltyTierPriceGroupEntity (this entity)  

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

### <a href=#BackingTable_RetailAffiliationPriceGroupRelationshipId name="BackingTable_RetailAffiliationPriceGroupRelationshipId">BackingTable_RetailAffiliationPriceGroupRelationshipId</a>

First included in: CommerceCustomers/RetailLoyaltyTierPriceGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailAffiliationPriceGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/CommerceCustomers/Miscellaneous/RetailAffiliationPriceGroup.md" target="_blank">/core/operationsCommon/Tables/Commerce/CommerceCustomers/Miscellaneous/RetailAffiliationPriceGroup.cdm.json/RetailAffiliationPriceGroup</a></td><td><a href="../../../Tables/Commerce/CommerceCustomers/Miscellaneous/RetailAffiliationPriceGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
