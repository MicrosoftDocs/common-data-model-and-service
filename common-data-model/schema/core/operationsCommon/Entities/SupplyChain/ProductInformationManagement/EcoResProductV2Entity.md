---
title: EcoResProductV2Entity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Products V2

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/EcoResProductV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Products V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ProductType](#ProductType)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[ProductSubType](#ProductSubType)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[ServiceType](#ServiceType)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[ProductNumber](#ProductNumber)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[ProductName](#ProductName)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[ProductSearchName](#ProductSearchName)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[ProductDescription](#ProductDescription)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[IsCatchWeightProduct](#IsCatchWeightProduct)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[ProductDimensionGroupName](#ProductDimensionGroupName)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[ProductDimensionGroupRecId](#ProductDimensionGroupRecId)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[StorageDimensionGroupName](#StorageDimensionGroupName)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[StorageDimensionGroupRecId](#StorageDimensionGroupRecId)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[TrackingDimensionGroupName](#TrackingDimensionGroupName)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[TrackingDimensionGroupRecId](#TrackingDimensionGroupRecId)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[VariantConfigurationTechnology](#VariantConfigurationTechnology)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[AreIdenticalConfigurationsAllowed](#AreIdenticalConfigurationsAllowed)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[IsAutomaticVariantGenerationEnabled](#IsAutomaticVariantGenerationEnabled)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[IsProductVariantUnitConversionEnabled](#IsProductVariantUnitConversionEnabled)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[RetailProductCategoryName](#RetailProductCategoryName)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[RetailCategoryRecId](#RetailCategoryRecId)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[ProductColorGroupId](#ProductColorGroupId)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[ProductSizeGroupId](#ProductSizeGroupId)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[ProductStyleGroupId](#ProductStyleGroupId)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[IsProductKit](#IsProductKit)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[STCCCode](#STCCCode)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[HarmonizedSystemCode](#HarmonizedSystemCode)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[NMFCCode](#NMFCCode)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[ProductVariantNameNomenclatureName](#ProductVariantNameNomenclatureName)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[ProductVariantNumberNomenclatureName](#ProductVariantNumberNomenclatureName)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[WarrantyDurationTime](#WarrantyDurationTime)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[WarrantyDurationTimeUnit](#WarrantyDurationTimeUnit)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[EngChgProductTypeName](#EngChgProductTypeName)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[EngChgProductOwnerId](#EngChgProductOwnerId)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[Relationship_ProductColorGroupRelationshipId](#Relationship_ProductColorGroupRelationshipId)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[Relationship_ProductDimensionGroupRelationshipId](#Relationship_ProductDimensionGroupRelationshipId)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[Relationship_StorageDimensionGroupRelationshipId](#Relationship_StorageDimensionGroupRelationshipId)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[Relationship_TrackingDimensionGroupRelationshipId](#Relationship_TrackingDimensionGroupRelationshipId)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[Relationship_ProductSizeGroupRelationshipId](#Relationship_ProductSizeGroupRelationshipId)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[Relationship_ProductStyleGroupRelationshipId](#Relationship_ProductStyleGroupRelationshipId)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[Relationship_StandardTransportationCommodityCodeRelationshipId](#Relationship_StandardTransportationCommodityCodeRelationshipId)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[Relationship_ProductHarmonizedTariffCodeRelationshipId](#Relationship_ProductHarmonizedTariffCodeRelationshipId)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[Relationship_USNationalMotorFreightClassificationCodeRelationshipId](#Relationship_USNationalMotorFreightClassificationCodeRelationshipId)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|
|[BackingTable_EcoResProductRelationshipId](#BackingTable_EcoResProductRelationshipId)||<a href="EcoResProductV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductV2Entity</a>|

### <a href=#ProductType name="ProductType">ProductType</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSubType name="ProductSubType">ProductSubType</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSubType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceType name="ServiceType">ServiceType</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductNumber name="ProductNumber">ProductNumber</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductName name="ProductName">ProductName</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSearchName name="ProductSearchName">ProductSearchName</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSearchName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductDescription name="ProductDescription">ProductDescription</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCatchWeightProduct name="IsCatchWeightProduct">IsCatchWeightProduct</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Catch weight product</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCatchWeightProduct attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Catch weight product</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductDimensionGroupName name="ProductDimensionGroupName">ProductDimensionGroupName</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product dimension group</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductDimensionGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product dimension group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductDimensionGroupRecId name="ProductDimensionGroupRecId">ProductDimensionGroupRecId</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductDimensionGroupRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StorageDimensionGroupName name="StorageDimensionGroupName">StorageDimensionGroupName</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Storage dimension group</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StorageDimensionGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Storage dimension group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StorageDimensionGroupRecId name="StorageDimensionGroupRecId">StorageDimensionGroupRecId</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StorageDimensionGroupRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TrackingDimensionGroupName name="TrackingDimensionGroupName">TrackingDimensionGroupName</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tracking dimension group</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrackingDimensionGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tracking dimension group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TrackingDimensionGroupRecId name="TrackingDimensionGroupRecId">TrackingDimensionGroupRecId</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrackingDimensionGroupRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VariantConfigurationTechnology name="VariantConfigurationTechnology">VariantConfigurationTechnology</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VariantConfigurationTechnology attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreIdenticalConfigurationsAllowed name="AreIdenticalConfigurationsAllowed">AreIdenticalConfigurationsAllowed</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreIdenticalConfigurationsAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAutomaticVariantGenerationEnabled name="IsAutomaticVariantGenerationEnabled">IsAutomaticVariantGenerationEnabled</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAutomaticVariantGenerationEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductVariantUnitConversionEnabled name="IsProductVariantUnitConversionEnabled">IsProductVariantUnitConversionEnabled</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable product variant unit conversions</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductVariantUnitConversionEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Enable product variant unit conversions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailProductCategoryName name="RetailProductCategoryName">RetailProductCategoryName</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Retail category</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailProductCategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Retail category</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailCategoryRecId name="RetailCategoryRecId">RetailCategoryRecId</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailCategoryRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductColorGroupId name="ProductColorGroupId">ProductColorGroupId</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductColorGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeGroupId name="ProductSizeGroupId">ProductSizeGroupId</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSizeGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductStyleGroupId name="ProductStyleGroupId">ProductStyleGroupId</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductStyleGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductKit name="IsProductKit">IsProductKit</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product kit</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductKit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product kit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#STCCCode name="STCCCode">STCCCode</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the STCCCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HarmonizedSystemCode name="HarmonizedSystemCode">HarmonizedSystemCode</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HarmonizedSystemCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NMFCCode name="NMFCCode">NMFCCode</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NMFCCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVariantNameNomenclatureName name="ProductVariantNameNomenclatureName">ProductVariantNameNomenclatureName</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product variant name nomenclature</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVariantNameNomenclatureName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product variant name nomenclature</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVariantNumberNomenclatureName name="ProductVariantNumberNomenclatureName">ProductVariantNumberNomenclatureName</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product variant number nomenclature</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVariantNumberNomenclatureName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product variant number nomenclature</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarrantyDurationTime name="WarrantyDurationTime">WarrantyDurationTime</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarrantyDurationTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarrantyDurationTimeUnit name="WarrantyDurationTimeUnit">WarrantyDurationTimeUnit</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarrantyDurationTimeUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EngChgProductTypeName name="EngChgProductTypeName">EngChgProductTypeName</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EngChgProductTypeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EngChgProductOwnerId name="EngChgProductOwnerId">EngChgProductOwnerId</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EngChgProductOwnerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProductColorGroupRelationshipId name="Relationship_ProductColorGroupRelationshipId">Relationship_ProductColorGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductColorGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductDimensionGroupRelationshipId name="Relationship_ProductDimensionGroupRelationshipId">Relationship_ProductDimensionGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductDimensionGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_StorageDimensionGroupRelationshipId name="Relationship_StorageDimensionGroupRelationshipId">Relationship_StorageDimensionGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_StorageDimensionGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TrackingDimensionGroupRelationshipId name="Relationship_TrackingDimensionGroupRelationshipId">Relationship_TrackingDimensionGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TrackingDimensionGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductSizeGroupRelationshipId name="Relationship_ProductSizeGroupRelationshipId">Relationship_ProductSizeGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductSizeGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductStyleGroupRelationshipId name="Relationship_ProductStyleGroupRelationshipId">Relationship_ProductStyleGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductStyleGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_StandardTransportationCommodityCodeRelationshipId name="Relationship_StandardTransportationCommodityCodeRelationshipId">Relationship_StandardTransportationCommodityCodeRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_StandardTransportationCommodityCodeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductHarmonizedTariffCodeRelationshipId name="Relationship_ProductHarmonizedTariffCodeRelationshipId">Relationship_ProductHarmonizedTariffCodeRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductHarmonizedTariffCodeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_USNationalMotorFreightClassificationCodeRelationshipId name="Relationship_USNationalMotorFreightClassificationCodeRelationshipId">Relationship_USNationalMotorFreightClassificationCodeRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_USNationalMotorFreightClassificationCodeRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_EcoResProductRelationshipId name="BackingTable_EcoResProductRelationshipId">BackingTable_EcoResProductRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_EcoResProductRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/EcoResProduct.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResProduct.cdm.json/EcoResProduct</a></td><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/EcoResProduct.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
