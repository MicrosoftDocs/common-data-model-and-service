---
title: PurchDemandConsolidationInternalCatalogItemCategoryVendorEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Demand consolidation internal catalog item category vendors in ProcurementAndSourcing(PurchDemandConsolidationInternalCatalogItemCategoryVendorEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchDemandConsolidationInternalCatalogItemCategoryVendorEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Demand consolidation internal catalog item category vendors</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[VendorAccountNumber](#VendorAccountNumber)||<a href="PurchDemandConsolidationInternalCatalogItemCategoryVendorEntity.md" target="_blank">ProcurementAndSourcing/PurchDemandConsolidationInternalCatalogItemCategoryVendorEntity</a>|
|[VendorLegalEntityId](#VendorLegalEntityId)||<a href="PurchDemandConsolidationInternalCatalogItemCategoryVendorEntity.md" target="_blank">ProcurementAndSourcing/PurchDemandConsolidationInternalCatalogItemCategoryVendorEntity</a>|
|[ProcurementProductCategoryName](#ProcurementProductCategoryName)||<a href="PurchDemandConsolidationInternalCatalogItemCategoryVendorEntity.md" target="_blank">ProcurementAndSourcing/PurchDemandConsolidationInternalCatalogItemCategoryVendorEntity</a>|
|[PurchasingPolicyName](#PurchasingPolicyName)||<a href="PurchDemandConsolidationInternalCatalogItemCategoryVendorEntity.md" target="_blank">ProcurementAndSourcing/PurchDemandConsolidationInternalCatalogItemCategoryVendorEntity</a>|
|[PurchaseOrderCreationAndDemandConsolidationPolicyRuleValidFrom](#PurchaseOrderCreationAndDemandConsolidationPolicyRuleValidFrom)||<a href="PurchDemandConsolidationInternalCatalogItemCategoryVendorEntity.md" target="_blank">ProcurementAndSourcing/PurchDemandConsolidationInternalCatalogItemCategoryVendorEntity</a>|
|[ProcurementProductCategoryHierarchyName](#ProcurementProductCategoryHierarchyName)||<a href="PurchDemandConsolidationInternalCatalogItemCategoryVendorEntity.md" target="_blank">ProcurementAndSourcing/PurchDemandConsolidationInternalCatalogItemCategoryVendorEntity</a>|
|[BackingTable_PurchReqConsolidationHoldByVendorRuleRelationshipId](#BackingTable_PurchReqConsolidationHoldByVendorRuleRelationshipId)||<a href="PurchDemandConsolidationInternalCatalogItemCategoryVendorEntity.md" target="_blank">ProcurementAndSourcing/PurchDemandConsolidationInternalCatalogItemCategoryVendorEntity</a>|

### <a href=#VendorAccountNumber name="VendorAccountNumber">VendorAccountNumber</a>

First included in: ProcurementAndSourcing/PurchDemandConsolidationInternalCatalogItemCategoryVendorEntity (this entity)  

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

### <a href=#VendorLegalEntityId name="VendorLegalEntityId">VendorLegalEntityId</a>

First included in: ProcurementAndSourcing/PurchDemandConsolidationInternalCatalogItemCategoryVendorEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorLegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcurementProductCategoryName name="ProcurementProductCategoryName">ProcurementProductCategoryName</a>

First included in: ProcurementAndSourcing/PurchDemandConsolidationInternalCatalogItemCategoryVendorEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementProductCategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchasingPolicyName name="PurchasingPolicyName">PurchasingPolicyName</a>

First included in: ProcurementAndSourcing/PurchDemandConsolidationInternalCatalogItemCategoryVendorEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasingPolicyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrderCreationAndDemandConsolidationPolicyRuleValidFrom name="PurchaseOrderCreationAndDemandConsolidationPolicyRuleValidFrom">PurchaseOrderCreationAndDemandConsolidationPolicyRuleValidFrom</a>

First included in: ProcurementAndSourcing/PurchDemandConsolidationInternalCatalogItemCategoryVendorEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderCreationAndDemandConsolidationPolicyRuleValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcurementProductCategoryHierarchyName name="ProcurementProductCategoryHierarchyName">ProcurementProductCategoryHierarchyName</a>

First included in: ProcurementAndSourcing/PurchDemandConsolidationInternalCatalogItemCategoryVendorEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementProductCategoryHierarchyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PurchReqConsolidationHoldByVendorRuleRelationshipId name="BackingTable_PurchReqConsolidationHoldByVendorRuleRelationshipId">BackingTable_PurchReqConsolidationHoldByVendorRuleRelationshipId</a>

First included in: ProcurementAndSourcing/PurchDemandConsolidationInternalCatalogItemCategoryVendorEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PurchReqConsolidationHoldByVendorRuleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Main/PurchReqConsolidationHoldByVendorRule.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Main/PurchReqConsolidationHoldByVendorRule.cdm.json/PurchReqConsolidationHoldByVendorRule</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Main/PurchReqConsolidationHoldByVendorRule.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
