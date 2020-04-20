---
title: RetailImportJournalTrans - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailImportJournalTrans

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Transaction/RetailImportJournalTrans.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailImportJournalTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[VendorItemId](#VendorItemId)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[VendAccount1](#VendAccount1)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[error](#error)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[fabricComposition](#fabricComposition)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[importedFileId](#importedFileId)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[InventColorId](#InventColorId)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[InventColorName](#InventColorName)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[InventColorTxt](#InventColorTxt)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[InventSizeId](#InventSizeId)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[InventSizeName](#InventSizeName)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[InventSizeTxt](#InventSizeTxt)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[inventStyleId](#inventStyleId)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[InventStyleName](#InventStyleName)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[inventStyleTxt](#inventStyleTxt)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[ItemBarCode](#ItemBarCode)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[ItemId](#ItemId)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[ItemName](#ItemName)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[JournalId](#JournalId)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[level1Name](#level1Name)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[level2Name](#level2Name)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[level3Name](#level3Name)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[level4Name](#level4Name)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[lineNum](#lineNum)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[newBarcode](#newBarcode)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[newItemNumber](#newItemNumber)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[newVariant](#newVariant)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[priceCalculationType](#priceCalculationType)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[PriceChange](#PriceChange)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[PurchPrice](#PurchPrice)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[PurchUnit](#PurchUnit)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[SalesPrice](#SalesPrice)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[SalesUnit](#SalesUnit)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[seasonCode](#seasonCode)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[Status](#Status)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[suggestedRetailPrice](#suggestedRetailPrice)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[unitPriceDate](#unitPriceDate)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[VendAccount](#VendAccount)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[vendorHirarchyLevel1](#vendorHirarchyLevel1)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[vendorHirarchyLevel2](#vendorHirarchyLevel2)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[vendorHirarchyLevel3](#vendorHirarchyLevel3)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[vendorHirarchyLevel4](#vendorHirarchyLevel4)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[DataAreaId](#DataAreaId)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[Relationship_InventItemBarcodeRelationshipId](#Relationship_InventItemBarcodeRelationshipId)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[Relationship_InventTableRelationshipId](#Relationship_InventTableRelationshipId)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[Relationship_InventTable1RelationshipId](#Relationship_InventTable1RelationshipId)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[Relationship_RetailImportJournalTableRelationshipId](#Relationship_RetailImportJournalTableRelationshipId)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[Relationship_RetailImportTableRelationshipId](#Relationship_RetailImportTableRelationshipId)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[Relationship_RetailSeasonTableRelationshipId](#Relationship_RetailSeasonTableRelationshipId)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[Relationship_VendTableRelationshipId](#Relationship_VendTableRelationshipId)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[Relationship_VendTable1RelationshipId](#Relationship_VendTable1RelationshipId)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RetailImportJournalTrans.md" target="_blank">Transaction/RetailImportJournalTrans</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailImportJournalTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#VendorItemId name="VendorItemId">VendorItemId</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendAccount1 name="VendAccount1">VendAccount1</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendAccount1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#error name="error">error</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the error attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#fabricComposition name="fabricComposition">fabricComposition</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the fabricComposition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#importedFileId name="importedFileId">importedFileId</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the importedFileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventColorId name="InventColorId">InventColorId</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventColorName name="InventColorName">InventColorName</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventColorName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventColorTxt name="InventColorTxt">InventColorTxt</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventColorTxt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventSizeId name="InventSizeId">InventSizeId</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventSizeName name="InventSizeName">InventSizeName</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventSizeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventSizeTxt name="InventSizeTxt">InventSizeTxt</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventSizeTxt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#inventStyleId name="inventStyleId">inventStyleId</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the inventStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventStyleName name="InventStyleName">InventStyleName</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventStyleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#inventStyleTxt name="inventStyleTxt">inventStyleTxt</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the inventStyleTxt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemBarCode name="ItemBarCode">ItemBarCode</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemBarCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemName name="ItemName">ItemName</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalId name="JournalId">JournalId</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#level1Name name="level1Name">level1Name</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the level1Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#level2Name name="level2Name">level2Name</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the level2Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#level3Name name="level3Name">level3Name</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the level3Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#level4Name name="level4Name">level4Name</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the level4Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#lineNum name="lineNum">lineNum</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the lineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#newBarcode name="newBarcode">newBarcode</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the newBarcode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#newItemNumber name="newItemNumber">newItemNumber</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the newItemNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#newVariant name="newVariant">newVariant</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the newVariant attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#priceCalculationType name="priceCalculationType">priceCalculationType</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the priceCalculationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#PriceChange name="PriceChange">PriceChange</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceChange attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#PurchPrice name="PurchPrice">PurchPrice</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PurchUnit name="PurchUnit">PurchUnit</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPrice name="SalesPrice">SalesPrice</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesUnit name="SalesUnit">SalesUnit</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#seasonCode name="seasonCode">seasonCode</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the seasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#suggestedRetailPrice name="suggestedRetailPrice">suggestedRetailPrice</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the suggestedRetailPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#unitPriceDate name="unitPriceDate">unitPriceDate</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the unitPriceDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#VendAccount name="VendAccount">VendAccount</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#vendorHirarchyLevel1 name="vendorHirarchyLevel1">vendorHirarchyLevel1</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the vendorHirarchyLevel1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#vendorHirarchyLevel2 name="vendorHirarchyLevel2">vendorHirarchyLevel2</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the vendorHirarchyLevel2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#vendorHirarchyLevel3 name="vendorHirarchyLevel3">vendorHirarchyLevel3</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the vendorHirarchyLevel3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#vendorHirarchyLevel4 name="vendorHirarchyLevel4">vendorHirarchyLevel4</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the vendorHirarchyLevel4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

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

### <a href=#Relationship_InventItemBarcodeRelationshipId name="Relationship_InventItemBarcodeRelationshipId">Relationship_InventItemBarcodeRelationshipId</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventItemBarcodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Main/InventItemBarcode.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/InventItemBarcode.cdm.json/InventItemBarcode</a></td><td><a href="../../../SupplyChain/Inventory/Main/InventItemBarcode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTableRelationshipId name="Relationship_InventTableRelationshipId">Relationship_InventTableRelationshipId</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/InventTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/InventTable.cdm.json/InventTable</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/InventTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTable1RelationshipId name="Relationship_InventTable1RelationshipId">Relationship_InventTable1RelationshipId</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTable1RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/InventTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/InventTable.cdm.json/InventTable</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/InventTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailImportJournalTableRelationshipId name="Relationship_RetailImportJournalTableRelationshipId">Relationship_RetailImportJournalTableRelationshipId</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailImportJournalTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailImportJournalTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Transaction/RetailImportJournalTable.cdm.json/RetailImportJournalTable</a></td><td><a href="RetailImportJournalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailImportTableRelationshipId name="Relationship_RetailImportTableRelationshipId">Relationship_RetailImportTableRelationshipId</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailImportTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailImportTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Transaction/RetailImportTable.cdm.json/RetailImportTable</a></td><td><a href="RetailImportTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailSeasonTableRelationshipId name="Relationship_RetailSeasonTableRelationshipId">Relationship_RetailSeasonTableRelationshipId</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailSeasonTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailSeasonTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Main/RetailSeasonTable.cdm.json/RetailSeasonTable</a></td><td><a href="../Main/RetailSeasonTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTableRelationshipId name="Relationship_VendTableRelationshipId">Relationship_VendTableRelationshipId</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTable1RelationshipId name="Relationship_VendTable1RelationshipId">Relationship_VendTable1RelationshipId</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTable1RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/RetailImportJournalTrans (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
