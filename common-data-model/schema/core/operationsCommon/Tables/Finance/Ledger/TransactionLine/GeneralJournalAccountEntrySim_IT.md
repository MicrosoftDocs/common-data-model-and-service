---
title: GeneralJournalAccountEntrySim_IT - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# General journal account entry

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Ledger/TransactionLine/GeneralJournalAccountEntrySim_IT.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[GeneralJournalAccountEntrySim_IT/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>General journal account entry</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="GeneralJournalAccountEntrySim_IT.md" target="_blank">TransactionLine/GeneralJournalAccountEntrySim_IT</a>|
|[AccountingCurrencyAmount](#AccountingCurrencyAmount)||<a href="GeneralJournalAccountEntrySim_IT.md" target="_blank">TransactionLine/GeneralJournalAccountEntrySim_IT</a>|
|[AllocationLevel](#AllocationLevel)||<a href="GeneralJournalAccountEntrySim_IT.md" target="_blank">TransactionLine/GeneralJournalAccountEntrySim_IT</a>|
|[GeneralJournalEntry](#GeneralJournalEntry)||<a href="GeneralJournalAccountEntrySim_IT.md" target="_blank">TransactionLine/GeneralJournalAccountEntrySim_IT</a>|
|[IsCorrection](#IsCorrection)||<a href="GeneralJournalAccountEntrySim_IT.md" target="_blank">TransactionLine/GeneralJournalAccountEntrySim_IT</a>|
|[IsCredit](#IsCredit)||<a href="GeneralJournalAccountEntrySim_IT.md" target="_blank">TransactionLine/GeneralJournalAccountEntrySim_IT</a>|
|[LedgerDimension](#LedgerDimension)||<a href="GeneralJournalAccountEntrySim_IT.md" target="_blank">TransactionLine/GeneralJournalAccountEntrySim_IT</a>|
|[PostingType](#PostingType)||<a href="GeneralJournalAccountEntrySim_IT.md" target="_blank">TransactionLine/GeneralJournalAccountEntrySim_IT</a>|
|[Quantity](#Quantity)||<a href="GeneralJournalAccountEntrySim_IT.md" target="_blank">TransactionLine/GeneralJournalAccountEntrySim_IT</a>|
|[ReportingCurrencyAmount](#ReportingCurrencyAmount)||<a href="GeneralJournalAccountEntrySim_IT.md" target="_blank">TransactionLine/GeneralJournalAccountEntrySim_IT</a>|
|[SkipCreditCalculation](#SkipCreditCalculation)||<a href="GeneralJournalAccountEntrySim_IT.md" target="_blank">TransactionLine/GeneralJournalAccountEntrySim_IT</a>|
|[Text](#Text)||<a href="GeneralJournalAccountEntrySim_IT.md" target="_blank">TransactionLine/GeneralJournalAccountEntrySim_IT</a>|
|[TransactionCurrencyAmount](#TransactionCurrencyAmount)||<a href="GeneralJournalAccountEntrySim_IT.md" target="_blank">TransactionLine/GeneralJournalAccountEntrySim_IT</a>|
|[TransactionCurrencyCode](#TransactionCurrencyCode)||<a href="GeneralJournalAccountEntrySim_IT.md" target="_blank">TransactionLine/GeneralJournalAccountEntrySim_IT</a>|
|[LedgerAccount](#LedgerAccount)||<a href="GeneralJournalAccountEntrySim_IT.md" target="_blank">TransactionLine/GeneralJournalAccountEntrySim_IT</a>|
|[MainAccount](#MainAccount)||<a href="GeneralJournalAccountEntrySim_IT.md" target="_blank">TransactionLine/GeneralJournalAccountEntrySim_IT</a>|
|[Relationship_GeneralJournalEntrySim_ITRelationshipId](#Relationship_GeneralJournalEntrySim_ITRelationshipId)||<a href="GeneralJournalAccountEntrySim_IT.md" target="_blank">TransactionLine/GeneralJournalAccountEntrySim_IT</a>|
|[Relationship_LedgerDimensionRelationshipId](#Relationship_LedgerDimensionRelationshipId)||<a href="GeneralJournalAccountEntrySim_IT.md" target="_blank">TransactionLine/GeneralJournalAccountEntrySim_IT</a>|
|[Relationship_TransactionCurrencyCodeRelationshipId](#Relationship_TransactionCurrencyCodeRelationshipId)||<a href="GeneralJournalAccountEntrySim_IT.md" target="_blank">TransactionLine/GeneralJournalAccountEntrySim_IT</a>|
|[Relationship_TransactionLogRelationshipId](#Relationship_TransactionLogRelationshipId)||<a href="GeneralJournalAccountEntrySim_IT.md" target="_blank">TransactionLine/GeneralJournalAccountEntrySim_IT</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: TransactionLine/GeneralJournalAccountEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[GeneralJournalAccountEntrySim_IT/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountingCurrencyAmount name="AccountingCurrencyAmount">AccountingCurrencyAmount</a>

First included in: TransactionLine/GeneralJournalAccountEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingCurrencyAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AllocationLevel name="AllocationLevel">AllocationLevel</a>

First included in: TransactionLine/GeneralJournalAccountEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllocationLevel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#GeneralJournalEntry name="GeneralJournalEntry">GeneralJournalEntry</a>

First included in: TransactionLine/GeneralJournalAccountEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralJournalEntry attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IsCorrection name="IsCorrection">IsCorrection</a>

First included in: TransactionLine/GeneralJournalAccountEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Correction</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCorrection attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Correction</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsCredit name="IsCredit">IsCredit</a>

First included in: TransactionLine/GeneralJournalAccountEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Crediting</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCredit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Crediting</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#LedgerDimension name="LedgerDimension">LedgerDimension</a>

First included in: TransactionLine/GeneralJournalAccountEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PostingType name="PostingType">PostingType</a>

First included in: TransactionLine/GeneralJournalAccountEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: TransactionLine/GeneralJournalAccountEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReportingCurrencyAmount name="ReportingCurrencyAmount">ReportingCurrencyAmount</a>

First included in: TransactionLine/GeneralJournalAccountEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCurrencyAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SkipCreditCalculation name="SkipCreditCalculation">SkipCreditCalculation</a>

First included in: TransactionLine/GeneralJournalAccountEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Skip</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SkipCreditCalculation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Skip</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Text name="Text">Text</a>

First included in: TransactionLine/GeneralJournalAccountEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Text attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCurrencyAmount name="TransactionCurrencyAmount">TransactionCurrencyAmount</a>

First included in: TransactionLine/GeneralJournalAccountEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransactionCurrencyCode name="TransactionCurrencyCode">TransactionCurrencyCode</a>

First included in: TransactionLine/GeneralJournalAccountEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerAccount name="LedgerAccount">LedgerAccount</a>

First included in: TransactionLine/GeneralJournalAccountEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccount name="MainAccount">MainAccount</a>

First included in: TransactionLine/GeneralJournalAccountEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_GeneralJournalEntrySim_ITRelationshipId name="Relationship_GeneralJournalEntrySim_ITRelationshipId">Relationship_GeneralJournalEntrySim_ITRelationshipId</a>

First included in: TransactionLine/GeneralJournalAccountEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_GeneralJournalEntrySim_ITRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../TransactionHeader/GeneralJournalEntrySim_IT.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/TransactionHeader/GeneralJournalEntrySim_IT.cdm.json/GeneralJournalEntrySim_IT</a></td><td><a href="../TransactionHeader/GeneralJournalEntrySim_IT.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerDimensionRelationshipId name="Relationship_LedgerDimensionRelationshipId">Relationship_LedgerDimensionRelationshipId</a>

First included in: TransactionLine/GeneralJournalAccountEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TransactionCurrencyCodeRelationshipId name="Relationship_TransactionCurrencyCodeRelationshipId">Relationship_TransactionCurrencyCodeRelationshipId</a>

First included in: TransactionLine/GeneralJournalAccountEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TransactionCurrencyCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TransactionLogRelationshipId name="Relationship_TransactionLogRelationshipId">Relationship_TransactionLogRelationshipId</a>

First included in: TransactionLine/GeneralJournalAccountEntrySim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TransactionLogRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/TransactionLog.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Transaction/TransactionLog.cdm.json/TransactionLog</a></td><td><a href="../Transaction/TransactionLog.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
