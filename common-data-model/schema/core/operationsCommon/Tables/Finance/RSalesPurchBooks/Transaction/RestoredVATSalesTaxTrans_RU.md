---
title: RestoredVATSalesTaxTrans_RU - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RestoredVATSalesTaxTrans_RU

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/RSalesPurchBooks/Transaction/RestoredVATSalesTaxTrans_RU.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RestoredVATSalesTaxTrans_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RestoredVATSalesTaxTrans_RU.md" target="_blank">Transaction/RestoredVATSalesTaxTrans_RU</a>|
|[CustInvoiceJourRecId](#CustInvoiceJourRecId)||<a href="RestoredVATSalesTaxTrans_RU.md" target="_blank">Transaction/RestoredVATSalesTaxTrans_RU</a>|
|[Factor](#Factor)||<a href="RestoredVATSalesTaxTrans_RU.md" target="_blank">Transaction/RestoredVATSalesTaxTrans_RU</a>|
|[FactureDate](#FactureDate)||<a href="RestoredVATSalesTaxTrans_RU.md" target="_blank">Transaction/RestoredVATSalesTaxTrans_RU</a>|
|[FactureExternalId](#FactureExternalId)||<a href="RestoredVATSalesTaxTrans_RU.md" target="_blank">Transaction/RestoredVATSalesTaxTrans_RU</a>|
|[FactureId](#FactureId)||<a href="RestoredVATSalesTaxTrans_RU.md" target="_blank">Transaction/RestoredVATSalesTaxTrans_RU</a>|
|[FactureModule](#FactureModule)||<a href="RestoredVATSalesTaxTrans_RU.md" target="_blank">Transaction/RestoredVATSalesTaxTrans_RU</a>|
|[InventTransId](#InventTransId)||<a href="RestoredVATSalesTaxTrans_RU.md" target="_blank">Transaction/RestoredVATSalesTaxTrans_RU</a>|
|[PrevPeriod](#PrevPeriod)||<a href="RestoredVATSalesTaxTrans_RU.md" target="_blank">Transaction/RestoredVATSalesTaxTrans_RU</a>|
|[TaxBaseAmount](#TaxBaseAmount)||<a href="RestoredVATSalesTaxTrans_RU.md" target="_blank">Transaction/RestoredVATSalesTaxTrans_RU</a>|
|[TaxCode](#TaxCode)||<a href="RestoredVATSalesTaxTrans_RU.md" target="_blank">Transaction/RestoredVATSalesTaxTrans_RU</a>|
|[TaxReducedDirect](#TaxReducedDirect)||<a href="RestoredVATSalesTaxTrans_RU.md" target="_blank">Transaction/RestoredVATSalesTaxTrans_RU</a>|
|[TaxReducedIndirect](#TaxReducedIndirect)||<a href="RestoredVATSalesTaxTrans_RU.md" target="_blank">Transaction/RestoredVATSalesTaxTrans_RU</a>|
|[TaxStandardDirect](#TaxStandardDirect)||<a href="RestoredVATSalesTaxTrans_RU.md" target="_blank">Transaction/RestoredVATSalesTaxTrans_RU</a>|
|[TaxStandardIndirect](#TaxStandardIndirect)||<a href="RestoredVATSalesTaxTrans_RU.md" target="_blank">Transaction/RestoredVATSalesTaxTrans_RU</a>|
|[TransDate](#TransDate)||<a href="RestoredVATSalesTaxTrans_RU.md" target="_blank">Transaction/RestoredVATSalesTaxTrans_RU</a>|
|[DataAreaId](#DataAreaId)||<a href="RestoredVATSalesTaxTrans_RU.md" target="_blank">Transaction/RestoredVATSalesTaxTrans_RU</a>|
|[Relationship_CustInvoiceJourRelationshipId](#Relationship_CustInvoiceJourRelationshipId)||<a href="RestoredVATSalesTaxTrans_RU.md" target="_blank">Transaction/RestoredVATSalesTaxTrans_RU</a>|
|[Relationship_FactureJourRelationshipId](#Relationship_FactureJourRelationshipId)||<a href="RestoredVATSalesTaxTrans_RU.md" target="_blank">Transaction/RestoredVATSalesTaxTrans_RU</a>|
|[Relationship_InventTransOriginRelationshipId](#Relationship_InventTransOriginRelationshipId)||<a href="RestoredVATSalesTaxTrans_RU.md" target="_blank">Transaction/RestoredVATSalesTaxTrans_RU</a>|
|[Relationship_RestoredVATLogTableRelationshipId](#Relationship_RestoredVATLogTableRelationshipId)||<a href="RestoredVATSalesTaxTrans_RU.md" target="_blank">Transaction/RestoredVATSalesTaxTrans_RU</a>|
|[Relationship_TaxTableRelationshipId](#Relationship_TaxTableRelationshipId)||<a href="RestoredVATSalesTaxTrans_RU.md" target="_blank">Transaction/RestoredVATSalesTaxTrans_RU</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RestoredVATSalesTaxTrans_RU.md" target="_blank">Transaction/RestoredVATSalesTaxTrans_RU</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/RestoredVATSalesTaxTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RestoredVATSalesTaxTrans_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustInvoiceJourRecId name="CustInvoiceJourRecId">CustInvoiceJourRecId</a>

First included in: Transaction/RestoredVATSalesTaxTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustInvoiceJourRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Factor name="Factor">Factor</a>

First included in: Transaction/RestoredVATSalesTaxTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Factor attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FactureDate name="FactureDate">FactureDate</a>

First included in: Transaction/RestoredVATSalesTaxTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FactureDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#FactureExternalId name="FactureExternalId">FactureExternalId</a>

First included in: Transaction/RestoredVATSalesTaxTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FactureExternalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FactureId name="FactureId">FactureId</a>

First included in: Transaction/RestoredVATSalesTaxTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FactureId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FactureModule name="FactureModule">FactureModule</a>

First included in: Transaction/RestoredVATSalesTaxTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FactureModule attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventTransId name="InventTransId">InventTransId</a>

First included in: Transaction/RestoredVATSalesTaxTrans_RU (this entity)  

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

### <a href=#PrevPeriod name="PrevPeriod">PrevPeriod</a>

First included in: Transaction/RestoredVATSalesTaxTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrevPeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxBaseAmount name="TaxBaseAmount">TaxBaseAmount</a>

First included in: Transaction/RestoredVATSalesTaxTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxCode name="TaxCode">TaxCode</a>

First included in: Transaction/RestoredVATSalesTaxTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxReducedDirect name="TaxReducedDirect">TaxReducedDirect</a>

First included in: Transaction/RestoredVATSalesTaxTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReducedDirect attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxReducedIndirect name="TaxReducedIndirect">TaxReducedIndirect</a>

First included in: Transaction/RestoredVATSalesTaxTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReducedIndirect attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxStandardDirect name="TaxStandardDirect">TaxStandardDirect</a>

First included in: Transaction/RestoredVATSalesTaxTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxStandardDirect attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxStandardIndirect name="TaxStandardIndirect">TaxStandardIndirect</a>

First included in: Transaction/RestoredVATSalesTaxTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxStandardIndirect attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: Transaction/RestoredVATSalesTaxTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/RestoredVATSalesTaxTrans_RU (this entity)  

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

### <a href=#Relationship_CustInvoiceJourRelationshipId name="Relationship_CustInvoiceJourRelationshipId">Relationship_CustInvoiceJourRelationshipId</a>

First included in: Transaction/RestoredVATSalesTaxTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustInvoiceJourRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Transaction/CustInvoiceJour.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Transaction/CustInvoiceJour.cdm.json/CustInvoiceJour</a></td><td><a href="../../AccountsReceivable/Transaction/CustInvoiceJour.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FactureJourRelationshipId name="Relationship_FactureJourRelationshipId">Relationship_FactureJourRelationshipId</a>

First included in: Transaction/RestoredVATSalesTaxTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FactureJourRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/FactureJour_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/RSalesPurchBooks/WorksheetHeader/FactureJour_RU.cdm.json/FactureJour_RU</a></td><td><a href="../WorksheetHeader/FactureJour_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTransOriginRelationshipId name="Relationship_InventTransOriginRelationshipId">Relationship_InventTransOriginRelationshipId</a>

First included in: Transaction/RestoredVATSalesTaxTrans_RU (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Transaction/InventTransOrigin.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/InventTransOrigin.cdm.json/InventTransOrigin</a></td><td><a href="../../../SupplyChain/Inventory/Transaction/InventTransOrigin.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RestoredVATLogTableRelationshipId name="Relationship_RestoredVATLogTableRelationshipId">Relationship_RestoredVATLogTableRelationshipId</a>

First included in: Transaction/RestoredVATSalesTaxTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RestoredVATLogTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/RestoredVATLogTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/RSalesPurchBooks/WorksheetHeader/RestoredVATLogTable_RU.cdm.json/RestoredVATLogTable_RU</a></td><td><a href="../WorksheetHeader/RestoredVATLogTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxTableRelationshipId name="Relationship_TaxTableRelationshipId">Relationship_TaxTableRelationshipId</a>

First included in: Transaction/RestoredVATSalesTaxTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Group/TaxTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxTable.cdm.json/TaxTable</a></td><td><a href="../../Tax/Group/TaxTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/RestoredVATSalesTaxTrans_RU (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
