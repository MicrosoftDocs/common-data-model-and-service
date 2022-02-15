---
title: ExportSalesInvoiceLineDomesticTaxGroup in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Export sales invoice line domestic sales tax group in Transaction(ExportSalesInvoiceLineDomesticTaxGroup)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/Transaction/ExportSalesInvoiceLineDomesticTaxGroup.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ExportSalesInvoiceLineDomesticTaxGroup/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Export sales invoice line domestic sales tax group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ExportSalesInvoiceLineDomesticTaxGroup.md" target="_blank">Transaction/ExportSalesInvoiceLineDomesticTaxGroup</a>|
|[CustInvoiceTrans](#CustInvoiceTrans)||<a href="ExportSalesInvoiceLineDomesticTaxGroup.md" target="_blank">Transaction/ExportSalesInvoiceLineDomesticTaxGroup</a>|
|[DomesticSalesTaxGroup](#DomesticSalesTaxGroup)||<a href="ExportSalesInvoiceLineDomesticTaxGroup.md" target="_blank">Transaction/ExportSalesInvoiceLineDomesticTaxGroup</a>|
|[ExportSalesInvoice](#ExportSalesInvoice)||<a href="ExportSalesInvoiceLineDomesticTaxGroup.md" target="_blank">Transaction/ExportSalesInvoiceLineDomesticTaxGroup</a>|
|[DataAreaId](#DataAreaId)||<a href="ExportSalesInvoiceLineDomesticTaxGroup.md" target="_blank">Transaction/ExportSalesInvoiceLineDomesticTaxGroup</a>|
|[Relationship_CustInvoiceTransRelationshipId](#Relationship_CustInvoiceTransRelationshipId)||<a href="ExportSalesInvoiceLineDomesticTaxGroup.md" target="_blank">Transaction/ExportSalesInvoiceLineDomesticTaxGroup</a>|
|[Relationship_DomesticSalesTaxGroupRelationshipId](#Relationship_DomesticSalesTaxGroupRelationshipId)||<a href="ExportSalesInvoiceLineDomesticTaxGroup.md" target="_blank">Transaction/ExportSalesInvoiceLineDomesticTaxGroup</a>|
|[Relationship_ExportSalesInvoiceRelationshipId](#Relationship_ExportSalesInvoiceRelationshipId)||<a href="ExportSalesInvoiceLineDomesticTaxGroup.md" target="_blank">Transaction/ExportSalesInvoiceLineDomesticTaxGroup</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="ExportSalesInvoiceLineDomesticTaxGroup.md" target="_blank">Transaction/ExportSalesInvoiceLineDomesticTaxGroup</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/ExportSalesInvoiceLineDomesticTaxGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ExportSalesInvoiceLineDomesticTaxGroup/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustInvoiceTrans name="CustInvoiceTrans">CustInvoiceTrans</a>

First included in: Transaction/ExportSalesInvoiceLineDomesticTaxGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustInvoiceTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DomesticSalesTaxGroup name="DomesticSalesTaxGroup">DomesticSalesTaxGroup</a>

First included in: Transaction/ExportSalesInvoiceLineDomesticTaxGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DomesticSalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExportSalesInvoice name="ExportSalesInvoice">ExportSalesInvoice</a>

First included in: Transaction/ExportSalesInvoiceLineDomesticTaxGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExportSalesInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/ExportSalesInvoiceLineDomesticTaxGroup (this entity)  

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

### <a href=#Relationship_CustInvoiceTransRelationshipId name="Relationship_CustInvoiceTransRelationshipId">Relationship_CustInvoiceTransRelationshipId</a>

First included in: Transaction/ExportSalesInvoiceLineDomesticTaxGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustInvoiceTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Transaction/CustInvoiceTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Transaction/CustInvoiceTrans.cdm.json/CustInvoiceTrans</a></td><td><a href="../../AccountsReceivable/Transaction/CustInvoiceTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DomesticSalesTaxGroupRelationshipId name="Relationship_DomesticSalesTaxGroupRelationshipId">Relationship_DomesticSalesTaxGroupRelationshipId</a>

First included in: Transaction/ExportSalesInvoiceLineDomesticTaxGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DomesticSalesTaxGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/TaxGroupHeading.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxGroupHeading.cdm.json/TaxGroupHeading</a></td><td><a href="../Group/TaxGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ExportSalesInvoiceRelationshipId name="Relationship_ExportSalesInvoiceRelationshipId">Relationship_ExportSalesInvoiceRelationshipId</a>

First included in: Transaction/ExportSalesInvoiceLineDomesticTaxGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ExportSalesInvoiceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../APARShared/Transaction/ExportSalesInvoice.md" target="_blank">/core/operationsCommon/Tables/Finance/APARShared/Transaction/ExportSalesInvoice.cdm.json/ExportSalesInvoice</a></td><td><a href="../../APARShared/Transaction/ExportSalesInvoice.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/ExportSalesInvoiceLineDomesticTaxGroup (this entity)  

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
