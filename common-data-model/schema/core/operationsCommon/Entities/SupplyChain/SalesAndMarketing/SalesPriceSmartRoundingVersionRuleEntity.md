---
title: SalesPriceSmartRoundingVersionRuleEntity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Sales price smart rounding version rules in SalesAndMarketing(SalesPriceSmartRoundingVersionRuleEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/SalesPriceSmartRoundingVersionRuleEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales price smart rounding version rules</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[SalesPriceSmartRoundingVersionId](#SalesPriceSmartRoundingVersionId)||<a href="SalesPriceSmartRoundingVersionRuleEntity.md" target="_blank">SalesAndMarketing/SalesPriceSmartRoundingVersionRuleEntity</a>|
|[RoundingSyntax](#RoundingSyntax)||<a href="SalesPriceSmartRoundingVersionRuleEntity.md" target="_blank">SalesAndMarketing/SalesPriceSmartRoundingVersionRuleEntity</a>|
|[RoundingDownLimitPoint](#RoundingDownLimitPoint)||<a href="SalesPriceSmartRoundingVersionRuleEntity.md" target="_blank">SalesAndMarketing/SalesPriceSmartRoundingVersionRuleEntity</a>|
|[RoundingUpLimitPoint](#RoundingUpLimitPoint)||<a href="SalesPriceSmartRoundingVersionRuleEntity.md" target="_blank">SalesAndMarketing/SalesPriceSmartRoundingVersionRuleEntity</a>|
|[FromUnitPrice](#FromUnitPrice)||<a href="SalesPriceSmartRoundingVersionRuleEntity.md" target="_blank">SalesAndMarketing/SalesPriceSmartRoundingVersionRuleEntity</a>|
|[ToUnitPrice](#ToUnitPrice)||<a href="SalesPriceSmartRoundingVersionRuleEntity.md" target="_blank">SalesAndMarketing/SalesPriceSmartRoundingVersionRuleEntity</a>|
|[RoundingVersionRecId](#RoundingVersionRecId)||<a href="SalesPriceSmartRoundingVersionRuleEntity.md" target="_blank">SalesAndMarketing/SalesPriceSmartRoundingVersionRuleEntity</a>|
|[BackingTable_PriceDiscSmartRoundingRuleRelationshipId](#BackingTable_PriceDiscSmartRoundingRuleRelationshipId)||<a href="SalesPriceSmartRoundingVersionRuleEntity.md" target="_blank">SalesAndMarketing/SalesPriceSmartRoundingVersionRuleEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SalesPriceSmartRoundingVersionRuleEntity.md" target="_blank">SalesAndMarketing/SalesPriceSmartRoundingVersionRuleEntity</a>|

### <a href=#SalesPriceSmartRoundingVersionId name="SalesPriceSmartRoundingVersionId">SalesPriceSmartRoundingVersionId</a>

First included in: SalesAndMarketing/SalesPriceSmartRoundingVersionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceSmartRoundingVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoundingSyntax name="RoundingSyntax">RoundingSyntax</a>

First included in: SalesAndMarketing/SalesPriceSmartRoundingVersionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundingSyntax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoundingDownLimitPoint name="RoundingDownLimitPoint">RoundingDownLimitPoint</a>

First included in: SalesAndMarketing/SalesPriceSmartRoundingVersionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundingDownLimitPoint attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoundingUpLimitPoint name="RoundingUpLimitPoint">RoundingUpLimitPoint</a>

First included in: SalesAndMarketing/SalesPriceSmartRoundingVersionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundingUpLimitPoint attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromUnitPrice name="FromUnitPrice">FromUnitPrice</a>

First included in: SalesAndMarketing/SalesPriceSmartRoundingVersionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromUnitPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToUnitPrice name="ToUnitPrice">ToUnitPrice</a>

First included in: SalesAndMarketing/SalesPriceSmartRoundingVersionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToUnitPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoundingVersionRecId name="RoundingVersionRecId">RoundingVersionRecId</a>

First included in: SalesAndMarketing/SalesPriceSmartRoundingVersionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundingVersionRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PriceDiscSmartRoundingRuleRelationshipId name="BackingTable_PriceDiscSmartRoundingRuleRelationshipId">BackingTable_PriceDiscSmartRoundingRuleRelationshipId</a>

First included in: SalesAndMarketing/SalesPriceSmartRoundingVersionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PriceDiscSmartRoundingRuleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Group/PriceDiscSmartRoundingRule.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/PriceDiscSmartRoundingRule.cdm.json/PriceDiscSmartRoundingRule</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Group/PriceDiscSmartRoundingRule.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/SalesPriceSmartRoundingVersionRuleEntity (this entity)  

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
