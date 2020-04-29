---
title: BOMBillOfMaterialsLineV3Entity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Bill of materials lines V3

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/BOMBillOfMaterialsLineV3Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bill of materials lines V3</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ConsumptionType](#ConsumptionType)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[BOMId](#BOMId)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[Quantity](#Quantity)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[QuantityDenominator](#QuantityDenominator)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[LineType](#LineType)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[WillCostCalculationIncludeLine](#WillCostCalculationIncludeLine)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[ConsumptionCalculationConstant](#ConsumptionCalculationConstant)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[PhysicalProductDensity](#PhysicalProductDensity)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[PhysicalProductDepth](#PhysicalProductDepth)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[IsConsumedAtOperationComplete](#IsConsumedAtOperationComplete)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[ConsumptionCalculationMethod](#ConsumptionCalculationMethod)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[ValidFromDate](#ValidFromDate)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[PhysicalProductHeight](#PhysicalProductHeight)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[SubBOMId](#SubBOMId)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[ItemNumber](#ItemNumber)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[SubRouteId](#SubRouteId)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[LineNumber](#LineNumber)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[RouteOperationNumber](#RouteOperationNumber)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[CatchWeightQuantity](#CatchWeightQuantity)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[WillManufacturedItemInheritBatchAttributes](#WillManufacturedItemInheritBatchAttributes)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[WillManufacturedItemInheritShelfLifeDates](#WillManufacturedItemInheritShelfLifeDates)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[PositionNumber](#PositionNumber)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[FlushingPrinciple](#FlushingPrinciple)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[RoundingUpMethod](#RoundingUpMethod)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[QuantityRoundingUpMultiples](#QuantityRoundingUpMultiples)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[ConstantScrapQuantity](#ConstantScrapQuantity)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[VariableScrapPercentage](#VariableScrapPercentage)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[ValidToDate](#ValidToDate)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[ProductUnitSymbol](#ProductUnitSymbol)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[VendorAccountNumber](#VendorAccountNumber)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[PhysicalProductWidth](#PhysicalProductWidth)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[IsResourceConsumptionUsed](#IsResourceConsumptionUsed)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[ProductColorId](#ProductColorId)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[ConsumptionSiteId](#ConsumptionSiteId)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[ConsumptionWarehouseId](#ConsumptionWarehouseId)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[LineBOMId](#LineBOMId)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[LineCreationSequenceNumber](#LineCreationSequenceNumber)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[ConfigurationGroupId](#ConfigurationGroupId)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[Relationship_RelationForeignKey1RelationshipId](#Relationship_RelationForeignKey1RelationshipId)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[Relationship_RouteHeaderRelationshipId](#Relationship_RouteHeaderRelationshipId)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[Relationship_SubBillOfMaterialsHeaderRelationshipId](#Relationship_SubBillOfMaterialsHeaderRelationshipId)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[Relationship_VendorRelationshipId](#Relationship_VendorRelationshipId)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[Relationship_BillOfMaterialsHeaderRelationshipId](#Relationship_BillOfMaterialsHeaderRelationshipId)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[Relationship_BOMConfigurationGroupRelationshipId](#Relationship_BOMConfigurationGroupRelationshipId)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[BackingTable_BOMRelationshipId](#BackingTable_BOMRelationshipId)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="BOMBillOfMaterialsLineV3Entity.md" target="_blank">ProductInformationManagement/BOMBillOfMaterialsLineV3Entity</a>|

### <a href=#ConsumptionType name="ConsumptionType">ConsumptionType</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOMId name="BOMId">BOMId</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOMId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

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

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

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

### <a href=#LineType name="LineType">LineType</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillCostCalculationIncludeLine name="WillCostCalculationIncludeLine">WillCostCalculationIncludeLine</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillCostCalculationIncludeLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumptionCalculationConstant name="ConsumptionCalculationConstant">ConsumptionCalculationConstant</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionCalculationConstant attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalProductDensity name="PhysicalProductDensity">PhysicalProductDensity</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalProductDensity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalProductDepth name="PhysicalProductDepth">PhysicalProductDepth</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalProductDepth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsConsumedAtOperationComplete name="IsConsumedAtOperationComplete">IsConsumedAtOperationComplete</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsConsumedAtOperationComplete attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumptionCalculationMethod name="ConsumptionCalculationMethod">ConsumptionCalculationMethod</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionCalculationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidFromDate name="ValidFromDate">ValidFromDate</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFromDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalProductHeight name="PhysicalProductHeight">PhysicalProductHeight</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalProductHeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubBOMId name="SubBOMId">SubBOMId</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubBOMId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

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

### <a href=#SubRouteId name="SubRouteId">SubRouteId</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubRouteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

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

### <a href=#RouteOperationNumber name="RouteOperationNumber">RouteOperationNumber</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteOperationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CatchWeightQuantity name="CatchWeightQuantity">CatchWeightQuantity</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

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

### <a href=#WillManufacturedItemInheritBatchAttributes name="WillManufacturedItemInheritBatchAttributes">WillManufacturedItemInheritBatchAttributes</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillManufacturedItemInheritBatchAttributes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillManufacturedItemInheritShelfLifeDates name="WillManufacturedItemInheritShelfLifeDates">WillManufacturedItemInheritShelfLifeDates</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillManufacturedItemInheritShelfLifeDates attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PositionNumber name="PositionNumber">PositionNumber</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FlushingPrinciple name="FlushingPrinciple">FlushingPrinciple</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FlushingPrinciple attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoundingUpMethod name="RoundingUpMethod">RoundingUpMethod</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

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

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

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

### <a href=#ConstantScrapQuantity name="ConstantScrapQuantity">ConstantScrapQuantity</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConstantScrapQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VariableScrapPercentage name="VariableScrapPercentage">VariableScrapPercentage</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VariableScrapPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidToDate name="ValidToDate">ValidToDate</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidToDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductUnitSymbol name="ProductUnitSymbol">ProductUnitSymbol</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAccountNumber name="VendorAccountNumber">VendorAccountNumber</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

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

### <a href=#PhysicalProductWidth name="PhysicalProductWidth">PhysicalProductWidth</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalProductWidth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsResourceConsumptionUsed name="IsResourceConsumptionUsed">IsResourceConsumptionUsed</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsResourceConsumptionUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

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

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

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

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

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

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

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

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

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

### <a href=#ConsumptionSiteId name="ConsumptionSiteId">ConsumptionSiteId</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsumptionWarehouseId name="ConsumptionWarehouseId">ConsumptionWarehouseId</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineBOMId name="LineBOMId">LineBOMId</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineBOMId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineCreationSequenceNumber name="LineCreationSequenceNumber">LineCreationSequenceNumber</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineCreationSequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConfigurationGroupId name="ConfigurationGroupId">ConfigurationGroupId</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfigurationGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RelationForeignKey1RelationshipId name="Relationship_RelationForeignKey1RelationshipId">Relationship_RelationForeignKey1RelationshipId</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RelationForeignKey1RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RouteHeaderRelationshipId name="Relationship_RouteHeaderRelationshipId">Relationship_RouteHeaderRelationshipId</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RouteHeaderRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SubBillOfMaterialsHeaderRelationshipId name="Relationship_SubBillOfMaterialsHeaderRelationshipId">Relationship_SubBillOfMaterialsHeaderRelationshipId</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SubBillOfMaterialsHeaderRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_VendorRelationshipId name="Relationship_VendorRelationshipId">Relationship_VendorRelationshipId</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendorRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_BillOfMaterialsHeaderRelationshipId name="Relationship_BillOfMaterialsHeaderRelationshipId">Relationship_BillOfMaterialsHeaderRelationshipId</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BillOfMaterialsHeaderRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_BOMConfigurationGroupRelationshipId name="Relationship_BOMConfigurationGroupRelationshipId">Relationship_BOMConfigurationGroupRelationshipId</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BOMConfigurationGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_BOMRelationshipId name="BackingTable_BOMRelationshipId">BackingTable_BOMRelationshipId</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BOMRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/BOM.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/BOM.cdm.json/BOM</a></td><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/BOM.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductInformationManagement/BOMBillOfMaterialsLineV3Entity (this entity)  

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
