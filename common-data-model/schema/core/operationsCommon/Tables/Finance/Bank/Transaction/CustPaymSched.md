---
title: CustPaymSched - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# CustPaymSched

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Bank/Transaction/CustPaymSched.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CustPaymSched/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[Description](#Description)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[ExtRecId](#ExtRecId)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[ExtTableId](#ExtTableId)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[LowestAmount](#LowestAmount)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[MCRMiscchargeDist](#MCRMiscchargeDist)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[MCRRefRecID](#MCRRefRecID)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[MCRRefTableID](#MCRRefTableID)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[Name](#Name)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[Notes](#Notes)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[NumOfPayment](#NumOfPayment)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[PaymentAmount](#PaymentAmount)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[PaymSchedBy](#PaymSchedBy)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[PeriodUnit](#PeriodUnit)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[QtyUnit](#QtyUnit)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[TaxDistribution](#TaxDistribution)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[PaymentType_ES](#PaymentType_ES)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[CopyPreciselyToInvoice](#CopyPreciselyToInvoice)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[DataAreaId](#DataAreaId)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[Relationship_BankBillOfExchangeTableRelationshipId](#Relationship_BankBillOfExchangeTableRelationshipId)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[Relationship_CustInvoiceJourRelationshipId](#Relationship_CustInvoiceJourRelationshipId)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[Relationship_CustInvoiceTableRelationshipId](#Relationship_CustInvoiceTableRelationshipId)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[Relationship_MCRContinuityCustHeaderRelationshipId](#Relationship_MCRContinuityCustHeaderRelationshipId)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[Relationship_MCRContinuityCustLineRelationshipId](#Relationship_MCRContinuityCustLineRelationshipId)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[Relationship_MCRInstallmentPlanSalesTableRelationshipId](#Relationship_MCRInstallmentPlanSalesTableRelationshipId)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[Relationship_PaymSchedRelationshipId](#Relationship_PaymSchedRelationshipId)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[Relationship_ProjProposalJourRelationshipId](#Relationship_ProjProposalJourRelationshipId)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[Relationship_SalesComplementaryInvoiceRelationshipId](#Relationship_SalesComplementaryInvoiceRelationshipId)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[Relationship_SalesParmTableRelationshipId](#Relationship_SalesParmTableRelationshipId)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[Relationship_SalesTableRelationshipId](#Relationship_SalesTableRelationshipId)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[Relationship_ProjInvoiceJourRelationshipId](#Relationship_ProjInvoiceJourRelationshipId)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="CustPaymSched.md" target="_blank">Transaction/CustPaymSched</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CustPaymSched/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExtRecId name="ExtRecId">ExtRecId</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExtRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ExtTableId name="ExtTableId">ExtTableId</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExtTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#LowestAmount name="LowestAmount">LowestAmount</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LowestAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MCRMiscchargeDist name="MCRMiscchargeDist">MCRMiscchargeDist</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRMiscchargeDist attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MCRRefRecID name="MCRRefRecID">MCRRefRecID</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRRefRecID attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MCRRefTableID name="MCRRefTableID">MCRRefTableID</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRRefTableID attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Notes name="Notes">Notes</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Notes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumOfPayment name="NumOfPayment">NumOfPayment</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumOfPayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PaymentAmount name="PaymentAmount">PaymentAmount</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PaymSchedBy name="PaymSchedBy">PaymSchedBy</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymSchedBy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PeriodUnit name="PeriodUnit">PeriodUnit</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodUnit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#QtyUnit name="QtyUnit">QtyUnit</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QtyUnit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxDistribution name="TaxDistribution">TaxDistribution</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxDistribution attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PaymentType_ES name="PaymentType_ES">PaymentType_ES</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentType_ES attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CopyPreciselyToInvoice name="CopyPreciselyToInvoice">CopyPreciselyToInvoice</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CopyPreciselyToInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/CustPaymSched (this entity)  

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

### <a href=#Relationship_BankBillOfExchangeTableRelationshipId name="Relationship_BankBillOfExchangeTableRelationshipId">Relationship_BankBillOfExchangeTableRelationshipId</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankBillOfExchangeTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Transaction/CustBillOfExchangeJour.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Transaction/CustBillOfExchangeJour.cdm.json/CustBillOfExchangeJour</a></td><td><a href="../../AccountsReceivable/Transaction/CustBillOfExchangeJour.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustInvoiceJourRelationshipId name="Relationship_CustInvoiceJourRelationshipId">Relationship_CustInvoiceJourRelationshipId</a>

First included in: Transaction/CustPaymSched (this entity)  

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

### <a href=#Relationship_CustInvoiceTableRelationshipId name="Relationship_CustInvoiceTableRelationshipId">Relationship_CustInvoiceTableRelationshipId</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustInvoiceTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/WorksheetHeader/CustInvoiceTable.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/WorksheetHeader/CustInvoiceTable.cdm.json/CustInvoiceTable</a></td><td><a href="../../AccountsReceivable/WorksheetHeader/CustInvoiceTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MCRContinuityCustHeaderRelationshipId name="Relationship_MCRContinuityCustHeaderRelationshipId">Relationship_MCRContinuityCustHeaderRelationshipId</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MCRContinuityCustHeaderRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Commerce/Retail/WorksheetHeader/MCRContinuityCustHeader.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/WorksheetHeader/MCRContinuityCustHeader.cdm.json/MCRContinuityCustHeader</a></td><td><a href="../../../Commerce/Retail/WorksheetHeader/MCRContinuityCustHeader.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MCRContinuityCustLineRelationshipId name="Relationship_MCRContinuityCustLineRelationshipId">Relationship_MCRContinuityCustLineRelationshipId</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MCRContinuityCustLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Commerce/Retail/WorksheetLine/MCRContinuityCustLine.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/WorksheetLine/MCRContinuityCustLine.cdm.json/MCRContinuityCustLine</a></td><td><a href="../../../Commerce/Retail/WorksheetLine/MCRContinuityCustLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MCRInstallmentPlanSalesTableRelationshipId name="Relationship_MCRInstallmentPlanSalesTableRelationshipId">Relationship_MCRInstallmentPlanSalesTableRelationshipId</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MCRInstallmentPlanSalesTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Commerce/Retail/Main/MCRInstallmentPlanSalesTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Main/MCRInstallmentPlanSalesTable.cdm.json/MCRInstallmentPlanSalesTable</a></td><td><a href="../../../Commerce/Retail/Main/MCRInstallmentPlanSalesTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymSchedRelationshipId name="Relationship_PaymSchedRelationshipId">Relationship_PaymSchedRelationshipId</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymSchedRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/PaymSched.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/PaymSched.cdm.json/PaymSched</a></td><td><a href="../Group/PaymSched.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjProposalJourRelationshipId name="Relationship_ProjProposalJourRelationshipId">Relationship_ProjProposalJourRelationshipId</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjProposalJourRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjProposalJour.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjProposalJour.cdm.json/ProjProposalJour</a></td><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjProposalJour.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesComplementaryInvoiceRelationshipId name="Relationship_SalesComplementaryInvoiceRelationshipId">Relationship_SalesComplementaryInvoiceRelationshipId</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesComplementaryInvoiceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Transaction/SalesComplementaryInvoiceHeader.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Transaction/SalesComplementaryInvoiceHeader.cdm.json/SalesComplementaryInvoiceHeader</a></td><td><a href="../../AccountsReceivable/Transaction/SalesComplementaryInvoiceHeader.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesParmTableRelationshipId name="Relationship_SalesParmTableRelationshipId">Relationship_SalesParmTableRelationshipId</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesParmTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/SalesAndMarketing/Transaction/SalesParmTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Transaction/SalesParmTable.cdm.json/SalesParmTable</a></td><td><a href="../../../SupplyChain/SalesAndMarketing/Transaction/SalesParmTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesTableRelationshipId name="Relationship_SalesTableRelationshipId">Relationship_SalesTableRelationshipId</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/SalesAndMarketing/WorksheetHeader/SalesTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/SalesTable.cdm.json/SalesTable</a></td><td><a href="../../../SupplyChain/SalesAndMarketing/WorksheetHeader/SalesTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjInvoiceJourRelationshipId name="Relationship_ProjInvoiceJourRelationshipId">Relationship_ProjInvoiceJourRelationshipId</a>

First included in: Transaction/CustPaymSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjInvoiceJourRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjInvoiceJour.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjInvoiceJour.cdm.json/ProjInvoiceJour</a></td><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjInvoiceJour.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/CustPaymSched (this entity)  

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
