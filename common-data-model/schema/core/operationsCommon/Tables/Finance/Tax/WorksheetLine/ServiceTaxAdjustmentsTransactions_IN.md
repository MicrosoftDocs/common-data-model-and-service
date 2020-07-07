---
title: ServiceTaxAdjustmentsTransactions_IN in WorksheetLine - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Service tax transactions in WorksheetLine

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/WorksheetLine/ServiceTaxAdjustmentsTransactions_IN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ServiceTaxAdjustmentsTransactions_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Service tax transactions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ServiceTaxAdjustmentsTransactions_IN.md" target="_blank">WorksheetLine/ServiceTaxAdjustmentsTransactions_IN</a>|
|[PayableAmountMST](#PayableAmountMST)||<a href="ServiceTaxAdjustmentsTransactions_IN.md" target="_blank">WorksheetLine/ServiceTaxAdjustmentsTransactions_IN</a>|
|[Posted](#Posted)||<a href="ServiceTaxAdjustmentsTransactions_IN.md" target="_blank">WorksheetLine/ServiceTaxAdjustmentsTransactions_IN</a>|
|[RecoverableAmountMST](#RecoverableAmountMST)||<a href="ServiceTaxAdjustmentsTransactions_IN.md" target="_blank">WorksheetLine/ServiceTaxAdjustmentsTransactions_IN</a>|
|[ServiceTaxAdjustments](#ServiceTaxAdjustments)||<a href="ServiceTaxAdjustmentsTransactions_IN.md" target="_blank">WorksheetLine/ServiceTaxAdjustmentsTransactions_IN</a>|
|[ServiceTaxAdjustmentsTransactions](#ServiceTaxAdjustmentsTransactions)||<a href="ServiceTaxAdjustmentsTransactions_IN.md" target="_blank">WorksheetLine/ServiceTaxAdjustmentsTransactions_IN</a>|
|[TaxPaymentVoucher](#TaxPaymentVoucher)||<a href="ServiceTaxAdjustmentsTransactions_IN.md" target="_blank">WorksheetLine/ServiceTaxAdjustmentsTransactions_IN</a>|
|[TaxTrans](#TaxTrans)||<a href="ServiceTaxAdjustmentsTransactions_IN.md" target="_blank">WorksheetLine/ServiceTaxAdjustmentsTransactions_IN</a>|
|[UtilizedPayableAmountMST](#UtilizedPayableAmountMST)||<a href="ServiceTaxAdjustmentsTransactions_IN.md" target="_blank">WorksheetLine/ServiceTaxAdjustmentsTransactions_IN</a>|
|[UtilizedRecoverableAmountMST](#UtilizedRecoverableAmountMST)||<a href="ServiceTaxAdjustmentsTransactions_IN.md" target="_blank">WorksheetLine/ServiceTaxAdjustmentsTransactions_IN</a>|
|[DataAreaId](#DataAreaId)||<a href="ServiceTaxAdjustmentsTransactions_IN.md" target="_blank">WorksheetLine/ServiceTaxAdjustmentsTransactions_IN</a>|
|[Relationship_ServiceTaxAdjustmentsRelationshipId](#Relationship_ServiceTaxAdjustmentsRelationshipId)||<a href="ServiceTaxAdjustmentsTransactions_IN.md" target="_blank">WorksheetLine/ServiceTaxAdjustmentsTransactions_IN</a>|
|[Relationship_TaxTransRelationshipId](#Relationship_TaxTransRelationshipId)||<a href="ServiceTaxAdjustmentsTransactions_IN.md" target="_blank">WorksheetLine/ServiceTaxAdjustmentsTransactions_IN</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="ServiceTaxAdjustmentsTransactions_IN.md" target="_blank">WorksheetLine/ServiceTaxAdjustmentsTransactions_IN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/ServiceTaxAdjustmentsTransactions_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ServiceTaxAdjustmentsTransactions_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PayableAmountMST name="PayableAmountMST">PayableAmountMST</a>

First included in: WorksheetLine/ServiceTaxAdjustmentsTransactions_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payable amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayableAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payable amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Posted name="Posted">Posted</a>

First included in: WorksheetLine/ServiceTaxAdjustmentsTransactions_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Posted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RecoverableAmountMST name="RecoverableAmountMST">RecoverableAmountMST</a>

First included in: WorksheetLine/ServiceTaxAdjustmentsTransactions_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recoverable amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecoverableAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Recoverable amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ServiceTaxAdjustments name="ServiceTaxAdjustments">ServiceTaxAdjustments</a>

First included in: WorksheetLine/ServiceTaxAdjustmentsTransactions_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceTaxAdjustments attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ServiceTaxAdjustmentsTransactions name="ServiceTaxAdjustmentsTransactions">ServiceTaxAdjustmentsTransactions</a>

First included in: WorksheetLine/ServiceTaxAdjustmentsTransactions_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceTaxAdjustmentsTransactions attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#TaxPaymentVoucher name="TaxPaymentVoucher">TaxPaymentVoucher</a>

First included in: WorksheetLine/ServiceTaxAdjustmentsTransactions_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPaymentVoucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxTrans name="TaxTrans">TaxTrans</a>

First included in: WorksheetLine/ServiceTaxAdjustmentsTransactions_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UtilizedPayableAmountMST name="UtilizedPayableAmountMST">UtilizedPayableAmountMST</a>

First included in: WorksheetLine/ServiceTaxAdjustmentsTransactions_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UtilizedPayableAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#UtilizedRecoverableAmountMST name="UtilizedRecoverableAmountMST">UtilizedRecoverableAmountMST</a>

First included in: WorksheetLine/ServiceTaxAdjustmentsTransactions_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UtilizedRecoverableAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/ServiceTaxAdjustmentsTransactions_IN (this entity)  

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

### <a href=#Relationship_ServiceTaxAdjustmentsRelationshipId name="Relationship_ServiceTaxAdjustmentsRelationshipId">Relationship_ServiceTaxAdjustmentsRelationshipId</a>

First included in: WorksheetLine/ServiceTaxAdjustmentsTransactions_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ServiceTaxAdjustmentsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/ServiceTaxAdjustments_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/WorksheetHeader/ServiceTaxAdjustments_IN.cdm.json/ServiceTaxAdjustments_IN</a></td><td><a href="../WorksheetHeader/ServiceTaxAdjustments_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxTransRelationshipId name="Relationship_TaxTransRelationshipId">Relationship_TaxTransRelationshipId</a>

First included in: WorksheetLine/ServiceTaxAdjustmentsTransactions_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/TaxTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Transaction/TaxTrans.cdm.json/TaxTrans</a></td><td><a href="../Transaction/TaxTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/ServiceTaxAdjustmentsTransactions_IN (this entity)  

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
