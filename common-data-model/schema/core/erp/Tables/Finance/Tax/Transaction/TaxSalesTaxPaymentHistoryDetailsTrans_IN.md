---
title: TaxSalesTaxPaymentHistoryDetailsTrans_IN - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# TaxSalesTaxPaymentHistoryDetailsTrans_IN

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/Tax/Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxSalesTaxPaymentHistoryDetailsTrans_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxSalesTaxPaymentHistoryDetailsTrans_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN</a>|
|[Mark](#Mark)||<a href="TaxSalesTaxPaymentHistoryDetailsTrans_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN</a>|
|[PayableAmountMST](#PayableAmountMST)||<a href="TaxSalesTaxPaymentHistoryDetailsTrans_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN</a>|
|[PayableAmountToSettle](#PayableAmountToSettle)||<a href="TaxSalesTaxPaymentHistoryDetailsTrans_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN</a>|
|[RecoverableAmountMST](#RecoverableAmountMST)||<a href="TaxSalesTaxPaymentHistoryDetailsTrans_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN</a>|
|[RecoverableAmountToSettle](#RecoverableAmountToSettle)||<a href="TaxSalesTaxPaymentHistoryDetailsTrans_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN</a>|
|[Source](#Source)||<a href="TaxSalesTaxPaymentHistoryDetailsTrans_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN</a>|
|[TaxCode](#TaxCode)||<a href="TaxSalesTaxPaymentHistoryDetailsTrans_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN</a>|
|[TaxRegistrationNumbers_IN](#TaxRegistrationNumbers_IN)||<a href="TaxSalesTaxPaymentHistoryDetailsTrans_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN</a>|
|[TaxSalesTaxPaymentHistoryDetails_IN](#TaxSalesTaxPaymentHistoryDetails_IN)||<a href="TaxSalesTaxPaymentHistoryDetailsTrans_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN</a>|
|[TaxTrans_IN](#TaxTrans_IN)||<a href="TaxSalesTaxPaymentHistoryDetailsTrans_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN</a>|
|[TaxType](#TaxType)||<a href="TaxSalesTaxPaymentHistoryDetailsTrans_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN</a>|
|[TransDate](#TransDate)||<a href="TaxSalesTaxPaymentHistoryDetailsTrans_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN</a>|
|[UtilizedPayableAmountMST](#UtilizedPayableAmountMST)||<a href="TaxSalesTaxPaymentHistoryDetailsTrans_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN</a>|
|[UtilizedRecoverableAmountMST](#UtilizedRecoverableAmountMST)||<a href="TaxSalesTaxPaymentHistoryDetailsTrans_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN</a>|
|[Voucher](#Voucher)||<a href="TaxSalesTaxPaymentHistoryDetailsTrans_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxSalesTaxPaymentHistoryDetailsTrans_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN</a>|
|[Relationship_TaxRegistrationNumbers_INRelationshipId](#Relationship_TaxRegistrationNumbers_INRelationshipId)||<a href="TaxSalesTaxPaymentHistoryDetailsTrans_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN</a>|
|[Relationship_TaxSalesTaxPaymentHistoryDetails_INRelationshipId](#Relationship_TaxSalesTaxPaymentHistoryDetails_INRelationshipId)||<a href="TaxSalesTaxPaymentHistoryDetailsTrans_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN</a>|
|[Relationship_TaxTableRelationshipId](#Relationship_TaxTableRelationshipId)||<a href="TaxSalesTaxPaymentHistoryDetailsTrans_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN</a>|
|[Relationship_TaxTrans_INRelationshipId](#Relationship_TaxTrans_INRelationshipId)||<a href="TaxSalesTaxPaymentHistoryDetailsTrans_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxSalesTaxPaymentHistoryDetailsTrans_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxSalesTaxPaymentHistoryDetailsTrans_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Mark name="Mark">Mark</a>

First included in: Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Mark attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PayableAmountMST name="PayableAmountMST">PayableAmountMST</a>

First included in: Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayableAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PayableAmountToSettle name="PayableAmountToSettle">PayableAmountToSettle</a>

First included in: Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayableAmountToSettle attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RecoverableAmountMST name="RecoverableAmountMST">RecoverableAmountMST</a>

First included in: Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecoverableAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RecoverableAmountToSettle name="RecoverableAmountToSettle">RecoverableAmountToSettle</a>

First included in: Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecoverableAmountToSettle attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Source name="Source">Source</a>

First included in: Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Source attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxCode name="TaxCode">TaxCode</a>

First included in: Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN (this entity)  

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

### <a href=#TaxRegistrationNumbers_IN name="TaxRegistrationNumbers_IN">TaxRegistrationNumbers_IN</a>

First included in: Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRegistrationNumbers_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxSalesTaxPaymentHistoryDetails_IN name="TaxSalesTaxPaymentHistoryDetails_IN">TaxSalesTaxPaymentHistoryDetails_IN</a>

First included in: Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxSalesTaxPaymentHistoryDetails_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxTrans_IN name="TaxTrans_IN">TaxTrans_IN</a>

First included in: Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxTrans_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxType name="TaxType">TaxType</a>

First included in: Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#UtilizedPayableAmountMST name="UtilizedPayableAmountMST">UtilizedPayableAmountMST</a>

First included in: Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UtilizedPayableAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#UtilizedRecoverableAmountMST name="UtilizedRecoverableAmountMST">UtilizedRecoverableAmountMST</a>

First included in: Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UtilizedRecoverableAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Voucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN (this entity)  

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

### <a href=#Relationship_TaxRegistrationNumbers_INRelationshipId name="Relationship_TaxRegistrationNumbers_INRelationshipId">Relationship_TaxRegistrationNumbers_INRelationshipId</a>

First included in: Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxRegistrationNumbers_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/TaxRegistrationNumbers_IN.md" target="_blank">/core/erp/Tables/Finance/Tax/Main/TaxRegistrationNumbers_IN.cdm.json/TaxRegistrationNumbers_IN</a></td><td><a href="../Main/TaxRegistrationNumbers_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxSalesTaxPaymentHistoryDetails_INRelationshipId name="Relationship_TaxSalesTaxPaymentHistoryDetails_INRelationshipId">Relationship_TaxSalesTaxPaymentHistoryDetails_INRelationshipId</a>

First included in: Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxSalesTaxPaymentHistoryDetails_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxSalesTaxPaymentHistoryDetails_IN.md" target="_blank">/core/erp/Tables/Finance/Tax/Transaction/TaxSalesTaxPaymentHistoryDetails_IN.cdm.json/TaxSalesTaxPaymentHistoryDetails_IN</a></td><td><a href="TaxSalesTaxPaymentHistoryDetails_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxTableRelationshipId name="Relationship_TaxTableRelationshipId">Relationship_TaxTableRelationshipId</a>

First included in: Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/TaxTable.md" target="_blank">/core/erp/Tables/Finance/Tax/Group/TaxTable.cdm.json/TaxTable</a></td><td><a href="../Group/TaxTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxTrans_INRelationshipId name="Relationship_TaxTrans_INRelationshipId">Relationship_TaxTrans_INRelationshipId</a>

First included in: Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxTrans_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxTrans_IN.md" target="_blank">/core/erp/Tables/Finance/Tax/Transaction/TaxTrans_IN.cdm.json/TaxTrans_IN</a></td><td><a href="TaxTrans_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN (this entity)  

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
