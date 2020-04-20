---
title: VendorEvaluationCriterionEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# VendorEvaluationCriterionEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/VendorEvaluationCriterionEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CriterionGroupRecId](#CriterionGroupRecId)||<a href="VendorEvaluationCriterionEntity.md" target="_blank">ProcurementAndSourcing/VendorEvaluationCriterionEntity</a>|
|[CriterionName](#CriterionName)||<a href="VendorEvaluationCriterionEntity.md" target="_blank">ProcurementAndSourcing/VendorEvaluationCriterionEntity</a>|
|[VendorEvaluationCriterionGroupName](#VendorEvaluationCriterionGroupName)||<a href="VendorEvaluationCriterionEntity.md" target="_blank">ProcurementAndSourcing/VendorEvaluationCriterionEntity</a>|
|[BackingTable_VendReviewCriterionRelationshipId](#BackingTable_VendReviewCriterionRelationshipId)||<a href="VendorEvaluationCriterionEntity.md" target="_blank">ProcurementAndSourcing/VendorEvaluationCriterionEntity</a>|

### <a href=#CriterionGroupRecId name="CriterionGroupRecId">CriterionGroupRecId</a>

First included in: ProcurementAndSourcing/VendorEvaluationCriterionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CriterionGroupRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CriterionName name="CriterionName">CriterionName</a>

First included in: ProcurementAndSourcing/VendorEvaluationCriterionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CriterionName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorEvaluationCriterionGroupName name="VendorEvaluationCriterionGroupName">VendorEvaluationCriterionGroupName</a>

First included in: ProcurementAndSourcing/VendorEvaluationCriterionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorEvaluationCriterionGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_VendReviewCriterionRelationshipId name="BackingTable_VendReviewCriterionRelationshipId">BackingTable_VendReviewCriterionRelationshipId</a>

First included in: ProcurementAndSourcing/VendorEvaluationCriterionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_VendReviewCriterionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Main/VendReviewCriterion.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Main/VendReviewCriterion.cdm.json/VendReviewCriterion</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Main/VendReviewCriterion.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
