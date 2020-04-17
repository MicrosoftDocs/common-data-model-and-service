---
title: RetailVendTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailVendTable

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Commerce/Retail/Main/RetailVendTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailVendTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[itemNumberSeq](#itemNumberSeq)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[AccountNum](#AccountNum)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[barcodeNumberSeq](#barcodeNumberSeq)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[colorIdPrefix](#colorIdPrefix)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[createBarcodeIfNeeded](#createBarcodeIfNeeded)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[defaultShelfLifePeriod_ATH](#defaultShelfLifePeriod_ATH)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[ExchRate](#ExchRate)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[FileExportPrefix](#FileExportPrefix)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[FixedExchRate](#FixedExchRate)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[ForeignVendPriceGroup_ATH](#ForeignVendPriceGroup_ATH)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[FranchiseeId](#FranchiseeId)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[itemNumberPrefix](#itemNumberPrefix)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[ItemSalesExportPath](#ItemSalesExportPath)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[pricePointGroupId](#pricePointGroupId)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[PricePointRoundingType](#PricePointRoundingType)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[purchUnit](#purchUnit)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[roundingMethod](#roundingMethod)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[salesPriceRounding](#salesPriceRounding)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[salesUnit](#salesUnit)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[serviceCategory](#serviceCategory)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[sizeIdPrefix](#sizeIdPrefix)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[styleIdPrefix](#styleIdPrefix)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[usePrefixForItemNumber](#usePrefixForItemNumber)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[useVendorsItemNumberSeq](#useVendorsItemNumberSeq)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[VendorProductHierarchyId](#VendorProductHierarchyId)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[vendType](#vendType)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[DataAreaId](#DataAreaId)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[Relationship_BarcodeNumberSeqRelationshipId](#Relationship_BarcodeNumberSeqRelationshipId)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[Relationship_EcoResCategoryHierarchyRelationshipId](#Relationship_EcoResCategoryHierarchyRelationshipId)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[Relationship_ItemNumberSeqRelationshipId](#Relationship_ItemNumberSeqRelationshipId)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[Relationship_PriceDiscGroupRelationshipId](#Relationship_PriceDiscGroupRelationshipId)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[Relationship_RetailRoundingMethodGroupRelationshipId](#Relationship_RetailRoundingMethodGroupRelationshipId)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[Relationship_RetailSalesPricePointGroupRelationshipId](#Relationship_RetailSalesPricePointGroupRelationshipId)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[Relationship_RetailServiceCategoryRelationshipId](#Relationship_RetailServiceCategoryRelationshipId)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[Relationship_VendTableRelationshipId](#Relationship_VendTableRelationshipId)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RetailVendTable.md" target="_blank">Main/RetailVendTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailVendTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#itemNumberSeq name="itemNumberSeq">itemNumberSeq</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the itemNumberSeq attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNum name="AccountNum">AccountNum</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#barcodeNumberSeq name="barcodeNumberSeq">barcodeNumberSeq</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the barcodeNumberSeq attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#colorIdPrefix name="colorIdPrefix">colorIdPrefix</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the colorIdPrefix attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#createBarcodeIfNeeded name="createBarcodeIfNeeded">createBarcodeIfNeeded</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createBarcodeIfNeeded attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#defaultShelfLifePeriod_ATH name="defaultShelfLifePeriod_ATH">defaultShelfLifePeriod_ATH</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the defaultShelfLifePeriod_ATH attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExchRate name="ExchRate">ExchRate</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FileExportPrefix name="FileExportPrefix">FileExportPrefix</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FileExportPrefix attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedExchRate name="FixedExchRate">FixedExchRate</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedExchRate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ForeignVendPriceGroup_ATH name="ForeignVendPriceGroup_ATH">ForeignVendPriceGroup_ATH</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForeignVendPriceGroup_ATH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FranchiseeId name="FranchiseeId">FranchiseeId</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FranchiseeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#itemNumberPrefix name="itemNumberPrefix">itemNumberPrefix</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the itemNumberPrefix attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSalesExportPath name="ItemSalesExportPath">ItemSalesExportPath</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSalesExportPath attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#pricePointGroupId name="pricePointGroupId">pricePointGroupId</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the pricePointGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PricePointRoundingType name="PricePointRoundingType">PricePointRoundingType</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PricePointRoundingType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#purchUnit name="purchUnit">purchUnit</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the purchUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#roundingMethod name="roundingMethod">roundingMethod</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the roundingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#salesPriceRounding name="salesPriceRounding">salesPriceRounding</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the salesPriceRounding attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#salesUnit name="salesUnit">salesUnit</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the salesUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#serviceCategory name="serviceCategory">serviceCategory</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the serviceCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#sizeIdPrefix name="sizeIdPrefix">sizeIdPrefix</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the sizeIdPrefix attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#styleIdPrefix name="styleIdPrefix">styleIdPrefix</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the styleIdPrefix attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#usePrefixForItemNumber name="usePrefixForItemNumber">usePrefixForItemNumber</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the usePrefixForItemNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#useVendorsItemNumberSeq name="useVendorsItemNumberSeq">useVendorsItemNumberSeq</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the useVendorsItemNumberSeq attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VendorProductHierarchyId name="VendorProductHierarchyId">VendorProductHierarchyId</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorProductHierarchyId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#vendType name="vendType">vendType</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the vendType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BarcodeNumberSeqRelationshipId name="Relationship_BarcodeNumberSeqRelationshipId">Relationship_BarcodeNumberSeqRelationshipId</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BarcodeNumberSeqRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md" target="_blank">/core/erp/Tables/System/SystemAdministration/Framework/NumberSequenceTable.cdm.json/NumberSequenceTable</a></td><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EcoResCategoryHierarchyRelationshipId name="Relationship_EcoResCategoryHierarchyRelationshipId">Relationship_EcoResCategoryHierarchyRelationshipId</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResCategoryHierarchyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResCategoryHierarchy.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResCategoryHierarchy.cdm.json/EcoResCategoryHierarchy</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResCategoryHierarchy.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ItemNumberSeqRelationshipId name="Relationship_ItemNumberSeqRelationshipId">Relationship_ItemNumberSeqRelationshipId</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ItemNumberSeqRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md" target="_blank">/core/erp/Tables/System/SystemAdministration/Framework/NumberSequenceTable.cdm.json/NumberSequenceTable</a></td><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PriceDiscGroupRelationshipId name="Relationship_PriceDiscGroupRelationshipId">Relationship_PriceDiscGroupRelationshipId</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PriceDiscGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/SalesAndMarketing/Group/PriceDiscGroup.md" target="_blank">/core/erp/Tables/SupplyChain/SalesAndMarketing/Group/PriceDiscGroup.cdm.json/PriceDiscGroup</a></td><td><a href="../../../SupplyChain/SalesAndMarketing/Group/PriceDiscGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailRoundingMethodGroupRelationshipId name="Relationship_RetailRoundingMethodGroupRelationshipId">Relationship_RetailRoundingMethodGroupRelationshipId</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailRoundingMethodGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/RetailRoundingMethodGroup.md" target="_blank">/core/erp/Tables/Commerce/Retail/Group/RetailRoundingMethodGroup.cdm.json/RetailRoundingMethodGroup</a></td><td><a href="../Group/RetailRoundingMethodGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailSalesPricePointGroupRelationshipId name="Relationship_RetailSalesPricePointGroupRelationshipId">Relationship_RetailSalesPricePointGroupRelationshipId</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailSalesPricePointGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/RetailSalesPricePointGroup.md" target="_blank">/core/erp/Tables/Commerce/Retail/Group/RetailSalesPricePointGroup.cdm.json/RetailSalesPricePointGroup</a></td><td><a href="../Group/RetailSalesPricePointGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailServiceCategoryRelationshipId name="Relationship_RetailServiceCategoryRelationshipId">Relationship_RetailServiceCategoryRelationshipId</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailServiceCategoryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailServiceCategory.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/RetailServiceCategory.cdm.json/RetailServiceCategory</a></td><td><a href="RetailServiceCategory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTableRelationshipId name="Relationship_VendTableRelationshipId">Relationship_VendTableRelationshipId</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md" target="_blank">/core/erp/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/RetailVendTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
