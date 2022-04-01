---
title: RetailLoyaltyRedeemSchemeLineEntity in CommerceCustomers - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Loyalty redeem lines in CommerceCustomers(RetailLoyaltyRedeemSchemeLineEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Loyalty redeem lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[FromRewardPoint](#FromRewardPoint)||<a href="RetailLoyaltyRedeemSchemeLineEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity</a>|
|[FromRewardPointAmountQty](#FromRewardPointAmountQty)||<a href="RetailLoyaltyRedeemSchemeLineEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity</a>|
|[LoyaltyScheme](#LoyaltyScheme)||<a href="RetailLoyaltyRedeemSchemeLineEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity</a>|
|[LoyaltyTier](#LoyaltyTier)||<a href="RetailLoyaltyRedeemSchemeLineEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity</a>|
|[ToRetailGroupMemberLine](#ToRetailGroupMemberLine)||<a href="RetailLoyaltyRedeemSchemeLineEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity</a>|
|[ToRewardAmountCurrency](#ToRewardAmountCurrency)||<a href="RetailLoyaltyRedeemSchemeLineEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity</a>|
|[ToRewardAmountQty](#ToRewardAmountQty)||<a href="RetailLoyaltyRedeemSchemeLineEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity</a>|
|[ToRewardType](#ToRewardType)||<a href="RetailLoyaltyRedeemSchemeLineEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity</a>|
|[ValidFrom](#ValidFrom)||<a href="RetailLoyaltyRedeemSchemeLineEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity</a>|
|[ValidTo](#ValidTo)||<a href="RetailLoyaltyRedeemSchemeLineEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity</a>|
|[LineNumber](#LineNumber)||<a href="RetailLoyaltyRedeemSchemeLineEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity</a>|
|[LoyaltySchemeId](#LoyaltySchemeId)||<a href="RetailLoyaltyRedeemSchemeLineEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity</a>|
|[RetailLoyaltyTier_Affiliation](#RetailLoyaltyTier_Affiliation)||<a href="RetailLoyaltyRedeemSchemeLineEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity</a>|
|[LoyaltyTierId](#LoyaltyTierId)||<a href="RetailLoyaltyRedeemSchemeLineEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity</a>|
|[LoyaltyProgramName](#LoyaltyProgramName)||<a href="RetailLoyaltyRedeemSchemeLineEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity</a>|
|[ItemId](#ItemId)||<a href="RetailLoyaltyRedeemSchemeLineEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity</a>|
|[Color](#Color)||<a href="RetailLoyaltyRedeemSchemeLineEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity</a>|
|[Size](#Size)||<a href="RetailLoyaltyRedeemSchemeLineEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity</a>|
|[Style](#Style)||<a href="RetailLoyaltyRedeemSchemeLineEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity</a>|
|[ConfigId](#ConfigId)||<a href="RetailLoyaltyRedeemSchemeLineEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity</a>|
|[CategoryHierarchyName](#CategoryHierarchyName)||<a href="RetailLoyaltyRedeemSchemeLineEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity</a>|
|[CategoryName](#CategoryName)||<a href="RetailLoyaltyRedeemSchemeLineEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity</a>|
|[FromRewardPointId](#FromRewardPointId)||<a href="RetailLoyaltyRedeemSchemeLineEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity</a>|
|[RetailAffiliationId](#RetailAffiliationId)||<a href="RetailLoyaltyRedeemSchemeLineEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity</a>|
|[AffiliationName](#AffiliationName)||<a href="RetailLoyaltyRedeemSchemeLineEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity</a>|
|[SourceDataAreaId](#SourceDataAreaId)||<a href="RetailLoyaltyRedeemSchemeLineEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity</a>|
|[BackingTable_RetailLoyaltyRedeemSchemeLineRelationshipId](#BackingTable_RetailLoyaltyRedeemSchemeLineRelationshipId)||<a href="RetailLoyaltyRedeemSchemeLineEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity</a>|

### <a href=#FromRewardPoint name="FromRewardPoint">FromRewardPoint</a>

First included in: CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromRewardPoint attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromRewardPointAmountQty name="FromRewardPointAmountQty">FromRewardPointAmountQty</a>

First included in: CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromRewardPointAmountQty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyScheme name="LoyaltyScheme">LoyaltyScheme</a>

First included in: CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyScheme attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyTier name="LoyaltyTier">LoyaltyTier</a>

First included in: CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity (this entity)  

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

### <a href=#ToRetailGroupMemberLine name="ToRetailGroupMemberLine">ToRetailGroupMemberLine</a>

First included in: CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToRetailGroupMemberLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToRewardAmountCurrency name="ToRewardAmountCurrency">ToRewardAmountCurrency</a>

First included in: CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToRewardAmountCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToRewardAmountQty name="ToRewardAmountQty">ToRewardAmountQty</a>

First included in: CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToRewardAmountQty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToRewardType name="ToRewardType">ToRewardType</a>

First included in: CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToRewardType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Start date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>End date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltySchemeId name="LoyaltySchemeId">LoyaltySchemeId</a>

First included in: CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltySchemeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailLoyaltyTier_Affiliation name="RetailLoyaltyTier_Affiliation">RetailLoyaltyTier_Affiliation</a>

First included in: CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity (this entity)  

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

First included in: CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyTierId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyProgramName name="LoyaltyProgramName">LoyaltyProgramName</a>

First included in: CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyProgramName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Color name="Color">Color</a>

First included in: CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Color attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Size name="Size">Size</a>

First included in: CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Size attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Style name="Style">Style</a>

First included in: CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Style attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConfigId name="ConfigId">ConfigId</a>

First included in: CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfigId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryHierarchyName name="CategoryHierarchyName">CategoryHierarchyName</a>

First included in: CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryHierarchyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryName name="CategoryName">CategoryName</a>

First included in: CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromRewardPointId name="FromRewardPointId">FromRewardPointId</a>

First included in: CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromRewardPointId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailAffiliationId name="RetailAffiliationId">RetailAffiliationId</a>

First included in: CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailAffiliationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AffiliationName name="AffiliationName">AffiliationName</a>

First included in: CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AffiliationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceDataAreaId name="SourceDataAreaId">SourceDataAreaId</a>

First included in: CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailLoyaltyRedeemSchemeLineRelationshipId name="BackingTable_RetailLoyaltyRedeemSchemeLineRelationshipId">BackingTable_RetailLoyaltyRedeemSchemeLineRelationshipId</a>

First included in: CommerceCustomers/RetailLoyaltyRedeemSchemeLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailLoyaltyRedeemSchemeLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/CommerceCustomers/Main/RetailLoyaltyRedeemSchemeLine.md" target="_blank">/core/operationsCommon/Tables/Commerce/CommerceCustomers/Main/RetailLoyaltyRedeemSchemeLine.cdm.json/RetailLoyaltyRedeemSchemeLine</a></td><td><a href="../../../Tables/Commerce/CommerceCustomers/Main/RetailLoyaltyRedeemSchemeLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
