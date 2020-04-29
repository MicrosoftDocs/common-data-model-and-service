---
title: ProcurementProductCategoryItemSalesTaxGroupAssignmentEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Procurement product category item sales tax group assignments

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Tax/ProcurementProductCategoryItemSalesTaxGroupAssignmentEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Procurement product category item sales tax group assignments</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ProductCategoryHierarchyName](#ProductCategoryHierarchyName)||<a href="ProcurementProductCategoryItemSalesTaxGroupAssignmentEntity.md" target="_blank">Tax/ProcurementProductCategoryItemSalesTaxGroupAssignmentEntity</a>|
|[ProductCategoryName](#ProductCategoryName)||<a href="ProcurementProductCategoryItemSalesTaxGroupAssignmentEntity.md" target="_blank">Tax/ProcurementProductCategoryItemSalesTaxGroupAssignmentEntity</a>|
|[ProductSalesTaxGroupLegalEntityId](#ProductSalesTaxGroupLegalEntityId)||<a href="ProcurementProductCategoryItemSalesTaxGroupAssignmentEntity.md" target="_blank">Tax/ProcurementProductCategoryItemSalesTaxGroupAssignmentEntity</a>|
|[ProductSalesTaxGroupId](#ProductSalesTaxGroupId)||<a href="ProcurementProductCategoryItemSalesTaxGroupAssignmentEntity.md" target="_blank">Tax/ProcurementProductCategoryItemSalesTaxGroupAssignmentEntity</a>|
|[IsPurchasingCalculatingWithholdingTax](#IsPurchasingCalculatingWithholdingTax)||<a href="ProcurementProductCategoryItemSalesTaxGroupAssignmentEntity.md" target="_blank">Tax/ProcurementProductCategoryItemSalesTaxGroupAssignmentEntity</a>|
|[ItemWithholdingTaxPurchaseGroupCode](#ItemWithholdingTaxPurchaseGroupCode)||<a href="ProcurementProductCategoryItemSalesTaxGroupAssignmentEntity.md" target="_blank">Tax/ProcurementProductCategoryItemSalesTaxGroupAssignmentEntity</a>|
|[BackingTable_ProcCategoryItemTaxGroupRelationshipId](#BackingTable_ProcCategoryItemTaxGroupRelationshipId)||<a href="ProcurementProductCategoryItemSalesTaxGroupAssignmentEntity.md" target="_blank">Tax/ProcurementProductCategoryItemSalesTaxGroupAssignmentEntity</a>|

### <a href=#ProductCategoryHierarchyName name="ProductCategoryHierarchyName">ProductCategoryHierarchyName</a>

First included in: Tax/ProcurementProductCategoryItemSalesTaxGroupAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product category hierarchy name</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCategoryHierarchyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product category hierarchy name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductCategoryName name="ProductCategoryName">ProductCategoryName</a>

First included in: Tax/ProcurementProductCategoryItemSalesTaxGroupAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product category name</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product category name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSalesTaxGroupLegalEntityId name="ProductSalesTaxGroupLegalEntityId">ProductSalesTaxGroupLegalEntityId</a>

First included in: Tax/ProcurementProductCategoryItemSalesTaxGroupAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSalesTaxGroupLegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSalesTaxGroupId name="ProductSalesTaxGroupId">ProductSalesTaxGroupId</a>

First included in: Tax/ProcurementProductCategoryItemSalesTaxGroupAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSalesTaxGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPurchasingCalculatingWithholdingTax name="IsPurchasingCalculatingWithholdingTax">IsPurchasingCalculatingWithholdingTax</a>

First included in: Tax/ProcurementProductCategoryItemSalesTaxGroupAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPurchasingCalculatingWithholdingTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemWithholdingTaxPurchaseGroupCode name="ItemWithholdingTaxPurchaseGroupCode">ItemWithholdingTaxPurchaseGroupCode</a>

First included in: Tax/ProcurementProductCategoryItemSalesTaxGroupAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemWithholdingTaxPurchaseGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_ProcCategoryItemTaxGroupRelationshipId name="BackingTable_ProcCategoryItemTaxGroupRelationshipId">BackingTable_ProcCategoryItemTaxGroupRelationshipId</a>

First included in: Tax/ProcurementProductCategoryItemSalesTaxGroupAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ProcCategoryItemTaxGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Main/ProcCategoryItemTaxGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Main/ProcCategoryItemTaxGroup.cdm.json/ProcCategoryItemTaxGroup</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Main/ProcCategoryItemTaxGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
