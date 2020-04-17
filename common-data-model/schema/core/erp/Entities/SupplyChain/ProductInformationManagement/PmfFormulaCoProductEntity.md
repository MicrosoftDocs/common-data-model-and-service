---
title: PmfFormulaCoProductEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# PmfFormulaCoProductEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/SupplyChain/ProductInformationManagement/PmfFormulaCoProductEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[FormulaId](#FormulaId)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[Quantity](#Quantity)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[QuantityDenominator](#QuantityDenominator)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[LineNumber](#LineNumber)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[CatchWeightQuantity](#CatchWeightQuantity)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[RoundingUpMethod](#RoundingUpMethod)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[QuantityRoundingUpMultiples](#QuantityRoundingUpMultiples)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[ConsumptionSiteId](#ConsumptionSiteId)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[ConsumptionWarehouseId](#ConsumptionWarehouseId)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[IsVersionActive](#IsVersionActive)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[VersionManufacturedItemNumber](#VersionManufacturedItemNumber)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[VersionValidFromDate](#VersionValidFromDate)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[VersionFromQuantity](#VersionFromQuantity)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[VersionProductConfigurationId](#VersionProductConfigurationId)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[VersionProductColorId](#VersionProductColorId)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[VersionProductionSiteId](#VersionProductionSiteId)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[VersionProductSizeId](#VersionProductSizeId)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[VersionProductStyleId](#VersionProductStyleId)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[VersionRecordId](#VersionRecordId)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[CoProductFormulaId](#CoProductFormulaId)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[CostAllocationMethod](#CostAllocationMethod)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[CostAllocationPercentage](#CostAllocationPercentage)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[Relationship_FormulaVersionRelationshipId](#Relationship_FormulaVersionRelationshipId)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[BackingTable_PmfFormulaCoByRelationshipId](#BackingTable_PmfFormulaCoByRelationshipId)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PmfFormulaCoProductEntity.md" target="_blank">ProductInformationManagement/PmfFormulaCoProductEntity</a>|

### <a href=#FormulaId name="FormulaId">FormulaId</a>

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

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

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

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

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionProductColorId name="VersionProductColorId">VersionProductColorId</a>

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionProductionSiteId name="VersionProductionSiteId">VersionProductionSiteId</a>

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionProductStyleId name="VersionProductStyleId">VersionProductStyleId</a>

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionRecordId name="VersionRecordId">VersionRecordId</a>

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/Main/PmfFormulaCoBy.md" target="_blank">/core/erp/Tables/SupplyChain/ProductionControl/Main/PmfFormulaCoBy.cdm.json/PmfFormulaCoBy</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/Main/PmfFormulaCoBy.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductInformationManagement/PmfFormulaCoProductEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
