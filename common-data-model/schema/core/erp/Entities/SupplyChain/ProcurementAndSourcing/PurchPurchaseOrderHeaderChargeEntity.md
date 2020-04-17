---
title: PurchPurchaseOrderHeaderChargeEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# PurchPurchaseOrderHeaderChargeEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/SupplyChain/ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ChargeCategory](#ChargeCategory)||<a href="PurchPurchaseOrderHeaderChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity</a>|
|[PurchaseChargeCode](#PurchaseChargeCode)||<a href="PurchPurchaseOrderHeaderChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity</a>|
|[ChargeDescription](#ChargeDescription)||<a href="PurchPurchaseOrderHeaderChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity</a>|
|[ChargeAccountingCurrencyCode](#ChargeAccountingCurrencyCode)||<a href="PurchPurchaseOrderHeaderChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity</a>|
|[ChargePercentage](#ChargePercentage)||<a href="PurchPurchaseOrderHeaderChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity</a>|
|[FixedChargeAmount](#FixedChargeAmount)||<a href="PurchPurchaseOrderHeaderChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity</a>|
|[ChargeLineNumber](#ChargeLineNumber)||<a href="PurchPurchaseOrderHeaderChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity</a>|
|[ExternalChargeAmount](#ExternalChargeAmount)||<a href="PurchPurchaseOrderHeaderChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity</a>|
|[ProportionalChargeAmount](#ProportionalChargeAmount)||<a href="PurchPurchaseOrderHeaderChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity</a>|
|[PurchaseOrderNumber](#PurchaseOrderNumber)||<a href="PurchPurchaseOrderHeaderChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity</a>|
|[SalesTaxGroupCode](#SalesTaxGroupCode)||<a href="PurchPurchaseOrderHeaderChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity</a>|
|[SalesTaxItemGroupCode](#SalesTaxItemGroupCode)||<a href="PurchPurchaseOrderHeaderChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity</a>|
|[DocumentTableId](#DocumentTableId)||<a href="PurchPurchaseOrderHeaderChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity</a>|
|[DocumentRecId](#DocumentRecId)||<a href="PurchPurchaseOrderHeaderChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity</a>|
|[DocumentStatus](#DocumentStatus)||<a href="PurchPurchaseOrderHeaderChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity</a>|
|[IsIntercompanyCharge](#IsIntercompanyCharge)||<a href="PurchPurchaseOrderHeaderChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity</a>|
|[Relationship_PurchaseOrderHeaderV2RelationshipId](#Relationship_PurchaseOrderHeaderV2RelationshipId)||<a href="PurchPurchaseOrderHeaderChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="PurchPurchaseOrderHeaderChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity</a>|
|[Relationship_TaxGroupRelationshipId](#Relationship_TaxGroupRelationshipId)||<a href="PurchPurchaseOrderHeaderChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity</a>|
|[Relationship_TaxItemGroupRelationshipId](#Relationship_TaxItemGroupRelationshipId)||<a href="PurchPurchaseOrderHeaderChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity</a>|
|[BackingTable_MarkupDocumentChargeEntityRelationshipId](#BackingTable_MarkupDocumentChargeEntityRelationshipId)||<a href="PurchPurchaseOrderHeaderChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PurchPurchaseOrderHeaderChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity</a>|

### <a href=#ChargeCategory name="ChargeCategory">ChargeCategory</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseChargeCode name="PurchaseChargeCode">PurchaseChargeCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseChargeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeDescription name="ChargeDescription">ChargeDescription</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeAccountingCurrencyCode name="ChargeAccountingCurrencyCode">ChargeAccountingCurrencyCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeAccountingCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargePercentage name="ChargePercentage">ChargePercentage</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargePercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedChargeAmount name="FixedChargeAmount">FixedChargeAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedChargeAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeLineNumber name="ChargeLineNumber">ChargeLineNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternalChargeAmount name="ExternalChargeAmount">ExternalChargeAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalChargeAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProportionalChargeAmount name="ProportionalChargeAmount">ProportionalChargeAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProportionalChargeAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrderNumber name="PurchaseOrderNumber">PurchaseOrderNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroupCode name="SalesTaxGroupCode">SalesTaxGroupCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxItemGroupCode name="SalesTaxItemGroupCode">SalesTaxItemGroupCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxItemGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentTableId name="DocumentTableId">DocumentTableId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentTableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentRecId name="DocumentRecId">DocumentRecId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentStatus name="DocumentStatus">DocumentStatus</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanyCharge name="IsIntercompanyCharge">IsIntercompanyCharge</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanyCharge attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchaseOrderHeaderV2RelationshipId name="Relationship_PurchaseOrderHeaderV2RelationshipId">Relationship_PurchaseOrderHeaderV2RelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchaseOrderHeaderV2RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TaxGroupRelationshipId name="Relationship_TaxGroupRelationshipId">Relationship_TaxGroupRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TaxItemGroupRelationshipId name="Relationship_TaxItemGroupRelationshipId">Relationship_TaxItemGroupRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxItemGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_MarkupDocumentChargeEntityRelationshipId name="BackingTable_MarkupDocumentChargeEntityRelationshipId">BackingTable_MarkupDocumentChargeEntityRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_MarkupDocumentChargeEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderHeaderChargeEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
