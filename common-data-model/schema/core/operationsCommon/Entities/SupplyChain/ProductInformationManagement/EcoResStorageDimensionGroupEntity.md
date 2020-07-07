---
title: EcoResStorageDimensionGroupEntity in ProductInformationManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Storage dimension groups in ProductInformationManagement

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/EcoResStorageDimensionGroupEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Storage dimension groups</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[GroupName](#GroupName)||<a href="EcoResStorageDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResStorageDimensionGroupEntity</a>|
|[GroupDescription](#GroupDescription)||<a href="EcoResStorageDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResStorageDimensionGroupEntity</a>|
|[IsWarehouseMandatory](#IsWarehouseMandatory)||<a href="EcoResStorageDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResStorageDimensionGroupEntity</a>|
|[IsWarehousePrimaryStorageDimension](#IsWarehousePrimaryStorageDimension)||<a href="EcoResStorageDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResStorageDimensionGroupEntity</a>|
|[AreAdvancedWarehouseManagementProcessesEnabled](#AreAdvancedWarehouseManagementProcessesEnabled)||<a href="EcoResStorageDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResStorageDimensionGroupEntity</a>|
|[WillPurchasePriceSearchUseSite](#WillPurchasePriceSearchUseSite)||<a href="EcoResStorageDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResStorageDimensionGroupEntity</a>|
|[WillSalesPriceSearchUseSite](#WillSalesPriceSearchUseSite)||<a href="EcoResStorageDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResStorageDimensionGroupEntity</a>|
|[WillCoveragePlanningUseWarehouse](#WillCoveragePlanningUseWarehouse)||<a href="EcoResStorageDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResStorageDimensionGroupEntity</a>|
|[IsFinancialInventoryEnabledForWarehouse](#IsFinancialInventoryEnabledForWarehouse)||<a href="EcoResStorageDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResStorageDimensionGroupEntity</a>|
|[IsPhysicalInventoryEnabledForWarehouse](#IsPhysicalInventoryEnabledForWarehouse)||<a href="EcoResStorageDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResStorageDimensionGroupEntity</a>|
|[WillPurchasePriceSearchUseWarehouse](#WillPurchasePriceSearchUseWarehouse)||<a href="EcoResStorageDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResStorageDimensionGroupEntity</a>|
|[WillSalesPriceSearchUseWarehouse](#WillSalesPriceSearchUseWarehouse)||<a href="EcoResStorageDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResStorageDimensionGroupEntity</a>|
|[IsLocationActive](#IsLocationActive)||<a href="EcoResStorageDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResStorageDimensionGroupEntity</a>|
|[IsBlankIssueAllowedForLocation](#IsBlankIssueAllowedForLocation)||<a href="EcoResStorageDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResStorageDimensionGroupEntity</a>|
|[IsBlankReceiptAllowedForLocation](#IsBlankReceiptAllowedForLocation)||<a href="EcoResStorageDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResStorageDimensionGroupEntity</a>|
|[WillCoveragePlanningUseLocation](#WillCoveragePlanningUseLocation)||<a href="EcoResStorageDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResStorageDimensionGroupEntity</a>|
|[IsPhysicalInventoryEnabledForLocation](#IsPhysicalInventoryEnabledForLocation)||<a href="EcoResStorageDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResStorageDimensionGroupEntity</a>|
|[WillCoveragePlanningUseInventoryStatus](#WillCoveragePlanningUseInventoryStatus)||<a href="EcoResStorageDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResStorageDimensionGroupEntity</a>|
|[WillPurchasePriceSearchUseInventoryStatus](#WillPurchasePriceSearchUseInventoryStatus)||<a href="EcoResStorageDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResStorageDimensionGroupEntity</a>|
|[WillSalesPriceSearchUseInventoryStatus](#WillSalesPriceSearchUseInventoryStatus)||<a href="EcoResStorageDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResStorageDimensionGroupEntity</a>|
|[BackingTable_EcoResStorageDimensionGroupRelationshipId](#BackingTable_EcoResStorageDimensionGroupRelationshipId)||<a href="EcoResStorageDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResStorageDimensionGroupEntity</a>|

### <a href=#GroupName name="GroupName">GroupName</a>

First included in: ProductInformationManagement/EcoResStorageDimensionGroupEntity (this entity)  

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

First included in: ProductInformationManagement/EcoResStorageDimensionGroupEntity (this entity)  

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

### <a href=#IsWarehouseMandatory name="IsWarehouseMandatory">IsWarehouseMandatory</a>

First included in: ProductInformationManagement/EcoResStorageDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWarehouseMandatory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWarehousePrimaryStorageDimension name="IsWarehousePrimaryStorageDimension">IsWarehousePrimaryStorageDimension</a>

First included in: ProductInformationManagement/EcoResStorageDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWarehousePrimaryStorageDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreAdvancedWarehouseManagementProcessesEnabled name="AreAdvancedWarehouseManagementProcessesEnabled">AreAdvancedWarehouseManagementProcessesEnabled</a>

First included in: ProductInformationManagement/EcoResStorageDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreAdvancedWarehouseManagementProcessesEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillPurchasePriceSearchUseSite name="WillPurchasePriceSearchUseSite">WillPurchasePriceSearchUseSite</a>

First included in: ProductInformationManagement/EcoResStorageDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include site when searching for purchase prices</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillPurchasePriceSearchUseSite attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include site when searching for purchase prices</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSalesPriceSearchUseSite name="WillSalesPriceSearchUseSite">WillSalesPriceSearchUseSite</a>

First included in: ProductInformationManagement/EcoResStorageDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include site when searching for sales prices</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSalesPriceSearchUseSite attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include site when searching for sales prices</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillCoveragePlanningUseWarehouse name="WillCoveragePlanningUseWarehouse">WillCoveragePlanningUseWarehouse</a>

First included in: ProductInformationManagement/EcoResStorageDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include warehouse when creating coverage plan </td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillCoveragePlanningUseWarehouse attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include warehouse when creating coverage plan </td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFinancialInventoryEnabledForWarehouse name="IsFinancialInventoryEnabledForWarehouse">IsFinancialInventoryEnabledForWarehouse</a>

First included in: ProductInformationManagement/EcoResStorageDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is financial inventory enabled for warehouse</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFinancialInventoryEnabledForWarehouse attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is financial inventory enabled for warehouse</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPhysicalInventoryEnabledForWarehouse name="IsPhysicalInventoryEnabledForWarehouse">IsPhysicalInventoryEnabledForWarehouse</a>

First included in: ProductInformationManagement/EcoResStorageDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is physical inventory enabled for warehouse</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPhysicalInventoryEnabledForWarehouse attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is physical inventory enabled for warehouse</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillPurchasePriceSearchUseWarehouse name="WillPurchasePriceSearchUseWarehouse">WillPurchasePriceSearchUseWarehouse</a>

First included in: ProductInformationManagement/EcoResStorageDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include warehouse when searching for purchase prices</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillPurchasePriceSearchUseWarehouse attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include warehouse when searching for purchase prices</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSalesPriceSearchUseWarehouse name="WillSalesPriceSearchUseWarehouse">WillSalesPriceSearchUseWarehouse</a>

First included in: ProductInformationManagement/EcoResStorageDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include warehouse when searching for sales prices</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSalesPriceSearchUseWarehouse attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include warehouse when searching for sales prices</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLocationActive name="IsLocationActive">IsLocationActive</a>

First included in: ProductInformationManagement/EcoResStorageDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is location active</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLocationActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is location active</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBlankIssueAllowedForLocation name="IsBlankIssueAllowedForLocation">IsBlankIssueAllowedForLocation</a>

First included in: ProductInformationManagement/EcoResStorageDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow no specification of location on physical update of product issues</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBlankIssueAllowedForLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow no specification of location on physical update of product issues</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBlankReceiptAllowedForLocation name="IsBlankReceiptAllowedForLocation">IsBlankReceiptAllowedForLocation</a>

First included in: ProductInformationManagement/EcoResStorageDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow no specification of location on physical update of product receipts</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBlankReceiptAllowedForLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow no specification of location on physical update of product receipts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillCoveragePlanningUseLocation name="WillCoveragePlanningUseLocation">WillCoveragePlanningUseLocation</a>

First included in: ProductInformationManagement/EcoResStorageDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include location when creating coverage plan </td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillCoveragePlanningUseLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include location when creating coverage plan </td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPhysicalInventoryEnabledForLocation name="IsPhysicalInventoryEnabledForLocation">IsPhysicalInventoryEnabledForLocation</a>

First included in: ProductInformationManagement/EcoResStorageDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is physical inventory enabled for location</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPhysicalInventoryEnabledForLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is physical inventory enabled for location</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillCoveragePlanningUseInventoryStatus name="WillCoveragePlanningUseInventoryStatus">WillCoveragePlanningUseInventoryStatus</a>

First included in: ProductInformationManagement/EcoResStorageDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include inventory status when creating coverage plan </td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillCoveragePlanningUseInventoryStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include inventory status when creating coverage plan </td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillPurchasePriceSearchUseInventoryStatus name="WillPurchasePriceSearchUseInventoryStatus">WillPurchasePriceSearchUseInventoryStatus</a>

First included in: ProductInformationManagement/EcoResStorageDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include inventory status when searching for purchase prices</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillPurchasePriceSearchUseInventoryStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include inventory status when searching for purchase prices</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSalesPriceSearchUseInventoryStatus name="WillSalesPriceSearchUseInventoryStatus">WillSalesPriceSearchUseInventoryStatus</a>

First included in: ProductInformationManagement/EcoResStorageDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include inventory status when searching for sales prices</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSalesPriceSearchUseInventoryStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include inventory status when searching for sales prices</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_EcoResStorageDimensionGroupRelationshipId name="BackingTable_EcoResStorageDimensionGroupRelationshipId">BackingTable_EcoResStorageDimensionGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResStorageDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_EcoResStorageDimensionGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Group/EcoResStorageDimensionGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Group/EcoResStorageDimensionGroup.cdm.json/EcoResStorageDimensionGroup</a></td><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Group/EcoResStorageDimensionGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
