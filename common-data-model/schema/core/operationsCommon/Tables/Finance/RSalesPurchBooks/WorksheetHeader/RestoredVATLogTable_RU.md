---
title: RestoredVATLogTable_RU - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# VAT restoring journal total amounts

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/RSalesPurchBooks/WorksheetHeader/RestoredVATLogTable_RU.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RestoredVATLogTable_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>VAT restoring journal total amounts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RestoredVATLogTable_RU.md" target="_blank">WorksheetHeader/RestoredVATLogTable_RU</a>|
|[Approved](#Approved)||<a href="RestoredVATLogTable_RU.md" target="_blank">WorksheetHeader/RestoredVATLogTable_RU</a>|
|[ApprovedBy](#ApprovedBy)||<a href="RestoredVATLogTable_RU.md" target="_blank">WorksheetHeader/RestoredVATLogTable_RU</a>|
|[DomesticGain](#DomesticGain)||<a href="RestoredVATLogTable_RU.md" target="_blank">WorksheetHeader/RestoredVATLogTable_RU</a>|
|[ExportGain](#ExportGain)||<a href="RestoredVATLogTable_RU.md" target="_blank">WorksheetHeader/RestoredVATLogTable_RU</a>|
|[NotLiableGain](#NotLiableGain)||<a href="RestoredVATLogTable_RU.md" target="_blank">WorksheetHeader/RestoredVATLogTable_RU</a>|
|[RecalcAll](#RecalcAll)||<a href="RestoredVATLogTable_RU.md" target="_blank">WorksheetHeader/RestoredVATLogTable_RU</a>|
|[RecalcIndirect](#RecalcIndirect)||<a href="RestoredVATLogTable_RU.md" target="_blank">WorksheetHeader/RestoredVATLogTable_RU</a>|
|[TaxReducedAsset](#TaxReducedAsset)||<a href="RestoredVATLogTable_RU.md" target="_blank">WorksheetHeader/RestoredVATLogTable_RU</a>|
|[TaxReducedDirect](#TaxReducedDirect)||<a href="RestoredVATLogTable_RU.md" target="_blank">WorksheetHeader/RestoredVATLogTable_RU</a>|
|[TaxReducedIndirect](#TaxReducedIndirect)||<a href="RestoredVATLogTable_RU.md" target="_blank">WorksheetHeader/RestoredVATLogTable_RU</a>|
|[TaxReducedIndirectInc](#TaxReducedIndirectInc)||<a href="RestoredVATLogTable_RU.md" target="_blank">WorksheetHeader/RestoredVATLogTable_RU</a>|
|[TaxStandardAsset](#TaxStandardAsset)||<a href="RestoredVATLogTable_RU.md" target="_blank">WorksheetHeader/RestoredVATLogTable_RU</a>|
|[TaxStandardDirect](#TaxStandardDirect)||<a href="RestoredVATLogTable_RU.md" target="_blank">WorksheetHeader/RestoredVATLogTable_RU</a>|
|[TaxStandardIndirect](#TaxStandardIndirect)||<a href="RestoredVATLogTable_RU.md" target="_blank">WorksheetHeader/RestoredVATLogTable_RU</a>|
|[TaxStandardIndirectInc](#TaxStandardIndirectInc)||<a href="RestoredVATLogTable_RU.md" target="_blank">WorksheetHeader/RestoredVATLogTable_RU</a>|
|[TotalGain](#TotalGain)||<a href="RestoredVATLogTable_RU.md" target="_blank">WorksheetHeader/RestoredVATLogTable_RU</a>|
|[TransDate](#TransDate)||<a href="RestoredVATLogTable_RU.md" target="_blank">WorksheetHeader/RestoredVATLogTable_RU</a>|
|[DataAreaId](#DataAreaId)||<a href="RestoredVATLogTable_RU.md" target="_blank">WorksheetHeader/RestoredVATLogTable_RU</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RestoredVATLogTable_RU.md" target="_blank">WorksheetHeader/RestoredVATLogTable_RU</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetHeader/RestoredVATLogTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RestoredVATLogTable_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Approved name="Approved">Approved</a>

First included in: WorksheetHeader/RestoredVATLogTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Approved attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ApprovedBy name="ApprovedBy">ApprovedBy</a>

First included in: WorksheetHeader/RestoredVATLogTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Approved by</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApprovedBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Approved by</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DomesticGain name="DomesticGain">DomesticGain</a>

First included in: WorksheetHeader/RestoredVATLogTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DomesticGain attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ExportGain name="ExportGain">ExportGain</a>

First included in: WorksheetHeader/RestoredVATLogTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExportGain attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#NotLiableGain name="NotLiableGain">NotLiableGain</a>

First included in: WorksheetHeader/RestoredVATLogTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NotLiableGain attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RecalcAll name="RecalcAll">RecalcAll</a>

First included in: WorksheetHeader/RestoredVATLogTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecalcAll attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RecalcIndirect name="RecalcIndirect">RecalcIndirect</a>

First included in: WorksheetHeader/RestoredVATLogTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecalcIndirect attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxReducedAsset name="TaxReducedAsset">TaxReducedAsset</a>

First included in: WorksheetHeader/RestoredVATLogTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReducedAsset attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxReducedDirect name="TaxReducedDirect">TaxReducedDirect</a>

First included in: WorksheetHeader/RestoredVATLogTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReducedDirect attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxReducedIndirect name="TaxReducedIndirect">TaxReducedIndirect</a>

First included in: WorksheetHeader/RestoredVATLogTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReducedIndirect attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxReducedIndirectInc name="TaxReducedIndirectInc">TaxReducedIndirectInc</a>

First included in: WorksheetHeader/RestoredVATLogTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReducedIndirectInc attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxStandardAsset name="TaxStandardAsset">TaxStandardAsset</a>

First included in: WorksheetHeader/RestoredVATLogTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxStandardAsset attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxStandardDirect name="TaxStandardDirect">TaxStandardDirect</a>

First included in: WorksheetHeader/RestoredVATLogTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxStandardDirect attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxStandardIndirect name="TaxStandardIndirect">TaxStandardIndirect</a>

First included in: WorksheetHeader/RestoredVATLogTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxStandardIndirect attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxStandardIndirectInc name="TaxStandardIndirectInc">TaxStandardIndirectInc</a>

First included in: WorksheetHeader/RestoredVATLogTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxStandardIndirectInc attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalGain name="TotalGain">TotalGain</a>

First included in: WorksheetHeader/RestoredVATLogTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalGain attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: WorksheetHeader/RestoredVATLogTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetHeader/RestoredVATLogTable_RU (this entity)  

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

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetHeader/RestoredVATLogTable_RU (this entity)  

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
