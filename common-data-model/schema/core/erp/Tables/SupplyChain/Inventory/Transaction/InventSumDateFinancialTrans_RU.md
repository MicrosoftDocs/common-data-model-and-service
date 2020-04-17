---
title: InventSumDateFinancialTrans_RU - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# InventSumDateFinancialTrans_RU

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/SupplyChain/Inventory/Transaction/InventSumDateFinancialTrans_RU.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventSumDateFinancialTrans_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="InventSumDateFinancialTrans_RU.md" target="_blank">Transaction/InventSumDateFinancialTrans_RU</a>|
|[AmountIssue](#AmountIssue)||<a href="InventSumDateFinancialTrans_RU.md" target="_blank">Transaction/InventSumDateFinancialTrans_RU</a>|
|[AmountReceipt](#AmountReceipt)||<a href="InventSumDateFinancialTrans_RU.md" target="_blank">Transaction/InventSumDateFinancialTrans_RU</a>|
|[FinancialDimId](#FinancialDimId)||<a href="InventSumDateFinancialTrans_RU.md" target="_blank">Transaction/InventSumDateFinancialTrans_RU</a>|
|[ItemId](#ItemId)||<a href="InventSumDateFinancialTrans_RU.md" target="_blank">Transaction/InventSumDateFinancialTrans_RU</a>|
|[ParmId](#ParmId)||<a href="InventSumDateFinancialTrans_RU.md" target="_blank">Transaction/InventSumDateFinancialTrans_RU</a>|
|[PhysicalAmountIssue](#PhysicalAmountIssue)||<a href="InventSumDateFinancialTrans_RU.md" target="_blank">Transaction/InventSumDateFinancialTrans_RU</a>|
|[PhysicalAmountReceipt](#PhysicalAmountReceipt)||<a href="InventSumDateFinancialTrans_RU.md" target="_blank">Transaction/InventSumDateFinancialTrans_RU</a>|
|[PhysicalQtyIssue](#PhysicalQtyIssue)||<a href="InventSumDateFinancialTrans_RU.md" target="_blank">Transaction/InventSumDateFinancialTrans_RU</a>|
|[PhysicalQtyReceipt](#PhysicalQtyReceipt)||<a href="InventSumDateFinancialTrans_RU.md" target="_blank">Transaction/InventSumDateFinancialTrans_RU</a>|
|[PhysicalTransferAmountIssue](#PhysicalTransferAmountIssue)||<a href="InventSumDateFinancialTrans_RU.md" target="_blank">Transaction/InventSumDateFinancialTrans_RU</a>|
|[PhysicalTransferAmountReceipt](#PhysicalTransferAmountReceipt)||<a href="InventSumDateFinancialTrans_RU.md" target="_blank">Transaction/InventSumDateFinancialTrans_RU</a>|
|[PhysicalTransferQtyIssue](#PhysicalTransferQtyIssue)||<a href="InventSumDateFinancialTrans_RU.md" target="_blank">Transaction/InventSumDateFinancialTrans_RU</a>|
|[PhysicalTransferQtyReceipt](#PhysicalTransferQtyReceipt)||<a href="InventSumDateFinancialTrans_RU.md" target="_blank">Transaction/InventSumDateFinancialTrans_RU</a>|
|[QtyIssue](#QtyIssue)||<a href="InventSumDateFinancialTrans_RU.md" target="_blank">Transaction/InventSumDateFinancialTrans_RU</a>|
|[QtyReceipt](#QtyReceipt)||<a href="InventSumDateFinancialTrans_RU.md" target="_blank">Transaction/InventSumDateFinancialTrans_RU</a>|
|[TransDate](#TransDate)||<a href="InventSumDateFinancialTrans_RU.md" target="_blank">Transaction/InventSumDateFinancialTrans_RU</a>|
|[TransferAmountIssue](#TransferAmountIssue)||<a href="InventSumDateFinancialTrans_RU.md" target="_blank">Transaction/InventSumDateFinancialTrans_RU</a>|
|[TransferAmountReceipt](#TransferAmountReceipt)||<a href="InventSumDateFinancialTrans_RU.md" target="_blank">Transaction/InventSumDateFinancialTrans_RU</a>|
|[TransferQtyIssue](#TransferQtyIssue)||<a href="InventSumDateFinancialTrans_RU.md" target="_blank">Transaction/InventSumDateFinancialTrans_RU</a>|
|[TransferQtyReceipt](#TransferQtyReceipt)||<a href="InventSumDateFinancialTrans_RU.md" target="_blank">Transaction/InventSumDateFinancialTrans_RU</a>|
|[DataAreaId](#DataAreaId)||<a href="InventSumDateFinancialTrans_RU.md" target="_blank">Transaction/InventSumDateFinancialTrans_RU</a>|
|[Relationship_InventSumDateFinancialDim_RURelationshipId](#Relationship_InventSumDateFinancialDim_RURelationshipId)||<a href="InventSumDateFinancialTrans_RU.md" target="_blank">Transaction/InventSumDateFinancialTrans_RU</a>|
|[Relationship_InventTableRelationshipId](#Relationship_InventTableRelationshipId)||<a href="InventSumDateFinancialTrans_RU.md" target="_blank">Transaction/InventSumDateFinancialTrans_RU</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="InventSumDateFinancialTrans_RU.md" target="_blank">Transaction/InventSumDateFinancialTrans_RU</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/InventSumDateFinancialTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventSumDateFinancialTrans_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AmountIssue name="AmountIssue">AmountIssue</a>

First included in: Transaction/InventSumDateFinancialTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountIssue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AmountReceipt name="AmountReceipt">AmountReceipt</a>

First included in: Transaction/InventSumDateFinancialTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountReceipt attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FinancialDimId name="FinancialDimId">FinancialDimId</a>

First included in: Transaction/InventSumDateFinancialTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinancialDimId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: Transaction/InventSumDateFinancialTrans_RU (this entity)  

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

### <a href=#ParmId name="ParmId">ParmId</a>

First included in: Transaction/InventSumDateFinancialTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParmId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalAmountIssue name="PhysicalAmountIssue">PhysicalAmountIssue</a>

First included in: Transaction/InventSumDateFinancialTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalAmountIssue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PhysicalAmountReceipt name="PhysicalAmountReceipt">PhysicalAmountReceipt</a>

First included in: Transaction/InventSumDateFinancialTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalAmountReceipt attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PhysicalQtyIssue name="PhysicalQtyIssue">PhysicalQtyIssue</a>

First included in: Transaction/InventSumDateFinancialTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalQtyIssue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PhysicalQtyReceipt name="PhysicalQtyReceipt">PhysicalQtyReceipt</a>

First included in: Transaction/InventSumDateFinancialTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalQtyReceipt attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PhysicalTransferAmountIssue name="PhysicalTransferAmountIssue">PhysicalTransferAmountIssue</a>

First included in: Transaction/InventSumDateFinancialTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalTransferAmountIssue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PhysicalTransferAmountReceipt name="PhysicalTransferAmountReceipt">PhysicalTransferAmountReceipt</a>

First included in: Transaction/InventSumDateFinancialTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalTransferAmountReceipt attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PhysicalTransferQtyIssue name="PhysicalTransferQtyIssue">PhysicalTransferQtyIssue</a>

First included in: Transaction/InventSumDateFinancialTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalTransferQtyIssue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PhysicalTransferQtyReceipt name="PhysicalTransferQtyReceipt">PhysicalTransferQtyReceipt</a>

First included in: Transaction/InventSumDateFinancialTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalTransferQtyReceipt attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#QtyIssue name="QtyIssue">QtyIssue</a>

First included in: Transaction/InventSumDateFinancialTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QtyIssue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#QtyReceipt name="QtyReceipt">QtyReceipt</a>

First included in: Transaction/InventSumDateFinancialTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QtyReceipt attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: Transaction/InventSumDateFinancialTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#TransferAmountIssue name="TransferAmountIssue">TransferAmountIssue</a>

First included in: Transaction/InventSumDateFinancialTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferAmountIssue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransferAmountReceipt name="TransferAmountReceipt">TransferAmountReceipt</a>

First included in: Transaction/InventSumDateFinancialTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferAmountReceipt attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransferQtyIssue name="TransferQtyIssue">TransferQtyIssue</a>

First included in: Transaction/InventSumDateFinancialTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferQtyIssue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransferQtyReceipt name="TransferQtyReceipt">TransferQtyReceipt</a>

First included in: Transaction/InventSumDateFinancialTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferQtyReceipt attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/InventSumDateFinancialTrans_RU (this entity)  

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

### <a href=#Relationship_InventSumDateFinancialDim_RURelationshipId name="Relationship_InventSumDateFinancialDim_RURelationshipId">Relationship_InventSumDateFinancialDim_RURelationshipId</a>

First included in: Transaction/InventSumDateFinancialTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventSumDateFinancialDim_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="InventSumDateFinancialDim_RU.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Transaction/InventSumDateFinancialDim_RU.cdm.json/InventSumDateFinancialDim_RU</a></td><td><a href="InventSumDateFinancialDim_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTableRelationshipId name="Relationship_InventTableRelationshipId">Relationship_InventTableRelationshipId</a>

First included in: Transaction/InventSumDateFinancialTrans_RU (this entity)  

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

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/InventSumDateFinancialTrans_RU (this entity)  

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
