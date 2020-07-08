---
title: ConsignmentReplenishmentOrderLine in WorksheetLine - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Consignment replenishment order lines in WorksheetLine(ConsignmentReplenishmentOrderLine)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetLine/ConsignmentReplenishmentOrderLine.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ConsignmentReplenishmentOrderLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Consignment replenishment order lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ConsignmentReplenishmentOrderLine.md" target="_blank">WorksheetLine/ConsignmentReplenishmentOrderLine</a>|
|[AddressRefTableId](#AddressRefTableId)||<a href="ConsignmentReplenishmentOrderLine.md" target="_blank">WorksheetLine/ConsignmentReplenishmentOrderLine</a>|
|[AddressRefRecId](#AddressRefRecId)||<a href="ConsignmentReplenishmentOrderLine.md" target="_blank">WorksheetLine/ConsignmentReplenishmentOrderLine</a>|
|[ConfirmedDeliveryDate](#ConfirmedDeliveryDate)||<a href="ConsignmentReplenishmentOrderLine.md" target="_blank">WorksheetLine/ConsignmentReplenishmentOrderLine</a>|
|[DeliveryAddressName](#DeliveryAddressName)||<a href="ConsignmentReplenishmentOrderLine.md" target="_blank">WorksheetLine/ConsignmentReplenishmentOrderLine</a>|
|[DeliveryPostalAddress](#DeliveryPostalAddress)||<a href="ConsignmentReplenishmentOrderLine.md" target="_blank">WorksheetLine/ConsignmentReplenishmentOrderLine</a>|
|[InventDimId](#InventDimId)||<a href="ConsignmentReplenishmentOrderLine.md" target="_blank">WorksheetLine/ConsignmentReplenishmentOrderLine</a>|
|[ItemId](#ItemId)||<a href="ConsignmentReplenishmentOrderLine.md" target="_blank">WorksheetLine/ConsignmentReplenishmentOrderLine</a>|
|[InventTransId](#InventTransId)||<a href="ConsignmentReplenishmentOrderLine.md" target="_blank">WorksheetLine/ConsignmentReplenishmentOrderLine</a>|
|[LineNumber](#LineNumber)||<a href="ConsignmentReplenishmentOrderLine.md" target="_blank">WorksheetLine/ConsignmentReplenishmentOrderLine</a>|
|[ReplenishmentInventoryQuantity](#ReplenishmentInventoryQuantity)||<a href="ConsignmentReplenishmentOrderLine.md" target="_blank">WorksheetLine/ConsignmentReplenishmentOrderLine</a>|
|[ReplenishmentOrderLineStatus](#ReplenishmentOrderLineStatus)||<a href="ConsignmentReplenishmentOrderLine.md" target="_blank">WorksheetLine/ConsignmentReplenishmentOrderLine</a>|
|[ReplenishmentOrderNumber](#ReplenishmentOrderNumber)||<a href="ConsignmentReplenishmentOrderLine.md" target="_blank">WorksheetLine/ConsignmentReplenishmentOrderLine</a>|
|[ReplenishmentQuantity](#ReplenishmentQuantity)||<a href="ConsignmentReplenishmentOrderLine.md" target="_blank">WorksheetLine/ConsignmentReplenishmentOrderLine</a>|
|[ReplenishmentUnitId](#ReplenishmentUnitId)||<a href="ConsignmentReplenishmentOrderLine.md" target="_blank">WorksheetLine/ConsignmentReplenishmentOrderLine</a>|
|[RequestedDeliveryDate](#RequestedDeliveryDate)||<a href="ConsignmentReplenishmentOrderLine.md" target="_blank">WorksheetLine/ConsignmentReplenishmentOrderLine</a>|
|[RemainingInventoryPhysicalQuantity](#RemainingInventoryPhysicalQuantity)||<a href="ConsignmentReplenishmentOrderLine.md" target="_blank">WorksheetLine/ConsignmentReplenishmentOrderLine</a>|
|[RemainingReplenishmentPhysicalQuantity](#RemainingReplenishmentPhysicalQuantity)||<a href="ConsignmentReplenishmentOrderLine.md" target="_blank">WorksheetLine/ConsignmentReplenishmentOrderLine</a>|
|[ReceiveReplenishmentQuantityNow](#ReceiveReplenishmentQuantityNow)||<a href="ConsignmentReplenishmentOrderLine.md" target="_blank">WorksheetLine/ConsignmentReplenishmentOrderLine</a>|
|[ReceiveInventoryQuantityNow](#ReceiveInventoryQuantityNow)||<a href="ConsignmentReplenishmentOrderLine.md" target="_blank">WorksheetLine/ConsignmentReplenishmentOrderLine</a>|
|[DataAreaId](#DataAreaId)||<a href="ConsignmentReplenishmentOrderLine.md" target="_blank">WorksheetLine/ConsignmentReplenishmentOrderLine</a>|
|[Relationship_DeliveryPostalAddressRelationshipId](#Relationship_DeliveryPostalAddressRelationshipId)||<a href="ConsignmentReplenishmentOrderLine.md" target="_blank">WorksheetLine/ConsignmentReplenishmentOrderLine</a>|
|[Relationship_InventoryDimensionRelationshipId](#Relationship_InventoryDimensionRelationshipId)||<a href="ConsignmentReplenishmentOrderLine.md" target="_blank">WorksheetLine/ConsignmentReplenishmentOrderLine</a>|
|[Relationship_ItemRelationshipId](#Relationship_ItemRelationshipId)||<a href="ConsignmentReplenishmentOrderLine.md" target="_blank">WorksheetLine/ConsignmentReplenishmentOrderLine</a>|
|[Relationship_ReplenishmentOrderHeaderRelationshipId](#Relationship_ReplenishmentOrderHeaderRelationshipId)||<a href="ConsignmentReplenishmentOrderLine.md" target="_blank">WorksheetLine/ConsignmentReplenishmentOrderLine</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="ConsignmentReplenishmentOrderLine.md" target="_blank">WorksheetLine/ConsignmentReplenishmentOrderLine</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/ConsignmentReplenishmentOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ConsignmentReplenishmentOrderLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AddressRefTableId name="AddressRefTableId">AddressRefTableId</a>

First included in: WorksheetLine/ConsignmentReplenishmentOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressRefTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AddressRefRecId name="AddressRefRecId">AddressRefRecId</a>

First included in: WorksheetLine/ConsignmentReplenishmentOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressRefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ConfirmedDeliveryDate name="ConfirmedDeliveryDate">ConfirmedDeliveryDate</a>

First included in: WorksheetLine/ConsignmentReplenishmentOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfirmedDeliveryDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#DeliveryAddressName name="DeliveryAddressName">DeliveryAddressName</a>

First included in: WorksheetLine/ConsignmentReplenishmentOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryPostalAddress name="DeliveryPostalAddress">DeliveryPostalAddress</a>

First included in: WorksheetLine/ConsignmentReplenishmentOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryPostalAddress attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InventDimId name="InventDimId">InventDimId</a>

First included in: WorksheetLine/ConsignmentReplenishmentOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: WorksheetLine/ConsignmentReplenishmentOrderLine (this entity)  

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

### <a href=#InventTransId name="InventTransId">InventTransId</a>

First included in: WorksheetLine/ConsignmentReplenishmentOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTransId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: WorksheetLine/ConsignmentReplenishmentOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ReplenishmentInventoryQuantity name="ReplenishmentInventoryQuantity">ReplenishmentInventoryQuantity</a>

First included in: WorksheetLine/ConsignmentReplenishmentOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentInventoryQuantity attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReplenishmentOrderLineStatus name="ReplenishmentOrderLineStatus">ReplenishmentOrderLineStatus</a>

First included in: WorksheetLine/ConsignmentReplenishmentOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentOrderLineStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReplenishmentOrderNumber name="ReplenishmentOrderNumber">ReplenishmentOrderNumber</a>

First included in: WorksheetLine/ConsignmentReplenishmentOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentQuantity name="ReplenishmentQuantity">ReplenishmentQuantity</a>

First included in: WorksheetLine/ConsignmentReplenishmentOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentQuantity attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReplenishmentUnitId name="ReplenishmentUnitId">ReplenishmentUnitId</a>

First included in: WorksheetLine/ConsignmentReplenishmentOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentUnitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedDeliveryDate name="RequestedDeliveryDate">RequestedDeliveryDate</a>

First included in: WorksheetLine/ConsignmentReplenishmentOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedDeliveryDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#RemainingInventoryPhysicalQuantity name="RemainingInventoryPhysicalQuantity">RemainingInventoryPhysicalQuantity</a>

First included in: WorksheetLine/ConsignmentReplenishmentOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainingInventoryPhysicalQuantity attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RemainingReplenishmentPhysicalQuantity name="RemainingReplenishmentPhysicalQuantity">RemainingReplenishmentPhysicalQuantity</a>

First included in: WorksheetLine/ConsignmentReplenishmentOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainingReplenishmentPhysicalQuantity attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReceiveReplenishmentQuantityNow name="ReceiveReplenishmentQuantityNow">ReceiveReplenishmentQuantityNow</a>

First included in: WorksheetLine/ConsignmentReplenishmentOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiveReplenishmentQuantityNow attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReceiveInventoryQuantityNow name="ReceiveInventoryQuantityNow">ReceiveInventoryQuantityNow</a>

First included in: WorksheetLine/ConsignmentReplenishmentOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiveInventoryQuantityNow attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/ConsignmentReplenishmentOrderLine (this entity)  

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

### <a href=#Relationship_DeliveryPostalAddressRelationshipId name="Relationship_DeliveryPostalAddressRelationshipId">Relationship_DeliveryPostalAddressRelationshipId</a>

First included in: WorksheetLine/ConsignmentReplenishmentOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DeliveryPostalAddressRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/LogisticsPostalAddress.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/LogisticsPostalAddress.cdm.json/LogisticsPostalAddress</a></td><td><a href="../../../Common/GAB/Main/LogisticsPostalAddress.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventoryDimensionRelationshipId name="Relationship_InventoryDimensionRelationshipId">Relationship_InventoryDimensionRelationshipId</a>

First included in: WorksheetLine/ConsignmentReplenishmentOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventoryDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Main/InventDim.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/InventDim.cdm.json/InventDim</a></td><td><a href="../../Inventory/Main/InventDim.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ItemRelationshipId name="Relationship_ItemRelationshipId">Relationship_ItemRelationshipId</a>

First included in: WorksheetLine/ConsignmentReplenishmentOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ItemRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReplenishmentOrderHeaderRelationshipId name="Relationship_ReplenishmentOrderHeaderRelationshipId">Relationship_ReplenishmentOrderHeaderRelationshipId</a>

First included in: WorksheetLine/ConsignmentReplenishmentOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReplenishmentOrderHeaderRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/ConsignmentReplenishmentOrderHeader.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/ConsignmentReplenishmentOrderHeader.cdm.json/ConsignmentReplenishmentOrderHeader</a></td><td><a href="../WorksheetHeader/ConsignmentReplenishmentOrderHeader.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/ConsignmentReplenishmentOrderLine (this entity)  

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
