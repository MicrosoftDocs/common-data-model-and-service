---
title: PSNCashPositionColumnSetupEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/30/2020
ms.author: nebanfic
---

# Cash position parameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/PSNCashPositionColumnSetupEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cash position parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ColumnOneLabel](#ColumnOneLabel)||<a href="PSNCashPositionColumnSetupEntity.md" target="_blank">GeneralLedger/PSNCashPositionColumnSetupEntity</a>|
|[ColumnOneRange](#ColumnOneRange)||<a href="PSNCashPositionColumnSetupEntity.md" target="_blank">GeneralLedger/PSNCashPositionColumnSetupEntity</a>|
|[ColumnTwoLabel](#ColumnTwoLabel)||<a href="PSNCashPositionColumnSetupEntity.md" target="_blank">GeneralLedger/PSNCashPositionColumnSetupEntity</a>|
|[ColumnTwoRange](#ColumnTwoRange)||<a href="PSNCashPositionColumnSetupEntity.md" target="_blank">GeneralLedger/PSNCashPositionColumnSetupEntity</a>|
|[ColumnTwoCreditRange](#ColumnTwoCreditRange)||<a href="PSNCashPositionColumnSetupEntity.md" target="_blank">GeneralLedger/PSNCashPositionColumnSetupEntity</a>|
|[ColumnTwoDebitRange](#ColumnTwoDebitRange)||<a href="PSNCashPositionColumnSetupEntity.md" target="_blank">GeneralLedger/PSNCashPositionColumnSetupEntity</a>|
|[ColumnThreeLabel](#ColumnThreeLabel)||<a href="PSNCashPositionColumnSetupEntity.md" target="_blank">GeneralLedger/PSNCashPositionColumnSetupEntity</a>|
|[ColumnThreeRange](#ColumnThreeRange)||<a href="PSNCashPositionColumnSetupEntity.md" target="_blank">GeneralLedger/PSNCashPositionColumnSetupEntity</a>|
|[ColumnThreeCreditRange](#ColumnThreeCreditRange)||<a href="PSNCashPositionColumnSetupEntity.md" target="_blank">GeneralLedger/PSNCashPositionColumnSetupEntity</a>|
|[ColumnThreeDebitRange](#ColumnThreeDebitRange)||<a href="PSNCashPositionColumnSetupEntity.md" target="_blank">GeneralLedger/PSNCashPositionColumnSetupEntity</a>|
|[ColumnFourLabel](#ColumnFourLabel)||<a href="PSNCashPositionColumnSetupEntity.md" target="_blank">GeneralLedger/PSNCashPositionColumnSetupEntity</a>|
|[ColumnFourRange](#ColumnFourRange)||<a href="PSNCashPositionColumnSetupEntity.md" target="_blank">GeneralLedger/PSNCashPositionColumnSetupEntity</a>|
|[ColumnFourCreditRange](#ColumnFourCreditRange)||<a href="PSNCashPositionColumnSetupEntity.md" target="_blank">GeneralLedger/PSNCashPositionColumnSetupEntity</a>|
|[ColumnFourDebitRange](#ColumnFourDebitRange)||<a href="PSNCashPositionColumnSetupEntity.md" target="_blank">GeneralLedger/PSNCashPositionColumnSetupEntity</a>|
|[ColumnFiveLabel](#ColumnFiveLabel)||<a href="PSNCashPositionColumnSetupEntity.md" target="_blank">GeneralLedger/PSNCashPositionColumnSetupEntity</a>|
|[ColumnSixLabel](#ColumnSixLabel)||<a href="PSNCashPositionColumnSetupEntity.md" target="_blank">GeneralLedger/PSNCashPositionColumnSetupEntity</a>|
|[ColumnSixRange](#ColumnSixRange)||<a href="PSNCashPositionColumnSetupEntity.md" target="_blank">GeneralLedger/PSNCashPositionColumnSetupEntity</a>|
|[ColumnSixCreditRange](#ColumnSixCreditRange)||<a href="PSNCashPositionColumnSetupEntity.md" target="_blank">GeneralLedger/PSNCashPositionColumnSetupEntity</a>|
|[ColumnSixDebitRange](#ColumnSixDebitRange)||<a href="PSNCashPositionColumnSetupEntity.md" target="_blank">GeneralLedger/PSNCashPositionColumnSetupEntity</a>|
|[ColumnSevenLabel](#ColumnSevenLabel)||<a href="PSNCashPositionColumnSetupEntity.md" target="_blank">GeneralLedger/PSNCashPositionColumnSetupEntity</a>|
|[ColumnSevenRange](#ColumnSevenRange)||<a href="PSNCashPositionColumnSetupEntity.md" target="_blank">GeneralLedger/PSNCashPositionColumnSetupEntity</a>|
|[ColumnSevenCreditRange](#ColumnSevenCreditRange)||<a href="PSNCashPositionColumnSetupEntity.md" target="_blank">GeneralLedger/PSNCashPositionColumnSetupEntity</a>|
|[ColumnSevenDebitRange](#ColumnSevenDebitRange)||<a href="PSNCashPositionColumnSetupEntity.md" target="_blank">GeneralLedger/PSNCashPositionColumnSetupEntity</a>|
|[ColumnEightLabel](#ColumnEightLabel)||<a href="PSNCashPositionColumnSetupEntity.md" target="_blank">GeneralLedger/PSNCashPositionColumnSetupEntity</a>|
|[Key](#Key)||<a href="PSNCashPositionColumnSetupEntity.md" target="_blank">GeneralLedger/PSNCashPositionColumnSetupEntity</a>|
|[BackingTable_PSNCashPositionColumnSetupRelationshipId](#BackingTable_PSNCashPositionColumnSetupRelationshipId)||<a href="PSNCashPositionColumnSetupEntity.md" target="_blank">GeneralLedger/PSNCashPositionColumnSetupEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PSNCashPositionColumnSetupEntity.md" target="_blank">GeneralLedger/PSNCashPositionColumnSetupEntity</a>|

### <a href=#ColumnOneLabel name="ColumnOneLabel">ColumnOneLabel</a>

First included in: GeneralLedger/PSNCashPositionColumnSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ColumnOneLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ColumnOneRange name="ColumnOneRange">ColumnOneRange</a>

First included in: GeneralLedger/PSNCashPositionColumnSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ColumnOneRange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ColumnTwoLabel name="ColumnTwoLabel">ColumnTwoLabel</a>

First included in: GeneralLedger/PSNCashPositionColumnSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ColumnTwoLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ColumnTwoRange name="ColumnTwoRange">ColumnTwoRange</a>

First included in: GeneralLedger/PSNCashPositionColumnSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ColumnTwoRange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ColumnTwoCreditRange name="ColumnTwoCreditRange">ColumnTwoCreditRange</a>

First included in: GeneralLedger/PSNCashPositionColumnSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ColumnTwoCreditRange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ColumnTwoDebitRange name="ColumnTwoDebitRange">ColumnTwoDebitRange</a>

First included in: GeneralLedger/PSNCashPositionColumnSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ColumnTwoDebitRange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ColumnThreeLabel name="ColumnThreeLabel">ColumnThreeLabel</a>

First included in: GeneralLedger/PSNCashPositionColumnSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ColumnThreeLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ColumnThreeRange name="ColumnThreeRange">ColumnThreeRange</a>

First included in: GeneralLedger/PSNCashPositionColumnSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ColumnThreeRange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ColumnThreeCreditRange name="ColumnThreeCreditRange">ColumnThreeCreditRange</a>

First included in: GeneralLedger/PSNCashPositionColumnSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ColumnThreeCreditRange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ColumnThreeDebitRange name="ColumnThreeDebitRange">ColumnThreeDebitRange</a>

First included in: GeneralLedger/PSNCashPositionColumnSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ColumnThreeDebitRange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ColumnFourLabel name="ColumnFourLabel">ColumnFourLabel</a>

First included in: GeneralLedger/PSNCashPositionColumnSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ColumnFourLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ColumnFourRange name="ColumnFourRange">ColumnFourRange</a>

First included in: GeneralLedger/PSNCashPositionColumnSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ColumnFourRange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ColumnFourCreditRange name="ColumnFourCreditRange">ColumnFourCreditRange</a>

First included in: GeneralLedger/PSNCashPositionColumnSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ColumnFourCreditRange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ColumnFourDebitRange name="ColumnFourDebitRange">ColumnFourDebitRange</a>

First included in: GeneralLedger/PSNCashPositionColumnSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ColumnFourDebitRange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ColumnFiveLabel name="ColumnFiveLabel">ColumnFiveLabel</a>

First included in: GeneralLedger/PSNCashPositionColumnSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ColumnFiveLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ColumnSixLabel name="ColumnSixLabel">ColumnSixLabel</a>

First included in: GeneralLedger/PSNCashPositionColumnSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ColumnSixLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ColumnSixRange name="ColumnSixRange">ColumnSixRange</a>

First included in: GeneralLedger/PSNCashPositionColumnSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ColumnSixRange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ColumnSixCreditRange name="ColumnSixCreditRange">ColumnSixCreditRange</a>

First included in: GeneralLedger/PSNCashPositionColumnSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ColumnSixCreditRange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ColumnSixDebitRange name="ColumnSixDebitRange">ColumnSixDebitRange</a>

First included in: GeneralLedger/PSNCashPositionColumnSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ColumnSixDebitRange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ColumnSevenLabel name="ColumnSevenLabel">ColumnSevenLabel</a>

First included in: GeneralLedger/PSNCashPositionColumnSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ColumnSevenLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ColumnSevenRange name="ColumnSevenRange">ColumnSevenRange</a>

First included in: GeneralLedger/PSNCashPositionColumnSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ColumnSevenRange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ColumnSevenCreditRange name="ColumnSevenCreditRange">ColumnSevenCreditRange</a>

First included in: GeneralLedger/PSNCashPositionColumnSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ColumnSevenCreditRange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ColumnSevenDebitRange name="ColumnSevenDebitRange">ColumnSevenDebitRange</a>

First included in: GeneralLedger/PSNCashPositionColumnSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ColumnSevenDebitRange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ColumnEightLabel name="ColumnEightLabel">ColumnEightLabel</a>

First included in: GeneralLedger/PSNCashPositionColumnSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ColumnEightLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: GeneralLedger/PSNCashPositionColumnSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PSNCashPositionColumnSetupRelationshipId name="BackingTable_PSNCashPositionColumnSetupRelationshipId">BackingTable_PSNCashPositionColumnSetupRelationshipId</a>

First included in: GeneralLedger/PSNCashPositionColumnSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PSNCashPositionColumnSetupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Bank/Parameter/PSNCashPositionColumnSetup.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Parameter/PSNCashPositionColumnSetup.cdm.json/PSNCashPositionColumnSetup</a></td><td><a href="../../../Tables/Finance/Bank/Parameter/PSNCashPositionColumnSetup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: GeneralLedger/PSNCashPositionColumnSetupEntity (this entity)  

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
