---
title: FBGeneralAdjustmentCodePISCOFINS_BR in Main - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Tax adjustment codes in Main(FBGeneralAdjustmentCodePISCOFINS_BR)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBGeneralAdjustmentCodePISCOFINS_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBGeneralAdjustmentCodePISCOFINS_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>General adjustment codes table</td></tr><tr><td>en</td><td>Tax adjustment codes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FBGeneralAdjustmentCodePISCOFINS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodePISCOFINS_BR</a>|
|[AdjustmentCode](#AdjustmentCode)||<a href="FBGeneralAdjustmentCodePISCOFINS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodePISCOFINS_BR</a>|
|[CreatePayment](#CreatePayment)||<a href="FBGeneralAdjustmentCodePISCOFINS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodePISCOFINS_BR</a>|
|[Description](#Description)||<a href="FBGeneralAdjustmentCodePISCOFINS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodePISCOFINS_BR</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="FBGeneralAdjustmentCodePISCOFINS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodePISCOFINS_BR</a>|
|[RevenueCode](#RevenueCode)||<a href="FBGeneralAdjustmentCodePISCOFINS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodePISCOFINS_BR</a>|
|[TaxType](#TaxType)||<a href="FBGeneralAdjustmentCodePISCOFINS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodePISCOFINS_BR</a>|
|[ValidFrom](#ValidFrom)||<a href="FBGeneralAdjustmentCodePISCOFINS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodePISCOFINS_BR</a>|
|[ValidTo](#ValidTo)||<a href="FBGeneralAdjustmentCodePISCOFINS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodePISCOFINS_BR</a>|
|[IsPovertyFund](#IsPovertyFund)||<a href="FBGeneralAdjustmentCodePISCOFINS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodePISCOFINS_BR</a>|
|[AdjustmentType](#AdjustmentType)||<a href="FBGeneralAdjustmentCodePISCOFINS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodePISCOFINS_BR</a>|
|[SpedAdjustmentCodePISCOFINS](#SpedAdjustmentCodePISCOFINS)||<a href="FBGeneralAdjustmentCodePISCOFINS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodePISCOFINS_BR</a>|
|[TransferEvent](#TransferEvent)||<a href="FBGeneralAdjustmentCodePISCOFINS_BR.md" target="_blank">Main/FBGeneralAdjustmentCodePISCOFINS_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/FBGeneralAdjustmentCodePISCOFINS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBGeneralAdjustmentCodePISCOFINS_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AdjustmentCode name="AdjustmentCode">AdjustmentCode</a>

First included in: Main/FBGeneralAdjustmentCodePISCOFINS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Identification</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdjustmentCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Identification</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreatePayment name="CreatePayment">CreatePayment</a>

First included in: Main/FBGeneralAdjustmentCodePISCOFINS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreatePayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Main/FBGeneralAdjustmentCodePISCOFINS_BR (this entity)  

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

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Main/FBGeneralAdjustmentCodePISCOFINS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RevenueCode name="RevenueCode">RevenueCode</a>

First included in: Main/FBGeneralAdjustmentCodePISCOFINS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevenueCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxType name="TaxType">TaxType</a>

First included in: Main/FBGeneralAdjustmentCodePISCOFINS_BR (this entity)  

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

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: Main/FBGeneralAdjustmentCodePISCOFINS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: Main/FBGeneralAdjustmentCodePISCOFINS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#IsPovertyFund name="IsPovertyFund">IsPovertyFund</a>

First included in: Main/FBGeneralAdjustmentCodePISCOFINS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>FCP</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPovertyFund attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>FCP</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#AdjustmentType name="AdjustmentType">AdjustmentType</a>

First included in: Main/FBGeneralAdjustmentCodePISCOFINS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdjustmentType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SpedAdjustmentCodePISCOFINS name="SpedAdjustmentCodePISCOFINS">SpedAdjustmentCodePISCOFINS</a>

First included in: Main/FBGeneralAdjustmentCodePISCOFINS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpedAdjustmentCodePISCOFINS attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferEvent name="TransferEvent">TransferEvent</a>

First included in: Main/FBGeneralAdjustmentCodePISCOFINS_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferEvent attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>
