---
title: TaxDocumentMeasureSourceDocumentLine - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/30/2020
ms.author: nebanfic
---

# Tax document measure source document line

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/WorksheetLine/TaxDocumentMeasureSourceDocumentLine.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxDocumentMeasureSourceDocumentLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax document measure source document line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxDocumentMeasureSourceDocumentLine.md" target="_blank">WorksheetLine/TaxDocumentMeasureSourceDocumentLine</a>|
|[AmountAccountingCurrency](#AmountAccountingCurrency)||<a href="TaxDocumentMeasureSourceDocumentLine.md" target="_blank">WorksheetLine/TaxDocumentMeasureSourceDocumentLine</a>|
|[AmountTransactionCurrency](#AmountTransactionCurrency)||<a href="TaxDocumentMeasureSourceDocumentLine.md" target="_blank">WorksheetLine/TaxDocumentMeasureSourceDocumentLine</a>|
|[DistributionLedgerDimension](#DistributionLedgerDimension)||<a href="TaxDocumentMeasureSourceDocumentLine.md" target="_blank">WorksheetLine/TaxDocumentMeasureSourceDocumentLine</a>|
|[DistributionLedgerPostingType](#DistributionLedgerPostingType)||<a href="TaxDocumentMeasureSourceDocumentLine.md" target="_blank">WorksheetLine/TaxDocumentMeasureSourceDocumentLine</a>|
|[DistributionSide](#DistributionSide)||<a href="TaxDocumentMeasureSourceDocumentLine.md" target="_blank">WorksheetLine/TaxDocumentMeasureSourceDocumentLine</a>|
|[DistributionTaxAccountingProvider](#DistributionTaxAccountingProvider)||<a href="TaxDocumentMeasureSourceDocumentLine.md" target="_blank">WorksheetLine/TaxDocumentMeasureSourceDocumentLine</a>|
|[JournalizationTaxAccountingProvider](#JournalizationTaxAccountingProvider)||<a href="TaxDocumentMeasureSourceDocumentLine.md" target="_blank">WorksheetLine/TaxDocumentMeasureSourceDocumentLine</a>|
|[JournalizationLedgerDimension](#JournalizationLedgerDimension)||<a href="TaxDocumentMeasureSourceDocumentLine.md" target="_blank">WorksheetLine/TaxDocumentMeasureSourceDocumentLine</a>|
|[JournalizationLedgerPostingType](#JournalizationLedgerPostingType)||<a href="TaxDocumentMeasureSourceDocumentLine.md" target="_blank">WorksheetLine/TaxDocumentMeasureSourceDocumentLine</a>|
|[Label](#Label)||<a href="TaxDocumentMeasureSourceDocumentLine.md" target="_blank">WorksheetLine/TaxDocumentMeasureSourceDocumentLine</a>|
|[RootRecId](#RootRecId)||<a href="TaxDocumentMeasureSourceDocumentLine.md" target="_blank">WorksheetLine/TaxDocumentMeasureSourceDocumentLine</a>|
|[RootTableName](#RootTableName)||<a href="TaxDocumentMeasureSourceDocumentLine.md" target="_blank">WorksheetLine/TaxDocumentMeasureSourceDocumentLine</a>|
|[SourceDocumentLine](#SourceDocumentLine)||<a href="TaxDocumentMeasureSourceDocumentLine.md" target="_blank">WorksheetLine/TaxDocumentMeasureSourceDocumentLine</a>|
|[SourceRecId](#SourceRecId)||<a href="TaxDocumentMeasureSourceDocumentLine.md" target="_blank">WorksheetLine/TaxDocumentMeasureSourceDocumentLine</a>|
|[SourceTableName](#SourceTableName)||<a href="TaxDocumentMeasureSourceDocumentLine.md" target="_blank">WorksheetLine/TaxDocumentMeasureSourceDocumentLine</a>|
|[TaxDocCompLineSourceDocLine](#TaxDocCompLineSourceDocLine)||<a href="TaxDocumentMeasureSourceDocumentLine.md" target="_blank">WorksheetLine/TaxDocumentMeasureSourceDocumentLine</a>|
|[TaxMeasure](#TaxMeasure)||<a href="TaxDocumentMeasureSourceDocumentLine.md" target="_blank">WorksheetLine/TaxDocumentMeasureSourceDocumentLine</a>|
|[NonRecoverableAmountAccountingCurrency](#NonRecoverableAmountAccountingCurrency)||<a href="TaxDocumentMeasureSourceDocumentLine.md" target="_blank">WorksheetLine/TaxDocumentMeasureSourceDocumentLine</a>|
|[NonRecoverableAmountTransactionCurrency](#NonRecoverableAmountTransactionCurrency)||<a href="TaxDocumentMeasureSourceDocumentLine.md" target="_blank">WorksheetLine/TaxDocumentMeasureSourceDocumentLine</a>|
|[NonRecoverableTaxMeasureLabel](#NonRecoverableTaxMeasureLabel)||<a href="TaxDocumentMeasureSourceDocumentLine.md" target="_blank">WorksheetLine/TaxDocumentMeasureSourceDocumentLine</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxDocumentMeasureSourceDocumentLine.md" target="_blank">WorksheetLine/TaxDocumentMeasureSourceDocumentLine</a>|
|[Relationship_TaxDocCompLineSourceDocLineRelationshipId](#Relationship_TaxDocCompLineSourceDocLineRelationshipId)||<a href="TaxDocumentMeasureSourceDocumentLine.md" target="_blank">WorksheetLine/TaxDocumentMeasureSourceDocumentLine</a>|
|[Relationship_JournalizationLedgerDimensionRelationshipId](#Relationship_JournalizationLedgerDimensionRelationshipId)||<a href="TaxDocumentMeasureSourceDocumentLine.md" target="_blank">WorksheetLine/TaxDocumentMeasureSourceDocumentLine</a>|
|[Relationship_SourceDocumentLineRelationshipId](#Relationship_SourceDocumentLineRelationshipId)||<a href="TaxDocumentMeasureSourceDocumentLine.md" target="_blank">WorksheetLine/TaxDocumentMeasureSourceDocumentLine</a>|
|[Relationship_DistributionLedgerDimensionRelationshipId](#Relationship_DistributionLedgerDimensionRelationshipId)||<a href="TaxDocumentMeasureSourceDocumentLine.md" target="_blank">WorksheetLine/TaxDocumentMeasureSourceDocumentLine</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxDocumentMeasureSourceDocumentLine.md" target="_blank">WorksheetLine/TaxDocumentMeasureSourceDocumentLine</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/TaxDocumentMeasureSourceDocumentLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxDocumentMeasureSourceDocumentLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AmountAccountingCurrency name="AmountAccountingCurrency">AmountAccountingCurrency</a>

First included in: WorksheetLine/TaxDocumentMeasureSourceDocumentLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountAccountingCurrency attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AmountTransactionCurrency name="AmountTransactionCurrency">AmountTransactionCurrency</a>

First included in: WorksheetLine/TaxDocumentMeasureSourceDocumentLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountTransactionCurrency attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DistributionLedgerDimension name="DistributionLedgerDimension">DistributionLedgerDimension</a>

First included in: WorksheetLine/TaxDocumentMeasureSourceDocumentLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DistributionLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DistributionLedgerPostingType name="DistributionLedgerPostingType">DistributionLedgerPostingType</a>

First included in: WorksheetLine/TaxDocumentMeasureSourceDocumentLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DistributionLedgerPostingType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DistributionSide name="DistributionSide">DistributionSide</a>

First included in: WorksheetLine/TaxDocumentMeasureSourceDocumentLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Distribution side</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DistributionSide attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Distribution side</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DistributionTaxAccountingProvider name="DistributionTaxAccountingProvider">DistributionTaxAccountingProvider</a>

First included in: WorksheetLine/TaxDocumentMeasureSourceDocumentLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DistributionTaxAccountingProvider attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#JournalizationTaxAccountingProvider name="JournalizationTaxAccountingProvider">JournalizationTaxAccountingProvider</a>

First included in: WorksheetLine/TaxDocumentMeasureSourceDocumentLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalizationTaxAccountingProvider attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#JournalizationLedgerDimension name="JournalizationLedgerDimension">JournalizationLedgerDimension</a>

First included in: WorksheetLine/TaxDocumentMeasureSourceDocumentLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalizationLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#JournalizationLedgerPostingType name="JournalizationLedgerPostingType">JournalizationLedgerPostingType</a>

First included in: WorksheetLine/TaxDocumentMeasureSourceDocumentLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalizationLedgerPostingType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Label name="Label">Label</a>

First included in: WorksheetLine/TaxDocumentMeasureSourceDocumentLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Label attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RootRecId name="RootRecId">RootRecId</a>

First included in: WorksheetLine/TaxDocumentMeasureSourceDocumentLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RootRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RootTableName name="RootTableName">RootTableName</a>

First included in: WorksheetLine/TaxDocumentMeasureSourceDocumentLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RootTableName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceDocumentLine name="SourceDocumentLine">SourceDocumentLine</a>

First included in: WorksheetLine/TaxDocumentMeasureSourceDocumentLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceDocumentLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SourceRecId name="SourceRecId">SourceRecId</a>

First included in: WorksheetLine/TaxDocumentMeasureSourceDocumentLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SourceTableName name="SourceTableName">SourceTableName</a>

First included in: WorksheetLine/TaxDocumentMeasureSourceDocumentLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceTableName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxDocCompLineSourceDocLine name="TaxDocCompLineSourceDocLine">TaxDocCompLineSourceDocLine</a>

First included in: WorksheetLine/TaxDocumentMeasureSourceDocumentLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxDocCompLineSourceDocLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxMeasure name="TaxMeasure">TaxMeasure</a>

First included in: WorksheetLine/TaxDocumentMeasureSourceDocumentLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxMeasure attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NonRecoverableAmountAccountingCurrency name="NonRecoverableAmountAccountingCurrency">NonRecoverableAmountAccountingCurrency</a>

First included in: WorksheetLine/TaxDocumentMeasureSourceDocumentLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NonRecoverableAmountAccountingCurrency attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#NonRecoverableAmountTransactionCurrency name="NonRecoverableAmountTransactionCurrency">NonRecoverableAmountTransactionCurrency</a>

First included in: WorksheetLine/TaxDocumentMeasureSourceDocumentLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NonRecoverableAmountTransactionCurrency attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#NonRecoverableTaxMeasureLabel name="NonRecoverableTaxMeasureLabel">NonRecoverableTaxMeasureLabel</a>

First included in: WorksheetLine/TaxDocumentMeasureSourceDocumentLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NonRecoverableTaxMeasureLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/TaxDocumentMeasureSourceDocumentLine (this entity)  

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

### <a href=#Relationship_TaxDocCompLineSourceDocLineRelationshipId name="Relationship_TaxDocCompLineSourceDocLineRelationshipId">Relationship_TaxDocCompLineSourceDocLineRelationshipId</a>

First included in: WorksheetLine/TaxDocumentMeasureSourceDocumentLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxDocCompLineSourceDocLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxDocCompLineSourceDocLine.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/WorksheetLine/TaxDocCompLineSourceDocLine.cdm.json/TaxDocCompLineSourceDocLine</a></td><td><a href="TaxDocCompLineSourceDocLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_JournalizationLedgerDimensionRelationshipId name="Relationship_JournalizationLedgerDimensionRelationshipId">Relationship_JournalizationLedgerDimensionRelationshipId</a>

First included in: WorksheetLine/TaxDocumentMeasureSourceDocumentLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_JournalizationLedgerDimensionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SourceDocumentLineRelationshipId name="Relationship_SourceDocumentLineRelationshipId">Relationship_SourceDocumentLineRelationshipId</a>

First included in: WorksheetLine/TaxDocumentMeasureSourceDocumentLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SourceDocumentLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountingFoundation/TransactionLine/SourceDocumentLine.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/TransactionLine/SourceDocumentLine.cdm.json/SourceDocumentLine</a></td><td><a href="../../AccountingFoundation/TransactionLine/SourceDocumentLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DistributionLedgerDimensionRelationshipId name="Relationship_DistributionLedgerDimensionRelationshipId">Relationship_DistributionLedgerDimensionRelationshipId</a>

First included in: WorksheetLine/TaxDocumentMeasureSourceDocumentLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DistributionLedgerDimensionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/TaxDocumentMeasureSourceDocumentLine (this entity)  

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
