---
title: InventCostTrans in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Standard cost transactions in Transaction(InventCostTrans)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/InventCostTrans.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventCostTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Standard cost transactions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[AccruedQty](#AccruedQty)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[Canceled](#Canceled)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[COGSQty](#COGSQty)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[CostTransRefType](#CostTransRefType)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[CostTransState](#CostTransState)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[CostTransType](#CostTransType)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[DefaultDimension](#DefaultDimension)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[DeferredCOGSQty](#DeferredCOGSQty)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[FinancialInventDimId](#FinancialInventDimId)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[InventTransId](#InventTransId)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[InventTransIdReturn](#InventTransIdReturn)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[ItemId](#ItemId)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[ItemPriceRefRecId](#ItemPriceRefRecId)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[OnHandQty](#OnHandQty)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[TransDate](#TransDate)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[TransRefId](#TransRefId)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[VarianceQty](#VarianceQty)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[Voucher](#Voucher)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[WIPInQty](#WIPInQty)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[WIPOutQty](#WIPOutQty)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[DataAreaId](#DataAreaId)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[Relationship_DefaultDimensionRelationshipId](#Relationship_DefaultDimensionRelationshipId)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[Relationship_FinancialInventDimRelationshipId](#Relationship_FinancialInventDimRelationshipId)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[Relationship_InventItemPriceRelationshipId](#Relationship_InventItemPriceRelationshipId)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[Relationship_InventJournalTableRelationshipId](#Relationship_InventJournalTableRelationshipId)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[Relationship_InventQualityOrderRelationshipId](#Relationship_InventQualityOrderRelationshipId)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[Relationship_InventQuarantineOrderRelationshipId](#Relationship_InventQuarantineOrderRelationshipId)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[Relationship_InventTableRelationshipId](#Relationship_InventTableRelationshipId)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[Relationship_InventTransferTableRelationshipId](#Relationship_InventTransferTableRelationshipId)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[Relationship_InventTransOriginRelationshipId](#Relationship_InventTransOriginRelationshipId)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[Relationship_PlanReferenceRelationshipId](#Relationship_PlanReferenceRelationshipId)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[Relationship_ProdTableRelationshipId](#Relationship_ProdTableRelationshipId)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[Relationship_PurchTableRelationshipId](#Relationship_PurchTableRelationshipId)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[Relationship_ReturnInventTransOriginRelationshipId](#Relationship_ReturnInventTransOriginRelationshipId)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[Relationship_SalesTableRelationshipId](#Relationship_SalesTableRelationshipId)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[Relationship_WMSOrderRelationshipId](#Relationship_WMSOrderRelationshipId)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="InventCostTrans.md" target="_blank">Transaction/InventCostTrans</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventCostTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccruedQty name="AccruedQty">AccruedQty</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccruedQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Canceled name="Canceled">Canceled</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Canceled</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Canceled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Canceled</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#COGSQty name="COGSQty">COGSQty</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the COGSQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CostTransRefType name="CostTransRefType">CostTransRefType</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostTransRefType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CostTransState name="CostTransState">CostTransState</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostTransState attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CostTransType name="CostTransType">CostTransType</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostTransType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DeferredCOGSQty name="DeferredCOGSQty">DeferredCOGSQty</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeferredCOGSQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FinancialInventDimId name="FinancialInventDimId">FinancialInventDimId</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinancialInventDimId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTransId name="InventTransId">InventTransId</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTransId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTransIdReturn name="InventTransIdReturn">InventTransIdReturn</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTransIdReturn attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemPriceRefRecId name="ItemPriceRefRecId">ItemPriceRefRecId</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemPriceRefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OnHandQty name="OnHandQty">OnHandQty</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnHandQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#TransRefId name="TransRefId">TransRefId</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransRefId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VarianceQty name="VarianceQty">VarianceQty</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VarianceQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Voucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPInQty name="WIPInQty">WIPInQty</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPInQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#WIPOutQty name="WIPOutQty">WIPOutQty</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPOutQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/InventCostTrans (this entity)  

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

### <a href=#Relationship_DefaultDimensionRelationshipId name="Relationship_DefaultDimensionRelationshipId">Relationship_DefaultDimensionRelationshipId</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FinancialInventDimRelationshipId name="Relationship_FinancialInventDimRelationshipId">Relationship_FinancialInventDimRelationshipId</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FinancialInventDimRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/InventDim.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/InventDim.cdm.json/InventDim</a></td><td><a href="../Main/InventDim.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventItemPriceRelationshipId name="Relationship_InventItemPriceRelationshipId">Relationship_InventItemPriceRelationshipId</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventItemPriceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../TransactionHeader/InventItemPrice.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/TransactionHeader/InventItemPrice.cdm.json/InventItemPrice</a></td><td><a href="../TransactionHeader/InventItemPrice.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventJournalTableRelationshipId name="Relationship_InventJournalTableRelationshipId">Relationship_InventJournalTableRelationshipId</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventJournalTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/InventJournalTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/InventJournalTable.cdm.json/InventJournalTable</a></td><td><a href="../WorksheetHeader/InventJournalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventQualityOrderRelationshipId name="Relationship_InventQualityOrderRelationshipId">Relationship_InventQualityOrderRelationshipId</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventQualityOrderRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/InventQualityOrderTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/InventQualityOrderTable.cdm.json/InventQualityOrderTable</a></td><td><a href="../WorksheetHeader/InventQualityOrderTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventQuarantineOrderRelationshipId name="Relationship_InventQuarantineOrderRelationshipId">Relationship_InventQuarantineOrderRelationshipId</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventQuarantineOrderRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetLine/InventQuarantineOrder.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetLine/InventQuarantineOrder.cdm.json/InventQuarantineOrder</a></td><td><a href="../WorksheetLine/InventQuarantineOrder.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTableRelationshipId name="Relationship_InventTableRelationshipId">Relationship_InventTableRelationshipId</a>

First included in: Transaction/InventCostTrans (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductInformationManagement/Main/InventTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/InventTable.cdm.json/InventTable</a></td><td><a href="../../ProductInformationManagement/Main/InventTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTransferTableRelationshipId name="Relationship_InventTransferTableRelationshipId">Relationship_InventTransferTableRelationshipId</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTransferTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/InventTransferTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/InventTransferTable.cdm.json/InventTransferTable</a></td><td><a href="../WorksheetHeader/InventTransferTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTransOriginRelationshipId name="Relationship_InventTransOriginRelationshipId">Relationship_InventTransOriginRelationshipId</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTransOriginRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="InventTransOrigin.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/InventTransOrigin.cdm.json/InventTransOrigin</a></td><td><a href="InventTransOrigin.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PlanReferenceRelationshipId name="Relationship_PlanReferenceRelationshipId">Relationship_PlanReferenceRelationshipId</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PlanReferenceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../MasterPlanning/Main/PlanReference.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Main/PlanReference.cdm.json/PlanReference</a></td><td><a href="../../MasterPlanning/Main/PlanReference.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProdTableRelationshipId name="Relationship_ProdTableRelationshipId">Relationship_ProdTableRelationshipId</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProdTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductionControl/WorksheetHeader/ProdTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/WorksheetHeader/ProdTable.cdm.json/ProdTable</a></td><td><a href="../../ProductionControl/WorksheetHeader/ProdTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchTableRelationshipId name="Relationship_PurchTableRelationshipId">Relationship_PurchTableRelationshipId</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProcurementAndSourcing/WorksheetHeader/PurchTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchTable.cdm.json/PurchTable</a></td><td><a href="../../ProcurementAndSourcing/WorksheetHeader/PurchTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReturnInventTransOriginRelationshipId name="Relationship_ReturnInventTransOriginRelationshipId">Relationship_ReturnInventTransOriginRelationshipId</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReturnInventTransOriginRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="InventTransOrigin.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/InventTransOrigin.cdm.json/InventTransOrigin</a></td><td><a href="InventTransOrigin.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesTableRelationshipId name="Relationship_SalesTableRelationshipId">Relationship_SalesTableRelationshipId</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/WorksheetHeader/SalesTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/SalesTable.cdm.json/SalesTable</a></td><td><a href="../../SalesAndMarketing/WorksheetHeader/SalesTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WMSOrderRelationshipId name="Relationship_WMSOrderRelationshipId">Relationship_WMSOrderRelationshipId</a>

First included in: Transaction/InventCostTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WMSOrderRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/WMSOrder.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/WMSOrder.cdm.json/WMSOrder</a></td><td><a href="../WorksheetHeader/WMSOrder.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/InventCostTrans (this entity)  

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
