---
title: PmfFormulaVersionEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# PmfFormulaVersionEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/PmfFormulaVersionEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[IsActive](#IsActive)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[IsApproved](#IsApproved)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[ApproverId](#ApproverId)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[FormulaId](#FormulaId)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[IsSelectedForDesigner](#IsSelectedForDesigner)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[ValidFromDate](#ValidFromDate)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[FromQuantity](#FromQuantity)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[ManufacturedItemNumber](#ManufacturedItemNumber)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[VersionName](#VersionName)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[FromCatchWeightQuantity](#FromCatchWeightQuantity)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[CatchWeightSize](#CatchWeightSize)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[ValidToDate](#ValidToDate)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[ApproverPersonnelNumber](#ApproverPersonnelNumber)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[ProductionSiteId](#ProductionSiteId)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[FormulaBatchSize](#FormulaBatchSize)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[BulkItemNumber](#BulkItemNumber)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[IsCoProductQuantityVariationAllowed](#IsCoProductQuantityVariationAllowed)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[ChangedDate](#ChangedDate)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[FormulaBatchSizeMultiples](#FormulaBatchSizeMultiples)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[WillCostCalculationIncludeVersion](#WillCostCalculationIncludeVersion)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[IsTotalCostAllocationUsed](#IsTotalCostAllocationUsed)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[YieldPercentage](#YieldPercentage)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[Relationship_FormulaHeaderRelationshipId](#Relationship_FormulaHeaderRelationshipId)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[Relationship_EcoResProductStyleEntityRelationshipId](#Relationship_EcoResProductStyleEntityRelationshipId)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[Relationship_EcoResProductSizeEntityRelationshipId](#Relationship_EcoResProductSizeEntityRelationshipId)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[Relationship_EcoResProductConfigurationEntityRelationshipId](#Relationship_EcoResProductConfigurationEntityRelationshipId)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[Relationship_EcoResProductColorEntityRelationshipId](#Relationship_EcoResProductColorEntityRelationshipId)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[Relationship_EcoResReleasedProductV2EntityRelationshipId](#Relationship_EcoResReleasedProductV2EntityRelationshipId)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[Relationship_HcmWorkerEntityRelationshipId](#Relationship_HcmWorkerEntityRelationshipId)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[BackingTable_BOMVersionRelationshipId](#BackingTable_BOMVersionRelationshipId)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PmfFormulaVersionEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionEntity</a>|

### <a href=#IsActive name="IsActive">IsActive</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsApproved name="IsApproved">IsApproved</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsApproved attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApproverId name="ApproverId">ApproverId</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApproverId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormulaId name="FormulaId">FormulaId</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

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

### <a href=#IsSelectedForDesigner name="IsSelectedForDesigner">IsSelectedForDesigner</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSelectedForDesigner attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidFromDate name="ValidFromDate">ValidFromDate</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

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

### <a href=#FromQuantity name="FromQuantity">FromQuantity</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManufacturedItemNumber name="ManufacturedItemNumber">ManufacturedItemNumber</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManufacturedItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionName name="VersionName">VersionName</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromCatchWeightQuantity name="FromCatchWeightQuantity">FromCatchWeightQuantity</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CatchWeightSize name="CatchWeightSize">CatchWeightSize</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatchWeightSize attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidToDate name="ValidToDate">ValidToDate</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

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

### <a href=#ApproverPersonnelNumber name="ApproverPersonnelNumber">ApproverPersonnelNumber</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApproverPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

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

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

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

### <a href=#ProductionSiteId name="ProductionSiteId">ProductionSiteId</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

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

### <a href=#FormulaBatchSize name="FormulaBatchSize">FormulaBatchSize</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormulaBatchSize attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BulkItemNumber name="BulkItemNumber">BulkItemNumber</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BulkItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCoProductQuantityVariationAllowed name="IsCoProductQuantityVariationAllowed">IsCoProductQuantityVariationAllowed</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCoProductQuantityVariationAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChangedDate name="ChangedDate">ChangedDate</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChangedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormulaBatchSizeMultiples name="FormulaBatchSizeMultiples">FormulaBatchSizeMultiples</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormulaBatchSizeMultiples attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillCostCalculationIncludeVersion name="WillCostCalculationIncludeVersion">WillCostCalculationIncludeVersion</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillCostCalculationIncludeVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTotalCostAllocationUsed name="IsTotalCostAllocationUsed">IsTotalCostAllocationUsed</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTotalCostAllocationUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#YieldPercentage name="YieldPercentage">YieldPercentage</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the YieldPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FormulaHeaderRelationshipId name="Relationship_FormulaHeaderRelationshipId">Relationship_FormulaHeaderRelationshipId</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FormulaHeaderRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_EcoResProductStyleEntityRelationshipId name="Relationship_EcoResProductStyleEntityRelationshipId">Relationship_EcoResProductStyleEntityRelationshipId</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResProductStyleEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_EcoResProductSizeEntityRelationshipId name="Relationship_EcoResProductSizeEntityRelationshipId">Relationship_EcoResProductSizeEntityRelationshipId</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResProductSizeEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_EcoResProductConfigurationEntityRelationshipId name="Relationship_EcoResProductConfigurationEntityRelationshipId">Relationship_EcoResProductConfigurationEntityRelationshipId</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResProductConfigurationEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_EcoResProductColorEntityRelationshipId name="Relationship_EcoResProductColorEntityRelationshipId">Relationship_EcoResProductColorEntityRelationshipId</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResProductColorEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_EcoResReleasedProductV2EntityRelationshipId name="Relationship_EcoResReleasedProductV2EntityRelationshipId">Relationship_EcoResReleasedProductV2EntityRelationshipId</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResReleasedProductV2EntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_HcmWorkerEntityRelationshipId name="Relationship_HcmWorkerEntityRelationshipId">Relationship_HcmWorkerEntityRelationshipId</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HcmWorkerEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_BOMVersionRelationshipId name="BackingTable_BOMVersionRelationshipId">BackingTable_BOMVersionRelationshipId</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BOMVersionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/BOMVersion.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/BOMVersion.cdm.json/BOMVersion</a></td><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/BOMVersion.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductInformationManagement/PmfFormulaVersionEntity (this entity)  

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
