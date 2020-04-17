---
title: RetailTransactionMarkupLineEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/16/2020
ms.author: nebanfic
---

# @RET261133

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Commerce/Retail/RetailTransactionMarkupLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.Application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>@RET261133</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CalculatedAmount](#CalculatedAmount)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[Channel](#Channel)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[MarkupCode](#MarkupCode)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[LineNumber](#LineNumber)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[MarkupCategoryType](#MarkupCategoryType)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[SalesLineNumber](#SalesLineNumber)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[TaxAmount](#TaxAmount)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[TaxAmountExclusive](#TaxAmountExclusive)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[TaxAmountInclusive](#TaxAmountInclusive)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[SalesTaxGroup](#SalesTaxGroup)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[ItemTaxGroup](#ItemTaxGroup)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[Terminal](#Terminal)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[TransactionNumber](#TransactionNumber)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[MarkupValue](#MarkupValue)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[RetailChannelTableOMOperatingUnitID](#RetailChannelTableOMOperatingUnitID)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[OperatingUnitNumber](#OperatingUnitNumber)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[ModuleType](#ModuleType)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[Store](#Store)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[Keep](#Keep)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[MarkupAutoTableRecId](#MarkupAutoTableRecId)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[NonGST](#NonGST)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[Exempt](#Exempt)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[HSNCode](#HSNCode)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[ServiceAccountingCode](#ServiceAccountingCode)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[ServiceCategory](#ServiceCategory)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[ITCCategory](#ITCCategory)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[TaxRateType](#TaxRateType)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[IsOverriddenLine](#IsOverriddenLine)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[BackingTable_RetailTransactionMarkupTransRelationshipId](#BackingTable_RetailTransactionMarkupTransRelationshipId)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailTransactionMarkupLineEntity.md" target="_blank">Retail/RetailTransactionMarkupLineEntity</a>|

### <a href=#CalculatedAmount name="CalculatedAmount">CalculatedAmount</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculatedAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Channel name="Channel">Channel</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Channel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MarkupCode name="MarkupCode">MarkupCode</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarkupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

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

### <a href=#MarkupCategoryType name="MarkupCategoryType">MarkupCategoryType</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarkupCategoryType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesLineNumber name="SalesLineNumber">SalesLineNumber</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmount name="TaxAmount">TaxAmount</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmountExclusive name="TaxAmountExclusive">TaxAmountExclusive</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountExclusive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmountInclusive name="TaxAmountInclusive">TaxAmountInclusive</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountInclusive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroup name="SalesTaxGroup">SalesTaxGroup</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemTaxGroup name="ItemTaxGroup">ItemTaxGroup</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Terminal name="Terminal">Terminal</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Terminal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionNumber name="TransactionNumber">TransactionNumber</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MarkupValue name="MarkupValue">MarkupValue</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarkupValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailChannelTableOMOperatingUnitID name="RetailChannelTableOMOperatingUnitID">RetailChannelTableOMOperatingUnitID</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailChannelTableOMOperatingUnitID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperatingUnitNumber name="OperatingUnitNumber">OperatingUnitNumber</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatingUnitNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ModuleType name="ModuleType">ModuleType</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ModuleType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Store name="Store">Store</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Store attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Keep name="Keep">Keep</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Keep attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MarkupAutoTableRecId name="MarkupAutoTableRecId">MarkupAutoTableRecId</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarkupAutoTableRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NonGST name="NonGST">NonGST</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NonGST attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Exempt name="Exempt">Exempt</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Exempt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HSNCode name="HSNCode">HSNCode</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HSNCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceAccountingCode name="ServiceAccountingCode">ServiceAccountingCode</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceAccountingCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceCategory name="ServiceCategory">ServiceCategory</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ITCCategory name="ITCCategory">ITCCategory</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ITCCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxRateType name="TaxRateType">TaxRateType</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOverriddenLine name="IsOverriddenLine">IsOverriddenLine</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOverriddenLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailTransactionMarkupTransRelationshipId name="BackingTable_RetailTransactionMarkupTransRelationshipId">BackingTable_RetailTransactionMarkupTransRelationshipId</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailTransactionMarkupTransRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Retail/RetailTransactionMarkupLineEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
