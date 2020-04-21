---
title: FBFiscalDocumentAdjustment_BR - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# FBFiscalDocumentAdjustment_BR

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FBFiscalDocumentAdjustment_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBFiscalDocumentAdjustment_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">Transaction/FBFiscalDocumentAdjustment_BR</a>|
|[CancelTransDate](#CancelTransDate)||<a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">Transaction/FBFiscalDocumentAdjustment_BR</a>|
|[CancelVoucher](#CancelVoucher)||<a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">Transaction/FBFiscalDocumentAdjustment_BR</a>|
|[ComplementaryDescription](#ComplementaryDescription)||<a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">Transaction/FBFiscalDocumentAdjustment_BR</a>|
|[CreatePayment](#CreatePayment)||<a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">Transaction/FBFiscalDocumentAdjustment_BR</a>|
|[FBFiscalDocumentAdjustmentCodeICMS_BR](#FBFiscalDocumentAdjustmentCodeICMS_BR)||<a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">Transaction/FBFiscalDocumentAdjustment_BR</a>|
|[FBObservationCodeTable_BR](#FBObservationCodeTable_BR)||<a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">Transaction/FBFiscalDocumentAdjustment_BR</a>|
|[FBTaxAssessment_BR](#FBTaxAssessment_BR)||<a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">Transaction/FBFiscalDocumentAdjustment_BR</a>|
|[FiscalDocumentTaxTrans_BR](#FiscalDocumentTaxTrans_BR)||<a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">Transaction/FBFiscalDocumentAdjustment_BR</a>|
|[FiscalEstablishmentId](#FiscalEstablishmentId)||<a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">Transaction/FBFiscalDocumentAdjustment_BR</a>|
|[IsCancelled](#IsCancelled)||<a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">Transaction/FBFiscalDocumentAdjustment_BR</a>|
|[State](#State)||<a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">Transaction/FBFiscalDocumentAdjustment_BR</a>|
|[TaxAmount](#TaxAmount)||<a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">Transaction/FBFiscalDocumentAdjustment_BR</a>|
|[TaxAmountOther](#TaxAmountOther)||<a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">Transaction/FBFiscalDocumentAdjustment_BR</a>|
|[TaxBaseAmount](#TaxBaseAmount)||<a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">Transaction/FBFiscalDocumentAdjustment_BR</a>|
|[TaxType_BR](#TaxType_BR)||<a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">Transaction/FBFiscalDocumentAdjustment_BR</a>|
|[TaxValue](#TaxValue)||<a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">Transaction/FBFiscalDocumentAdjustment_BR</a>|
|[TransDate](#TransDate)||<a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">Transaction/FBFiscalDocumentAdjustment_BR</a>|
|[Voucher](#Voucher)||<a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">Transaction/FBFiscalDocumentAdjustment_BR</a>|
|[VoucherDataArea](#VoucherDataArea)||<a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">Transaction/FBFiscalDocumentAdjustment_BR</a>|
|[IsPovertyFund](#IsPovertyFund)||<a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">Transaction/FBFiscalDocumentAdjustment_BR</a>|
|[FBGeneralAdjustmentCode_BR](#FBGeneralAdjustmentCode_BR)||<a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">Transaction/FBFiscalDocumentAdjustment_BR</a>|
|[Relationship_FBFiscalDocumentAdjustmentCodeICMS_BRRelationshipId](#Relationship_FBFiscalDocumentAdjustmentCodeICMS_BRRelationshipId)||<a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">Transaction/FBFiscalDocumentAdjustment_BR</a>|
|[Relationship_FBObservationCodeTable_BRRelationshipId](#Relationship_FBObservationCodeTable_BRRelationshipId)||<a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">Transaction/FBFiscalDocumentAdjustment_BR</a>|
|[Relationship_FBTaxAssessment_BRRelationshipId](#Relationship_FBTaxAssessment_BRRelationshipId)||<a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">Transaction/FBFiscalDocumentAdjustment_BR</a>|
|[Relationship_FiscalDocumentTaxTrans_BRRelationshipId](#Relationship_FiscalDocumentTaxTrans_BRRelationshipId)||<a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">Transaction/FBFiscalDocumentAdjustment_BR</a>|
|[Relationship_FBGeneralAdjustmentCode_BRRelationshipId](#Relationship_FBGeneralAdjustmentCode_BRRelationshipId)||<a href="FBFiscalDocumentAdjustment_BR.md" target="_blank">Transaction/FBFiscalDocumentAdjustment_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/FBFiscalDocumentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBFiscalDocumentAdjustment_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CancelTransDate name="CancelTransDate">CancelTransDate</a>

First included in: Transaction/FBFiscalDocumentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CancelTransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#CancelVoucher name="CancelVoucher">CancelVoucher</a>

First included in: Transaction/FBFiscalDocumentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CancelVoucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ComplementaryDescription name="ComplementaryDescription">ComplementaryDescription</a>

First included in: Transaction/FBFiscalDocumentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ComplementaryDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreatePayment name="CreatePayment">CreatePayment</a>

First included in: Transaction/FBFiscalDocumentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreatePayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FBFiscalDocumentAdjustmentCodeICMS_BR name="FBFiscalDocumentAdjustmentCodeICMS_BR">FBFiscalDocumentAdjustmentCodeICMS_BR</a>

First included in: Transaction/FBFiscalDocumentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBFiscalDocumentAdjustmentCodeICMS_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FBObservationCodeTable_BR name="FBObservationCodeTable_BR">FBObservationCodeTable_BR</a>

First included in: Transaction/FBFiscalDocumentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBObservationCodeTable_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FBTaxAssessment_BR name="FBTaxAssessment_BR">FBTaxAssessment_BR</a>

First included in: Transaction/FBFiscalDocumentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBTaxAssessment_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FiscalDocumentTaxTrans_BR name="FiscalDocumentTaxTrans_BR">FiscalDocumentTaxTrans_BR</a>

First included in: Transaction/FBFiscalDocumentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentTaxTrans_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FiscalEstablishmentId name="FiscalEstablishmentId">FiscalEstablishmentId</a>

First included in: Transaction/FBFiscalDocumentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCancelled name="IsCancelled">IsCancelled</a>

First included in: Transaction/FBFiscalDocumentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCancelled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#State name="State">State</a>

First included in: Transaction/FBFiscalDocumentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the State attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmount name="TaxAmount">TaxAmount</a>

First included in: Transaction/FBFiscalDocumentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxAmountOther name="TaxAmountOther">TaxAmountOther</a>

First included in: Transaction/FBFiscalDocumentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountOther attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxBaseAmount name="TaxBaseAmount">TaxBaseAmount</a>

First included in: Transaction/FBFiscalDocumentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxType_BR name="TaxType_BR">TaxType_BR</a>

First included in: Transaction/FBFiscalDocumentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxType_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxValue name="TaxValue">TaxValue</a>

First included in: Transaction/FBFiscalDocumentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: Transaction/FBFiscalDocumentAdjustment_BR (this entity)  

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

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: Transaction/FBFiscalDocumentAdjustment_BR (this entity)  

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

### <a href=#VoucherDataArea name="VoucherDataArea">VoucherDataArea</a>

First included in: Transaction/FBFiscalDocumentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoucherDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPovertyFund name="IsPovertyFund">IsPovertyFund</a>

First included in: Transaction/FBFiscalDocumentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPovertyFund attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FBGeneralAdjustmentCode_BR name="FBGeneralAdjustmentCode_BR">FBGeneralAdjustmentCode_BR</a>

First included in: Transaction/FBFiscalDocumentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBGeneralAdjustmentCode_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_FBFiscalDocumentAdjustmentCodeICMS_BRRelationshipId name="Relationship_FBFiscalDocumentAdjustmentCodeICMS_BRRelationshipId">Relationship_FBFiscalDocumentAdjustmentCodeICMS_BRRelationshipId</a>

First included in: Transaction/FBFiscalDocumentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBFiscalDocumentAdjustmentCodeICMS_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FBFiscalDocumentAdjustmentCodeICMS_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBFiscalDocumentAdjustmentCodeICMS_BR.cdm.json/FBFiscalDocumentAdjustmentCodeICMS_BR</a></td><td><a href="../Main/FBFiscalDocumentAdjustmentCodeICMS_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBObservationCodeTable_BRRelationshipId name="Relationship_FBObservationCodeTable_BRRelationshipId">Relationship_FBObservationCodeTable_BRRelationshipId</a>

First included in: Transaction/FBFiscalDocumentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBObservationCodeTable_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FBObservationCodeTable_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBObservationCodeTable_BR.cdm.json/FBObservationCodeTable_BR</a></td><td><a href="../Main/FBObservationCodeTable_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBTaxAssessment_BRRelationshipId name="Relationship_FBTaxAssessment_BRRelationshipId">Relationship_FBTaxAssessment_BRRelationshipId</a>

First included in: Transaction/FBFiscalDocumentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBTaxAssessment_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="FBTaxAssessment_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FBTaxAssessment_BR.cdm.json/FBTaxAssessment_BR</a></td><td><a href="FBTaxAssessment_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalDocumentTaxTrans_BRRelationshipId name="Relationship_FiscalDocumentTaxTrans_BRRelationshipId">Relationship_FiscalDocumentTaxTrans_BRRelationshipId</a>

First included in: Transaction/FBFiscalDocumentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalDocumentTaxTrans_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="FiscalDocumentTaxTrans_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FiscalDocumentTaxTrans_BR.cdm.json/FiscalDocumentTaxTrans_BR</a></td><td><a href="FiscalDocumentTaxTrans_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FBGeneralAdjustmentCode_BRRelationshipId name="Relationship_FBGeneralAdjustmentCode_BRRelationshipId">Relationship_FBGeneralAdjustmentCode_BRRelationshipId</a>

First included in: Transaction/FBFiscalDocumentAdjustment_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBGeneralAdjustmentCode_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FBGeneralAdjustmentCode_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBGeneralAdjustmentCode_BR.cdm.json/FBGeneralAdjustmentCode_BR</a></td><td><a href="../Main/FBGeneralAdjustmentCode_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
