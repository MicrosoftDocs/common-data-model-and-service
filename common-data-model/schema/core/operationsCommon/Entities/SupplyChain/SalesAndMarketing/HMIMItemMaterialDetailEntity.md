---
title: HMIMItemMaterialDetailEntity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Item hazardous material in SalesAndMarketing(HMIMItemMaterialDetailEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/HMIMItemMaterialDetailEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item hazardous material</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ItemId](#ItemId)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[MaterialDescription](#MaterialDescription)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[ShippingPrintText](#ShippingPrintText)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[Qty](#Qty)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[Multiplier](#Multiplier)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[UnitOfMeasure](#UnitOfMeasure)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[PackCode](#PackCode)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[PackCodeDescription](#PackCodeDescription)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[IdentificationCode](#IdentificationCode)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[IdentificationCodeDescription](#IdentificationCodeDescription)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[TechnicalNameCode](#TechnicalNameCode)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[TechnicalNameCodeDescription](#TechnicalNameCodeDescription)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[TunnelCode](#TunnelCode)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[TunnelCodeDescription](#TunnelCodeDescription)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[MarinePollutant](#MarinePollutant)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[EnviroDangerous](#EnviroDangerous)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[LimitedQty](#LimitedQty)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[TransportCategoryCode](#TransportCategoryCode)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[TransportCategoryCodeDescription](#TransportCategoryCodeDescription)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[DivisionCode](#DivisionCode)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[DivisionCodeDescription](#DivisionCodeDescription)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[ClassCode](#ClassCode)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[ClassCodeDescription](#ClassCodeDescription)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[PackingGroupCode](#PackingGroupCode)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[PackingGroupCodeDescription](#PackingGroupCodeDescription)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[RegCode](#RegCode)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[LabelCode](#LabelCode)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[LabelCodeDescription](#LabelCodeDescription)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[NOS](#NOS)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[StowageCode](#StowageCode)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[StowageCodeDescription](#StowageCodeDescription)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[IATAStar](#IATAStar)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[EMSCode](#EMSCode)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[EMSCodeDescription](#EMSCodeDescription)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[AirType](#AirType)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[PackInstCodePassenger](#PackInstCodePassenger)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[PackInstCodePassengerDescription](#PackInstCodePassengerDescription)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[PackInstCodeCargo](#PackInstCodeCargo)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[PackInstCodeCargoDescription](#PackInstCodeCargoDescription)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[BackingTable_HMIMItemMaterialRelationshipId](#BackingTable_HMIMItemMaterialRelationshipId)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="HMIMItemMaterialDetailEntity.md" target="_blank">SalesAndMarketing/HMIMItemMaterialDetailEntity</a>|

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaterialDescription name="MaterialDescription">MaterialDescription</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaterialDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingPrintText name="ShippingPrintText">ShippingPrintText</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingPrintText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Qty name="Qty">Qty</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Qty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Multiplier name="Multiplier">Multiplier</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Multiplier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitOfMeasure name="UnitOfMeasure">UnitOfMeasure</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitOfMeasure attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackCode name="PackCode">PackCode</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackCodeDescription name="PackCodeDescription">PackCodeDescription</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackCodeDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IdentificationCode name="IdentificationCode">IdentificationCode</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IdentificationCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IdentificationCodeDescription name="IdentificationCodeDescription">IdentificationCodeDescription</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IdentificationCodeDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TechnicalNameCode name="TechnicalNameCode">TechnicalNameCode</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TechnicalNameCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TechnicalNameCodeDescription name="TechnicalNameCodeDescription">TechnicalNameCodeDescription</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TechnicalNameCodeDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TunnelCode name="TunnelCode">TunnelCode</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TunnelCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TunnelCodeDescription name="TunnelCodeDescription">TunnelCodeDescription</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TunnelCodeDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MarinePollutant name="MarinePollutant">MarinePollutant</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarinePollutant attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnviroDangerous name="EnviroDangerous">EnviroDangerous</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnviroDangerous attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LimitedQty name="LimitedQty">LimitedQty</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LimitedQty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportCategoryCode name="TransportCategoryCode">TransportCategoryCode</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportCategoryCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportCategoryCodeDescription name="TransportCategoryCodeDescription">TransportCategoryCodeDescription</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportCategoryCodeDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DivisionCode name="DivisionCode">DivisionCode</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DivisionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DivisionCodeDescription name="DivisionCodeDescription">DivisionCodeDescription</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DivisionCodeDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClassCode name="ClassCode">ClassCode</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClassCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClassCodeDescription name="ClassCodeDescription">ClassCodeDescription</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClassCodeDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackingGroupCode name="PackingGroupCode">PackingGroupCode</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackingGroupCodeDescription name="PackingGroupCodeDescription">PackingGroupCodeDescription</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingGroupCodeDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RegCode name="RegCode">RegCode</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LabelCode name="LabelCode">LabelCode</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LabelCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LabelCodeDescription name="LabelCodeDescription">LabelCodeDescription</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LabelCodeDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NOS name="NOS">NOS</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NOS attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StowageCode name="StowageCode">StowageCode</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StowageCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StowageCodeDescription name="StowageCodeDescription">StowageCodeDescription</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StowageCodeDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IATAStar name="IATAStar">IATAStar</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IATAStar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EMSCode name="EMSCode">EMSCode</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EMSCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EMSCodeDescription name="EMSCodeDescription">EMSCodeDescription</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EMSCodeDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AirType name="AirType">AirType</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AirType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackInstCodePassenger name="PackInstCodePassenger">PackInstCodePassenger</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackInstCodePassenger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackInstCodePassengerDescription name="PackInstCodePassengerDescription">PackInstCodePassengerDescription</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackInstCodePassengerDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackInstCodeCargo name="PackInstCodeCargo">PackInstCodeCargo</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackInstCodeCargo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackInstCodeCargoDescription name="PackInstCodeCargoDescription">PackInstCodeCargoDescription</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackInstCodeCargoDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_HMIMItemMaterialRelationshipId name="BackingTable_HMIMItemMaterialRelationshipId">BackingTable_HMIMItemMaterialRelationshipId</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_HMIMItemMaterialRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Worksheet/HMIMItemMaterial.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Worksheet/HMIMItemMaterial.cdm.json/HMIMItemMaterial</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Worksheet/HMIMItemMaterial.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/HMIMItemMaterialDetailEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
