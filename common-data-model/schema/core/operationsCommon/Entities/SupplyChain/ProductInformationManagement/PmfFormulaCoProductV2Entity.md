---
title: PmfFormulaCoProductV2Entity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Formula co-products V2

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/PmfFormulaCoProductV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Formula co-products V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[FormulaId](#FormulaId)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[Quantity](#Quantity)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[QuantityDenominator](#QuantityDenominator)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[ItemNumber](#ItemNumber)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[LineNumber](#LineNumber)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[CatchWeightQuantity](#CatchWeightQuantity)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[RoundingUpMethod](#RoundingUpMethod)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[QuantityRoundingUpMultiples](#QuantityRoundingUpMultiples)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[ConsumptionSiteId](#ConsumptionSiteId)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[ConsumptionWarehouseId](#ConsumptionWarehouseId)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[ProductColorId](#ProductColorId)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[IsVersionActive](#IsVersionActive)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[VersionManufacturedItemNumber](#VersionManufacturedItemNumber)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[VersionValidFromDate](#VersionValidFromDate)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[VersionFromQuantity](#VersionFromQuantity)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[VersionProductConfigurationId](#VersionProductConfigurationId)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[VersionProductColorId](#VersionProductColorId)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[VersionProductionSiteId](#VersionProductionSiteId)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[VersionProductSizeId](#VersionProductSizeId)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[VersionProductStyleId](#VersionProductStyleId)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[VersionProductVersionId](#VersionProductVersionId)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[VersionRecordId](#VersionRecordId)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[CoProductFormulaId](#CoProductFormulaId)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[CostAllocationMethod](#CostAllocationMethod)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[CostAllocationPercentage](#CostAllocationPercentage)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[Relationship_FormulaVersionRelationshipId](#Relationship_FormulaVersionRelationshipId)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[BackingTable_PmfFormulaCoByRelationshipId](#BackingTable_PmfFormulaCoByRelationshipId)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PmfFormulaCoProductV2Entity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductV2Entity</a>|

### <a href=#FormulaId name="FormulaId">FormulaId</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormulaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuantityDenominator name="QuantityDenominator">QuantityDenominator</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuantityDenominator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

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

### <a href=#CatchWeightQuantity name="CatchWeightQuantity">CatchWeightQuantity</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoundingUpMethod name="RoundingUpMethod">RoundingUpMethod</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundingUpMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuantityRoundingUpMultiples name="QuantityRoundingUpMultiples">QuantityRoundingUpMultiples</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuantityRoundingUpMultiples attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumptionSiteId name="ConsumptionSiteId">ConsumptionSiteId</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Consumption site</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Consumption site</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumptionWarehouseId name="ConsumptionWarehouseId">ConsumptionWarehouseId</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Consumption warehouse</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Consumption warehouse</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVersionId name="ProductVersionId">ProductVersionId</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsVersionActive name="IsVersionActive">IsVersionActive</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsVersionActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionManufacturedItemNumber name="VersionManufacturedItemNumber">VersionManufacturedItemNumber</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionManufacturedItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionValidFromDate name="VersionValidFromDate">VersionValidFromDate</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionValidFromDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionFromQuantity name="VersionFromQuantity">VersionFromQuantity</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionFromQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionProductConfigurationId name="VersionProductConfigurationId">VersionProductConfigurationId</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version product configuration</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version product configuration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionProductColorId name="VersionProductColorId">VersionProductColorId</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version product color</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version product color</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionProductionSiteId name="VersionProductionSiteId">VersionProductionSiteId</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionProductionSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionProductSizeId name="VersionProductSizeId">VersionProductSizeId</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version product size</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version product size</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionProductStyleId name="VersionProductStyleId">VersionProductStyleId</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version product style</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version product style</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionProductVersionId name="VersionProductVersionId">VersionProductVersionId</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version product version</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionProductVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version product version</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionRecordId name="VersionRecordId">VersionRecordId</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CoProductFormulaId name="CoProductFormulaId">CoProductFormulaId</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CoProductFormulaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostAllocationMethod name="CostAllocationMethod">CostAllocationMethod</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostAllocationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostAllocationPercentage name="CostAllocationPercentage">CostAllocationPercentage</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostAllocationPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FormulaVersionRelationshipId name="Relationship_FormulaVersionRelationshipId">Relationship_FormulaVersionRelationshipId</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FormulaVersionRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_PmfFormulaCoByRelationshipId name="BackingTable_PmfFormulaCoByRelationshipId">BackingTable_PmfFormulaCoByRelationshipId</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PmfFormulaCoByRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/Main/PmfFormulaCoBy.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Main/PmfFormulaCoBy.cdm.json/PmfFormulaCoBy</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/Main/PmfFormulaCoBy.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductInformationManagement/PmfFormulaCoProductV2Entity (this entity)  

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
