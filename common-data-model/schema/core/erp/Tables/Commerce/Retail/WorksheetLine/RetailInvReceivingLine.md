---
title: RetailInvReceivingLine - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailInvReceivingLine

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Commerce/Retail/WorksheetLine/RetailInvReceivingLine.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailInvReceivingLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailInvReceivingLine.md" target="_blank">WorksheetLine/RetailInvReceivingLine</a>|
|[Barcode](#Barcode)||<a href="RetailInvReceivingLine.md" target="_blank">WorksheetLine/RetailInvReceivingLine</a>|
|[Color](#Color)||<a href="RetailInvReceivingLine.md" target="_blank">WorksheetLine/RetailInvReceivingLine</a>|
|[Configuration](#Configuration)||<a href="RetailInvReceivingLine.md" target="_blank">WorksheetLine/RetailInvReceivingLine</a>|
|[Date](#Date)||<a href="RetailInvReceivingLine.md" target="_blank">WorksheetLine/RetailInvReceivingLine</a>|
|[ItemName](#ItemName)||<a href="RetailInvReceivingLine.md" target="_blank">WorksheetLine/RetailInvReceivingLine</a>|
|[Itemnumber](#Itemnumber)||<a href="RetailInvReceivingLine.md" target="_blank">WorksheetLine/RetailInvReceivingLine</a>|
|[Ordered](#Ordered)||<a href="RetailInvReceivingLine.md" target="_blank">WorksheetLine/RetailInvReceivingLine</a>|
|[Ordernumber](#Ordernumber)||<a href="RetailInvReceivingLine.md" target="_blank">WorksheetLine/RetailInvReceivingLine</a>|
|[OrderType](#OrderType)||<a href="RetailInvReceivingLine.md" target="_blank">WorksheetLine/RetailInvReceivingLine</a>|
|[QtyReceiveNow](#QtyReceiveNow)||<a href="RetailInvReceivingLine.md" target="_blank">WorksheetLine/RetailInvReceivingLine</a>|
|[Received](#Received)||<a href="RetailInvReceivingLine.md" target="_blank">WorksheetLine/RetailInvReceivingLine</a>|
|[RefRecId](#RefRecId)||<a href="RetailInvReceivingLine.md" target="_blank">WorksheetLine/RetailInvReceivingLine</a>|
|[Serialnumber](#Serialnumber)||<a href="RetailInvReceivingLine.md" target="_blank">WorksheetLine/RetailInvReceivingLine</a>|
|[Size](#Size)||<a href="RetailInvReceivingLine.md" target="_blank">WorksheetLine/RetailInvReceivingLine</a>|
|[Style](#Style)||<a href="RetailInvReceivingLine.md" target="_blank">WorksheetLine/RetailInvReceivingLine</a>|
|[Unit](#Unit)||<a href="RetailInvReceivingLine.md" target="_blank">WorksheetLine/RetailInvReceivingLine</a>|
|[DataAreaId](#DataAreaId)||<a href="RetailInvReceivingLine.md" target="_blank">WorksheetLine/RetailInvReceivingLine</a>|
|[Relationship_EcoResColorRelationshipId](#Relationship_EcoResColorRelationshipId)||<a href="RetailInvReceivingLine.md" target="_blank">WorksheetLine/RetailInvReceivingLine</a>|
|[Relationship_EcoResConfigurationRelationshipId](#Relationship_EcoResConfigurationRelationshipId)||<a href="RetailInvReceivingLine.md" target="_blank">WorksheetLine/RetailInvReceivingLine</a>|
|[Relationship_EcoResSizeRelationshipId](#Relationship_EcoResSizeRelationshipId)||<a href="RetailInvReceivingLine.md" target="_blank">WorksheetLine/RetailInvReceivingLine</a>|
|[Relationship_EcoResStyleRelationshipId](#Relationship_EcoResStyleRelationshipId)||<a href="RetailInvReceivingLine.md" target="_blank">WorksheetLine/RetailInvReceivingLine</a>|
|[Relationship_InventItemBarcodeRelationshipId](#Relationship_InventItemBarcodeRelationshipId)||<a href="RetailInvReceivingLine.md" target="_blank">WorksheetLine/RetailInvReceivingLine</a>|
|[Relationship_InventSerialRelationshipId](#Relationship_InventSerialRelationshipId)||<a href="RetailInvReceivingLine.md" target="_blank">WorksheetLine/RetailInvReceivingLine</a>|
|[Relationship_InventTableRelationshipId](#Relationship_InventTableRelationshipId)||<a href="RetailInvReceivingLine.md" target="_blank">WorksheetLine/RetailInvReceivingLine</a>|
|[Relationship_InvReceivingTableRelationshipId](#Relationship_InvReceivingTableRelationshipId)||<a href="RetailInvReceivingLine.md" target="_blank">WorksheetLine/RetailInvReceivingLine</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RetailInvReceivingLine.md" target="_blank">WorksheetLine/RetailInvReceivingLine</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/RetailInvReceivingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailInvReceivingLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Barcode name="Barcode">Barcode</a>

First included in: WorksheetLine/RetailInvReceivingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Barcode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Color name="Color">Color</a>

First included in: WorksheetLine/RetailInvReceivingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Color attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Configuration name="Configuration">Configuration</a>

First included in: WorksheetLine/RetailInvReceivingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Configuration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Date name="Date">Date</a>

First included in: WorksheetLine/RetailInvReceivingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Date attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ItemName name="ItemName">ItemName</a>

First included in: WorksheetLine/RetailInvReceivingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Itemnumber name="Itemnumber">Itemnumber</a>

First included in: WorksheetLine/RetailInvReceivingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Itemnumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Ordered name="Ordered">Ordered</a>

First included in: WorksheetLine/RetailInvReceivingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Ordered attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Ordernumber name="Ordernumber">Ordernumber</a>

First included in: WorksheetLine/RetailInvReceivingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Ordernumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderType name="OrderType">OrderType</a>

First included in: WorksheetLine/RetailInvReceivingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#QtyReceiveNow name="QtyReceiveNow">QtyReceiveNow</a>

First included in: WorksheetLine/RetailInvReceivingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QtyReceiveNow attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Received name="Received">Received</a>

First included in: WorksheetLine/RetailInvReceivingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Received attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RefRecId name="RefRecId">RefRecId</a>

First included in: WorksheetLine/RetailInvReceivingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Serialnumber name="Serialnumber">Serialnumber</a>

First included in: WorksheetLine/RetailInvReceivingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Serialnumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Size name="Size">Size</a>

First included in: WorksheetLine/RetailInvReceivingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Size attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Style name="Style">Style</a>

First included in: WorksheetLine/RetailInvReceivingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Style attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Unit name="Unit">Unit</a>

First included in: WorksheetLine/RetailInvReceivingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Unit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/RetailInvReceivingLine (this entity)  

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

### <a href=#Relationship_EcoResColorRelationshipId name="Relationship_EcoResColorRelationshipId">Relationship_EcoResColorRelationshipId</a>

First included in: WorksheetLine/RetailInvReceivingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResColorRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResColor.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResColor.cdm.json/EcoResColor</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResColor.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EcoResConfigurationRelationshipId name="Relationship_EcoResConfigurationRelationshipId">Relationship_EcoResConfigurationRelationshipId</a>

First included in: WorksheetLine/RetailInvReceivingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResConfigurationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResConfiguration.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResConfiguration.cdm.json/EcoResConfiguration</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResConfiguration.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EcoResSizeRelationshipId name="Relationship_EcoResSizeRelationshipId">Relationship_EcoResSizeRelationshipId</a>

First included in: WorksheetLine/RetailInvReceivingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResSizeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResSize.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResSize.cdm.json/EcoResSize</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResSize.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EcoResStyleRelationshipId name="Relationship_EcoResStyleRelationshipId">Relationship_EcoResStyleRelationshipId</a>

First included in: WorksheetLine/RetailInvReceivingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResStyleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResStyle.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResStyle.cdm.json/EcoResStyle</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResStyle.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventItemBarcodeRelationshipId name="Relationship_InventItemBarcodeRelationshipId">Relationship_InventItemBarcodeRelationshipId</a>

First included in: WorksheetLine/RetailInvReceivingLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Main/InventItemBarcode.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Main/InventItemBarcode.cdm.json/InventItemBarcode</a></td><td><a href="../../../SupplyChain/Inventory/Main/InventItemBarcode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventSerialRelationshipId name="Relationship_InventSerialRelationshipId">Relationship_InventSerialRelationshipId</a>

First included in: WorksheetLine/RetailInvReceivingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventSerialRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/WorksheetHeader/InventSerial.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/WorksheetHeader/InventSerial.cdm.json/InventSerial</a></td><td><a href="../../../SupplyChain/Inventory/WorksheetHeader/InventSerial.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTableRelationshipId name="Relationship_InventTableRelationshipId">Relationship_InventTableRelationshipId</a>

First included in: WorksheetLine/RetailInvReceivingLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/InventTable.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/InventTable.cdm.json/InventTable</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/InventTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InvReceivingTableRelationshipId name="Relationship_InvReceivingTableRelationshipId">Relationship_InvReceivingTableRelationshipId</a>

First included in: WorksheetLine/RetailInvReceivingLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InvReceivingTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/RetailInvReceivingListTable.md" target="_blank">/core/erp/Tables/Commerce/Retail/WorksheetHeader/RetailInvReceivingListTable.cdm.json/RetailInvReceivingListTable</a></td><td><a href="../WorksheetHeader/RetailInvReceivingListTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/RetailInvReceivingLine (this entity)  

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
