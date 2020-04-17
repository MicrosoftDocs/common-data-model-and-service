---
title: PurchaseOrderResponseLineHistory - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# PurchaseOrderResponseLineHistory

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/SupplyChain/ProcurementAndSourcing/TransactionLine/PurchaseOrderResponseLineHistory.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchaseOrderResponseLineHistory/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[ValidTo](#ValidTo)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[ValidFrom](#ValidFrom)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[ExternalItemId](#ExternalItemId)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[ItemId](#ItemId)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[ProcurementCategory](#ProcurementCategory)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[Name](#Name)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[InventDimId](#InventDimId)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[DeliveryDate](#DeliveryDate)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[ConfirmedDlv](#ConfirmedDlv)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[PurchQty](#PurchQty)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[PurchPrice](#PurchPrice)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[PriceUnit](#PriceUnit)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[PurchUnit](#PurchUnit)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[LineDisc](#LineDisc)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[LinePercent](#LinePercent)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[LineAmount](#LineAmount)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[DeliveryPostalAddress](#DeliveryPostalAddress)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[PurchaseOrderResponseLine](#PurchaseOrderResponseLine)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[PurchLine](#PurchLine)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[LineNumber](#LineNumber)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[PurchaseOrderResponseHeaderHistory](#PurchaseOrderResponseHeaderHistory)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[PurchaseOrderResponseHeader](#PurchaseOrderResponseHeader)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[LineState](#LineState)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[Delivering](#Delivering)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[ConsumptionState](#ConsumptionState)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[DataAreaId](#DataAreaId)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[Relationship_InventTableRelationshipId](#Relationship_InventTableRelationshipId)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[Relationship_ProcurementCategoryRelationshipId](#Relationship_ProcurementCategoryRelationshipId)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[Relationship_InventDimRelationshipId](#Relationship_InventDimRelationshipId)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[Relationship_PurchaseOrderResponseLineRelationshipId](#Relationship_PurchaseOrderResponseLineRelationshipId)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[Relationship_PurchLineRelationshipId](#Relationship_PurchLineRelationshipId)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[Relationship_PurchaseOrderResponseHeaderHistoryRelationshipId](#Relationship_PurchaseOrderResponseHeaderHistoryRelationshipId)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[Relationship_PurchaseOrderResponseHeaderRelationshipId](#Relationship_PurchaseOrderResponseHeaderRelationshipId)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="PurchaseOrderResponseLineHistory.md" target="_blank">TransactionLine/PurchaseOrderResponseLineHistory</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchaseOrderResponseLineHistory/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#ExternalItemId name="ExternalItemId">ExternalItemId</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcurementCategory name="ProcurementCategory">ProcurementCategory</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementCategory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventDimId name="InventDimId">InventDimId</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryDate name="DeliveryDate">DeliveryDate</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#ConfirmedDlv name="ConfirmedDlv">ConfirmedDlv</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfirmedDlv attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#PurchQty name="PurchQty">PurchQty</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PurchPrice name="PurchPrice">PurchPrice</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

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

### <a href=#PriceUnit name="PriceUnit">PriceUnit</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceUnit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PurchUnit name="PurchUnit">PurchUnit</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDisc name="LineDisc">LineDisc</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDisc attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LinePercent name="LinePercent">LinePercent</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LinePercent attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LineAmount name="LineAmount">LineAmount</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DeliveryPostalAddress name="DeliveryPostalAddress">DeliveryPostalAddress</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryPostalAddress attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PurchaseOrderResponseLine name="PurchaseOrderResponseLine">PurchaseOrderResponseLine</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderResponseLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PurchLine name="PurchLine">PurchLine</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PurchaseOrderResponseHeaderHistory name="PurchaseOrderResponseHeaderHistory">PurchaseOrderResponseHeaderHistory</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderResponseHeaderHistory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PurchaseOrderResponseHeader name="PurchaseOrderResponseHeader">PurchaseOrderResponseHeader</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderResponseHeader attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LineState name="LineState">LineState</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineState attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Delivering name="Delivering">Delivering</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Delivering attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ConsumptionState name="ConsumptionState">ConsumptionState</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsumptionState attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

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

### <a href=#Relationship_InventTableRelationshipId name="Relationship_InventTableRelationshipId">Relationship_InventTableRelationshipId</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductInformationManagement/Main/InventTable.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/InventTable.cdm.json/InventTable</a></td><td><a href="../../ProductInformationManagement/Main/InventTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProcurementCategoryRelationshipId name="Relationship_ProcurementCategoryRelationshipId">Relationship_ProcurementCategoryRelationshipId</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProcurementCategoryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductInformationManagement/Main/EcoResCategory.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResCategory.cdm.json/EcoResCategory</a></td><td><a href="../../ProductInformationManagement/Main/EcoResCategory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventDimRelationshipId name="Relationship_InventDimRelationshipId">Relationship_InventDimRelationshipId</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventDimRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Main/InventDim.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Main/InventDim.cdm.json/InventDim</a></td><td><a href="../../Inventory/Main/InventDim.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchaseOrderResponseLineRelationshipId name="Relationship_PurchaseOrderResponseLineRelationshipId">Relationship_PurchaseOrderResponseLineRelationshipId</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchaseOrderResponseLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetLine/PurchaseOrderResponseLine.md" target="_blank">/core/erp/Tables/SupplyChain/ProcurementAndSourcing/WorksheetLine/PurchaseOrderResponseLine.cdm.json/PurchaseOrderResponseLine</a></td><td><a href="../WorksheetLine/PurchaseOrderResponseLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchLineRelationshipId name="Relationship_PurchLineRelationshipId">Relationship_PurchLineRelationshipId</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetLine/PurchLine.md" target="_blank">/core/erp/Tables/SupplyChain/ProcurementAndSourcing/WorksheetLine/PurchLine.cdm.json/PurchLine</a></td><td><a href="../WorksheetLine/PurchLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchaseOrderResponseHeaderHistoryRelationshipId name="Relationship_PurchaseOrderResponseHeaderHistoryRelationshipId">Relationship_PurchaseOrderResponseHeaderHistoryRelationshipId</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchaseOrderResponseHeaderHistoryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../TransactionHeader/PurchaseOrderResponseHeaderHistory.md" target="_blank">/core/erp/Tables/SupplyChain/ProcurementAndSourcing/TransactionHeader/PurchaseOrderResponseHeaderHistory.cdm.json/PurchaseOrderResponseHeaderHistory</a></td><td><a href="../TransactionHeader/PurchaseOrderResponseHeaderHistory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchaseOrderResponseHeaderRelationshipId name="Relationship_PurchaseOrderResponseHeaderRelationshipId">Relationship_PurchaseOrderResponseHeaderRelationshipId</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchaseOrderResponseHeaderRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/PurchaseOrderResponseHeader.md" target="_blank">/core/erp/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchaseOrderResponseHeader.cdm.json/PurchaseOrderResponseHeader</a></td><td><a href="../WorksheetHeader/PurchaseOrderResponseHeader.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: TransactionLine/PurchaseOrderResponseLineHistory (this entity)  

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
