---
title: TaxSalesTaxPaymentTaxAdjustments_IN - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Adjustment

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/Transaction/TaxSalesTaxPaymentTaxAdjustments_IN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxSalesTaxPaymentTaxAdjustments_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Adjustment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxSalesTaxPaymentTaxAdjustments_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentTaxAdjustments_IN</a>|
|[SettledPayableAmountMST](#SettledPayableAmountMST)||<a href="TaxSalesTaxPaymentTaxAdjustments_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentTaxAdjustments_IN</a>|
|[SettledRecoverableAmountMST](#SettledRecoverableAmountMST)||<a href="TaxSalesTaxPaymentTaxAdjustments_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentTaxAdjustments_IN</a>|
|[TaxReportPeriod_IN](#TaxReportPeriod_IN)||<a href="TaxSalesTaxPaymentTaxAdjustments_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentTaxAdjustments_IN</a>|
|[TaxSalesTaxPaymentHistoryDetailsTrans_IN](#TaxSalesTaxPaymentHistoryDetailsTrans_IN)||<a href="TaxSalesTaxPaymentTaxAdjustments_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentTaxAdjustments_IN</a>|
|[TaxTrans_IN](#TaxTrans_IN)||<a href="TaxSalesTaxPaymentTaxAdjustments_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentTaxAdjustments_IN</a>|
|[UtilizedPayableAmountMST](#UtilizedPayableAmountMST)||<a href="TaxSalesTaxPaymentTaxAdjustments_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentTaxAdjustments_IN</a>|
|[UtilizedRecoverableAmountMST](#UtilizedRecoverableAmountMST)||<a href="TaxSalesTaxPaymentTaxAdjustments_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentTaxAdjustments_IN</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxSalesTaxPaymentTaxAdjustments_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentTaxAdjustments_IN</a>|
|[Relationship_TaxReportPeriod_INRelationshipId](#Relationship_TaxReportPeriod_INRelationshipId)||<a href="TaxSalesTaxPaymentTaxAdjustments_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentTaxAdjustments_IN</a>|
|[Relationship_TaxSalesTaxPaymentHistoryDetailsTrans_INRelationshipId](#Relationship_TaxSalesTaxPaymentHistoryDetailsTrans_INRelationshipId)||<a href="TaxSalesTaxPaymentTaxAdjustments_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentTaxAdjustments_IN</a>|
|[Relationship_TaxTrans_INRelationshipId](#Relationship_TaxTrans_INRelationshipId)||<a href="TaxSalesTaxPaymentTaxAdjustments_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentTaxAdjustments_IN</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxSalesTaxPaymentTaxAdjustments_IN.md" target="_blank">Transaction/TaxSalesTaxPaymentTaxAdjustments_IN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/TaxSalesTaxPaymentTaxAdjustments_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxSalesTaxPaymentTaxAdjustments_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SettledPayableAmountMST name="SettledPayableAmountMST">SettledPayableAmountMST</a>

First included in: Transaction/TaxSalesTaxPaymentTaxAdjustments_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Settled payable amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettledPayableAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Settled payable amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SettledRecoverableAmountMST name="SettledRecoverableAmountMST">SettledRecoverableAmountMST</a>

First included in: Transaction/TaxSalesTaxPaymentTaxAdjustments_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Settled Recoverable Amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettledRecoverableAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Settled Recoverable Amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxReportPeriod_IN name="TaxReportPeriod_IN">TaxReportPeriod_IN</a>

First included in: Transaction/TaxSalesTaxPaymentTaxAdjustments_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReportPeriod_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxSalesTaxPaymentHistoryDetailsTrans_IN name="TaxSalesTaxPaymentHistoryDetailsTrans_IN">TaxSalesTaxPaymentHistoryDetailsTrans_IN</a>

First included in: Transaction/TaxSalesTaxPaymentTaxAdjustments_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxSalesTaxPaymentHistoryDetailsTrans_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxTrans_IN name="TaxTrans_IN">TaxTrans_IN</a>

First included in: Transaction/TaxSalesTaxPaymentTaxAdjustments_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxTrans_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UtilizedPayableAmountMST name="UtilizedPayableAmountMST">UtilizedPayableAmountMST</a>

First included in: Transaction/TaxSalesTaxPaymentTaxAdjustments_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UtilizedPayableAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#UtilizedRecoverableAmountMST name="UtilizedRecoverableAmountMST">UtilizedRecoverableAmountMST</a>

First included in: Transaction/TaxSalesTaxPaymentTaxAdjustments_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UtilizedRecoverableAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/TaxSalesTaxPaymentTaxAdjustments_IN (this entity)  

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

### <a href=#Relationship_TaxReportPeriod_INRelationshipId name="Relationship_TaxReportPeriod_INRelationshipId">Relationship_TaxReportPeriod_INRelationshipId</a>

First included in: Transaction/TaxSalesTaxPaymentTaxAdjustments_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportPeriod_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportPeriod_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Transaction/TaxReportPeriod_IN.cdm.json/TaxReportPeriod_IN</a></td><td><a href="TaxReportPeriod_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxSalesTaxPaymentHistoryDetailsTrans_INRelationshipId name="Relationship_TaxSalesTaxPaymentHistoryDetailsTrans_INRelationshipId">Relationship_TaxSalesTaxPaymentHistoryDetailsTrans_INRelationshipId</a>

First included in: Transaction/TaxSalesTaxPaymentTaxAdjustments_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxSalesTaxPaymentHistoryDetailsTrans_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxSalesTaxPaymentHistoryDetailsTrans_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Transaction/TaxSalesTaxPaymentHistoryDetailsTrans_IN.cdm.json/TaxSalesTaxPaymentHistoryDetailsTrans_IN</a></td><td><a href="TaxSalesTaxPaymentHistoryDetailsTrans_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxTrans_INRelationshipId name="Relationship_TaxTrans_INRelationshipId">Relationship_TaxTrans_INRelationshipId</a>

First included in: Transaction/TaxSalesTaxPaymentTaxAdjustments_IN (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxTrans_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Transaction/TaxTrans_IN.cdm.json/TaxTrans_IN</a></td><td><a href="TaxTrans_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/TaxSalesTaxPaymentTaxAdjustments_IN (this entity)  

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
