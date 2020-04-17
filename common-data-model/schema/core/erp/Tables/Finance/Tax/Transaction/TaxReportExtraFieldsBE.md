---
title: TaxReportExtraFieldsBE - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# TaxReportExtraFieldsBE

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/Tax/Transaction/TaxReportExtraFieldsBE.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxReportExtraFieldsBE/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxReportExtraFieldsBE.md" target="_blank">Transaction/TaxReportExtraFieldsBE</a>|
|[FromDate](#FromDate)||<a href="TaxReportExtraFieldsBE.md" target="_blank">Transaction/TaxReportExtraFieldsBE</a>|
|[NihilAnnualListing](#NihilAnnualListing)||<a href="TaxReportExtraFieldsBE.md" target="_blank">Transaction/TaxReportExtraFieldsBE</a>|
|[PaymentFormOrder](#PaymentFormOrder)||<a href="TaxReportExtraFieldsBE.md" target="_blank">Transaction/TaxReportExtraFieldsBE</a>|
|[Reimbursement](#Reimbursement)||<a href="TaxReportExtraFieldsBE.md" target="_blank">Transaction/TaxReportExtraFieldsBE</a>|
|[TaxPeriod](#TaxPeriod)||<a href="TaxReportExtraFieldsBE.md" target="_blank">Transaction/TaxReportExtraFieldsBE</a>|
|[ToDate](#ToDate)||<a href="TaxReportExtraFieldsBE.md" target="_blank">Transaction/TaxReportExtraFieldsBE</a>|
|[TransDate](#TransDate)||<a href="TaxReportExtraFieldsBE.md" target="_blank">Transaction/TaxReportExtraFieldsBE</a>|
|[VATDisbursement](#VATDisbursement)||<a href="TaxReportExtraFieldsBE.md" target="_blank">Transaction/TaxReportExtraFieldsBE</a>|
|[Voucher](#Voucher)||<a href="TaxReportExtraFieldsBE.md" target="_blank">Transaction/TaxReportExtraFieldsBE</a>|
|[AdjustedValue](#AdjustedValue)||<a href="TaxReportExtraFieldsBE.md" target="_blank">Transaction/TaxReportExtraFieldsBE</a>|
|[SpecialPercentageB1](#SpecialPercentageB1)||<a href="TaxReportExtraFieldsBE.md" target="_blank">Transaction/TaxReportExtraFieldsBE</a>|
|[SpecialPercentageB2](#SpecialPercentageB2)||<a href="TaxReportExtraFieldsBE.md" target="_blank">Transaction/TaxReportExtraFieldsBE</a>|
|[SpecialPercentageB3](#SpecialPercentageB3)||<a href="TaxReportExtraFieldsBE.md" target="_blank">Transaction/TaxReportExtraFieldsBE</a>|
|[SpecialPercentageB4](#SpecialPercentageB4)||<a href="TaxReportExtraFieldsBE.md" target="_blank">Transaction/TaxReportExtraFieldsBE</a>|
|[SpecialPercentageB5](#SpecialPercentageB5)||<a href="TaxReportExtraFieldsBE.md" target="_blank">Transaction/TaxReportExtraFieldsBE</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxReportExtraFieldsBE.md" target="_blank">Transaction/TaxReportExtraFieldsBE</a>|
|[Relationship_TaxPeriodHeadRelationshipId](#Relationship_TaxPeriodHeadRelationshipId)||<a href="TaxReportExtraFieldsBE.md" target="_blank">Transaction/TaxReportExtraFieldsBE</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxReportExtraFieldsBE.md" target="_blank">Transaction/TaxReportExtraFieldsBE</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/TaxReportExtraFieldsBE (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxReportExtraFieldsBE/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FromDate name="FromDate">FromDate</a>

First included in: Transaction/TaxReportExtraFieldsBE (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#NihilAnnualListing name="NihilAnnualListing">NihilAnnualListing</a>

First included in: Transaction/TaxReportExtraFieldsBE (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NihilAnnualListing attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PaymentFormOrder name="PaymentFormOrder">PaymentFormOrder</a>

First included in: Transaction/TaxReportExtraFieldsBE (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentFormOrder attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Reimbursement name="Reimbursement">Reimbursement</a>

First included in: Transaction/TaxReportExtraFieldsBE (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Reimbursement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxPeriod name="TaxPeriod">TaxPeriod</a>

First included in: Transaction/TaxReportExtraFieldsBE (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToDate name="ToDate">ToDate</a>

First included in: Transaction/TaxReportExtraFieldsBE (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: Transaction/TaxReportExtraFieldsBE (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#VATDisbursement name="VATDisbursement">VATDisbursement</a>

First included in: Transaction/TaxReportExtraFieldsBE (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATDisbursement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: Transaction/TaxReportExtraFieldsBE (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Voucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdjustedValue name="AdjustedValue">AdjustedValue</a>

First included in: Transaction/TaxReportExtraFieldsBE (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdjustedValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SpecialPercentageB1 name="SpecialPercentageB1">SpecialPercentageB1</a>

First included in: Transaction/TaxReportExtraFieldsBE (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialPercentageB1 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SpecialPercentageB2 name="SpecialPercentageB2">SpecialPercentageB2</a>

First included in: Transaction/TaxReportExtraFieldsBE (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialPercentageB2 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SpecialPercentageB3 name="SpecialPercentageB3">SpecialPercentageB3</a>

First included in: Transaction/TaxReportExtraFieldsBE (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialPercentageB3 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SpecialPercentageB4 name="SpecialPercentageB4">SpecialPercentageB4</a>

First included in: Transaction/TaxReportExtraFieldsBE (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialPercentageB4 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SpecialPercentageB5 name="SpecialPercentageB5">SpecialPercentageB5</a>

First included in: Transaction/TaxReportExtraFieldsBE (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialPercentageB5 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/TaxReportExtraFieldsBE (this entity)  

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

### <a href=#Relationship_TaxPeriodHeadRelationshipId name="Relationship_TaxPeriodHeadRelationshipId">Relationship_TaxPeriodHeadRelationshipId</a>

First included in: Transaction/TaxReportExtraFieldsBE (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxPeriodHeadRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/TaxPeriodHead.md" target="_blank">/core/erp/Tables/Finance/Tax/Group/TaxPeriodHead.cdm.json/TaxPeriodHead</a></td><td><a href="../Group/TaxPeriodHead.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/TaxReportExtraFieldsBE (this entity)  

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
