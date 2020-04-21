---
title: CFMAnalyticDataEditUncommitted - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# CFMAnalyticDataEditUncommitted

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/RCashFlowManagement/Transaction/CFMAnalyticDataEditUncommitted.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CFMAnalyticDataEditUncommitted/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="CFMAnalyticDataEditUncommitted.md" target="_blank">Transaction/CFMAnalyticDataEditUncommitted</a>|
|[DataArea](#DataArea)||<a href="CFMAnalyticDataEditUncommitted.md" target="_blank">Transaction/CFMAnalyticDataEditUncommitted</a>|
|[DueDate](#DueDate)||<a href="CFMAnalyticDataEditUncommitted.md" target="_blank">Transaction/CFMAnalyticDataEditUncommitted</a>|
|[JournalTable](#JournalTable)||<a href="CFMAnalyticDataEditUncommitted.md" target="_blank">Transaction/CFMAnalyticDataEditUncommitted</a>|
|[PaymentAccountNum](#PaymentAccountNum)||<a href="CFMAnalyticDataEditUncommitted.md" target="_blank">Transaction/CFMAnalyticDataEditUncommitted</a>|
|[PaymentAccountType](#PaymentAccountType)||<a href="CFMAnalyticDataEditUncommitted.md" target="_blank">Transaction/CFMAnalyticDataEditUncommitted</a>|
|[PaymMode](#PaymMode)||<a href="CFMAnalyticDataEditUncommitted.md" target="_blank">Transaction/CFMAnalyticDataEditUncommitted</a>|
|[PaymSpec](#PaymSpec)||<a href="CFMAnalyticDataEditUncommitted.md" target="_blank">Transaction/CFMAnalyticDataEditUncommitted</a>|
|[SourceRefRecId](#SourceRefRecId)||<a href="CFMAnalyticDataEditUncommitted.md" target="_blank">Transaction/CFMAnalyticDataEditUncommitted</a>|
|[SourceType](#SourceType)||<a href="CFMAnalyticDataEditUncommitted.md" target="_blank">Transaction/CFMAnalyticDataEditUncommitted</a>|
|[Relationship_CFMJournalTableRelationshipId](#Relationship_CFMJournalTableRelationshipId)||<a href="CFMAnalyticDataEditUncommitted.md" target="_blank">Transaction/CFMAnalyticDataEditUncommitted</a>|
|[Relationship_CFMPaymentRequestTableRelationshipId](#Relationship_CFMPaymentRequestTableRelationshipId)||<a href="CFMAnalyticDataEditUncommitted.md" target="_blank">Transaction/CFMAnalyticDataEditUncommitted</a>|
|[Relationship_CompanyInfoRelationshipId](#Relationship_CompanyInfoRelationshipId)||<a href="CFMAnalyticDataEditUncommitted.md" target="_blank">Transaction/CFMAnalyticDataEditUncommitted</a>|
|[Relationship_CustTransOpenRelationshipId](#Relationship_CustTransOpenRelationshipId)||<a href="CFMAnalyticDataEditUncommitted.md" target="_blank">Transaction/CFMAnalyticDataEditUncommitted</a>|
|[Relationship_VendTransOpenRelationshipId](#Relationship_VendTransOpenRelationshipId)||<a href="CFMAnalyticDataEditUncommitted.md" target="_blank">Transaction/CFMAnalyticDataEditUncommitted</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/CFMAnalyticDataEditUncommitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CFMAnalyticDataEditUncommitted/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataArea name="DataArea">DataArea</a>

First included in: Transaction/CFMAnalyticDataEditUncommitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DueDate name="DueDate">DueDate</a>

First included in: Transaction/CFMAnalyticDataEditUncommitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DueDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#JournalTable name="JournalTable">JournalTable</a>

First included in: Transaction/CFMAnalyticDataEditUncommitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PaymentAccountNum name="PaymentAccountNum">PaymentAccountNum</a>

First included in: Transaction/CFMAnalyticDataEditUncommitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentAccountNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentAccountType name="PaymentAccountType">PaymentAccountType</a>

First included in: Transaction/CFMAnalyticDataEditUncommitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentAccountType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PaymMode name="PaymMode">PaymMode</a>

First included in: Transaction/CFMAnalyticDataEditUncommitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymSpec name="PaymSpec">PaymSpec</a>

First included in: Transaction/CFMAnalyticDataEditUncommitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymSpec attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceRefRecId name="SourceRefRecId">SourceRefRecId</a>

First included in: Transaction/CFMAnalyticDataEditUncommitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceRefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SourceType name="SourceType">SourceType</a>

First included in: Transaction/CFMAnalyticDataEditUncommitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_CFMJournalTableRelationshipId name="Relationship_CFMJournalTableRelationshipId">Relationship_CFMJournalTableRelationshipId</a>

First included in: Transaction/CFMAnalyticDataEditUncommitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CFMJournalTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/CFMJournalTable.md" target="_blank">/core/operationsCommon/Tables/Finance/RCashFlowManagement/WorksheetHeader/CFMJournalTable.cdm.json/CFMJournalTable</a></td><td><a href="../WorksheetHeader/CFMJournalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CFMPaymentRequestTableRelationshipId name="Relationship_CFMPaymentRequestTableRelationshipId">Relationship_CFMPaymentRequestTableRelationshipId</a>

First included in: Transaction/CFMAnalyticDataEditUncommitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CFMPaymentRequestTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/CFMPaymentRequestTable.md" target="_blank">/core/operationsCommon/Tables/Finance/RCashFlowManagement/WorksheetHeader/CFMPaymentRequestTable.cdm.json/CFMPaymentRequestTable</a></td><td><a href="../WorksheetHeader/CFMPaymentRequestTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyInfoRelationshipId name="Relationship_CompanyInfoRelationshipId">Relationship_CompanyInfoRelationshipId</a>

First included in: Transaction/CFMAnalyticDataEditUncommitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyInfoRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CustTransOpenRelationshipId name="Relationship_CustTransOpenRelationshipId">Relationship_CustTransOpenRelationshipId</a>

First included in: Transaction/CFMAnalyticDataEditUncommitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTransOpenRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Transaction/CustTransOpen.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Transaction/CustTransOpen.cdm.json/CustTransOpen</a></td><td><a href="../../AccountsReceivable/Transaction/CustTransOpen.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTransOpenRelationshipId name="Relationship_VendTransOpenRelationshipId">Relationship_VendTransOpenRelationshipId</a>

First included in: Transaction/CFMAnalyticDataEditUncommitted (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTransOpenRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsPayable/Transaction/VendTransOpen.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Transaction/VendTransOpen.cdm.json/VendTransOpen</a></td><td><a href="../../AccountsPayable/Transaction/VendTransOpen.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
