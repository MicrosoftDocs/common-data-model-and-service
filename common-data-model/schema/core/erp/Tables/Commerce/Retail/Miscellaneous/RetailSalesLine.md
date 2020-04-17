---
title: RetailSalesLine - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailSalesLine

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailSalesLine.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailSalesLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[Catalog](#Catalog)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[LineDscAmount](#LineDscAmount)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[LineManualDiscountAmount](#LineManualDiscountAmount)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[LineManualDiscountPercentage](#LineManualDiscountPercentage)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[LinePercentageDiscount](#LinePercentageDiscount)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[ListingId](#ListingId)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[PeriodicDiscount](#PeriodicDiscount)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[PeriodicPercentageDiscount](#PeriodicPercentageDiscount)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[TotalDiscount](#TotalDiscount)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[TotalPctDiscount](#TotalPctDiscount)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[SalesLine](#SalesLine)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[FulfillmentStoreId](#FulfillmentStoreId)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[InventTransId](#InventTransId)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[ReturnReasonCodeId](#ReturnReasonCodeId)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[OriginalPrice](#OriginalPrice)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[PriceOverrideReasonCode](#PriceOverrideReasonCode)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[IsPriceOverridden](#IsPriceOverridden)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[FulfillmentStatus](#FulfillmentStatus)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[QuantityPicked](#QuantityPicked)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[QuantityPacked](#QuantityPacked)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[QuantityInvoiced](#QuantityInvoiced)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[InfocodeId](#InfocodeId)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[Information](#Information)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[SubInfocodeId](#SubInfocodeId)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[TenderDiscount](#TenderDiscount)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[TenderDiscountPercentage](#TenderDiscountPercentage)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[IsPriceKeyedIn](#IsPriceKeyedIn)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[DataAreaId](#DataAreaId)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[Relationship_CatalogRelationshipId](#Relationship_CatalogRelationshipId)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[Relationship_SalesLine1RelationshipId](#Relationship_SalesLine1RelationshipId)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[Relationship_ReturnReasonCodeRelationshipId](#Relationship_ReturnReasonCodeRelationshipId)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RetailSalesLine.md" target="_blank">Miscellaneous/RetailSalesLine</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailSalesLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Catalog name="Catalog">Catalog</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Catalog attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LineDscAmount name="LineDscAmount">LineDscAmount</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDscAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LineManualDiscountAmount name="LineManualDiscountAmount">LineManualDiscountAmount</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineManualDiscountAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LineManualDiscountPercentage name="LineManualDiscountPercentage">LineManualDiscountPercentage</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineManualDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LinePercentageDiscount name="LinePercentageDiscount">LinePercentageDiscount</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LinePercentageDiscount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ListingId name="ListingId">ListingId</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ListingId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodicDiscount name="PeriodicDiscount">PeriodicDiscount</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodicDiscount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PeriodicPercentageDiscount name="PeriodicPercentageDiscount">PeriodicPercentageDiscount</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodicPercentageDiscount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalDiscount name="TotalDiscount">TotalDiscount</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalPctDiscount name="TotalPctDiscount">TotalPctDiscount</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalPctDiscount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesLine name="SalesLine">SalesLine</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FulfillmentStoreId name="FulfillmentStoreId">FulfillmentStoreId</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FulfillmentStoreId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTransId name="InventTransId">InventTransId</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTransId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnReasonCodeId name="ReturnReasonCodeId">ReturnReasonCodeId</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnReasonCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginalPrice name="OriginalPrice">OriginalPrice</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PriceOverrideReasonCode name="PriceOverrideReasonCode">PriceOverrideReasonCode</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceOverrideReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPriceOverridden name="IsPriceOverridden">IsPriceOverridden</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPriceOverridden attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FulfillmentStatus name="FulfillmentStatus">FulfillmentStatus</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FulfillmentStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#QuantityPicked name="QuantityPicked">QuantityPicked</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuantityPicked attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#QuantityPacked name="QuantityPacked">QuantityPacked</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuantityPacked attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#QuantityInvoiced name="QuantityInvoiced">QuantityInvoiced</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuantityInvoiced attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InfocodeId name="InfocodeId">InfocodeId</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InfocodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Information name="Information">Information</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Information attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubInfocodeId name="SubInfocodeId">SubInfocodeId</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubInfocodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TenderDiscount name="TenderDiscount">TenderDiscount</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TenderDiscount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TenderDiscountPercentage name="TenderDiscountPercentage">TenderDiscountPercentage</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TenderDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#IsPriceKeyedIn name="IsPriceKeyedIn">IsPriceKeyedIn</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPriceKeyedIn attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

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

### <a href=#Relationship_CatalogRelationshipId name="Relationship_CatalogRelationshipId">Relationship_CatalogRelationshipId</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CatalogRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/Catalog.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/Catalog.cdm.json/Catalog</a></td><td><a href="../Main/Catalog.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesLine1RelationshipId name="Relationship_SalesLine1RelationshipId">Relationship_SalesLine1RelationshipId</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesLine1RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/SalesAndMarketing/WorksheetLine/SalesLine.md" target="_blank">/core/erp/Tables/SupplyChain/SalesAndMarketing/WorksheetLine/SalesLine.cdm.json/SalesLine</a></td><td><a href="../../../SupplyChain/SalesAndMarketing/WorksheetLine/SalesLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReturnReasonCodeRelationshipId name="Relationship_ReturnReasonCodeRelationshipId">Relationship_ReturnReasonCodeRelationshipId</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReturnReasonCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/SalesAndMarketing/Reference/ReturnReasonCode.md" target="_blank">/core/erp/Tables/SupplyChain/SalesAndMarketing/Reference/ReturnReasonCode.cdm.json/ReturnReasonCode</a></td><td><a href="../../../SupplyChain/SalesAndMarketing/Reference/ReturnReasonCode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/RetailSalesLine (this entity)  

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
