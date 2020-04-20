---
title: TaxEngineTaxJournalLine - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# TaxEngineTaxJournalLine

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/WorksheetLine/TaxEngineTaxJournalLine.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxEngineTaxJournalLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[AmountCurCredit](#AmountCurCredit)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[AmountCurDebit](#AmountCurDebit)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[LedgerDimension](#LedgerDimension)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[OffsetLedgerDimension](#OffsetLedgerDimension)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[AccountType](#AccountType)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[OffsetAccountType](#OffsetAccountType)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[DefaultDimension](#DefaultDimension)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[OffsetDefaultDimension](#OffsetDefaultDimension)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[CurrencyCode](#CurrencyCode)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[TaxEngineTaxJournal](#TaxEngineTaxJournal)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[LedgerJournalTrans](#LedgerJournalTrans)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[TaxComponent](#TaxComponent)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[OffsetTaxComponent](#OffsetTaxComponent)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[TaxPostingType](#TaxPostingType)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[OffsetTaxPostingType](#OffsetTaxPostingType)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[TransDate](#TransDate)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[Purpose](#Purpose)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[TaxMeasure](#TaxMeasure)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[Description](#Description)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[ExchRate](#ExchRate)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[ExchrateSecond](#ExchrateSecond)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[Triangulation](#Triangulation)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[TaxTrans](#TaxTrans)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[Relationship_DefaultDimensionRelationshipId](#Relationship_DefaultDimensionRelationshipId)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[Relationship_LedgerDimensionRelationshipId](#Relationship_LedgerDimensionRelationshipId)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[Relationship_OffsetDefaultDimensionRelationshipId](#Relationship_OffsetDefaultDimensionRelationshipId)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[Relationship_OffsetLedgerDimensionRelationshipId](#Relationship_OffsetLedgerDimensionRelationshipId)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[Relationship_TaxEngineTaxJournalRelationshipId](#Relationship_TaxEngineTaxJournalRelationshipId)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[Relationship_LedgerJournalTransRelationshipId](#Relationship_LedgerJournalTransRelationshipId)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[Relationship_LedgerJournalTxtRelationshipId](#Relationship_LedgerJournalTxtRelationshipId)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxEngineTaxJournalLine.md" target="_blank">WorksheetLine/TaxEngineTaxJournalLine</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxEngineTaxJournalLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AmountCurCredit name="AmountCurCredit">AmountCurCredit</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountCurCredit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AmountCurDebit name="AmountCurDebit">AmountCurDebit</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountCurDebit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LedgerDimension name="LedgerDimension">LedgerDimension</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

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

### <a href=#OffsetLedgerDimension name="OffsetLedgerDimension">OffsetLedgerDimension</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountType name="AccountType">AccountType</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OffsetAccountType name="OffsetAccountType">OffsetAccountType</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetAccountType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OffsetDefaultDimension name="OffsetDefaultDimension">OffsetDefaultDimension</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetDefaultDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxEngineTaxJournal name="TaxEngineTaxJournal">TaxEngineTaxJournal</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxEngineTaxJournal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LedgerJournalTrans name="LedgerJournalTrans">LedgerJournalTrans</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

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

### <a href=#TaxComponent name="TaxComponent">TaxComponent</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxComponent attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OffsetTaxComponent name="OffsetTaxComponent">OffsetTaxComponent</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetTaxComponent attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxPostingType name="TaxPostingType">TaxPostingType</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPostingType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OffsetTaxPostingType name="OffsetTaxPostingType">OffsetTaxPostingType</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetTaxPostingType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Purpose name="Purpose">Purpose</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Purpose attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxMeasure name="TaxMeasure">TaxMeasure</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxMeasure attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchRate name="ExchRate">ExchRate</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ExchrateSecond name="ExchrateSecond">ExchrateSecond</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchrateSecond attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Triangulation name="Triangulation">Triangulation</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Triangulation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxTrans name="TaxTrans">TaxTrans</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

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

### <a href=#Relationship_DefaultDimensionRelationshipId name="Relationship_DefaultDimensionRelationshipId">Relationship_DefaultDimensionRelationshipId</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerDimensionRelationshipId name="Relationship_LedgerDimensionRelationshipId">Relationship_LedgerDimensionRelationshipId</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

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

### <a href=#Relationship_OffsetDefaultDimensionRelationshipId name="Relationship_OffsetDefaultDimensionRelationshipId">Relationship_OffsetDefaultDimensionRelationshipId</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OffsetDefaultDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OffsetLedgerDimensionRelationshipId name="Relationship_OffsetLedgerDimensionRelationshipId">Relationship_OffsetLedgerDimensionRelationshipId</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OffsetLedgerDimensionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TaxEngineTaxJournalRelationshipId name="Relationship_TaxEngineTaxJournalRelationshipId">Relationship_TaxEngineTaxJournalRelationshipId</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxEngineTaxJournalRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/TaxEngineTaxJournal.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/WorksheetHeader/TaxEngineTaxJournal.cdm.json/TaxEngineTaxJournal</a></td><td><a href="../WorksheetHeader/TaxEngineTaxJournal.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerJournalTransRelationshipId name="Relationship_LedgerJournalTransRelationshipId">Relationship_LedgerJournalTransRelationshipId</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

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

### <a href=#Relationship_LedgerJournalTxtRelationshipId name="Relationship_LedgerJournalTxtRelationshipId">Relationship_LedgerJournalTxtRelationshipId</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerJournalTxtRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountingFoundation/Main/LedgerJournalTxt.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/Main/LedgerJournalTxt.cdm.json/LedgerJournalTxt</a></td><td><a href="../../AccountingFoundation/Main/LedgerJournalTxt.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/TaxEngineTaxJournalLine (this entity)  

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
