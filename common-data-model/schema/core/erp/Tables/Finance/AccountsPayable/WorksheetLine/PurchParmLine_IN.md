---
title: PurchParmLine_IN - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# PurchParmLine_IN

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/AccountsPayable/WorksheetLine/PurchParmLine_IN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchParmLine_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PurchParmLine_IN.md" target="_blank">WorksheetLine/PurchParmLine_IN</a>|
|[AssessableValueAccountingCurrency](#AssessableValueAccountingCurrency)||<a href="PurchParmLine_IN.md" target="_blank">WorksheetLine/PurchParmLine_IN</a>|
|[InventSiteGateEntryLine](#InventSiteGateEntryLine)||<a href="PurchParmLine_IN.md" target="_blank">WorksheetLine/PurchParmLine_IN</a>|
|[PurchParmLine](#PurchParmLine)||<a href="PurchParmLine_IN.md" target="_blank">WorksheetLine/PurchParmLine_IN</a>|
|[SourceRecId](#SourceRecId)||<a href="PurchParmLine_IN.md" target="_blank">WorksheetLine/PurchParmLine_IN</a>|
|[SourceTableId](#SourceTableId)||<a href="PurchParmLine_IN.md" target="_blank">WorksheetLine/PurchParmLine_IN</a>|
|[AcceptedQty](#AcceptedQty)||<a href="PurchParmLine_IN.md" target="_blank">WorksheetLine/PurchParmLine_IN</a>|
|[AssessableValueTransactionCurrency](#AssessableValueTransactionCurrency)||<a href="PurchParmLine_IN.md" target="_blank">WorksheetLine/PurchParmLine_IN</a>|
|[CustomsBillOfEntryNumberTable](#CustomsBillOfEntryNumberTable)||<a href="PurchParmLine_IN.md" target="_blank">WorksheetLine/PurchParmLine_IN</a>|
|[CustomsImportInvoiceNumberTable](#CustomsImportInvoiceNumberTable)||<a href="PurchParmLine_IN.md" target="_blank">WorksheetLine/PurchParmLine_IN</a>|
|[CustomsInvoiceRegnRecId](#CustomsInvoiceRegnRecId)||<a href="PurchParmLine_IN.md" target="_blank">WorksheetLine/PurchParmLine_IN</a>|
|[MaximumRetailPrice](#MaximumRetailPrice)||<a href="PurchParmLine_IN.md" target="_blank">WorksheetLine/PurchParmLine_IN</a>|
|[ReceivedQty](#ReceivedQty)||<a href="PurchParmLine_IN.md" target="_blank">WorksheetLine/PurchParmLine_IN</a>|
|[RejectedQty](#RejectedQty)||<a href="PurchParmLine_IN.md" target="_blank">WorksheetLine/PurchParmLine_IN</a>|
|[DataAreaId](#DataAreaId)||<a href="PurchParmLine_IN.md" target="_blank">WorksheetLine/PurchParmLine_IN</a>|
|[Relationship_InventSiteGateEntryLineRelationshipId](#Relationship_InventSiteGateEntryLineRelationshipId)||<a href="PurchParmLine_IN.md" target="_blank">WorksheetLine/PurchParmLine_IN</a>|
|[Relationship_PurchParmLineRelationshipId](#Relationship_PurchParmLineRelationshipId)||<a href="PurchParmLine_IN.md" target="_blank">WorksheetLine/PurchParmLine_IN</a>|
|[Relationship_CustomsBillOfEntryNumberTableRelationshipId](#Relationship_CustomsBillOfEntryNumberTableRelationshipId)||<a href="PurchParmLine_IN.md" target="_blank">WorksheetLine/PurchParmLine_IN</a>|
|[Relationship_CustomsImportInvoiceNumberTableRelationshipId](#Relationship_CustomsImportInvoiceNumberTableRelationshipId)||<a href="PurchParmLine_IN.md" target="_blank">WorksheetLine/PurchParmLine_IN</a>|
|[Relationship_CustomsInvoiceRegnTransRelationshipId](#Relationship_CustomsInvoiceRegnTransRelationshipId)||<a href="PurchParmLine_IN.md" target="_blank">WorksheetLine/PurchParmLine_IN</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="PurchParmLine_IN.md" target="_blank">WorksheetLine/PurchParmLine_IN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/PurchParmLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchParmLine_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AssessableValueAccountingCurrency name="AssessableValueAccountingCurrency">AssessableValueAccountingCurrency</a>

First included in: WorksheetLine/PurchParmLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssessableValueAccountingCurrency attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InventSiteGateEntryLine name="InventSiteGateEntryLine">InventSiteGateEntryLine</a>

First included in: WorksheetLine/PurchParmLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventSiteGateEntryLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PurchParmLine name="PurchParmLine">PurchParmLine</a>

First included in: WorksheetLine/PurchParmLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchParmLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SourceRecId name="SourceRecId">SourceRecId</a>

First included in: WorksheetLine/PurchParmLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SourceTableId name="SourceTableId">SourceTableId</a>

First included in: WorksheetLine/PurchParmLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#AcceptedQty name="AcceptedQty">AcceptedQty</a>

First included in: WorksheetLine/PurchParmLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceptedQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AssessableValueTransactionCurrency name="AssessableValueTransactionCurrency">AssessableValueTransactionCurrency</a>

First included in: WorksheetLine/PurchParmLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssessableValueTransactionCurrency attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CustomsBillOfEntryNumberTable name="CustomsBillOfEntryNumberTable">CustomsBillOfEntryNumberTable</a>

First included in: WorksheetLine/PurchParmLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsBillOfEntryNumberTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustomsImportInvoiceNumberTable name="CustomsImportInvoiceNumberTable">CustomsImportInvoiceNumberTable</a>

First included in: WorksheetLine/PurchParmLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsImportInvoiceNumberTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustomsInvoiceRegnRecId name="CustomsInvoiceRegnRecId">CustomsInvoiceRegnRecId</a>

First included in: WorksheetLine/PurchParmLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsInvoiceRegnRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MaximumRetailPrice name="MaximumRetailPrice">MaximumRetailPrice</a>

First included in: WorksheetLine/PurchParmLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRetailPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReceivedQty name="ReceivedQty">ReceivedQty</a>

First included in: WorksheetLine/PurchParmLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivedQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RejectedQty name="RejectedQty">RejectedQty</a>

First included in: WorksheetLine/PurchParmLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RejectedQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/PurchParmLine_IN (this entity)  

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

### <a href=#Relationship_InventSiteGateEntryLineRelationshipId name="Relationship_InventSiteGateEntryLineRelationshipId">Relationship_InventSiteGateEntryLineRelationshipId</a>

First included in: WorksheetLine/PurchParmLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventSiteGateEntryLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/WorksheetLine/InventSiteGateEntryLine_IN.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/WorksheetLine/InventSiteGateEntryLine_IN.cdm.json/InventSiteGateEntryLine_IN</a></td><td><a href="../../../SupplyChain/Inventory/WorksheetLine/InventSiteGateEntryLine_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchParmLineRelationshipId name="Relationship_PurchParmLineRelationshipId">Relationship_PurchParmLineRelationshipId</a>

First included in: WorksheetLine/PurchParmLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchParmLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProcurementAndSourcing/WorksheetLine/PurchParmLine.md" target="_blank">/core/erp/Tables/SupplyChain/ProcurementAndSourcing/WorksheetLine/PurchParmLine.cdm.json/PurchParmLine</a></td><td><a href="../../../SupplyChain/ProcurementAndSourcing/WorksheetLine/PurchParmLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustomsBillOfEntryNumberTableRelationshipId name="Relationship_CustomsBillOfEntryNumberTableRelationshipId">Relationship_CustomsBillOfEntryNumberTableRelationshipId</a>

First included in: WorksheetLine/PurchParmLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustomsBillOfEntryNumberTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Main/CustomsBillOfEntryNumberTable_IN.md" target="_blank">/core/erp/Tables/Finance/AccountsReceivable/Main/CustomsBillOfEntryNumberTable_IN.cdm.json/CustomsBillOfEntryNumberTable_IN</a></td><td><a href="../../AccountsReceivable/Main/CustomsBillOfEntryNumberTable_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustomsImportInvoiceNumberTableRelationshipId name="Relationship_CustomsImportInvoiceNumberTableRelationshipId">Relationship_CustomsImportInvoiceNumberTableRelationshipId</a>

First included in: WorksheetLine/PurchParmLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustomsImportInvoiceNumberTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Main/CustomsImportInvoiceNumberTable_IN.md" target="_blank">/core/erp/Tables/Finance/AccountsReceivable/Main/CustomsImportInvoiceNumberTable_IN.cdm.json/CustomsImportInvoiceNumberTable_IN</a></td><td><a href="../../AccountsReceivable/Main/CustomsImportInvoiceNumberTable_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustomsInvoiceRegnTransRelationshipId name="Relationship_CustomsInvoiceRegnTransRelationshipId">Relationship_CustomsInvoiceRegnTransRelationshipId</a>

First included in: WorksheetLine/PurchParmLine_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustomsInvoiceRegnTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Transaction/CustomsInvoiceRegnTrans_IN.md" target="_blank">/core/erp/Tables/Finance/AccountsReceivable/Transaction/CustomsInvoiceRegnTrans_IN.cdm.json/CustomsInvoiceRegnTrans_IN</a></td><td><a href="../../AccountsReceivable/Transaction/CustomsInvoiceRegnTrans_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/PurchParmLine_IN (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
