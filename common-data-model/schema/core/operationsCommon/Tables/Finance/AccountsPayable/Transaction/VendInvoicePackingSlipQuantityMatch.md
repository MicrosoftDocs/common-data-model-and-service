---
title: VendInvoicePackingSlipQuantityMatch - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/30/2020
ms.author: nebanfic
---

# Vendor invoice - product receipt line connections

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/AccountsPayable/Transaction/VendInvoicePackingSlipQuantityMatch.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendInvoicePackingSlipQuantityMatch/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor invoice - product receipt line connections</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="VendInvoicePackingSlipQuantityMatch.md" target="_blank">Transaction/VendInvoicePackingSlipQuantityMatch</a>|
|[InventQuantity](#InventQuantity)||<a href="VendInvoicePackingSlipQuantityMatch.md" target="_blank">Transaction/VendInvoicePackingSlipQuantityMatch</a>|
|[InvoiceSourceDocumentLIne](#InvoiceSourceDocumentLIne)||<a href="VendInvoicePackingSlipQuantityMatch.md" target="_blank">Transaction/VendInvoicePackingSlipQuantityMatch</a>|
|[PackingSlipSourceDocumentLine](#PackingSlipSourceDocumentLine)||<a href="VendInvoicePackingSlipQuantityMatch.md" target="_blank">Transaction/VendInvoicePackingSlipQuantityMatch</a>|
|[PdsCWQuantity](#PdsCWQuantity)||<a href="VendInvoicePackingSlipQuantityMatch.md" target="_blank">Transaction/VendInvoicePackingSlipQuantityMatch</a>|
|[Quantity](#Quantity)||<a href="VendInvoicePackingSlipQuantityMatch.md" target="_blank">Transaction/VendInvoicePackingSlipQuantityMatch</a>|
|[Relationship_VendInvoiceTransRelationshipId](#Relationship_VendInvoiceTransRelationshipId)||<a href="VendInvoicePackingSlipQuantityMatch.md" target="_blank">Transaction/VendInvoicePackingSlipQuantityMatch</a>|
|[Relationship_VendPackingSlipTransRelationshipId](#Relationship_VendPackingSlipTransRelationshipId)||<a href="VendInvoicePackingSlipQuantityMatch.md" target="_blank">Transaction/VendInvoicePackingSlipQuantityMatch</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/VendInvoicePackingSlipQuantityMatch (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendInvoicePackingSlipQuantityMatch/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InventQuantity name="InventQuantity">InventQuantity</a>

First included in: Transaction/VendInvoicePackingSlipQuantityMatch (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventQuantity attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InvoiceSourceDocumentLIne name="InvoiceSourceDocumentLIne">InvoiceSourceDocumentLIne</a>

First included in: Transaction/VendInvoicePackingSlipQuantityMatch (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceSourceDocumentLIne attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PackingSlipSourceDocumentLine name="PackingSlipSourceDocumentLine">PackingSlipSourceDocumentLine</a>

First included in: Transaction/VendInvoicePackingSlipQuantityMatch (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingSlipSourceDocumentLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PdsCWQuantity name="PdsCWQuantity">PdsCWQuantity</a>

First included in: Transaction/VendInvoicePackingSlipQuantityMatch (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsCWQuantity attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: Transaction/VendInvoicePackingSlipQuantityMatch (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Relationship_VendInvoiceTransRelationshipId name="Relationship_VendInvoiceTransRelationshipId">Relationship_VendInvoiceTransRelationshipId</a>

First included in: Transaction/VendInvoicePackingSlipQuantityMatch (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendInvoiceTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="VendInvoiceTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Transaction/VendInvoiceTrans.cdm.json/VendInvoiceTrans</a></td><td><a href="VendInvoiceTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendPackingSlipTransRelationshipId name="Relationship_VendPackingSlipTransRelationshipId">Relationship_VendPackingSlipTransRelationshipId</a>

First included in: Transaction/VendInvoicePackingSlipQuantityMatch (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendPackingSlipTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProcurementAndSourcing/Transaction/VendPackingSlipTrans.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Transaction/VendPackingSlipTrans.cdm.json/VendPackingSlipTrans</a></td><td><a href="../../../SupplyChain/ProcurementAndSourcing/Transaction/VendPackingSlipTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
