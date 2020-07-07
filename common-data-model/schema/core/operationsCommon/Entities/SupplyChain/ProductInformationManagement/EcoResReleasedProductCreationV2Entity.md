---
title: EcoResReleasedProductCreationV2Entity in ProductInformationManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Released product creation V2 in ProductInformationManagement

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/EcoResReleasedProductCreationV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Released product creation V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ItemNumber](#ItemNumber)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[ProductType](#ProductType)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[ProductSubType](#ProductSubType)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[ServiceType](#ServiceType)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[VariantConfigurationTechnology](#VariantConfigurationTechnology)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[ProductNumber](#ProductNumber)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[ProductName](#ProductName)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[ProductSearchName](#ProductSearchName)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[ProductDescription](#ProductDescription)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[SearchName](#SearchName)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[ProductGroupId](#ProductGroupId)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[ItemModelGroupId](#ItemModelGroupId)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[ProductDimensionGroupName](#ProductDimensionGroupName)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[StorageDimensionGroupName](#StorageDimensionGroupName)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[TrackingDimensionGroupName](#TrackingDimensionGroupName)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[IsCatchWeightProduct](#IsCatchWeightProduct)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[IsProductKit](#IsProductKit)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[RetailProductCategoryname](#RetailProductCategoryname)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[InventoryReservationHierarchyName](#InventoryReservationHierarchyName)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[BOMUnitSymbol](#BOMUnitSymbol)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[InventoryUnitSymbol](#InventoryUnitSymbol)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[SalesUnitSymbol](#SalesUnitSymbol)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[PurchaseUnitSymbol](#PurchaseUnitSymbol)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[SalesSalesTaxItemGroupCode](#SalesSalesTaxItemGroupCode)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[PurchaseSalesTaxItemGroupCode](#PurchaseSalesTaxItemGroupCode)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[WarrantyDurationTime](#WarrantyDurationTime)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[WarrantyDurationTimeUnit](#WarrantyDurationTimeUnit)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[WarrantablePriceRangeBaseType](#WarrantablePriceRangeBaseType)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[LowerWarrantablePriceRangeLimit](#LowerWarrantablePriceRangeLimit)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[UpperWarrantablePriceRangeLimit](#UpperWarrantablePriceRangeLimit)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[BackingTable_EcoResReleasedProductV2EntityRelationshipId](#BackingTable_EcoResReleasedProductV2EntityRelationshipId)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="EcoResReleasedProductCreationV2Entity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductCreationV2Entity</a>|

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductType name="ProductType">ProductType</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSubType name="ProductSubType">ProductSubType</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSubType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceType name="ServiceType">ServiceType</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VariantConfigurationTechnology name="VariantConfigurationTechnology">VariantConfigurationTechnology</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VariantConfigurationTechnology attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductNumber name="ProductNumber">ProductNumber</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductName name="ProductName">ProductName</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSearchName name="ProductSearchName">ProductSearchName</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSearchName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductDescription name="ProductDescription">ProductDescription</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SearchName name="SearchName">SearchName</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SearchName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductGroupId name="ProductGroupId">ProductGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemModelGroupId name="ItemModelGroupId">ItemModelGroupId</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemModelGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductDimensionGroupName name="ProductDimensionGroupName">ProductDimensionGroupName</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductDimensionGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StorageDimensionGroupName name="StorageDimensionGroupName">StorageDimensionGroupName</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StorageDimensionGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TrackingDimensionGroupName name="TrackingDimensionGroupName">TrackingDimensionGroupName</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrackingDimensionGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCatchWeightProduct name="IsCatchWeightProduct">IsCatchWeightProduct</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCatchWeightProduct attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductKit name="IsProductKit">IsProductKit</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductKit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailProductCategoryname name="RetailProductCategoryname">RetailProductCategoryname</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailProductCategoryname attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryReservationHierarchyName name="InventoryReservationHierarchyName">InventoryReservationHierarchyName</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryReservationHierarchyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOMUnitSymbol name="BOMUnitSymbol">BOMUnitSymbol</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOMUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryUnitSymbol name="InventoryUnitSymbol">InventoryUnitSymbol</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesUnitSymbol name="SalesUnitSymbol">SalesUnitSymbol</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseUnitSymbol name="PurchaseUnitSymbol">PurchaseUnitSymbol</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesSalesTaxItemGroupCode name="SalesSalesTaxItemGroupCode">SalesSalesTaxItemGroupCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesSalesTaxItemGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseSalesTaxItemGroupCode name="PurchaseSalesTaxItemGroupCode">PurchaseSalesTaxItemGroupCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseSalesTaxItemGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarrantyDurationTime name="WarrantyDurationTime">WarrantyDurationTime</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarrantyDurationTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarrantyDurationTimeUnit name="WarrantyDurationTimeUnit">WarrantyDurationTimeUnit</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarrantyDurationTimeUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarrantablePriceRangeBaseType name="WarrantablePriceRangeBaseType">WarrantablePriceRangeBaseType</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarrantablePriceRangeBaseType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LowerWarrantablePriceRangeLimit name="LowerWarrantablePriceRangeLimit">LowerWarrantablePriceRangeLimit</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LowerWarrantablePriceRangeLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UpperWarrantablePriceRangeLimit name="UpperWarrantablePriceRangeLimit">UpperWarrantablePriceRangeLimit</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpperWarrantablePriceRangeLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_EcoResReleasedProductV2EntityRelationshipId name="BackingTable_EcoResReleasedProductV2EntityRelationshipId">BackingTable_EcoResReleasedProductV2EntityRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_EcoResReleasedProductV2EntityRelationshipId attribute are listed below.</summary>

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

First included in: ProductInformationManagement/EcoResReleasedProductCreationV2Entity (this entity)  

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
