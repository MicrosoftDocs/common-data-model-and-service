---
title: WHSDocumentRoutingPrinterEntity in WMS - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Document routing printers in WMS(WHSDocumentRoutingPrinterEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WHSDocumentRoutingPrinterEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Document routing printers</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DocumentRouting](#DocumentRouting)||<a href="WHSDocumentRoutingPrinterEntity.md" target="_blank">WMS/WHSDocumentRoutingPrinterEntity</a>|
|[DocumentRoutingPrinterLayoutId](#DocumentRoutingPrinterLayoutId)||<a href="WHSDocumentRoutingPrinterEntity.md" target="_blank">WMS/WHSDocumentRoutingPrinterEntity</a>|
|[DocumentRoutingPrinterName](#DocumentRoutingPrinterName)||<a href="WHSDocumentRoutingPrinterEntity.md" target="_blank">WMS/WHSDocumentRoutingPrinterEntity</a>|
|[DocumentRoutingWarehouseId](#DocumentRoutingWarehouseId)||<a href="WHSDocumentRoutingPrinterEntity.md" target="_blank">WMS/WHSDocumentRoutingPrinterEntity</a>|
|[DocumentRoutingSequence](#DocumentRoutingSequence)||<a href="WHSDocumentRoutingPrinterEntity.md" target="_blank">WMS/WHSDocumentRoutingPrinterEntity</a>|
|[DocumentRoutingWorkOrderType](#DocumentRoutingWorkOrderType)||<a href="WHSDocumentRoutingPrinterEntity.md" target="_blank">WMS/WHSDocumentRoutingPrinterEntity</a>|
|[Relationship_DocumentRoutingPrinterLayoutRelationshipId](#Relationship_DocumentRoutingPrinterLayoutRelationshipId)||<a href="WHSDocumentRoutingPrinterEntity.md" target="_blank">WMS/WHSDocumentRoutingPrinterEntity</a>|
|[Relationship_PurchaseOrderDocumentRoutingV2RelationshipId](#Relationship_PurchaseOrderDocumentRoutingV2RelationshipId)||<a href="WHSDocumentRoutingPrinterEntity.md" target="_blank">WMS/WHSDocumentRoutingPrinterEntity</a>|
|[Relationship_ReturnOrderDocumentRoutingV2RelationshipId](#Relationship_ReturnOrderDocumentRoutingV2RelationshipId)||<a href="WHSDocumentRoutingPrinterEntity.md" target="_blank">WMS/WHSDocumentRoutingPrinterEntity</a>|
|[Relationship_SalesOrderDocumentRoutingV2RelationshipId](#Relationship_SalesOrderDocumentRoutingV2RelationshipId)||<a href="WHSDocumentRoutingPrinterEntity.md" target="_blank">WMS/WHSDocumentRoutingPrinterEntity</a>|
|[Relationship_WarehouseOrderDocumentRoutingProdPickV2RelationshipId](#Relationship_WarehouseOrderDocumentRoutingProdPickV2RelationshipId)||<a href="WHSDocumentRoutingPrinterEntity.md" target="_blank">WMS/WHSDocumentRoutingPrinterEntity</a>|
|[Relationship_WarehouseOrderDocumentRoutingProdPutV2RelationshipId](#Relationship_WarehouseOrderDocumentRoutingProdPutV2RelationshipId)||<a href="WHSDocumentRoutingPrinterEntity.md" target="_blank">WMS/WHSDocumentRoutingPrinterEntity</a>|
|[Relationship_WarehouseOrderDocumentRoutingProdProcessPutV2RelationshipId](#Relationship_WarehouseOrderDocumentRoutingProdProcessPutV2RelationshipId)||<a href="WHSDocumentRoutingPrinterEntity.md" target="_blank">WMS/WHSDocumentRoutingPrinterEntity</a>|
|[Relationship_WarehouseOrderDocumentRoutingTransferIssueV2RelationshipId](#Relationship_WarehouseOrderDocumentRoutingTransferIssueV2RelationshipId)||<a href="WHSDocumentRoutingPrinterEntity.md" target="_blank">WMS/WHSDocumentRoutingPrinterEntity</a>|
|[Relationship_WarehouseOrderDocumentRoutingTransferReceiptV2RelationshipId](#Relationship_WarehouseOrderDocumentRoutingTransferReceiptV2RelationshipId)||<a href="WHSDocumentRoutingPrinterEntity.md" target="_blank">WMS/WHSDocumentRoutingPrinterEntity</a>|
|[Relationship_WarehouseOrderDocumentRoutingInventV2RelationshipId](#Relationship_WarehouseOrderDocumentRoutingInventV2RelationshipId)||<a href="WHSDocumentRoutingPrinterEntity.md" target="_blank">WMS/WHSDocumentRoutingPrinterEntity</a>|
|[Relationship_WarehouseOrderDocumentRoutingWorkCancelV2RelationshipId](#Relationship_WarehouseOrderDocumentRoutingWorkCancelV2RelationshipId)||<a href="WHSDocumentRoutingPrinterEntity.md" target="_blank">WMS/WHSDocumentRoutingPrinterEntity</a>|
|[Relationship_WarehouseOrderDocumentRoutingCycleCountV2RelationshipId](#Relationship_WarehouseOrderDocumentRoutingCycleCountV2RelationshipId)||<a href="WHSDocumentRoutingPrinterEntity.md" target="_blank">WMS/WHSDocumentRoutingPrinterEntity</a>|
|[Relationship_WarehouseOrderDocumentRoutingReplenishmentV2RelationshipId](#Relationship_WarehouseOrderDocumentRoutingReplenishmentV2RelationshipId)||<a href="WHSDocumentRoutingPrinterEntity.md" target="_blank">WMS/WHSDocumentRoutingPrinterEntity</a>|
|[Relationship_WarehouseOrderDocumentRoutingKanbanPutV2RelationshipId](#Relationship_WarehouseOrderDocumentRoutingKanbanPutV2RelationshipId)||<a href="WHSDocumentRoutingPrinterEntity.md" target="_blank">WMS/WHSDocumentRoutingPrinterEntity</a>|
|[Relationship_WarehouseOrderDocumentRoutingKanbanPickV2RelationshipId](#Relationship_WarehouseOrderDocumentRoutingKanbanPickV2RelationshipId)||<a href="WHSDocumentRoutingPrinterEntity.md" target="_blank">WMS/WHSDocumentRoutingPrinterEntity</a>|
|[Relationship_WarehouseOrderDocumentRoutingCycleCountAcceptedV2RelationshipId](#Relationship_WarehouseOrderDocumentRoutingCycleCountAcceptedV2RelationshipId)||<a href="WHSDocumentRoutingPrinterEntity.md" target="_blank">WMS/WHSDocumentRoutingPrinterEntity</a>|
|[Relationship_WarehouseOrderDocumentRoutingPackedContainerPickingV2RelationshipId](#Relationship_WarehouseOrderDocumentRoutingPackedContainerPickingV2RelationshipId)||<a href="WHSDocumentRoutingPrinterEntity.md" target="_blank">WMS/WHSDocumentRoutingPrinterEntity</a>|
|[BackingTable_WHSDocumentRoutingLineRelationshipId](#BackingTable_WHSDocumentRoutingLineRelationshipId)||<a href="WHSDocumentRoutingPrinterEntity.md" target="_blank">WMS/WHSDocumentRoutingPrinterEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSDocumentRoutingPrinterEntity.md" target="_blank">WMS/WHSDocumentRoutingPrinterEntity</a>|

### <a href=#DocumentRouting name="DocumentRouting">DocumentRouting</a>

First included in: WMS/WHSDocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentRouting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentRoutingPrinterLayoutId name="DocumentRoutingPrinterLayoutId">DocumentRoutingPrinterLayoutId</a>

First included in: WMS/WHSDocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentRoutingPrinterLayoutId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentRoutingPrinterName name="DocumentRoutingPrinterName">DocumentRoutingPrinterName</a>

First included in: WMS/WHSDocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentRoutingPrinterName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentRoutingWarehouseId name="DocumentRoutingWarehouseId">DocumentRoutingWarehouseId</a>

First included in: WMS/WHSDocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentRoutingWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentRoutingSequence name="DocumentRoutingSequence">DocumentRoutingSequence</a>

First included in: WMS/WHSDocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentRoutingSequence attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentRoutingWorkOrderType name="DocumentRoutingWorkOrderType">DocumentRoutingWorkOrderType</a>

First included in: WMS/WHSDocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentRoutingWorkOrderType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DocumentRoutingPrinterLayoutRelationshipId name="Relationship_DocumentRoutingPrinterLayoutRelationshipId">Relationship_DocumentRoutingPrinterLayoutRelationshipId</a>

First included in: WMS/WHSDocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DocumentRoutingPrinterLayoutRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PurchaseOrderDocumentRoutingV2RelationshipId name="Relationship_PurchaseOrderDocumentRoutingV2RelationshipId">Relationship_PurchaseOrderDocumentRoutingV2RelationshipId</a>

First included in: WMS/WHSDocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchaseOrderDocumentRoutingV2RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReturnOrderDocumentRoutingV2RelationshipId name="Relationship_ReturnOrderDocumentRoutingV2RelationshipId">Relationship_ReturnOrderDocumentRoutingV2RelationshipId</a>

First included in: WMS/WHSDocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReturnOrderDocumentRoutingV2RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SalesOrderDocumentRoutingV2RelationshipId name="Relationship_SalesOrderDocumentRoutingV2RelationshipId">Relationship_SalesOrderDocumentRoutingV2RelationshipId</a>

First included in: WMS/WHSDocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesOrderDocumentRoutingV2RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseOrderDocumentRoutingProdPickV2RelationshipId name="Relationship_WarehouseOrderDocumentRoutingProdPickV2RelationshipId">Relationship_WarehouseOrderDocumentRoutingProdPickV2RelationshipId</a>

First included in: WMS/WHSDocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseOrderDocumentRoutingProdPickV2RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseOrderDocumentRoutingProdPutV2RelationshipId name="Relationship_WarehouseOrderDocumentRoutingProdPutV2RelationshipId">Relationship_WarehouseOrderDocumentRoutingProdPutV2RelationshipId</a>

First included in: WMS/WHSDocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseOrderDocumentRoutingProdPutV2RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseOrderDocumentRoutingProdProcessPutV2RelationshipId name="Relationship_WarehouseOrderDocumentRoutingProdProcessPutV2RelationshipId">Relationship_WarehouseOrderDocumentRoutingProdProcessPutV2RelationshipId</a>

First included in: WMS/WHSDocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseOrderDocumentRoutingProdProcessPutV2RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseOrderDocumentRoutingTransferIssueV2RelationshipId name="Relationship_WarehouseOrderDocumentRoutingTransferIssueV2RelationshipId">Relationship_WarehouseOrderDocumentRoutingTransferIssueV2RelationshipId</a>

First included in: WMS/WHSDocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseOrderDocumentRoutingTransferIssueV2RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseOrderDocumentRoutingTransferReceiptV2RelationshipId name="Relationship_WarehouseOrderDocumentRoutingTransferReceiptV2RelationshipId">Relationship_WarehouseOrderDocumentRoutingTransferReceiptV2RelationshipId</a>

First included in: WMS/WHSDocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseOrderDocumentRoutingTransferReceiptV2RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseOrderDocumentRoutingInventV2RelationshipId name="Relationship_WarehouseOrderDocumentRoutingInventV2RelationshipId">Relationship_WarehouseOrderDocumentRoutingInventV2RelationshipId</a>

First included in: WMS/WHSDocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseOrderDocumentRoutingInventV2RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseOrderDocumentRoutingWorkCancelV2RelationshipId name="Relationship_WarehouseOrderDocumentRoutingWorkCancelV2RelationshipId">Relationship_WarehouseOrderDocumentRoutingWorkCancelV2RelationshipId</a>

First included in: WMS/WHSDocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseOrderDocumentRoutingWorkCancelV2RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseOrderDocumentRoutingCycleCountV2RelationshipId name="Relationship_WarehouseOrderDocumentRoutingCycleCountV2RelationshipId">Relationship_WarehouseOrderDocumentRoutingCycleCountV2RelationshipId</a>

First included in: WMS/WHSDocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseOrderDocumentRoutingCycleCountV2RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseOrderDocumentRoutingReplenishmentV2RelationshipId name="Relationship_WarehouseOrderDocumentRoutingReplenishmentV2RelationshipId">Relationship_WarehouseOrderDocumentRoutingReplenishmentV2RelationshipId</a>

First included in: WMS/WHSDocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseOrderDocumentRoutingReplenishmentV2RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseOrderDocumentRoutingKanbanPutV2RelationshipId name="Relationship_WarehouseOrderDocumentRoutingKanbanPutV2RelationshipId">Relationship_WarehouseOrderDocumentRoutingKanbanPutV2RelationshipId</a>

First included in: WMS/WHSDocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseOrderDocumentRoutingKanbanPutV2RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseOrderDocumentRoutingKanbanPickV2RelationshipId name="Relationship_WarehouseOrderDocumentRoutingKanbanPickV2RelationshipId">Relationship_WarehouseOrderDocumentRoutingKanbanPickV2RelationshipId</a>

First included in: WMS/WHSDocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseOrderDocumentRoutingKanbanPickV2RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseOrderDocumentRoutingCycleCountAcceptedV2RelationshipId name="Relationship_WarehouseOrderDocumentRoutingCycleCountAcceptedV2RelationshipId">Relationship_WarehouseOrderDocumentRoutingCycleCountAcceptedV2RelationshipId</a>

First included in: WMS/WHSDocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseOrderDocumentRoutingCycleCountAcceptedV2RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseOrderDocumentRoutingPackedContainerPickingV2RelationshipId name="Relationship_WarehouseOrderDocumentRoutingPackedContainerPickingV2RelationshipId">Relationship_WarehouseOrderDocumentRoutingPackedContainerPickingV2RelationshipId</a>

First included in: WMS/WHSDocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseOrderDocumentRoutingPackedContainerPickingV2RelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_WHSDocumentRoutingLineRelationshipId name="BackingTable_WHSDocumentRoutingLineRelationshipId">BackingTable_WHSDocumentRoutingLineRelationshipId</a>

First included in: WMS/WHSDocumentRoutingPrinterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSDocumentRoutingLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Group/WHSDocumentRoutingLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/WHSDocumentRoutingLine.cdm.json/WHSDocumentRoutingLine</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Group/WHSDocumentRoutingLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WHSDocumentRoutingPrinterEntity (this entity)  

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
