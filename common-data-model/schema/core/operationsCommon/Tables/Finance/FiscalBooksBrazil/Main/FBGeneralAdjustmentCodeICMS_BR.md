---
title: FBGeneralAdjustmentCodeICMS_BR - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# FBGeneralAdjustmentCodeICMS_BR

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBGeneralAdjustmentCodeICMS_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBGeneralAdjustmentCodeICMS_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodeICMS_BR</a>|
|[AdjustmentCode](#AdjustmentCode)||<a href="FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodeICMS_BR</a>|
|[CreatePayment](#CreatePayment)||<a href="FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodeICMS_BR</a>|
|[Description](#Description)||<a href="FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodeICMS_BR</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodeICMS_BR</a>|
|[RevenueCode](#RevenueCode)||<a href="FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodeICMS_BR</a>|
|[TaxType](#TaxType)||<a href="FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodeICMS_BR</a>|
|[ValidFrom](#ValidFrom)||<a href="FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodeICMS_BR</a>|
|[ValidTo](#ValidTo)||<a href="FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodeICMS_BR</a>|
|[IsPovertyFund](#IsPovertyFund)||<a href="FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodeICMS_BR</a>|
|[TaxPovertyFundPayment](#TaxPovertyFundPayment)||<a href="FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodeICMS_BR</a>|
|[Classification](#Classification)||<a href="FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodeICMS_BR</a>|
|[GIAAdjustmentCode](#GIAAdjustmentCode)||<a href="FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodeICMS_BR</a>|
|[OccurrenceCode](#OccurrenceCode)||<a href="FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodeICMS_BR</a>|
|[SpedAdjustmentCode](#SpedAdjustmentCode)||<a href="FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodeICMS_BR</a>|
|[State](#State)||<a href="FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodeICMS_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/FBGeneralAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBGeneralAdjustmentCodeICMS_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AdjustmentCode name="AdjustmentCode">AdjustmentCode</a>

First included in: Main/FBGeneralAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdjustmentCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreatePayment name="CreatePayment">CreatePayment</a>

First included in: Main/FBGeneralAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreatePayment attribute are listed below.</summary>

</details>

### <a href=#Description name="Description">Description</a>

First included in: Main/FBGeneralAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Main/FBGeneralAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.readOnly**  
</details>

### <a href=#RevenueCode name="RevenueCode">RevenueCode</a>

First included in: Main/FBGeneralAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevenueCode attribute are listed below.</summary>

</details>

### <a href=#TaxType name="TaxType">TaxType</a>

First included in: Main/FBGeneralAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: Main/FBGeneralAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: Main/FBGeneralAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

</details>

### <a href=#IsPovertyFund name="IsPovertyFund">IsPovertyFund</a>

First included in: Main/FBGeneralAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPovertyFund attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxPovertyFundPayment name="TaxPovertyFundPayment">TaxPovertyFundPayment</a>

First included in: Main/FBGeneralAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPovertyFundPayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Classification name="Classification">Classification</a>

First included in: Main/FBGeneralAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Classification attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#GIAAdjustmentCode name="GIAAdjustmentCode">GIAAdjustmentCode</a>

First included in: Main/FBGeneralAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GIAAdjustmentCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OccurrenceCode name="OccurrenceCode">OccurrenceCode</a>

First included in: Main/FBGeneralAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OccurrenceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpedAdjustmentCode name="SpedAdjustmentCode">SpedAdjustmentCode</a>

First included in: Main/FBGeneralAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpedAdjustmentCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#State name="State">State</a>

First included in: Main/FBGeneralAdjustmentCodeICMS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the State attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
