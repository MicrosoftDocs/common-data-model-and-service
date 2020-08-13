---
title: CatVendorProductCandidatePurchasePriceEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Vendor catalog product purchase prices in ProcurementAndSourcing(CatVendorProductCandidatePurchasePriceEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor catalog product purchase prices</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CurrencyCode](#CurrencyCode)||<a href="CatVendorProductCandidatePurchasePriceEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity</a>|
|[Price](#Price)||<a href="CatVendorProductCandidatePurchasePriceEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity</a>|
|[UnitOfMeasureRecId](#UnitOfMeasureRecId)||<a href="CatVendorProductCandidatePurchasePriceEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity</a>|
|[UnitSymbol](#UnitSymbol)||<a href="CatVendorProductCandidatePurchasePriceEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity</a>|
|[ProductCandidateRecId](#ProductCandidateRecId)||<a href="CatVendorProductCandidatePurchasePriceEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity</a>|
|[CatalogMaintenanceRequestRecId](#CatalogMaintenanceRequestRecId)||<a href="CatVendorProductCandidatePurchasePriceEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity</a>|
|[ProductCandidateColorId](#ProductCandidateColorId)||<a href="CatVendorProductCandidatePurchasePriceEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity</a>|
|[ProductCandidateConfigurationId](#ProductCandidateConfigurationId)||<a href="CatVendorProductCandidatePurchasePriceEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity</a>|
|[ProductCandidateProductSubtype](#ProductCandidateProductSubtype)||<a href="CatVendorProductCandidatePurchasePriceEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity</a>|
|[ProductCandidateSizeId](#ProductCandidateSizeId)||<a href="CatVendorProductCandidatePurchasePriceEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity</a>|
|[ProductCandidateStyleId](#ProductCandidateStyleId)||<a href="CatVendorProductCandidatePurchasePriceEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity</a>|
|[ProductCandidateProductNumber](#ProductCandidateProductNumber)||<a href="CatVendorProductCandidatePurchasePriceEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity</a>|
|[VendorCatalogMaintenanceRequestUploadDateTime](#VendorCatalogMaintenanceRequestUploadDateTime)||<a href="CatVendorProductCandidatePurchasePriceEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity</a>|
|[Relationship_CatVendorProductCandidateEntityRelationshipId](#Relationship_CatVendorProductCandidateEntityRelationshipId)||<a href="CatVendorProductCandidatePurchasePriceEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity</a>|
|[BackingTable_CatVendorProductCandidatePriceRelationshipId](#BackingTable_CatVendorProductCandidatePriceRelationshipId)||<a href="CatVendorProductCandidatePurchasePriceEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity</a>|

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Price name="Price">Price</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Price attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitOfMeasureRecId name="UnitOfMeasureRecId">UnitOfMeasureRecId</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitOfMeasureRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitSymbol name="UnitSymbol">UnitSymbol</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductCandidateRecId name="ProductCandidateRecId">ProductCandidateRecId</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCandidateRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CatalogMaintenanceRequestRecId name="CatalogMaintenanceRequestRecId">CatalogMaintenanceRequestRecId</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatalogMaintenanceRequestRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductCandidateColorId name="ProductCandidateColorId">ProductCandidateColorId</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCandidateColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductCandidateConfigurationId name="ProductCandidateConfigurationId">ProductCandidateConfigurationId</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCandidateConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductCandidateProductSubtype name="ProductCandidateProductSubtype">ProductCandidateProductSubtype</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCandidateProductSubtype attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductCandidateSizeId name="ProductCandidateSizeId">ProductCandidateSizeId</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCandidateSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductCandidateStyleId name="ProductCandidateStyleId">ProductCandidateStyleId</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCandidateStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductCandidateProductNumber name="ProductCandidateProductNumber">ProductCandidateProductNumber</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCandidateProductNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorCatalogMaintenanceRequestUploadDateTime name="VendorCatalogMaintenanceRequestUploadDateTime">VendorCatalogMaintenanceRequestUploadDateTime</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorCatalogMaintenanceRequestUploadDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CatVendorProductCandidateEntityRelationshipId name="Relationship_CatVendorProductCandidateEntityRelationshipId">Relationship_CatVendorProductCandidateEntityRelationshipId</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CatVendorProductCandidateEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_CatVendorProductCandidatePriceRelationshipId name="BackingTable_CatVendorProductCandidatePriceRelationshipId">BackingTable_CatVendorProductCandidatePriceRelationshipId</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidatePurchasePriceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CatVendorProductCandidatePriceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Main/CatVendorProductCandidatePrice.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Main/CatVendorProductCandidatePrice.cdm.json/CatVendorProductCandidatePrice</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Main/CatVendorProductCandidatePrice.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
