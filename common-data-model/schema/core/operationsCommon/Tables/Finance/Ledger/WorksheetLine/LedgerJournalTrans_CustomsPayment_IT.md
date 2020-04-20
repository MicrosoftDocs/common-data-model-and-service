---
title: LedgerJournalTrans_CustomsPayment_IT - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# LedgerJournalTrans_CustomsPayment_IT

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Ledger/WorksheetLine/LedgerJournalTrans_CustomsPayment_IT.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerJournalTrans_CustomsPayment_IT/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="LedgerJournalTrans_CustomsPayment_IT.md" target="_blank">WorksheetLine/LedgerJournalTrans_CustomsPayment_IT</a>|
|[LedgerJournalTrans_Customs](#LedgerJournalTrans_Customs)||<a href="LedgerJournalTrans_CustomsPayment_IT.md" target="_blank">WorksheetLine/LedgerJournalTrans_CustomsPayment_IT</a>|
|[PaymentAmount](#PaymentAmount)||<a href="LedgerJournalTrans_CustomsPayment_IT.md" target="_blank">WorksheetLine/LedgerJournalTrans_CustomsPayment_IT</a>|
|[PaymentId](#PaymentId)||<a href="LedgerJournalTrans_CustomsPayment_IT.md" target="_blank">WorksheetLine/LedgerJournalTrans_CustomsPayment_IT</a>|
|[DataAreaId](#DataAreaId)||<a href="LedgerJournalTrans_CustomsPayment_IT.md" target="_blank">WorksheetLine/LedgerJournalTrans_CustomsPayment_IT</a>|
|[Relationship_CustomsPayments_ITRelationshipId](#Relationship_CustomsPayments_ITRelationshipId)||<a href="LedgerJournalTrans_CustomsPayment_IT.md" target="_blank">WorksheetLine/LedgerJournalTrans_CustomsPayment_IT</a>|
|[Relationship_LedgerJournalTrans_Customs_ITRelationshipId](#Relationship_LedgerJournalTrans_Customs_ITRelationshipId)||<a href="LedgerJournalTrans_CustomsPayment_IT.md" target="_blank">WorksheetLine/LedgerJournalTrans_CustomsPayment_IT</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="LedgerJournalTrans_CustomsPayment_IT.md" target="_blank">WorksheetLine/LedgerJournalTrans_CustomsPayment_IT</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/LedgerJournalTrans_CustomsPayment_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerJournalTrans_CustomsPayment_IT/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LedgerJournalTrans_Customs name="LedgerJournalTrans_Customs">LedgerJournalTrans_Customs</a>

First included in: WorksheetLine/LedgerJournalTrans_CustomsPayment_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerJournalTrans_Customs attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PaymentAmount name="PaymentAmount">PaymentAmount</a>

First included in: WorksheetLine/LedgerJournalTrans_CustomsPayment_IT (this entity)  

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

### <a href=#PaymentId name="PaymentId">PaymentId</a>

First included in: WorksheetLine/LedgerJournalTrans_CustomsPayment_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/LedgerJournalTrans_CustomsPayment_IT (this entity)  

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

### <a href=#Relationship_CustomsPayments_ITRelationshipId name="Relationship_CustomsPayments_ITRelationshipId">Relationship_CustomsPayments_ITRelationshipId</a>

First included in: WorksheetLine/LedgerJournalTrans_CustomsPayment_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustomsPayments_ITRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Group/CustomsPayments_IT.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Group/CustomsPayments_IT.cdm.json/CustomsPayments_IT</a></td><td><a href="../../AccountsReceivable/Group/CustomsPayments_IT.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerJournalTrans_Customs_ITRelationshipId name="Relationship_LedgerJournalTrans_Customs_ITRelationshipId">Relationship_LedgerJournalTrans_Customs_ITRelationshipId</a>

First included in: WorksheetLine/LedgerJournalTrans_CustomsPayment_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerJournalTrans_Customs_ITRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="LedgerJournalTrans_Customs_IT.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/WorksheetLine/LedgerJournalTrans_Customs_IT.cdm.json/LedgerJournalTrans_Customs_IT</a></td><td><a href="LedgerJournalTrans_Customs_IT.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/LedgerJournalTrans_CustomsPayment_IT (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
