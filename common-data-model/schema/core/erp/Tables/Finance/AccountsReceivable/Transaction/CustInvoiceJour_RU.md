---
title: CustInvoiceJour_RU - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# CustInvoiceJour_RU

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/AccountsReceivable/Transaction/CustInvoiceJour_RU.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CustInvoiceJour_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="CustInvoiceJour_RU.md" target="_blank">Transaction/CustInvoiceJour_RU</a>|
|[AttorneyDate_RU](#AttorneyDate_RU)||<a href="CustInvoiceJour_RU.md" target="_blank">Transaction/CustInvoiceJour_RU</a>|
|[AttorneyId_RU](#AttorneyId_RU)||<a href="CustInvoiceJour_RU.md" target="_blank">Transaction/CustInvoiceJour_RU</a>|
|[AttorneyIssuedName_RU](#AttorneyIssuedName_RU)||<a href="CustInvoiceJour_RU.md" target="_blank">Transaction/CustInvoiceJour_RU</a>|
|[ConsigneeAccount_RU](#ConsigneeAccount_RU)||<a href="CustInvoiceJour_RU.md" target="_blank">Transaction/CustInvoiceJour_RU</a>|
|[ConsignorAccount_RU](#ConsignorAccount_RU)||<a href="CustInvoiceJour_RU.md" target="_blank">Transaction/CustInvoiceJour_RU</a>|
|[Correct_RU](#Correct_RU)||<a href="CustInvoiceJour_RU.md" target="_blank">Transaction/CustInvoiceJour_RU</a>|
|[CorrectedInvoiceDate_RU](#CorrectedInvoiceDate_RU)||<a href="CustInvoiceJour_RU.md" target="_blank">Transaction/CustInvoiceJour_RU</a>|
|[CorrectedInvoiceId_RU](#CorrectedInvoiceId_RU)||<a href="CustInvoiceJour_RU.md" target="_blank">Transaction/CustInvoiceJour_RU</a>|
|[CustInvoiceJour](#CustInvoiceJour)||<a href="CustInvoiceJour_RU.md" target="_blank">Transaction/CustInvoiceJour_RU</a>|
|[CustInvoicePrintoutType_RU](#CustInvoicePrintoutType_RU)||<a href="CustInvoiceJour_RU.md" target="_blank">Transaction/CustInvoiceJour_RU</a>|
|[FacturedFully_RU](#FacturedFully_RU)||<a href="CustInvoiceJour_RU.md" target="_blank">Transaction/CustInvoiceJour_RU</a>|
|[InventOwnerId_RU](#InventOwnerId_RU)||<a href="CustInvoiceJour_RU.md" target="_blank">Transaction/CustInvoiceJour_RU</a>|
|[InventProfileType_RU](#InventProfileType_RU)||<a href="CustInvoiceJour_RU.md" target="_blank">Transaction/CustInvoiceJour_RU</a>|
|[InvoicePostingType_RU](#InvoicePostingType_RU)||<a href="CustInvoiceJour_RU.md" target="_blank">Transaction/CustInvoiceJour_RU</a>|
|[NonRealRevenue_RU](#NonRealRevenue_RU)||<a href="CustInvoiceJour_RU.md" target="_blank">Transaction/CustInvoiceJour_RU</a>|
|[PrintStandardCurrency_RU](#PrintStandardCurrency_RU)||<a href="CustInvoiceJour_RU.md" target="_blank">Transaction/CustInvoiceJour_RU</a>|
|[SettleVoucher_RU](#SettleVoucher_RU)||<a href="CustInvoiceJour_RU.md" target="_blank">Transaction/CustInvoiceJour_RU</a>|
|[VATOnPayment_RU](#VATOnPayment_RU)||<a href="CustInvoiceJour_RU.md" target="_blank">Transaction/CustInvoiceJour_RU</a>|
|[DataAreaId](#DataAreaId)||<a href="CustInvoiceJour_RU.md" target="_blank">Transaction/CustInvoiceJour_RU</a>|
|[Relationship_CustInvoiceJourRelationshipId](#Relationship_CustInvoiceJourRelationshipId)||<a href="CustInvoiceJour_RU.md" target="_blank">Transaction/CustInvoiceJour_RU</a>|
|[Relationship_CustTable_RURelationshipId](#Relationship_CustTable_RURelationshipId)||<a href="CustInvoiceJour_RU.md" target="_blank">Transaction/CustInvoiceJour_RU</a>|
|[Relationship_InventOwner_RURelationshipId](#Relationship_InventOwner_RURelationshipId)||<a href="CustInvoiceJour_RU.md" target="_blank">Transaction/CustInvoiceJour_RU</a>|
|[Relationship_VendTable_RURelationshipId](#Relationship_VendTable_RURelationshipId)||<a href="CustInvoiceJour_RU.md" target="_blank">Transaction/CustInvoiceJour_RU</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="CustInvoiceJour_RU.md" target="_blank">Transaction/CustInvoiceJour_RU</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/CustInvoiceJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CustInvoiceJour_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AttorneyDate_RU name="AttorneyDate_RU">AttorneyDate_RU</a>

First included in: Transaction/CustInvoiceJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttorneyDate_RU attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#AttorneyId_RU name="AttorneyId_RU">AttorneyId_RU</a>

First included in: Transaction/CustInvoiceJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttorneyId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AttorneyIssuedName_RU name="AttorneyIssuedName_RU">AttorneyIssuedName_RU</a>

First included in: Transaction/CustInvoiceJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttorneyIssuedName_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsigneeAccount_RU name="ConsigneeAccount_RU">ConsigneeAccount_RU</a>

First included in: Transaction/CustInvoiceJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsigneeAccount_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConsignorAccount_RU name="ConsignorAccount_RU">ConsignorAccount_RU</a>

First included in: Transaction/CustInvoiceJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConsignorAccount_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Correct_RU name="Correct_RU">Correct_RU</a>

First included in: Transaction/CustInvoiceJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Correct_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#CorrectedInvoiceDate_RU name="CorrectedInvoiceDate_RU">CorrectedInvoiceDate_RU</a>

First included in: Transaction/CustInvoiceJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedInvoiceDate_RU attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#CorrectedInvoiceId_RU name="CorrectedInvoiceId_RU">CorrectedInvoiceId_RU</a>

First included in: Transaction/CustInvoiceJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedInvoiceId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustInvoiceJour name="CustInvoiceJour">CustInvoiceJour</a>

First included in: Transaction/CustInvoiceJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustInvoiceJour attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustInvoicePrintoutType_RU name="CustInvoicePrintoutType_RU">CustInvoicePrintoutType_RU</a>

First included in: Transaction/CustInvoiceJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustInvoicePrintoutType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#FacturedFully_RU name="FacturedFully_RU">FacturedFully_RU</a>

First included in: Transaction/CustInvoiceJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FacturedFully_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#InventOwnerId_RU name="InventOwnerId_RU">InventOwnerId_RU</a>

First included in: Transaction/CustInvoiceJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventOwnerId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventProfileType_RU name="InventProfileType_RU">InventProfileType_RU</a>

First included in: Transaction/CustInvoiceJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventProfileType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InvoicePostingType_RU name="InvoicePostingType_RU">InvoicePostingType_RU</a>

First included in: Transaction/CustInvoiceJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoicePostingType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#NonRealRevenue_RU name="NonRealRevenue_RU">NonRealRevenue_RU</a>

First included in: Transaction/CustInvoiceJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NonRealRevenue_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintStandardCurrency_RU name="PrintStandardCurrency_RU">PrintStandardCurrency_RU</a>

First included in: Transaction/CustInvoiceJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintStandardCurrency_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SettleVoucher_RU name="SettleVoucher_RU">SettleVoucher_RU</a>

First included in: Transaction/CustInvoiceJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettleVoucher_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#VATOnPayment_RU name="VATOnPayment_RU">VATOnPayment_RU</a>

First included in: Transaction/CustInvoiceJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATOnPayment_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/CustInvoiceJour_RU (this entity)  

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

First included in: Transaction/CustInvoiceJour_RU (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="CustInvoiceJour.md" target="_blank">/core/erp/Tables/Finance/AccountsReceivable/Transaction/CustInvoiceJour.cdm.json/CustInvoiceJour</a></td><td><a href="CustInvoiceJour.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustTable_RURelationshipId name="Relationship_CustTable_RURelationshipId">Relationship_CustTable_RURelationshipId</a>

First included in: Transaction/CustInvoiceJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Customer/Main/CustTable.md" target="_blank">/core/erp/Tables/Common/Customer/Main/CustTable.cdm.json/CustTable</a></td><td><a href="../../../Common/Customer/Main/CustTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventOwner_RURelationshipId name="Relationship_InventOwner_RURelationshipId">Relationship_InventOwner_RURelationshipId</a>

First included in: Transaction/CustInvoiceJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventOwner_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/InventOwner_RU.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Group/InventOwner_RU.cdm.json/InventOwner_RU</a></td><td><a href="../../../SupplyChain/Inventory/Group/InventOwner_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTable_RURelationshipId name="Relationship_VendTable_RURelationshipId">Relationship_VendTable_RURelationshipId</a>

First included in: Transaction/CustInvoiceJour_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md" target="_blank">/core/erp/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/CustInvoiceJour_RU (this entity)  

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
