---
title: TaxSalesTaxHierarchiesEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Sales tax hierarchy

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Tax/TaxSalesTaxHierarchiesEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax hierarchy</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IsSetoffable](#IsSetoffable)||<a href="TaxSalesTaxHierarchiesEntity.md" target="_blank">Tax/TaxSalesTaxHierarchiesEntity</a>|
|[HierarchyName](#HierarchyName)||<a href="TaxSalesTaxHierarchiesEntity.md" target="_blank">Tax/TaxSalesTaxHierarchiesEntity</a>|
|[ClassId](#ClassId)||<a href="TaxSalesTaxHierarchiesEntity.md" target="_blank">Tax/TaxSalesTaxHierarchiesEntity</a>|
|[HierarchyVersionDescription](#HierarchyVersionDescription)||<a href="TaxSalesTaxHierarchiesEntity.md" target="_blank">Tax/TaxSalesTaxHierarchiesEntity</a>|
|[IsActiveVersion](#IsActiveVersion)||<a href="TaxSalesTaxHierarchiesEntity.md" target="_blank">Tax/TaxSalesTaxHierarchiesEntity</a>|
|[HierarchyVersion](#HierarchyVersion)||<a href="TaxSalesTaxHierarchiesEntity.md" target="_blank">Tax/TaxSalesTaxHierarchiesEntity</a>|
|[HierarchyStructure](#HierarchyStructure)||<a href="TaxSalesTaxHierarchiesEntity.md" target="_blank">Tax/TaxSalesTaxHierarchiesEntity</a>|
|[BackingTable_TaxReportHierarchy_INRelationshipId](#BackingTable_TaxReportHierarchy_INRelationshipId)||<a href="TaxSalesTaxHierarchiesEntity.md" target="_blank">Tax/TaxSalesTaxHierarchiesEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TaxSalesTaxHierarchiesEntity.md" target="_blank">Tax/TaxSalesTaxHierarchiesEntity</a>|

### <a href=#IsSetoffable name="IsSetoffable">IsSetoffable</a>

First included in: Tax/TaxSalesTaxHierarchiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSetoffable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyName name="HierarchyName">HierarchyName</a>

First included in: Tax/TaxSalesTaxHierarchiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClassId name="ClassId">ClassId</a>

First included in: Tax/TaxSalesTaxHierarchiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClassId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyVersionDescription name="HierarchyVersionDescription">HierarchyVersionDescription</a>

First included in: Tax/TaxSalesTaxHierarchiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyVersionDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActiveVersion name="IsActiveVersion">IsActiveVersion</a>

First included in: Tax/TaxSalesTaxHierarchiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActiveVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyVersion name="HierarchyVersion">HierarchyVersion</a>

First included in: Tax/TaxSalesTaxHierarchiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyStructure name="HierarchyStructure">HierarchyStructure</a>

First included in: Tax/TaxSalesTaxHierarchiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyStructure attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TaxReportHierarchy_INRelationshipId name="BackingTable_TaxReportHierarchy_INRelationshipId">BackingTable_TaxReportHierarchy_INRelationshipId</a>

First included in: Tax/TaxSalesTaxHierarchiesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TaxReportHierarchy_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Tax/Group/TaxReportHierarchy_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportHierarchy_IN.cdm.json/TaxReportHierarchy_IN</a></td><td><a href="../../../Tables/Finance/Tax/Group/TaxReportHierarchy_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Tax/TaxSalesTaxHierarchiesEntity (this entity)  

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
