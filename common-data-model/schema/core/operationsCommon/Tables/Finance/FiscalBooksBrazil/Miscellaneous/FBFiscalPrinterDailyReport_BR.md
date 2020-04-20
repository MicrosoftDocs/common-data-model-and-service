---
title: FBFiscalPrinterDailyReport_BR - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# FBFiscalPrinterDailyReport_BR

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/FBFiscalPrinterDailyReport_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBFiscalPrinterDailyReport_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FBFiscalPrinterDailyReport_BR.md" target="_blank">Miscellaneous/FBFiscalPrinterDailyReport_BR</a>|
|[AccountingDate](#AccountingDate)||<a href="FBFiscalPrinterDailyReport_BR.md" target="_blank">Miscellaneous/FBFiscalPrinterDailyReport_BR</a>|
|[CanceledAmount](#CanceledAmount)||<a href="FBFiscalPrinterDailyReport_BR.md" target="_blank">Miscellaneous/FBFiscalPrinterDailyReport_BR</a>|
|[DiscountAmount](#DiscountAmount)||<a href="FBFiscalPrinterDailyReport_BR.md" target="_blank">Miscellaneous/FBFiscalPrinterDailyReport_BR</a>|
|[ExemptBaseAmount](#ExemptBaseAmount)||<a href="FBFiscalPrinterDailyReport_BR.md" target="_blank">Miscellaneous/FBFiscalPrinterDailyReport_BR</a>|
|[FBBookingPeriod_BR](#FBBookingPeriod_BR)||<a href="FBFiscalPrinterDailyReport_BR.md" target="_blank">Miscellaneous/FBFiscalPrinterDailyReport_BR</a>|
|[GrossAmount](#GrossAmount)||<a href="FBFiscalPrinterDailyReport_BR.md" target="_blank">Miscellaneous/FBFiscalPrinterDailyReport_BR</a>|
|[ISSTaxAmount](#ISSTaxAmount)||<a href="FBFiscalPrinterDailyReport_BR.md" target="_blank">Miscellaneous/FBFiscalPrinterDailyReport_BR</a>|
|[NetAmount](#NetAmount)||<a href="FBFiscalPrinterDailyReport_BR.md" target="_blank">Miscellaneous/FBFiscalPrinterDailyReport_BR</a>|
|[Number](#Number)||<a href="FBFiscalPrinterDailyReport_BR.md" target="_blank">Miscellaneous/FBFiscalPrinterDailyReport_BR</a>|
|[STAmount](#STAmount)||<a href="FBFiscalPrinterDailyReport_BR.md" target="_blank">Miscellaneous/FBFiscalPrinterDailyReport_BR</a>|
|[TaxAmount](#TaxAmount)||<a href="FBFiscalPrinterDailyReport_BR.md" target="_blank">Miscellaneous/FBFiscalPrinterDailyReport_BR</a>|
|[TaxBaseAmount](#TaxBaseAmount)||<a href="FBFiscalPrinterDailyReport_BR.md" target="_blank">Miscellaneous/FBFiscalPrinterDailyReport_BR</a>|
|[Relationship_FBBookingPeriod_BRRelationshipId](#Relationship_FBBookingPeriod_BRRelationshipId)||<a href="FBFiscalPrinterDailyReport_BR.md" target="_blank">Miscellaneous/FBFiscalPrinterDailyReport_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/FBFiscalPrinterDailyReport_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBFiscalPrinterDailyReport_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountingDate name="AccountingDate">AccountingDate</a>

First included in: Miscellaneous/FBFiscalPrinterDailyReport_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#CanceledAmount name="CanceledAmount">CanceledAmount</a>

First included in: Miscellaneous/FBFiscalPrinterDailyReport_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanceledAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DiscountAmount name="DiscountAmount">DiscountAmount</a>

First included in: Miscellaneous/FBFiscalPrinterDailyReport_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ExemptBaseAmount name="ExemptBaseAmount">ExemptBaseAmount</a>

First included in: Miscellaneous/FBFiscalPrinterDailyReport_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExemptBaseAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FBBookingPeriod_BR name="FBBookingPeriod_BR">FBBookingPeriod_BR</a>

First included in: Miscellaneous/FBFiscalPrinterDailyReport_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBBookingPeriod_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#GrossAmount name="GrossAmount">GrossAmount</a>

First included in: Miscellaneous/FBFiscalPrinterDailyReport_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrossAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ISSTaxAmount name="ISSTaxAmount">ISSTaxAmount</a>

First included in: Miscellaneous/FBFiscalPrinterDailyReport_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ISSTaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#NetAmount name="NetAmount">NetAmount</a>

First included in: Miscellaneous/FBFiscalPrinterDailyReport_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Number name="Number">Number</a>

First included in: Miscellaneous/FBFiscalPrinterDailyReport_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Number attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#STAmount name="STAmount">STAmount</a>

First included in: Miscellaneous/FBFiscalPrinterDailyReport_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the STAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxAmount name="TaxAmount">TaxAmount</a>

First included in: Miscellaneous/FBFiscalPrinterDailyReport_BR (this entity)  

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

### <a href=#TaxBaseAmount name="TaxBaseAmount">TaxBaseAmount</a>

First included in: Miscellaneous/FBFiscalPrinterDailyReport_BR (this entity)  

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

### <a href=#Relationship_FBBookingPeriod_BRRelationshipId name="Relationship_FBBookingPeriod_BRRelationshipId">Relationship_FBBookingPeriod_BRRelationshipId</a>

First included in: Miscellaneous/FBFiscalPrinterDailyReport_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FBBookingPeriod_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/FBBookingPeriod_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FBBookingPeriod_BR.cdm.json/FBBookingPeriod_BR</a></td><td><a href="../Transaction/FBBookingPeriod_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
