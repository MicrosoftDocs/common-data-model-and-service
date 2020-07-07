---
title: ProcurementProductCategoryVendorEvaluationCriterionGroupAssignmentEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Procurement product category vendor evaluation criterion group assignments in ProcurementAndSourcing

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/ProcurementProductCategoryVendorEvaluationCriterionGroupAssignmentEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Procurement product category vendor evaluation criterion group assignments</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ProductCategoryHierarchyName](#ProductCategoryHierarchyName)||<a href="ProcurementProductCategoryVendorEvaluationCriterionGroupAssignmentEntity.md" target="_blank">ProcurementAndSourcing/ProcurementProductCategoryVendorEvaluationCriterionGroupAssignmentEntity</a>|
|[ProductCategoryName](#ProductCategoryName)||<a href="ProcurementProductCategoryVendorEvaluationCriterionGroupAssignmentEntity.md" target="_blank">ProcurementAndSourcing/ProcurementProductCategoryVendorEvaluationCriterionGroupAssignmentEntity</a>|
|[VendorEvaluationCriterionGroupName](#VendorEvaluationCriterionGroupName)||<a href="ProcurementProductCategoryVendorEvaluationCriterionGroupAssignmentEntity.md" target="_blank">ProcurementAndSourcing/ProcurementProductCategoryVendorEvaluationCriterionGroupAssignmentEntity</a>|
|[BackingTable_VendReviewCategoryCriterionGroupRelationshipId](#BackingTable_VendReviewCategoryCriterionGroupRelationshipId)||<a href="ProcurementProductCategoryVendorEvaluationCriterionGroupAssignmentEntity.md" target="_blank">ProcurementAndSourcing/ProcurementProductCategoryVendorEvaluationCriterionGroupAssignmentEntity</a>|

### <a href=#ProductCategoryHierarchyName name="ProductCategoryHierarchyName">ProductCategoryHierarchyName</a>

First included in: ProcurementAndSourcing/ProcurementProductCategoryVendorEvaluationCriterionGroupAssignmentEntity (this entity)  

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

First included in: ProcurementAndSourcing/ProcurementProductCategoryVendorEvaluationCriterionGroupAssignmentEntity (this entity)  

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

### <a href=#VendorEvaluationCriterionGroupName name="VendorEvaluationCriterionGroupName">VendorEvaluationCriterionGroupName</a>

First included in: ProcurementAndSourcing/ProcurementProductCategoryVendorEvaluationCriterionGroupAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor evaluation criterion group name</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorEvaluationCriterionGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor evaluation criterion group name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_VendReviewCategoryCriterionGroupRelationshipId name="BackingTable_VendReviewCategoryCriterionGroupRelationshipId">BackingTable_VendReviewCategoryCriterionGroupRelationshipId</a>

First included in: ProcurementAndSourcing/ProcurementProductCategoryVendorEvaluationCriterionGroupAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_VendReviewCategoryCriterionGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Main/VendReviewCategoryCriterionGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Main/VendReviewCategoryCriterionGroup.cdm.json/VendReviewCategoryCriterionGroup</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Main/VendReviewCategoryCriterionGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
