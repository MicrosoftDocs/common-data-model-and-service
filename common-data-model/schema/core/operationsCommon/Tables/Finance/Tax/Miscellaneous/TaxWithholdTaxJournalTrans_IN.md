---
title: TaxWithholdTaxJournalTrans_IN - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Tax adjustment journal trans

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/Miscellaneous/TaxWithholdTaxJournalTrans_IN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxWithholdTaxJournalTrans_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax adjustment journal trans</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxWithholdTaxJournalTrans_IN.md" target="_blank">Miscellaneous/TaxWithholdTaxJournalTrans_IN</a>|
|[AccountNum](#AccountNum)||<a href="TaxWithholdTaxJournalTrans_IN.md" target="_blank">Miscellaneous/TaxWithholdTaxJournalTrans_IN</a>|
|[AccountType](#AccountType)||<a href="TaxWithholdTaxJournalTrans_IN.md" target="_blank">Miscellaneous/TaxWithholdTaxJournalTrans_IN</a>|
|[LedgerJournalTrans](#LedgerJournalTrans)||<a href="TaxWithholdTaxJournalTrans_IN.md" target="_blank">Miscellaneous/TaxWithholdTaxJournalTrans_IN</a>|
|[RateOfDeduction](#RateOfDeduction)||<a href="TaxWithholdTaxJournalTrans_IN.md" target="_blank">Miscellaneous/TaxWithholdTaxJournalTrans_IN</a>|
|[SourceAmountOriginCur](#SourceAmountOriginCur)||<a href="TaxWithholdTaxJournalTrans_IN.md" target="_blank">Miscellaneous/TaxWithholdTaxJournalTrans_IN</a>|
|[SourceTaxAmountCur](#SourceTaxAmountCur)||<a href="TaxWithholdTaxJournalTrans_IN.md" target="_blank">Miscellaneous/TaxWithholdTaxJournalTrans_IN</a>|
|[SourceTaxBaseAmountCur](#SourceTaxBaseAmountCur)||<a href="TaxWithholdTaxJournalTrans_IN.md" target="_blank">Miscellaneous/TaxWithholdTaxJournalTrans_IN</a>|
|[SourceTransDate](#SourceTransDate)||<a href="TaxWithholdTaxJournalTrans_IN.md" target="_blank">Miscellaneous/TaxWithholdTaxJournalTrans_IN</a>|
|[SourceTransRecId](#SourceTransRecId)||<a href="TaxWithholdTaxJournalTrans_IN.md" target="_blank">Miscellaneous/TaxWithholdTaxJournalTrans_IN</a>|
|[SourceTransTableId](#SourceTransTableId)||<a href="TaxWithholdTaxJournalTrans_IN.md" target="_blank">Miscellaneous/TaxWithholdTaxJournalTrans_IN</a>|
|[SourceTransVoucher](#SourceTransVoucher)||<a href="TaxWithholdTaxJournalTrans_IN.md" target="_blank">Miscellaneous/TaxWithholdTaxJournalTrans_IN</a>|
|[TaxWithholdAccountType](#TaxWithholdAccountType)||<a href="TaxWithholdTaxJournalTrans_IN.md" target="_blank">Miscellaneous/TaxWithholdTaxJournalTrans_IN</a>|
|[TaxWithholdGroup](#TaxWithholdGroup)||<a href="TaxWithholdTaxJournalTrans_IN.md" target="_blank">Miscellaneous/TaxWithholdTaxJournalTrans_IN</a>|
|[TaxWithholdType](#TaxWithholdType)||<a href="TaxWithholdTaxJournalTrans_IN.md" target="_blank">Miscellaneous/TaxWithholdTaxJournalTrans_IN</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxWithholdTaxJournalTrans_IN.md" target="_blank">Miscellaneous/TaxWithholdTaxJournalTrans_IN</a>|
|[Relationship_CustTransRelationshipId](#Relationship_CustTransRelationshipId)||<a href="TaxWithholdTaxJournalTrans_IN.md" target="_blank">Miscellaneous/TaxWithholdTaxJournalTrans_IN</a>|
|[Relationship_LedgerJournalTransRelationshipId](#Relationship_LedgerJournalTransRelationshipId)||<a href="TaxWithholdTaxJournalTrans_IN.md" target="_blank">Miscellaneous/TaxWithholdTaxJournalTrans_IN</a>|
|[Relationship_TaxWithholdGroupHeadingRelationshipId](#Relationship_TaxWithholdGroupHeadingRelationshipId)||<a href="TaxWithholdTaxJournalTrans_IN.md" target="_blank">Miscellaneous/TaxWithholdTaxJournalTrans_IN</a>|
|[Relationship_VendTransRelationshipId](#Relationship_VendTransRelationshipId)||<a href="TaxWithholdTaxJournalTrans_IN.md" target="_blank">Miscellaneous/TaxWithholdTaxJournalTrans_IN</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxWithholdTaxJournalTrans_IN.md" target="_blank">Miscellaneous/TaxWithholdTaxJournalTrans_IN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/TaxWithholdTaxJournalTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxWithholdTaxJournalTrans_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountNum name="AccountNum">AccountNum</a>

First included in: Miscellaneous/TaxWithholdTaxJournalTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountType name="AccountType">AccountType</a>

First included in: Miscellaneous/TaxWithholdTaxJournalTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LedgerJournalTrans name="LedgerJournalTrans">LedgerJournalTrans</a>

First included in: Miscellaneous/TaxWithholdTaxJournalTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerJournalTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RateOfDeduction name="RateOfDeduction">RateOfDeduction</a>

First included in: Miscellaneous/TaxWithholdTaxJournalTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RateOfDeduction attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SourceAmountOriginCur name="SourceAmountOriginCur">SourceAmountOriginCur</a>

First included in: Miscellaneous/TaxWithholdTaxJournalTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceAmountOriginCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SourceTaxAmountCur name="SourceTaxAmountCur">SourceTaxAmountCur</a>

First included in: Miscellaneous/TaxWithholdTaxJournalTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceTaxAmountCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SourceTaxBaseAmountCur name="SourceTaxBaseAmountCur">SourceTaxBaseAmountCur</a>

First included in: Miscellaneous/TaxWithholdTaxJournalTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceTaxBaseAmountCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SourceTransDate name="SourceTransDate">SourceTransDate</a>

First included in: Miscellaneous/TaxWithholdTaxJournalTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceTransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#SourceTransRecId name="SourceTransRecId">SourceTransRecId</a>

First included in: Miscellaneous/TaxWithholdTaxJournalTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceTransRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SourceTransTableId name="SourceTransTableId">SourceTransTableId</a>

First included in: Miscellaneous/TaxWithholdTaxJournalTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceTransTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SourceTransVoucher name="SourceTransVoucher">SourceTransVoucher</a>

First included in: Miscellaneous/TaxWithholdTaxJournalTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceTransVoucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdAccountType name="TaxWithholdAccountType">TaxWithholdAccountType</a>

First included in: Miscellaneous/TaxWithholdTaxJournalTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdAccountType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxWithholdGroup name="TaxWithholdGroup">TaxWithholdGroup</a>

First included in: Miscellaneous/TaxWithholdTaxJournalTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdType name="TaxWithholdType">TaxWithholdType</a>

First included in: Miscellaneous/TaxWithholdTaxJournalTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/TaxWithholdTaxJournalTrans_IN (this entity)  

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

### <a href=#Relationship_CustTransRelationshipId name="Relationship_CustTransRelationshipId">Relationship_CustTransRelationshipId</a>

First included in: Miscellaneous/TaxWithholdTaxJournalTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Transaction/CustTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Transaction/CustTrans.cdm.json/CustTrans</a></td><td><a href="../../AccountsReceivable/Transaction/CustTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerJournalTransRelationshipId name="Relationship_LedgerJournalTransRelationshipId">Relationship_LedgerJournalTransRelationshipId</a>

First included in: Miscellaneous/TaxWithholdTaxJournalTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerJournalTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountingFoundation/WorksheetLine/LedgerJournalTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/WorksheetLine/LedgerJournalTrans.cdm.json/LedgerJournalTrans</a></td><td><a href="../../AccountingFoundation/WorksheetLine/LedgerJournalTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWithholdGroupHeadingRelationshipId name="Relationship_TaxWithholdGroupHeadingRelationshipId">Relationship_TaxWithholdGroupHeadingRelationshipId</a>

First included in: Miscellaneous/TaxWithholdTaxJournalTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdGroupHeadingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/TaxWithholdGroupHeading.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxWithholdGroupHeading.cdm.json/TaxWithholdGroupHeading</a></td><td><a href="../Group/TaxWithholdGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTransRelationshipId name="Relationship_VendTransRelationshipId">Relationship_VendTransRelationshipId</a>

First included in: Miscellaneous/TaxWithholdTaxJournalTrans_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsPayable/Transaction/VendTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Transaction/VendTrans.cdm.json/VendTrans</a></td><td><a href="../../AccountsPayable/Transaction/VendTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/TaxWithholdTaxJournalTrans_IN (this entity)  

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
