---
title: EcoResProductDimensionGroupEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/30/2020
ms.author: nebanfic
---

# Product dimension groups

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/EcoResProductDimensionGroupEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product dimension groups</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[GroupName](#GroupName)||<a href="EcoResProductDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResProductDimensionGroupEntity</a>|
|[GroupDescription](#GroupDescription)||<a href="EcoResProductDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResProductDimensionGroupEntity</a>|
|[IsProductConfigurationActive](#IsProductConfigurationActive)||<a href="EcoResProductDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResProductDimensionGroupEntity</a>|
|[WillPurchasePriceSearchUseProductConfiguration](#WillPurchasePriceSearchUseProductConfiguration)||<a href="EcoResProductDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResProductDimensionGroupEntity</a>|
|[WillSalesPriceSearchUseProductConfiguration](#WillSalesPriceSearchUseProductConfiguration)||<a href="EcoResProductDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResProductDimensionGroupEntity</a>|
|[ProductConfigurationDisplayOrder](#ProductConfigurationDisplayOrder)||<a href="EcoResProductDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResProductDimensionGroupEntity</a>|
|[IsProductSizeActive](#IsProductSizeActive)||<a href="EcoResProductDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResProductDimensionGroupEntity</a>|
|[WillPurchasePriceSearchUseProductSize](#WillPurchasePriceSearchUseProductSize)||<a href="EcoResProductDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResProductDimensionGroupEntity</a>|
|[WillSalesPriceSearchUseProductSize](#WillSalesPriceSearchUseProductSize)||<a href="EcoResProductDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResProductDimensionGroupEntity</a>|
|[ProductSizeDisplayOrder](#ProductSizeDisplayOrder)||<a href="EcoResProductDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResProductDimensionGroupEntity</a>|
|[IsProductColorActive](#IsProductColorActive)||<a href="EcoResProductDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResProductDimensionGroupEntity</a>|
|[WillPurchasePriceSearchUseProductColor](#WillPurchasePriceSearchUseProductColor)||<a href="EcoResProductDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResProductDimensionGroupEntity</a>|
|[WillSalesPriceSearchUseProductColor](#WillSalesPriceSearchUseProductColor)||<a href="EcoResProductDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResProductDimensionGroupEntity</a>|
|[ProductColorDisplayOrder](#ProductColorDisplayOrder)||<a href="EcoResProductDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResProductDimensionGroupEntity</a>|
|[IsProductStyleActive](#IsProductStyleActive)||<a href="EcoResProductDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResProductDimensionGroupEntity</a>|
|[IsProductVersionActive](#IsProductVersionActive)||<a href="EcoResProductDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResProductDimensionGroupEntity</a>|
|[WillPurchasePriceSearchUseProductStyle](#WillPurchasePriceSearchUseProductStyle)||<a href="EcoResProductDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResProductDimensionGroupEntity</a>|
|[WillPurchasePriceSearchUseProductVersion](#WillPurchasePriceSearchUseProductVersion)||<a href="EcoResProductDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResProductDimensionGroupEntity</a>|
|[WillSalesPriceSearchUseProductStyle](#WillSalesPriceSearchUseProductStyle)||<a href="EcoResProductDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResProductDimensionGroupEntity</a>|
|[WillSalesPriceSearchUseProductVersion](#WillSalesPriceSearchUseProductVersion)||<a href="EcoResProductDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResProductDimensionGroupEntity</a>|
|[ProductStyleDisplayOrder](#ProductStyleDisplayOrder)||<a href="EcoResProductDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResProductDimensionGroupEntity</a>|
|[ProductVersionDisplayOrder](#ProductVersionDisplayOrder)||<a href="EcoResProductDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResProductDimensionGroupEntity</a>|
|[ProductVariantNomenclatureName](#ProductVariantNomenclatureName)||<a href="EcoResProductDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResProductDimensionGroupEntity</a>|
|[ProductVariantNomenclatureRecId](#ProductVariantNomenclatureRecId)||<a href="EcoResProductDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResProductDimensionGroupEntity</a>|
|[BackingTable_EcoResProductDimensionGroupRelationshipId](#BackingTable_EcoResProductDimensionGroupRelationshipId)||<a href="EcoResProductDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResProductDimensionGroupEntity</a>|

### <a href=#GroupName name="GroupName">GroupName</a>

First included in: ProductInformationManagement/EcoResProductDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupDescription name="GroupDescription">GroupDescription</a>

First included in: ProductInformationManagement/EcoResProductDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductConfigurationActive name="IsProductConfigurationActive">IsProductConfigurationActive</a>

First included in: ProductInformationManagement/EcoResProductDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Configuration active</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductConfigurationActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Configuration active</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillPurchasePriceSearchUseProductConfiguration name="WillPurchasePriceSearchUseProductConfiguration">WillPurchasePriceSearchUseProductConfiguration</a>

First included in: ProductInformationManagement/EcoResProductDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use configuration for purchase price</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillPurchasePriceSearchUseProductConfiguration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use configuration for purchase price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSalesPriceSearchUseProductConfiguration name="WillSalesPriceSearchUseProductConfiguration">WillSalesPriceSearchUseProductConfiguration</a>

First included in: ProductInformationManagement/EcoResProductDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use configuration for sales price</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSalesPriceSearchUseProductConfiguration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use configuration for sales price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationDisplayOrder name="ProductConfigurationDisplayOrder">ProductConfigurationDisplayOrder</a>

First included in: ProductInformationManagement/EcoResProductDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Display order for dimension group configuration</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductConfigurationDisplayOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Display order for dimension group configuration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductSizeActive name="IsProductSizeActive">IsProductSizeActive</a>

First included in: ProductInformationManagement/EcoResProductDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Size active</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductSizeActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Size active</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillPurchasePriceSearchUseProductSize name="WillPurchasePriceSearchUseProductSize">WillPurchasePriceSearchUseProductSize</a>

First included in: ProductInformationManagement/EcoResProductDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use size for purchase price</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillPurchasePriceSearchUseProductSize attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use size for purchase price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSalesPriceSearchUseProductSize name="WillSalesPriceSearchUseProductSize">WillSalesPriceSearchUseProductSize</a>

First included in: ProductInformationManagement/EcoResProductDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use size for sales price</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSalesPriceSearchUseProductSize attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use size for sales price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeDisplayOrder name="ProductSizeDisplayOrder">ProductSizeDisplayOrder</a>

First included in: ProductInformationManagement/EcoResProductDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Display order for dimension group size</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSizeDisplayOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Display order for dimension group size</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductColorActive name="IsProductColorActive">IsProductColorActive</a>

First included in: ProductInformationManagement/EcoResProductDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Color active</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductColorActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Color active</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillPurchasePriceSearchUseProductColor name="WillPurchasePriceSearchUseProductColor">WillPurchasePriceSearchUseProductColor</a>

First included in: ProductInformationManagement/EcoResProductDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use color for purchase price</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillPurchasePriceSearchUseProductColor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use color for purchase price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSalesPriceSearchUseProductColor name="WillSalesPriceSearchUseProductColor">WillSalesPriceSearchUseProductColor</a>

First included in: ProductInformationManagement/EcoResProductDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use color for sales price</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSalesPriceSearchUseProductColor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use color for sales price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductColorDisplayOrder name="ProductColorDisplayOrder">ProductColorDisplayOrder</a>

First included in: ProductInformationManagement/EcoResProductDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Display order for dimension group color</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductColorDisplayOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Display order for dimension group color</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductStyleActive name="IsProductStyleActive">IsProductStyleActive</a>

First included in: ProductInformationManagement/EcoResProductDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Style active</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductStyleActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Style active</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductVersionActive name="IsProductVersionActive">IsProductVersionActive</a>

First included in: ProductInformationManagement/EcoResProductDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version active</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductVersionActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version active</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillPurchasePriceSearchUseProductStyle name="WillPurchasePriceSearchUseProductStyle">WillPurchasePriceSearchUseProductStyle</a>

First included in: ProductInformationManagement/EcoResProductDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use style for purchase price</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillPurchasePriceSearchUseProductStyle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use style for purchase price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillPurchasePriceSearchUseProductVersion name="WillPurchasePriceSearchUseProductVersion">WillPurchasePriceSearchUseProductVersion</a>

First included in: ProductInformationManagement/EcoResProductDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use version for purchase price</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillPurchasePriceSearchUseProductVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use version for purchase price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSalesPriceSearchUseProductStyle name="WillSalesPriceSearchUseProductStyle">WillSalesPriceSearchUseProductStyle</a>

First included in: ProductInformationManagement/EcoResProductDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use style for sales price</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSalesPriceSearchUseProductStyle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use style for sales price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSalesPriceSearchUseProductVersion name="WillSalesPriceSearchUseProductVersion">WillSalesPriceSearchUseProductVersion</a>

First included in: ProductInformationManagement/EcoResProductDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use version for sales price</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSalesPriceSearchUseProductVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use version for sales price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductStyleDisplayOrder name="ProductStyleDisplayOrder">ProductStyleDisplayOrder</a>

First included in: ProductInformationManagement/EcoResProductDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Display order for dimension group style</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductStyleDisplayOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Display order for dimension group style</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVersionDisplayOrder name="ProductVersionDisplayOrder">ProductVersionDisplayOrder</a>

First included in: ProductInformationManagement/EcoResProductDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>@Retail:EcoResProductDimensionGroupVersionDisplayOrder</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVersionDisplayOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>@Retail:EcoResProductDimensionGroupVersionDisplayOrder</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVariantNomenclatureName name="ProductVariantNomenclatureName">ProductVariantNomenclatureName</a>

First included in: ProductInformationManagement/EcoResProductDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Nomenclature Name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVariantNomenclatureName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Nomenclature Name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVariantNomenclatureRecId name="ProductVariantNomenclatureRecId">ProductVariantNomenclatureRecId</a>

First included in: ProductInformationManagement/EcoResProductDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVariantNomenclatureRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_EcoResProductDimensionGroupRelationshipId name="BackingTable_EcoResProductDimensionGroupRelationshipId">BackingTable_EcoResProductDimensionGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_EcoResProductDimensionGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Group/EcoResProductDimensionGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Group/EcoResProductDimensionGroup.cdm.json/EcoResProductDimensionGroup</a></td><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Group/EcoResProductDimensionGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
