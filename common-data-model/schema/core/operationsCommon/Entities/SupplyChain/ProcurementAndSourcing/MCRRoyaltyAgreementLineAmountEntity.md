---
title: MCRRoyaltyAgreementLineAmountEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Royalty agreement line amounts

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Royalty agreement line amounts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RoyaltyAgreementId](#RoyaltyAgreementId)||<a href="MCRRoyaltyAgreementLineAmountEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity</a>|
|[RoyaltyAgreementLineId](#RoyaltyAgreementLineId)||<a href="MCRRoyaltyAgreementLineAmountEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity</a>|
|[LineNumber](#LineNumber)||<a href="MCRRoyaltyAgreementLineAmountEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity</a>|
|[AmountTakenFrom](#AmountTakenFrom)||<a href="MCRRoyaltyAgreementLineAmountEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity</a>|
|[FromValue](#FromValue)||<a href="MCRRoyaltyAgreementLineAmountEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity</a>|
|[ToValue](#ToValue)||<a href="MCRRoyaltyAgreementLineAmountEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity</a>|
|[FromNetSalesAmount](#FromNetSalesAmount)||<a href="MCRRoyaltyAgreementLineAmountEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity</a>|
|[FromGrossSalesAmount](#FromGrossSalesAmount)||<a href="MCRRoyaltyAgreementLineAmountEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity</a>|
|[ToNetSalesAmount](#ToNetSalesAmount)||<a href="MCRRoyaltyAgreementLineAmountEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity</a>|
|[ToGrossSalesAmount](#ToGrossSalesAmount)||<a href="MCRRoyaltyAgreementLineAmountEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity</a>|
|[SalesUnitSymbol](#SalesUnitSymbol)||<a href="MCRRoyaltyAgreementLineAmountEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity</a>|
|[SalesPriceQuantity](#SalesPriceQuantity)||<a href="MCRRoyaltyAgreementLineAmountEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity</a>|
|[RoyaltyValueType](#RoyaltyValueType)||<a href="MCRRoyaltyAgreementLineAmountEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity</a>|
|[RoyaltyValue](#RoyaltyValue)||<a href="MCRRoyaltyAgreementLineAmountEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity</a>|
|[RoyaltyAmountPerProductUnitSold](#RoyaltyAmountPerProductUnitSold)||<a href="MCRRoyaltyAgreementLineAmountEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity</a>|
|[FixedRoyaltyAmount](#FixedRoyaltyAmount)||<a href="MCRRoyaltyAgreementLineAmountEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity</a>|
|[RoyaltyPercentage](#RoyaltyPercentage)||<a href="MCRRoyaltyAgreementLineAmountEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity</a>|
|[VendorAccountNumber](#VendorAccountNumber)||<a href="MCRRoyaltyAgreementLineAmountEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity</a>|
|[Relationship_RoyaltyAgreementLineRelationshipId](#Relationship_RoyaltyAgreementLineRelationshipId)||<a href="MCRRoyaltyAgreementLineAmountEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity</a>|
|[BackingTable_MCRRoyaltyTablePricingRelationshipId](#BackingTable_MCRRoyaltyTablePricingRelationshipId)||<a href="MCRRoyaltyAgreementLineAmountEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="MCRRoyaltyAgreementLineAmountEntity.md" target="_blank">ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity</a>|

### <a href=#RoyaltyAgreementId name="RoyaltyAgreementId">RoyaltyAgreementId</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Royalty agreement Id</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoyaltyAgreementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Royalty agreement Id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoyaltyAgreementLineId name="RoyaltyAgreementLineId">RoyaltyAgreementLineId</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Royalty agreement line Id</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoyaltyAgreementLineId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Royalty agreement line Id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Line number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Line number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountTakenFrom name="AmountTakenFrom">AmountTakenFrom</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountTakenFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromValue name="FromValue">FromValue</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToValue name="ToValue">ToValue</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromNetSalesAmount name="FromNetSalesAmount">FromNetSalesAmount</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>From net amount</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromNetSalesAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>From net amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromGrossSalesAmount name="FromGrossSalesAmount">FromGrossSalesAmount</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>From gross amount</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromGrossSalesAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>From gross amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToNetSalesAmount name="ToNetSalesAmount">ToNetSalesAmount</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>To net amount</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToNetSalesAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>To net amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToGrossSalesAmount name="ToGrossSalesAmount">ToGrossSalesAmount</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>To gross amount</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToGrossSalesAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>To gross amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesUnitSymbol name="SalesUnitSymbol">SalesUnitSymbol</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPriceQuantity name="SalesPriceQuantity">SalesPriceQuantity</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoyaltyValueType name="RoyaltyValueType">RoyaltyValueType</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoyaltyValueType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoyaltyValue name="RoyaltyValue">RoyaltyValue</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoyaltyValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoyaltyAmountPerProductUnitSold name="RoyaltyAmountPerProductUnitSold">RoyaltyAmountPerProductUnitSold</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Royalty amount per product unit sold</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoyaltyAmountPerProductUnitSold attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Royalty amount per product unit sold</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedRoyaltyAmount name="FixedRoyaltyAmount">FixedRoyaltyAmount</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fixed royalty amount</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedRoyaltyAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fixed royalty amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoyaltyPercentage name="RoyaltyPercentage">RoyaltyPercentage</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Royalty percentage</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoyaltyPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Royalty percentage</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAccountNumber name="VendorAccountNumber">VendorAccountNumber</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RoyaltyAgreementLineRelationshipId name="Relationship_RoyaltyAgreementLineRelationshipId">Relationship_RoyaltyAgreementLineRelationshipId</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RoyaltyAgreementLineRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_MCRRoyaltyTablePricingRelationshipId name="BackingTable_MCRRoyaltyTablePricingRelationshipId">BackingTable_MCRRoyaltyTablePricingRelationshipId</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_MCRRoyaltyTablePricingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Reference/MCRRoyaltyTablePricing.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Reference/MCRRoyaltyTablePricing.cdm.json/MCRRoyaltyTablePricing</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Reference/MCRRoyaltyTablePricing.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/MCRRoyaltyAgreementLineAmountEntity (this entity)  

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
