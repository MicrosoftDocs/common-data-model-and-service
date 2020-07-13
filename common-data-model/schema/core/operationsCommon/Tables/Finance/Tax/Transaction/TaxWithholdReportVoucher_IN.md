---
title: TaxWithholdReportVoucher_IN in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Withholding tax payment in Transaction(TaxWithholdReportVoucher_IN)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/Transaction/TaxWithholdReportVoucher_IN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxWithholdReportVoucher_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Withholding tax payment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxWithholdReportVoucher_IN.md" target="_blank">Transaction/TaxWithholdReportVoucher_IN</a>|
|[FromDate](#FromDate)||<a href="TaxWithholdReportVoucher_IN.md" target="_blank">Transaction/TaxWithholdReportVoucher_IN</a>|
|[PaymentVersion](#PaymentVersion)||<a href="TaxWithholdReportVoucher_IN.md" target="_blank">Transaction/TaxWithholdReportVoucher_IN</a>|
|[TaxRepCounter](#TaxRepCounter)||<a href="TaxWithholdReportVoucher_IN.md" target="_blank">Transaction/TaxWithholdReportVoucher_IN</a>|
|[TaxType](#TaxType)||<a href="TaxWithholdReportVoucher_IN.md" target="_blank">Transaction/TaxWithholdReportVoucher_IN</a>|
|[TaxWithholdRegNumber](#TaxWithholdRegNumber)||<a href="TaxWithholdReportVoucher_IN.md" target="_blank">Transaction/TaxWithholdReportVoucher_IN</a>|
|[TaxWithholdSettlementPeriod](#TaxWithholdSettlementPeriod)||<a href="TaxWithholdReportVoucher_IN.md" target="_blank">Transaction/TaxWithholdReportVoucher_IN</a>|
|[ToDate](#ToDate)||<a href="TaxWithholdReportVoucher_IN.md" target="_blank">Transaction/TaxWithholdReportVoucher_IN</a>|
|[TransDate](#TransDate)||<a href="TaxWithholdReportVoucher_IN.md" target="_blank">Transaction/TaxWithholdReportVoucher_IN</a>|
|[Voucher](#Voucher)||<a href="TaxWithholdReportVoucher_IN.md" target="_blank">Transaction/TaxWithholdReportVoucher_IN</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxWithholdReportVoucher_IN.md" target="_blank">Transaction/TaxWithholdReportVoucher_IN</a>|
|[Relationship_GeneralJournalEntryRelationshipId](#Relationship_GeneralJournalEntryRelationshipId)||<a href="TaxWithholdReportVoucher_IN.md" target="_blank">Transaction/TaxWithholdReportVoucher_IN</a>|
|[Relationship_TaxWithholdHeadRelationshipId](#Relationship_TaxWithholdHeadRelationshipId)||<a href="TaxWithholdReportVoucher_IN.md" target="_blank">Transaction/TaxWithholdReportVoucher_IN</a>|
|[Relationship_taxWithholdRegNumberRelationshipId](#Relationship_taxWithholdRegNumberRelationshipId)||<a href="TaxWithholdReportVoucher_IN.md" target="_blank">Transaction/TaxWithholdReportVoucher_IN</a>|
|[Relationship_TaxWithholdSettleTransRelationshipId](#Relationship_TaxWithholdSettleTransRelationshipId)||<a href="TaxWithholdReportVoucher_IN.md" target="_blank">Transaction/TaxWithholdReportVoucher_IN</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxWithholdReportVoucher_IN.md" target="_blank">Transaction/TaxWithholdReportVoucher_IN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/TaxWithholdReportVoucher_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxWithholdReportVoucher_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FromDate name="FromDate">FromDate</a>

First included in: Transaction/TaxWithholdReportVoucher_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>From date</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>From date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#PaymentVersion name="PaymentVersion">PaymentVersion</a>

First included in: Transaction/TaxWithholdReportVoucher_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentVersion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxRepCounter name="TaxRepCounter">TaxRepCounter</a>

First included in: Transaction/TaxWithholdReportVoucher_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRepCounter attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxType name="TaxType">TaxType</a>

First included in: Transaction/TaxWithholdReportVoucher_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxWithholdRegNumber name="TaxWithholdRegNumber">TaxWithholdRegNumber</a>

First included in: Transaction/TaxWithholdReportVoucher_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdRegNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxWithholdSettlementPeriod name="TaxWithholdSettlementPeriod">TaxWithholdSettlementPeriod</a>

First included in: Transaction/TaxWithholdReportVoucher_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdSettlementPeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ToDate name="ToDate">ToDate</a>

First included in: Transaction/TaxWithholdReportVoucher_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>To date</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>To date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: Transaction/TaxWithholdReportVoucher_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: Transaction/TaxWithholdReportVoucher_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Voucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/TaxWithholdReportVoucher_IN (this entity)  

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

### <a href=#Relationship_GeneralJournalEntryRelationshipId name="Relationship_GeneralJournalEntryRelationshipId">Relationship_GeneralJournalEntryRelationshipId</a>

First included in: Transaction/TaxWithholdReportVoucher_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_GeneralJournalEntryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/TransactionHeader/GeneralJournalEntry.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/TransactionHeader/GeneralJournalEntry.cdm.json/GeneralJournalEntry</a></td><td><a href="../../Ledger/TransactionHeader/GeneralJournalEntry.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWithholdHeadRelationshipId name="Relationship_TaxWithholdHeadRelationshipId">Relationship_TaxWithholdHeadRelationshipId</a>

First included in: Transaction/TaxWithholdReportVoucher_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdHeadRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/TaxWithholdHead_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxWithholdHead_IN.cdm.json/TaxWithholdHead_IN</a></td><td><a href="../Group/TaxWithholdHead_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_taxWithholdRegNumberRelationshipId name="Relationship_taxWithholdRegNumberRelationshipId">Relationship_taxWithholdRegNumberRelationshipId</a>

First included in: Transaction/TaxWithholdReportVoucher_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_taxWithholdRegNumberRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/TaxWithholdRegNumbers_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Main/TaxWithholdRegNumbers_IN.cdm.json/TaxWithholdRegNumbers_IN</a></td><td><a href="../Main/TaxWithholdRegNumbers_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWithholdSettleTransRelationshipId name="Relationship_TaxWithholdSettleTransRelationshipId">Relationship_TaxWithholdSettleTransRelationshipId</a>

First included in: Transaction/TaxWithholdReportVoucher_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdSettleTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxWithholdSettleTrans_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Transaction/TaxWithholdSettleTrans_IN.cdm.json/TaxWithholdSettleTrans_IN</a></td><td><a href="TaxWithholdSettleTrans_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/TaxWithholdReportVoucher_IN (this entity)  

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
