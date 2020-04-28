---
title: EcoResTrackingDimensionGroupEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Tracking dimension groups

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/EcoResTrackingDimensionGroupEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tracking dimension groups</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[GroupName](#GroupName)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[GroupDescription](#GroupDescription)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[SerialNumberCapturingOperation](#SerialNumberCapturingOperation)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[IsSerialNumberControlEnabled](#IsSerialNumberControlEnabled)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[IsSerialNumberActive](#IsSerialNumberActive)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[IsSerialNumberEnabledForSalesProcess](#IsSerialNumberEnabledForSalesProcess)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[IsSerialNumberEnabledForProductionConsumptionProcess](#IsSerialNumberEnabledForProductionConsumptionProcess)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[IsBlankIssueAllowedForSerialNumber](#IsBlankIssueAllowedForSerialNumber)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[IsBlankReceiptAllowedForSerialNumber](#IsBlankReceiptAllowedForSerialNumber)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[IsCoveragePlanEnabledForSerialNumber](#IsCoveragePlanEnabledForSerialNumber)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[IsFinancialInventoryEnabledForSerialNumber](#IsFinancialInventoryEnabledForSerialNumber)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[IsPhysicalInventoryEnabledForSerialNumber](#IsPhysicalInventoryEnabledForSerialNumber)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[IsPrimaryStockingEnabledForSerialNumber](#IsPrimaryStockingEnabledForSerialNumber)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[IsPurchasePriceBySerialNumber](#IsPurchasePriceBySerialNumber)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[IsSalesPriceBySerialNumber](#IsSalesPriceBySerialNumber)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[IsBatchNumberActive](#IsBatchNumberActive)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[IsBlankIssueAllowedForBatchNumber](#IsBlankIssueAllowedForBatchNumber)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[IsBlankReceiptAllowedForBatchNumber](#IsBlankReceiptAllowedForBatchNumber)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[IsCoveragePlanEnabledForBatchNumber](#IsCoveragePlanEnabledForBatchNumber)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[IsFinancialInventoryEnabledForBatchNumber](#IsFinancialInventoryEnabledForBatchNumber)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[IsPhysicalInventoryEnabledForBatchNumber](#IsPhysicalInventoryEnabledForBatchNumber)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[IsPrimaryStockingEnabledForBatchNumber](#IsPrimaryStockingEnabledForBatchNumber)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[IsPurchasePriceByBatchNumber](#IsPurchasePriceByBatchNumber)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[IsSalesPriceByBatchNumber](#IsSalesPriceByBatchNumber)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[IsInventoryOwnerActive](#IsInventoryOwnerActive)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[IsInventoryProfileActive](#IsInventoryProfileActive)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[IsGTDActive](#IsGTDActive)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[IsCoveragePlanEnabledForInventoryProfile](#IsCoveragePlanEnabledForInventoryProfile)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|
|[BackingTable_EcoResTrackingDimensionGroupRelationshipId](#BackingTable_EcoResTrackingDimensionGroupRelationshipId)||<a href="EcoResTrackingDimensionGroupEntity.md" target="_blank">ProductInformationManagement/EcoResTrackingDimensionGroupEntity</a>|

### <a href=#GroupName name="GroupName">GroupName</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupDescription name="GroupDescription">GroupDescription</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SerialNumberCapturingOperation name="SerialNumberCapturingOperation">SerialNumberCapturingOperation</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SerialNumberCapturingOperation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSerialNumberControlEnabled name="IsSerialNumberControlEnabled">IsSerialNumberControlEnabled</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSerialNumberControlEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSerialNumberActive name="IsSerialNumberActive">IsSerialNumberActive</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is serial number active</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSerialNumberActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is serial number active</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSerialNumberEnabledForSalesProcess name="IsSerialNumberEnabledForSalesProcess">IsSerialNumberEnabledForSalesProcess</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is serial number enabled for sales process</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSerialNumberEnabledForSalesProcess attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is serial number enabled for sales process</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSerialNumberEnabledForProductionConsumptionProcess name="IsSerialNumberEnabledForProductionConsumptionProcess">IsSerialNumberEnabledForProductionConsumptionProcess</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSerialNumberEnabledForProductionConsumptionProcess attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBlankIssueAllowedForSerialNumber name="IsBlankIssueAllowedForSerialNumber">IsBlankIssueAllowedForSerialNumber</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow no specification of serial number on physical update of product issues</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBlankIssueAllowedForSerialNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow no specification of serial number on physical update of product issues</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBlankReceiptAllowedForSerialNumber name="IsBlankReceiptAllowedForSerialNumber">IsBlankReceiptAllowedForSerialNumber</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow no specification of serial number on physical update of product receipts</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBlankReceiptAllowedForSerialNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow no specification of serial number on physical update of product receipts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCoveragePlanEnabledForSerialNumber name="IsCoveragePlanEnabledForSerialNumber">IsCoveragePlanEnabledForSerialNumber</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include serial number when creating coverage plan </td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCoveragePlanEnabledForSerialNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include serial number when creating coverage plan </td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFinancialInventoryEnabledForSerialNumber name="IsFinancialInventoryEnabledForSerialNumber">IsFinancialInventoryEnabledForSerialNumber</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is financial inventory enabled for serial number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFinancialInventoryEnabledForSerialNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is financial inventory enabled for serial number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPhysicalInventoryEnabledForSerialNumber name="IsPhysicalInventoryEnabledForSerialNumber">IsPhysicalInventoryEnabledForSerialNumber</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is physical inventory enabled for serial number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPhysicalInventoryEnabledForSerialNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is physical inventory enabled for serial number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrimaryStockingEnabledForSerialNumber name="IsPrimaryStockingEnabledForSerialNumber">IsPrimaryStockingEnabledForSerialNumber</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is primary stocking enabled for serial number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrimaryStockingEnabledForSerialNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is primary stocking enabled for serial number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPurchasePriceBySerialNumber name="IsPurchasePriceBySerialNumber">IsPurchasePriceBySerialNumber</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include serial number when searching for purchase prices</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPurchasePriceBySerialNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include serial number when searching for purchase prices</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesPriceBySerialNumber name="IsSalesPriceBySerialNumber">IsSalesPriceBySerialNumber</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include serial number when searching for sales prices</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesPriceBySerialNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include serial number when searching for sales prices</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBatchNumberActive name="IsBatchNumberActive">IsBatchNumberActive</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is batch number active</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBatchNumberActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is batch number active</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBlankIssueAllowedForBatchNumber name="IsBlankIssueAllowedForBatchNumber">IsBlankIssueAllowedForBatchNumber</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow no specification of batch number on physical update of product issues</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBlankIssueAllowedForBatchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow no specification of batch number on physical update of product issues</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBlankReceiptAllowedForBatchNumber name="IsBlankReceiptAllowedForBatchNumber">IsBlankReceiptAllowedForBatchNumber</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow no specification of batch number on physical update of product receipts</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBlankReceiptAllowedForBatchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow no specification of batch number on physical update of product receipts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCoveragePlanEnabledForBatchNumber name="IsCoveragePlanEnabledForBatchNumber">IsCoveragePlanEnabledForBatchNumber</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include batch number when creating coverage plan </td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCoveragePlanEnabledForBatchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include batch number when creating coverage plan </td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFinancialInventoryEnabledForBatchNumber name="IsFinancialInventoryEnabledForBatchNumber">IsFinancialInventoryEnabledForBatchNumber</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is financial inventory enabled for batch number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFinancialInventoryEnabledForBatchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is financial inventory enabled for batch number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPhysicalInventoryEnabledForBatchNumber name="IsPhysicalInventoryEnabledForBatchNumber">IsPhysicalInventoryEnabledForBatchNumber</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is physical inventory enabled for batch number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPhysicalInventoryEnabledForBatchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is physical inventory enabled for batch number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrimaryStockingEnabledForBatchNumber name="IsPrimaryStockingEnabledForBatchNumber">IsPrimaryStockingEnabledForBatchNumber</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is primary stocking enabled for batch number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrimaryStockingEnabledForBatchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is primary stocking enabled for batch number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPurchasePriceByBatchNumber name="IsPurchasePriceByBatchNumber">IsPurchasePriceByBatchNumber</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include batch number when searching for purchase prices</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPurchasePriceByBatchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include batch number when searching for purchase prices</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesPriceByBatchNumber name="IsSalesPriceByBatchNumber">IsSalesPriceByBatchNumber</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include batch number when searching for sales prices</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesPriceByBatchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include batch number when searching for sales prices</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventoryOwnerActive name="IsInventoryOwnerActive">IsInventoryOwnerActive</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is inventory owner active</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventoryOwnerActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is inventory owner active</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInventoryProfileActive name="IsInventoryProfileActive">IsInventoryProfileActive</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is inventory profile active</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventoryProfileActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is inventory profile active</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsGTDActive name="IsGTDActive">IsGTDActive</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is GTD active</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsGTDActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is GTD active</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCoveragePlanEnabledForInventoryProfile name="IsCoveragePlanEnabledForInventoryProfile">IsCoveragePlanEnabledForInventoryProfile</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include inventory profile when creating coverage plan</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCoveragePlanEnabledForInventoryProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include inventory profile when creating coverage plan</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_EcoResTrackingDimensionGroupRelationshipId name="BackingTable_EcoResTrackingDimensionGroupRelationshipId">BackingTable_EcoResTrackingDimensionGroupRelationshipId</a>

First included in: ProductInformationManagement/EcoResTrackingDimensionGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_EcoResTrackingDimensionGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Group/EcoResTrackingDimensionGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Group/EcoResTrackingDimensionGroup.cdm.json/EcoResTrackingDimensionGroup</a></td><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Group/EcoResTrackingDimensionGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
